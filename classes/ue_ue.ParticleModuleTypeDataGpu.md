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

## Properties

### CameraMotionBlurAmount

• **CameraMotionBlurAmount**: `number`

___

### EmitterInfo

• **EmitterInfo**: [`GPUSpriteEmitterInfo`](ue_ue.GPUSpriteEmitterInfo.md)

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

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[ModuleEditorColor](ue_ue.ParticleModuleTypeDataBase.md#moduleeditorcolor)

___

### ResourceData

• **ResourceData**: [`GPUSpriteResourceData`](ue_ue.GPUSpriteResourceData.md)

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

### \_\_tid\_ParticleModuleTypeDataGpu\_\_

• **\_\_tid\_ParticleModuleTypeDataGpu\_\_**: `boolean`

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

### bClearExistingParticlesOnInit

• **bClearExistingParticlesOnInit**: `boolean`

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bCurvesAsColor](ue_ue.ParticleModuleTypeDataBase.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bEditable](ue_ue.ParticleModuleTypeDataBase.md#beditable)

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

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleTypeDataBase.md#brequiresloopingnotification)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[StaticClass](ue_ue.ParticleModuleTypeDataBase.md#staticclass)
