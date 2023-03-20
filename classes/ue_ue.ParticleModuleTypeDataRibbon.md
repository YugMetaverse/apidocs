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

#### Defined in

[ue/ue.d.ts:56607](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56607)

## Properties

### DistanceTessellationStepSize

• **DistanceTessellationStepSize**: `number`

#### Defined in

[ue/ue.d.ts:56625](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56625)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[LODDuplicate](ue_ue.ParticleModuleTypeDataBase.md#lodduplicate)

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[LODValidity](ue_ue.ParticleModuleTypeDataBase.md#lodvalidity)

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6748)

___

### MaxParticleInTrailCount

• **MaxParticleInTrailCount**: `number`

#### Defined in

[ue/ue.d.ts:56611](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56611)

___

### MaxTessellationBetweenParticles

• **MaxTessellationBetweenParticles**: `number`

#### Defined in

[ue/ue.d.ts:56608](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56608)

___

### MaxTrailCount

• **MaxTrailCount**: `number`

#### Defined in

[ue/ue.d.ts:56610](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56610)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[ModuleEditorColor](ue_ue.ParticleModuleTypeDataBase.md#moduleeditorcolor)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6749)

___

### RenderAxis

• **RenderAxis**: [`ETrailsRenderAxisOption`](../enums/ue_ue.ETrailsRenderAxisOption.md)

#### Defined in

[ue/ue.d.ts:56618](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56618)

___

### SheetsPerTrail

• **SheetsPerTrail**: `number`

#### Defined in

[ue/ue.d.ts:56609](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56609)

___

### TangentSpawningScalar

• **TangentSpawningScalar**: `number`

#### Defined in

[ue/ue.d.ts:56619](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56619)

___

### TangentTessellationScalar

• **TangentTessellationScalar**: `number`

#### Defined in

[ue/ue.d.ts:56627](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56627)

___

### TilingDistance

• **TilingDistance**: `number`

#### Defined in

[ue/ue.d.ts:56624](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56624)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[__tid_Object__](ue_ue.ParticleModuleTypeDataBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModuleTypeDataBase\_\_

• **\_\_tid\_ParticleModuleTypeDataBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[__tid_ParticleModuleTypeDataBase__](ue_ue.ParticleModuleTypeDataBase.md#__tid_particlemoduletypedatabase__)

#### Defined in

[ue/ue.d.ts:6904](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6904)

___

### \_\_tid\_ParticleModuleTypeDataRibbon\_\_

• **\_\_tid\_ParticleModuleTypeDataRibbon\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:56632](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56632)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleTypeDataBase.md#__tid_particlemodule__)

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[b3DDrawMode](ue_ue.ParticleModuleTypeDataBase.md#b3ddrawmode)

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6741)

___

### bClipSourceSegement

• **bClipSourceSegement**: `boolean`

#### Defined in

[ue/ue.d.ts:56614](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56614)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bCurvesAsColor](ue_ue.ParticleModuleTypeDataBase.md#bcurvesascolor)

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6740)

___

### bDeadTrailsOnDeactivate

• **bDeadTrailsOnDeactivate**: `boolean`

#### Defined in

[ue/ue.d.ts:56612](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56612)

___

### bDeadTrailsOnSourceLoss

• **bDeadTrailsOnSourceLoss**: `boolean`

#### Defined in

[ue/ue.d.ts:56613](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56613)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bEditable](ue_ue.ParticleModuleTypeDataBase.md#beditable)

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6744)

___

### bEnablePreviousTangentRecalculation

• **bEnablePreviousTangentRecalculation**: `boolean`

#### Defined in

[ue/ue.d.ts:56615](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56615)

___

### bEnableTangentDiffInterpScale

• **bEnableTangentDiffInterpScale**: `boolean`

#### Defined in

[ue/ue.d.ts:56626](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56626)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bEnabled](ue_ue.ParticleModuleTypeDataBase.md#benabled)

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleTypeDataBase.md#bfinalupdatemodule)

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6738)

___

### bRenderGeometry

• **bRenderGeometry**: `boolean`

#### Defined in

[ue/ue.d.ts:56620](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56620)

___

### bRenderSpawnPoints

• **bRenderSpawnPoints**: `boolean`

#### Defined in

[ue/ue.d.ts:56621](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56621)

___

### bRenderTangents

• **bRenderTangents**: `boolean`

#### Defined in

[ue/ue.d.ts:56622](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56622)

___

### bRenderTessellation

• **bRenderTessellation**: `boolean`

#### Defined in

[ue/ue.d.ts:56623](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56623)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleTypeDataBase.md#brequiresloopingnotification)

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6747)

___

### bSpawnInitialParticle

• **bSpawnInitialParticle**: `boolean`

#### Defined in

[ue/ue.d.ts:56617](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56617)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bSpawnModule](ue_ue.ParticleModuleTypeDataBase.md#bspawnmodule)

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleTypeDataBase.md#bsupported3ddrawmode)

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleTypeDataBase.md#bsupportsrandomseed)

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6746)

___

### bTangentRecalculationEveryFrame

• **bTangentRecalculationEveryFrame**: `boolean`

#### Defined in

[ue/ue.d.ts:56616](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56616)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleTypeDataBase.md#bupdateforgpuemitter)

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bUpdateModule](ue_ue.ParticleModuleTypeDataBase.md#bupdatemodule)

#### Defined in

[ue/ue.d.ts:6737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6737)

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

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleTypeDataBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetClass](ue_ue.ParticleModuleTypeDataBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetName](ue_ue.ParticleModuleTypeDataBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetOuter](ue_ue.ParticleModuleTypeDataBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetWorld](ue_ue.ParticleModuleTypeDataBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:56629](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56629)

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

#### Defined in

[ue/ue.d.ts:56630](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56630)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[StaticClass](ue_ue.ParticleModuleTypeDataBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:56628](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56628)
