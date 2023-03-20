[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ToolMenuEntryScript

# Class: ToolMenuEntryScript

[ue/ue](../modules/ue_ue.md).ToolMenuEntryScript

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ToolMenuEntryScript`**

## Table of contents

### Constructors

- [constructor](ue_ue.ToolMenuEntryScript.md#constructor)

### Properties

- [Data](ue_ue.ToolMenuEntryScript.md#data)
- [\_\_tid\_Object\_\_](ue_ue.ToolMenuEntryScript.md#__tid_object__)
- [\_\_tid\_ToolMenuEntryScript\_\_](ue_ue.ToolMenuEntryScript.md#__tid_toolmenuentryscript__)

### Methods

- [CanExecute](ue_ue.ToolMenuEntryScript.md#canexecute)
- [ConstructMenuEntry](ue_ue.ToolMenuEntryScript.md#constructmenuentry)
- [CreateDefaultSubobject](ue_ue.ToolMenuEntryScript.md#createdefaultsubobject)
- [Execute](ue_ue.ToolMenuEntryScript.md#execute)
- [ExecuteUbergraph](ue_ue.ToolMenuEntryScript.md#executeubergraph)
- [GetCheckState](ue_ue.ToolMenuEntryScript.md#getcheckstate)
- [GetClass](ue_ue.ToolMenuEntryScript.md#getclass)
- [GetIcon](ue_ue.ToolMenuEntryScript.md#geticon)
- [GetLabel](ue_ue.ToolMenuEntryScript.md#getlabel)
- [GetName](ue_ue.ToolMenuEntryScript.md#getname)
- [GetOuter](ue_ue.ToolMenuEntryScript.md#getouter)
- [GetToolTip](ue_ue.ToolMenuEntryScript.md#gettooltip)
- [GetWorld](ue_ue.ToolMenuEntryScript.md#getworld)
- [InitEntry](ue_ue.ToolMenuEntryScript.md#initentry)
- [IsVisible](ue_ue.ToolMenuEntryScript.md#isvisible)
- [RegisterMenuEntry](ue_ue.ToolMenuEntryScript.md#registermenuentry)
- [Find](ue_ue.ToolMenuEntryScript.md#find)
- [Load](ue_ue.ToolMenuEntryScript.md#load)
- [StaticClass](ue_ue.ToolMenuEntryScript.md#staticclass)

## Constructors

### constructor

• **new ToolMenuEntryScript**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Data

• **Data**: [`ToolMenuEntryScriptData`](ue_ue.ToolMenuEntryScriptData.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_ToolMenuEntryScript\_\_

• **\_\_tid\_ToolMenuEntryScript\_\_**: `boolean`

## Methods

### CanExecute

▸ **CanExecute**(`Context`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Context` | [`ToolMenuContext`](ue_ue.ToolMenuContext.md) |

#### Returns

`boolean`

___

### ConstructMenuEntry

▸ **ConstructMenuEntry**(`Menu`, `SectionName`, `Context`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Menu` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ToolMenu`](ue_ue.ToolMenu.md)\> |
| `SectionName` | `string` |
| `Context` | [`ToolMenuContext`](ue_ue.ToolMenuContext.md) |

#### Returns

`void`

___

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

___

### Execute

▸ **Execute**(`Context`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Context` | [`ToolMenuContext`](ue_ue.ToolMenuContext.md) |

#### Returns

`void`

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetCheckState

▸ **GetCheckState**(`Context`): [`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Context` | [`ToolMenuContext`](ue_ue.ToolMenuContext.md) |

#### Returns

[`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetIcon

▸ **GetIcon**(`Context`): [`ScriptSlateIcon`](ue_ue.ScriptSlateIcon.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Context` | [`ToolMenuContext`](ue_ue.ToolMenuContext.md) |

#### Returns

[`ScriptSlateIcon`](ue_ue.ScriptSlateIcon.md)

___

### GetLabel

▸ **GetLabel**(`Context`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Context` | [`ToolMenuContext`](ue_ue.ToolMenuContext.md) |

#### Returns

`string`

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetToolTip

▸ **GetToolTip**(`Context`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Context` | [`ToolMenuContext`](ue_ue.ToolMenuContext.md) |

#### Returns

`string`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### InitEntry

▸ **InitEntry**(`OwnerName`, `Menu`, `Section`, `Name`, `Label?`, `ToolTip?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerName` | `string` |
| `Menu` | `string` |
| `Section` | `string` |
| `Name` | `string` |
| `Label?` | `string` |
| `ToolTip?` | `string` |

#### Returns

`void`

___

### IsVisible

▸ **IsVisible**(`Context`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Context` | [`ToolMenuContext`](ue_ue.ToolMenuContext.md) |

#### Returns

`boolean`

___

### RegisterMenuEntry

▸ **RegisterMenuEntry**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ToolMenuEntryScript`](ue_ue.ToolMenuEntryScript.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ToolMenuEntryScript`](ue_ue.ToolMenuEntryScript.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ToolMenuEntryScript`](ue_ue.ToolMenuEntryScript.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ToolMenuEntryScript`](ue_ue.ToolMenuEntryScript.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
