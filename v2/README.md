# SWAR Process Definition v2

- [1. [Required] Property SWAR Process Definition v2 > reference](#reference)
- [2. [Required] Property SWAR Process Definition v2 > description](#description)
- [3. [Required] Property SWAR Process Definition v2 > fullDescription](#fullDescription)
- [4. [Optional] Property SWAR Process Definition v2 > executionRefName](#executionRefName)
- [5. [Optional] Property SWAR Process Definition v2 > executionRefMask](#executionRefMask)
- [6. [Required] Property SWAR Process Definition v2 > version](#version)
- [7. [Required] Property SWAR Process Definition v2 > definition](#definition)
  - [7.1. [Required] Property SWAR Process Definition v2 > definition > processRef](#definition_processRef)
  - [7.2. [Optional] Property SWAR Process Definition v2 > definition > description](#definition_description)
  - [7.3. [Optional] Property SWAR Process Definition v2 > definition > externalIdName](#definition_externalIdName)
  - [7.4. [Required] Property SWAR Process Definition v2 > definition > dataModel](#definition_dataModel)
    - [7.4.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields](#definition_dataModel_fields)
      - [7.4.1.1. Property SWAR Process Definition v2 > definition > dataModel > fields > DataType](#definition_dataModel_fields_additionalProperties)
        - [7.4.1.1.1. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > StringType`](#definition_dataModel_fields_additionalProperties_oneOf_i0)
          - [7.4.1.1.1.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 0 > type](#definition_dataModel_fields_additionalProperties_oneOf_i0_type)
          - [7.4.1.1.1.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 0 > nullable](#definition_dataModel_fields_additionalProperties_oneOf_i0_nullable)
          - [7.4.1.1.1.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 0 > mask](#definition_dataModel_fields_additionalProperties_oneOf_i0_mask)
          - [7.4.1.1.1.4. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 0 > check](#definition_dataModel_fields_additionalProperties_oneOf_i0_check)
        - [7.4.1.1.2. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > NumberType`](#definition_dataModel_fields_additionalProperties_oneOf_i1)
          - [7.4.1.1.2.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 1 > type](#definition_dataModel_fields_additionalProperties_oneOf_i1_type)
          - [7.4.1.1.2.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 1 > digits](#definition_dataModel_fields_additionalProperties_oneOf_i1_digits)
          - [7.4.1.1.2.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 1 > decimals](#definition_dataModel_fields_additionalProperties_oneOf_i1_decimals)
          - [7.4.1.1.2.4. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 1 > nullable](#definition_dataModel_fields_additionalProperties_oneOf_i1_nullable)
          - [7.4.1.1.2.5. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 1 > check](#definition_dataModel_fields_additionalProperties_oneOf_i1_check)
        - [7.4.1.1.3. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > BooleanType`](#definition_dataModel_fields_additionalProperties_oneOf_i2)
          - [7.4.1.1.3.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 2 > type](#definition_dataModel_fields_additionalProperties_oneOf_i2_type)
          - [7.4.1.1.3.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 2 > nullable](#definition_dataModel_fields_additionalProperties_oneOf_i2_nullable)
          - [7.4.1.1.3.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 2 > check](#definition_dataModel_fields_additionalProperties_oneOf_i2_check)
        - [7.4.1.1.4. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > DateTimeType`](#definition_dataModel_fields_additionalProperties_oneOf_i3)
          - [7.4.1.1.4.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 3 > type](#definition_dataModel_fields_additionalProperties_oneOf_i3_type)
          - [7.4.1.1.4.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 3 > nullable](#definition_dataModel_fields_additionalProperties_oneOf_i3_nullable)
          - [7.4.1.1.4.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 3 > check](#definition_dataModel_fields_additionalProperties_oneOf_i3_check)
        - [7.4.1.1.5. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > AnyType`](#definition_dataModel_fields_additionalProperties_oneOf_i4)
          - [7.4.1.1.5.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 4 > type](#definition_dataModel_fields_additionalProperties_oneOf_i4_type)
          - [7.4.1.1.5.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 4 > nullable](#definition_dataModel_fields_additionalProperties_oneOf_i4_nullable)
          - [7.4.1.1.5.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 4 > check](#definition_dataModel_fields_additionalProperties_oneOf_i4_check)
        - [7.4.1.1.6. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > EnumType`](#definition_dataModel_fields_additionalProperties_oneOf_i5)
          - [7.4.1.1.6.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 5 > type](#definition_dataModel_fields_additionalProperties_oneOf_i5_type)
          - [7.4.1.1.6.2. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 5 > values](#definition_dataModel_fields_additionalProperties_oneOf_i5_values)
            - [7.4.1.1.6.2.1. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 5 > values > oneOf > item 0`](#definition_dataModel_fields_additionalProperties_oneOf_i5_values_oneOf_i0)
              - [7.4.1.1.6.2.1.1. SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 5 > values > oneOf > item 0 > item 0 items](#autogenerated_heading_2)
            - [7.4.1.1.6.2.2. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 5 > values > oneOf > item 1`](#definition_dataModel_fields_additionalProperties_oneOf_i5_values_oneOf_i1)
          - [7.4.1.1.6.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 5 > nullable](#definition_dataModel_fields_additionalProperties_oneOf_i5_nullable)
        - [7.4.1.1.7. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > ArrayType`](#definition_dataModel_fields_additionalProperties_oneOf_i6)
          - [7.4.1.1.7.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 6 > type](#definition_dataModel_fields_additionalProperties_oneOf_i6_type)
          - [7.4.1.1.7.2. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 6 > elementType](#definition_dataModel_fields_additionalProperties_oneOf_i6_elementType)
          - [7.4.1.1.7.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 6 > nullable](#definition_dataModel_fields_additionalProperties_oneOf_i6_nullable)
        - [7.4.1.1.8. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > MediaDataType`](#definition_dataModel_fields_additionalProperties_oneOf_i7)
          - [7.4.1.1.8.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 7 > type](#definition_dataModel_fields_additionalProperties_oneOf_i7_type)
          - [7.4.1.1.8.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 7 > nullable](#definition_dataModel_fields_additionalProperties_oneOf_i7_nullable)
          - [7.4.1.1.8.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 7 > check](#definition_dataModel_fields_additionalProperties_oneOf_i7_check)
        - [7.4.1.1.9. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > ObjectDataType`](#definition_dataModel_fields_additionalProperties_oneOf_i8)
          - [7.4.1.1.9.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 8 > type](#definition_dataModel_fields_additionalProperties_oneOf_i8_type)
          - [7.4.1.1.9.2. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 8 > fields](#definition_dataModel_fields_additionalProperties_oneOf_i8_fields)
            - [7.4.1.1.9.2.1. Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 8 > fields > DataType](#definition_dataModel_fields_additionalProperties_oneOf_i8_fields_additionalProperties)
          - [7.4.1.1.9.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 8 > nullable](#definition_dataModel_fields_additionalProperties_oneOf_i8_nullable)
    - [7.4.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > nullable](#definition_dataModel_nullable)
  - [7.5. [Required] Property SWAR Process Definition v2 > definition > activities](#definition_activities)
    - [7.5.1. SWAR Process Definition v2 > definition > activities > Activity](#autogenerated_heading_3)
      - [7.5.1.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > TaskActivity`](#definition_activities_items_oneOf_i0)
        - [7.5.1.1.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > type](#definition_activities_items_oneOf_i0_type)
        - [7.5.1.1.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > id](#definition_activities_items_oneOf_i0_id)
        - [7.5.1.1.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > name](#definition_activities_items_oneOf_i0_name)
        - [7.5.1.1.4. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > description](#definition_activities_items_oneOf_i0_description)
        - [7.5.1.1.5. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action](#definition_activities_items_oneOf_i0_action)
          - [7.5.1.1.5.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > FormAction`](#definition_activities_items_oneOf_i0_action_oneOf_i0)
            - [7.5.1.1.5.1.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_type)
            - [7.5.1.1.5.1.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition)
              - [7.5.1.1.5.1.2.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > id](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_id)
              - [7.5.1.1.5.1.2.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > description](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_description)
              - [7.5.1.1.5.1.2.3. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > showTitle](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_showTitle)
              - [7.5.1.1.5.1.2.4. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields)
                - [7.5.1.1.5.1.2.4.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > formElement](#autogenerated_heading_4)
                  - [7.5.1.1.5.1.2.4.1.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > formRow`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0)
                    - [7.5.1.1.5.1.2.4.1.1.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > scalarFieldWrapper](#autogenerated_heading_5)
                      - [7.5.1.1.5.1.2.4.1.1.1.1. Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > scalarField](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 0`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i0)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.1.1. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 0 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i0_type)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 1`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i1)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.2.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 1 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i1_type)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.3. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 2`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i2)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.3.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 2 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i2_type)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.4. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 3`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i3)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.4.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 3 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i3_type)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.5. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 4`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i4)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.5.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 4 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i4_type)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.6. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 5`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i5)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.6.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 5 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i5_type)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.7. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 6`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i6)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.7.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 6 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i6_type)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.8. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 7`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i7)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.8.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 7 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i7_type)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.9. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 8`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i8)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.9.1. The following properties are required](#autogenerated_heading_6)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.9.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 8 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i8_type)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.10. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 9`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i9)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.10.1. The following properties are required](#autogenerated_heading_7)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.10.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 9 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i9_type)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.11. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 10`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i10)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.11.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 10 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i10_type)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.11.2. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 10 > required](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i10_required)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.12. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 11`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i11)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.12.1. The following properties are required](#autogenerated_heading_8)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.12.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 11 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i11_type)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.13. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_type)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.14. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > label](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_label)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.15. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > errorMessage](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_errorMessage)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.16. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > hidden](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_hidden)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.16.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > hidden > oneOf > item 0`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_hidden_oneOf_i0)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.16.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > hidden > oneOf > item 1`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_hidden_oneOf_i1)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.17. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > width](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_width)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.18. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > required](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_required)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.19. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > check](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_check)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.20. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > maxLength](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_maxLength)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.21. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > mask](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_mask)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.22. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > maskMessage](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_maskMessage)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.23. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > digits](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_digits)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.24. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > decimals](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_decimals)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.25. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > values](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_values)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.25.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > values > oneOf > item 0`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_values_oneOf_i0)
                            - [7.5.1.1.5.1.2.4.1.1.1.1.25.1.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > values > oneOf > item 0 > item 0 items](#autogenerated_heading_9)
                          - [7.5.1.1.5.1.2.4.1.1.1.1.25.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > values > oneOf > item 1`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_values_oneOf_i1)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.26. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > horizontal](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_horizontal)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.27. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > expression](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_expression)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.28. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > style](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_style)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.29. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > align](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_align)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.30. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > mediaType](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_mediaType)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.31. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > maxDuration](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_maxDuration)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.32. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > quality](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_quality)
                        - [7.5.1.1.5.1.2.4.1.1.1.1.33. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > useFrontCamera](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_useFrontCamera)
                  - [7.5.1.1.5.1.2.4.1.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > topLevelFieldWrapper`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1)
                    - [7.5.1.1.5.1.2.4.1.2.1. Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties)
                      - [7.5.1.1.5.1.2.4.1.2.1.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > scalarField`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i0)
                      - [7.5.1.1.5.1.2.4.1.2.1.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > arrayField`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1)
                        - [7.5.1.1.5.1.2.4.1.2.1.2.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > type](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_type)
                        - [7.5.1.1.5.1.2.4.1.2.1.2.2. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > fixed](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_fixed)
                        - [7.5.1.1.5.1.2.4.1.2.1.2.3. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > label](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_label)
                        - [7.5.1.1.5.1.2.4.1.2.1.2.4. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > fields](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_fields)
                          - [7.5.1.1.5.1.2.4.1.2.1.2.4.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > fields > fields items](#autogenerated_heading_10)
                            - [7.5.1.1.5.1.2.4.1.2.1.2.4.1.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > fields > fields items > oneOf > formRow`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_fields_items_oneOf_i0)
                            - [7.5.1.1.5.1.2.4.1.2.1.2.4.1.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > fields > fields items > oneOf > scalarFieldWrapper`](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_fields_items_oneOf_i1)
          - [7.5.1.1.5.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > InstructionAction`](#definition_activities_items_oneOf_i0_action_oneOf_i1)
            - [7.5.1.1.5.2.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 1 > type](#definition_activities_items_oneOf_i0_action_oneOf_i1_type)
            - [7.5.1.1.5.2.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 1 > instructions](#definition_activities_items_oneOf_i0_action_oneOf_i1_instructions)
          - [7.5.1.1.5.3. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > ChoiceAction`](#definition_activities_items_oneOf_i0_action_oneOf_i2)
            - [7.5.1.1.5.3.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 2 > type](#definition_activities_items_oneOf_i0_action_oneOf_i2_type)
            - [7.5.1.1.5.3.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 2 > prompt](#definition_activities_items_oneOf_i0_action_oneOf_i2_prompt)
            - [7.5.1.1.5.3.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 2 > options](#definition_activities_items_oneOf_i0_action_oneOf_i2_options)
              - [7.5.1.1.5.3.3.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 2 > options > ChoiceOption](#autogenerated_heading_11)
                - [7.5.1.1.5.3.3.1.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 2 > options > options items > key](#definition_activities_items_oneOf_i0_action_oneOf_i2_options_items_key)
                - [7.5.1.1.5.3.3.1.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 2 > options > options items > label](#definition_activities_items_oneOf_i0_action_oneOf_i2_options_items_label)
        - [7.5.1.1.6. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > required](#definition_activities_items_oneOf_i0_required)
        - [7.5.1.1.7. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > input](#definition_activities_items_oneOf_i0_input)
          - [7.5.1.1.7.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > input > Mapping](#autogenerated_heading_12)
        - [7.5.1.1.8. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > output](#definition_activities_items_oneOf_i0_output)
          - [7.5.1.1.8.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > output > Mapping](#autogenerated_heading_13)
      - [7.5.1.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > SequenceActivity`](#definition_activities_items_oneOf_i1)
        - [7.5.1.2.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 1 > type](#definition_activities_items_oneOf_i1_type)
        - [7.5.1.2.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 1 > id](#definition_activities_items_oneOf_i1_id)
        - [7.5.1.2.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 1 > name](#definition_activities_items_oneOf_i1_name)
        - [7.5.1.2.4. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 1 > description](#definition_activities_items_oneOf_i1_description)
        - [7.5.1.2.5. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 1 > activities](#definition_activities_items_oneOf_i1_activities)
          - [7.5.1.2.5.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 1 > activities > Activity](#autogenerated_heading_14)
      - [7.5.1.3. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > DecisionActivity`](#definition_activities_items_oneOf_i2)
        - [7.5.1.3.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > type](#definition_activities_items_oneOf_i2_type)
        - [7.5.1.3.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > id](#definition_activities_items_oneOf_i2_id)
        - [7.5.1.3.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > expression](#definition_activities_items_oneOf_i2_expression)
        - [7.5.1.3.4. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > branches](#definition_activities_items_oneOf_i2_branches)
          - [7.5.1.3.4.1. Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > branches > Activity](#definition_activities_items_oneOf_i2_branches_additionalProperties)
        - [7.5.1.3.5. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > name](#definition_activities_items_oneOf_i2_name)
        - [7.5.1.3.6. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > description](#definition_activities_items_oneOf_i2_description)
      - [7.5.1.4. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > GroupActivity`](#definition_activities_items_oneOf_i3)
        - [7.5.1.4.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 3 > type](#definition_activities_items_oneOf_i3_type)
        - [7.5.1.4.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 3 > id](#definition_activities_items_oneOf_i3_id)
        - [7.5.1.4.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 3 > name](#definition_activities_items_oneOf_i3_name)
        - [7.5.1.4.4. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 3 > description](#definition_activities_items_oneOf_i3_description)
        - [7.5.1.4.5. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 3 > activities](#definition_activities_items_oneOf_i3_activities)
          - [7.5.1.4.5.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 3 > activities > Activity](#autogenerated_heading_15)
      - [7.5.1.5. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > ScriptActivity`](#definition_activities_items_oneOf_i4)
        - [7.5.1.5.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > type](#definition_activities_items_oneOf_i4_type)
        - [7.5.1.5.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > id](#definition_activities_items_oneOf_i4_id)
        - [7.5.1.5.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > name](#definition_activities_items_oneOf_i4_name)
        - [7.5.1.5.4. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > description](#definition_activities_items_oneOf_i4_description)
        - [7.5.1.5.5. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > script](#definition_activities_items_oneOf_i4_script)
          - [7.5.1.5.5.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > script > script items](#autogenerated_heading_16)
        - [7.5.1.5.6. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > outputKey](#definition_activities_items_oneOf_i4_outputKey)
      - [7.5.1.6. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > HttpActivity`](#definition_activities_items_oneOf_i5)
        - [7.5.1.6.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > type](#definition_activities_items_oneOf_i5_type)
        - [7.5.1.6.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > id](#definition_activities_items_oneOf_i5_id)
        - [7.5.1.6.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > name](#definition_activities_items_oneOf_i5_name)
        - [7.5.1.6.4. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > description](#definition_activities_items_oneOf_i5_description)
        - [7.5.1.6.5. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > urlExpression](#definition_activities_items_oneOf_i5_urlExpression)
        - [7.5.1.6.6. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > method](#definition_activities_items_oneOf_i5_method)
        - [7.5.1.6.7. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > bodyExpression](#definition_activities_items_oneOf_i5_bodyExpression)
        - [7.5.1.6.8. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > outputKey](#definition_activities_items_oneOf_i5_outputKey)

**Title:** SWAR Process Definition v2

|                           |             |
| ------------------------- | ----------- |
| **Type**                  | `object`    |
| **Required**              | No          |
| **Additional properties** | Not allowed |

**Description:** SWAR process definition aligned with the current modules/swar-domain Kotlin serialization model

<details>
<summary>
<strong> <a name="reference"></a>1. [Required] Property SWAR Process Definition v2 > reference</strong>  

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
<strong> <a name="description"></a>2. [Required] Property SWAR Process Definition v2 > description</strong>  

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
<strong> <a name="fullDescription"></a>3. [Required] Property SWAR Process Definition v2 > fullDescription</strong>  

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
<strong> <a name="executionRefName"></a>4. [Optional] Property SWAR Process Definition v2 > executionRefName</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |
| **Default**  | `"UUID"` |

**Description:** Name of the process execution reference. Defaults to UUID.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="executionRefMask"></a>5. [Optional] Property SWAR Process Definition v2 > executionRefMask</strong>  

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
<strong> <a name="version"></a>6. [Required] Property SWAR Process Definition v2 > version</strong>  

</summary>
<blockquote>

|                |                      |
| -------------- | -------------------- |
| **Type**       | `string`             |
| **Required**   | Yes                  |
| **Defined in** | #/definitions/SemVer |

| Restrictions                      |                                                                                                       |
| --------------------------------- | ----------------------------------------------------------------------------------------------------- |
| **Must match regular expression** | ```^\d+(\.\d+){0,2}$``` [Test](https://regex101.com/?regex=%5E%5Cd%2B%28%5C.%5Cd%2B%29%7B0%2C2%7D%24) |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition"></a>7. [Required] Property SWAR Process Definition v2 > definition</strong>  

</summary>
<blockquote>

|                           |                          |
| ------------------------- | ------------------------ |
| **Type**                  | `object`                 |
| **Required**              | Yes                      |
| **Additional properties** | Not allowed              |
| **Defined in**            | #/definitions/ProcessDef |

<details>
<summary>
<strong> <a name="definition_processRef"></a>7.1. [Required] Property SWAR Process Definition v2 > definition > processRef</strong>  

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
<strong> <a name="definition_description"></a>7.2. [Optional] Property SWAR Process Definition v2 > definition > description</strong>  

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
<strong> <a name="definition_externalIdName"></a>7.3. [Optional] Property SWAR Process Definition v2 > definition > externalIdName</strong>  

</summary>
<blockquote>

|              |                  |
| ------------ | ---------------- |
| **Type**     | `string or null` |
| **Required** | No               |
| **Default**  | `"uuid"`         |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel"></a>7.4. [Required] Property SWAR Process Definition v2 > definition > dataModel</strong>  

</summary>
<blockquote>

|                           |                          |
| ------------------------- | ------------------------ |
| **Type**                  | `object`                 |
| **Required**              | Yes                      |
| **Additional properties** | Not allowed              |
| **Defined in**            | #/definitions/ObjectType |

<details>
<summary>
<strong> <a name="definition_dataModel_fields"></a>7.4.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields</strong>  

</summary>
<blockquote>

|                           |                                                                                                          |
| ------------------------- | -------------------------------------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                                                 |
| **Required**              | Yes                                                                                                      |
| **Additional properties** | [Each additional property must conform to the schema](#definition_dataModel_fields_additionalProperties) |

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties"></a>7.4.1.1. Property SWAR Process Definition v2 > definition > dataModel > fields > DataType</strong>  

</summary>
<blockquote>

|                           |                        |
| ------------------------- | ---------------------- |
| **Type**                  | `combining`            |
| **Required**              | No                     |
| **Additional properties** | Any type allowed       |
| **Defined in**            | #/definitions/DataType |

<blockquote>

| One of(Option)                                                               |
| ---------------------------------------------------------------------------- |
| [StringType](#definition_dataModel_fields_additionalProperties_oneOf_i0)     |
| [NumberType](#definition_dataModel_fields_additionalProperties_oneOf_i1)     |
| [BooleanType](#definition_dataModel_fields_additionalProperties_oneOf_i2)    |
| [DateTimeType](#definition_dataModel_fields_additionalProperties_oneOf_i3)   |
| [AnyType](#definition_dataModel_fields_additionalProperties_oneOf_i4)        |
| [EnumType](#definition_dataModel_fields_additionalProperties_oneOf_i5)       |
| [ArrayType](#definition_dataModel_fields_additionalProperties_oneOf_i6)      |
| [MediaDataType](#definition_dataModel_fields_additionalProperties_oneOf_i7)  |
| [ObjectDataType](#definition_dataModel_fields_additionalProperties_oneOf_i8) |

<blockquote>

###### <a name="definition_dataModel_fields_additionalProperties_oneOf_i0"></a>7.4.1.1.1. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > StringType`

|                           |                          |
| ------------------------- | ------------------------ |
| **Type**                  | `object`                 |
| **Required**              | No                       |
| **Additional properties** | Not allowed              |
| **Defined in**            | #/definitions/StringType |

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i0_type"></a>7.4.1.1.1.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 0 > type</strong>  

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
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i0_nullable"></a>7.4.1.1.1.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 0 > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `false`   |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i0_mask"></a>7.4.1.1.1.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 0 > mask</strong>  

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
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i0_check"></a>7.4.1.1.1.4. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 0 > check</strong>  

</summary>
<blockquote>

|              |                  |
| ------------ | ---------------- |
| **Type**     | `string or null` |
| **Required** | No               |

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_dataModel_fields_additionalProperties_oneOf_i1"></a>7.4.1.1.2. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > NumberType`

|                           |                          |
| ------------------------- | ------------------------ |
| **Type**                  | `object`                 |
| **Required**              | No                       |
| **Additional properties** | Not allowed              |
| **Defined in**            | #/definitions/NumberType |

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i1_type"></a>7.4.1.1.2.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 1 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"number"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i1_digits"></a>7.4.1.1.2.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 1 > digits</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `integer` |
| **Required** | No        |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i1_decimals"></a>7.4.1.1.2.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 1 > decimals</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `integer` |
| **Required** | No        |
| **Default**  | `0`       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i1_nullable"></a>7.4.1.1.2.4. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 1 > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `false`   |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i1_check"></a>7.4.1.1.2.5. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 1 > check</strong>  

</summary>
<blockquote>

|              |                  |
| ------------ | ---------------- |
| **Type**     | `string or null` |
| **Required** | No               |

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_dataModel_fields_additionalProperties_oneOf_i2"></a>7.4.1.1.3. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > BooleanType`

|                           |                           |
| ------------------------- | ------------------------- |
| **Type**                  | `object`                  |
| **Required**              | No                        |
| **Additional properties** | Not allowed               |
| **Defined in**            | #/definitions/BooleanType |

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i2_type"></a>7.4.1.1.3.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 2 > type</strong>  

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
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i2_nullable"></a>7.4.1.1.3.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 2 > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `false`   |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i2_check"></a>7.4.1.1.3.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 2 > check</strong>  

</summary>
<blockquote>

|              |                  |
| ------------ | ---------------- |
| **Type**     | `string or null` |
| **Required** | No               |

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_dataModel_fields_additionalProperties_oneOf_i3"></a>7.4.1.1.4. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > DateTimeType`

|                           |                            |
| ------------------------- | -------------------------- |
| **Type**                  | `object`                   |
| **Required**              | No                         |
| **Additional properties** | Not allowed                |
| **Defined in**            | #/definitions/DateTimeType |

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i3_type"></a>7.4.1.1.4.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 3 > type</strong>  

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
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i3_nullable"></a>7.4.1.1.4.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 3 > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `false`   |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i3_check"></a>7.4.1.1.4.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 3 > check</strong>  

</summary>
<blockquote>

|              |                  |
| ------------ | ---------------- |
| **Type**     | `string or null` |
| **Required** | No               |

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_dataModel_fields_additionalProperties_oneOf_i4"></a>7.4.1.1.5. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > AnyType`

|                           |                       |
| ------------------------- | --------------------- |
| **Type**                  | `object`              |
| **Required**              | No                    |
| **Additional properties** | Not allowed           |
| **Defined in**            | #/definitions/AnyType |

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i4_type"></a>7.4.1.1.5.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 4 > type</strong>  

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
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i4_nullable"></a>7.4.1.1.5.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 4 > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `false`   |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i4_check"></a>7.4.1.1.5.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 4 > check</strong>  

</summary>
<blockquote>

|              |                  |
| ------------ | ---------------- |
| **Type**     | `string or null` |
| **Required** | No               |

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_dataModel_fields_additionalProperties_oneOf_i5"></a>7.4.1.1.6. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > EnumType`

|                           |                        |
| ------------------------- | ---------------------- |
| **Type**                  | `object`               |
| **Required**              | No                     |
| **Additional properties** | Not allowed            |
| **Defined in**            | #/definitions/EnumType |

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i5_type"></a>7.4.1.1.6.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 5 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"enum"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i5_values"></a>7.4.1.1.6.2. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 5 > values</strong>  

</summary>
<blockquote>

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `combining`      |
| **Required**              | Yes              |
| **Additional properties** | Any type allowed |

**Description:** Static values or an expression that resolves the allowed values at runtime.

<blockquote>

| One of(Option)                                                                       |
| ------------------------------------------------------------------------------------ |
| [item 0](#definition_dataModel_fields_additionalProperties_oneOf_i5_values_oneOf_i0) |
| [item 1](#definition_dataModel_fields_additionalProperties_oneOf_i5_values_oneOf_i1) |

<blockquote>

###### <a name="definition_dataModel_fields_additionalProperties_oneOf_i5_values_oneOf_i0"></a>7.4.1.1.6.2.1. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 5 > values > oneOf > item 0`

|              |                   |
| ------------ | ----------------- |
| **Type**     | `array of string` |
| **Required** | No                |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                                                                  | Description |
| ------------------------------------------------------------------------------------------------ | ----------- |
| [item 0 items](#definition_dataModel_fields_additionalProperties_oneOf_i5_values_oneOf_i0_items) | -           |

###### <a name="autogenerated_heading_2"></a>7.4.1.1.6.2.1.1. SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 5 > values > oneOf > item 0 > item 0 items

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
<blockquote>

###### <a name="definition_dataModel_fields_additionalProperties_oneOf_i5_values_oneOf_i1"></a>7.4.1.1.6.2.2. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 5 > values > oneOf > item 1`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>

</blockquote>

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i5_nullable"></a>7.4.1.1.6.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 5 > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `false`   |

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_dataModel_fields_additionalProperties_oneOf_i6"></a>7.4.1.1.7. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > ArrayType`

|                           |                         |
| ------------------------- | ----------------------- |
| **Type**                  | `object`                |
| **Required**              | No                      |
| **Additional properties** | Not allowed             |
| **Defined in**            | #/definitions/ArrayType |

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i6_type"></a>7.4.1.1.7.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 6 > type</strong>  

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
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i6_elementType"></a>7.4.1.1.7.2. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 6 > elementType</strong>  

</summary>
<blockquote>

|                           |                                                                                                       |
| ------------------------- | ----------------------------------------------------------------------------------------------------- |
| **Type**                  | `combining`                                                                                           |
| **Required**              | Yes                                                                                                   |
| **Additional properties** | Any type allowed                                                                                      |
| **Same definition as**    | [definition_dataModel_fields_additionalProperties](#definition_dataModel_fields_additionalProperties) |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i6_nullable"></a>7.4.1.1.7.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 6 > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `false`   |

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_dataModel_fields_additionalProperties_oneOf_i7"></a>7.4.1.1.8. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > MediaDataType`

|                           |                             |
| ------------------------- | --------------------------- |
| **Type**                  | `object`                    |
| **Required**              | No                          |
| **Additional properties** | Not allowed                 |
| **Defined in**            | #/definitions/MediaDataType |

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i7_type"></a>7.4.1.1.8.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 7 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"media"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i7_nullable"></a>7.4.1.1.8.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 7 > nullable</strong>  

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
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i7_check"></a>7.4.1.1.8.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 7 > check</strong>  

</summary>
<blockquote>

|              |                  |
| ------------ | ---------------- |
| **Type**     | `string or null` |
| **Required** | No               |

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_dataModel_fields_additionalProperties_oneOf_i8"></a>7.4.1.1.9. Property `SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > ObjectDataType`

|                           |                              |
| ------------------------- | ---------------------------- |
| **Type**                  | `object`                     |
| **Required**              | No                           |
| **Additional properties** | Not allowed                  |
| **Defined in**            | #/definitions/ObjectDataType |

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i8_type"></a>7.4.1.1.9.1. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 8 > type</strong>  

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
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i8_fields"></a>7.4.1.1.9.2. [Required] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 8 > fields</strong>  

</summary>
<blockquote>

|                           |                                                                                                                                               |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                                                                                      |
| **Required**              | Yes                                                                                                                                           |
| **Additional properties** | [Each additional property must conform to the schema](#definition_dataModel_fields_additionalProperties_oneOf_i8_fields_additionalProperties) |

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i8_fields_additionalProperties"></a>7.4.1.1.9.2.1. Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 8 > fields > DataType</strong>  

</summary>
<blockquote>

|                           |                                                                                                       |
| ------------------------- | ----------------------------------------------------------------------------------------------------- |
| **Type**                  | `combining`                                                                                           |
| **Required**              | No                                                                                                    |
| **Additional properties** | Any type allowed                                                                                      |
| **Same definition as**    | [definition_dataModel_fields_additionalProperties](#definition_dataModel_fields_additionalProperties) |

</blockquote>
</details>

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_fields_additionalProperties_oneOf_i8_nullable"></a>7.4.1.1.9.3. [Optional] Property SWAR Process Definition v2 > definition > dataModel > fields > additionalProperties > oneOf > item 8 > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `false`   |

</blockquote>
</details>

</blockquote>

</blockquote>

</blockquote>
</details>

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_dataModel_nullable"></a>7.4.2. [Optional] Property SWAR Process Definition v2 > definition > dataModel > nullable</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `false`   |

</blockquote>
</details>

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities"></a>7.5. [Required] Property SWAR Process Definition v2 > definition > activities</strong>  

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

| Each item of this array must be          | Description |
| ---------------------------------------- | ----------- |
| [Activity](#definition_activities_items) | -           |

#### <a name="autogenerated_heading_3"></a>7.5.1. SWAR Process Definition v2 > definition > activities > Activity

|                           |                        |
| ------------------------- | ---------------------- |
| **Type**                  | `combining`            |
| **Required**              | No                     |
| **Additional properties** | Any type allowed       |
| **Defined in**            | #/definitions/Activity |

<blockquote>

| One of(Option)                                            |
| --------------------------------------------------------- |
| [TaskActivity](#definition_activities_items_oneOf_i0)     |
| [SequenceActivity](#definition_activities_items_oneOf_i1) |
| [DecisionActivity](#definition_activities_items_oneOf_i2) |
| [GroupActivity](#definition_activities_items_oneOf_i3)    |
| [ScriptActivity](#definition_activities_items_oneOf_i4)   |
| [HttpActivity](#definition_activities_items_oneOf_i5)     |

<blockquote>

##### <a name="definition_activities_items_oneOf_i0"></a>7.5.1.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > TaskActivity`

|                           |                            |
| ------------------------- | -------------------------- |
| **Type**                  | `object`                   |
| **Required**              | No                         |
| **Additional properties** | Not allowed                |
| **Defined in**            | #/definitions/TaskActivity |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_type"></a>7.5.1.1.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > type</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i0_id"></a>7.5.1.1.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > id</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i0_name"></a>7.5.1.1.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > name</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i0_description"></a>7.5.1.1.4. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > description</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i0_action"></a>7.5.1.1.5. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action</strong>  

</summary>
<blockquote>

|                           |                          |
| ------------------------- | ------------------------ |
| **Type**                  | `combining`              |
| **Required**              | Yes                      |
| **Additional properties** | Any type allowed         |
| **Defined in**            | #/definitions/TaskAction |

<blockquote>

| One of(Option)                                                             |
| -------------------------------------------------------------------------- |
| [FormAction](#definition_activities_items_oneOf_i0_action_oneOf_i0)        |
| [InstructionAction](#definition_activities_items_oneOf_i0_action_oneOf_i1) |
| [ChoiceAction](#definition_activities_items_oneOf_i0_action_oneOf_i2)      |

<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0"></a>7.5.1.1.5.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > FormAction`

|                           |                          |
| ------------------------- | ------------------------ |
| **Type**                  | `object`                 |
| **Required**              | No                       |
| **Additional properties** | Not allowed              |
| **Defined in**            | #/definitions/FormAction |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_type"></a>7.5.1.1.5.1.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > type</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition"></a>7.5.1.1.5.1.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition</strong>  

</summary>
<blockquote>

**Title:** Form Definition

|                           |                             |
| ------------------------- | --------------------------- |
| **Type**                  | `object`                    |
| **Required**              | Yes                         |
| **Additional properties** | Not allowed                 |
| **Defined in**            | form-definition.schema.json |

**Description:** Serializable definition of a SWAR form, matching FormSerializer.

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_id"></a>7.5.1.1.5.1.2.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > id</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** Unique form identifier.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_description"></a>7.5.1.1.5.1.2.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > description</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** Human-readable form description.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_showTitle"></a>7.5.1.1.5.1.2.3. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > showTitle</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `false`   |

**Description:** When true, render the description as the form title.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields"></a>7.5.1.1.5.1.2.4. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `array` |
| **Required** | Yes     |

**Description:** Ordered top-level scalar fields, rows, and array fields.

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                                                              | Description                                               |
| -------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| [formElement](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items) | A top-level element: a row, scalar field, or array field. |

###### <a name="autogenerated_heading_4"></a>7.5.1.1.5.1.2.4.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > formElement

|                           |                           |
| ------------------------- | ------------------------- |
| **Type**                  | `combining`               |
| **Required**              | No                        |
| **Additional properties** | Any type allowed          |
| **Defined in**            | #/definitions/formElement |

**Description:** A top-level element: a row, scalar field, or array field.

<blockquote>

| One of(Option)                                                                                                 |
| -------------------------------------------------------------------------------------------------------------- |
| [formRow](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0)              |
| [topLevelFieldWrapper](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1) |

<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0"></a>7.5.1.1.5.1.2.4.1.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > formRow`

|                |                       |
| -------------- | --------------------- |
| **Type**       | `array`               |
| **Required**   | No                    |
| **Defined in** | #/definitions/formRow |

**Description:** Horizontal grouping of scalar fields. Rows are encoded directly as JSON arrays.

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                                                                                    | Description                                                       |
| ------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------- |
| [scalarFieldWrapper](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items) | Single-key scalar field object. Used in rows and array templates. |

###### <a name="autogenerated_heading_5"></a>7.5.1.1.5.1.2.4.1.1.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > scalarFieldWrapper

|                           |                                                                                                                                                                          |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Type**                  | `object`                                                                                                                                                                 |
| **Required**              | No                                                                                                                                                                       |
| **Additional properties** | [Each additional property must conform to the schema](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties) |
| **Defined in**            | #/definitions/scalarFieldWrapper                                                                                                                                         |

**Description:** Single-key scalar field object. Used in rows and array templates.

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties"></a>7.5.1.1.5.1.2.4.1.1.1.1. Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > scalarField</strong>  

</summary>
<blockquote>

|                           |                           |
| ------------------------- | ------------------------- |
| **Type**                  | `combining`               |
| **Required**              | No                        |
| **Additional properties** | Not allowed               |
| **Defined in**            | #/definitions/scalarField |

<blockquote>

| One of(Option)                                                                                                                         |
| -------------------------------------------------------------------------------------------------------------------------------------- |
| [item 0](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i0)   |
| [item 1](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i1)   |
| [item 2](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i2)   |
| [item 3](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i3)   |
| [item 4](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i4)   |
| [item 5](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i5)   |
| [item 6](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i6)   |
| [item 7](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i7)   |
| [item 8](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i8)   |
| [item 9](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i9)   |
| [item 10](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i10) |
| [item 11](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i11) |

<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i0"></a>7.5.1.1.5.1.2.4.1.1.1.1.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 0`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i0_type"></a>7.5.1.1.5.1.2.4.1.1.1.1.1.1. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 0 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | No      |

Specific value: `"text"`

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i1"></a>7.5.1.1.5.1.2.4.1.1.1.1.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 1`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i1_type"></a>7.5.1.1.5.1.2.4.1.1.1.1.2.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 1 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"mask"`

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i2"></a>7.5.1.1.5.1.2.4.1.1.1.1.3. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 2`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i2_type"></a>7.5.1.1.5.1.2.4.1.1.1.1.3.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 2 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"multiline"`

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i3"></a>7.5.1.1.5.1.2.4.1.1.1.1.4. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 3`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i3_type"></a>7.5.1.1.5.1.2.4.1.1.1.1.4.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 3 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"number"`

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i4"></a>7.5.1.1.5.1.2.4.1.1.1.1.5. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 4`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i4_type"></a>7.5.1.1.5.1.2.4.1.1.1.1.5.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 4 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"checkbox"`

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i5"></a>7.5.1.1.5.1.2.4.1.1.1.1.6. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 5`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i5_type"></a>7.5.1.1.5.1.2.4.1.1.1.1.6.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 5 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"toggle"`

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i6"></a>7.5.1.1.5.1.2.4.1.1.1.1.7. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 6`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i6_type"></a>7.5.1.1.5.1.2.4.1.1.1.1.7.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 6 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"date"`

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i7"></a>7.5.1.1.5.1.2.4.1.1.1.1.8. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 7`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i7_type"></a>7.5.1.1.5.1.2.4.1.1.1.1.8.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 7 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"datetime"`

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i8"></a>7.5.1.1.5.1.2.4.1.1.1.1.9. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 8`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

###### <a name="autogenerated_heading_6"></a>7.5.1.1.5.1.2.4.1.1.1.1.9.1. The following properties are required
* values

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i8_type"></a>7.5.1.1.5.1.2.4.1.1.1.1.9.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 8 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"select"`

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i9"></a>7.5.1.1.5.1.2.4.1.1.1.1.10. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 9`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

###### <a name="autogenerated_heading_7"></a>7.5.1.1.5.1.2.4.1.1.1.1.10.1. The following properties are required
* values

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i9_type"></a>7.5.1.1.5.1.2.4.1.1.1.1.10.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 9 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"radio"`

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i10"></a>7.5.1.1.5.1.2.4.1.1.1.1.11. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 10`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i10_type"></a>7.5.1.1.5.1.2.4.1.1.1.1.11.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 10 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"display"`

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i10_required"></a>7.5.1.1.5.1.2.4.1.1.1.1.11.2. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 10 > required</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | No      |

Specific value: `false`

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i11"></a>7.5.1.1.5.1.2.4.1.1.1.1.12. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 11`

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

###### <a name="autogenerated_heading_8"></a>7.5.1.1.5.1.2.4.1.1.1.1.12.1. The following properties are required
* mediaType

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_oneOf_i11_type"></a>7.5.1.1.5.1.2.4.1.1.1.1.12.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > oneOf > item 11 > type</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `const` |
| **Required** | Yes     |

Specific value: `"media"`

</blockquote>
</details>

</blockquote>

</blockquote>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_type"></a>7.5.1.1.5.1.2.4.1.1.1.1.13. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > type</strong>  

</summary>
<blockquote>

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `"text"`           |

**Description:** Field kind. When omitted, FormSerializer deserializes the field as text.

Must be one of:
* "text"
* "mask"
* "multiline"
* "number"
* "checkbox"
* "toggle"
* "date"
* "datetime"
* "select"
* "radio"
* "display"
* "media"

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_label"></a>7.5.1.1.5.1.2.4.1.1.1.1.14. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > label</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Explicit display label. When omitted, the label is inferred from the field name.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_errorMessage"></a>7.5.1.1.5.1.2.4.1.1.1.1.15. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > errorMessage</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Message displayed when validation fails.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_hidden"></a>7.5.1.1.5.1.2.4.1.1.1.1.16. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > hidden</strong>  

</summary>
<blockquote>

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `combining`      |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

**Description:** Visibility expression. A literal boolean is the common always-hidden/always-visible case; a string is evaluated as an expression against the same scope as check, re-evaluated whenever sibling field values change. Omitted means always visible. A hidden field takes no layout space and is exempt from validation while hidden.

<blockquote>

| One of(Option)                                                                                                                              |
| ------------------------------------------------------------------------------------------------------------------------------------------- |
| [item 0](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_hidden_oneOf_i0) |
| [item 1](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_hidden_oneOf_i1) |

<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_hidden_oneOf_i0"></a>7.5.1.1.5.1.2.4.1.1.1.1.16.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > hidden > oneOf > item 0`

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_hidden_oneOf_i1"></a>7.5.1.1.5.1.2.4.1.1.1.1.16.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > hidden > oneOf > item 1`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>

</blockquote>

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_width"></a>7.5.1.1.5.1.2.4.1.1.1.1.17. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > width</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `integer` |
| **Required** | No        |

**Description:** Responsive-grid weight. Defaults to 12, except radio fields, which default to 1.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_required"></a>7.5.1.1.5.1.2.4.1.1.1.1.18. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > required</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `true`    |

**Description:** Inverse of DataType.nullable. The serializer omits it when true.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_check"></a>7.5.1.1.5.1.2.4.1.1.1.1.19. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > check</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Validation expression evaluated with the field value bound as value.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_maxLength"></a>7.5.1.1.5.1.2.4.1.1.1.1.20. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > maxLength</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `integer` |
| **Required** | No        |

**Description:** Text-field UI hint; validation must be expressed with check.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_mask"></a>7.5.1.1.5.1.2.4.1.1.1.1.21. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > mask</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Input mask used by a mask field.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_maskMessage"></a>7.5.1.1.5.1.2.4.1.1.1.1.22. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > maskMessage</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Hint describing the expected masked input.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_digits"></a>7.5.1.1.5.1.2.4.1.1.1.1.23. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > digits</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `integer` |
| **Required** | No        |

**Description:** Total numeric precision.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_decimals"></a>7.5.1.1.5.1.2.4.1.1.1.1.24. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > decimals</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `integer` |
| **Required** | No        |

**Description:** Numeric scale. Defaults to 0.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_values"></a>7.5.1.1.5.1.2.4.1.1.1.1.25. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > values</strong>  

</summary>
<blockquote>

|                           |                          |
| ------------------------- | ------------------------ |
| **Type**                  | `combining`              |
| **Required**              | No                       |
| **Additional properties** | Any type allowed         |
| **Defined in**            | #/definitions/enumValues |

**Description:** Static options or an expression that resolves to options at runtime.

<blockquote>

| One of(Option)                                                                                                                              |
| ------------------------------------------------------------------------------------------------------------------------------------------- |
| [item 0](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_values_oneOf_i0) |
| [item 1](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_values_oneOf_i1) |

<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_values_oneOf_i0"></a>7.5.1.1.5.1.2.4.1.1.1.1.25.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > values > oneOf > item 0`

|              |                   |
| ------------ | ----------------- |
| **Type**     | `array of string` |
| **Required** | No                |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                                                                                                                         | Description |
| ------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| [item 0 items](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_values_oneOf_i0_items) | -           |

###### <a name="autogenerated_heading_9"></a>7.5.1.1.5.1.2.4.1.1.1.1.25.1.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > values > oneOf > item 0 > item 0 items

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_values_oneOf_i1"></a>7.5.1.1.5.1.2.4.1.1.1.1.25.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > values > oneOf > item 1`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>

</blockquote>

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_horizontal"></a>7.5.1.1.5.1.2.4.1.1.1.1.26. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > horizontal</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `false`   |

**Description:** Lay out radio options horizontally.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_expression"></a>7.5.1.1.5.1.2.4.1.1.1.1.27. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > expression</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Expression evaluated and rendered by a display field.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_style"></a>7.5.1.1.5.1.2.4.1.1.1.1.28. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > style</strong>  

</summary>
<blockquote>

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `"body"`           |

**Description:** Display-field typography style.

Must be one of:
* "header"
* "title"
* "body"
* "label"

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_align"></a>7.5.1.1.5.1.2.4.1.1.1.1.29. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > align</strong>  

</summary>
<blockquote>

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `"left"`           |

**Description:** Display-field horizontal alignment.

Must be one of:
* "left"
* "center"
* "right"

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_mediaType"></a>7.5.1.1.5.1.2.4.1.1.1.1.30. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > mediaType</strong>  

</summary>
<blockquote>

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |

**Description:** Kind of media to capture.

Must be one of:
* "photo"
* "video"
* "audio"

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_maxDuration"></a>7.5.1.1.5.1.2.4.1.1.1.1.31. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > maxDuration</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `integer` |
| **Required** | No        |

**Description:** Maximum recording duration in whole seconds. Ignored for photos.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_quality"></a>7.5.1.1.5.1.2.4.1.1.1.1.32. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > quality</strong>  

</summary>
<blockquote>

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `"default"`        |

**Description:** Best-effort platform capture quality.

Must be one of:
* "low"
* "default"
* "high"

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties_useFrontCamera"></a>7.5.1.1.5.1.2.4.1.1.1.1.33. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 0 > item 0 items > additionalProperties > useFrontCamera</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `false`   |

**Description:** Use the front camera for photo or video capture.

</blockquote>
</details>

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1"></a>7.5.1.1.5.1.2.4.1.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > topLevelFieldWrapper`

|                           |                                                                                                                                                                    |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Type**                  | `object`                                                                                                                                                           |
| **Required**              | No                                                                                                                                                                 |
| **Additional properties** | [Each additional property must conform to the schema](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties) |
| **Defined in**            | #/definitions/topLevelFieldWrapper                                                                                                                                 |

**Description:** Single-key object whose key is the field name.

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties"></a>7.5.1.1.5.1.2.4.1.2.1. Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties</strong>  

</summary>
<blockquote>

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `combining`      |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

<blockquote>

| One of(Option)                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------------------- |
| [scalarField](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i0) |
| [arrayField](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1)  |

<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i0"></a>7.5.1.1.5.1.2.4.1.2.1.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > scalarField`

|                           |                                                                                                                                                                                                                                       |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Type**                  | `combining`                                                                                                                                                                                                                           |
| **Required**              | No                                                                                                                                                                                                                                    |
| **Additional properties** | Not allowed                                                                                                                                                                                                                           |
| **Same definition as**    | [definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties) |

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1"></a>7.5.1.1.5.1.2.4.1.2.1.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > arrayField`

|                           |                          |
| ------------------------- | ------------------------ |
| **Type**                  | `object`                 |
| **Required**              | No                       |
| **Additional properties** | Not allowed              |
| **Defined in**            | #/definitions/arrayField |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_type"></a>7.5.1.1.5.1.2.4.1.2.1.2.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > type</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_fixed"></a>7.5.1.1.5.1.2.4.1.2.1.2.2. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > fixed</strong>  

</summary>
<blockquote>

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `false`   |

**Description:** When true, the row count is set once from the data the form is initialized with and cannot be changed by the user — no add/remove controls are rendered.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_label"></a>7.5.1.1.5.1.2.4.1.2.1.2.3. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > label</strong>  

</summary>
<blockquote>

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Explicit display label for the array's section header. When omitted, the label is inferred from the field name.

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_fields"></a>7.5.1.1.5.1.2.4.1.2.1.2.4. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > fields</strong>  

</summary>
<blockquote>

|              |         |
| ------------ | ------- |
| **Type**     | `array` |
| **Required** | Yes     |

**Description:** Repeatable template containing scalar fields or rows. Nested arrays are not supported.

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | False              |
| **Tuple validation** | See below          |

| Each item of this array must be                                                                                                                   | Description |
| ------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| [fields items](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_fields_items) | -           |

###### <a name="autogenerated_heading_10"></a>7.5.1.1.5.1.2.4.1.2.1.2.4.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > fields > fields items

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `combining`      |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

<blockquote>

| One of(Option)                                                                                                                                                   |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [formRow](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_fields_items_oneOf_i0)            |
| [scalarFieldWrapper](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_fields_items_oneOf_i1) |

<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_fields_items_oneOf_i0"></a>7.5.1.1.5.1.2.4.1.2.1.2.4.1.1. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > fields > fields items > oneOf > formRow`

|                        |                                                                                                                                                                                 |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Type**               | `array`                                                                                                                                                                         |
| **Required**           | No                                                                                                                                                                              |
| **Same definition as** | [definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0) |

**Description:** Horizontal grouping of scalar fields. Rows are encoded directly as JSON arrays.

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i1_additionalProperties_oneOf_i1_fields_items_oneOf_i1"></a>7.5.1.1.5.1.2.4.1.2.1.2.4.1.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 0 > definition > fields > fields items > oneOf > item 1 > additionalProperties > oneOf > item 1 > fields > fields items > oneOf > scalarFieldWrapper`

|                           |                                                                                                                                                                                             |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                                                                                                                                    |
| **Required**              | No                                                                                                                                                                                          |
| **Additional properties** | [Each additional property must conform to the schema](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items_additionalProperties)                    |
| **Same definition as**    | [definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items](#definition_activities_items_oneOf_i0_action_oneOf_i0_definition_fields_items_oneOf_i0_items) |

**Description:** Single-key scalar field object. Used in rows and array templates.

</blockquote>

</blockquote>

</blockquote>
</details>

</blockquote>

</blockquote>

</blockquote>
</details>

</blockquote>

</blockquote>

</blockquote>
</details>

</blockquote>
</details>

</blockquote>
<blockquote>

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i1"></a>7.5.1.1.5.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > InstructionAction`

|                           |                                 |
| ------------------------- | ------------------------------- |
| **Type**                  | `object`                        |
| **Required**              | No                              |
| **Additional properties** | Not allowed                     |
| **Defined in**            | #/definitions/InstructionAction |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i1_type"></a>7.5.1.1.5.2.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 1 > type</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i1_instructions"></a>7.5.1.1.5.2.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 1 > instructions</strong>  

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

###### <a name="definition_activities_items_oneOf_i0_action_oneOf_i2"></a>7.5.1.1.5.3. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > ChoiceAction`

|                           |                            |
| ------------------------- | -------------------------- |
| **Type**                  | `object`                   |
| **Required**              | No                         |
| **Additional properties** | Not allowed                |
| **Defined in**            | #/definitions/ChoiceAction |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i2_type"></a>7.5.1.1.5.3.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 2 > type</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i2_prompt"></a>7.5.1.1.5.3.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 2 > prompt</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i2_options"></a>7.5.1.1.5.3.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 2 > options</strong>  

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

| Each item of this array must be                                                     | Description |
| ----------------------------------------------------------------------------------- | ----------- |
| [ChoiceOption](#definition_activities_items_oneOf_i0_action_oneOf_i2_options_items) | -           |

###### <a name="autogenerated_heading_11"></a>7.5.1.1.5.3.3.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 2 > options > ChoiceOption

|                           |                            |
| ------------------------- | -------------------------- |
| **Type**                  | `object`                   |
| **Required**              | No                         |
| **Additional properties** | Not allowed                |
| **Defined in**            | #/definitions/ChoiceOption |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i2_options_items_key"></a>7.5.1.1.5.3.3.1.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 2 > options > options items > key</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i0_action_oneOf_i2_options_items_label"></a>7.5.1.1.5.3.3.1.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > action > oneOf > item 2 > options > options items > label</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i0_required"></a>7.5.1.1.6. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > required</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i0_input"></a>7.5.1.1.7. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > input</strong>  

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

| Each item of this array must be                              | Description |
| ------------------------------------------------------------ | ----------- |
| [Mapping](#definition_activities_items_oneOf_i0_input_items) | -           |

###### <a name="autogenerated_heading_12"></a>7.5.1.1.7.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > input > Mapping

|                |                       |
| -------------- | --------------------- |
| **Type**       | `string`              |
| **Required**   | No                    |
| **Defined in** | #/definitions/Mapping |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i0_output"></a>7.5.1.1.8. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > output</strong>  

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

| Each item of this array must be                               | Description |
| ------------------------------------------------------------- | ----------- |
| [Mapping](#definition_activities_items_oneOf_i0_output_items) | -           |

###### <a name="autogenerated_heading_13"></a>7.5.1.1.8.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 0 > output > Mapping

|                        |                                                                                                       |
| ---------------------- | ----------------------------------------------------------------------------------------------------- |
| **Type**               | `string`                                                                                              |
| **Required**           | No                                                                                                    |
| **Same definition as** | [definition_activities_items_oneOf_i0_input_items](#definition_activities_items_oneOf_i0_input_items) |

</blockquote>
</details>

</blockquote>
<blockquote>

##### <a name="definition_activities_items_oneOf_i1"></a>7.5.1.2. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > SequenceActivity`

|                           |                                |
| ------------------------- | ------------------------------ |
| **Type**                  | `object`                       |
| **Required**              | No                             |
| **Additional properties** | Not allowed                    |
| **Defined in**            | #/definitions/SequenceActivity |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i1_type"></a>7.5.1.2.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 1 > type</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i1_id"></a>7.5.1.2.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 1 > id</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i1_name"></a>7.5.1.2.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 1 > name</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i1_description"></a>7.5.1.2.4. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 1 > description</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i1_activities"></a>7.5.1.2.5. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 1 > activities</strong>  

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

| Each item of this array must be                                    | Description |
| ------------------------------------------------------------------ | ----------- |
| [Activity](#definition_activities_items_oneOf_i1_activities_items) | -           |

###### <a name="autogenerated_heading_14"></a>7.5.1.2.5.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 1 > activities > Activity

|                           |                                                             |
| ------------------------- | ----------------------------------------------------------- |
| **Type**                  | `combining`                                                 |
| **Required**              | No                                                          |
| **Additional properties** | Any type allowed                                            |
| **Same definition as**    | [definition_activities_items](#definition_activities_items) |

</blockquote>
</details>

</blockquote>
<blockquote>

##### <a name="definition_activities_items_oneOf_i2"></a>7.5.1.3. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > DecisionActivity`

|                           |                                |
| ------------------------- | ------------------------------ |
| **Type**                  | `object`                       |
| **Required**              | No                             |
| **Additional properties** | Not allowed                    |
| **Defined in**            | #/definitions/DecisionActivity |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i2_type"></a>7.5.1.3.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > type</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i2_id"></a>7.5.1.3.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > id</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i2_expression"></a>7.5.1.3.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > expression</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i2_branches"></a>7.5.1.3.4. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > branches</strong>  

</summary>
<blockquote>

|                           |                                                                                                                            |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                                                                   |
| **Required**              | Yes                                                                                                                        |
| **Additional properties** | [Each additional property must conform to the schema](#definition_activities_items_oneOf_i2_branches_additionalProperties) |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i2_branches_additionalProperties"></a>7.5.1.3.4.1. Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > branches > Activity</strong>  

</summary>
<blockquote>

|                           |                                                             |
| ------------------------- | ----------------------------------------------------------- |
| **Type**                  | `combining`                                                 |
| **Required**              | No                                                          |
| **Additional properties** | Any type allowed                                            |
| **Same definition as**    | [definition_activities_items](#definition_activities_items) |

</blockquote>
</details>

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i2_name"></a>7.5.1.3.5. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > name</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i2_description"></a>7.5.1.3.6. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 2 > description</strong>  

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

##### <a name="definition_activities_items_oneOf_i3"></a>7.5.1.4. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > GroupActivity`

|                           |                             |
| ------------------------- | --------------------------- |
| **Type**                  | `object`                    |
| **Required**              | No                          |
| **Additional properties** | Not allowed                 |
| **Defined in**            | #/definitions/GroupActivity |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i3_type"></a>7.5.1.4.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 3 > type</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i3_id"></a>7.5.1.4.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 3 > id</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i3_name"></a>7.5.1.4.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 3 > name</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i3_description"></a>7.5.1.4.4. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 3 > description</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i3_activities"></a>7.5.1.4.5. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 3 > activities</strong>  

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

| Each item of this array must be                                    | Description |
| ------------------------------------------------------------------ | ----------- |
| [Activity](#definition_activities_items_oneOf_i3_activities_items) | -           |

###### <a name="autogenerated_heading_15"></a>7.5.1.4.5.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 3 > activities > Activity

|                           |                                                             |
| ------------------------- | ----------------------------------------------------------- |
| **Type**                  | `combining`                                                 |
| **Required**              | No                                                          |
| **Additional properties** | Any type allowed                                            |
| **Same definition as**    | [definition_activities_items](#definition_activities_items) |

</blockquote>
</details>

</blockquote>
<blockquote>

##### <a name="definition_activities_items_oneOf_i4"></a>7.5.1.5. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > ScriptActivity`

|                           |                              |
| ------------------------- | ---------------------------- |
| **Type**                  | `object`                     |
| **Required**              | No                           |
| **Additional properties** | Not allowed                  |
| **Defined in**            | #/definitions/ScriptActivity |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i4_type"></a>7.5.1.5.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > type</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i4_id"></a>7.5.1.5.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > id</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i4_name"></a>7.5.1.5.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > name</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i4_description"></a>7.5.1.5.4. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > description</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i4_script"></a>7.5.1.5.5. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > script</strong>  

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

| Each item of this array must be                                    | Description |
| ------------------------------------------------------------------ | ----------- |
| [script items](#definition_activities_items_oneOf_i4_script_items) | -           |

###### <a name="autogenerated_heading_16"></a>7.5.1.5.5.1. SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > script > script items

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i4_outputKey"></a>7.5.1.5.6. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 4 > outputKey</strong>  

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

##### <a name="definition_activities_items_oneOf_i5"></a>7.5.1.6. Property `SWAR Process Definition v2 > definition > activities > activities items > oneOf > HttpActivity`

|                           |                            |
| ------------------------- | -------------------------- |
| **Type**                  | `object`                   |
| **Required**              | No                         |
| **Additional properties** | Not allowed                |
| **Defined in**            | #/definitions/HttpActivity |

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i5_type"></a>7.5.1.6.1. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > type</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i5_id"></a>7.5.1.6.2. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > id</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i5_name"></a>7.5.1.6.3. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > name</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i5_description"></a>7.5.1.6.4. [Optional] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > description</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i5_urlExpression"></a>7.5.1.6.5. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > urlExpression</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i5_method"></a>7.5.1.6.6. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > method</strong>  

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
<strong> <a name="definition_activities_items_oneOf_i5_bodyExpression"></a>7.5.1.6.7. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > bodyExpression</strong>  

</summary>
<blockquote>

|              |                  |
| ------------ | ---------------- |
| **Type**     | `string or null` |
| **Required** | Yes              |

</blockquote>
</details>

<details>
<summary>
<strong> <a name="definition_activities_items_oneOf_i5_outputKey"></a>7.5.1.6.8. [Required] Property SWAR Process Definition v2 > definition > activities > activities items > oneOf > item 5 > outputKey</strong>  

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

</blockquote>
</details>

----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans) on 2026-08-24 at 15:43:35 +0000