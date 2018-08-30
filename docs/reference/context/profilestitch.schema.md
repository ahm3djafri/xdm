
# Profile Stitch Schema

```
https://ns.adobe.com/xdm/context/profileStitch
```

Details about the ids that were joined by profile stitching.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | Yes | Experimental | No | Forbidden | Permitted | [context/profilestitch.schema.json](context/profilestitch.schema.json) |
## Schema Hierarchy

* Profile Stitch `https://ns.adobe.com/xdm/context/profileStitch`
  * [Identity](profilestitchidentity.schema.md) `https://ns.adobe.com/xdm/context/profileStitchIdentity`
  * [End User IDs](enduserids.schema.md) `https://ns.adobe.com/xdm/context/enduserids`


## Profile Stitch Example
```json
{
  "xdm:profileStitchID": {
    "@id": "https://data.adobe.io/entities/profileStitchIdentity/1",
    "xdm:namespace": {
      "xdm:code": "AAM"
    }
  },
  "xdm:version": "1.0",
  "xdm:endUserIds": {
    "https://ns.adobe.com/experience/mcid": {
      "xdm:id": "https://data.adobe.io/entities/identity/92312748749128",
      "additionalIDs": [
        "https://data.adobe.io/entities/identity/62312748749321",
        "https://data.adobe.io/entities/identity/49312748749132"
      ],
      "xdm:namespace": {
        "xdm:code": "ECID"
      }
    }
  }
}
```

# Profile Stitch Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [xdm:endUserIDs](#xdmenduserids) | End User IDs | Optional | Profile Stitch (this schema) |
| [xdm:profileStitchID](#xdmprofilestitchid) | Identity | Optional | Profile Stitch (this schema) |
| [xdm:version](#xdmversion) | `string` | Optional | Profile Stitch (this schema) |
| `*` | any | Additional | this schema *allows* additional properties |

## xdm:endUserIDs
### End User IDs

Condensed, normalized encapsulation of all end user identifiers.

`xdm:endUserIDs`
* is optional
* type: End User IDs
* defined in this schema

### xdm:endUserIDs Type


* [End User IDs](enduserids.schema.md) – `https://ns.adobe.com/xdm/context/enduserids`





## xdm:profileStitchID
### Profile Stitch ID

The identity of the segment or snapshot definition in with the domain of the specific system that processes that type of segment.

`xdm:profileStitchID`
* is optional
* type: Identity
* defined in this schema

### xdm:profileStitchID Type


* [Identity](profilestitchidentity.schema.md) – `https://ns.adobe.com/xdm/context/profileStitchIdentity`





## xdm:version
### Version

The version of the profile stitch definition used. Useful for debugging.

`xdm:version`
* is optional
* type: `string`
* defined in this schema

### xdm:version Type


`string`





