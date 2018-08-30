
# Creator Schema

```
http://www.iptc.org/creator
```

The creator of the show. Based on [www.iptc.org](https://www.iptc.org/std/videometadatahub/recommendation/pre-versions/IPTC-VideoMetadataHub-props-Rec_1.1.html)

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | Yes | Experimental | No | Forbidden | Permitted | [external/iptc/creator.schema.json](external/iptc/creator.schema.json) |

## Creator Example
```json
{
  "iptc4xmpExt:Name": "nba_highlights",
  "iptc4xmpExt:Identifier": "http://espn.com/series-identifiers/2613953"
}
```

# Creator Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [iptc4xmpExt:Name](#iptc4xmpextname) | `string` | Optional | Creator (this schema) |
| `*` | any | Additional | this schema *allows* additional properties |

## iptc4xmpExt:Name
### Creator Name

Full name of the Creator.

`iptc4xmpExt:Name`
* is optional
* type: `string`
* defined in this schema

### iptc4xmpExt:Name Type


`string`





