[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PlayerInput

# Class: PlayerInput

[ue/ue](../modules/ue_ue.md).PlayerInput

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PlayerInput`**

## Table of contents

### Constructors

- [constructor](ue_ue.PlayerInput.md#constructor)

### Properties

- [DebugExecBindings](ue_ue.PlayerInput.md#debugexecbindings)
- [InvertedAxis](ue_ue.PlayerInput.md#invertedaxis)
- [\_\_tid\_Object\_\_](ue_ue.PlayerInput.md#__tid_object__)
- [\_\_tid\_PlayerInput\_\_](ue_ue.PlayerInput.md#__tid_playerinput__)

### Methods

- [ClearSmoothing](ue_ue.PlayerInput.md#clearsmoothing)
- [CreateDefaultSubobject](ue_ue.PlayerInput.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PlayerInput.md#executeubergraph)
- [GetClass](ue_ue.PlayerInput.md#getclass)
- [GetName](ue_ue.PlayerInput.md#getname)
- [GetOuter](ue_ue.PlayerInput.md#getouter)
- [GetWorld](ue_ue.PlayerInput.md#getworld)
- [InvertAxis](ue_ue.PlayerInput.md#invertaxis)
- [InvertAxisKey](ue_ue.PlayerInput.md#invertaxiskey)
- [SetBind](ue_ue.PlayerInput.md#setbind)
- [SetMouseSensitivity](ue_ue.PlayerInput.md#setmousesensitivity)
- [Find](ue_ue.PlayerInput.md#find)
- [Load](ue_ue.PlayerInput.md#load)
- [StaticClass](ue_ue.PlayerInput.md#staticclass)

## Constructors

### constructor

• **new PlayerInput**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### DebugExecBindings

• **DebugExecBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`KeyBind`](ue_ue.KeyBind.md)\>

___

### InvertedAxis

• **InvertedAxis**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PlayerInput\_\_

• **\_\_tid\_PlayerInput\_\_**: `boolean`

## Methods

### ClearSmoothing

▸ **ClearSmoothing**(): `void`

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

### InvertAxis

▸ **InvertAxis**(`AxisName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AxisName` | `string` |

#### Returns

`void`

___

### InvertAxisKey

▸ **InvertAxisKey**(`AxisKey`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AxisKey` | [`Key`](ue_ue.Key.md) |

#### Returns

`void`

___

### SetBind

▸ **SetBind**(`BindName`, `Command`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BindName` | `string` |
| `Command` | `string` |

#### Returns

`void`

___

### SetMouseSensitivity

▸ **SetMouseSensitivity**(`Sensitivity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Sensitivity` | `number` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PlayerInput`](ue_ue.PlayerInput.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PlayerInput`](ue_ue.PlayerInput.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PlayerInput`](ue_ue.PlayerInput.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PlayerInput`](ue_ue.PlayerInput.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
