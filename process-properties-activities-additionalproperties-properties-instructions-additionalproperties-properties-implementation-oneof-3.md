# Untitled object in SWAR Process Definition Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties/properties/instructions/additionalProperties/properties/implementation/oneOf/3
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [process.schema.json\*](../out/process.schema.json "open original schema") |

## 3 Type

`object` ([Details](process-properties-activities-additionalproperties-properties-instructions-additionalproperties-properties-implementation-oneof-3.md))

# 3 Properties

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                           |
| :---------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)           | `string` | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-additionalproperties-properties-instructions-additionalproperties-properties-implementation-oneof-3-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties/properties/instructions/additionalProperties/properties/implementation/oneOf/3/properties/type")           |
| [message](#message)     | `string` | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-additionalproperties-properties-instructions-additionalproperties-properties-implementation-oneof-3-properties-message.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties/properties/instructions/additionalProperties/properties/implementation/oneOf/3/properties/message")     |
| [questions](#questions) | `array`  | Required | cannot be null | [SWAR Process Definition](process-properties-activities-additionalproperties-properties-instructions-additionalproperties-properties-implementation-oneof-3-properties-questions.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties/properties/instructions/additionalProperties/properties/implementation/oneOf/3/properties/questions") |

## type



`type`

* is optional

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-additionalproperties-properties-instructions-additionalproperties-properties-implementation-oneof-3-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties/properties/instructions/additionalProperties/properties/implementation/oneOf/3/properties/type")

### type Type

`string`

### type Constraints

**constant**: the value of this property must be equal to:

```json
"multipleChoice"
```

## message



`message`

* is optional

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-additionalproperties-properties-instructions-additionalproperties-properties-implementation-oneof-3-properties-message.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties/properties/instructions/additionalProperties/properties/implementation/oneOf/3/properties/message")

### message Type

`string`

## questions



`questions`

* is required

* Type: `object[]` ([Details](process-properties-activities-additionalproperties-properties-instructions-additionalproperties-properties-implementation-oneof-3-properties-questions-items.md))

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-additionalproperties-properties-instructions-additionalproperties-properties-implementation-oneof-3-properties-questions.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties/properties/instructions/additionalProperties/properties/implementation/oneOf/3/properties/questions")

### questions Type

`object[]` ([Details](process-properties-activities-additionalproperties-properties-instructions-additionalproperties-properties-implementation-oneof-3-properties-questions-items.md))
