
# Organizational Unit Schema

```
https://ns.adobe.com/xdm/common/orgunit
```

The organizaational unit of a parent organization.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | Yes | Experimental | Yes | Forbidden | Permitted | [common/orgunit.schema.json](common/orgunit.schema.json) |

## Organizational Unit Example
```json
{
  "@id": "https://data.adobe.io/org-apparals-men",
  "xdm:label": "Men Apparals"
}
```

# Organizational Unit Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [@id](#id) | `string` | Optional | Organizational Unit (this schema) |
| [xdm:label](#xdmlabel) | `string` | Optional | Organizational Unit (this schema) |
| `*` | any | Additional | this schema *allows* additional properties |

## @id
### Identifier

The ID associated with this organizational unit.

`@id`
* is optional
* type: `string`
* defined in this schema

### @id Type


`string`
* format: `uri` – Uniformous Resource Identifier (according to [RFC3986](http://tools.ietf.org/html/rfc3986))






## xdm:label
### Label of the organizational unit.

The user-friendly name for the organizational unit.

`xdm:label`
* is optional
* type: `string`
* defined in this schema

### xdm:label Type


`string`





