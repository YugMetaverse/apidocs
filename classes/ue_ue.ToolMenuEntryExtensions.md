[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ToolMenuEntryExtensions

# Class: ToolMenuEntryExtensions

[ue/ue](../modules/ue_ue.md).ToolMenuEntryExtensions

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ToolMenuEntryExtensions`**

## Table of contents

### Constructors

- [constructor](ue_ue.ToolMenuEntryExtensions.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.ToolMenuEntryExtensions.md#__tid_object__)
- [\_\_tid\_ToolMenuEntryExtensions\_\_](ue_ue.ToolMenuEntryExtensions.md#__tid_toolmenuentryextensions__)

### Methods

- [CreateDefaultSubobject](ue_ue.ToolMenuEntryExtensions.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ToolMenuEntryExtensions.md#executeubergraph)
- [GetClass](ue_ue.ToolMenuEntryExtensions.md#getclass)
- [GetName](ue_ue.ToolMenuEntryExtensions.md#getname)
- [GetOuter](ue_ue.ToolMenuEntryExtensions.md#getouter)
- [GetWorld](ue_ue.ToolMenuEntryExtensions.md#getworld)
- [BreakScriptSlateIcon](ue_ue.ToolMenuEntryExtensions.md#breakscriptslateicon)
- [BreakStringCommand](ue_ue.ToolMenuEntryExtensions.md#breakstringcommand)
- [BreakToolMenuOwner](ue_ue.ToolMenuEntryExtensions.md#breaktoolmenuowner)
- [Find](ue_ue.ToolMenuEntryExtensions.md#find)
- [GetLabel](ue_ue.ToolMenuEntryExtensions.md#getlabel)
- [GetToolTip](ue_ue.ToolMenuEntryExtensions.md#gettooltip)
- [InitMenuEntry](ue_ue.ToolMenuEntryExtensions.md#initmenuentry)
- [Load](ue_ue.ToolMenuEntryExtensions.md#load)
- [MakeScriptSlateIcon](ue_ue.ToolMenuEntryExtensions.md#makescriptslateicon)
- [MakeStringCommand](ue_ue.ToolMenuEntryExtensions.md#makestringcommand)
- [MakeToolMenuOwner](ue_ue.ToolMenuEntryExtensions.md#maketoolmenuowner)
- [SetIcon](ue_ue.ToolMenuEntryExtensions.md#seticon)
- [SetLabel](ue_ue.ToolMenuEntryExtensions.md#setlabel)
- [SetStringCommand](ue_ue.ToolMenuEntryExtensions.md#setstringcommand)
- [SetToolTip](ue_ue.ToolMenuEntryExtensions.md#settooltip)
- [StaticClass](ue_ue.ToolMenuEntryExtensions.md#staticclass)

## Constructors

### constructor

• **new ToolMenuEntryExtensions**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_ToolMenuEntryExtensions\_\_

• **\_\_tid\_ToolMenuEntryExtensions\_\_**: `boolean`

## Methods

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

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

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

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### BreakScriptSlateIcon

▸ `Static` **BreakScriptSlateIcon**(`InValue`, `StyleSetName`, `StyleName`, `SmallStyleName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InValue` | [`ScriptSlateIcon`](ue_ue.ScriptSlateIcon.md) |
| `StyleSetName` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `StyleName` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `SmallStyleName` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

___

### BreakStringCommand

▸ `Static` **BreakStringCommand**(`InValue`, `Type`, `CustomType`, `String`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InValue` | [`ToolMenuStringCommand`](ue_ue.ToolMenuStringCommand.md) |
| `Type` | [`$Ref`](../interfaces/puerts._Ref.md)<[`EToolMenuStringCommandType`](../enums/ue_ue.EToolMenuStringCommandType.md)\> |
| `CustomType` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `String` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

___

### BreakToolMenuOwner

▸ `Static` **BreakToolMenuOwner**(`InValue`, `Name`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InValue` | [`ToolMenuOwner`](ue_ue.ToolMenuOwner.md) |
| `Name` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ToolMenuEntryExtensions`](ue_ue.ToolMenuEntryExtensions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ToolMenuEntryExtensions`](ue_ue.ToolMenuEntryExtensions.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### GetLabel

▸ `Static` **GetLabel**(`Target`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Target` | [`ToolMenuEntry`](ue_ue.ToolMenuEntry.md) |

#### Returns

`string`

___

### GetToolTip

▸ `Static` **GetToolTip**(`Target`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Target` | [`ToolMenuEntry`](ue_ue.ToolMenuEntry.md) |

#### Returns

`string`

___

### InitMenuEntry

▸ `Static` **InitMenuEntry**(`InOwner`, `InName`, `InLabel`, `InToolTip`, `CommandType`, `CustomCommandType`, `CommandString`): [`ToolMenuEntry`](ue_ue.ToolMenuEntry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOwner` | `string` |
| `InName` | `string` |
| `InLabel` | `string` |
| `InToolTip` | `string` |
| `CommandType` | [`EToolMenuStringCommandType`](../enums/ue_ue.EToolMenuStringCommandType.md) |
| `CustomCommandType` | `string` |
| `CommandString` | `string` |

#### Returns

[`ToolMenuEntry`](ue_ue.ToolMenuEntry.md)

___

### Load

▸ `Static` **Load**(`InName`): [`ToolMenuEntryExtensions`](ue_ue.ToolMenuEntryExtensions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ToolMenuEntryExtensions`](ue_ue.ToolMenuEntryExtensions.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### MakeScriptSlateIcon

▸ `Static` **MakeScriptSlateIcon**(`StyleSetName`, `StyleName`, `SmallStyleName?`): [`ScriptSlateIcon`](ue_ue.ScriptSlateIcon.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `StyleSetName` | `string` |
| `StyleName` | `string` |
| `SmallStyleName?` | `string` |

#### Returns

[`ScriptSlateIcon`](ue_ue.ScriptSlateIcon.md)

___

### MakeStringCommand

▸ `Static` **MakeStringCommand**(`Type`, `CustomType`, `String`): [`ToolMenuStringCommand`](ue_ue.ToolMenuStringCommand.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Type` | [`EToolMenuStringCommandType`](../enums/ue_ue.EToolMenuStringCommandType.md) |
| `CustomType` | `string` |
| `String` | `string` |

#### Returns

[`ToolMenuStringCommand`](ue_ue.ToolMenuStringCommand.md)

___

### MakeToolMenuOwner

▸ `Static` **MakeToolMenuOwner**(`Name`): [`ToolMenuOwner`](ue_ue.ToolMenuOwner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

[`ToolMenuOwner`](ue_ue.ToolMenuOwner.md)

___

### SetIcon

▸ `Static` **SetIcon**(`Target`, `StyleSetName`, `StyleName?`, `SmallStyleName?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Target` | [`$Ref`](../interfaces/puerts._Ref.md)<[`ToolMenuEntry`](ue_ue.ToolMenuEntry.md)\> |
| `StyleSetName` | `string` |
| `StyleName?` | `string` |
| `SmallStyleName?` | `string` |

#### Returns

`void`

___

### SetLabel

▸ `Static` **SetLabel**(`Target`, `Label`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Target` | [`$Ref`](../interfaces/puerts._Ref.md)<[`ToolMenuEntry`](ue_ue.ToolMenuEntry.md)\> |
| `Label` | `string` |

#### Returns

`void`

___

### SetStringCommand

▸ `Static` **SetStringCommand**(`Target`, `Type`, `CustomType`, `String`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Target` | [`$Ref`](../interfaces/puerts._Ref.md)<[`ToolMenuEntry`](ue_ue.ToolMenuEntry.md)\> |
| `Type` | [`EToolMenuStringCommandType`](../enums/ue_ue.EToolMenuStringCommandType.md) |
| `CustomType` | `string` |
| `String` | `string` |

#### Returns

`void`

___

### SetToolTip

▸ `Static` **SetToolTip**(`Target`, `ToolTip`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Target` | [`$Ref`](../interfaces/puerts._Ref.md)<[`ToolMenuEntry`](ue_ue.ToolMenuEntry.md)\> |
| `ToolTip` | `string` |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
