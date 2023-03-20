[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GrassVariety

# Class: GrassVariety

[ue/ue](../modules/ue_ue.md).GrassVariety

## Table of contents

### Constructors

- [constructor](ue_ue.GrassVariety.md#constructor)

### Properties

- [AlignToSurface](ue_ue.GrassVariety.md#aligntosurface)
- [EndCullDistance](ue_ue.GrassVariety.md#endculldistance)
- [GrassDensity](ue_ue.GrassVariety.md#grassdensity)
- [GrassMesh](ue_ue.GrassVariety.md#grassmesh)
- [LightingChannels](ue_ue.GrassVariety.md#lightingchannels)
- [MinLOD](ue_ue.GrassVariety.md#minlod)
- [PlacementJitter](ue_ue.GrassVariety.md#placementjitter)
- [RandomRotation](ue_ue.GrassVariety.md#randomrotation)
- [ScaleX](ue_ue.GrassVariety.md#scalex)
- [ScaleY](ue_ue.GrassVariety.md#scaley)
- [ScaleZ](ue_ue.GrassVariety.md#scalez)
- [Scaling](ue_ue.GrassVariety.md#scaling)
- [StartCullDistance](ue_ue.GrassVariety.md#startculldistance)
- [\_\_tid\_GrassVariety\_\_](ue_ue.GrassVariety.md#__tid_grassvariety__)
- [bCastDynamicShadow](ue_ue.GrassVariety.md#bcastdynamicshadow)
- [bKeepInstanceBufferCPUCopy](ue_ue.GrassVariety.md#bkeepinstancebuffercpucopy)
- [bReceivesDecals](ue_ue.GrassVariety.md#breceivesdecals)
- [bUseGrid](ue_ue.GrassVariety.md#busegrid)
- [bUseLandscapeLightmap](ue_ue.GrassVariety.md#buselandscapelightmap)

### Methods

- [StaticClass](ue_ue.GrassVariety.md#staticclass)
- [StaticStruct](ue_ue.GrassVariety.md#staticstruct)

## Constructors

### constructor

• **new GrassVariety**()

• **new GrassVariety**(`GrassMesh`, `GrassDensity`, `bUseGrid`, `PlacementJitter`, `StartCullDistance`, `EndCullDistance`, `MinLOD`, `Scaling`, `ScaleX`, `ScaleY`, `ScaleZ`, `RandomRotation`, `AlignToSurface`, `bUseLandscapeLightmap`, `LightingChannels`, `bReceivesDecals`, `bCastDynamicShadow`, `bKeepInstanceBufferCPUCopy`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `GrassMesh` | [`StaticMesh`](ue_ue.StaticMesh.md) |
| `GrassDensity` | [`PerPlatformFloat`](ue_ue.PerPlatformFloat.md) |
| `bUseGrid` | `boolean` |
| `PlacementJitter` | `number` |
| `StartCullDistance` | [`PerPlatformInt`](ue_ue.PerPlatformInt.md) |
| `EndCullDistance` | [`PerPlatformInt`](ue_ue.PerPlatformInt.md) |
| `MinLOD` | `number` |
| `Scaling` | [`EGrassScaling`](../enums/ue_ue.EGrassScaling.md) |
| `ScaleX` | [`FloatInterval`](ue_ue.FloatInterval.md) |
| `ScaleY` | [`FloatInterval`](ue_ue.FloatInterval.md) |
| `ScaleZ` | [`FloatInterval`](ue_ue.FloatInterval.md) |
| `RandomRotation` | `boolean` |
| `AlignToSurface` | `boolean` |
| `bUseLandscapeLightmap` | `boolean` |
| `LightingChannels` | [`LightingChannels`](ue_ue.LightingChannels.md) |
| `bReceivesDecals` | `boolean` |
| `bCastDynamicShadow` | `boolean` |
| `bKeepInstanceBufferCPUCopy` | `boolean` |

## Properties

### AlignToSurface

• **AlignToSurface**: `boolean`

___

### EndCullDistance

• **EndCullDistance**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

___

### GrassDensity

• **GrassDensity**: [`PerPlatformFloat`](ue_ue.PerPlatformFloat.md)

___

### GrassMesh

• **GrassMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

___

### MinLOD

• **MinLOD**: `number`

___

### PlacementJitter

• **PlacementJitter**: `number`

___

### RandomRotation

• **RandomRotation**: `boolean`

___

### ScaleX

• **ScaleX**: [`FloatInterval`](ue_ue.FloatInterval.md)

___

### ScaleY

• **ScaleY**: [`FloatInterval`](ue_ue.FloatInterval.md)

___

### ScaleZ

• **ScaleZ**: [`FloatInterval`](ue_ue.FloatInterval.md)

___

### Scaling

• **Scaling**: [`EGrassScaling`](../enums/ue_ue.EGrassScaling.md)

___

### StartCullDistance

• **StartCullDistance**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

___

### \_\_tid\_GrassVariety\_\_

• `Private` **\_\_tid\_GrassVariety\_\_**: `boolean`

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

___

### bKeepInstanceBufferCPUCopy

• **bKeepInstanceBufferCPUCopy**: `boolean`

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

___

### bUseGrid

• **bUseGrid**: `boolean`

___

### bUseLandscapeLightmap

• **bUseLandscapeLightmap**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
