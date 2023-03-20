[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleParameterDynamic

# Class: ParticleModuleParameterDynamic

[ue/ue](../modules/ue_ue.md).ParticleModuleParameterDynamic

## Hierarchy

- [`ParticleModuleParameterBase`](ue_ue.ParticleModuleParameterBase.md)

  ↳ **`ParticleModuleParameterDynamic`**

  ↳↳ [`ParticleModuleParameterDynamic_Seeded`](ue_ue.ParticleModuleParameterDynamic_Seeded.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleParameterDynamic.md#constructor)

### Properties

- [DynamicParams](ue_ue.ParticleModuleParameterDynamic.md#dynamicparams)
- [LODDuplicate](ue_ue.ParticleModuleParameterDynamic.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleParameterDynamic.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleParameterDynamic.md#moduleeditorcolor)
- [UpdateFlags](ue_ue.ParticleModuleParameterDynamic.md#updateflags)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleParameterDynamic.md#__tid_object__)
- [\_\_tid\_ParticleModuleParameterBase\_\_](ue_ue.ParticleModuleParameterDynamic.md#__tid_particlemoduleparameterbase__)
- [\_\_tid\_ParticleModuleParameterDynamic\_\_](ue_ue.ParticleModuleParameterDynamic.md#__tid_particlemoduleparameterdynamic__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleParameterDynamic.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleParameterDynamic.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModuleParameterDynamic.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleParameterDynamic.md#beditable)
- [bEnabled](ue_ue.ParticleModuleParameterDynamic.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleParameterDynamic.md#bfinalupdatemodule)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleParameterDynamic.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleParameterDynamic.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleParameterDynamic.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleParameterDynamic.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleParameterDynamic.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleParameterDynamic.md#bupdatemodule)
- [bUsesVelocity](ue_ue.ParticleModuleParameterDynamic.md#busesvelocity)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleParameterDynamic.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleParameterDynamic.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleParameterDynamic.md#getclass)
- [GetName](ue_ue.ParticleModuleParameterDynamic.md#getname)
- [GetOuter](ue_ue.ParticleModuleParameterDynamic.md#getouter)
- [GetWorld](ue_ue.ParticleModuleParameterDynamic.md#getworld)
- [Find](ue_ue.ParticleModuleParameterDynamic.md#find)
- [Load](ue_ue.ParticleModuleParameterDynamic.md#load)
- [StaticClass](ue_ue.ParticleModuleParameterDynamic.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleParameterDynamic**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[constructor](ue_ue.ParticleModuleParameterBase.md#constructor)

## Properties

### DynamicParams

• **DynamicParams**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EmitterDynamicParameter`](ue_ue.EmitterDynamicParameter.md)\>

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[LODDuplicate](ue_ue.ParticleModuleParameterBase.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[LODValidity](ue_ue.ParticleModuleParameterBase.md#lodvalidity)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[ModuleEditorColor](ue_ue.ParticleModuleParameterBase.md#moduleeditorcolor)

___

### UpdateFlags

• **UpdateFlags**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[__tid_Object__](ue_ue.ParticleModuleParameterBase.md#__tid_object__)

___

### \_\_tid\_ParticleModuleParameterBase\_\_

• **\_\_tid\_ParticleModuleParameterBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[__tid_ParticleModuleParameterBase__](ue_ue.ParticleModuleParameterBase.md#__tid_particlemoduleparameterbase__)

___

### \_\_tid\_ParticleModuleParameterDynamic\_\_

• **\_\_tid\_ParticleModuleParameterDynamic\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleParameterBase.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[b3DDrawMode](ue_ue.ParticleModuleParameterBase.md#b3ddrawmode)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[bCurvesAsColor](ue_ue.ParticleModuleParameterBase.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[bEditable](ue_ue.ParticleModuleParameterBase.md#beditable)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[bEnabled](ue_ue.ParticleModuleParameterBase.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleParameterBase.md#bfinalupdatemodule)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleParameterBase.md#brequiresloopingnotification)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[bSpawnModule](ue_ue.ParticleModuleParameterBase.md#bspawnmodule)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleParameterBase.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleParameterBase.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleParameterBase.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[bUpdateModule](ue_ue.ParticleModuleParameterBase.md#bupdatemodule)

___

### bUsesVelocity

• **bUsesVelocity**: `boolean`

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

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleParameterBase.md#createdefaultsubobject)

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

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleParameterBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[GetClass](ue_ue.ParticleModuleParameterBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[GetName](ue_ue.ParticleModuleParameterBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[GetOuter](ue_ue.ParticleModuleParameterBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[GetWorld](ue_ue.ParticleModuleParameterBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleParameterDynamic`](ue_ue.ParticleModuleParameterDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleParameterDynamic`](ue_ue.ParticleModuleParameterDynamic.md)

#### Overrides

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[Find](ue_ue.ParticleModuleParameterBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleParameterDynamic`](ue_ue.ParticleModuleParameterDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleParameterDynamic`](ue_ue.ParticleModuleParameterDynamic.md)

#### Overrides

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[Load](ue_ue.ParticleModuleParameterBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleParameterBase](ue_ue.ParticleModuleParameterBase.md).[StaticClass](ue_ue.ParticleModuleParameterBase.md#staticclass)
