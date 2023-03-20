[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleEventReceiverSpawn

# Class: ParticleModuleEventReceiverSpawn

[ue/ue](../modules/ue_ue.md).ParticleModuleEventReceiverSpawn

## Hierarchy

- [`ParticleModuleEventReceiverBase`](ue_ue.ParticleModuleEventReceiverBase.md)

  ↳ **`ParticleModuleEventReceiverSpawn`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleEventReceiverSpawn.md#constructor)

### Properties

- [EventGeneratorType](ue_ue.ParticleModuleEventReceiverSpawn.md#eventgeneratortype)
- [EventName](ue_ue.ParticleModuleEventReceiverSpawn.md#eventname)
- [InheritVelocityScale](ue_ue.ParticleModuleEventReceiverSpawn.md#inheritvelocityscale)
- [LODDuplicate](ue_ue.ParticleModuleEventReceiverSpawn.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleEventReceiverSpawn.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleEventReceiverSpawn.md#moduleeditorcolor)
- [PhysicalMaterials](ue_ue.ParticleModuleEventReceiverSpawn.md#physicalmaterials)
- [SpawnCount](ue_ue.ParticleModuleEventReceiverSpawn.md#spawncount)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleEventReceiverSpawn.md#__tid_object__)
- [\_\_tid\_ParticleModuleEventBase\_\_](ue_ue.ParticleModuleEventReceiverSpawn.md#__tid_particlemoduleeventbase__)
- [\_\_tid\_ParticleModuleEventReceiverBase\_\_](ue_ue.ParticleModuleEventReceiverSpawn.md#__tid_particlemoduleeventreceiverbase__)
- [\_\_tid\_ParticleModuleEventReceiverSpawn\_\_](ue_ue.ParticleModuleEventReceiverSpawn.md#__tid_particlemoduleeventreceiverspawn__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleEventReceiverSpawn.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleEventReceiverSpawn.md#b3ddrawmode)
- [bBanPhysicalMaterials](ue_ue.ParticleModuleEventReceiverSpawn.md#bbanphysicalmaterials)
- [bCurvesAsColor](ue_ue.ParticleModuleEventReceiverSpawn.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleEventReceiverSpawn.md#beditable)
- [bEnabled](ue_ue.ParticleModuleEventReceiverSpawn.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleEventReceiverSpawn.md#bfinalupdatemodule)
- [bInheritVelocity](ue_ue.ParticleModuleEventReceiverSpawn.md#binheritvelocity)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleEventReceiverSpawn.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleEventReceiverSpawn.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleEventReceiverSpawn.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleEventReceiverSpawn.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleEventReceiverSpawn.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleEventReceiverSpawn.md#bupdatemodule)
- [bUsePSysLocation](ue_ue.ParticleModuleEventReceiverSpawn.md#busepsyslocation)
- [bUseParticleTime](ue_ue.ParticleModuleEventReceiverSpawn.md#buseparticletime)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleEventReceiverSpawn.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleEventReceiverSpawn.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleEventReceiverSpawn.md#getclass)
- [GetName](ue_ue.ParticleModuleEventReceiverSpawn.md#getname)
- [GetOuter](ue_ue.ParticleModuleEventReceiverSpawn.md#getouter)
- [GetWorld](ue_ue.ParticleModuleEventReceiverSpawn.md#getworld)
- [Find](ue_ue.ParticleModuleEventReceiverSpawn.md#find)
- [Load](ue_ue.ParticleModuleEventReceiverSpawn.md#load)
- [StaticClass](ue_ue.ParticleModuleEventReceiverSpawn.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleEventReceiverSpawn**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[constructor](ue_ue.ParticleModuleEventReceiverBase.md#constructor)

## Properties

### EventGeneratorType

• **EventGeneratorType**: [`EParticleEventType`](../enums/ue_ue.EParticleEventType.md)

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[EventGeneratorType](ue_ue.ParticleModuleEventReceiverBase.md#eventgeneratortype)

___

### EventName

• **EventName**: `string`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[EventName](ue_ue.ParticleModuleEventReceiverBase.md#eventname)

___

### InheritVelocityScale

• **InheritVelocityScale**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[LODDuplicate](ue_ue.ParticleModuleEventReceiverBase.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[LODValidity](ue_ue.ParticleModuleEventReceiverBase.md#lodvalidity)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[ModuleEditorColor](ue_ue.ParticleModuleEventReceiverBase.md#moduleeditorcolor)

___

### PhysicalMaterials

• **PhysicalMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)\>

___

### SpawnCount

• **SpawnCount**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[__tid_Object__](ue_ue.ParticleModuleEventReceiverBase.md#__tid_object__)

___

### \_\_tid\_ParticleModuleEventBase\_\_

• **\_\_tid\_ParticleModuleEventBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[__tid_ParticleModuleEventBase__](ue_ue.ParticleModuleEventReceiverBase.md#__tid_particlemoduleeventbase__)

___

### \_\_tid\_ParticleModuleEventReceiverBase\_\_

• **\_\_tid\_ParticleModuleEventReceiverBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[__tid_ParticleModuleEventReceiverBase__](ue_ue.ParticleModuleEventReceiverBase.md#__tid_particlemoduleeventreceiverbase__)

___

### \_\_tid\_ParticleModuleEventReceiverSpawn\_\_

• **\_\_tid\_ParticleModuleEventReceiverSpawn\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleEventReceiverBase.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[b3DDrawMode](ue_ue.ParticleModuleEventReceiverBase.md#b3ddrawmode)

___

### bBanPhysicalMaterials

• **bBanPhysicalMaterials**: `boolean`

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[bCurvesAsColor](ue_ue.ParticleModuleEventReceiverBase.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[bEditable](ue_ue.ParticleModuleEventReceiverBase.md#beditable)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[bEnabled](ue_ue.ParticleModuleEventReceiverBase.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleEventReceiverBase.md#bfinalupdatemodule)

___

### bInheritVelocity

• **bInheritVelocity**: `boolean`

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleEventReceiverBase.md#brequiresloopingnotification)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[bSpawnModule](ue_ue.ParticleModuleEventReceiverBase.md#bspawnmodule)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleEventReceiverBase.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleEventReceiverBase.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleEventReceiverBase.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[bUpdateModule](ue_ue.ParticleModuleEventReceiverBase.md#bupdatemodule)

___

### bUsePSysLocation

• **bUsePSysLocation**: `boolean`

___

### bUseParticleTime

• **bUseParticleTime**: `boolean`

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

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleEventReceiverBase.md#createdefaultsubobject)

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

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleEventReceiverBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[GetClass](ue_ue.ParticleModuleEventReceiverBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[GetName](ue_ue.ParticleModuleEventReceiverBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[GetOuter](ue_ue.ParticleModuleEventReceiverBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[GetWorld](ue_ue.ParticleModuleEventReceiverBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleEventReceiverSpawn`](ue_ue.ParticleModuleEventReceiverSpawn.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleEventReceiverSpawn`](ue_ue.ParticleModuleEventReceiverSpawn.md)

#### Overrides

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[Find](ue_ue.ParticleModuleEventReceiverBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleEventReceiverSpawn`](ue_ue.ParticleModuleEventReceiverSpawn.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleEventReceiverSpawn`](ue_ue.ParticleModuleEventReceiverSpawn.md)

#### Overrides

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[Load](ue_ue.ParticleModuleEventReceiverBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleEventReceiverBase](ue_ue.ParticleModuleEventReceiverBase.md).[StaticClass](ue_ue.ParticleModuleEventReceiverBase.md#staticclass)
