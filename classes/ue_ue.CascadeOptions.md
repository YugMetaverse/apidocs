[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CascadeOptions

# Class: CascadeOptions

[ue/ue](../modules/ue_ue.md).CascadeOptions

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`CascadeOptions`**

## Table of contents

### Constructors

- [constructor](ue_ue.CascadeOptions.md#constructor)

### Properties

- [BackgroundColor](ue_ue.CascadeOptions.md#backgroundcolor)
- [Cascade\_MouseMoveThreshold](ue_ue.CascadeOptions.md#cascade_mousemovethreshold)
- [Emitter\_Background](ue_ue.CascadeOptions.md#emitter_background)
- [Emitter\_Selected](ue_ue.CascadeOptions.md#emitter_selected)
- [Emitter\_Unselected](ue_ue.CascadeOptions.md#emitter_unselected)
- [Empty\_Background](ue_ue.CascadeOptions.md#empty_background)
- [FloorMesh](ue_ue.CascadeOptions.md#floormesh)
- [FloorPosition](ue_ue.CascadeOptions.md#floorposition)
- [FloorRotation](ue_ue.CascadeOptions.md#floorrotation)
- [FloorScale](ue_ue.CascadeOptions.md#floorscale)
- [FloorScale3D](ue_ue.CascadeOptions.md#floorscale3d)
- [GridColor\_Hi](ue_ue.CascadeOptions.md#gridcolor_hi)
- [GridColor\_Low](ue_ue.CascadeOptions.md#gridcolor_low)
- [GridPerspectiveSize](ue_ue.CascadeOptions.md#gridperspectivesize)
- [ModuleColor\_Beam\_Selected](ue_ue.CascadeOptions.md#modulecolor_beam_selected)
- [ModuleColor\_Beam\_Unselected](ue_ue.CascadeOptions.md#modulecolor_beam_unselected)
- [ModuleColor\_Event\_Selected](ue_ue.CascadeOptions.md#modulecolor_event_selected)
- [ModuleColor\_Event\_Unselected](ue_ue.CascadeOptions.md#modulecolor_event_unselected)
- [ModuleColor\_General\_Selected](ue_ue.CascadeOptions.md#modulecolor_general_selected)
- [ModuleColor\_General\_Unselected](ue_ue.CascadeOptions.md#modulecolor_general_unselected)
- [ModuleColor\_Light\_Selected](ue_ue.CascadeOptions.md#modulecolor_light_selected)
- [ModuleColor\_Light\_Unselected](ue_ue.CascadeOptions.md#modulecolor_light_unselected)
- [ModuleColor\_Required\_Selected](ue_ue.CascadeOptions.md#modulecolor_required_selected)
- [ModuleColor\_Required\_Unselected](ue_ue.CascadeOptions.md#modulecolor_required_unselected)
- [ModuleColor\_Spawn\_Selected](ue_ue.CascadeOptions.md#modulecolor_spawn_selected)
- [ModuleColor\_Spawn\_Unselected](ue_ue.CascadeOptions.md#modulecolor_spawn_unselected)
- [ModuleColor\_SubUV\_Selected](ue_ue.CascadeOptions.md#modulecolor_subuv_selected)
- [ModuleColor\_SubUV\_Unselected](ue_ue.CascadeOptions.md#modulecolor_subuv_unselected)
- [ModuleColor\_Trail\_Selected](ue_ue.CascadeOptions.md#modulecolor_trail_selected)
- [ModuleColor\_Trail\_Unselected](ue_ue.CascadeOptions.md#modulecolor_trail_unselected)
- [ModuleColor\_TypeData\_Selected](ue_ue.CascadeOptions.md#modulecolor_typedata_selected)
- [ModuleColor\_TypeData\_Unselected](ue_ue.CascadeOptions.md#modulecolor_typedata_unselected)
- [MotionModeRadius](ue_ue.CascadeOptions.md#motionmoderadius)
- [ParticleMemoryUpdateTime](ue_ue.CascadeOptions.md#particlememoryupdatetime)
- [ShowPPFlags](ue_ue.CascadeOptions.md#showppflags)
- [SlimCascadeDrawHeight](ue_ue.CascadeOptions.md#slimcascadedrawheight)
- [\_\_tid\_CascadeOptions\_\_](ue_ue.CascadeOptions.md#__tid_cascadeoptions__)
- [\_\_tid\_Object\_\_](ue_ue.CascadeOptions.md#__tid_object__)
- [bCenterCascadeModuleText](ue_ue.CascadeOptions.md#bcentercascademoduletext)
- [bShowFloor](ue_ue.CascadeOptions.md#bshowfloor)
- [bShowGrid](ue_ue.CascadeOptions.md#bshowgrid)
- [bShowModuleDump](ue_ue.CascadeOptions.md#bshowmoduledump)
- [bShowParticleCounts](ue_ue.CascadeOptions.md#bshowparticlecounts)
- [bShowParticleDistance](ue_ue.CascadeOptions.md#bshowparticledistance)
- [bShowParticleEvents](ue_ue.CascadeOptions.md#bshowparticleevents)
- [bShowParticleMemory](ue_ue.CascadeOptions.md#bshowparticlememory)
- [bShowParticleTimes](ue_ue.CascadeOptions.md#bshowparticletimes)
- [bUseSlimCascadeDraw](ue_ue.CascadeOptions.md#buseslimcascadedraw)
- [bUseSpaceBarReset](ue_ue.CascadeOptions.md#busespacebarreset)
- [bUseSpaceBarResetInLevel](ue_ue.CascadeOptions.md#busespacebarresetinlevel)
- [bUseSubMenus](ue_ue.CascadeOptions.md#busesubmenus)

### Methods

- [CreateDefaultSubobject](ue_ue.CascadeOptions.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CascadeOptions.md#executeubergraph)
- [GetClass](ue_ue.CascadeOptions.md#getclass)
- [GetName](ue_ue.CascadeOptions.md#getname)
- [GetOuter](ue_ue.CascadeOptions.md#getouter)
- [GetWorld](ue_ue.CascadeOptions.md#getworld)
- [Find](ue_ue.CascadeOptions.md#find)
- [Load](ue_ue.CascadeOptions.md#load)
- [StaticClass](ue_ue.CascadeOptions.md#staticclass)

## Constructors

### constructor

• **new CascadeOptions**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:26248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26248)

## Properties

### BackgroundColor

• **BackgroundColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26250)

___

### Cascade\_MouseMoveThreshold

• **Cascade\_MouseMoveThreshold**: `number`

#### Defined in

[ue/ue.d.ts:26296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26296)

___

### Emitter\_Background

• **Emitter\_Background**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26255)

___

### Emitter\_Selected

• **Emitter\_Selected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26257)

___

### Emitter\_Unselected

• **Emitter\_Unselected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26256](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26256)

___

### Empty\_Background

• **Empty\_Background**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26254)

___

### FloorMesh

• **FloorMesh**: `string`

#### Defined in

[ue/ue.d.ts:26287](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26287)

___

### FloorPosition

• **FloorPosition**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:26288](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26288)

___

### FloorRotation

• **FloorRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:26289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26289)

___

### FloorScale

• **FloorScale**: `number`

#### Defined in

[ue/ue.d.ts:26290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26290)

___

### FloorScale3D

• **FloorScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:26291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26291)

___

### GridColor\_Hi

• **GridColor\_Hi**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26277](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26277)

___

### GridColor\_Low

• **GridColor\_Low**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26278](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26278)

___

### GridPerspectiveSize

• **GridPerspectiveSize**: `number`

#### Defined in

[ue/ue.d.ts:26279](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26279)

___

### ModuleColor\_Beam\_Selected

• **ModuleColor\_Beam\_Selected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26263](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26263)

___

### ModuleColor\_Beam\_Unselected

• **ModuleColor\_Beam\_Unselected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26262)

___

### ModuleColor\_Event\_Selected

• **ModuleColor\_Event\_Selected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26275](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26275)

___

### ModuleColor\_Event\_Unselected

• **ModuleColor\_Event\_Unselected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26274](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26274)

___

### ModuleColor\_General\_Selected

• **ModuleColor\_General\_Selected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26259)

___

### ModuleColor\_General\_Unselected

• **ModuleColor\_General\_Unselected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26258)

___

### ModuleColor\_Light\_Selected

• **ModuleColor\_Light\_Selected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26269](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26269)

___

### ModuleColor\_Light\_Unselected

• **ModuleColor\_Light\_Unselected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26268](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26268)

___

### ModuleColor\_Required\_Selected

• **ModuleColor\_Required\_Selected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26273](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26273)

___

### ModuleColor\_Required\_Unselected

• **ModuleColor\_Required\_Unselected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26272](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26272)

___

### ModuleColor\_Spawn\_Selected

• **ModuleColor\_Spawn\_Selected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26267](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26267)

___

### ModuleColor\_Spawn\_Unselected

• **ModuleColor\_Spawn\_Unselected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26266](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26266)

___

### ModuleColor\_SubUV\_Selected

• **ModuleColor\_SubUV\_Selected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26271](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26271)

___

### ModuleColor\_SubUV\_Unselected

• **ModuleColor\_SubUV\_Unselected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26270](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26270)

___

### ModuleColor\_Trail\_Selected

• **ModuleColor\_Trail\_Selected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26265](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26265)

___

### ModuleColor\_Trail\_Unselected

• **ModuleColor\_Trail\_Unselected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26264](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26264)

___

### ModuleColor\_TypeData\_Selected

• **ModuleColor\_TypeData\_Selected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26261)

___

### ModuleColor\_TypeData\_Unselected

• **ModuleColor\_TypeData\_Unselected**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:26260](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26260)

___

### MotionModeRadius

• **MotionModeRadius**: `number`

#### Defined in

[ue/ue.d.ts:26297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26297)

___

### ParticleMemoryUpdateTime

• **ParticleMemoryUpdateTime**: `number`

#### Defined in

[ue/ue.d.ts:26285](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26285)

___

### ShowPPFlags

• **ShowPPFlags**: `number`

#### Defined in

[ue/ue.d.ts:26292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26292)

___

### SlimCascadeDrawHeight

• **SlimCascadeDrawHeight**: `number`

#### Defined in

[ue/ue.d.ts:26294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26294)

___

### \_\_tid\_CascadeOptions\_\_

• **\_\_tid\_CascadeOptions\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:26302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26302)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bCenterCascadeModuleText

• **bCenterCascadeModuleText**: `boolean`

#### Defined in

[ue/ue.d.ts:26295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26295)

___

### bShowFloor

• **bShowFloor**: `boolean`

#### Defined in

[ue/ue.d.ts:26286](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26286)

___

### bShowGrid

• **bShowGrid**: `boolean`

#### Defined in

[ue/ue.d.ts:26276](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26276)

___

### bShowModuleDump

• **bShowModuleDump**: `boolean`

#### Defined in

[ue/ue.d.ts:26249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26249)

___

### bShowParticleCounts

• **bShowParticleCounts**: `boolean`

#### Defined in

[ue/ue.d.ts:26280](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26280)

___

### bShowParticleDistance

• **bShowParticleDistance**: `boolean`

#### Defined in

[ue/ue.d.ts:26283](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26283)

___

### bShowParticleEvents

• **bShowParticleEvents**: `boolean`

#### Defined in

[ue/ue.d.ts:26281](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26281)

___

### bShowParticleMemory

• **bShowParticleMemory**: `boolean`

#### Defined in

[ue/ue.d.ts:26284](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26284)

___

### bShowParticleTimes

• **bShowParticleTimes**: `boolean`

#### Defined in

[ue/ue.d.ts:26282](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26282)

___

### bUseSlimCascadeDraw

• **bUseSlimCascadeDraw**: `boolean`

#### Defined in

[ue/ue.d.ts:26293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26293)

___

### bUseSpaceBarReset

• **bUseSpaceBarReset**: `boolean`

#### Defined in

[ue/ue.d.ts:26252](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26252)

___

### bUseSpaceBarResetInLevel

• **bUseSpaceBarResetInLevel**: `boolean`

#### Defined in

[ue/ue.d.ts:26253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26253)

___

### bUseSubMenus

• **bUseSubMenus**: `boolean`

#### Defined in

[ue/ue.d.ts:26251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26251)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CascadeOptions`](ue_ue.CascadeOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CascadeOptions`](ue_ue.CascadeOptions.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:26299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26299)

___

### Load

▸ `Static` **Load**(`InName`): [`CascadeOptions`](ue_ue.CascadeOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CascadeOptions`](ue_ue.CascadeOptions.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:26300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26300)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:26298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L26298)
