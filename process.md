# SWAR Process Definition Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json
```

SWAR Version 1.2 process definition

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                               |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [process.schema.json](../out/process.schema.json "open original schema") |

## SWAR Process Definition Type

`object` ([SWAR Process Definition](process.md))

# SWAR Process Definition Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                           |
| :-------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)               | `string` | Required | cannot be null | [SWAR Process Definition](process-properties-name.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/name")               |
| [description](#description) | `string` | Optional | cannot be null | [SWAR Process Definition](process-properties-description.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/description") |
| [title](#title)             | `string` | Optional | cannot be null | [SWAR Process Definition](process-properties-title.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/title")             |
| [roles](#roles)             | `array`  | Optional | cannot be null | [SWAR Process Definition](process-properties-roles.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/roles")             |
| [primaryKey](#primarykey)   | `array`  | Optional | cannot be null | [SWAR Process Definition](process-properties-primarykey.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/primaryKey")   |
| [options](#options)         | `object` | Optional | cannot be null | [SWAR Process Definition](process-properties-options.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/options")         |
| [activities](#activities)   | `array`  | Required | cannot be null | [SWAR Process Definition](process-properties-activities.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities")   |

## name

The name of the process (a short description)

`name`

* is required

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-name.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/name")

### name Type

`string`

## description

A detailed description of the process

`description`

* is optional

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-description.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/description")

### description Type

`string`

## title

A one line description of the process (subject)

`title`

* is optional

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-title.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/title")

### title Type

`string`

## roles



`roles`

* is optional

* Type: `string[]`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-roles.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/roles")

### roles Type

`string[]`

## primaryKey

Define with input parameter fields are considered a primary key of a process instance.

`primaryKey`

* is optional

* Type: `string[]`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-primarykey.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/primaryKey")

### primaryKey Type

`string[]`

## options

Additional ad hoc properties

`options`

* is optional

* Type: `object` ([Details](process-properties-options.md))

* cannot be null

* defined in: [SWAR Process Definition](process-properties-options.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/options")

### options Type

`object` ([Details](process-properties-options.md))

## activities

The activities of the process

`activities`

* is required

* Type: `object[]` ([Details](process-properties-activities-items.md))

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities")

### activities Type

`object[]` ([Details](process-properties-activities-items.md))
