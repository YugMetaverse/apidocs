[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KismetAnimationLibrary

# Class: KismetAnimationLibrary

[ue/ue](../modules/ue_ue.md).KismetAnimationLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`KismetAnimationLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.KismetAnimationLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.KismetAnimationLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_KismetAnimationLibrary\_\_](ue_ue.KismetAnimationLibrary.md#__tid_kismetanimationlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.KismetAnimationLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.KismetAnimationLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.KismetAnimationLibrary.md#executeubergraph)
- [GetClass](ue_ue.KismetAnimationLibrary.md#getclass)
- [GetName](ue_ue.KismetAnimationLibrary.md#getname)
- [GetOuter](ue_ue.KismetAnimationLibrary.md#getouter)
- [GetWorld](ue_ue.KismetAnimationLibrary.md#getworld)
- [Find](ue_ue.KismetAnimationLibrary.md#find)
- [K2\_CalculateVelocityFromPositionHistory](ue_ue.KismetAnimationLibrary.md#k2_calculatevelocityfrompositionhistory)
- [K2\_CalculateVelocityFromSockets](ue_ue.KismetAnimationLibrary.md#k2_calculatevelocityfromsockets)
- [K2\_DirectionBetweenSockets](ue_ue.KismetAnimationLibrary.md#k2_directionbetweensockets)
- [K2\_DistanceBetweenTwoSocketsAndMapRange](ue_ue.KismetAnimationLibrary.md#k2_distancebetweentwosocketsandmaprange)
- [K2\_EndProfilingTimer](ue_ue.KismetAnimationLibrary.md#k2_endprofilingtimer)
- [K2\_LookAt](ue_ue.KismetAnimationLibrary.md#k2_lookat)
- [K2\_MakePerlinNoiseAndRemap](ue_ue.KismetAnimationLibrary.md#k2_makeperlinnoiseandremap)
- [K2\_MakePerlinNoiseVectorAndRemap](ue_ue.KismetAnimationLibrary.md#k2_makeperlinnoisevectorandremap)
- [K2\_StartProfilingTimer](ue_ue.KismetAnimationLibrary.md#k2_startprofilingtimer)
- [K2\_TwoBoneIK](ue_ue.KismetAnimationLibrary.md#k2_twoboneik)
- [Load](ue_ue.KismetAnimationLibrary.md#load)
- [StaticClass](ue_ue.KismetAnimationLibrary.md#staticclass)

## Constructors

### constructor

• **new KismetAnimationLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_KismetAnimationLibrary\_\_

• **\_\_tid\_KismetAnimationLibrary\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`KismetAnimationLibrary`](ue_ue.KismetAnimationLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`KismetAnimationLibrary`](ue_ue.KismetAnimationLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### K2\_CalculateVelocityFromPositionHistory

▸ `Static` **K2_CalculateVelocityFromPositionHistory**(`DeltaSeconds`, `Position`, `History`, `NumberOfSamples`, `VelocityMin`, `VelocityMax`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaSeconds` | `number` |
| `Position` | [`Vector`](ue_ue_s.Vector.md) |
| `History` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PositionHistory`](ue_ue.PositionHistory.md)\> |
| `NumberOfSamples` | `number` |
| `VelocityMin` | `number` |
| `VelocityMax` | `number` |

#### Returns

`number`

___

### K2\_CalculateVelocityFromSockets

▸ `Static` **K2_CalculateVelocityFromSockets**(`DeltaSeconds`, `Component`, `SocketOrBoneName`, `ReferenceSocketOrBone`, `SocketSpace`, `OffsetInBoneSpace`, `History`, `NumberOfSamples`, `VelocityMin`, `VelocityMax`, `EasingType`, `CustomCurve`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaSeconds` | `number` |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\> |
| `SocketOrBoneName` | `string` |
| `ReferenceSocketOrBone` | `string` |
| `SocketSpace` | [`ERelativeTransformSpace`](../enums/ue_ue.ERelativeTransformSpace.md) |
| `OffsetInBoneSpace` | [`Vector`](ue_ue_s.Vector.md) |
| `History` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PositionHistory`](ue_ue.PositionHistory.md)\> |
| `NumberOfSamples` | `number` |
| `VelocityMin` | `number` |
| `VelocityMax` | `number` |
| `EasingType` | [`EEasingFuncType`](../enums/ue_ue.EEasingFuncType.md) |
| `CustomCurve` | [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md) |

#### Returns

`number`

___

### K2\_DirectionBetweenSockets

▸ `Static` **K2_DirectionBetweenSockets**(`Component`, `SocketOrBoneNameFrom`, `SocketOrBoneNameTo`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\> |
| `SocketOrBoneNameFrom` | `string` |
| `SocketOrBoneNameTo` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### K2\_DistanceBetweenTwoSocketsAndMapRange

▸ `Static` **K2_DistanceBetweenTwoSocketsAndMapRange**(`Component`, `SocketOrBoneNameA`, `SocketSpaceA`, `SocketOrBoneNameB`, `SocketSpaceB`, `bRemapRange`, `InRangeMin`, `InRangeMax`, `OutRangeMin`, `OutRangeMax`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\> |
| `SocketOrBoneNameA` | `string` |
| `SocketSpaceA` | [`ERelativeTransformSpace`](../enums/ue_ue.ERelativeTransformSpace.md) |
| `SocketOrBoneNameB` | `string` |
| `SocketSpaceB` | [`ERelativeTransformSpace`](../enums/ue_ue.ERelativeTransformSpace.md) |
| `bRemapRange` | `boolean` |
| `InRangeMin` | `number` |
| `InRangeMax` | `number` |
| `OutRangeMin` | `number` |
| `OutRangeMax` | `number` |

#### Returns

`number`

___

### K2\_EndProfilingTimer

▸ `Static` **K2_EndProfilingTimer**(`bLog?`, `LogPrefix?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bLog?` | `boolean` |
| `LogPrefix?` | `string` |

#### Returns

`number`

___

### K2\_LookAt

▸ `Static` **K2_LookAt**(`CurrentTransform`, `TargetPosition`, `LookAtVector`, `bUseUpVector`, `UpVector`, `ClampConeInDegree`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `CurrentTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `TargetPosition` | [`Vector`](ue_ue_s.Vector.md) |
| `LookAtVector` | [`Vector`](ue_ue_s.Vector.md) |
| `bUseUpVector` | `boolean` |
| `UpVector` | [`Vector`](ue_ue_s.Vector.md) |
| `ClampConeInDegree` | `number` |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### K2\_MakePerlinNoiseAndRemap

▸ `Static` **K2_MakePerlinNoiseAndRemap**(`Value`, `RangeOutMin`, `RangeOutMax`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |
| `RangeOutMin` | `number` |
| `RangeOutMax` | `number` |

#### Returns

`number`

___

### K2\_MakePerlinNoiseVectorAndRemap

▸ `Static` **K2_MakePerlinNoiseVectorAndRemap**(`X`, `Y`, `Z`, `RangeOutMinX`, `RangeOutMaxX`, `RangeOutMinY`, `RangeOutMaxY`, `RangeOutMinZ`, `RangeOutMaxZ`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `X` | `number` |
| `Y` | `number` |
| `Z` | `number` |
| `RangeOutMinX` | `number` |
| `RangeOutMaxX` | `number` |
| `RangeOutMinY` | `number` |
| `RangeOutMaxY` | `number` |
| `RangeOutMinZ` | `number` |
| `RangeOutMaxZ` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### K2\_StartProfilingTimer

▸ `Static` **K2_StartProfilingTimer**(): `void`

#### Returns

`void`

___

### K2\_TwoBoneIK

▸ `Static` **K2_TwoBoneIK**(`RootPos`, `JointPos`, `EndPos`, `JointTarget`, `Effector`, `OutJointPos`, `OutEndPos`, `bAllowStretching`, `StartStretchRatio`, `MaxStretchScale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RootPos` | [`Vector`](ue_ue_s.Vector.md) |
| `JointPos` | [`Vector`](ue_ue_s.Vector.md) |
| `EndPos` | [`Vector`](ue_ue_s.Vector.md) |
| `JointTarget` | [`Vector`](ue_ue_s.Vector.md) |
| `Effector` | [`Vector`](ue_ue_s.Vector.md) |
| `OutJointPos` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `OutEndPos` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `bAllowStretching` | `boolean` |
| `StartStretchRatio` | `number` |
| `MaxStretchScale` | `number` |

#### Returns

`void`

___

### Load

▸ `Static` **Load**(`InName`): [`KismetAnimationLibrary`](ue_ue.KismetAnimationLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`KismetAnimationLibrary`](ue_ue.KismetAnimationLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
