[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ConsoleSettings

# Class: ConsoleSettings

[ue/ue](../modules/ue_ue.md).ConsoleSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ConsoleSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.ConsoleSettings.md#constructor)

### Properties

- [AutoCompleteCVarColor](ue_ue.ConsoleSettings.md#autocompletecvarcolor)
- [AutoCompleteCommandColor](ue_ue.ConsoleSettings.md#autocompletecommandcolor)
- [AutoCompleteFadedColor](ue_ue.ConsoleSettings.md#autocompletefadedcolor)
- [AutoCompleteMapPaths](ue_ue.ConsoleSettings.md#autocompletemappaths)
- [BackgroundOpacityPercentage](ue_ue.ConsoleSettings.md#backgroundopacitypercentage)
- [HistoryColor](ue_ue.ConsoleSettings.md#historycolor)
- [InputColor](ue_ue.ConsoleSettings.md#inputcolor)
- [ManualAutoCompleteList](ue_ue.ConsoleSettings.md#manualautocompletelist)
- [MaxScrollbackSize](ue_ue.ConsoleSettings.md#maxscrollbacksize)
- [\_\_tid\_ConsoleSettings\_\_](ue_ue.ConsoleSettings.md#__tid_consolesettings__)
- [\_\_tid\_Object\_\_](ue_ue.ConsoleSettings.md#__tid_object__)
- [bDisplayHelpInAutoComplete](ue_ue.ConsoleSettings.md#bdisplayhelpinautocomplete)
- [bOrderTopToBottom](ue_ue.ConsoleSettings.md#bordertoptobottom)

### Methods

- [CreateDefaultSubobject](ue_ue.ConsoleSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ConsoleSettings.md#executeubergraph)
- [GetClass](ue_ue.ConsoleSettings.md#getclass)
- [GetName](ue_ue.ConsoleSettings.md#getname)
- [GetOuter](ue_ue.ConsoleSettings.md#getouter)
- [GetWorld](ue_ue.ConsoleSettings.md#getworld)
- [Find](ue_ue.ConsoleSettings.md#find)
- [Load](ue_ue.ConsoleSettings.md#load)
- [StaticClass](ue_ue.ConsoleSettings.md#staticclass)

## Constructors

### constructor

• **new ConsoleSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AutoCompleteCVarColor

• **AutoCompleteCVarColor**: [`Color`](ue_ue_s.Color.md)

___

### AutoCompleteCommandColor

• **AutoCompleteCommandColor**: [`Color`](ue_ue_s.Color.md)

___

### AutoCompleteFadedColor

• **AutoCompleteFadedColor**: [`Color`](ue_ue_s.Color.md)

___

### AutoCompleteMapPaths

• **AutoCompleteMapPaths**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### BackgroundOpacityPercentage

• **BackgroundOpacityPercentage**: `number`

___

### HistoryColor

• **HistoryColor**: [`Color`](ue_ue_s.Color.md)

___

### InputColor

• **InputColor**: [`Color`](ue_ue_s.Color.md)

___

### ManualAutoCompleteList

• **ManualAutoCompleteList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AutoCompleteCommand`](ue_ue.AutoCompleteCommand.md)\>

___

### MaxScrollbackSize

• **MaxScrollbackSize**: `number`

___

### \_\_tid\_ConsoleSettings\_\_

• **\_\_tid\_ConsoleSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bDisplayHelpInAutoComplete

• **bDisplayHelpInAutoComplete**: `boolean`

___

### bOrderTopToBottom

• **bOrderTopToBottom**: `boolean`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ConsoleSettings`](ue_ue.ConsoleSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ConsoleSettings`](ue_ue.ConsoleSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ConsoleSettings`](ue_ue.ConsoleSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ConsoleSettings`](ue_ue.ConsoleSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
