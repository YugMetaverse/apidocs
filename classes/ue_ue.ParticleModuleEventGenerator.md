[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleEventGenerator

# Class: ParticleModuleEventGenerator

[ue/ue](../modules/ue_ue.md).ParticleModuleEventGenerator

## Hierarchy

- [`ParticleModuleEventBase`](ue_ue.ParticleModuleEventBase.md)

  ↳ **`ParticleModuleEventGenerator`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleEventGenerator.md#constructor)

### Properties

- [Events](ue_ue.ParticleModuleEventGenerator.md#events)
- [LODDuplicate](ue_ue.ParticleModuleEventGenerator.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleEventGenerator.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleEventGenerator.md#moduleeditorcolor)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleEventGenerator.md#__tid_object__)
- [\_\_tid\_ParticleModuleEventBase\_\_](ue_ue.ParticleModuleEventGenerator.md#__tid_particlemoduleeventbase__)
- [\_\_tid\_ParticleModuleEventGenerator\_\_](ue_ue.ParticleModuleEventGenerator.md#__tid_particlemoduleeventgenerator__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleEventGenerator.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleEventGenerator.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModuleEventGenerator.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleEventGenerator.md#beditable)
- [bEnabled](ue_ue.ParticleModuleEventGenerator.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleEventGenerator.md#bfinalupdatemodule)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleEventGenerator.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleEventGenerator.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleEventGenerator.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleEventGenerator.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleEventGenerator.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleEventGenerator.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleEventGenerator.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleEventGenerator.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleEventGenerator.md#getclass)
- [GetName](ue_ue.ParticleModuleEventGenerator.md#getname)
- [GetOuter](ue_ue.ParticleModuleEventGenerator.md#getouter)
- [GetWorld](ue_ue.ParticleModuleEventGenerator.md#getworld)
- [Find](ue_ue.ParticleModuleEventGenerator.md#find)
- [Load](ue_ue.ParticleModuleEventGenerator.md#load)
- [StaticClass](ue_ue.ParticleModuleEventGenerator.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleEventGenerator**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[constructor](ue_ue.ParticleModuleEventBase.md#constructor)

#### Defined in

[ue/ue.d.ts:6973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6973)

## Properties

### Events

• **Events**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleEvent_GenerateInfo`](ue_ue.ParticleEvent_GenerateInfo.md)\>

#### Defined in

[ue/ue.d.ts:6974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6974)

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

### \_\_tid\_ParticleModuleEventGenerator\_\_

• **\_\_tid\_ParticleModuleEventGenerator\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:6979](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6979)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleEventGenerator`](ue_ue.ParticleModuleEventGenerator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleEventGenerator`](ue_ue.ParticleModuleEventGenerator.md)

#### Overrides

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[Find](ue_ue.ParticleModuleEventBase.md#find)

#### Defined in

[ue/ue.d.ts:6976](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6976)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleEventGenerator`](ue_ue.ParticleModuleEventGenerator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleEventGenerator`](ue_ue.ParticleModuleEventGenerator.md)

#### Overrides

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[Load](ue_ue.ParticleModuleEventBase.md#load)

#### Defined in

[ue/ue.d.ts:6977](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6977)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleEventBase](ue_ue.ParticleModuleEventBase.md).[StaticClass](ue_ue.ParticleModuleEventBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:6975](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6975)
