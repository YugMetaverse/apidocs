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

## Properties

### CollisionMesh

• **CollisionMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### DampingRate

• **DampingRate**: `number`

___

### DebugLatForce

• **DebugLatForce**: `number`

___

### DebugLatSlip

• **DebugLatSlip**: `number`

___

### DebugLongForce

• **DebugLongForce**: `number`

___

### DebugLongSlip

• **DebugLongSlip**: `number`

___

### DebugNormalizedTireLoad

• **DebugNormalizedTireLoad**: `number`

___

### DebugWheelTorque

• **DebugWheelTorque**: `number`

___

### LatStiffMaxLoad

• **LatStiffMaxLoad**: `number`

___

### LatStiffValue

• **LatStiffValue**: `number`

___

### Location

• **Location**: [`Vector`](ue_ue_s.Vector.md)

___

### LongStiffValue

• **LongStiffValue**: `number`

___

### Mass

• **Mass**: `number`

___

### MaxBrakeTorque

• **MaxBrakeTorque**: `number`

___

### MaxHandBrakeTorque

• **MaxHandBrakeTorque**: `number`

___

### Offset

• **Offset**: [`Vector`](ue_ue_s.Vector.md)

___

### OldLocation

• **OldLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### ShapeRadius

• **ShapeRadius**: `number`

___

### ShapeWidth

• **ShapeWidth**: `number`

___

### SteerAngle

• **SteerAngle**: `number`

___

### SuspensionDampingRatio

• **SuspensionDampingRatio**: `number`

___

### SuspensionForceOffset

• **SuspensionForceOffset**: `number`

___

### SuspensionMaxDrop

• **SuspensionMaxDrop**: `number`

___

### SuspensionMaxRaise

• **SuspensionMaxRaise**: `number`

___

### SuspensionNaturalFrequency

• **SuspensionNaturalFrequency**: `number`

___

### SweepType

• **SweepType**: [`EWheelSweepType`](../enums/ue_ue.EWheelSweepType.md)

___

### TireConfig

• **TireConfig**: [`TireConfig`](ue_ue.TireConfig.md)

___

### TireType

• **TireType**: [`TireType`](ue_ue.TireType.md)

___

### VehicleSim

• **VehicleSim**: [`WheeledVehicleMovementComponent`](ue_ue.WheeledVehicleMovementComponent.md)

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

___

### WheelIndex

• **WheelIndex**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_VehicleWheel\_\_

• **\_\_tid\_VehicleWheel\_\_**: `boolean`

___

### bAffectedByHandbrake

• **bAffectedByHandbrake**: `boolean`

___

### bAutoAdjustCollisionSize

• **bAutoAdjustCollisionSize**: `boolean`

___

### bDontCreateShape

• **bDontCreateShape**: `boolean`

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

### GetRotationAngle

▸ **GetRotationAngle**(): `number`

#### Returns

`number`

___

### GetSteerAngle

▸ **GetSteerAngle**(): `number`

#### Returns

`number`

___

### GetSuspensionOffset

▸ **GetSuspensionOffset**(): `number`

#### Returns

`number`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### IsInAir

▸ **IsInAir**(): `boolean`

#### Returns

`boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
