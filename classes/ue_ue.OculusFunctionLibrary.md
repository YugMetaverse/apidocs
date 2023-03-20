[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / OculusFunctionLibrary

# Class: OculusFunctionLibrary

[ue/ue](../modules/ue_ue.md).OculusFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`OculusFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.OculusFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.OculusFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.OculusFunctionLibrary.md#__tid_object__)
- [\_\_tid\_OculusFunctionLibrary\_\_](ue_ue.OculusFunctionLibrary.md#__tid_oculusfunctionlibrary__)

### Methods

- [CreateDefaultSubobject](ue_ue.OculusFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.OculusFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.OculusFunctionLibrary.md#getclass)
- [GetName](ue_ue.OculusFunctionLibrary.md#getname)
- [GetOuter](ue_ue.OculusFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.OculusFunctionLibrary.md#getworld)
- [AddLoadingSplashScreen](ue_ue.OculusFunctionLibrary.md#addloadingsplashscreen)
- [ClearLoadingSplashScreens](ue_ue.OculusFunctionLibrary.md#clearloadingsplashscreens)
- [EnableAutoLoadingSplashScreen](ue_ue.OculusFunctionLibrary.md#enableautoloadingsplashscreen)
- [EnableOrientationTracking](ue_ue.OculusFunctionLibrary.md#enableorientationtracking)
- [EnablePositionTracking](ue_ue.OculusFunctionLibrary.md#enablepositiontracking)
- [Find](ue_ue.OculusFunctionLibrary.md#find)
- [GetAvailableDisplayFrequencies](ue_ue.OculusFunctionLibrary.md#getavailabledisplayfrequencies)
- [GetBaseRotationAndBaseOffsetInMeters](ue_ue.OculusFunctionLibrary.md#getbaserotationandbaseoffsetinmeters)
- [GetBaseRotationAndPositionOffset](ue_ue.OculusFunctionLibrary.md#getbaserotationandpositionoffset)
- [GetCurrentDisplayFrequency](ue_ue.OculusFunctionLibrary.md#getcurrentdisplayfrequency)
- [GetDeviceName](ue_ue.OculusFunctionLibrary.md#getdevicename)
- [GetFixedFoveatedRenderingLevel](ue_ue.OculusFunctionLibrary.md#getfixedfoveatedrenderinglevel)
- [GetGPUFrameTime](ue_ue.OculusFunctionLibrary.md#getgpuframetime)
- [GetGPUUtilization](ue_ue.OculusFunctionLibrary.md#getgpuutilization)
- [GetGuardianDimensions](ue_ue.OculusFunctionLibrary.md#getguardiandimensions)
- [GetGuardianPoints](ue_ue.OculusFunctionLibrary.md#getguardianpoints)
- [GetLoadingSplashParams](ue_ue.OculusFunctionLibrary.md#getloadingsplashparams)
- [GetNodeGuardianIntersection](ue_ue.OculusFunctionLibrary.md#getnodeguardianintersection)
- [GetPlayAreaTransform](ue_ue.OculusFunctionLibrary.md#getplayareatransform)
- [GetPointGuardianIntersection](ue_ue.OculusFunctionLibrary.md#getpointguardianintersection)
- [GetPose](ue_ue.OculusFunctionLibrary.md#getpose)
- [GetRawSensorData](ue_ue.OculusFunctionLibrary.md#getrawsensordata)
- [GetUserProfile](ue_ue.OculusFunctionLibrary.md#getuserprofile)
- [HasInputFocus](ue_ue.OculusFunctionLibrary.md#hasinputfocus)
- [HasSystemOverlayPresent](ue_ue.OculusFunctionLibrary.md#hassystemoverlaypresent)
- [HideLoadingIcon](ue_ue.OculusFunctionLibrary.md#hideloadingicon)
- [HideLoadingSplashScreen](ue_ue.OculusFunctionLibrary.md#hideloadingsplashscreen)
- [IsAutoLoadingSplashScreenEnabled](ue_ue.OculusFunctionLibrary.md#isautoloadingsplashscreenenabled)
- [IsDeviceTracked](ue_ue.OculusFunctionLibrary.md#isdevicetracked)
- [IsGuardianConfigured](ue_ue.OculusFunctionLibrary.md#isguardianconfigured)
- [IsGuardianDisplayed](ue_ue.OculusFunctionLibrary.md#isguardiandisplayed)
- [IsLoadingIconEnabled](ue_ue.OculusFunctionLibrary.md#isloadingiconenabled)
- [Load](ue_ue.OculusFunctionLibrary.md#load)
- [SetBaseRotationAndBaseOffsetInMeters](ue_ue.OculusFunctionLibrary.md#setbaserotationandbaseoffsetinmeters)
- [SetBaseRotationAndPositionOffset](ue_ue.OculusFunctionLibrary.md#setbaserotationandpositionoffset)
- [SetCPUAndGPULevels](ue_ue.OculusFunctionLibrary.md#setcpuandgpulevels)
- [SetColorScaleAndOffset](ue_ue.OculusFunctionLibrary.md#setcolorscaleandoffset)
- [SetDisplayFrequency](ue_ue.OculusFunctionLibrary.md#setdisplayfrequency)
- [SetFixedFoveatedRenderingLevel](ue_ue.OculusFunctionLibrary.md#setfixedfoveatedrenderinglevel)
- [SetGuardianVisibility](ue_ue.OculusFunctionLibrary.md#setguardianvisibility)
- [SetLoadingSplashParams](ue_ue.OculusFunctionLibrary.md#setloadingsplashparams)
- [SetPositionScale3D](ue_ue.OculusFunctionLibrary.md#setpositionscale3d)
- [SetReorientHMDOnControllerRecenter](ue_ue.OculusFunctionLibrary.md#setreorienthmdoncontrollerrecenter)
- [ShowLoadingIcon](ue_ue.OculusFunctionLibrary.md#showloadingicon)
- [ShowLoadingSplashScreen](ue_ue.OculusFunctionLibrary.md#showloadingsplashscreen)
- [StaticClass](ue_ue.OculusFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new OculusFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:53734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53734)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_OculusFunctionLibrary\_\_

• **\_\_tid\_OculusFunctionLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:53782](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53782)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### AddLoadingSplashScreen

▸ `Static` **AddLoadingSplashScreen**(`Texture`, `TranslationInMeters`, `Rotation`, `SizeInMeters?`, `DeltaRotation?`, `bClearBeforeAdd?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Texture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture2D`](ue_ue.Texture2D.md)\> |
| `TranslationInMeters` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `SizeInMeters?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `DeltaRotation?` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bClearBeforeAdd?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53735)

___

### ClearLoadingSplashScreens

▸ `Static` **ClearLoadingSplashScreens**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53736)

___

### EnableAutoLoadingSplashScreen

▸ `Static` **EnableAutoLoadingSplashScreen**(`bAutoShowEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bAutoShowEnabled` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53737)

___

### EnableOrientationTracking

▸ `Static` **EnableOrientationTracking**(`bOrientationTracking`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bOrientationTracking` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53738)

___

### EnablePositionTracking

▸ `Static` **EnablePositionTracking**(`bPositionTracking`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bPositionTracking` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53739)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`OculusFunctionLibrary`](ue_ue.OculusFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`OculusFunctionLibrary`](ue_ue.OculusFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:53779](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53779)

___

### GetAvailableDisplayFrequencies

▸ `Static` **GetAvailableDisplayFrequencies**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:53740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53740)

___

### GetBaseRotationAndBaseOffsetInMeters

▸ `Static` **GetBaseRotationAndBaseOffsetInMeters**(`OutRotation`, `OutBaseOffsetInMeters`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutRotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |
| `OutBaseOffsetInMeters` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53741)

___

### GetBaseRotationAndPositionOffset

▸ `Static` **GetBaseRotationAndPositionOffset**(`OutRot`, `OutPosOffset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutRot` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |
| `OutPosOffset` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53742)

___

### GetCurrentDisplayFrequency

▸ `Static` **GetCurrentDisplayFrequency**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:53743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53743)

___

### GetDeviceName

▸ `Static` **GetDeviceName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:53744](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53744)

___

### GetFixedFoveatedRenderingLevel

▸ `Static` **GetFixedFoveatedRenderingLevel**(): [`EFixedFoveatedRenderingLevel`](../enums/ue_ue.EFixedFoveatedRenderingLevel.md)

#### Returns

[`EFixedFoveatedRenderingLevel`](../enums/ue_ue.EFixedFoveatedRenderingLevel.md)

#### Defined in

[ue/ue.d.ts:53745](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53745)

___

### GetGPUFrameTime

▸ `Static` **GetGPUFrameTime**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:53746](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53746)

___

### GetGPUUtilization

▸ `Static` **GetGPUUtilization**(`IsGPUAvailable`, `GPUUtilization`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `IsGPUAvailable` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `GPUUtilization` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53747](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53747)

___

### GetGuardianDimensions

▸ `Static` **GetGuardianDimensions**(`BoundaryType`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoundaryType` | [`EBoundaryType`](../enums/ue_ue.EBoundaryType.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:53748](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53748)

___

### GetGuardianPoints

▸ `Static` **GetGuardianPoints**(`BoundaryType`, `UsePawnSpace?`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoundaryType` | [`EBoundaryType`](../enums/ue_ue.EBoundaryType.md) |
| `UsePawnSpace?` | `boolean` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:53749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53749)

___

### GetLoadingSplashParams

▸ `Static` **GetLoadingSplashParams**(`TexturePath`, `DistanceInMeters`, `SizeInMeters`, `RotationAxis`, `RotationDeltaInDeg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TexturePath` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `DistanceInMeters` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `SizeInMeters` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |
| `RotationAxis` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `RotationDeltaInDeg` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53750](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53750)

___

### GetNodeGuardianIntersection

▸ `Static` **GetNodeGuardianIntersection**(`DeviceType`, `BoundaryType`): [`GuardianTestResult`](ue_ue.GuardianTestResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeviceType` | [`ETrackedDeviceType`](../enums/ue_ue.ETrackedDeviceType.md) |
| `BoundaryType` | [`EBoundaryType`](../enums/ue_ue.EBoundaryType.md) |

#### Returns

[`GuardianTestResult`](ue_ue.GuardianTestResult.md)

#### Defined in

[ue/ue.d.ts:53751](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53751)

___

### GetPlayAreaTransform

▸ `Static` **GetPlayAreaTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:53752](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53752)

___

### GetPointGuardianIntersection

▸ `Static` **GetPointGuardianIntersection**(`Point`, `BoundaryType`): [`GuardianTestResult`](ue_ue.GuardianTestResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point` | [`Vector`](ue_ue_s.Vector.md) |
| `BoundaryType` | [`EBoundaryType`](../enums/ue_ue.EBoundaryType.md) |

#### Returns

[`GuardianTestResult`](ue_ue.GuardianTestResult.md)

#### Defined in

[ue/ue.d.ts:53753](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53753)

___

### GetPose

▸ `Static` **GetPose**(`DeviceRotation`, `DevicePosition`, `NeckPosition`, `bUseOrienationForPlayerCamera?`, `bUsePositionForPlayerCamera?`, `PositionScale?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeviceRotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |
| `DevicePosition` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `NeckPosition` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `bUseOrienationForPlayerCamera?` | `boolean` |
| `bUsePositionForPlayerCamera?` | `boolean` |
| `PositionScale?` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53754](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53754)

___

### GetRawSensorData

▸ `Static` **GetRawSensorData**(`AngularAcceleration`, `LinearAcceleration`, `AngularVelocity`, `LinearVelocity`, `TimeInSeconds`, `DeviceType?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AngularAcceleration` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `LinearAcceleration` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `AngularVelocity` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `LinearVelocity` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `TimeInSeconds` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `DeviceType?` | [`ETrackedDeviceType`](../enums/ue_ue.ETrackedDeviceType.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53755](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53755)

___

### GetUserProfile

▸ `Static` **GetUserProfile**(`Profile`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Profile` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HmdUserProfile`](ue_ue.HmdUserProfile.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:53756](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53756)

___

### HasInputFocus

▸ `Static` **HasInputFocus**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:53757](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53757)

___

### HasSystemOverlayPresent

▸ `Static` **HasSystemOverlayPresent**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:53758](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53758)

___

### HideLoadingIcon

▸ `Static` **HideLoadingIcon**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53759](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53759)

___

### HideLoadingSplashScreen

▸ `Static` **HideLoadingSplashScreen**(`bClear?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bClear?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53760](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53760)

___

### IsAutoLoadingSplashScreenEnabled

▸ `Static` **IsAutoLoadingSplashScreenEnabled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:53761](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53761)

___

### IsDeviceTracked

▸ `Static` **IsDeviceTracked**(`DeviceType`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeviceType` | [`ETrackedDeviceType`](../enums/ue_ue.ETrackedDeviceType.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:53762](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53762)

___

### IsGuardianConfigured

▸ `Static` **IsGuardianConfigured**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:53763](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53763)

___

### IsGuardianDisplayed

▸ `Static` **IsGuardianDisplayed**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:53764](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53764)

___

### IsLoadingIconEnabled

▸ `Static` **IsLoadingIconEnabled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:53765](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53765)

___

### Load

▸ `Static` **Load**(`InName`): [`OculusFunctionLibrary`](ue_ue.OculusFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`OculusFunctionLibrary`](ue_ue.OculusFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:53780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53780)

___

### SetBaseRotationAndBaseOffsetInMeters

▸ `Static` **SetBaseRotationAndBaseOffsetInMeters**(`Rotation`, `BaseOffsetInMeters`, `Options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `BaseOffsetInMeters` | [`Vector`](ue_ue_s.Vector.md) |
| `Options` | [`EOrientPositionSelector`](../enums/ue_ue.EOrientPositionSelector.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53766](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53766)

___

### SetBaseRotationAndPositionOffset

▸ `Static` **SetBaseRotationAndPositionOffset**(`BaseRot`, `PosOffset`, `Options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BaseRot` | [`Rotator`](ue_ue_s.Rotator.md) |
| `PosOffset` | [`Vector`](ue_ue_s.Vector.md) |
| `Options` | [`EOrientPositionSelector`](../enums/ue_ue.EOrientPositionSelector.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53767](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53767)

___

### SetCPUAndGPULevels

▸ `Static` **SetCPUAndGPULevels**(`CPULevel`, `GPULevel`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CPULevel` | `number` |
| `GPULevel` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53769](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53769)

___

### SetColorScaleAndOffset

▸ `Static` **SetColorScaleAndOffset**(`ColorScale`, `ColorOffset`, `bApplyToAllLayers?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ColorScale` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `ColorOffset` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `bApplyToAllLayers?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53768](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53768)

___

### SetDisplayFrequency

▸ `Static` **SetDisplayFrequency**(`RequestedFrequency`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RequestedFrequency` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53770](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53770)

___

### SetFixedFoveatedRenderingLevel

▸ `Static` **SetFixedFoveatedRenderingLevel**(`level`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `level` | [`EFixedFoveatedRenderingLevel`](../enums/ue_ue.EFixedFoveatedRenderingLevel.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53771](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53771)

___

### SetGuardianVisibility

▸ `Static` **SetGuardianVisibility**(`GuardianVisible`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GuardianVisible` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53772](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53772)

___

### SetLoadingSplashParams

▸ `Static` **SetLoadingSplashParams**(`TexturePath`, `DistanceInMeters`, `SizeInMeters`, `RotationAxis`, `RotationDeltaInDeg`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TexturePath` | `string` |
| `DistanceInMeters` | [`Vector`](ue_ue_s.Vector.md) |
| `SizeInMeters` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `RotationAxis` | [`Vector`](ue_ue_s.Vector.md) |
| `RotationDeltaInDeg` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53773](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53773)

___

### SetPositionScale3D

▸ `Static` **SetPositionScale3D**(`PosScale3D`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PosScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53774](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53774)

___

### SetReorientHMDOnControllerRecenter

▸ `Static` **SetReorientHMDOnControllerRecenter**(`recenterMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `recenterMode` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53775](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53775)

___

### ShowLoadingIcon

▸ `Static` **ShowLoadingIcon**(`Texture`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Texture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture2D`](ue_ue.Texture2D.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53776](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53776)

___

### ShowLoadingSplashScreen

▸ `Static` **ShowLoadingSplashScreen**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:53777](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53777)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:53778](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53778)
