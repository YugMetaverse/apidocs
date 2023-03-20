[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VehicleWheel

# Class: VehicleWheel

[ue/ue](../modules/ue_ue.md).VehicleWheel

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`VehicleWheel`**

## Table of contents

### Constructors

- [constructor](ue_ue.VehicleWheel.md#constructor)

### Properties

- [CollisionMesh](ue_ue.VehicleWheel.md#collisionmesh)
- [DampingRate](ue_ue.VehicleWheel.md#dampingrate)
- [DebugLatForce](ue_ue.VehicleWheel.md#debuglatforce)
- [DebugLatSlip](ue_ue.VehicleWheel.md#debuglatslip)
- [DebugLongForce](ue_ue.VehicleWheel.md#debuglongforce)
- [DebugLongSlip](ue_ue.VehicleWheel.md#debuglongslip)
- [DebugNormalizedTireLoad](ue_ue.VehicleWheel.md#debugnormalizedtireload)
- [DebugWheelTorque](ue_ue.VehicleWheel.md#debugwheeltorque)
- [LatStiffMaxLoad](ue_ue.VehicleWheel.md#latstiffmaxload)
- [LatStiffValue](ue_ue.VehicleWheel.md#latstiffvalue)
- [Location](ue_ue.VehicleWheel.md#location)
- [LongStiffValue](ue_ue.VehicleWheel.md#longstiffvalue)
- [Mass](ue_ue.VehicleWheel.md#mass)
- [MaxBrakeTorque](ue_ue.VehicleWheel.md#maxbraketorque)
- [MaxHandBrakeTorque](ue_ue.VehicleWheel.md#maxhandbraketorque)
- [Offset](ue_ue.VehicleWheel.md#offset)
- [OldLocation](ue_ue.VehicleWheel.md#oldlocation)
- [ShapeRadius](ue_ue.VehicleWheel.md#shaperadius)
- [ShapeWidth](ue_ue.VehicleWheel.md#shapewidth)
- [SteerAngle](ue_ue.VehicleWheel.md#steerangle)
- [SuspensionDampingRatio](ue_ue.VehicleWheel.md#suspensiondampingratio)
- [SuspensionForceOffset](ue_ue.VehicleWheel.md#suspensionforceoffset)
- [SuspensionMaxDrop](ue_ue.VehicleWheel.md#suspensionmaxdrop)
- [SuspensionMaxRaise](ue_ue.VehicleWheel.md#suspensionmaxraise)
- [SuspensionNaturalFrequency](ue_ue.VehicleWheel.md#suspensionnaturalfrequency)
- [SweepType](ue_ue.VehicleWheel.md#sweeptype)
- [TireConfig](ue_ue.VehicleWheel.md#tireconfig)
- [TireType](ue_ue.VehicleWheel.md#tiretype)
- [VehicleSim](ue_ue.VehicleWheel.md#vehiclesim)
- [Velocity](ue_ue.VehicleWheel.md#velocity)
- [WheelIndex](ue_ue.VehicleWheel.md#wheelindex)
- [\_\_tid\_Object\_\_](ue_ue.VehicleWheel.md#__tid_object__)
- [\_\_tid\_VehicleWheel\_\_](ue_ue.VehicleWheel.md#__tid_vehiclewheel__)
- [bAffectedByHandbrake](ue_ue.VehicleWheel.md#baffectedbyhandbrake)
- [bAutoAdjustCollisionSize](ue_ue.VehicleWheel.md#bautoadjustcollisionsize)
- [bDontCreateShape](ue_ue.VehicleWheel.md#bdontcreateshape)

### Methods

- [CreateDefaultSubobject](ue_ue.VehicleWheel.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VehicleWheel.md#executeubergraph)
- [GetClass](ue_ue.VehicleWheel.md#getclass)
- [GetName](ue_ue.VehicleWheel.md#getname)
- [GetOuter](ue_ue.VehicleWheel.md#getouter)
- [GetRotationAngle](ue_ue.VehicleWheel.md#getrotationangle)
- [GetSteerAngle](ue_ue.VehicleWheel.md#getsteerangle)
- [GetSuspensionOffset](ue_ue.VehicleWheel.md#getsuspensionoffset)
- [GetWorld](ue_ue.VehicleWheel.md#getworld)
- [IsInAir](ue_ue.VehicleWheel.md#isinair)
- [Find](ue_ue.VehicleWheel.md#find)
- [Load](ue_ue.VehicleWheel.md#load)
- [StaticClass](ue_ue.VehicleWheel.md#staticclass)

## Constructors

### constructor

• **new VehicleWheel**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:60433](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60433)

## Properties

### CollisionMesh

• **CollisionMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:60434](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60434)

___

### DampingRate

• **DampingRate**: `number`

#### Defined in

[ue/ue.d.ts:60441](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60441)

___

### DebugLatForce

• **DebugLatForce**: `number`

#### Defined in

[ue/ue.d.ts:60464](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60464)

___

### DebugLatSlip

• **DebugLatSlip**: `number`

#### Defined in

[ue/ue.d.ts:60460](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60460)

___

### DebugLongForce

• **DebugLongForce**: `number`

#### Defined in

[ue/ue.d.ts:60463](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60463)

___

### DebugLongSlip

• **DebugLongSlip**: `number`

#### Defined in

[ue/ue.d.ts:60459](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60459)

___

### DebugNormalizedTireLoad

• **DebugNormalizedTireLoad**: `number`

#### Defined in

[ue/ue.d.ts:60461](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60461)

___

### DebugWheelTorque

• **DebugWheelTorque**: `number`

#### Defined in

[ue/ue.d.ts:60462](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60462)

___

### LatStiffMaxLoad

• **LatStiffMaxLoad**: `number`

#### Defined in

[ue/ue.d.ts:60446](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60446)

___

### LatStiffValue

• **LatStiffValue**: `number`

#### Defined in

[ue/ue.d.ts:60447](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60447)

___

### Location

• **Location**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:60465](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60465)

___

### LongStiffValue

• **LongStiffValue**: `number`

#### Defined in

[ue/ue.d.ts:60448](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60448)

___

### Mass

• **Mass**: `number`

#### Defined in

[ue/ue.d.ts:60440](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60440)

___

### MaxBrakeTorque

• **MaxBrakeTorque**: `number`

#### Defined in

[ue/ue.d.ts:60455](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60455)

___

### MaxHandBrakeTorque

• **MaxHandBrakeTorque**: `number`

#### Defined in

[ue/ue.d.ts:60456](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60456)

___

### Offset

• **Offset**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:60437](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60437)

___

### OldLocation

• **OldLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:60466](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60466)

___

### ShapeRadius

• **ShapeRadius**: `number`

#### Defined in

[ue/ue.d.ts:60438](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60438)

___

### ShapeWidth

• **ShapeWidth**: `number`

#### Defined in

[ue/ue.d.ts:60439](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60439)

___

### SteerAngle

• **SteerAngle**: `number`

#### Defined in

[ue/ue.d.ts:60442](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60442)

___

### SuspensionDampingRatio

• **SuspensionDampingRatio**: `number`

#### Defined in

[ue/ue.d.ts:60453](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60453)

___

### SuspensionForceOffset

• **SuspensionForceOffset**: `number`

#### Defined in

[ue/ue.d.ts:60449](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60449)

___

### SuspensionMaxDrop

• **SuspensionMaxDrop**: `number`

#### Defined in

[ue/ue.d.ts:60451](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60451)

___

### SuspensionMaxRaise

• **SuspensionMaxRaise**: `number`

#### Defined in

[ue/ue.d.ts:60450](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60450)

___

### SuspensionNaturalFrequency

• **SuspensionNaturalFrequency**: `number`

#### Defined in

[ue/ue.d.ts:60452](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60452)

___

### SweepType

• **SweepType**: [`EWheelSweepType`](../enums/ue_ue.EWheelSweepType.md)

#### Defined in

[ue/ue.d.ts:60454](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60454)

___

### TireConfig

• **TireConfig**: [`TireConfig`](ue_ue.TireConfig.md)

#### Defined in

[ue/ue.d.ts:60445](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60445)

___

### TireType

• **TireType**: [`TireType`](ue_ue.TireType.md)

#### Defined in

[ue/ue.d.ts:60444](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60444)

___

### VehicleSim

• **VehicleSim**: [`WheeledVehicleMovementComponent`](ue_ue.WheeledVehicleMovementComponent.md)

#### Defined in

[ue/ue.d.ts:60457](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60457)

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:60467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60467)

___

### WheelIndex

• **WheelIndex**: `number`

#### Defined in

[ue/ue.d.ts:60458](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60458)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_VehicleWheel\_\_

• **\_\_tid\_VehicleWheel\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:60476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60476)

___

### bAffectedByHandbrake

• **bAffectedByHandbrake**: `boolean`

#### Defined in

[ue/ue.d.ts:60443](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60443)

___

### bAutoAdjustCollisionSize

• **bAutoAdjustCollisionSize**: `boolean`

#### Defined in

[ue/ue.d.ts:60436](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60436)

___

### bDontCreateShape

• **bDontCreateShape**: `boolean`

#### Defined in

[ue/ue.d.ts:60435](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60435)

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

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetRotationAngle

▸ **GetRotationAngle**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:60468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60468)

___

### GetSteerAngle

▸ **GetSteerAngle**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:60469](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60469)

___

### GetSuspensionOffset

▸ **GetSuspensionOffset**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:60470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60470)

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

### IsInAir

▸ **IsInAir**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:60471](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60471)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VehicleWheel`](ue_ue.VehicleWheel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VehicleWheel`](ue_ue.VehicleWheel.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:60473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60473)

___

### Load

▸ `Static` **Load**(`InName`): [`VehicleWheel`](ue_ue.VehicleWheel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VehicleWheel`](ue_ue.VehicleWheel.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:60474](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60474)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:60472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60472)
