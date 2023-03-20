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

#### Defined in

[ue/ue.d.ts:6735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6735)

## Properties

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6748)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6749)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6741)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6740)

___

### bEditable

• **bEditable**: `boolean`

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6744)

___

### bEnabled

• **bEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6738)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6747)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6746)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

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

#### Defined in

[ue/ue.d.ts:6751](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6751)

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

#### Defined in

[ue/ue.d.ts:6752](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6752)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:6750](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6750)
