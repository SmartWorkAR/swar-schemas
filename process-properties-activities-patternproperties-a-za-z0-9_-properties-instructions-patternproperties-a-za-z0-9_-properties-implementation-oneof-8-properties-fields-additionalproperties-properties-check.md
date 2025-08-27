# Untitled string in SWAR Process Definition Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/activities/patternProperties/^[A-Za-z0-9_]+$/properties/instructions/patternProperties/^[A-Za-z0-9_]+$/properties/implementation/oneOf/8/properties/fields/additionalProperties/properties/check
```



| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [process.schema.json\*](../out/process.schema.json "open original schema") |

## check Type

`string`

## check Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^(validar(String|Fecha|InNumero|OutNumero|FechaUI)|VerificarMismoValor)\(.+\)[ ;]*$
```

[try pattern](https://regexr.com/?expression=%5E\(validar\(String%7CFecha%7CInNumero%7COutNumero%7CFechaUI\)%7CVerificarMismoValor\)%5C\(.%2B%5C\)%5B%20%3B%5D*%24 "try regular expression with regexr.com")
