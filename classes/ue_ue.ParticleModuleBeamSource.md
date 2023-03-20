[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleBeamSource

# Class: ParticleModuleBeamSource

[ue/ue](../modules/ue_ue.md).ParticleModuleBeamSource

## Hierarchy

- [`ParticleModuleBeamBase`](ue_ue.ParticleModuleBeamBase.md)

  ↳ **`ParticleModuleBeamSource`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleBeamSource.md#constructor)

### Properties

- [LODDuplicate](ue_ue.ParticleModuleBeamSource.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleBeamSource.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleBeamSource.md#moduleeditorcolor)
- [Source](ue_ue.ParticleModuleBeamSource.md#source)
- [SourceMethod](ue_ue.ParticleModuleBeamSource.md#sourcemethod)
- [SourceName](ue_ue.ParticleModuleBeamSource.md#sourcename)
- [SourceStrength](ue_ue.ParticleModuleBeamSource.md#sourcestrength)
- [SourceTangent](ue_ue.ParticleModuleBeamSource.md#sourcetangent)
- [SourceTangentMethod](ue_ue.ParticleModuleBeamSource.md#sourcetangentmethod)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleBeamSource.md#__tid_object__)
- [\_\_tid\_ParticleModuleBeamBase\_\_](ue_ue.ParticleModuleBeamSource.md#__tid_particlemodulebeambase__)
- [\_\_tid\_ParticleModuleBeamSource\_\_](ue_ue.ParticleModuleBeamSource.md#__tid_particlemodulebeamsource__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleBeamSource.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleBeamSource.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModuleBeamSource.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleBeamSource.md#beditable)
- [bEnabled](ue_ue.ParticleModuleBeamSource.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleBeamSource.md#bfinalupdatemodule)
- [bLockSource](ue_ue.ParticleModuleBeamSource.md#blocksource)
- [bLockSourceStength](ue_ue.ParticleModuleBeamSource.md#blocksourcestength)
- [bLockSourceTangent](ue_ue.ParticleModuleBeamSource.md#blocksourcetangent)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleBeamSource.md#brequiresloopingnotification)
- [bSourceAbsolute](ue_ue.ParticleModuleBeamSource.md#bsourceabsolute)
- [bSpawnModule](ue_ue.ParticleModuleBeamSource.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleBeamSource.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleBeamSource.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleBeamSource.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleBeamSource.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleBeamSource.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleBeamSource.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleBeamSource.md#getclass)
- [GetName](ue_ue.ParticleModuleBeamSource.md#getname)
- [GetOuter](ue_ue.ParticleModuleBeamSource.md#getouter)
- [GetWorld](ue_ue.ParticleModuleBeamSource.md#getworld)
- [Find](ue_ue.ParticleModuleBeamSource.md#find)
- [Load](ue_ue.ParticleModuleBeamSource.md#load)
- [StaticClass](ue_ue.ParticleModuleBeamSource.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleBeamSource**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[constructor](ue_ue.ParticleModuleBeamBase.md#constructor)

## Properties

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[LODDuplicate](ue_ue.ParticleModuleBeamBase.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[LODValidity](ue_ue.ParticleModuleBeamBase.md#lodvalidity)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[ModuleEditorColor](ue_ue.ParticleModuleBeamBase.md#moduleeditorcolor)

___

### Source

• **Source**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

___

### SourceMethod

• **SourceMethod**: [`Beam2SourceTargetMethod`](../enums/ue_ue.Beam2SourceTargetMethod.md)

___

### SourceName

• **SourceName**: `string`

___

### SourceStrength

• **SourceStrength**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### SourceTangent

• **SourceTangent**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

___

### SourceTangentMethod

• **SourceTangentMethod**: [`Beam2SourceTargetTangentMethod`](../enums/ue_ue.Beam2SourceTargetTangentMethod.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[__tid_Object__](ue_ue.ParticleModuleBeamBase.md#__tid_object__)

___

### \_\_tid\_ParticleModuleBeamBase\_\_

• **\_\_tid\_ParticleModuleBeamBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[__tid_ParticleModuleBeamBase__](ue_ue.ParticleModuleBeamBase.md#__tid_particlemodulebeambase__)

___

### \_\_tid\_ParticleModuleBeamSource\_\_

• **\_\_tid\_ParticleModuleBeamSource\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleBeamBase.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[b3DDrawMode](ue_ue.ParticleModuleBeamBase.md#b3ddrawmode)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bCurvesAsColor](ue_ue.ParticleModuleBeamBase.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bEditable](ue_ue.ParticleModuleBeamBase.md#beditable)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bEnabled](ue_ue.ParticleModuleBeamBase.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleBeamBase.md#bfinalupdatemodule)

___

### bLockSource

• **bLockSource**: `boolean`

___

### bLockSourceStength

• **bLockSourceStength**: `boolean`

___

### bLockSourceTangent

• **bLockSourceTangent**: `boolean`

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleBeamBase.md#brequiresloopingnotification)

___

### bSourceAbsolute

• **bSourceAbsolute**: `boolean`

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bSpawnModule](ue_ue.ParticleModuleBeamBase.md#bspawnmodule)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleBeamBase.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleBeamBase.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleBeamBase.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bUpdateModule](ue_ue.ParticleModuleBeamBase.md#bupdatemodule)

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

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleBeamBase.md#createdefaultsubobject)

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

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleBeamBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetClass](ue_ue.ParticleModuleBeamBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetName](ue_ue.ParticleModuleBeamBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetOuter](ue_ue.ParticleModuleBeamBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetWorld](ue_ue.ParticleModuleBeamBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleBeamSource`](ue_ue.ParticleModuleBeamSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleBeamSource`](ue_ue.ParticleModuleBeamSource.md)

#### Overrides

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[Find](ue_ue.ParticleModuleBeamBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleBeamSource`](ue_ue.ParticleModuleBeamSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleBeamSource`](ue_ue.ParticleModuleBeamSource.md)

#### Overrides

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[Load](ue_ue.ParticleModuleBeamBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[StaticClass](ue_ue.ParticleModuleBeamBase.md#staticclass)
