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

## Properties

### BestRatioSkelMeshName

• **BestRatioSkelMeshName**: `string`

___

### BoneUseAnimTranslation

• **BoneUseAnimTranslation**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### ForceMeshTranslationBoneNames

• **ForceMeshTranslationBoneNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ForceUseMeshTranslation

• **ForceUseMeshTranslation**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### LinkupCache

• **LinkupCache**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimSetMeshLinkup`](ue_ue.AnimSetMeshLinkup.md)\>

___

### PreviewSkelMeshName

• **PreviewSkelMeshName**: `string`

___

### Sequences

• **Sequences**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimSequence`](ue_ue.AnimSequence.md)\>

___

### TrackBoneNames

• **TrackBoneNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### UseTranslationBoneNames

• **UseTranslationBoneNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### \_\_tid\_AnimSet\_\_

• **\_\_tid\_AnimSet\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAnimRotationOnly

• **bAnimRotationOnly**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
