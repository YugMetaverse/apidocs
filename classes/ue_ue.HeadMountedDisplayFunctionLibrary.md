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

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_HeadMountedDisplayFunctionLibrary\_\_

• **\_\_tid\_HeadMountedDisplayFunctionLibrary\_\_**: `boolean`

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

### CalibrateExternalTrackingToHMD

▸ `Static` **CalibrateExternalTrackingToHMD**(`ExternalTrackingTransform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ExternalTrackingTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

___

### EnableHMD

▸ `Static` **EnableHMD**(`bEnable`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`boolean`

___

### EnableLowPersistenceMode

▸ `Static` **EnableLowPersistenceMode**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

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

___

### GetHMDDeviceName

▸ `Static` **GetHMDDeviceName**(): `string`

#### Returns

`string`

___

### GetHMDWornState

▸ `Static` **GetHMDWornState**(): [`EHMDWornState`](../enums/ue_ue.EHMDWornState.md)

#### Returns

[`EHMDWornState`](../enums/ue_ue.EHMDWornState.md)

___

### GetNumOfTrackingSensors

▸ `Static` **GetNumOfTrackingSensors**(): `number`

#### Returns

`number`

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

___

### GetPixelDensity

▸ `Static` **GetPixelDensity**(): `number`

#### Returns

`number`

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

___

### GetScreenPercentage

▸ `Static` **GetScreenPercentage**(): `number`

#### Returns

`number`

___

### GetTrackingOrigin

▸ `Static` **GetTrackingOrigin**(): [`EHMDTrackingOrigin`](../enums/ue_ue.EHMDTrackingOrigin.md)

#### Returns

[`EHMDTrackingOrigin`](../enums/ue_ue.EHMDTrackingOrigin.md)

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

___

### GetTrackingToWorldTransform

▸ `Static` **GetTrackingToWorldTransform**(`WorldContext`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContext` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

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

___

### GetWorldToMetersScale

▸ `Static` **GetWorldToMetersScale**(`WorldContext`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContext` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

___

### HasValidTrackingPosition

▸ `Static` **HasValidTrackingPosition**(): `boolean`

#### Returns

`boolean`

___

### IsDeviceTracking

▸ `Static` **IsDeviceTracking**(`XRDeviceId`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `XRDeviceId` | [`XRDeviceId`](ue_ue.XRDeviceId.md) |

#### Returns

`boolean`

___

### IsHeadMountedDisplayConnected

▸ `Static` **IsHeadMountedDisplayConnected**(): `boolean`

#### Returns

`boolean`

___

### IsHeadMountedDisplayEnabled

▸ `Static` **IsHeadMountedDisplayEnabled**(): `boolean`

#### Returns

`boolean`

___

### IsInLowPersistenceMode

▸ `Static` **IsInLowPersistenceMode**(): `boolean`

#### Returns

`boolean`

___

### IsSpectatorScreenModeControllable

▸ `Static` **IsSpectatorScreenModeControllable**(): `boolean`

#### Returns

`boolean`

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

___

### SetSpectatorScreenMode

▸ `Static` **SetSpectatorScreenMode**(`Mode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Mode` | [`ESpectatorScreenMode`](../enums/ue_ue.ESpectatorScreenMode.md) |

#### Returns

`void`

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

___

### SetSpectatorScreenTexture

▸ `Static` **SetSpectatorScreenTexture**(`InTexture`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTexture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |

#### Returns

`void`

___

### SetTrackingOrigin

▸ `Static` **SetTrackingOrigin**(`Origin`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Origin` | [`EHMDTrackingOrigin`](../enums/ue_ue.EHMDTrackingOrigin.md) |

#### Returns

`void`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

___

### UpdateExternalTrackingHMDPosition

▸ `Static` **UpdateExternalTrackingHMDPosition**(`ExternalTrackingTransform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ExternalTrackingTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`
