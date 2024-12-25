# Untitled object in SWAR Process Definition Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities
```

The activities of the process. Entries with the format: {activity1: { Data for the activity}, ...}

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [process.schema.json\*](../out/process.schema.json "open original schema") |

## activities Type

`object` ([Details](process-properties-activities.md))

# activities Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                   |
| :-------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Additional Properties | `object` | Optional | cannot be null | [SWAR Process Definition](process-properties-activities-additionalproperties.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties") |

## Additional Properties

Additional properties are allowed, as long as they follow this schema:



* is optional

* Type: `object` ([Details](process-properties-activities-additionalproperties.md))

* cannot be null

* defined in: [SWAR Process Definition](process-properties-activities-additionalproperties.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.1/process.schema.json#/properties/activities/additionalProperties")

### additionalProperties Type

`object` ([Details](process-properties-activities-additionalproperties.md))
