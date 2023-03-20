[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleVelocityBase

# Class: ParticleModuleVelocityBase

[ue/ue](../modules/ue_ue.md).ParticleModuleVelocityBase

## Hierarchy

- [`ParticleModule`](ue_ue.ParticleModule.md)

  ↳ **`ParticleModuleVelocityBase`**

  ↳↳ [`ParticleModuleVelocity`](ue_ue.ParticleModuleVelocity.md)

  ↳↳ [`ParticleModuleVelocityCone`](ue_ue.ParticleModuleVelocityCone.md)

  ↳↳ [`ParticleModuleVelocityInheritParent`](ue_ue.ParticleModuleVelocityInheritParent.md)

  ↳↳ [`ParticleModuleVelocityOverLifetime`](ue_ue.ParticleModuleVelocityOverLifetime.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleVelocityBase.md#constructor)

### Properties

- [LODDuplicate](ue_ue.ParticleModuleVelocityBase.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleVelocityBase.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleVelocityBase.md#moduleeditorcolor)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleVelocityBase.md#__tid_object__)
- [\_\_tid\_ParticleModuleVelocityBase\_\_](ue_ue.ParticleModuleVelocityBase.md#__tid_particlemodulevelocitybase__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleVelocityBase.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleVelocityBase.md#b3ddrawmode)
- [bApplyOwnerScale](ue_ue.ParticleModuleVelocityBase.md#bapplyownerscale)
- [bCurvesAsColor](ue_ue.ParticleModuleVelocityBase.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleVelocityBase.md#beditable)
- [bEnabled](ue_ue.ParticleModuleVelocityBase.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleVelocityBase.md#bfinalupdatemodule)
- [bInWorldSpace](ue_ue.ParticleModuleVelocityBase.md#binworldspace)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleVelocityBase.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleVelocityBase.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleVelocityBase.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleVelocityBase.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleVelocityBase.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleVelocityBase.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleVelocityBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleVelocityBase.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleVelocityBase.md#getclass)
- [GetName](ue_ue.ParticleModuleVelocityBase.md#getname)
- [GetOuter](ue_ue.ParticleModuleVelocityBase.md#getouter)
- [GetWorld](ue_ue.ParticleModuleVelocityBase.md#getworld)
- [Find](ue_ue.ParticleModuleVelocityBase.md#find)
- [Load](ue_ue.ParticleModuleVelocityBase.md#load)
- [StaticClass](ue_ue.ParticleModuleVelocityBase.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleVelocityBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModule](ue_ue.ParticleModule.md).[constructor](ue_ue.ParticleModule.md#constructor)

## Properties

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[LODDuplicate](ue_ue.ParticleModule.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[LODValidity](ue_ue.ParticleModule.md#lodvalidity)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[ModuleEditorColor](ue_ue.ParticleModule.md#moduleeditorcolor)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[__tid_Object__](ue_ue.ParticleModule.md#__tid_object__)

___

### \_\_tid\_ParticleModuleVelocityBase\_\_

• **\_\_tid\_ParticleModuleVelocityBase\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[__tid_ParticleModule__](ue_ue.ParticleModule.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[b3DDrawMode](ue_ue.ParticleModule.md#b3ddrawmode)

___

### bApplyOwnerScale

• **bApplyOwnerScale**: `boolean`

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bCurvesAsColor](ue_ue.ParticleModule.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bEditable](ue_ue.ParticleModule.md#beditable)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bEnabled](ue_ue.ParticleModule.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bFinalUpdateModule](ue_ue.ParticleModule.md#bfinalupdatemodule)

___

### bInWorldSpace

• **bInWorldSpace**: `boolean`

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bRequiresLoopingNotification](ue_ue.ParticleModule.md#brequiresloopingnotification)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bSpawnModule](ue_ue.ParticleModule.md#bspawnmodule)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bSupported3DDrawMode](ue_ue.ParticleModule.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bSupportsRandomSeed](ue_ue.ParticleModule.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bUpdateForGPUEmitter](ue_ue.ParticleModule.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bUpdateModule](ue_ue.ParticleModule.md#bupdatemodule)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetClass](ue_ue.ParticleModule.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetName](ue_ue.ParticleModule.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetOuter](ue_ue.ParticleModule.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetWorld](ue_ue.ParticleModule.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleVelocityBase`](ue_ue.ParticleModuleVelocityBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleVelocityBase`](ue_ue.ParticleModuleVelocityBase.md)

#### Overrides

[ParticleModule](ue_ue.ParticleModule.md).[Find](ue_ue.ParticleModule.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleVelocityBase`](ue_ue.ParticleModuleVelocityBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleVelocityBase`](ue_ue.ParticleModuleVelocityBase.md)

#### Overrides

[ParticleModule](ue_ue.ParticleModule.md).[Load](ue_ue.ParticleModule.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModule](ue_ue.ParticleModule.md).[StaticClass](ue_ue.ParticleModule.md#staticclass)
