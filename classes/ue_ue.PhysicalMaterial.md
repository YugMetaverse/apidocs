[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PhysicalMaterial

# Class: PhysicalMaterial

[ue/ue](../modules/ue_ue.md).PhysicalMaterial

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PhysicalMaterial`**

## Table of contents

### Constructors

- [constructor](ue_ue.PhysicalMaterial.md#constructor)

### Properties

- [Density](ue_ue.PhysicalMaterial.md#density)
- [DestructibleDamageThresholdScale](ue_ue.PhysicalMaterial.md#destructibledamagethresholdscale)
- [Friction](ue_ue.PhysicalMaterial.md#friction)
- [FrictionCombineMode](ue_ue.PhysicalMaterial.md#frictioncombinemode)
- [PhysicalMaterialProperty](ue_ue.PhysicalMaterial.md#physicalmaterialproperty)
- [RaiseMassToPower](ue_ue.PhysicalMaterial.md#raisemasstopower)
- [Restitution](ue_ue.PhysicalMaterial.md#restitution)
- [RestitutionCombineMode](ue_ue.PhysicalMaterial.md#restitutioncombinemode)
- [SurfaceType](ue_ue.PhysicalMaterial.md#surfacetype)
- [TireFrictionScale](ue_ue.PhysicalMaterial.md#tirefrictionscale)
- [TireFrictionScales](ue_ue.PhysicalMaterial.md#tirefrictionscales)
- [\_\_tid\_Object\_\_](ue_ue.PhysicalMaterial.md#__tid_object__)
- [\_\_tid\_PhysicalMaterial\_\_](ue_ue.PhysicalMaterial.md#__tid_physicalmaterial__)
- [bOverrideFrictionCombineMode](ue_ue.PhysicalMaterial.md#boverridefrictioncombinemode)
- [bOverrideRestitutionCombineMode](ue_ue.PhysicalMaterial.md#boverriderestitutioncombinemode)

### Methods

- [CreateDefaultSubobject](ue_ue.PhysicalMaterial.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PhysicalMaterial.md#executeubergraph)
- [GetClass](ue_ue.PhysicalMaterial.md#getclass)
- [GetName](ue_ue.PhysicalMaterial.md#getname)
- [GetOuter](ue_ue.PhysicalMaterial.md#getouter)
- [GetWorld](ue_ue.PhysicalMaterial.md#getworld)
- [Find](ue_ue.PhysicalMaterial.md#find)
- [Load](ue_ue.PhysicalMaterial.md#load)
- [StaticClass](ue_ue.PhysicalMaterial.md#staticclass)

## Constructors

### constructor

• **new PhysicalMaterial**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Density

• **Density**: `number`

___

### DestructibleDamageThresholdScale

• **DestructibleDamageThresholdScale**: `number`

___

### Friction

• **Friction**: `number`

___

### FrictionCombineMode

• **FrictionCombineMode**: [`EFrictionCombineMode`](../enums/ue_ue.EFrictionCombineMode.md)

___

### PhysicalMaterialProperty

• **PhysicalMaterialProperty**: [`PhysicalMaterialPropertyBase`](ue_ue.PhysicalMaterialPropertyBase.md)

___

### RaiseMassToPower

• **RaiseMassToPower**: `number`

___

### Restitution

• **Restitution**: `number`

___

### RestitutionCombineMode

• **RestitutionCombineMode**: [`EFrictionCombineMode`](../enums/ue_ue.EFrictionCombineMode.md)

___

### SurfaceType

• **SurfaceType**: [`EPhysicalSurface`](../enums/ue_ue.EPhysicalSurface.md)

___

### TireFrictionScale

• **TireFrictionScale**: `number`

___

### TireFrictionScales

• **TireFrictionScales**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TireFrictionScalePair`](ue_ue.TireFrictionScalePair.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PhysicalMaterial\_\_

• **\_\_tid\_PhysicalMaterial\_\_**: `boolean`

___

### bOverrideFrictionCombineMode

• **bOverrideFrictionCombineMode**: `boolean`

___

### bOverrideRestitutionCombineMode

• **bOverrideRestitutionCombineMode**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
