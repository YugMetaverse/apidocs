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

#### Defined in

[ue/ue.d.ts:10076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10076)

## Properties

### ArtificialRadiusExpansion

• **ArtificialRadiusExpansion**: `number`

#### Defined in

[ue/ue.d.ts:10081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10081)

___

### DefaultTimeToLive

• **DefaultTimeToLive**: `number`

#### Defined in

[ue/ue.d.ts:10077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10077)

___

### DeltaTimeToPredict

• **DeltaTimeToPredict**: `number`

#### Defined in

[ue/ue.d.ts:10080](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10080)

___

### HeightCheckMargin

• **HeightCheckMargin**: `number`

#### Defined in

[ue/ue.d.ts:10083](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10083)

___

### LockTimeAfterAvoid

• **LockTimeAfterAvoid**: `number`

#### Defined in

[ue/ue.d.ts:10078](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10078)

___

### LockTimeAfterClean

• **LockTimeAfterClean**: `number`

#### Defined in

[ue/ue.d.ts:10079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10079)

___

### TestHeightDifference

• **TestHeightDifference**: `number`

#### Defined in

[ue/ue.d.ts:10082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10082)

___

### \_\_tid\_AvoidanceManager\_\_

• **\_\_tid\_AvoidanceManager\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:10092](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10092)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetAvoidanceVelocityForComponent

▸ **GetAvoidanceVelocityForComponent**(`MovementComp`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MovementComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MovementComponent`](ue_ue.MovementComponent.md)\> |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:10084](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10084)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetNewAvoidanceUID

▸ **GetNewAvoidanceUID**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:10085](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10085)

___

### GetObjectCount

▸ **GetObjectCount**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:10086](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10086)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:10087](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10087)

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

#### Defined in

[ue/ue.d.ts:10089](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10089)

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

#### Defined in

[ue/ue.d.ts:10090](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10090)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:10088](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10088)
