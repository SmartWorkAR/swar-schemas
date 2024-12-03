# Untitled object in SWAR Process Definition Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/1
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [process.schema.json\*](../out/process.schema.json "open original schema") |

## 1 Type

`object` ([Details](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-1.md))

# 1 Properties

| Property                | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                               |
| :---------------------- | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)           | Not specified | Required | cannot be null | [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-1-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/1/properties/type")           |
| [message](#message)     | `string`      | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-1-properties-message.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/1/properties/message")     |
| [questions](#questions) | `array`       | Required | cannot be null | [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-1-properties-questions.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/1/properties/questions") |

## type



`type`

* is required

* Type: unknown

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-1-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/1/properties/type")

### type Type

unknown

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

* defined in: [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-1-properties-message.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/1/properties/message")

### message Type

`string`

## questions



`questions`

* is required

* Type: `object[]` ([Details](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-1-properties-questions-items.md))

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-1-properties-questions.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/1/properties/questions")

### questions Type

`object[]` ([Details](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-1-properties-questions-items.md))
