# Untitled object in SWAR Process Definition Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [process.schema.json\*](../out/process.schema.json "open original schema") |

## additionalProperties Type

`object` ([Details](process-properties-activities-additionalproperties.md))

# additionalProperties Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                   |
| :---------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [description](#description)   | `string` | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-additionalproperties-properties-description.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties/properties/description")   |
| [instructions](#instructions) | `object` | Required | cannot be null | [SWAR Process Definition](process-properties-activities-additionalproperties-properties-instructions.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties/properties/instructions") |

## description

A Description for the activity

`description`

* is optional

* Type: `string`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-additionalproperties-properties-description.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties/properties/description")

### description Type

`string`

## instructions

In SWAR 1.x an activity is defined by a map of instructions {id: instruction data}

`instructions`

* is required

* Type: `object` ([Details](process-properties-activities-additionalproperties-properties-instructions.md))

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-additionalproperties-properties-instructions.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties/properties/instructions")

### instructions Type

`object` ([Details](process-properties-activities-additionalproperties-properties-instructions.md))
