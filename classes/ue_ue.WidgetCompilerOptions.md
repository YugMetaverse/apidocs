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

#### Defined in

[ue/ue.d.ts:64429](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64429)

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

#### Defined in

[ue/ue.d.ts:64430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64430)

## Properties

### PropertyBindingRule

• **PropertyBindingRule**: [`EPropertyBindingPermissionLevel`](../enums/ue_ue.EPropertyBindingPermissionLevel.md)

#### Defined in

[ue/ue.d.ts:64435](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64435)

___

### Rules

• **Rules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`WidgetCompilerRule`](ue_ue.WidgetCompilerRule.md)\>\>

#### Defined in

[ue/ue.d.ts:64436](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64436)

___

### \_\_tid\_WidgetCompilerOptions\_\_

• `Private` **\_\_tid\_WidgetCompilerOptions\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64442](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64442)

___

### bAllowBlueprintPaint

• **bAllowBlueprintPaint**: `boolean`

#### Defined in

[ue/ue.d.ts:64434](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64434)

___

### bAllowBlueprintTick

• **bAllowBlueprintTick**: `boolean`

#### Defined in

[ue/ue.d.ts:64433](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64433)

___

### bCookSlowConstructionWidgetTree

• **bCookSlowConstructionWidgetTree**: `boolean`

#### Defined in

[ue/ue.d.ts:64431](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64431)

___

### bWidgetSupportsDynamicCreation

• **bWidgetSupportsDynamicCreation**: `boolean`

#### Defined in

[ue/ue.d.ts:64432](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64432)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:64440](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64440)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:64441](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64441)
