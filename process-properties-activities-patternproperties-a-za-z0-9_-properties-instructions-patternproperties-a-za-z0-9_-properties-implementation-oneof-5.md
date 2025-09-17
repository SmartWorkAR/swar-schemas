# Untitled object in SWAR Process Definition Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^[A-Za-z0-9_]+$/properties/instructions/patternProperties/^[A-Za-z0-9_]+$/properties/implementation/oneOf/5
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [process.schema.json\*](../out/process.schema.json "open original schema") |

## 5 Type

`object` ([Details](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5.md))

# 5 Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| :-------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)               | `string` | Required | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/5/properties/type")               |
| [title](#title)             | `string` | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-title.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/5/properties/title")             |
| [fields](#fields)           | `object` | Required | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-fields.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/5/properties/fields")           |
| [expressions](#expressions) | `object` | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-expressions.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/5/properties/expressions") |

## type



`type`

* is required

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-type.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/5/properties/type")

### type Type

`string`

### type Constraints

**constant**: the value of this property must be equal to:

```json
"form2"
```

## title



`title`

* is optional

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-title.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/5/properties/title")

### title Type

`string`

## fields



`fields`

* is required

* Type: `object` ([Details](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-fields.md))

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-fields.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/5/properties/fields")

### fields Type

`object` ([Details](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-fields.md))

## expressions

Expresiones de lógica para validar campos, habilitarlos o hacerlos visibles. El sufijo \_valid, \_enabled o \_visible indica la regla a aplicar.

`expressions`

* is optional

* Type: `object` ([Details](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-expressions.md))

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-expressions.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/5/properties/expressions")

### expressions Type

`object` ([Details](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-expressions.md))
