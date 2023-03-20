[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleCameraOffset

# Class: ParticleModuleCameraOffset

[ue/ue](../modules/ue_ue.md).ParticleModuleCameraOffset

## Hierarchy

- [`ParticleModuleCameraBase`](ue_ue.ParticleModuleCameraBase.md)

  ↳ **`ParticleModuleCameraOffset`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleCameraOffset.md#constructor)

### Properties

- [CameraOffset](ue_ue.ParticleModuleCameraOffset.md#cameraoffset)
- [LODDuplicate](ue_ue.ParticleModuleCameraOffset.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleCameraOffset.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleCameraOffset.md#moduleeditorcolor)
- [UpdateMethod](ue_ue.ParticleModuleCameraOffset.md#updatemethod)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleCameraOffset.md#__tid_object__)
- [\_\_tid\_ParticleModuleCameraBase\_\_](ue_ue.ParticleModuleCameraOffset.md#__tid_particlemodulecamerabase__)
- [\_\_tid\_ParticleModuleCameraOffset\_\_](ue_ue.ParticleModuleCameraOffset.md#__tid_particlemodulecameraoffset__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleCameraOffset.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleCameraOffset.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModuleCameraOffset.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleCameraOffset.md#beditable)
- [bEnabled](ue_ue.ParticleModuleCameraOffset.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleCameraOffset.md#bfinalupdatemodule)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleCameraOffset.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleCameraOffset.md#bspawnmodule)
- [bSpawnTimeOnly](ue_ue.ParticleModuleCameraOffset.md#bspawntimeonly)
- [bSupported3DDrawMode](ue_ue.ParticleModuleCameraOffset.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleCameraOffset.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleCameraOffset.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleCameraOffset.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleCameraOffset.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleCameraOffset.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleCameraOffset.md#getclass)
- [GetName](ue_ue.ParticleModuleCameraOffset.md#getname)
- [GetOuter](ue_ue.ParticleModuleCameraOffset.md#getouter)
- [GetWorld](ue_ue.ParticleModuleCameraOffset.md#getworld)
- [Find](ue_ue.ParticleModuleCameraOffset.md#find)
- [Load](ue_ue.ParticleModuleCameraOffset.md#load)
- [StaticClass](ue_ue.ParticleModuleCameraOffset.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleCameraOffset**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[constructor](ue_ue.ParticleModuleCameraBase.md#constructor)

## Properties

### CameraOffset

• **CameraOffset**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[LODDuplicate](ue_ue.ParticleModuleCameraBase.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[LODValidity](ue_ue.ParticleModuleCameraBase.md#lodvalidity)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[ModuleEditorColor](ue_ue.ParticleModuleCameraBase.md#moduleeditorcolor)

___

### UpdateMethod

• **UpdateMethod**: [`EParticleCameraOffsetUpdateMethod`](../enums/ue_ue.EParticleCameraOffsetUpdateMethod.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[__tid_Object__](ue_ue.ParticleModuleCameraBase.md#__tid_object__)

___

### \_\_tid\_ParticleModuleCameraBase\_\_

• **\_\_tid\_ParticleModuleCameraBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[__tid_ParticleModuleCameraBase__](ue_ue.ParticleModuleCameraBase.md#__tid_particlemodulecamerabase__)

___

### \_\_tid\_ParticleModuleCameraOffset\_\_

• **\_\_tid\_ParticleModuleCameraOffset\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleCameraBase.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[b3DDrawMode](ue_ue.ParticleModuleCameraBase.md#b3ddrawmode)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[bCurvesAsColor](ue_ue.ParticleModuleCameraBase.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[bEditable](ue_ue.ParticleModuleCameraBase.md#beditable)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[bEnabled](ue_ue.ParticleModuleCameraBase.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleCameraBase.md#bfinalupdatemodule)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleCameraBase.md#brequiresloopingnotification)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[bSpawnModule](ue_ue.ParticleModuleCameraBase.md#bspawnmodule)

___

### bSpawnTimeOnly

• **bSpawnTimeOnly**: `boolean`

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleCameraBase.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleCameraBase.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleCameraBase.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[bUpdateModule](ue_ue.ParticleModuleCameraBase.md#bupdatemodule)

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

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleCameraBase.md#createdefaultsubobject)

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

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleCameraBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[GetClass](ue_ue.ParticleModuleCameraBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[GetName](ue_ue.ParticleModuleCameraBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[GetOuter](ue_ue.ParticleModuleCameraBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[GetWorld](ue_ue.ParticleModuleCameraBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleCameraOffset`](ue_ue.ParticleModuleCameraOffset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleCameraOffset`](ue_ue.ParticleModuleCameraOffset.md)

#### Overrides

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[Find](ue_ue.ParticleModuleCameraBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleCameraOffset`](ue_ue.ParticleModuleCameraOffset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleCameraOffset`](ue_ue.ParticleModuleCameraOffset.md)

#### Overrides

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[Load](ue_ue.ParticleModuleCameraBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleCameraBase](ue_ue.ParticleModuleCameraBase.md).[StaticClass](ue_ue.ParticleModuleCameraBase.md#staticclass)
