[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DamageType

# Class: DamageType

[ue/ue](../modules/ue_ue.md).DamageType

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`DamageType`**

  ↳↳ [`DmgTypeBP_Environmental_C`](ue_ue.Engine.EngineDamageTypes.DmgTypeBP_Environmental.DmgTypeBP_Environmental_C.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DamageType.md#constructor)

### Properties

- [DamageFalloff](ue_ue.DamageType.md#damagefalloff)
- [DamageImpulse](ue_ue.DamageType.md#damageimpulse)
- [DestructibleDamageSpreadScale](ue_ue.DamageType.md#destructibledamagespreadscale)
- [DestructibleImpulse](ue_ue.DamageType.md#destructibleimpulse)
- [\_\_tid\_DamageType\_\_](ue_ue.DamageType.md#__tid_damagetype__)
- [\_\_tid\_Object\_\_](ue_ue.DamageType.md#__tid_object__)
- [bCausedByWorld](ue_ue.DamageType.md#bcausedbyworld)
- [bRadialDamageVelChange](ue_ue.DamageType.md#bradialdamagevelchange)
- [bScaleMomentumByMass](ue_ue.DamageType.md#bscalemomentumbymass)

### Methods

- [CreateDefaultSubobject](ue_ue.DamageType.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DamageType.md#executeubergraph)
- [GetClass](ue_ue.DamageType.md#getclass)
- [GetName](ue_ue.DamageType.md#getname)
- [GetOuter](ue_ue.DamageType.md#getouter)
- [GetWorld](ue_ue.DamageType.md#getworld)
- [Find](ue_ue.DamageType.md#find)
- [Load](ue_ue.DamageType.md#load)
- [StaticClass](ue_ue.DamageType.md#staticclass)

## Constructors

### constructor

• **new DamageType**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### DamageFalloff

• **DamageFalloff**: `number`

___

### DamageImpulse

• **DamageImpulse**: `number`

___

### DestructibleDamageSpreadScale

• **DestructibleDamageSpreadScale**: `number`

___

### DestructibleImpulse

• **DestructibleImpulse**: `number`

___

### \_\_tid\_DamageType\_\_

• **\_\_tid\_DamageType\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bCausedByWorld

• **bCausedByWorld**: `boolean`

___

### bRadialDamageVelChange

• **bRadialDamageVelChange**: `boolean`

___

### bScaleMomentumByMass

• **bScaleMomentumByMass**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DamageType`](ue_ue.DamageType.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DamageType`](ue_ue.DamageType.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DamageType`](ue_ue.DamageType.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DamageType`](ue_ue.DamageType.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
