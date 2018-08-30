
# Episode Schema

```
http://www.iptc.org/season
```

The season the show belongs to. Based on [www.iptc.org](https://www.iptc.org/std/videometadatahub/recommendation/pre-versions/IPTC-VideoMetadataHub-props-Rec_1.1.html)

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | Yes | Experimental | No | Forbidden | Permitted | [external/iptc/episode.schema.json](external/iptc/episode.schema.json) |

## Episode Example
```json
{
  "iptc4xmpExt:Number": 1
}
```

# Episode Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [iptc4xmpExt:Identifier](#iptc4xmpextidentifier) | `string` | Optional | Episode (this schema) |
| [iptc4xmpExt:Name](#iptc4xmpextname) | `string` | Optional | Episode (this schema) |
| [iptc4xmpExt:Number](#iptc4xmpextnumber) | `number` | Optional | Episode (this schema) |
| `*` | any | Additional | this schema *allows* additional properties |

## iptc4xmpExt:Identifier
### Episode Identifier

Identifier of the episode.

`iptc4xmpExt:Identifier`
* is optional
* type: `string`
* defined in this schema

### iptc4xmpExt:Identifier Type


`string`
* format: `uri` – Uniformous Resource Identifier (according to [RFC3986](http://tools.ietf.org/html/rfc3986))






## iptc4xmpExt:Name
### Episode Name

Name of the episode.

`iptc4xmpExt:Name`
* is optional
* type: `string`
* defined in this schema

### iptc4xmpExt:Name Type


`string`






## iptc4xmpExt:Number
### Episode Number

Number of the episode.

`iptc4xmpExt:Number`
* is optional
* type: `number`
* defined in this schema

### iptc4xmpExt:Number Type


`number`





