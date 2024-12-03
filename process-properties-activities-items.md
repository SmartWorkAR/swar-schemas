# Untitled object in SWAR Process Definition Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [process.schema.json\*](../out/process.schema.json "open original schema") |

## items Type

`object` ([Details](process-properties-activities-items.md))

# items Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                     |
| :---------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                     | `string` | Required | cannot be null | [SWAR Process Definition](process-properties-activities-items-properties-id.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/id")                     |
| [description](#description)   | `string` | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-items-properties-description.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/description")   |
| [instructions](#instructions) | `array`  | Required | cannot be null | [SWAR Process Definition](process-properties-activities-items-properties-instructions.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions") |

## id



`id`

* is required

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-items-properties-id.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/id")

### id Type

`string`

## description



`description`

* is optional

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-items-properties-description.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/description")

### description Type

`string`

## instructions



`instructions`

* is required

* Type: `object[]` ([Details](process-properties-activities-items-properties-instructions-items.md))

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-items-properties-instructions.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions")

### instructions Type

`object[]` ([Details](process-properties-activities-items-properties-instructions-items.md))
