# Untitled object in SWAR Process Definition Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^[A-Za-z0-9_]+$/properties/instructions/patternProperties/^[A-Za-z0-9_]+$/properties/implementation/oneOf/5/properties/expressions
```

Expresiones de lógica para validar campos, habilitarlos o hacerlos visibles. El sufijo \_valid, \_enabled o \_visible indica la regla a aplicar.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [process.schema.json\*](../out/process.schema.json "open original schema") |

## expressions Type

`object` ([Details](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-expressions.md))

# expressions Properties

| Property                                             | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| :--------------------------------------------------- | :------ | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `^[a-zA-Z_][a-zA-Z0-9_]*_(valid\|enabled\|visible)$` | `array` | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-expressions-patternproperties-a-za-z_a-za-z0-9__validenabledvisible.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/5/properties/expressions/patternProperties/^\[a-zA-Z_]\[a-zA-Z0-9_]*_(valid\|enabled\|visible)$") |

## Pattern: `^[a-zA-Z_][a-zA-Z0-9_]*_(valid|enabled|visible)$`



`^[a-zA-Z_][a-zA-Z0-9_]*_(valid|enabled|visible)$`

* is optional

* Type: `string[]`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-patternproperties-a-za-z0-9_-properties-instructions-patternproperties-a-za-z0-9_-properties-implementation-oneof-5-properties-expressions-patternproperties-a-za-z_a-za-z0-9__validenabledvisible.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^\[A-Za-z0-9_]+$/properties/instructions/patternProperties/^\[A-Za-z0-9_]+$/properties/implementation/oneOf/5/properties/expressions/patternProperties/^\[a-zA-Z_]\[a-zA-Z0-9_]*_(valid|enabled|visible)$")

### ^\[a-zA-Z\_]\[a-zA-Z0-9\_]\*\_(valid|enabled|visible)$ Type

`string[]`
