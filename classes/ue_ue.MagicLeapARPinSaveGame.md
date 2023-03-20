[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapARPinSaveGame

# Class: MagicLeapARPinSaveGame

[ue/ue](../modules/ue_ue.md).MagicLeapARPinSaveGame

## Hierarchy

- [`SaveGame`](ue_ue.SaveGame.md)

  ↳ **`MagicLeapARPinSaveGame`**

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapARPinSaveGame.md#constructor)

### Properties

- [ComponentWorldTransform](ue_ue.MagicLeapARPinSaveGame.md#componentworldtransform)
- [PinTransform](ue_ue.MagicLeapARPinSaveGame.md#pintransform)
- [PinnedID](ue_ue.MagicLeapARPinSaveGame.md#pinnedid)
- [\_\_tid\_MagicLeapARPinSaveGame\_\_](ue_ue.MagicLeapARPinSaveGame.md#__tid_magicleaparpinsavegame__)
- [\_\_tid\_Object\_\_](ue_ue.MagicLeapARPinSaveGame.md#__tid_object__)
- [\_\_tid\_SaveGame\_\_](ue_ue.MagicLeapARPinSaveGame.md#__tid_savegame__)

### Methods

- [CreateDefaultSubobject](ue_ue.MagicLeapARPinSaveGame.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MagicLeapARPinSaveGame.md#executeubergraph)
- [GetClass](ue_ue.MagicLeapARPinSaveGame.md#getclass)
- [GetName](ue_ue.MagicLeapARPinSaveGame.md#getname)
- [GetOuter](ue_ue.MagicLeapARPinSaveGame.md#getouter)
- [GetWorld](ue_ue.MagicLeapARPinSaveGame.md#getworld)
- [Find](ue_ue.MagicLeapARPinSaveGame.md#find)
- [Load](ue_ue.MagicLeapARPinSaveGame.md#load)
- [StaticClass](ue_ue.MagicLeapARPinSaveGame.md#staticclass)

## Constructors

### constructor

• **new MagicLeapARPinSaveGame**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SaveGame](ue_ue.SaveGame.md).[constructor](ue_ue.SaveGame.md#constructor)

## Properties

### ComponentWorldTransform

• **ComponentWorldTransform**: [`Transform`](ue_ue_s.Transform.md)

___

### PinTransform

• **PinTransform**: [`Transform`](ue_ue_s.Transform.md)

___

### PinnedID

• **PinnedID**: [`Guid`](ue_ue_s.Guid.md)

___

### \_\_tid\_MagicLeapARPinSaveGame\_\_

• **\_\_tid\_MagicLeapARPinSaveGame\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SaveGame](ue_ue.SaveGame.md).[__tid_Object__](ue_ue.SaveGame.md#__tid_object__)

___

### \_\_tid\_SaveGame\_\_

• **\_\_tid\_SaveGame\_\_**: `boolean`

#### Inherited from

[SaveGame](ue_ue.SaveGame.md).[__tid_SaveGame__](ue_ue.SaveGame.md#__tid_savegame__)

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

[SaveGame](ue_ue.SaveGame.md).[CreateDefaultSubobject](ue_ue.SaveGame.md#createdefaultsubobject)

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

[SaveGame](ue_ue.SaveGame.md).[ExecuteUbergraph](ue_ue.SaveGame.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SaveGame](ue_ue.SaveGame.md).[GetClass](ue_ue.SaveGame.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SaveGame](ue_ue.SaveGame.md).[GetName](ue_ue.SaveGame.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SaveGame](ue_ue.SaveGame.md).[GetOuter](ue_ue.SaveGame.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SaveGame](ue_ue.SaveGame.md).[GetWorld](ue_ue.SaveGame.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MagicLeapARPinSaveGame`](ue_ue.MagicLeapARPinSaveGame.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MagicLeapARPinSaveGame`](ue_ue.MagicLeapARPinSaveGame.md)

#### Overrides

[SaveGame](ue_ue.SaveGame.md).[Find](ue_ue.SaveGame.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MagicLeapARPinSaveGame`](ue_ue.MagicLeapARPinSaveGame.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MagicLeapARPinSaveGame`](ue_ue.MagicLeapARPinSaveGame.md)

#### Overrides

[SaveGame](ue_ue.SaveGame.md).[Load](ue_ue.SaveGame.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SaveGame](ue_ue.SaveGame.md).[StaticClass](ue_ue.SaveGame.md#staticclass)
