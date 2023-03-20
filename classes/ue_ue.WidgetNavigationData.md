[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WidgetNavigationData

# Class: WidgetNavigationData

[ue/ue](../modules/ue_ue.md).WidgetNavigationData

## Table of contents

### Constructors

- [constructor](ue_ue.WidgetNavigationData.md#constructor)

### Properties

- [CustomDelegate](ue_ue.WidgetNavigationData.md#customdelegate)
- [Rule](ue_ue.WidgetNavigationData.md#rule)
- [Widget](ue_ue.WidgetNavigationData.md#widget)
- [WidgetToFocus](ue_ue.WidgetNavigationData.md#widgettofocus)
- [\_\_tid\_WidgetNavigationData\_\_](ue_ue.WidgetNavigationData.md#__tid_widgetnavigationdata__)

### Methods

- [StaticClass](ue_ue.WidgetNavigationData.md#staticclass)
- [StaticStruct](ue_ue.WidgetNavigationData.md#staticstruct)

## Constructors

### constructor

• **new WidgetNavigationData**()

#### Defined in

[ue/ue.d.ts:10745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10745)

• **new WidgetNavigationData**(`Rule`, `WidgetToFocus`, `Widget`, `CustomDelegate`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rule` | [`EUINavigationRule`](../enums/ue_ue.EUINavigationRule.md) |
| `WidgetToFocus` | `string` |
| `Widget` | [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Widget`](ue_ue.Widget.md)\> |
| `CustomDelegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Navigation`: [`EUINavigation`](../enums/ue_ue.EUINavigation.md)) => [`Widget`](ue_ue.Widget.md)\> |

#### Defined in

[ue/ue.d.ts:10746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10746)

## Properties

### CustomDelegate

• **CustomDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Navigation`: [`EUINavigation`](../enums/ue_ue.EUINavigation.md)) => [`Widget`](ue_ue.Widget.md)\>

#### Defined in

[ue/ue.d.ts:10750](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10750)

___

### Rule

• **Rule**: [`EUINavigationRule`](../enums/ue_ue.EUINavigationRule.md)

#### Defined in

[ue/ue.d.ts:10747](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10747)

___

### Widget

• **Widget**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Widget`](ue_ue.Widget.md)\>

#### Defined in

[ue/ue.d.ts:10749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10749)

___

### WidgetToFocus

• **WidgetToFocus**: `string`

#### Defined in

[ue/ue.d.ts:10748](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10748)

___

### \_\_tid\_WidgetNavigationData\_\_

• `Private` **\_\_tid\_WidgetNavigationData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:10756](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10756)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:10754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10754)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:10755](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10755)