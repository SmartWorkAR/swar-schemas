# Untitled object in SWAR Process Definition Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^[A-Za-z0-9_]+$/properties/instructions/patternProperties/^[A-Za-z0-9_]+$/properties/implementation/oneOf/9
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [process.schema.json\*](../out/process.schema.json "open original schema") |

## 9 Type

`object` ([Details](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-9.md))

# 9 Properties

| Property                    | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| :-------------------------- | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)               | Not specified | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-9-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/9/properties/type")               |
| [labels](#labels)           | `array`       | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-9-properties-labels.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/9/properties/labels")           |
| [photoLabels](#photolabels) | `array`       | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-9-properties-photolabels.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/9/properties/photoLabels") |
| [validRange](#validrange)   | `array`       | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-9-properties-validrange.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/9/properties/validRange")   |
| [tolerancia](#tolerancia)   | `integer`     | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-9-properties-tolerancia.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/9/properties/tolerancia")   |

## type



`type`

* is optional

* Type: unknown

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-9-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/9/properties/type")

### type Type

unknown

### type Constraints

**constant**: the value of this property must be equal to:

```json
"tripleInputPhoto"
```

## labels



`labels`

* is optional

* Type: `string[]`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-9-properties-labels.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/9/properties/labels")

### labels Type

`string[]`

### labels Constraints

**minimum number of items**: the minimum number of items for this array is: `3`

## photoLabels



`photoLabels`

* is optional

* Type: `string[]`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-9-properties-photolabels.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/9/properties/photoLabels")

### photoLabels Type

`string[]`

### photoLabels Constraints

**minimum number of items**: the minimum number of items for this array is: `3`

## validRange



`validRange`

* is optional

* Type: `number[]`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-9-properties-validrange.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/9/properties/validRange")

### validRange Type

`number[]`

### validRange Constraints

**minimum number of items**: the minimum number of items for this array is: `2`

## tolerancia



`tolerancia`

* is optional

* Type: `integer`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-9-properties-tolerancia.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/9/properties/tolerancia")

### tolerancia Type

`integer`
