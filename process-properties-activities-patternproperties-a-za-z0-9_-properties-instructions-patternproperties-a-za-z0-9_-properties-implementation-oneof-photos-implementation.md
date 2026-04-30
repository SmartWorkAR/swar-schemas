# Photos Implementation Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^[A-Za-z0-9_]+$/properties/instructions/patternProperties/^[A-Za-z0-9_]+$/properties/implementation/oneOf/1
```

Captura de fotos. Define los nombres de los campos de foto.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [process.schema.json\*](../out/process.schema.json "open original schema") |

## 1 Type

`object` ([Photos Implementation](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-photos-implementation.md))

# 1 Properties

| Property          | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| :---------------- | :------------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)     | Not specified | Required | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-photos-implementation-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/1/properties/type")     |
| [photos](#photos) | `object`      | Required | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-photos-implementation-properties-photos.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/1/properties/photos") |

## type



`type`

* is required

* Type: unknown

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-photos-implementation-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/1/properties/type")

### type Type

unknown

### type Constraints

**constant**: the value of this property must be equal to:

```json
"photos"
```

## photos



`photos`

* is required

* Type: `object` ([Details](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-photos-implementation-properties-photos.md))

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-photos-implementation-properties-photos.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/1/properties/photos")

### photos Type

`object` ([Details](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-photos-implementation-properties-photos.md))
