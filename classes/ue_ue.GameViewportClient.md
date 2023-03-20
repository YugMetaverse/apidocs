[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameViewportClient

# Class: GameViewportClient

[ue/ue](../modules/ue_ue.md).GameViewportClient

## Hierarchy

- [`ScriptViewportClient`](ue_ue.ScriptViewportClient.md)

  ↳ **`GameViewportClient`**

## Table of contents

### Constructors

- [constructor](ue_ue.GameViewportClient.md#constructor)

### Properties

- [DebugProperties](ue_ue.GameViewportClient.md#debugproperties)
- [GameInstance](ue_ue.GameViewportClient.md#gameinstance)
- [ViewportConsole](ue_ue.GameViewportClient.md#viewportconsole)
- [World](ue_ue.GameViewportClient.md#world)
- [\_\_tid\_GameViewportClient\_\_](ue_ue.GameViewportClient.md#__tid_gameviewportclient__)
- [\_\_tid\_Object\_\_](ue_ue.GameViewportClient.md#__tid_object__)
- [\_\_tid\_ScriptViewportClient\_\_](ue_ue.GameViewportClient.md#__tid_scriptviewportclient__)

### Methods

- [CreateDefaultSubobject](ue_ue.GameViewportClient.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GameViewportClient.md#executeubergraph)
- [GetClass](ue_ue.GameViewportClient.md#getclass)
- [GetName](ue_ue.GameViewportClient.md#getname)
- [GetOuter](ue_ue.GameViewportClient.md#getouter)
- [GetWorld](ue_ue.GameViewportClient.md#getworld)
- [SSSwapControllers](ue_ue.GameViewportClient.md#ssswapcontrollers)
- [SetConsoleTarget](ue_ue.GameViewportClient.md#setconsoletarget)
- [ShowTitleSafeArea](ue_ue.GameViewportClient.md#showtitlesafearea)
- [Find](ue_ue.GameViewportClient.md#find)
- [Load](ue_ue.GameViewportClient.md#load)
- [StaticClass](ue_ue.GameViewportClient.md#staticclass)

## Constructors

### constructor

• **new GameViewportClient**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ScriptViewportClient](ue_ue.ScriptViewportClient.md).[constructor](ue_ue.ScriptViewportClient.md#constructor)

## Properties

### DebugProperties

• **DebugProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DebugDisplayProperty`](ue_ue.DebugDisplayProperty.md)\>

___

### GameInstance

• **GameInstance**: [`GameInstance`](ue_ue.GameInstance.md)

___

### ViewportConsole

• **ViewportConsole**: [`Console`](ue_ue.Console.md)

___

### World

• **World**: [`World`](ue_ue.World.md)

___

### \_\_tid\_GameViewportClient\_\_

• **\_\_tid\_GameViewportClient\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ScriptViewportClient](ue_ue.ScriptViewportClient.md).[__tid_Object__](ue_ue.ScriptViewportClient.md#__tid_object__)

___

### \_\_tid\_ScriptViewportClient\_\_

• **\_\_tid\_ScriptViewportClient\_\_**: `boolean`

#### Inherited from

[ScriptViewportClient](ue_ue.ScriptViewportClient.md).[__tid_ScriptViewportClient__](ue_ue.ScriptViewportClient.md#__tid_scriptviewportclient__)

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

[ScriptViewportClient](ue_ue.ScriptViewportClient.md).[CreateDefaultSubobject](ue_ue.ScriptViewportClient.md#createdefaultsubobject)

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

[ScriptViewportClient](ue_ue.ScriptViewportClient.md).[ExecuteUbergraph](ue_ue.ScriptViewportClient.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ScriptViewportClient](ue_ue.ScriptViewportClient.md).[GetClass](ue_ue.ScriptViewportClient.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ScriptViewportClient](ue_ue.ScriptViewportClient.md).[GetName](ue_ue.ScriptViewportClient.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ScriptViewportClient](ue_ue.ScriptViewportClient.md).[GetOuter](ue_ue.ScriptViewportClient.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ScriptViewportClient](ue_ue.ScriptViewportClient.md).[GetWorld](ue_ue.ScriptViewportClient.md#getworld)

___

### SSSwapControllers

▸ **SSSwapControllers**(): `void`

#### Returns

`void`

___

### SetConsoleTarget

▸ **SetConsoleTarget**(`PlayerIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerIndex` | `number` |

#### Returns

`void`

___

### ShowTitleSafeArea

▸ **ShowTitleSafeArea**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameViewportClient`](ue_ue.GameViewportClient.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameViewportClient`](ue_ue.GameViewportClient.md)

#### Overrides

[ScriptViewportClient](ue_ue.ScriptViewportClient.md).[Find](ue_ue.ScriptViewportClient.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GameViewportClient`](ue_ue.GameViewportClient.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameViewportClient`](ue_ue.GameViewportClient.md)

#### Overrides

[ScriptViewportClient](ue_ue.ScriptViewportClient.md).[Load](ue_ue.ScriptViewportClient.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ScriptViewportClient](ue_ue.ScriptViewportClient.md).[StaticClass](ue_ue.ScriptViewportClient.md#staticclass)
