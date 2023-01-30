---
sidebar_position: 1
---

# Properties

Each blueprint has a `properties` section under its `schema`. In this section, you can define all of the unique properties that describe your asset.

## Use cases

Example use cases for the various property types:

- `string` - for IDs and file names;
- `number` - for Core counts and Memory sizes;
- `boolean` - to denote locked environments;
- etc.

## Structure

```json showLineNumbers
{
  "myStringProp": {
    "title": "My string",
    "icon": "My icon",
    "description": "My string property",
    "type": "string",
    "default": "My default"
  }
}
```

The different components that make up a basic property definition are listed in the following table:

| Field         | Description                                                                                                                                                                        |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `title`       | Property name                                                                                                                                                                      |
| `type`        | **Mandatory field.** The data type of the property.                                                                                                                                |
| `icon`        | Icon for the property <br /><br />See the full icon list.                                                                                                                          |
| `description` | Description of the property.<br /> This value is visible to users when hovering on the info icon in the UI. It provides detailed information about the use of a specific property. |
| `default`     | Default value for this property in case an entity is created without explicitly providing a value.                                                                                 |

## Available properties

import DocCardList from '@theme/DocCardList';

<DocCardList />