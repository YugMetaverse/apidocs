[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / StreamableRenderAsset

# Class: StreamableRenderAsset

[ue/ue](../modules/ue_ue.md).StreamableRenderAsset

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`StreamableRenderAsset`**

  ↳↳ [`Texture`](ue_ue.Texture.md)

  ↳↳ [`SkeletalMesh`](ue_ue.SkeletalMesh.md)

  ↳↳ [`StaticMesh`](ue_ue.StaticMesh.md)

## Table of contents

### Constructors

- [constructor](ue_ue.StreamableRenderAsset.md#constructor)

### Properties

- [CachedCombinedLODBias](ue_ue.StreamableRenderAsset.md#cachedcombinedlodbias)
- [CachedNumResidentLODs](ue_ue.StreamableRenderAsset.md#cachednumresidentlods)
- [ForceMipLevelsToBeResidentTimestamp](ue_ue.StreamableRenderAsset.md#forcemiplevelstoberesidenttimestamp)
- [NeverStream](ue_ue.StreamableRenderAsset.md#neverstream)
- [NumCinematicMipLevels](ue_ue.StreamableRenderAsset.md#numcinematicmiplevels)
- [StreamingIndex](ue_ue.StreamableRenderAsset.md#streamingindex)
- [\_\_tid\_Object\_\_](ue_ue.StreamableRenderAsset.md#__tid_object__)
- [\_\_tid\_StreamableRenderAsset\_\_](ue_ue.StreamableRenderAsset.md#__tid_streamablerenderasset__)
- [bCachedReadyForStreaming](ue_ue.StreamableRenderAsset.md#bcachedreadyforstreaming)
- [bForceMiplevelsToBeResident](ue_ue.StreamableRenderAsset.md#bforcemiplevelstoberesident)
- [bGlobalForceMipLevelsToBeResident](ue_ue.StreamableRenderAsset.md#bglobalforcemiplevelstoberesident)
- [bHasStreamingUpdatePending](ue_ue.StreamableRenderAsset.md#bhasstreamingupdatepending)
- [bIgnoreStreamingMipBias](ue_ue.StreamableRenderAsset.md#bignorestreamingmipbias)
- [bIsStreamable](ue_ue.StreamableRenderAsset.md#bisstreamable)
- [bUseCinematicMipLevels](ue_ue.StreamableRenderAsset.md#busecinematicmiplevels)

### Methods

- [CreateDefaultSubobject](ue_ue.StreamableRenderAsset.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.StreamableRenderAsset.md#executeubergraph)
- [GetClass](ue_ue.StreamableRenderAsset.md#getclass)
- [GetName](ue_ue.StreamableRenderAsset.md#getname)
- [GetOuter](ue_ue.StreamableRenderAsset.md#getouter)
- [GetWorld](ue_ue.StreamableRenderAsset.md#getworld)
- [Find](ue_ue.StreamableRenderAsset.md#find)
- [Load](ue_ue.StreamableRenderAsset.md#load)
- [StaticClass](ue_ue.StreamableRenderAsset.md#staticclass)

## Constructors

### constructor

• **new StreamableRenderAsset**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

___

### NeverStream

• **NeverStream**: `boolean`

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

___

### StreamingIndex

• **StreamingIndex**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

___

### bIsStreamable

• **bIsStreamable**: `boolean`

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`StreamableRenderAsset`](ue_ue.StreamableRenderAsset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`StreamableRenderAsset`](ue_ue.StreamableRenderAsset.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`StreamableRenderAsset`](ue_ue.StreamableRenderAsset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`StreamableRenderAsset`](ue_ue.StreamableRenderAsset.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
