[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModule

# Class: ParticleModule

[ue/ue](../modules/ue_ue.md).ParticleModule

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ParticleModule`**

  ↳↳ [`ParticleModuleRequired`](ue_ue.ParticleModuleRequired.md)

  ↳↳ [`ParticleModuleTypeDataBase`](ue_ue.ParticleModuleTypeDataBase.md)

  ↳↳ [`ParticleModuleSpawnBase`](ue_ue.ParticleModuleSpawnBase.md)

  ↳↳ [`ParticleModuleEventBase`](ue_ue.ParticleModuleEventBase.md)

  ↳↳ [`ParticleModuleOrbitBase`](ue_ue.ParticleModuleOrbitBase.md)

  ↳↳ [`ParticleModuleAccelerationBase`](ue_ue.ParticleModuleAccelerationBase.md)

  ↳↳ [`ParticleModuleAttractorBase`](ue_ue.ParticleModuleAttractorBase.md)

  ↳↳ [`ParticleModuleBeamBase`](ue_ue.ParticleModuleBeamBase.md)

  ↳↳ [`ParticleModuleCameraBase`](ue_ue.ParticleModuleCameraBase.md)

  ↳↳ [`ParticleModuleCollisionBase`](ue_ue.ParticleModuleCollisionBase.md)

  ↳↳ [`ParticleModuleColorBase`](ue_ue.ParticleModuleColorBase.md)

  ↳↳ [`ParticleModuleKillBase`](ue_ue.ParticleModuleKillBase.md)

  ↳↳ [`ParticleModuleLifetimeBase`](ue_ue.ParticleModuleLifetimeBase.md)

  ↳↳ [`ParticleModuleLightBase`](ue_ue.ParticleModuleLightBase.md)

  ↳↳ [`ParticleModuleLocationBase`](ue_ue.ParticleModuleLocationBase.md)

  ↳↳ [`ParticleModuleMaterialBase`](ue_ue.ParticleModuleMaterialBase.md)

  ↳↳ [`ParticleModuleRotationBase`](ue_ue.ParticleModuleRotationBase.md)

  ↳↳ [`ParticleModuleRotationRateBase`](ue_ue.ParticleModuleRotationRateBase.md)

  ↳↳ [`ParticleModuleOrientationBase`](ue_ue.ParticleModuleOrientationBase.md)

  ↳↳ [`ParticleModuleParameterBase`](ue_ue.ParticleModuleParameterBase.md)

  ↳↳ [`ParticleModuleSizeBase`](ue_ue.ParticleModuleSizeBase.md)

  ↳↳ [`ParticleModuleSubUVBase`](ue_ue.ParticleModuleSubUVBase.md)

  ↳↳ [`ParticleModuleTrailBase`](ue_ue.ParticleModuleTrailBase.md)

  ↳↳ [`ParticleModuleVectorFieldBase`](ue_ue.ParticleModuleVectorFieldBase.md)

  ↳↳ [`ParticleModuleVelocityBase`](ue_ue.ParticleModuleVelocityBase.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModule.md#constructor)

### Properties

- [LODDuplicate](ue_ue.ParticleModule.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModule.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModule.md#moduleeditorcolor)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModule.md#__tid_object__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModule.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModule.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModule.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModule.md#beditable)
- [bEnabled](ue_ue.ParticleModule.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModule.md#bfinalupdatemodule)
- [bRequiresLoopingNotification](ue_ue.ParticleModule.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModule.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModule.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModule.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModule.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModule.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModule.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModule.md#executeubergraph)
- [GetClass](ue_ue.ParticleModule.md#getclass)
- [GetName](ue_ue.ParticleModule.md#getname)
- [GetOuter](ue_ue.ParticleModule.md#getouter)
- [GetWorld](ue_ue.ParticleModule.md#getworld)
- [Find](ue_ue.ParticleModule.md#find)
- [Load](ue_ue.ParticleModule.md#load)
- [StaticClass](ue_ue.ParticleModule.md#staticclass)

## Constructors

### constructor

• **new ParticleModule**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### LODDuplicate

• **LODDuplicate**: `boolean`

___

### LODValidity

• **LODValidity**: `number`

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

___

### bEditable

• **bEditable**: `boolean`

___

### bEnabled

• **bEnabled**: `boolean`

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

___

### bSpawnModule

• **bSpawnModule**: `boolean`

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

___

### bUpdateModule

• **bUpdateModule**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModule`](ue_ue.ParticleModule.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModule`](ue_ue.ParticleModule.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModule`](ue_ue.ParticleModule.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModule`](ue_ue.ParticleModule.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
