[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Console

# Class: Console

[ue/ue](../modules/ue_ue.md).Console

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Console`**

## Table of contents

### Constructors

- [constructor](ue_ue.Console.md#constructor)

### Properties

- [ConsoleTargetPlayer](ue_ue.Console.md#consoletargetplayer)
- [DefaultTexture\_Black](ue_ue.Console.md#defaulttexture_black)
- [DefaultTexture\_White](ue_ue.Console.md#defaulttexture_white)
- [HistoryBuffer](ue_ue.Console.md#historybuffer)
- [\_\_tid\_Console\_\_](ue_ue.Console.md#__tid_console__)
- [\_\_tid\_Object\_\_](ue_ue.Console.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.Console.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Console.md#executeubergraph)
- [GetClass](ue_ue.Console.md#getclass)
- [GetName](ue_ue.Console.md#getname)
- [GetOuter](ue_ue.Console.md#getouter)
- [GetWorld](ue_ue.Console.md#getworld)
- [Find](ue_ue.Console.md#find)
- [Load](ue_ue.Console.md#load)
- [StaticClass](ue_ue.Console.md#staticclass)

## Constructors

### constructor

• **new Console**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ConsoleTargetPlayer

• **ConsoleTargetPlayer**: [`LocalPlayer`](ue_ue.LocalPlayer.md)

___

### DefaultTexture\_Black

• **DefaultTexture\_Black**: [`Texture2D`](ue_ue.Texture2D.md)

___

### DefaultTexture\_White

• **DefaultTexture\_White**: [`Texture2D`](ue_ue.Texture2D.md)

___

### HistoryBuffer

• **HistoryBuffer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### \_\_tid\_Console\_\_

• **\_\_tid\_Console\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Console`](ue_ue.Console.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Console`](ue_ue.Console.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Console`](ue_ue.Console.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Console`](ue_ue.Console.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
