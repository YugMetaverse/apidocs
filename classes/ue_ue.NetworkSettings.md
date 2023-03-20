[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NetworkSettings

# Class: NetworkSettings

[ue/ue](../modules/ue_ue.md).NetworkSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`NetworkSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.NetworkSettings.md#constructor)

### Properties

- [MaxRepArrayMemory](ue_ue.NetworkSettings.md#maxreparraymemory)
- [MaxRepArraySize](ue_ue.NetworkSettings.md#maxreparraysize)
- [NetworkEmulationProfiles](ue_ue.NetworkSettings.md#networkemulationprofiles)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.NetworkSettings.md#__tid_developersettings__)
- [\_\_tid\_NetworkSettings\_\_](ue_ue.NetworkSettings.md#__tid_networksettings__)
- [\_\_tid\_Object\_\_](ue_ue.NetworkSettings.md#__tid_object__)
- [bEnableMultiplayerWorldOriginRebasing](ue_ue.NetworkSettings.md#benablemultiplayerworldoriginrebasing)
- [bVerifyPeer](ue_ue.NetworkSettings.md#bverifypeer)

### Methods

- [CreateDefaultSubobject](ue_ue.NetworkSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NetworkSettings.md#executeubergraph)
- [GetClass](ue_ue.NetworkSettings.md#getclass)
- [GetName](ue_ue.NetworkSettings.md#getname)
- [GetOuter](ue_ue.NetworkSettings.md#getouter)
- [GetWorld](ue_ue.NetworkSettings.md#getworld)
- [Find](ue_ue.NetworkSettings.md#find)
- [Load](ue_ue.NetworkSettings.md#load)
- [StaticClass](ue_ue.NetworkSettings.md#staticclass)

## Constructors

### constructor

• **new NetworkSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

#### Defined in

[ue/ue.d.ts:53499](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53499)

## Properties

### MaxRepArrayMemory

• **MaxRepArrayMemory**: `number`

#### Defined in

[ue/ue.d.ts:53503](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53503)

___

### MaxRepArraySize

• **MaxRepArraySize**: `number`

#### Defined in

[ue/ue.d.ts:53502](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53502)

___

### NetworkEmulationProfiles

• **NetworkEmulationProfiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NetworkEmulationProfileDescription`](ue_ue.NetworkEmulationProfileDescription.md)\>

#### Defined in

[ue/ue.d.ts:53504](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53504)

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

#### Defined in

[ue/ue.d.ts:16950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16950)

___

### \_\_tid\_NetworkSettings\_\_

• **\_\_tid\_NetworkSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:53509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53509)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bEnableMultiplayerWorldOriginRebasing

• **bEnableMultiplayerWorldOriginRebasing**: `boolean`

#### Defined in

[ue/ue.d.ts:53501](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53501)

___

### bVerifyPeer

• **bVerifyPeer**: `boolean`

#### Defined in

[ue/ue.d.ts:53500](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53500)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NetworkSettings`](ue_ue.NetworkSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NetworkSettings`](ue_ue.NetworkSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

#### Defined in

[ue/ue.d.ts:53506](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53506)

___

### Load

▸ `Static` **Load**(`InName`): [`NetworkSettings`](ue_ue.NetworkSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NetworkSettings`](ue_ue.NetworkSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

#### Defined in

[ue/ue.d.ts:53507](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53507)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)

#### Defined in

[ue/ue.d.ts:53505](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53505)