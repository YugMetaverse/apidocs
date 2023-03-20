[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleBeamModifier

# Class: ParticleModuleBeamModifier

[ue/ue](../modules/ue_ue.md).ParticleModuleBeamModifier

## Hierarchy

- [`ParticleModuleBeamBase`](ue_ue.ParticleModuleBeamBase.md)

  ↳ **`ParticleModuleBeamModifier`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleBeamModifier.md#constructor)

### Properties

- [LODDuplicate](ue_ue.ParticleModuleBeamModifier.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleBeamModifier.md#lodvalidity)
- [ModifierType](ue_ue.ParticleModuleBeamModifier.md#modifiertype)
- [ModuleEditorColor](ue_ue.ParticleModuleBeamModifier.md#moduleeditorcolor)
- [Position](ue_ue.ParticleModuleBeamModifier.md#position)
- [PositionOptions](ue_ue.ParticleModuleBeamModifier.md#positionoptions)
- [Strength](ue_ue.ParticleModuleBeamModifier.md#strength)
- [StrengthOptions](ue_ue.ParticleModuleBeamModifier.md#strengthoptions)
- [Tangent](ue_ue.ParticleModuleBeamModifier.md#tangent)
- [TangentOptions](ue_ue.ParticleModuleBeamModifier.md#tangentoptions)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleBeamModifier.md#__tid_object__)
- [\_\_tid\_ParticleModuleBeamBase\_\_](ue_ue.ParticleModuleBeamModifier.md#__tid_particlemodulebeambase__)
- [\_\_tid\_ParticleModuleBeamModifier\_\_](ue_ue.ParticleModuleBeamModifier.md#__tid_particlemodulebeammodifier__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleBeamModifier.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleBeamModifier.md#b3ddrawmode)
- [bAbsoluteTangent](ue_ue.ParticleModuleBeamModifier.md#babsolutetangent)
- [bCurvesAsColor](ue_ue.ParticleModuleBeamModifier.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleBeamModifier.md#beditable)
- [bEnabled](ue_ue.ParticleModuleBeamModifier.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleBeamModifier.md#bfinalupdatemodule)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleBeamModifier.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleBeamModifier.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleBeamModifier.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleBeamModifier.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleBeamModifier.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleBeamModifier.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleBeamModifier.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleBeamModifier.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleBeamModifier.md#getclass)
- [GetName](ue_ue.ParticleModuleBeamModifier.md#getname)
- [GetOuter](ue_ue.ParticleModuleBeamModifier.md#getouter)
- [GetWorld](ue_ue.ParticleModuleBeamModifier.md#getworld)
- [Find](ue_ue.ParticleModuleBeamModifier.md#find)
- [Load](ue_ue.ParticleModuleBeamModifier.md#load)
- [StaticClass](ue_ue.ParticleModuleBeamModifier.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleBeamModifier**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[constructor](ue_ue.ParticleModuleBeamBase.md#constructor)

#### Defined in

[ue/ue.d.ts:55400](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55400)

## Properties

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[LODDuplicate](ue_ue.ParticleModuleBeamBase.md#lodduplicate)

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[LODValidity](ue_ue.ParticleModuleBeamBase.md#lodvalidity)

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6748)

___

### ModifierType

• **ModifierType**: [`BeamModifierType`](../enums/ue_ue.BeamModifierType.md)

#### Defined in

[ue/ue.d.ts:55401](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55401)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[ModuleEditorColor](ue_ue.ParticleModuleBeamBase.md#moduleeditorcolor)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6749)

___

### Position

• **Position**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

#### Defined in

[ue/ue.d.ts:55403](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55403)

___

### PositionOptions

• **PositionOptions**: [`BeamModifierOptions`](ue_ue.BeamModifierOptions.md)

#### Defined in

[ue/ue.d.ts:55402](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55402)

___

### Strength

• **Strength**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:55408](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55408)

___

### StrengthOptions

• **StrengthOptions**: [`BeamModifierOptions`](ue_ue.BeamModifierOptions.md)

#### Defined in

[ue/ue.d.ts:55407](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55407)

___

### Tangent

• **Tangent**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

#### Defined in

[ue/ue.d.ts:55405](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55405)

___

### TangentOptions

• **TangentOptions**: [`BeamModifierOptions`](ue_ue.BeamModifierOptions.md)

#### Defined in

[ue/ue.d.ts:55404](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55404)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[__tid_Object__](ue_ue.ParticleModuleBeamBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModuleBeamBase\_\_

• **\_\_tid\_ParticleModuleBeamBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[__tid_ParticleModuleBeamBase__](ue_ue.ParticleModuleBeamBase.md#__tid_particlemodulebeambase__)

#### Defined in

[ue/ue.d.ts:55382](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55382)

___

### \_\_tid\_ParticleModuleBeamModifier\_\_

• **\_\_tid\_ParticleModuleBeamModifier\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:55413](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55413)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleBeamBase.md#__tid_particlemodule__)

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[b3DDrawMode](ue_ue.ParticleModuleBeamBase.md#b3ddrawmode)

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6741)

___

### bAbsoluteTangent

• **bAbsoluteTangent**: `boolean`

#### Defined in

[ue/ue.d.ts:55406](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55406)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bCurvesAsColor](ue_ue.ParticleModuleBeamBase.md#bcurvesascolor)

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6740)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bEditable](ue_ue.ParticleModuleBeamBase.md#beditable)

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6744)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bEnabled](ue_ue.ParticleModuleBeamBase.md#benabled)

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleBeamBase.md#bfinalupdatemodule)

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6738)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleBeamBase.md#brequiresloopingnotification)

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6747)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bSpawnModule](ue_ue.ParticleModuleBeamBase.md#bspawnmodule)

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleBeamBase.md#bsupported3ddrawmode)

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleBeamBase.md#bsupportsrandomseed)

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6746)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleBeamBase.md#bupdateforgpuemitter)

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bUpdateModule](ue_ue.ParticleModuleBeamBase.md#bupdatemodule)

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

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleBeamBase.md#createdefaultsubobject)

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

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleBeamBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetClass](ue_ue.ParticleModuleBeamBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetName](ue_ue.ParticleModuleBeamBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetOuter](ue_ue.ParticleModuleBeamBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetWorld](ue_ue.ParticleModuleBeamBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleBeamModifier`](ue_ue.ParticleModuleBeamModifier.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleBeamModifier`](ue_ue.ParticleModuleBeamModifier.md)

#### Overrides

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[Find](ue_ue.ParticleModuleBeamBase.md#find)

#### Defined in

[ue/ue.d.ts:55410](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55410)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleBeamModifier`](ue_ue.ParticleModuleBeamModifier.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleBeamModifier`](ue_ue.ParticleModuleBeamModifier.md)

#### Overrides

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[Load](ue_ue.ParticleModuleBeamBase.md#load)

#### Defined in

[ue/ue.d.ts:55411](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55411)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[StaticClass](ue_ue.ParticleModuleBeamBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:55409](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55409)
