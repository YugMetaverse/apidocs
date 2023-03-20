[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleTypeDataGpu

# Class: ParticleModuleTypeDataGpu

[ue/ue](../modules/ue_ue.md).ParticleModuleTypeDataGpu

## Hierarchy

- [`ParticleModuleTypeDataBase`](ue_ue.ParticleModuleTypeDataBase.md)

  ↳ **`ParticleModuleTypeDataGpu`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleTypeDataGpu.md#constructor)

### Properties

- [CameraMotionBlurAmount](ue_ue.ParticleModuleTypeDataGpu.md#cameramotionbluramount)
- [EmitterInfo](ue_ue.ParticleModuleTypeDataGpu.md#emitterinfo)
- [LODDuplicate](ue_ue.ParticleModuleTypeDataGpu.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleTypeDataGpu.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleTypeDataGpu.md#moduleeditorcolor)
- [ResourceData](ue_ue.ParticleModuleTypeDataGpu.md#resourcedata)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleTypeDataGpu.md#__tid_object__)
- [\_\_tid\_ParticleModuleTypeDataBase\_\_](ue_ue.ParticleModuleTypeDataGpu.md#__tid_particlemoduletypedatabase__)
- [\_\_tid\_ParticleModuleTypeDataGpu\_\_](ue_ue.ParticleModuleTypeDataGpu.md#__tid_particlemoduletypedatagpu__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleTypeDataGpu.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleTypeDataGpu.md#b3ddrawmode)
- [bClearExistingParticlesOnInit](ue_ue.ParticleModuleTypeDataGpu.md#bclearexistingparticlesoninit)
- [bCurvesAsColor](ue_ue.ParticleModuleTypeDataGpu.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleTypeDataGpu.md#beditable)
- [bEnabled](ue_ue.ParticleModuleTypeDataGpu.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleTypeDataGpu.md#bfinalupdatemodule)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleTypeDataGpu.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleTypeDataGpu.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleTypeDataGpu.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleTypeDataGpu.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleTypeDataGpu.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleTypeDataGpu.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleTypeDataGpu.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleTypeDataGpu.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleTypeDataGpu.md#getclass)
- [GetName](ue_ue.ParticleModuleTypeDataGpu.md#getname)
- [GetOuter](ue_ue.ParticleModuleTypeDataGpu.md#getouter)
- [GetWorld](ue_ue.ParticleModuleTypeDataGpu.md#getworld)
- [Find](ue_ue.ParticleModuleTypeDataGpu.md#find)
- [Load](ue_ue.ParticleModuleTypeDataGpu.md#load)
- [StaticClass](ue_ue.ParticleModuleTypeDataGpu.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleTypeDataGpu**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[constructor](ue_ue.ParticleModuleTypeDataBase.md#constructor)

#### Defined in

[ue/ue.d.ts:56568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56568)

## Properties

### CameraMotionBlurAmount

• **CameraMotionBlurAmount**: `number`

#### Defined in

[ue/ue.d.ts:56571](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56571)

___

### EmitterInfo

• **EmitterInfo**: [`GPUSpriteEmitterInfo`](ue_ue.GPUSpriteEmitterInfo.md)

#### Defined in

[ue/ue.d.ts:56569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56569)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[LODDuplicate](ue_ue.ParticleModuleTypeDataBase.md#lodduplicate)

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[LODValidity](ue_ue.ParticleModuleTypeDataBase.md#lodvalidity)

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6748)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[ModuleEditorColor](ue_ue.ParticleModuleTypeDataBase.md#moduleeditorcolor)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6749)

___

### ResourceData

• **ResourceData**: [`GPUSpriteResourceData`](ue_ue.GPUSpriteResourceData.md)

#### Defined in

[ue/ue.d.ts:56570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56570)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[__tid_Object__](ue_ue.ParticleModuleTypeDataBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModuleTypeDataBase\_\_

• **\_\_tid\_ParticleModuleTypeDataBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[__tid_ParticleModuleTypeDataBase__](ue_ue.ParticleModuleTypeDataBase.md#__tid_particlemoduletypedatabase__)

#### Defined in

[ue/ue.d.ts:6904](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6904)

___

### \_\_tid\_ParticleModuleTypeDataGpu\_\_

• **\_\_tid\_ParticleModuleTypeDataGpu\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:56577](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56577)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleTypeDataBase.md#__tid_particlemodule__)

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[b3DDrawMode](ue_ue.ParticleModuleTypeDataBase.md#b3ddrawmode)

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6741)

___

### bClearExistingParticlesOnInit

• **bClearExistingParticlesOnInit**: `boolean`

#### Defined in

[ue/ue.d.ts:56572](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56572)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bCurvesAsColor](ue_ue.ParticleModuleTypeDataBase.md#bcurvesascolor)

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6740)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bEditable](ue_ue.ParticleModuleTypeDataBase.md#beditable)

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6744)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bEnabled](ue_ue.ParticleModuleTypeDataBase.md#benabled)

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleTypeDataBase.md#bfinalupdatemodule)

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6738)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleTypeDataBase.md#brequiresloopingnotification)

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6747)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bSpawnModule](ue_ue.ParticleModuleTypeDataBase.md#bspawnmodule)

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleTypeDataBase.md#bsupported3ddrawmode)

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleTypeDataBase.md#bsupportsrandomseed)

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6746)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleTypeDataBase.md#bupdateforgpuemitter)

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bUpdateModule](ue_ue.ParticleModuleTypeDataBase.md#bupdatemodule)

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

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleTypeDataBase.md#createdefaultsubobject)

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

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleTypeDataBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetClass](ue_ue.ParticleModuleTypeDataBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetName](ue_ue.ParticleModuleTypeDataBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetOuter](ue_ue.ParticleModuleTypeDataBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetWorld](ue_ue.ParticleModuleTypeDataBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleTypeDataGpu`](ue_ue.ParticleModuleTypeDataGpu.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleTypeDataGpu`](ue_ue.ParticleModuleTypeDataGpu.md)

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[Find](ue_ue.ParticleModuleTypeDataBase.md#find)

#### Defined in

[ue/ue.d.ts:56574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56574)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleTypeDataGpu`](ue_ue.ParticleModuleTypeDataGpu.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleTypeDataGpu`](ue_ue.ParticleModuleTypeDataGpu.md)

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[Load](ue_ue.ParticleModuleTypeDataBase.md#load)

#### Defined in

[ue/ue.d.ts:56575](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56575)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[StaticClass](ue_ue.ParticleModuleTypeDataBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:56573](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56573)
