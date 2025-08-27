# Untitled object in SWAR Process Definition Schema

```txt
https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/options
```

Additional ad hoc properties.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [process.schema.json\*](../out/process.schema.json "open original schema") |

## options Type

`object` ([Details](process-properties-options.md))

# options Properties

| Property                                           | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                     |
| :------------------------------------------------- | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [showQr](#showqr)                                  | `boolean` | Optional | cannot be null | [SWAR Process Definition](process-properties-options-properties-showqr.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/options/properties/showQr")                               |
| [canEditOnFinish](#caneditonfinish)                | `boolean` | Optional | cannot be null | [SWAR Process Definition](process-properties-options-properties-caneditonfinish.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/options/properties/canEditOnFinish")             |
| [canUploadBeforeFinish](#canuploadbeforefinish)    | `boolean` | Optional | cannot be null | [SWAR Process Definition](process-properties-options-properties-canuploadbeforefinish.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/options/properties/canUploadBeforeFinish") |
| [mission\_can\_be\_shared](#mission_can_be_shared) | `boolean` | Optional | cannot be null | [SWAR Process Definition](process-properties-options-properties-mission_can_be_shared.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/options/properties/mission_can_be_shared") |
| [canCreateOnDevice](#cancreateondevice)            | `boolean` | Optional | cannot be null | [SWAR Process Definition](process-properties-options-properties-cancreateondevice.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/options/properties/canCreateOnDevice")         |

## showQr

The mission can be initiated from a device using a QR code.

`showQr`

* is optional

* Type: `boolean`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-options-properties-showqr.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/options/properties/showQr")

### showQr Type

`boolean`

## canEditOnFinish

After completing a mission, it can be modified.

`canEditOnFinish`

* is optional

* Type: `boolean`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-options-properties-caneditonfinish.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/options/properties/canEditOnFinish")

### canEditOnFinish Type

`boolean`

## canUploadBeforeFinish

The mission can be partially uploaded to the server.

`canUploadBeforeFinish`

* is optional

* Type: `boolean`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-options-properties-canuploadbeforefinish.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/options/properties/canUploadBeforeFinish")

### canUploadBeforeFinish Type

`boolean`

## mission\_can\_be\_shared

If a mission was created locally, it can be shared between users of the same category.

`mission_can_be_shared`

* is optional

* Type: `boolean`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-options-properties-mission_can_be_shared.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/options/properties/mission_can_be_shared")

### mission\_can\_be\_shared Type

`boolean`

## canCreateOnDevice

The mission can be created from the device. Default true.

`canCreateOnDevice`

* is optional

* Type: `boolean`

* cannot be null

* defined in: [SWAR Process Definition](process-properties-options-properties-cancreateondevice.md "https://smartworkar.github.io/swar-schemas/schemas/v1.2.3/process.schema.json#/properties/options/properties/canCreateOnDevice")

### canCreateOnDevice Type

`boolean`
