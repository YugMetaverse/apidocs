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

#### Defined in

[ue/ue.d.ts:383](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L383)

## Properties

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

#### Defined in

[ue/ue.d.ts:387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L387)

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

#### Defined in

[ue/ue.d.ts:388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L388)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Defined in

[ue/ue.d.ts:384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L384)

___

### NeverStream

• **NeverStream**: `boolean`

#### Defined in

[ue/ue.d.ts:390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L390)

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

#### Defined in

[ue/ue.d.ts:385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L385)

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Defined in

[ue/ue.d.ts:386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L386)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L401)

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

#### Defined in

[ue/ue.d.ts:389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L389)

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

#### Defined in

[ue/ue.d.ts:394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L394)

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

#### Defined in

[ue/ue.d.ts:391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L391)

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

#### Defined in

[ue/ue.d.ts:393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L393)

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

#### Defined in

[ue/ue.d.ts:395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L395)

___

### bIsStreamable

• **bIsStreamable**: `boolean`

#### Defined in

[ue/ue.d.ts:392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L392)

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

#### Defined in

[ue/ue.d.ts:396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L396)

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

#### Defined in

[ue/ue.d.ts:398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L398)

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

#### Defined in

[ue/ue.d.ts:399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L399)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L397)
