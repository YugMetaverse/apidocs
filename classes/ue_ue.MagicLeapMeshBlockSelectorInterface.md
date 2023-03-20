[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapMeshBlockSelectorInterface

# Class: MagicLeapMeshBlockSelectorInterface

[ue/ue](../modules/ue_ue.md).MagicLeapMeshBlockSelectorInterface

## Hierarchy

- [`Interface`](ue_ue.Interface.md)

  ↳ **`MagicLeapMeshBlockSelectorInterface`**

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapMeshBlockSelectorInterface.md#constructor)

### Properties

- [\_\_tid\_Interface\_\_](ue_ue.MagicLeapMeshBlockSelectorInterface.md#__tid_interface__)
- [\_\_tid\_MagicLeapMeshBlockSelectorInterface\_\_](ue_ue.MagicLeapMeshBlockSelectorInterface.md#__tid_magicleapmeshblockselectorinterface__)
- [\_\_tid\_Object\_\_](ue_ue.MagicLeapMeshBlockSelectorInterface.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MagicLeapMeshBlockSelectorInterface.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MagicLeapMeshBlockSelectorInterface.md#executeubergraph)
- [GetClass](ue_ue.MagicLeapMeshBlockSelectorInterface.md#getclass)
- [GetName](ue_ue.MagicLeapMeshBlockSelectorInterface.md#getname)
- [GetOuter](ue_ue.MagicLeapMeshBlockSelectorInterface.md#getouter)
- [GetWorld](ue_ue.MagicLeapMeshBlockSelectorInterface.md#getworld)
- [SelectMeshBlocks](ue_ue.MagicLeapMeshBlockSelectorInterface.md#selectmeshblocks)
- [Find](ue_ue.MagicLeapMeshBlockSelectorInterface.md#find)
- [Load](ue_ue.MagicLeapMeshBlockSelectorInterface.md#load)
- [StaticClass](ue_ue.MagicLeapMeshBlockSelectorInterface.md#staticclass)

## Constructors

### constructor

• **new MagicLeapMeshBlockSelectorInterface**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Interface](ue_ue.Interface.md).[constructor](ue_ue.Interface.md#constructor)

## Properties

### \_\_tid\_Interface\_\_

• **\_\_tid\_Interface\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Interface__](ue_ue.Interface.md#__tid_interface__)

___

### \_\_tid\_MagicLeapMeshBlockSelectorInterface\_\_

• **\_\_tid\_MagicLeapMeshBlockSelectorInterface\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Object__](ue_ue.Interface.md#__tid_object__)

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

[Interface](ue_ue.Interface.md).[CreateDefaultSubobject](ue_ue.Interface.md#createdefaultsubobject)

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

[Interface](ue_ue.Interface.md).[ExecuteUbergraph](ue_ue.Interface.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetClass](ue_ue.Interface.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Interface](ue_ue.Interface.md).[GetName](ue_ue.Interface.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetOuter](ue_ue.Interface.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetWorld](ue_ue.Interface.md#getworld)

___

### SelectMeshBlocks

▸ **SelectMeshBlocks**(`NewMeshInfo`, `RequestedMesh`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMeshInfo` | [`MagicLeapTrackingMeshInfo`](ue_ue.MagicLeapTrackingMeshInfo.md) |
| `RequestedMesh` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MagicLeapMeshBlockRequest`](ue_ue.MagicLeapMeshBlockRequest.md)\>\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MagicLeapMeshBlockSelectorInterface`](ue_ue.MagicLeapMeshBlockSelectorInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MagicLeapMeshBlockSelectorInterface`](ue_ue.MagicLeapMeshBlockSelectorInterface.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Find](ue_ue.Interface.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MagicLeapMeshBlockSelectorInterface`](ue_ue.MagicLeapMeshBlockSelectorInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MagicLeapMeshBlockSelectorInterface`](ue_ue.MagicLeapMeshBlockSelectorInterface.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Load](ue_ue.Interface.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Interface](ue_ue.Interface.md).[StaticClass](ue_ue.Interface.md#staticclass)
