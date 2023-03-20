[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WidgetCompilerOptions

# Class: WidgetCompilerOptions

[ue/ue](../modules/ue_ue.md).WidgetCompilerOptions

## Table of contents

### Constructors

- [constructor](ue_ue.WidgetCompilerOptions.md#constructor)

### Properties

- [PropertyBindingRule](ue_ue.WidgetCompilerOptions.md#propertybindingrule)
- [Rules](ue_ue.WidgetCompilerOptions.md#rules)
- [\_\_tid\_WidgetCompilerOptions\_\_](ue_ue.WidgetCompilerOptions.md#__tid_widgetcompileroptions__)
- [bAllowBlueprintPaint](ue_ue.WidgetCompilerOptions.md#ballowblueprintpaint)
- [bAllowBlueprintTick](ue_ue.WidgetCompilerOptions.md#ballowblueprinttick)
- [bCookSlowConstructionWidgetTree](ue_ue.WidgetCompilerOptions.md#bcookslowconstructionwidgettree)
- [bWidgetSupportsDynamicCreation](ue_ue.WidgetCompilerOptions.md#bwidgetsupportsdynamiccreation)

### Methods

- [StaticClass](ue_ue.WidgetCompilerOptions.md#staticclass)
- [StaticStruct](ue_ue.WidgetCompilerOptions.md#staticstruct)

## Constructors

### constructor

• **new WidgetCompilerOptions**()

• **new WidgetCompilerOptions**(`bCookSlowConstructionWidgetTree`, `bWidgetSupportsDynamicCreation`, `bAllowBlueprintTick`, `bAllowBlueprintPaint`, `PropertyBindingRule`, `Rules`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `bCookSlowConstructionWidgetTree` | `boolean` |
| `bWidgetSupportsDynamicCreation` | `boolean` |
| `bAllowBlueprintTick` | `boolean` |
| `bAllowBlueprintPaint` | `boolean` |
| `PropertyBindingRule` | [`EPropertyBindingPermissionLevel`](../enums/ue_ue.EPropertyBindingPermissionLevel.md) |
| `Rules` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`WidgetCompilerRule`](ue_ue.WidgetCompilerRule.md)\>\> |

## Properties

### PropertyBindingRule

• **PropertyBindingRule**: [`EPropertyBindingPermissionLevel`](../enums/ue_ue.EPropertyBindingPermissionLevel.md)

___

### Rules

• **Rules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`WidgetCompilerRule`](ue_ue.WidgetCompilerRule.md)\>\>

___

### \_\_tid\_WidgetCompilerOptions\_\_

• `Private` **\_\_tid\_WidgetCompilerOptions\_\_**: `boolean`

___

### bAllowBlueprintPaint

• **bAllowBlueprintPaint**: `boolean`

___

### bAllowBlueprintTick

• **bAllowBlueprintTick**: `boolean`

___

### bCookSlowConstructionWidgetTree

• **bCookSlowConstructionWidgetTree**: `boolean`

___

### bWidgetSupportsDynamicCreation

• **bWidgetSupportsDynamicCreation**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
