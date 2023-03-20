[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleSourceMovement

# Class: ParticleModuleSourceMovement

[ue/ue](../modules/ue_ue.md).ParticleModuleSourceMovement

## Hierarchy

- [`ParticleModuleLocationBase`](ue_ue.ParticleModuleLocationBase.md)

  ↳ **`ParticleModuleSourceMovement`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleSourceMovement.md#constructor)

### Properties

- [LODDuplicate](ue_ue.ParticleModuleSourceMovement.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleSourceMovement.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleSourceMovement.md#moduleeditorcolor)
- [SourceMovementScale](ue_ue.ParticleModuleSourceMovement.md#sourcemovementscale)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleSourceMovement.md#__tid_object__)
- [\_\_tid\_ParticleModuleLocationBase\_\_](ue_ue.ParticleModuleSourceMovement.md#__tid_particlemodulelocationbase__)
- [\_\_tid\_ParticleModuleSourceMovement\_\_](ue_ue.ParticleModuleSourceMovement.md#__tid_particlemodulesourcemovement__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleSourceMovement.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleSourceMovement.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModuleSourceMovement.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleSourceMovement.md#beditable)
- [bEnabled](ue_ue.ParticleModuleSourceMovement.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleSourceMovement.md#bfinalupdatemodule)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleSourceMovement.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleSourceMovement.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleSourceMovement.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleSourceMovement.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleSourceMovement.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleSourceMovement.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleSourceMovement.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleSourceMovement.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleSourceMovement.md#getclass)
- [GetName](ue_ue.ParticleModuleSourceMovement.md#getname)
- [GetOuter](ue_ue.ParticleModuleSourceMovement.md#getouter)
- [GetWorld](ue_ue.ParticleModuleSourceMovement.md#getworld)
- [Find](ue_ue.ParticleModuleSourceMovement.md#find)
- [Load](ue_ue.ParticleModuleSourceMovement.md#load)
- [StaticClass](ue_ue.ParticleModuleSourceMovement.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleSourceMovement**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[constructor](ue_ue.ParticleModuleLocationBase.md#constructor)

## Properties

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[LODDuplicate](ue_ue.ParticleModuleLocationBase.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[LODValidity](ue_ue.ParticleModuleLocationBase.md#lodvalidity)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[ModuleEditorColor](ue_ue.ParticleModuleLocationBase.md#moduleeditorcolor)

___

### SourceMovementScale

• **SourceMovementScale**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[__tid_Object__](ue_ue.ParticleModuleLocationBase.md#__tid_object__)

___

### \_\_tid\_ParticleModuleLocationBase\_\_

• **\_\_tid\_ParticleModuleLocationBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[__tid_ParticleModuleLocationBase__](ue_ue.ParticleModuleLocationBase.md#__tid_particlemodulelocationbase__)

___

### \_\_tid\_ParticleModuleSourceMovement\_\_

• **\_\_tid\_ParticleModuleSourceMovement\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleLocationBase.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[b3DDrawMode](ue_ue.ParticleModuleLocationBase.md#b3ddrawmode)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bCurvesAsColor](ue_ue.ParticleModuleLocationBase.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bEditable](ue_ue.ParticleModuleLocationBase.md#beditable)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bEnabled](ue_ue.ParticleModuleLocationBase.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleLocationBase.md#bfinalupdatemodule)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleLocationBase.md#brequiresloopingnotification)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bSpawnModule](ue_ue.ParticleModuleLocationBase.md#bspawnmodule)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleLocationBase.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleLocationBase.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleLocationBase.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[bUpdateModule](ue_ue.ParticleModuleLocationBase.md#bupdatemodule)

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

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleLocationBase.md#createdefaultsubobject)

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

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleLocationBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[GetClass](ue_ue.ParticleModuleLocationBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[GetName](ue_ue.ParticleModuleLocationBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[GetOuter](ue_ue.ParticleModuleLocationBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[GetWorld](ue_ue.ParticleModuleLocationBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleSourceMovement`](ue_ue.ParticleModuleSourceMovement.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleSourceMovement`](ue_ue.ParticleModuleSourceMovement.md)

#### Overrides

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[Find](ue_ue.ParticleModuleLocationBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleSourceMovement`](ue_ue.ParticleModuleSourceMovement.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleSourceMovement`](ue_ue.ParticleModuleSourceMovement.md)

#### Overrides

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[Load](ue_ue.ParticleModuleLocationBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleLocationBase](ue_ue.ParticleModuleLocationBase.md).[StaticClass](ue_ue.ParticleModuleLocationBase.md#staticclass)
