[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleTrailSource

# Class: ParticleModuleTrailSource

[ue/ue](../modules/ue_ue.md).ParticleModuleTrailSource

## Hierarchy

- [`ParticleModuleTrailBase`](ue_ue.ParticleModuleTrailBase.md)

  ↳ **`ParticleModuleTrailSource`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleTrailSource.md#constructor)

### Properties

- [LODDuplicate](ue_ue.ParticleModuleTrailSource.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleTrailSource.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleTrailSource.md#moduleeditorcolor)
- [SelectionMethod](ue_ue.ParticleModuleTrailSource.md#selectionmethod)
- [SourceMethod](ue_ue.ParticleModuleTrailSource.md#sourcemethod)
- [SourceName](ue_ue.ParticleModuleTrailSource.md#sourcename)
- [SourceOffsetCount](ue_ue.ParticleModuleTrailSource.md#sourceoffsetcount)
- [SourceOffsetDefaults](ue_ue.ParticleModuleTrailSource.md#sourceoffsetdefaults)
- [SourceStrength](ue_ue.ParticleModuleTrailSource.md#sourcestrength)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleTrailSource.md#__tid_object__)
- [\_\_tid\_ParticleModuleTrailBase\_\_](ue_ue.ParticleModuleTrailSource.md#__tid_particlemoduletrailbase__)
- [\_\_tid\_ParticleModuleTrailSource\_\_](ue_ue.ParticleModuleTrailSource.md#__tid_particlemoduletrailsource__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleTrailSource.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleTrailSource.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModuleTrailSource.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleTrailSource.md#beditable)
- [bEnabled](ue_ue.ParticleModuleTrailSource.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleTrailSource.md#bfinalupdatemodule)
- [bInheritRotation](ue_ue.ParticleModuleTrailSource.md#binheritrotation)
- [bLockSourceStength](ue_ue.ParticleModuleTrailSource.md#blocksourcestength)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleTrailSource.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleTrailSource.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleTrailSource.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleTrailSource.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleTrailSource.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleTrailSource.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleTrailSource.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleTrailSource.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleTrailSource.md#getclass)
- [GetName](ue_ue.ParticleModuleTrailSource.md#getname)
- [GetOuter](ue_ue.ParticleModuleTrailSource.md#getouter)
- [GetWorld](ue_ue.ParticleModuleTrailSource.md#getworld)
- [Find](ue_ue.ParticleModuleTrailSource.md#find)
- [Load](ue_ue.ParticleModuleTrailSource.md#load)
- [StaticClass](ue_ue.ParticleModuleTrailSource.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleTrailSource**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[constructor](ue_ue.ParticleModuleTrailBase.md#constructor)

## Properties

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[LODDuplicate](ue_ue.ParticleModuleTrailBase.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[LODValidity](ue_ue.ParticleModuleTrailBase.md#lodvalidity)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[ModuleEditorColor](ue_ue.ParticleModuleTrailBase.md#moduleeditorcolor)

___

### SelectionMethod

• **SelectionMethod**: [`EParticleSourceSelectionMethod`](../enums/ue_ue.EParticleSourceSelectionMethod.md)

___

### SourceMethod

• **SourceMethod**: [`ETrail2SourceMethod`](../enums/ue_ue.ETrail2SourceMethod.md)

___

### SourceName

• **SourceName**: `string`

___

### SourceOffsetCount

• **SourceOffsetCount**: `number`

___

### SourceOffsetDefaults

• **SourceOffsetDefaults**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### SourceStrength

• **SourceStrength**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[__tid_Object__](ue_ue.ParticleModuleTrailBase.md#__tid_object__)

___

### \_\_tid\_ParticleModuleTrailBase\_\_

• **\_\_tid\_ParticleModuleTrailBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[__tid_ParticleModuleTrailBase__](ue_ue.ParticleModuleTrailBase.md#__tid_particlemoduletrailbase__)

___

### \_\_tid\_ParticleModuleTrailSource\_\_

• **\_\_tid\_ParticleModuleTrailSource\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleTrailBase.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[b3DDrawMode](ue_ue.ParticleModuleTrailBase.md#b3ddrawmode)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[bCurvesAsColor](ue_ue.ParticleModuleTrailBase.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[bEditable](ue_ue.ParticleModuleTrailBase.md#beditable)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[bEnabled](ue_ue.ParticleModuleTrailBase.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleTrailBase.md#bfinalupdatemodule)

___

### bInheritRotation

• **bInheritRotation**: `boolean`

___

### bLockSourceStength

• **bLockSourceStength**: `boolean`

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleTrailBase.md#brequiresloopingnotification)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[bSpawnModule](ue_ue.ParticleModuleTrailBase.md#bspawnmodule)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleTrailBase.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleTrailBase.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleTrailBase.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[bUpdateModule](ue_ue.ParticleModuleTrailBase.md#bupdatemodule)

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

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleTrailBase.md#createdefaultsubobject)

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

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleTrailBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[GetClass](ue_ue.ParticleModuleTrailBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[GetName](ue_ue.ParticleModuleTrailBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[GetOuter](ue_ue.ParticleModuleTrailBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[GetWorld](ue_ue.ParticleModuleTrailBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleTrailSource`](ue_ue.ParticleModuleTrailSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleTrailSource`](ue_ue.ParticleModuleTrailSource.md)

#### Overrides

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[Find](ue_ue.ParticleModuleTrailBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleTrailSource`](ue_ue.ParticleModuleTrailSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleTrailSource`](ue_ue.ParticleModuleTrailSource.md)

#### Overrides

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[Load](ue_ue.ParticleModuleTrailBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleTrailBase](ue_ue.ParticleModuleTrailBase.md).[StaticClass](ue_ue.ParticleModuleTrailBase.md#staticclass)
