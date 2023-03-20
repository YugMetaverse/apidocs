[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimSet

# Class: AnimSet

[ue/ue](../modules/ue_ue.md).AnimSet

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AnimSet`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimSet.md#constructor)

### Properties

- [BestRatioSkelMeshName](ue_ue.AnimSet.md#bestratioskelmeshname)
- [BoneUseAnimTranslation](ue_ue.AnimSet.md#boneuseanimtranslation)
- [ForceMeshTranslationBoneNames](ue_ue.AnimSet.md#forcemeshtranslationbonenames)
- [ForceUseMeshTranslation](ue_ue.AnimSet.md#forceusemeshtranslation)
- [LinkupCache](ue_ue.AnimSet.md#linkupcache)
- [PreviewSkelMeshName](ue_ue.AnimSet.md#previewskelmeshname)
- [Sequences](ue_ue.AnimSet.md#sequences)
- [TrackBoneNames](ue_ue.AnimSet.md#trackbonenames)
- [UseTranslationBoneNames](ue_ue.AnimSet.md#usetranslationbonenames)
- [\_\_tid\_AnimSet\_\_](ue_ue.AnimSet.md#__tid_animset__)
- [\_\_tid\_Object\_\_](ue_ue.AnimSet.md#__tid_object__)
- [bAnimRotationOnly](ue_ue.AnimSet.md#banimrotationonly)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimSet.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimSet.md#executeubergraph)
- [GetClass](ue_ue.AnimSet.md#getclass)
- [GetName](ue_ue.AnimSet.md#getname)
- [GetOuter](ue_ue.AnimSet.md#getouter)
- [GetWorld](ue_ue.AnimSet.md#getworld)
- [Find](ue_ue.AnimSet.md#find)
- [Load](ue_ue.AnimSet.md#load)
- [StaticClass](ue_ue.AnimSet.md#staticclass)

## Constructors

### constructor

• **new AnimSet**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:20401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20401)

## Properties

### BestRatioSkelMeshName

• **BestRatioSkelMeshName**: `string`

#### Defined in

[ue/ue.d.ts:20411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20411)

___

### BoneUseAnimTranslation

• **BoneUseAnimTranslation**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:20406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20406)

___

### ForceMeshTranslationBoneNames

• **ForceMeshTranslationBoneNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:20409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20409)

___

### ForceUseMeshTranslation

• **ForceUseMeshTranslation**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:20407](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20407)

___

### LinkupCache

• **LinkupCache**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimSetMeshLinkup`](ue_ue.AnimSetMeshLinkup.md)\>

#### Defined in

[ue/ue.d.ts:20405](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20405)

___

### PreviewSkelMeshName

• **PreviewSkelMeshName**: `string`

#### Defined in

[ue/ue.d.ts:20410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20410)

___

### Sequences

• **Sequences**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimSequence`](ue_ue.AnimSequence.md)\>

#### Defined in

[ue/ue.d.ts:20404](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20404)

___

### TrackBoneNames

• **TrackBoneNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:20403](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20403)

___

### UseTranslationBoneNames

• **UseTranslationBoneNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:20408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20408)

___

### \_\_tid\_AnimSet\_\_

• **\_\_tid\_AnimSet\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20416)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAnimRotationOnly

• **bAnimRotationOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:20402](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20402)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimSet`](ue_ue.AnimSet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimSet`](ue_ue.AnimSet.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:20413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20413)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimSet`](ue_ue.AnimSet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimSet`](ue_ue.AnimSet.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:20414](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20414)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:20412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20412)
