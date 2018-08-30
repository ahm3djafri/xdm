
# Segment Identity Schema

```
https://ns.adobe.com/xdm/context/segmentidentity
```

SegmentIdentity is used to clearly distinguish segments from multiple sources. SegmentIdentity is established by an segment identity provider, which itself is referenced in the `namespace` attribute. Within each `namespace`, the segmentidentity is unique.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | Yes | Experimental | Yes | Forbidden | Permitted | [context/segmentidentity.schema.json](context/segmentidentity.schema.json) |
## Schema Hierarchy

* Segment Identity `https://ns.adobe.com/xdm/context/segmentidentity`
  * [Namespace](namespace.schema.md) `https://ns.adobe.com/xdm/context/namespace`


## Segment Identity Example
```json
{
  "@id": "https://data.adobe.io/entities/segmentIdentity/id123",
  "xdm:namespace": {
    "xdm:code": "AA12345"
  }
}
```

# Segment Identity Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [@id](#id) | `string` | Optional | Segment Identity (this schema) |
| [xdm:namespace](#xdmnamespace) | Namespace | Optional | Segment Identity (this schema) |
| [xdm:xid](#xdmxid) | `string` | Optional | Segment Identity (this schema) |
| `*` | any | Additional | this schema *allows* additional properties |

## @id
### Identifier

Identity of the Segment in the related namespace.

`@id`
* is optional
* type: `string`
* defined in this schema

### @id Type


`string`
* format: `uri` – Uniformous Resource Identifier (according to [RFC3986](http://tools.ietf.org/html/rfc3986))






## xdm:namespace
### Namespace

The namespace associated with the `xid` attribute.

`xdm:namespace`
* is optional
* type: Namespace
* defined in this schema

### xdm:namespace Type


* [Namespace](namespace.schema.md) – `https://ns.adobe.com/xdm/context/namespace`





## xdm:xid
### Experience Identifier

When present, this value represents a cross-namespace identifier that is unique across all namespace-scoped identifiers in all namespaces.

`xdm:xid`
* is optional
* type: `string`
* defined in this schema

### xdm:xid Type


`string`





