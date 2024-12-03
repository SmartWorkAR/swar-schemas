# Untitled object in SWAR Process Definition Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/0
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [process.schema.json\*](../out/process.schema.json "open original schema") |

## 0 Type

`object` ([Details](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-0.md))

# 0 Properties

| Property          | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                         |
| :---------------- | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)     | Not specified | Required | cannot be null | [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-0-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/0/properties/type")     |
| [title](#title)   | `string`      | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-0-properties-title.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/0/properties/title")   |
| [fields](#fields) | `array`       | Required | cannot be null | [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-0-properties-fields.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/0/properties/fields") |
| [key](#key)       | `string`      | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-0-properties-key.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/0/properties/key")       |

## type



`type`

* is required

* Type: unknown

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-0-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/0/properties/type")

### type Type

unknown

### type Constraints

**constant**: the value of this property must be equal to:

```json
"form"
```

## title



`title`

* is optional

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-0-properties-title.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/0/properties/title")

### title Type

`string`

## fields



`fields`

* is required

* Type: `object[]` ([Details](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-0-properties-fields-items.md))

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-0-properties-fields.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/0/properties/fields")

### fields Type

`object[]` ([Details](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-0-properties-fields-items.md))

## key



`key`

* is optional

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-items-properties-instructions-items-properties-implementation-oneof-0-properties-key.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/items/properties/instructions/items/properties/implementation/oneOf/0/properties/key")

### key Type

`string`
