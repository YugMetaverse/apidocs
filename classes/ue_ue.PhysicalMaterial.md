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

#### Defined in

[ue/ue.d.ts:756](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L756)

## Properties

### Density

• **Density**: `number`

#### Defined in

[ue/ue.d.ts:763](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L763)

___

### DestructibleDamageThresholdScale

• **DestructibleDamageThresholdScale**: `number`

#### Defined in

[ue/ue.d.ts:765](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L765)

___

### Friction

• **Friction**: `number`

#### Defined in

[ue/ue.d.ts:757](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L757)

___

### FrictionCombineMode

• **FrictionCombineMode**: [`EFrictionCombineMode`](../enums/ue_ue.EFrictionCombineMode.md)

#### Defined in

[ue/ue.d.ts:758](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L758)

___

### PhysicalMaterialProperty

• **PhysicalMaterialProperty**: [`PhysicalMaterialPropertyBase`](ue_ue.PhysicalMaterialPropertyBase.md)

#### Defined in

[ue/ue.d.ts:766](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L766)

___

### RaiseMassToPower

• **RaiseMassToPower**: `number`

#### Defined in

[ue/ue.d.ts:764](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L764)

___

### Restitution

• **Restitution**: `number`

#### Defined in

[ue/ue.d.ts:760](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L760)

___

### RestitutionCombineMode

• **RestitutionCombineMode**: [`EFrictionCombineMode`](../enums/ue_ue.EFrictionCombineMode.md)

#### Defined in

[ue/ue.d.ts:761](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L761)

___

### SurfaceType

• **SurfaceType**: [`EPhysicalSurface`](../enums/ue_ue.EPhysicalSurface.md)

#### Defined in

[ue/ue.d.ts:767](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L767)

___

### TireFrictionScale

• **TireFrictionScale**: `number`

#### Defined in

[ue/ue.d.ts:768](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L768)

___

### TireFrictionScales

• **TireFrictionScales**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TireFrictionScalePair`](ue_ue.TireFrictionScalePair.md)\>

#### Defined in

[ue/ue.d.ts:769](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L769)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PhysicalMaterial\_\_

• **\_\_tid\_PhysicalMaterial\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:774](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L774)

___

### bOverrideFrictionCombineMode

• **bOverrideFrictionCombineMode**: `boolean`

#### Defined in

[ue/ue.d.ts:759](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L759)

___

### bOverrideRestitutionCombineMode

• **bOverrideRestitutionCombineMode**: `boolean`

#### Defined in

[ue/ue.d.ts:762](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L762)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:771](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L771)

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

#### Defined in

[ue/ue.d.ts:772](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L772)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:770](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L770)
