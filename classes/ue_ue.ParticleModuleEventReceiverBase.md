[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleEventReceiverBase

# Class: ParticleModuleEventReceiverBase

[ue/ue](../modules/ue_ue.md).ParticleModuleEventReceiverBase

## Hierarchy

- [`ParticleModuleEventBase`](ue_ue.ParticleModuleEventBase.md)

  ↳ **`ParticleModuleEventReceiverBase`**

  ↳↳ [`ParticleModuleEventReceiverKillParticles`](ue_ue.ParticleModuleEventReceiverKillParticles.md)

  ↳↳ [`ParticleModuleEventReceiverSpawn`](ue_ue.ParticleModuleEventReceiverSpawn.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleEventReceiverBase.md#constructor)

### Properties

- [EventGeneratorType](ue_ue.ParticleModuleEventReceiverBase.md#eventgeneratortype)
- [EventName](ue_ue.ParticleModuleEventReceiverBase.md#eventname)
- [LODDuplicate](ue_ue.ParticleModuleEventReceiverBase.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleEventReceiverBase.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleEventReceiverBase.md#moduleeditorcolor)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleEventReceiverBase.md#__tid_object__)
- [\_\_tid\_ParticleModuleEventBase\_\_](ue_ue.ParticleModuleEventReceiverBase.md#__tid_particlemoduleeventbase__)
- [\_\_tid\_ParticleModuleEventReceiverBase\_\_](ue_ue.ParticleModuleEventReceiverBase.md#__tid_particlemoduleeventreceiverbase__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleEventReceiverBase.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleEventReceiverBase.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModuleEventReceiverBase.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleEventReceiverBase.md#beditable)
- [bEnabled](ue_ue.ParticleModuleEventReceiverBase.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleEventReceiverBase.md#bfinalupdatemodule)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleEventReceiverBase.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleEventReceiverBase.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleEventReceiverBase.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleEventReceiverBase.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleEventReceiverBase.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleEventReceiverBase.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleEventReceiverBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleEventReceiverBase.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleEventReceiverBase.md#getclass)
- [GetName](ue_ue.ParticleModuleEventReceiverBase.md#getname)
- [GetOuter](ue_ue.ParticleModuleEventReceiverBase.md#getouter)
- [GetWorld](ue_ue.ParticleModuleEventReceiverBase.md#getworld)
- [Find](ue_ue.ParticleModuleEventReceiverBase.md#find)
- [Load](ue_ue.ParticleModuleEventReceiverBase.md#load)
- [StaticClass](ue_ue.ParticleModuleEventReceiverBase.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleEventReceiverBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[constructor](ue_ue.ParticleModuleEventBase.md#constructor)

#### Defined in

[ue/ue.d.ts:7052](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7052)

## Properties

### EventGeneratorType

• **EventGeneratorType**: [`EParticleEventType`](../enums/ue_ue.EParticleEventType.md)

#### Defined in

[ue/ue.d.ts:7053](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7053)

___

### EventName

• **EventName**: `string`

#### Defined in

[ue/ue.d.ts:7054](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7054)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[LODDuplicate](ue_ue.ParticleModuleEventBase.md#lodduplicate)

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[LODValidity](ue_ue.ParticleModuleEventBase.md#lodvalidity)

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6748)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[ModuleEditorColor](ue_ue.ParticleModuleEventBase.md#moduleeditorcolor)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6749)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[__tid_Object__](ue_ue.ParticleModuleEventBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModuleEventBase\_\_

• **\_\_tid\_ParticleModuleEventBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[__tid_ParticleModuleEventBase__](ue_ue.ParticleModuleEventBase.md#__tid_particlemoduleeventbase__)

#### Defined in

[ue/ue.d.ts:6939](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6939)

___

### \_\_tid\_ParticleModuleEventReceiverBase\_\_

• **\_\_tid\_ParticleModuleEventReceiverBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7059](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7059)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleEventBase.md#__tid_particlemodule__)

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[b3DDrawMode](ue_ue.ParticleModuleEventBase.md#b3ddrawmode)

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6741)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[bCurvesAsColor](ue_ue.ParticleModuleEventBase.md#bcurvesascolor)

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6740)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[bEditable](ue_ue.ParticleModuleEventBase.md#beditable)

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6744)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[bEnabled](ue_ue.ParticleModuleEventBase.md#benabled)

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleEventBase.md#bfinalupdatemodule)

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6738)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleEventBase.md#brequiresloopingnotification)

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6747)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[bSpawnModule](ue_ue.ParticleModuleEventBase.md#bspawnmodule)

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleEventBase.md#bsupported3ddrawmode)

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleEventBase.md#bsupportsrandomseed)

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6746)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleEventBase.md#bupdateforgpuemitter)

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[bUpdateModule](ue_ue.ParticleModuleEventBase.md#bupdatemodule)

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

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleEventBase.md#createdefaultsubobject)

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

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleEventBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[GetClass](ue_ue.ParticleModuleEventBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[GetName](ue_ue.ParticleModuleEventBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[GetOuter](ue_ue.ParticleModuleEventBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[GetWorld](ue_ue.ParticleModuleEventBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleEventReceiverBase`](ue_ue.ParticleModuleEventReceiverBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleEventReceiverBase`](ue_ue.ParticleModuleEventReceiverBase.md)

#### Overrides

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[Find](ue_ue.ParticleModuleEventBase.md#find)

#### Defined in

[ue/ue.d.ts:7056](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7056)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleEventReceiverBase`](ue_ue.ParticleModuleEventReceiverBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleEventReceiverBase`](ue_ue.ParticleModuleEventReceiverBase.md)

#### Overrides

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[Load](ue_ue.ParticleModuleEventBase.md#load)

#### Defined in

[ue/ue.d.ts:7057](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7057)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[StaticClass](ue_ue.ParticleModuleEventBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:7055](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7055)
