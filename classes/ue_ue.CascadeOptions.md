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

## Properties

### BackgroundColor

• **BackgroundColor**: [`Color`](ue_ue_s.Color.md)

___

### Cascade\_MouseMoveThreshold

• **Cascade\_MouseMoveThreshold**: `number`

___

### Emitter\_Background

• **Emitter\_Background**: [`Color`](ue_ue_s.Color.md)

___

### Emitter\_Selected

• **Emitter\_Selected**: [`Color`](ue_ue_s.Color.md)

___

### Emitter\_Unselected

• **Emitter\_Unselected**: [`Color`](ue_ue_s.Color.md)

___

### Empty\_Background

• **Empty\_Background**: [`Color`](ue_ue_s.Color.md)

___

### FloorMesh

• **FloorMesh**: `string`

___

### FloorPosition

• **FloorPosition**: [`Vector`](ue_ue_s.Vector.md)

___

### FloorRotation

• **FloorRotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### FloorScale

• **FloorScale**: `number`

___

### FloorScale3D

• **FloorScale3D**: [`Vector`](ue_ue_s.Vector.md)

___

### GridColor\_Hi

• **GridColor\_Hi**: [`Color`](ue_ue_s.Color.md)

___

### GridColor\_Low

• **GridColor\_Low**: [`Color`](ue_ue_s.Color.md)

___

### GridPerspectiveSize

• **GridPerspectiveSize**: `number`

___

### ModuleColor\_Beam\_Selected

• **ModuleColor\_Beam\_Selected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_Beam\_Unselected

• **ModuleColor\_Beam\_Unselected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_Event\_Selected

• **ModuleColor\_Event\_Selected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_Event\_Unselected

• **ModuleColor\_Event\_Unselected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_General\_Selected

• **ModuleColor\_General\_Selected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_General\_Unselected

• **ModuleColor\_General\_Unselected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_Light\_Selected

• **ModuleColor\_Light\_Selected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_Light\_Unselected

• **ModuleColor\_Light\_Unselected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_Required\_Selected

• **ModuleColor\_Required\_Selected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_Required\_Unselected

• **ModuleColor\_Required\_Unselected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_Spawn\_Selected

• **ModuleColor\_Spawn\_Selected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_Spawn\_Unselected

• **ModuleColor\_Spawn\_Unselected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_SubUV\_Selected

• **ModuleColor\_SubUV\_Selected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_SubUV\_Unselected

• **ModuleColor\_SubUV\_Unselected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_Trail\_Selected

• **ModuleColor\_Trail\_Selected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_Trail\_Unselected

• **ModuleColor\_Trail\_Unselected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_TypeData\_Selected

• **ModuleColor\_TypeData\_Selected**: [`Color`](ue_ue_s.Color.md)

___

### ModuleColor\_TypeData\_Unselected

• **ModuleColor\_TypeData\_Unselected**: [`Color`](ue_ue_s.Color.md)

___

### MotionModeRadius

• **MotionModeRadius**: `number`

___

### ParticleMemoryUpdateTime

• **ParticleMemoryUpdateTime**: `number`

___

### ShowPPFlags

• **ShowPPFlags**: `number`

___

### SlimCascadeDrawHeight

• **SlimCascadeDrawHeight**: `number`

___

### \_\_tid\_CascadeOptions\_\_

• **\_\_tid\_CascadeOptions\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bCenterCascadeModuleText

• **bCenterCascadeModuleText**: `boolean`

___

### bShowFloor

• **bShowFloor**: `boolean`

___

### bShowGrid

• **bShowGrid**: `boolean`

___

### bShowModuleDump

• **bShowModuleDump**: `boolean`

___

### bShowParticleCounts

• **bShowParticleCounts**: `boolean`

___

### bShowParticleDistance

• **bShowParticleDistance**: `boolean`

___

### bShowParticleEvents

• **bShowParticleEvents**: `boolean`

___

### bShowParticleMemory

• **bShowParticleMemory**: `boolean`

___

### bShowParticleTimes

• **bShowParticleTimes**: `boolean`

___

### bUseSlimCascadeDraw

• **bUseSlimCascadeDraw**: `boolean`

___

### bUseSpaceBarReset

• **bUseSpaceBarReset**: `boolean`

___

### bUseSpaceBarResetInLevel

• **bUseSpaceBarResetInLevel**: `boolean`

___

### bUseSubMenus

• **bUseSubMenus**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
