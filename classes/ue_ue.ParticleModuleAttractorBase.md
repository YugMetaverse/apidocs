[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleAttractorBase

# Class: ParticleModuleAttractorBase

[ue/ue](../modules/ue_ue.md).ParticleModuleAttractorBase

## Hierarchy

- [`ParticleModule`](ue_ue.ParticleModule.md)

  ↳ **`ParticleModuleAttractorBase`**

  ↳↳ [`ParticleModuleAttractorLine`](ue_ue.ParticleModuleAttractorLine.md)

  ↳↳ [`ParticleModuleAttractorParticle`](ue_ue.ParticleModuleAttractorParticle.md)

  ↳↳ [`ParticleModuleAttractorPoint`](ue_ue.ParticleModuleAttractorPoint.md)

  ↳↳ [`ParticleModuleAttractorPointGravity`](ue_ue.ParticleModuleAttractorPointGravity.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleAttractorBase.md#constructor)

### Properties

- [LODDuplicate](ue_ue.ParticleModuleAttractorBase.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleAttractorBase.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleAttractorBase.md#moduleeditorcolor)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleAttractorBase.md#__tid_object__)
- [\_\_tid\_ParticleModuleAttractorBase\_\_](ue_ue.ParticleModuleAttractorBase.md#__tid_particlemoduleattractorbase__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleAttractorBase.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleAttractorBase.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModuleAttractorBase.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleAttractorBase.md#beditable)
- [bEnabled](ue_ue.ParticleModuleAttractorBase.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleAttractorBase.md#bfinalupdatemodule)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleAttractorBase.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleAttractorBase.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleAttractorBase.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleAttractorBase.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleAttractorBase.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleAttractorBase.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleAttractorBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleAttractorBase.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleAttractorBase.md#getclass)
- [GetName](ue_ue.ParticleModuleAttractorBase.md#getname)
- [GetOuter](ue_ue.ParticleModuleAttractorBase.md#getouter)
- [GetWorld](ue_ue.ParticleModuleAttractorBase.md#getworld)
- [Find](ue_ue.ParticleModuleAttractorBase.md#find)
- [Load](ue_ue.ParticleModuleAttractorBase.md#load)
- [StaticClass](ue_ue.ParticleModuleAttractorBase.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleAttractorBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModule](ue_ue.ParticleModule.md).[constructor](ue_ue.ParticleModule.md#constructor)

#### Defined in

[ue/ue.d.ts:55302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55302)

## Properties

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[LODDuplicate](ue_ue.ParticleModule.md#lodduplicate)

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[LODValidity](ue_ue.ParticleModule.md#lodvalidity)

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6748)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[ModuleEditorColor](ue_ue.ParticleModule.md#moduleeditorcolor)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6749)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[__tid_Object__](ue_ue.ParticleModule.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModuleAttractorBase\_\_

• **\_\_tid\_ParticleModuleAttractorBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:55307](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55307)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[__tid_ParticleModule__](ue_ue.ParticleModule.md#__tid_particlemodule__)

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[b3DDrawMode](ue_ue.ParticleModule.md#b3ddrawmode)

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6741)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bCurvesAsColor](ue_ue.ParticleModule.md#bcurvesascolor)

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6740)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bEditable](ue_ue.ParticleModule.md#beditable)

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6744)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bEnabled](ue_ue.ParticleModule.md#benabled)

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bFinalUpdateModule](ue_ue.ParticleModule.md#bfinalupdatemodule)

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6738)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bRequiresLoopingNotification](ue_ue.ParticleModule.md#brequiresloopingnotification)

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6747)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bSpawnModule](ue_ue.ParticleModule.md#bspawnmodule)

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bSupported3DDrawMode](ue_ue.ParticleModule.md#bsupported3ddrawmode)

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bSupportsRandomSeed](ue_ue.ParticleModule.md#bsupportsrandomseed)

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6746)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bUpdateForGPUEmitter](ue_ue.ParticleModule.md#bupdateforgpuemitter)

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bUpdateModule](ue_ue.ParticleModule.md#bupdatemodule)

#### Defined in

[ue/ue.d.ts:6737](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6737)

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

[ParticleModule](ue_ue.ParticleModule.md).[CreateDefaultSubobject](ue_ue.ParticleModule.md#createdefaultsubobject)

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

[ParticleModule](ue_ue.ParticleModule.md).[ExecuteUbergraph](ue_ue.ParticleModule.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetClass](ue_ue.ParticleModule.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetName](ue_ue.ParticleModule.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetOuter](ue_ue.ParticleModule.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetWorld](ue_ue.ParticleModule.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleAttractorBase`](ue_ue.ParticleModuleAttractorBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleAttractorBase`](ue_ue.ParticleModuleAttractorBase.md)

#### Overrides

[ParticleModule](ue_ue.ParticleModule.md).[Find](ue_ue.ParticleModule.md#find)

#### Defined in

[ue/ue.d.ts:55304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55304)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleAttractorBase`](ue_ue.ParticleModuleAttractorBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleAttractorBase`](ue_ue.ParticleModuleAttractorBase.md)

#### Overrides

[ParticleModule](ue_ue.ParticleModule.md).[Load](ue_ue.ParticleModule.md#load)

#### Defined in

[ue/ue.d.ts:55305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55305)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModule](ue_ue.ParticleModule.md).[StaticClass](ue_ue.ParticleModule.md#staticclass)

#### Defined in

[ue/ue.d.ts:55303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55303)