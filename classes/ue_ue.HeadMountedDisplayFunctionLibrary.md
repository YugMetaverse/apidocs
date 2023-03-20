[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / HeadMountedDisplayFunctionLibrary

# Class: HeadMountedDisplayFunctionLibrary

[ue/ue](../modules/ue_ue.md).HeadMountedDisplayFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`HeadMountedDisplayFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.HeadMountedDisplayFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.HeadMountedDisplayFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_HeadMountedDisplayFunctionLibrary\_\_](ue_ue.HeadMountedDisplayFunctionLibrary.md#__tid_headmounteddisplayfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.HeadMountedDisplayFunctionLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.HeadMountedDisplayFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.HeadMountedDisplayFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.HeadMountedDisplayFunctionLibrary.md#getclass)
- [GetName](ue_ue.HeadMountedDisplayFunctionLibrary.md#getname)
- [GetOuter](ue_ue.HeadMountedDisplayFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.HeadMountedDisplayFunctionLibrary.md#getworld)
- [CalibrateExternalTrackingToHMD](ue_ue.HeadMountedDisplayFunctionLibrary.md#calibrateexternaltrackingtohmd)
- [EnableHMD](ue_ue.HeadMountedDisplayFunctionLibrary.md#enablehmd)
- [EnableLowPersistenceMode](ue_ue.HeadMountedDisplayFunctionLibrary.md#enablelowpersistencemode)
- [EnumerateTrackedDevices](ue_ue.HeadMountedDisplayFunctionLibrary.md#enumeratetrackeddevices)
- [Find](ue_ue.HeadMountedDisplayFunctionLibrary.md#find)
- [GetDevicePose](ue_ue.HeadMountedDisplayFunctionLibrary.md#getdevicepose)
- [GetDeviceWorldPose](ue_ue.HeadMountedDisplayFunctionLibrary.md#getdeviceworldpose)
- [GetHMDDeviceName](ue_ue.HeadMountedDisplayFunctionLibrary.md#gethmddevicename)
- [GetHMDWornState](ue_ue.HeadMountedDisplayFunctionLibrary.md#gethmdwornstate)
- [GetNumOfTrackingSensors](ue_ue.HeadMountedDisplayFunctionLibrary.md#getnumoftrackingsensors)
- [GetOrientationAndPosition](ue_ue.HeadMountedDisplayFunctionLibrary.md#getorientationandposition)
- [GetPixelDensity](ue_ue.HeadMountedDisplayFunctionLibrary.md#getpixeldensity)
- [GetPositionalTrackingCameraParameters](ue_ue.HeadMountedDisplayFunctionLibrary.md#getpositionaltrackingcameraparameters)
- [GetScreenPercentage](ue_ue.HeadMountedDisplayFunctionLibrary.md#getscreenpercentage)
- [GetTrackingOrigin](ue_ue.HeadMountedDisplayFunctionLibrary.md#gettrackingorigin)
- [GetTrackingSensorParameters](ue_ue.HeadMountedDisplayFunctionLibrary.md#gettrackingsensorparameters)
- [GetTrackingToWorldTransform](ue_ue.HeadMountedDisplayFunctionLibrary.md#gettrackingtoworldtransform)
- [GetVRFocusState](ue_ue.HeadMountedDisplayFunctionLibrary.md#getvrfocusstate)
- [GetWorldToMetersScale](ue_ue.HeadMountedDisplayFunctionLibrary.md#getworldtometersscale)
- [HasValidTrackingPosition](ue_ue.HeadMountedDisplayFunctionLibrary.md#hasvalidtrackingposition)
- [IsDeviceTracking](ue_ue.HeadMountedDisplayFunctionLibrary.md#isdevicetracking)
- [IsHeadMountedDisplayConnected](ue_ue.HeadMountedDisplayFunctionLibrary.md#isheadmounteddisplayconnected)
- [IsHeadMountedDisplayEnabled](ue_ue.HeadMountedDisplayFunctionLibrary.md#isheadmounteddisplayenabled)
- [IsInLowPersistenceMode](ue_ue.HeadMountedDisplayFunctionLibrary.md#isinlowpersistencemode)
- [IsSpectatorScreenModeControllable](ue_ue.HeadMountedDisplayFunctionLibrary.md#isspectatorscreenmodecontrollable)
- [Load](ue_ue.HeadMountedDisplayFunctionLibrary.md#load)
- [ResetOrientationAndPosition](ue_ue.HeadMountedDisplayFunctionLibrary.md#resetorientationandposition)
- [SetClippingPlanes](ue_ue.HeadMountedDisplayFunctionLibrary.md#setclippingplanes)
- [SetSpectatorScreenMode](ue_ue.HeadMountedDisplayFunctionLibrary.md#setspectatorscreenmode)
- [SetSpectatorScreenModeTexturePlusEyeLayout](ue_ue.HeadMountedDisplayFunctionLibrary.md#setspectatorscreenmodetexturepluseyelayout)
- [SetSpectatorScreenTexture](ue_ue.HeadMountedDisplayFunctionLibrary.md#setspectatorscreentexture)
- [SetTrackingOrigin](ue_ue.HeadMountedDisplayFunctionLibrary.md#settrackingorigin)
- [SetWorldToMetersScale](ue_ue.HeadMountedDisplayFunctionLibrary.md#setworldtometersscale)
- [StaticClass](ue_ue.HeadMountedDisplayFunctionLibrary.md#staticclass)
- [UpdateExternalTrackingHMDPosition](ue_ue.HeadMountedDisplayFunctionLibrary.md#updateexternaltrackinghmdposition)

## Constructors

### constructor

• **new HeadMountedDisplayFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:38517](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38517)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13418)

___

### \_\_tid\_HeadMountedDisplayFunctionLibrary\_\_

• **\_\_tid\_HeadMountedDisplayFunctionLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:38554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38554)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### CalibrateExternalTrackingToHMD

▸ `Static` **CalibrateExternalTrackingToHMD**(`ExternalTrackingTransform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ExternalTrackingTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38518](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38518)

___

### EnableHMD

▸ `Static` **EnableHMD**(`bEnable`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:38519](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38519)

___

### EnableLowPersistenceMode

▸ `Static` **EnableLowPersistenceMode**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38520](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38520)

___

### EnumerateTrackedDevices

▸ `Static` **EnumerateTrackedDevices**(`SystemId?`, `DeviceType?`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`XRDeviceId`](ue_ue.XRDeviceId.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `SystemId?` | `string` |
| `DeviceType?` | [`EXRTrackedDeviceType`](../enums/ue_ue.EXRTrackedDeviceType.md) |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`XRDeviceId`](ue_ue.XRDeviceId.md)\>

#### Defined in

[ue/ue.d.ts:38521](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38521)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`HeadMountedDisplayFunctionLibrary`](ue_ue.HeadMountedDisplayFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`HeadMountedDisplayFunctionLibrary`](ue_ue.HeadMountedDisplayFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:38551](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38551)

___

### GetDevicePose

▸ `Static` **GetDevicePose**(`XRDeviceId`, `bIsTracked`, `Orientation`, `bHasPositionalTracking`, `Position`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `XRDeviceId` | [`XRDeviceId`](ue_ue.XRDeviceId.md) |
| `bIsTracked` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `Orientation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |
| `bHasPositionalTracking` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `Position` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38522](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38522)

___

### GetDeviceWorldPose

▸ `Static` **GetDeviceWorldPose**(`WorldContext`, `XRDeviceId`, `bIsTracked`, `Orientation`, `bHasPositionalTracking`, `Position`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContext` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `XRDeviceId` | [`XRDeviceId`](ue_ue.XRDeviceId.md) |
| `bIsTracked` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `Orientation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |
| `bHasPositionalTracking` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `Position` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38523](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38523)

___

### GetHMDDeviceName

▸ `Static` **GetHMDDeviceName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:38524](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38524)

___

### GetHMDWornState

▸ `Static` **GetHMDWornState**(): [`EHMDWornState`](../enums/ue_ue.EHMDWornState.md)

#### Returns

[`EHMDWornState`](../enums/ue_ue.EHMDWornState.md)

#### Defined in

[ue/ue.d.ts:38525](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38525)

___

### GetNumOfTrackingSensors

▸ `Static` **GetNumOfTrackingSensors**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:38526](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38526)

___

### GetOrientationAndPosition

▸ `Static` **GetOrientationAndPosition**(`DeviceRotation`, `DevicePosition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeviceRotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |
| `DevicePosition` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38527](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38527)

___

### GetPixelDensity

▸ `Static` **GetPixelDensity**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:38528](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38528)

___

### GetPositionalTrackingCameraParameters

▸ `Static` **GetPositionalTrackingCameraParameters**(`CameraOrigin`, `CameraRotation`, `HFOV`, `VFOV`, `CameraDistance`, `NearPlane`, `FarPlane`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CameraOrigin` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `CameraRotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |
| `HFOV` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `VFOV` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `CameraDistance` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `NearPlane` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `FarPlane` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38529](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38529)

___

### GetScreenPercentage

▸ `Static` **GetScreenPercentage**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:38530](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38530)

___

### GetTrackingOrigin

▸ `Static` **GetTrackingOrigin**(): [`EHMDTrackingOrigin`](../enums/ue_ue.EHMDTrackingOrigin.md)

#### Returns

[`EHMDTrackingOrigin`](../enums/ue_ue.EHMDTrackingOrigin.md)

#### Defined in

[ue/ue.d.ts:38531](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38531)

___

### GetTrackingSensorParameters

▸ `Static` **GetTrackingSensorParameters**(`Origin`, `Rotation`, `LeftFOV`, `RightFOV`, `TopFOV`, `BottomFOV`, `Distance`, `NearPlane`, `FarPlane`, `IsActive`, `Index?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Origin` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Rotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |
| `LeftFOV` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `RightFOV` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `TopFOV` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `BottomFOV` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Distance` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `NearPlane` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `FarPlane` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `IsActive` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `Index?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38532](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38532)

___

### GetTrackingToWorldTransform

▸ `Static` **GetTrackingToWorldTransform**(`WorldContext`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContext` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:38533](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38533)

___

### GetVRFocusState

▸ `Static` **GetVRFocusState**(`bUseFocus`, `bHasFocus`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bUseFocus` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `bHasFocus` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38534](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38534)

___

### GetWorldToMetersScale

▸ `Static` **GetWorldToMetersScale**(`WorldContext`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContext` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:38535](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38535)

___

### HasValidTrackingPosition

▸ `Static` **HasValidTrackingPosition**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:38536](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38536)

___

### IsDeviceTracking

▸ `Static` **IsDeviceTracking**(`XRDeviceId`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `XRDeviceId` | [`XRDeviceId`](ue_ue.XRDeviceId.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:38537](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38537)

___

### IsHeadMountedDisplayConnected

▸ `Static` **IsHeadMountedDisplayConnected**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:38538](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38538)

___

### IsHeadMountedDisplayEnabled

▸ `Static` **IsHeadMountedDisplayEnabled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:38539](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38539)

___

### IsInLowPersistenceMode

▸ `Static` **IsInLowPersistenceMode**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:38540](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38540)

___

### IsSpectatorScreenModeControllable

▸ `Static` **IsSpectatorScreenModeControllable**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:38541](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38541)

___

### Load

▸ `Static` **Load**(`InName`): [`HeadMountedDisplayFunctionLibrary`](ue_ue.HeadMountedDisplayFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`HeadMountedDisplayFunctionLibrary`](ue_ue.HeadMountedDisplayFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:38552](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38552)

___

### ResetOrientationAndPosition

▸ `Static` **ResetOrientationAndPosition**(`Yaw?`, `Options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Yaw?` | `number` |
| `Options?` | [`EOrientPositionSelector`](../enums/ue_ue.EOrientPositionSelector.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38542](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38542)

___

### SetClippingPlanes

▸ `Static` **SetClippingPlanes**(`Near`, `Far`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Near` | `number` |
| `Far` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38543](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38543)

___

### SetSpectatorScreenMode

▸ `Static` **SetSpectatorScreenMode**(`Mode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Mode` | [`ESpectatorScreenMode`](../enums/ue_ue.ESpectatorScreenMode.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38544](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38544)

___

### SetSpectatorScreenModeTexturePlusEyeLayout

▸ `Static` **SetSpectatorScreenModeTexturePlusEyeLayout**(`EyeRectMin`, `EyeRectMax`, `TextureRectMin`, `TextureRectMax`, `bDrawEyeFirst?`, `bClearBlack?`, `bUseAlpha?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EyeRectMin` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `EyeRectMax` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `TextureRectMin` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `TextureRectMax` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `bDrawEyeFirst?` | `boolean` |
| `bClearBlack?` | `boolean` |
| `bUseAlpha?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38545)

___

### SetSpectatorScreenTexture

▸ `Static` **SetSpectatorScreenTexture**(`InTexture`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTexture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38546](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38546)

___

### SetTrackingOrigin

▸ `Static` **SetTrackingOrigin**(`Origin`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Origin` | [`EHMDTrackingOrigin`](../enums/ue_ue.EHMDTrackingOrigin.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38547](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38547)

___

### SetWorldToMetersScale

▸ `Static` **SetWorldToMetersScale**(`WorldContext`, `NewScale?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContext` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `NewScale?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38548](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38548)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:38550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38550)

___

### UpdateExternalTrackingHMDPosition

▸ `Static` **UpdateExternalTrackingHMDPosition**(`ExternalTrackingTransform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ExternalTrackingTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38549](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38549)
