# SWAR Process Definition v2

- [1. [Required] Property SWAR Process Definition v2 > processRef](#processRef)
- [2. [Optional] Property SWAR Process Definition v2 > description](#description)
- [3. [Optional] Property SWAR Process Definition v2 > externalIdName](#externalIdName)
- [4. [Required] Property SWAR Process Definition v2 > dataModel](#dataModel)
  - [4.1. Property `SWAR Process Definition v2 > dataModel > allOf > Data Type Reference`](#dataModel_allOf_i0)
    - [4.1.1. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > String Type`](#dataModel_allOf_i0_oneOf_i0)
      - [4.1.1.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > String Type > type](#dataModel_allOf_i0_oneOf_i0_type)
      - [4.1.1.2. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > String Type > nullable](#dataModel_allOf_i0_oneOf_i0_nullable)
      - [4.1.1.3. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > String Type > mask](#dataModel_allOf_i0_oneOf_i0_mask)
      - [4.1.1.4. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > String Type > check](#dataModel_allOf_i0_oneOf_i0_check)
    - [4.1.2. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Number Type`](#dataModel_allOf_i0_oneOf_i1)
      - [4.1.2.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Number Type > type](#dataModel_allOf_i0_oneOf_i1_type)
      - [4.1.2.2. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Number Type > digits](#dataModel_allOf_i0_oneOf_i1_digits)
      - [4.1.2.3. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Number Type > decimals](#dataModel_allOf_i0_oneOf_i1_decimals)
      - [4.1.2.4. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Number Type > nullable](#dataModel_allOf_i0_oneOf_i1_nullable)
      - [4.1.2.5. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Number Type > check](#dataModel_allOf_i0_oneOf_i1_check)
    - [4.1.3. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Boolean Type`](#dataModel_allOf_i0_oneOf_i2)
      - [4.1.3.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Boolean Type > type](#dataModel_allOf_i0_oneOf_i2_type)
      - [4.1.3.2. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Boolean Type > nullable](#dataModel_allOf_i0_oneOf_i2_nullable)
      - [4.1.3.3. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Boolean Type > check](#dataModel_allOf_i0_oneOf_i2_check)
    - [4.1.4. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > DateTime Type`](#dataModel_allOf_i0_oneOf_i3)
      - [4.1.4.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > DateTime Type > type](#dataModel_allOf_i0_oneOf_i3_type)
      - [4.1.4.2. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > DateTime Type > nullable](#dataModel_allOf_i0_oneOf_i3_nullable)
      - [4.1.4.3. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > DateTime Type > check](#dataModel_allOf_i0_oneOf_i3_check)
    - [4.1.5. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Any Type`](#dataModel_allOf_i0_oneOf_i4)
      - [4.1.5.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Any Type > type](#dataModel_allOf_i0_oneOf_i4_type)
      - [4.1.5.2. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Any Type > nullable](#dataModel_allOf_i0_oneOf_i4_nullable)
      - [4.1.5.3. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Any Type > check](#dataModel_allOf_i0_oneOf_i4_check)
    - [4.1.6. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Null Type`](#dataModel_allOf_i0_oneOf_i5)
      - [4.1.6.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Null Type > type](#dataModel_allOf_i0_oneOf_i5_type)
    - [4.1.7. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Array Type`](#dataModel_allOf_i0_oneOf_i6)
      - [4.1.7.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Array Type > type](#dataModel_allOf_i0_oneOf_i6_type)
      - [4.1.7.2. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Array Type > elementType](#dataModel_allOf_i0_oneOf_i6_elementType)
      - [4.1.7.3. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Array Type > nullable](#dataModel_allOf_i0_oneOf_i6_nullable)
    - [4.1.8. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Object Type`](#dataModel_allOf_i0_oneOf_i7)
      - [4.1.8.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Object Type > type](#dataModel_allOf_i0_oneOf_i7_type)
      - [4.1.8.2. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Object Type > nullable](#dataModel_allOf_i0_oneOf_i7_nullable)
      - [4.1.8.3. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Object Type > fields](#dataModel_allOf_i0_oneOf_i7_fields)
        - [4.1.8.3.1. Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Object Type > fields > DataType](#dataModel_allOf_i0_oneOf_i7_fields_additionalProperties)
  - [4.2. Property `SWAR Process Definition v2 > dataModel > allOf > Object Type Constraint`](#dataModel_allOf_i1)
    - [4.2.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > Object Type Constraint > type](#dataModel_allOf_i1_type)
- [5. [Required] Property SWAR Process Definition v2 > activities](#activities)
  - [5.1. SWAR Process Definition v2 > activities > Activity](#autogenerated_heading_2)
    - [5.1.1. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity`](#activities_items_oneOf_i0)
      - [5.1.1.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > type](#activities_items_oneOf_i0_type)
      - [5.1.1.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > id](#activities_items_oneOf_i0_id)
      - [5.1.1.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > name](#activities_items_oneOf_i0_name)
      - [5.1.1.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > description](#activities_items_oneOf_i0_description)
      - [5.1.1.5. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action](#activities_items_oneOf_i0_action)
        - [5.1.1.5.1. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action`](#activities_items_oneOf_i0_action_oneOf_i0)
          - [5.1.1.5.1.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > type](#activities_items_oneOf_i0_action_oneOf_i0_type)
          - [5.1.1.5.1.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition](#activities_items_oneOf_i0_action_oneOf_i0_definition)
            - [5.1.1.5.1.2.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > id](#activities_items_oneOf_i0_action_oneOf_i0_definition_id)
            - [5.1.1.5.1.2.2. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > description](#activities_items_oneOf_i0_action_oneOf_i0_definition_description)
            - [5.1.1.5.1.2.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > elements](#activities_items_oneOf_i0_action_oneOf_i0_definition_elements)
              - [5.1.1.5.1.2.3.1. SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > elements > FormRow](#autogenerated_heading_3)
                - [5.1.1.5.1.2.3.1.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > elements > elements items > elements](#activities_items_oneOf_i0_action_oneOf_i0_definition_elements_items_elements)
                  - [5.1.1.5.1.2.3.1.1.1. SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > elements > elements items > elements > FormElement](#autogenerated_heading_4)
            - [5.1.1.5.1.2.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > parameters](#activities_items_oneOf_i0_action_oneOf_i0_definition_parameters)
              - [5.1.1.5.1.2.4.1. SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > parameters > parameters items](#autogenerated_heading_5)
        - [5.1.1.5.2. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Instruction Action`](#activities_items_oneOf_i0_action_oneOf_i1)
          - [5.1.1.5.2.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Instruction Action > type](#activities_items_oneOf_i0_action_oneOf_i1_type)
          - [5.1.1.5.2.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Instruction Action > instructions](#activities_items_oneOf_i0_action_oneOf_i1_instructions)
        - [5.1.1.5.3. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action`](#activities_items_oneOf_i0_action_oneOf_i2)
          - [5.1.1.5.3.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action > type](#activities_items_oneOf_i0_action_oneOf_i2_type)
          - [5.1.1.5.3.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action > prompt](#activities_items_oneOf_i0_action_oneOf_i2_prompt)
          - [5.1.1.5.3.3. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action > options](#activities_items_oneOf_i0_action_oneOf_i2_options)
            - [5.1.1.5.3.3.1. SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action > options > ChoiceOption](#autogenerated_heading_6)
              - [5.1.1.5.3.3.1.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action > options > options items > key](#activities_items_oneOf_i0_action_oneOf_i2_options_items_key)
              - [5.1.1.5.3.3.1.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action > options > options items > label](#activities_items_oneOf_i0_action_oneOf_i2_options_items_label)
      - [5.1.1.6. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > required](#activities_items_oneOf_i0_required)
      - [5.1.1.7. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > input](#activities_items_oneOf_i0_input)
        - [5.1.1.7.1. SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > input > Mapping](#autogenerated_heading_7)
      - [5.1.1.8. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > output](#activities_items_oneOf_i0_output)
        - [5.1.1.8.1. SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > output > Mapping](#autogenerated_heading_8)
    - [5.1.2. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity`](#activities_items_oneOf_i1)
      - [5.1.2.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity > type](#activities_items_oneOf_i1_type)
      - [5.1.2.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity > id](#activities_items_oneOf_i1_id)
      - [5.1.2.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity > name](#activities_items_oneOf_i1_name)
      - [5.1.2.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity > description](#activities_items_oneOf_i1_description)
      - [5.1.2.5. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity > activities](#activities_items_oneOf_i1_activities)
        - [5.1.2.5.1. SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity > activities > Activity](#autogenerated_heading_9)
    - [5.1.3. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity`](#activities_items_oneOf_i2)
      - [5.1.3.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity > type](#activities_items_oneOf_i2_type)
      - [5.1.3.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity > id](#activities_items_oneOf_i2_id)
      - [5.1.3.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity > name](#activities_items_oneOf_i2_name)
      - [5.1.3.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity > description](#activities_items_oneOf_i2_description)
      - [5.1.3.5. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity > activities](#activities_items_oneOf_i2_activities)
        - [5.1.3.5.1. SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity > activities > Activity](#autogenerated_heading_10)
    - [5.1.4. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity`](#activities_items_oneOf_i3)
      - [5.1.4.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > type](#activities_items_oneOf_i3_type)
      - [5.1.4.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > id](#activities_items_oneOf_i3_id)
      - [5.1.4.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > name](#activities_items_oneOf_i3_name)
      - [5.1.4.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > description](#activities_items_oneOf_i3_description)
      - [5.1.4.5. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > expression](#activities_items_oneOf_i3_expression)
      - [5.1.4.6. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > branches](#activities_items_oneOf_i3_branches)
        - [5.1.4.6.1. Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > branches > Activity](#activities_items_oneOf_i3_branches_additionalProperties)
    - [5.1.5. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity`](#activities_items_oneOf_i4)
      - [5.1.5.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > type](#activities_items_oneOf_i4_type)
      - [5.1.5.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > id](#activities_items_oneOf_i4_id)
      - [5.1.5.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > name](#activities_items_oneOf_i4_name)
      - [5.1.5.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > description](#activities_items_oneOf_i4_description)
      - [5.1.5.5. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > script](#activities_items_oneOf_i4_script)
        - [5.1.5.5.1. SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > script > script items](#autogenerated_heading_11)
      - [5.1.5.6. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > outputKey](#activities_items_oneOf_i4_outputKey)
    - [5.1.6. Property `SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity`](#activities_items_oneOf_i5)
      - [5.1.6.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > type](#activities_items_oneOf_i5_type)
      - [5.1.6.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > id](#activities_items_oneOf_i5_id)
      - [5.1.6.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > name](#activities_items_oneOf_i5_name)
      - [5.1.6.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > description](#activities_items_oneOf_i5_description)
      - [5.1.6.5. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > urlExpression](#activities_items_oneOf_i5_urlExpression)
      - [5.1.6.6. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > method](#activities_items_oneOf_i5_method)
      - [5.1.6.7. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > bodyExpression](#activities_items_oneOf_i5_bodyExpression)
      - [5.1.6.8. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > outputKey](#activities_items_oneOf_i5_outputKey)

**Title:** SWAR Process Definition v2

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** SWAR Version 2.0 process definition

<details>
<summary>
<strong> <a name="processRef"></a>1. [Required] Property SWAR Process Definition v2 > processRef</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

| Restrictions   |   |
| -------------- | - |
| **Min length** | 1 |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="description"></a>2. [Optional] Property SWAR Process Definition v2 > description</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="externalIdName"></a>3. [Optional] Property SWAR Process Definition v2 > externalIdName</strong>  

</summary>
<blockquote>

|              |                  |
| ------------ | ---------------- |
| **Type**     | `string or null` |
| **Required** | No               |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel"></a>4. [Required] Property SWAR Process Definition v2 > dataModel</strong>  

</summary>
<blockquote>

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `combining`      |
| **Required**              | Yes              |
| **Additional properties** | Any type allowed |

<blockquote>

| All of(Requirement)                           |
| --------------------------------------------- |
| [Data Type Reference](#dataModel_allOf_i0)    |
| [Object Type Constraint](#dataModel_allOf_i1) |

<blockquote>

### <a name="dataModel_allOf_i0"></a>4.1. Property `SWAR Process Definition v2 > dataModel > allOf > Data Type Reference`

**Title:** Data Type Reference

|                           |                        |
| ------------------------- | ---------------------- |
| **Type**                  | `combining`            |
| **Required**              | No                     |
| **Additional properties** | Any type allowed       |
| **Defined in**            | #/definitions/DataType |

**Description:** Referencia al tipo de dato definido en DataType. Puede ser cualquiera de los tipos: string, number, boolean, datetime, array, object, etc.

<blockquote>

| One of(Option)                                |
| --------------------------------------------- |
| [String Type](#dataModel_allOf_i0_oneOf_i0)   |
| [Number Type](#dataModel_allOf_i0_oneOf_i1)   |
| [Boolean Type](#dataModel_allOf_i0_oneOf_i2)  |
| [DateTime Type](#dataModel_allOf_i0_oneOf_i3) |
| [Any Type](#dataModel_allOf_i0_oneOf_i4)      |
| [Null Type](#dataModel_allOf_i0_oneOf_i5)     |
| [Array Type](#dataModel_allOf_i0_oneOf_i6)    |
| [Object Type](#dataModel_allOf_i0_oneOf_i7)   |

<blockquote>

#### <a name="dataModel_allOf_i0_oneOf_i0"></a>4.1.1. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > String Type`

**Title:** String Type

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Cadena de texto con opciones de máscara y validación. Ejemplo: nombres, direcciones, códigos.

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i0_type"></a>4.1.1.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > String Type > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"string"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i0_nullable"></a>4.1.1.2. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > String Type > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i0_mask"></a>4.1.1.3. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > String Type > mask</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i0_check"></a>4.1.1.4. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > String Type > check</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

</blockquote>
<blockquote>

#### <a name="dataModel_allOf_i0_oneOf_i1"></a>4.1.2. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Number Type`

**Title:** Number Type

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Campo numérico con control de precisión. Soporta números enteros y decimales con configurable digits y decimals.

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i1_type"></a>4.1.2.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Number Type > type</strong>  

</summary>
<blockquote>

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | Yes                |

Must be one of:
* "number"
* "int"

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i1_digits"></a>4.1.2.2. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Number Type > digits</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `integer` |
| **Required** | No        |

| Restrictions |        |
| ------------ | ------ |
| **Minimum**  | &ge; 0 |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i1_decimals"></a>4.1.2.3. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Number Type > decimals</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `integer` |
| **Required** | No        |

| Restrictions |        |
| ------------ | ------ |
| **Minimum**  | &ge; 0 |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i1_nullable"></a>4.1.2.4. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Number Type > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i1_check"></a>4.1.2.5. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Number Type > check</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

</blockquote>
<blockquote>

#### <a name="dataModel_allOf_i0_oneOf_i2"></a>4.1.3. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Boolean Type`

**Title:** Boolean Type

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Valor booleano true/false. Puede ser nulo.

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i2_type"></a>4.1.3.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Boolean Type > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"boolean"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i2_nullable"></a>4.1.3.2. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Boolean Type > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i2_check"></a>4.1.3.3. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Boolean Type > check</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

</blockquote>
<blockquote>

#### <a name="dataModel_allOf_i0_oneOf_i3"></a>4.1.4. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > DateTime Type`

**Title:** DateTime Type

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Fecha y/o hora. Almacena valores de fecha con formato ISO 8601.

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i3_type"></a>4.1.4.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > DateTime Type > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"datetime"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i3_nullable"></a>4.1.4.2. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > DateTime Type > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i3_check"></a>4.1.4.3. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > DateTime Type > check</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

</blockquote>
<blockquote>

#### <a name="dataModel_allOf_i0_oneOf_i4"></a>4.1.5. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Any Type`

**Title:** Any Type

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Tipo flexible que acepta cualquier valor. Útil para datos dinámicos o campos sin tipo fijo.

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i4_type"></a>4.1.5.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Any Type > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"any"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i4_nullable"></a>4.1.5.2. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Any Type > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i4_check"></a>4.1.5.3. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Any Type > check</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

</blockquote>
<blockquote>

#### <a name="dataModel_allOf_i0_oneOf_i5"></a>4.1.6. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Null Type`

**Title:** Null Type

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Valor nulo explícito. Indica ausencia de valor o campo vacío.

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i5_type"></a>4.1.6.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Null Type > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"null"`

</blockquote>
</details>

</blockquote>
<blockquote>

#### <a name="dataModel_allOf_i0_oneOf_i6"></a>4.1.7. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Array Type`

**Title:** Array Type

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Arreglo de elementos del mismo tipo. Define elementType para especificar el tipo de cada elemento.

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i6_type"></a>4.1.7.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Array Type > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"array"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i6_elementType"></a>4.1.7.2. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Array Type > elementType</strong>  

</summary>
<blockquote>

|                           |                                           |
| ------------------------- | ----------------------------------------- |
| **Type**                  | `combining`                               |
| **Required**              | Yes                                       |
| **Additional properties** | Any type allowed                          |
| **Same definition as**    | [dataModel_allOf_i0](#dataModel_allOf_i0) |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i6_nullable"></a>4.1.7.3. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Array Type > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |

</blockquote>
</details>

</blockquote>
<blockquote>

#### <a name="dataModel_allOf_i0_oneOf_i7"></a>4.1.8. Property `SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Object Type`

**Title:** Object Type

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Objeto con campos definidos. Cada campo tiene su propio DataType permitiendo estructuras anidadas.

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i7_type"></a>4.1.8.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Object Type > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"object"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i7_nullable"></a>4.1.8.2. [Optional] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Object Type > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i7_fields"></a>4.1.8.3. [Required] Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Object Type > fields</strong>  

</summary>
<blockquote>

|                           |                                                                                                                 |
| ------------------------- | --------------------------------------------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                                                        |
| **Required**              | Yes                                                                                                             |
| **Additional properties** | [Each additional property must conform to the schema](#dataModel_allOf_i0_oneOf_i7_fields_additionalProperties) |

<details>
<summary>
<strong> <a name="dataModel_allOf_i0_oneOf_i7_fields_additionalProperties"></a>4.1.8.3.1. Property SWAR Process Definition v2 > dataModel > allOf > item 0 > oneOf > Object Type > fields > DataType</strong>  

</summary>
<blockquote>

|                           |                                           |
| ------------------------- | ----------------------------------------- |
| **Type**                  | `combining`                               |
| **Required**              | No                                        |
| **Additional properties** | Any type allowed                          |
| **Same definition as**    | [dataModel_allOf_i0](#dataModel_allOf_i0) |

</blockquote>
</details>

</blockquote>
</details>

</blockquote>

</blockquote>

</blockquote>
<blockquote>

### <a name="dataModel_allOf_i1"></a>4.2. Property `SWAR Process Definition v2 > dataModel > allOf > Object Type Constraint`

**Title:** Object Type Constraint

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

**Description:** Restricción adicional que requiere que el tipo de dato sea específicamente 'object'. Se usa para definir estructuras con campos.

<details>
<summary>
<strong> <a name="dataModel_allOf_i1_type"></a>4.2.1. [Required] Property SWAR Process Definition v2 > dataModel > allOf > Object Type Constraint > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"object"`

</blockquote>
</details>

</blockquote>

</blockquote>

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities"></a>5. [Required] Property SWAR Process Definition v2 > activities</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `array` |
| **Required** | Yes     |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be | Description |
| ------------------------------- | ----------- |
| [Activity](#activities_items)   | -           |

### <a name="autogenerated_heading_2"></a>5.1. SWAR Process Definition v2 > activities > Activity

|                           |                        |
| ------------------------- | ---------------------- |
| **Type**                  | `combining`            |
| **Required**              | No                     |
| **Additional properties** | Any type allowed       |
| **Defined in**            | #/definitions/Activity |

<blockquote>

| One of(Option)                                  |
| ----------------------------------------------- |
| [Task Activity](#activities_items_oneOf_i0)     |
| [Sequence Activity](#activities_items_oneOf_i1) |
| [Group Activity](#activities_items_oneOf_i2)    |
| [Decision Activity](#activities_items_oneOf_i3) |
| [Script Activity](#activities_items_oneOf_i4)   |
| [HTTP Activity](#activities_items_oneOf_i5)     |

<blockquote>

#### <a name="activities_items_oneOf_i0"></a>5.1.1. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity`

**Title:** Task Activity

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Una tarea atómica que ejecuta una acción específica (formulario, instrucción, o elección). Es la unidad básica de trabajo.

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_type"></a>5.1.1.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"task"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_id"></a>5.1.1.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > id</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

| Restrictions   |   |
| -------------- | - |
| **Min length** | 1 |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_name"></a>5.1.1.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > name</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_description"></a>5.1.1.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > description</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action"></a>5.1.1.5. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action</strong>  

</summary>
<blockquote>

|                           |                          |
| ------------------------- | ------------------------ |
| **Type**                  | `combining`              |
| **Required**              | Yes                      |
| **Additional properties** | Any type allowed         |
| **Defined in**            | #/definitions/TaskAction |

<blockquote>

| One of(Option)                                                   |
| ---------------------------------------------------------------- |
| [Form Action](#activities_items_oneOf_i0_action_oneOf_i0)        |
| [Instruction Action](#activities_items_oneOf_i0_action_oneOf_i1) |
| [Choice Action](#activities_items_oneOf_i0_action_oneOf_i2)      |

<blockquote>

###### <a name="activities_items_oneOf_i0_action_oneOf_i0"></a>5.1.1.5.1. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action`

**Title:** Form Action

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Muestra un formulario al usuario con campos definidos. El usuario completa los datos y se almacenan en el proceso.

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i0_type"></a>5.1.1.5.1.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"form"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i0_definition"></a>5.1.1.5.1.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition</strong>  

</summary>
<blockquote>

|                           |                              |
| ------------------------- | ---------------------------- |
| **Type**                  | `object`                     |
| **Required**              | Yes                          |
| **Additional properties** | Not allowed                  |
| **Defined in**            | #/definitions/FormDefinition |

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i0_definition_id"></a>5.1.1.5.1.2.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > id</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i0_definition_description"></a>5.1.1.5.1.2.2. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > description</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i0_definition_elements"></a>5.1.1.5.1.2.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > elements</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `array` |
| **Required** | No      |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                                                 | Description |
| ------------------------------------------------------------------------------- | ----------- |
| [FormRow](#activities_items_oneOf_i0_action_oneOf_i0_definition_elements_items) | -           |

###### <a name="autogenerated_heading_3"></a>5.1.1.5.1.2.3.1. SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > elements > FormRow

|                           |                       |
| ------------------------- | --------------------- |
| **Type**                  | `object`              |
| **Required**              | No                    |
| **Additional properties** | Not allowed           |
| **Defined in**            | #/definitions/FormRow |

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i0_definition_elements_items_elements"></a>5.1.1.5.1.2.3.1.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > elements > elements items > elements</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `array` |
| **Required** | Yes     |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                                                                    | Description |
| -------------------------------------------------------------------------------------------------- | ----------- |
| [FormElement](#activities_items_oneOf_i0_action_oneOf_i0_definition_elements_items_elements_items) | -           |

###### <a name="autogenerated_heading_4"></a>5.1.1.5.1.2.3.1.1.1. SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > elements > elements items > elements > FormElement

|                           |                           |
| ------------------------- | ------------------------- |
| **Type**                  | `object`                  |
| **Required**              | No                        |
| **Additional properties** | Any type allowed          |
| **Defined in**            | #/definitions/FormElement |

</blockquote>
</details>

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i0_definition_parameters"></a>5.1.1.5.1.2.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > parameters</strong>  

</summary>
<blockquote>

|              |                   |
| ------------ | ----------------- |
| **Type**     | `array of string` |
| **Required** | No                |
| **Default**  | `[]`              |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                                                            | Description |
| ------------------------------------------------------------------------------------------ | ----------- |
| [parameters items](#activities_items_oneOf_i0_action_oneOf_i0_definition_parameters_items) | -           |

###### <a name="autogenerated_heading_5"></a>5.1.1.5.1.2.4.1. SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Form Action > definition > parameters > parameters items

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="activities_items_oneOf_i0_action_oneOf_i1"></a>5.1.1.5.2. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Instruction Action`

**Title:** Instruction Action

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Muestra instrucciones al usuario. No requiere entrada de datos, solo muestra información.

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i1_type"></a>5.1.1.5.2.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Instruction Action > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"instruction"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i1_instructions"></a>5.1.1.5.2.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Instruction Action > instructions</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="activities_items_oneOf_i0_action_oneOf_i2"></a>5.1.1.5.3. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action`

**Title:** Choice Action

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Presenta opciones al usuario para que seleccione una. Cada opción tiene una clave y etiqueta.

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i2_type"></a>5.1.1.5.3.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"choice"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i2_prompt"></a>5.1.1.5.3.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action > prompt</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i2_options"></a>5.1.1.5.3.3. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action > options</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `array` |
| **Required** | Yes     |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                                          | Description |
| ------------------------------------------------------------------------ | ----------- |
| [ChoiceOption](#activities_items_oneOf_i0_action_oneOf_i2_options_items) | -           |

###### <a name="autogenerated_heading_6"></a>5.1.1.5.3.3.1. SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action > options > ChoiceOption

|                           |                            |
| ------------------------- | -------------------------- |
| **Type**                  | `object`                   |
| **Required**              | No                         |
| **Additional properties** | Not allowed                |
| **Defined in**            | #/definitions/ChoiceOption |

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i2_options_items_key"></a>5.1.1.5.3.3.1.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action > options > options items > key</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_action_oneOf_i2_options_items_label"></a>5.1.1.5.3.3.1.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > action > oneOf > Choice Action > options > options items > label</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

</blockquote>
</details>

</blockquote>
</details>

</blockquote>

</blockquote>

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_required"></a>5.1.1.6. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > required</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `true`    |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_input"></a>5.1.1.7. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > input</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `array` |
| **Required** | No      |
| **Default**  | `[]`    |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                   | Description                                                                                                      |
| ------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| [Mapping](#activities_items_oneOf_i0_input_items) | Mapping statement serialized as a string. Either a simple field name or an assignment like 'process.x = task.y'. |

###### <a name="autogenerated_heading_7"></a>5.1.1.7.1. SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > input > Mapping

|                |                       |
| -------------- | --------------------- |
| **Type**       | `string`              |
| **Required**   | No                    |
| **Defined in** | #/definitions/Mapping |

**Description:** Mapping statement serialized as a string. Either a simple field name or an assignment like 'process.x = task.y'.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i0_output"></a>5.1.1.8. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > output</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `array` |
| **Required** | No      |
| **Default**  | `[]`    |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                    | Description                                                                                                      |
| -------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| [Mapping](#activities_items_oneOf_i0_output_items) | Mapping statement serialized as a string. Either a simple field name or an assignment like 'process.x = task.y'. |

###### <a name="autogenerated_heading_8"></a>5.1.1.8.1. SWAR Process Definition v2 > activities > activities items > oneOf > Task Activity > output > Mapping

|                        |                                                                                 |
| ---------------------- | ------------------------------------------------------------------------------- |
| **Type**               | `string`                                                                        |
| **Required**           | No                                                                              |
| **Same definition as** | [activities_items_oneOf_i0_input_items](#activities_items_oneOf_i0_input_items) |

**Description:** Mapping statement serialized as a string. Either a simple field name or an assignment like 'process.x = task.y'.

</blockquote>
</details>

</blockquote>
<blockquote>

#### <a name="activities_items_oneOf_i1"></a>5.1.2. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity`

**Title:** Sequence Activity

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Grupo de actividades que se ejecutan en orden secuencial. Las actividades se procesan una tras otra.

<details>
<summary>
<strong> <a name="activities_items_oneOf_i1_type"></a>5.1.2.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"sequence"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i1_id"></a>5.1.2.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity > id</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

| Restrictions   |   |
| -------------- | - |
| **Min length** | 1 |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i1_name"></a>5.1.2.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity > name</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i1_description"></a>5.1.2.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity > description</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i1_activities"></a>5.1.2.5. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity > activities</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `array` |
| **Required** | Yes     |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                         | Description |
| ------------------------------------------------------- | ----------- |
| [Activity](#activities_items_oneOf_i1_activities_items) | -           |

###### <a name="autogenerated_heading_9"></a>5.1.2.5.1. SWAR Process Definition v2 > activities > activities items > oneOf > Sequence Activity > activities > Activity

|                           |                                       |
| ------------------------- | ------------------------------------- |
| **Type**                  | `combining`                           |
| **Required**              | No                                    |
| **Additional properties** | Any type allowed                      |
| **Same definition as**    | [activities_items](#activities_items) |

</blockquote>
</details>

</blockquote>
<blockquote>

#### <a name="activities_items_oneOf_i2"></a>5.1.3. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity`

**Title:** Group Activity

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Agrupador lógico de actividades. Permite organizar actividades relacionadas sin afectar el flujo de ejecución.

<details>
<summary>
<strong> <a name="activities_items_oneOf_i2_type"></a>5.1.3.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"group"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i2_id"></a>5.1.3.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity > id</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

| Restrictions   |   |
| -------------- | - |
| **Min length** | 1 |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i2_name"></a>5.1.3.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity > name</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i2_description"></a>5.1.3.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity > description</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i2_activities"></a>5.1.3.5. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity > activities</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `array` |
| **Required** | Yes     |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                         | Description |
| ------------------------------------------------------- | ----------- |
| [Activity](#activities_items_oneOf_i2_activities_items) | -           |

###### <a name="autogenerated_heading_10"></a>5.1.3.5.1. SWAR Process Definition v2 > activities > activities items > oneOf > Group Activity > activities > Activity

|                           |                                       |
| ------------------------- | ------------------------------------- |
| **Type**                  | `combining`                           |
| **Required**              | No                                    |
| **Additional properties** | Any type allowed                      |
| **Same definition as**    | [activities_items](#activities_items) |

</blockquote>
</details>

</blockquote>
<blockquote>

#### <a name="activities_items_oneOf_i3"></a>5.1.4. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity`

**Title:** Decision Activity

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Decisión condicional que evalúa una expresión y ejecuta diferentes ramas según el resultado. Soporta múltiples ramas.

<details>
<summary>
<strong> <a name="activities_items_oneOf_i3_type"></a>5.1.4.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"decision"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i3_id"></a>5.1.4.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > id</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

| Restrictions   |   |
| -------------- | - |
| **Min length** | 1 |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i3_name"></a>5.1.4.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > name</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i3_description"></a>5.1.4.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > description</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i3_expression"></a>5.1.4.5. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > expression</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i3_branches"></a>5.1.4.6. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > branches</strong>  

</summary>
<blockquote>

|                           |                                                                                                                 |
| ------------------------- | --------------------------------------------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                                                        |
| **Required**              | Yes                                                                                                             |
| **Additional properties** | [Each additional property must conform to the schema](#activities_items_oneOf_i3_branches_additionalProperties) |

<details>
<summary>
<strong> <a name="activities_items_oneOf_i3_branches_additionalProperties"></a>5.1.4.6.1. Property SWAR Process Definition v2 > activities > activities items > oneOf > Decision Activity > branches > Activity</strong>  

</summary>
<blockquote>

|                           |                                       |
| ------------------------- | ------------------------------------- |
| **Type**                  | `combining`                           |
| **Required**              | No                                    |
| **Additional properties** | Any type allowed                      |
| **Same definition as**    | [activities_items](#activities_items) |

</blockquote>
</details>

</blockquote>
</details>

</blockquote>
<blockquote>

#### <a name="activities_items_oneOf_i4"></a>5.1.5. Property `SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity`

**Title:** Script Activity

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Ejecuta código script. El resultado se almacena en outputKey para ser usado por otras actividades.

<details>
<summary>
<strong> <a name="activities_items_oneOf_i4_type"></a>5.1.5.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"script"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i4_id"></a>5.1.5.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > id</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

| Restrictions   |   |
| -------------- | - |
| **Min length** | 1 |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i4_name"></a>5.1.5.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > name</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i4_description"></a>5.1.5.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > description</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i4_script"></a>5.1.5.5. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > script</strong>  

</summary>
<blockquote>

|              |                   |
| ------------ | ----------------- |
| **Type**     | `array of string` |
| **Required** | Yes               |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                         | Description |
| ------------------------------------------------------- | ----------- |
| [script items](#activities_items_oneOf_i4_script_items) | -           |

###### <a name="autogenerated_heading_11"></a>5.1.5.5.1. SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > script > script items

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i4_outputKey"></a>5.1.5.6. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > Script Activity > outputKey</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

</blockquote>
</details>

</blockquote>
<blockquote>

#### <a name="activities_items_oneOf_i5"></a>5.1.6. Property `SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity`

**Title:** HTTP Activity

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** Llama a un endpoint HTTP. Soporta GET, POST, PUT, DELETE y otros métodos. El resultado se guarda en outputKey.

<details>
<summary>
<strong> <a name="activities_items_oneOf_i5_type"></a>5.1.6.1. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"http"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i5_id"></a>5.1.6.2. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > id</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

| Restrictions   |   |
| -------------- | - |
| **Min length** | 1 |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i5_name"></a>5.1.6.3. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > name</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i5_description"></a>5.1.6.4. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > description</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i5_urlExpression"></a>5.1.6.5. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > urlExpression</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i5_method"></a>5.1.6.6. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > method</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i5_bodyExpression"></a>5.1.6.7. [Optional] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > bodyExpression</strong>  

</summary>
<blockquote>

|              |                  |
| ------------ | ---------------- |
| **Type**     | `string or null` |
| **Required** | No               |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="activities_items_oneOf_i5_outputKey"></a>5.1.6.8. [Required] Property SWAR Process Definition v2 > activities > activities items > oneOf > HTTP Activity > outputKey</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

</blockquote>
</details>

</blockquote>

</blockquote>

</blockquote>
</details>

----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans) on 2026-05-04 at 15:30:34 +0000