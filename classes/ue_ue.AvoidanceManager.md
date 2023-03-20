[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AvoidanceManager

# Class: AvoidanceManager

[ue/ue](../modules/ue_ue.md).AvoidanceManager

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AvoidanceManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.AvoidanceManager.md#constructor)

### Properties

- [ArtificialRadiusExpansion](ue_ue.AvoidanceManager.md#artificialradiusexpansion)
- [DefaultTimeToLive](ue_ue.AvoidanceManager.md#defaulttimetolive)
- [DeltaTimeToPredict](ue_ue.AvoidanceManager.md#deltatimetopredict)
- [HeightCheckMargin](ue_ue.AvoidanceManager.md#heightcheckmargin)
- [LockTimeAfterAvoid](ue_ue.AvoidanceManager.md#locktimeafteravoid)
- [LockTimeAfterClean](ue_ue.AvoidanceManager.md#locktimeafterclean)
- [TestHeightDifference](ue_ue.AvoidanceManager.md#testheightdifference)
- [\_\_tid\_AvoidanceManager\_\_](ue_ue.AvoidanceManager.md#__tid_avoidancemanager__)
- [\_\_tid\_Object\_\_](ue_ue.AvoidanceManager.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AvoidanceManager.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AvoidanceManager.md#executeubergraph)
- [GetAvoidanceVelocityForComponent](ue_ue.AvoidanceManager.md#getavoidancevelocityforcomponent)
- [GetClass](ue_ue.AvoidanceManager.md#getclass)
- [GetName](ue_ue.AvoidanceManager.md#getname)
- [GetNewAvoidanceUID](ue_ue.AvoidanceManager.md#getnewavoidanceuid)
- [GetObjectCount](ue_ue.AvoidanceManager.md#getobjectcount)
- [GetOuter](ue_ue.AvoidanceManager.md#getouter)
- [GetWorld](ue_ue.AvoidanceManager.md#getworld)
- [RegisterMovementComponent](ue_ue.AvoidanceManager.md#registermovementcomponent)
- [Find](ue_ue.AvoidanceManager.md#find)
- [Load](ue_ue.AvoidanceManager.md#load)
- [StaticClass](ue_ue.AvoidanceManager.md#staticclass)

## Constructors

### constructor

• **new AvoidanceManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ArtificialRadiusExpansion

• **ArtificialRadiusExpansion**: `number`

___

### DefaultTimeToLive

• **DefaultTimeToLive**: `number`

___

### DeltaTimeToPredict

• **DeltaTimeToPredict**: `number`

___

### HeightCheckMargin

• **HeightCheckMargin**: `number`

___

### LockTimeAfterAvoid

• **LockTimeAfterAvoid**: `number`

___

### LockTimeAfterClean

• **LockTimeAfterClean**: `number`

___

### TestHeightDifference

• **TestHeightDifference**: `number`

___

### \_\_tid\_AvoidanceManager\_\_

• **\_\_tid\_AvoidanceManager\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

### GetAvoidanceVelocityForComponent

▸ **GetAvoidanceVelocityForComponent**(`MovementComp`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MovementComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MovementComponent`](ue_ue.MovementComponent.md)\> |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

### GetNewAvoidanceUID

▸ **GetNewAvoidanceUID**(): `number`

#### Returns

`number`

___

### GetObjectCount

▸ **GetObjectCount**(): `number`

#### Returns

`number`

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

### RegisterMovementComponent

▸ **RegisterMovementComponent**(`MovementComp`, `AvoidanceWeight?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MovementComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MovementComponent`](ue_ue.MovementComponent.md)\> |
| `AvoidanceWeight?` | `number` |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AvoidanceManager`](ue_ue.AvoidanceManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AvoidanceManager`](ue_ue.AvoidanceManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AvoidanceManager`](ue_ue.AvoidanceManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AvoidanceManager`](ue_ue.AvoidanceManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
