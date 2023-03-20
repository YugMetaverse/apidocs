[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleTypeDataRibbon

# Class: ParticleModuleTypeDataRibbon

[ue/ue](../modules/ue_ue.md).ParticleModuleTypeDataRibbon

## Hierarchy

- [`ParticleModuleTypeDataBase`](ue_ue.ParticleModuleTypeDataBase.md)

  ↳ **`ParticleModuleTypeDataRibbon`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleTypeDataRibbon.md#constructor)

### Properties

- [DistanceTessellationStepSize](ue_ue.ParticleModuleTypeDataRibbon.md#distancetessellationstepsize)
- [LODDuplicate](ue_ue.ParticleModuleTypeDataRibbon.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleTypeDataRibbon.md#lodvalidity)
- [MaxParticleInTrailCount](ue_ue.ParticleModuleTypeDataRibbon.md#maxparticleintrailcount)
- [MaxTessellationBetweenParticles](ue_ue.ParticleModuleTypeDataRibbon.md#maxtessellationbetweenparticles)
- [MaxTrailCount](ue_ue.ParticleModuleTypeDataRibbon.md#maxtrailcount)
- [ModuleEditorColor](ue_ue.ParticleModuleTypeDataRibbon.md#moduleeditorcolor)
- [RenderAxis](ue_ue.ParticleModuleTypeDataRibbon.md#renderaxis)
- [SheetsPerTrail](ue_ue.ParticleModuleTypeDataRibbon.md#sheetspertrail)
- [TangentSpawningScalar](ue_ue.ParticleModuleTypeDataRibbon.md#tangentspawningscalar)
- [TangentTessellationScalar](ue_ue.ParticleModuleTypeDataRibbon.md#tangenttessellationscalar)
- [TilingDistance](ue_ue.ParticleModuleTypeDataRibbon.md#tilingdistance)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleTypeDataRibbon.md#__tid_object__)
- [\_\_tid\_ParticleModuleTypeDataBase\_\_](ue_ue.ParticleModuleTypeDataRibbon.md#__tid_particlemoduletypedatabase__)
- [\_\_tid\_ParticleModuleTypeDataRibbon\_\_](ue_ue.ParticleModuleTypeDataRibbon.md#__tid_particlemoduletypedataribbon__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleTypeDataRibbon.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleTypeDataRibbon.md#b3ddrawmode)
- [bClipSourceSegement](ue_ue.ParticleModuleTypeDataRibbon.md#bclipsourcesegement)
- [bCurvesAsColor](ue_ue.ParticleModuleTypeDataRibbon.md#bcurvesascolor)
- [bDeadTrailsOnDeactivate](ue_ue.ParticleModuleTypeDataRibbon.md#bdeadtrailsondeactivate)
- [bDeadTrailsOnSourceLoss](ue_ue.ParticleModuleTypeDataRibbon.md#bdeadtrailsonsourceloss)
- [bEditable](ue_ue.ParticleModuleTypeDataRibbon.md#beditable)
- [bEnablePreviousTangentRecalculation](ue_ue.ParticleModuleTypeDataRibbon.md#benableprevioustangentrecalculation)
- [bEnableTangentDiffInterpScale](ue_ue.ParticleModuleTypeDataRibbon.md#benabletangentdiffinterpscale)
- [bEnabled](ue_ue.ParticleModuleTypeDataRibbon.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleTypeDataRibbon.md#bfinalupdatemodule)
- [bRenderGeometry](ue_ue.ParticleModuleTypeDataRibbon.md#brendergeometry)
- [bRenderSpawnPoints](ue_ue.ParticleModuleTypeDataRibbon.md#brenderspawnpoints)
- [bRenderTangents](ue_ue.ParticleModuleTypeDataRibbon.md#brendertangents)
- [bRenderTessellation](ue_ue.ParticleModuleTypeDataRibbon.md#brendertessellation)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleTypeDataRibbon.md#brequiresloopingnotification)
- [bSpawnInitialParticle](ue_ue.ParticleModuleTypeDataRibbon.md#bspawninitialparticle)
- [bSpawnModule](ue_ue.ParticleModuleTypeDataRibbon.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleTypeDataRibbon.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleTypeDataRibbon.md#bsupportsrandomseed)
- [bTangentRecalculationEveryFrame](ue_ue.ParticleModuleTypeDataRibbon.md#btangentrecalculationeveryframe)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleTypeDataRibbon.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleTypeDataRibbon.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleTypeDataRibbon.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleTypeDataRibbon.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleTypeDataRibbon.md#getclass)
- [GetName](ue_ue.ParticleModuleTypeDataRibbon.md#getname)
- [GetOuter](ue_ue.ParticleModuleTypeDataRibbon.md#getouter)
- [GetWorld](ue_ue.ParticleModuleTypeDataRibbon.md#getworld)
- [Find](ue_ue.ParticleModuleTypeDataRibbon.md#find)
- [Load](ue_ue.ParticleModuleTypeDataRibbon.md#load)
- [StaticClass](ue_ue.ParticleModuleTypeDataRibbon.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleTypeDataRibbon**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[constructor](ue_ue.ParticleModuleTypeDataBase.md#constructor)

## Properties

### DistanceTessellationStepSize

• **DistanceTessellationStepSize**: `number`

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[LODDuplicate](ue_ue.ParticleModuleTypeDataBase.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[LODValidity](ue_ue.ParticleModuleTypeDataBase.md#lodvalidity)

___

### MaxParticleInTrailCount

• **MaxParticleInTrailCount**: `number`

___

### MaxTessellationBetweenParticles

• **MaxTessellationBetweenParticles**: `number`

___

### MaxTrailCount

• **MaxTrailCount**: `number`

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[ModuleEditorColor](ue_ue.ParticleModuleTypeDataBase.md#moduleeditorcolor)

___

### RenderAxis

• **RenderAxis**: [`ETrailsRenderAxisOption`](../enums/ue_ue.ETrailsRenderAxisOption.md)

___

### SheetsPerTrail

• **SheetsPerTrail**: `number`

___

### TangentSpawningScalar

• **TangentSpawningScalar**: `number`

___

### TangentTessellationScalar

• **TangentTessellationScalar**: `number`

___

### TilingDistance

• **TilingDistance**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[__tid_Object__](ue_ue.ParticleModuleTypeDataBase.md#__tid_object__)

___

### \_\_tid\_ParticleModuleTypeDataBase\_\_

• **\_\_tid\_ParticleModuleTypeDataBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[__tid_ParticleModuleTypeDataBase__](ue_ue.ParticleModuleTypeDataBase.md#__tid_particlemoduletypedatabase__)

___

### \_\_tid\_ParticleModuleTypeDataRibbon\_\_

• **\_\_tid\_ParticleModuleTypeDataRibbon\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleTypeDataBase.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[b3DDrawMode](ue_ue.ParticleModuleTypeDataBase.md#b3ddrawmode)

___

### bClipSourceSegement

• **bClipSourceSegement**: `boolean`

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bCurvesAsColor](ue_ue.ParticleModuleTypeDataBase.md#bcurvesascolor)

___

### bDeadTrailsOnDeactivate

• **bDeadTrailsOnDeactivate**: `boolean`

___

### bDeadTrailsOnSourceLoss

• **bDeadTrailsOnSourceLoss**: `boolean`

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bEditable](ue_ue.ParticleModuleTypeDataBase.md#beditable)

___

### bEnablePreviousTangentRecalculation

• **bEnablePreviousTangentRecalculation**: `boolean`

___

### bEnableTangentDiffInterpScale

• **bEnableTangentDiffInterpScale**: `boolean`

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bEnabled](ue_ue.ParticleModuleTypeDataBase.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleTypeDataBase.md#bfinalupdatemodule)

___

### bRenderGeometry

• **bRenderGeometry**: `boolean`

___

### bRenderSpawnPoints

• **bRenderSpawnPoints**: `boolean`

___

### bRenderTangents

• **bRenderTangents**: `boolean`

___

### bRenderTessellation

• **bRenderTessellation**: `boolean`

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleTypeDataBase.md#brequiresloopingnotification)

___

### bSpawnInitialParticle

• **bSpawnInitialParticle**: `boolean`

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bSpawnModule](ue_ue.ParticleModuleTypeDataBase.md#bspawnmodule)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleTypeDataBase.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleTypeDataBase.md#bsupportsrandomseed)

___

### bTangentRecalculationEveryFrame

• **bTangentRecalculationEveryFrame**: `boolean`

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleTypeDataBase.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bUpdateModule](ue_ue.ParticleModuleTypeDataBase.md#bupdatemodule)

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

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleTypeDataBase.md#createdefaultsubobject)

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

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleTypeDataBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetClass](ue_ue.ParticleModuleTypeDataBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetName](ue_ue.ParticleModuleTypeDataBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetOuter](ue_ue.ParticleModuleTypeDataBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetWorld](ue_ue.ParticleModuleTypeDataBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleTypeDataRibbon`](ue_ue.ParticleModuleTypeDataRibbon.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleTypeDataRibbon`](ue_ue.ParticleModuleTypeDataRibbon.md)

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[Find](ue_ue.ParticleModuleTypeDataBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleTypeDataRibbon`](ue_ue.ParticleModuleTypeDataRibbon.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleTypeDataRibbon`](ue_ue.ParticleModuleTypeDataRibbon.md)

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[Load](ue_ue.ParticleModuleTypeDataBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[StaticClass](ue_ue.ParticleModuleTypeDataBase.md#staticclass)
