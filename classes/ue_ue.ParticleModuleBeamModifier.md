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

## Properties

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[LODDuplicate](ue_ue.ParticleModuleBeamBase.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[LODValidity](ue_ue.ParticleModuleBeamBase.md#lodvalidity)

___

### ModifierType

• **ModifierType**: [`BeamModifierType`](../enums/ue_ue.BeamModifierType.md)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[ModuleEditorColor](ue_ue.ParticleModuleBeamBase.md#moduleeditorcolor)

___

### Position

• **Position**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

___

### PositionOptions

• **PositionOptions**: [`BeamModifierOptions`](ue_ue.BeamModifierOptions.md)

___

### Strength

• **Strength**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### StrengthOptions

• **StrengthOptions**: [`BeamModifierOptions`](ue_ue.BeamModifierOptions.md)

___

### Tangent

• **Tangent**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

___

### TangentOptions

• **TangentOptions**: [`BeamModifierOptions`](ue_ue.BeamModifierOptions.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[__tid_Object__](ue_ue.ParticleModuleBeamBase.md#__tid_object__)

___

### \_\_tid\_ParticleModuleBeamBase\_\_

• **\_\_tid\_ParticleModuleBeamBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[__tid_ParticleModuleBeamBase__](ue_ue.ParticleModuleBeamBase.md#__tid_particlemodulebeambase__)

___

### \_\_tid\_ParticleModuleBeamModifier\_\_

• **\_\_tid\_ParticleModuleBeamModifier\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleBeamBase.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[b3DDrawMode](ue_ue.ParticleModuleBeamBase.md#b3ddrawmode)

___

### bAbsoluteTangent

• **bAbsoluteTangent**: `boolean`

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bCurvesAsColor](ue_ue.ParticleModuleBeamBase.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bEditable](ue_ue.ParticleModuleBeamBase.md#beditable)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bEnabled](ue_ue.ParticleModuleBeamBase.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleBeamBase.md#bfinalupdatemodule)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleBeamBase.md#brequiresloopingnotification)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bSpawnModule](ue_ue.ParticleModuleBeamBase.md#bspawnmodule)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleBeamBase.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleBeamBase.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleBeamBase.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bUpdateModule](ue_ue.ParticleModuleBeamBase.md#bupdatemodule)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetClass](ue_ue.ParticleModuleBeamBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetName](ue_ue.ParticleModuleBeamBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetOuter](ue_ue.ParticleModuleBeamBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetWorld](ue_ue.ParticleModuleBeamBase.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[StaticClass](ue_ue.ParticleModuleBeamBase.md#staticclass)
