# Untitled object in SWAR Process Definition Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^[A-Za-z0-9_]+$/properties/instructions/patternProperties/^[A-Za-z0-9_]+$/properties/implementation/oneOf/4
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [process.schema.json\*](../out/process.schema.json "open original schema") |

## 4 Type

`object` ([Details](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-4.md))

# 4 Properties

| Property                          | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| :-------------------------------- | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)                     | Not specified | Required | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-4-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/4/properties/type")                     |
| [description](#description)       | `string`      | Required | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-4-properties-description.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/4/properties/description")       |
| [labels](#labels)                 | `array`       | Required | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-4-properties-labels.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/4/properties/labels")                 |
| [referenceValue](#referencevalue) | `string`      | Required | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-4-properties-referencevalue.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/4/properties/referenceValue") |
| [tolerance](#tolerance)           | `number`      | Required | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-4-properties-tolerance.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/4/properties/tolerance")           |

## type



`type`

* is required

* Type: unknown

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-4-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/4/properties/type")

### type Type

unknown

### type Constraints

**constant**: the value of this property must be equal to:

```json
"doubleInput"
```

## description



`description`

* is required

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-4-properties-description.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/4/properties/description")

### description Type

`string`

## labels



`labels`

* is required

* Type: `string[]`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-4-properties-labels.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/4/properties/labels")

### labels Type

`string[]`

### labels Constraints

**minimum number of items**: the minimum number of items for this array is: `2`

## referenceValue



`referenceValue`

* is required

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-4-properties-referencevalue.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/4/properties/referenceValue")

### referenceValue Type

`string`

## tolerance



`tolerance`

* is required

* Type: `number`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-4-properties-tolerance.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/4/properties/tolerance")

### tolerance Type

`number`
