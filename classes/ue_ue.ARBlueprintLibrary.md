[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARBlueprintLibrary

# Class: ARBlueprintLibrary

[ue/ue](../modules/ue_ue.md).ARBlueprintLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`ARBlueprintLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARBlueprintLibrary.md#constructor)

### Properties

- [\_\_tid\_ARBlueprintLibrary\_\_](ue_ue.ARBlueprintLibrary.md#__tid_arblueprintlibrary__)
- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.ARBlueprintLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.ARBlueprintLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ARBlueprintLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARBlueprintLibrary.md#executeubergraph)
- [GetClass](ue_ue.ARBlueprintLibrary.md#getclass)
- [GetName](ue_ue.ARBlueprintLibrary.md#getname)
- [GetOuter](ue_ue.ARBlueprintLibrary.md#getouter)
- [GetWorld](ue_ue.ARBlueprintLibrary.md#getworld)
- [AddManualEnvironmentCaptureProbe](ue_ue.ARBlueprintLibrary.md#addmanualenvironmentcaptureprobe)
- [AddRuntimeCandidateImage](ue_ue.ARBlueprintLibrary.md#addruntimecandidateimage)
- [DebugDrawPin](ue_ue.ARBlueprintLibrary.md#debugdrawpin)
- [DebugDrawTrackedGeometry](ue_ue.ARBlueprintLibrary.md#debugdrawtrackedgeometry)
- [Find](ue_ue.ARBlueprintLibrary.md#find)
- [GetARSessionStatus](ue_ue.ARBlueprintLibrary.md#getarsessionstatus)
- [GetAllGeometries](ue_ue.ARBlueprintLibrary.md#getallgeometries)
- [GetAllPins](ue_ue.ARBlueprintLibrary.md#getallpins)
- [GetAllTracked2DPoses](ue_ue.ARBlueprintLibrary.md#getalltracked2dposes)
- [GetAllTrackedEnvironmentCaptureProbes](ue_ue.ARBlueprintLibrary.md#getalltrackedenvironmentcaptureprobes)
- [GetAllTrackedImages](ue_ue.ARBlueprintLibrary.md#getalltrackedimages)
- [GetAllTrackedPlanes](ue_ue.ARBlueprintLibrary.md#getalltrackedplanes)
- [GetAllTrackedPoints](ue_ue.ARBlueprintLibrary.md#getalltrackedpoints)
- [GetAllTrackedPoses](ue_ue.ARBlueprintLibrary.md#getalltrackedposes)
- [GetCameraDepth](ue_ue.ARBlueprintLibrary.md#getcameradepth)
- [GetCameraImage](ue_ue.ARBlueprintLibrary.md#getcameraimage)
- [GetCurrentLightEstimate](ue_ue.ARBlueprintLibrary.md#getcurrentlightestimate)
- [GetPersonSegmentationDepthImage](ue_ue.ARBlueprintLibrary.md#getpersonsegmentationdepthimage)
- [GetPersonSegmentationImage](ue_ue.ARBlueprintLibrary.md#getpersonsegmentationimage)
- [GetPointCloud](ue_ue.ARBlueprintLibrary.md#getpointcloud)
- [GetSessionConfig](ue_ue.ARBlueprintLibrary.md#getsessionconfig)
- [GetSupportedVideoFormats](ue_ue.ARBlueprintLibrary.md#getsupportedvideoformats)
- [GetTrackingQuality](ue_ue.ARBlueprintLibrary.md#gettrackingquality)
- [GetTrackingQualityReason](ue_ue.ARBlueprintLibrary.md#gettrackingqualityreason)
- [GetWorldMappingStatus](ue_ue.ARBlueprintLibrary.md#getworldmappingstatus)
- [IsARSupported](ue_ue.ARBlueprintLibrary.md#isarsupported)
- [IsSessionTrackingFeatureSupported](ue_ue.ARBlueprintLibrary.md#issessiontrackingfeaturesupported)
- [IsSessionTypeSupported](ue_ue.ARBlueprintLibrary.md#issessiontypesupported)
- [LineTraceTrackedObjects](ue_ue.ARBlueprintLibrary.md#linetracetrackedobjects)
- [LineTraceTrackedObjects3D](ue_ue.ARBlueprintLibrary.md#linetracetrackedobjects3d)
- [Load](ue_ue.ARBlueprintLibrary.md#load)
- [PauseARSession](ue_ue.ARBlueprintLibrary.md#pausearsession)
- [PinComponent](ue_ue.ARBlueprintLibrary.md#pincomponent)
- [PinComponentToTraceResult](ue_ue.ARBlueprintLibrary.md#pincomponenttotraceresult)
- [RemovePin](ue_ue.ARBlueprintLibrary.md#removepin)
- [SetAlignmentTransform](ue_ue.ARBlueprintLibrary.md#setalignmenttransform)
- [StartARSession](ue_ue.ARBlueprintLibrary.md#startarsession)
- [StaticClass](ue_ue.ARBlueprintLibrary.md#staticclass)
- [StopARSession](ue_ue.ARBlueprintLibrary.md#stoparsession)
- [UnpinComponent](ue_ue.ARBlueprintLibrary.md#unpincomponent)

## Constructors

### constructor

• **new ARBlueprintLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_ARBlueprintLibrary\_\_

• **\_\_tid\_ARBlueprintLibrary\_\_**: `boolean`

___

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

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

### AddManualEnvironmentCaptureProbe

▸ `Static` **AddManualEnvironmentCaptureProbe**(`Location`, `Extent`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Extent` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`boolean`

___

### AddRuntimeCandidateImage

▸ `Static` **AddRuntimeCandidateImage**(`SessionConfig`, `CandidateTexture`, `FriendlyName`, `PhysicalWidth`): [`ARCandidateImage`](ue_ue.ARCandidateImage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SessionConfig` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ARSessionConfig`](ue_ue.ARSessionConfig.md)\> |
| `CandidateTexture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture2D`](ue_ue.Texture2D.md)\> |
| `FriendlyName` | `string` |
| `PhysicalWidth` | `number` |

#### Returns

[`ARCandidateImage`](ue_ue.ARCandidateImage.md)

___

### DebugDrawPin

▸ `Static` **DebugDrawPin**(`ARPin`, `WorldContextObject`, `Color?`, `Scale?`, `PersistForSeconds?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ARPin` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ARPin`](ue_ue.ARPin.md)\> |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Color?` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `Scale?` | `number` |
| `PersistForSeconds?` | `number` |

#### Returns

`void`

___

### DebugDrawTrackedGeometry

▸ `Static` **DebugDrawTrackedGeometry**(`TrackedGeometry`, `WorldContextObject`, `Color?`, `OutlineThickness?`, `PersistForSeconds?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackedGeometry` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)\> |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Color?` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `OutlineThickness?` | `number` |
| `PersistForSeconds?` | `number` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARBlueprintLibrary`](ue_ue.ARBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARBlueprintLibrary`](ue_ue.ARBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetARSessionStatus

▸ `Static` **GetARSessionStatus**(): [`ARSessionStatus`](ue_ue.ARSessionStatus.md)

#### Returns

[`ARSessionStatus`](ue_ue.ARSessionStatus.md)

___

### GetAllGeometries

▸ `Static` **GetAllGeometries**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md)\>

___

### GetAllPins

▸ `Static` **GetAllPins**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARPin`](ue_ue.ARPin.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARPin`](ue_ue.ARPin.md)\>

___

### GetAllTracked2DPoses

▸ `Static` **GetAllTracked2DPoses**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARPose2D`](ue_ue.ARPose2D.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARPose2D`](ue_ue.ARPose2D.md)\>

___

### GetAllTrackedEnvironmentCaptureProbes

▸ `Static` **GetAllTrackedEnvironmentCaptureProbes**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AREnvironmentCaptureProbe`](ue_ue.AREnvironmentCaptureProbe.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AREnvironmentCaptureProbe`](ue_ue.AREnvironmentCaptureProbe.md)\>

___

### GetAllTrackedImages

▸ `Static` **GetAllTrackedImages**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARTrackedImage`](ue_ue.ARTrackedImage.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARTrackedImage`](ue_ue.ARTrackedImage.md)\>

___

### GetAllTrackedPlanes

▸ `Static` **GetAllTrackedPlanes**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARPlaneGeometry`](ue_ue.ARPlaneGeometry.md)\>

___

### GetAllTrackedPoints

▸ `Static` **GetAllTrackedPoints**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARTrackedPoint`](ue_ue.ARTrackedPoint.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARTrackedPoint`](ue_ue.ARTrackedPoint.md)\>

___

### GetAllTrackedPoses

▸ `Static` **GetAllTrackedPoses**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARTrackedPose`](ue_ue.ARTrackedPose.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARTrackedPose`](ue_ue.ARTrackedPose.md)\>

___

### GetCameraDepth

▸ `Static` **GetCameraDepth**(): [`ARTextureCameraDepth`](ue_ue.ARTextureCameraDepth.md)

#### Returns

[`ARTextureCameraDepth`](ue_ue.ARTextureCameraDepth.md)

___

### GetCameraImage

▸ `Static` **GetCameraImage**(): [`ARTextureCameraImage`](ue_ue.ARTextureCameraImage.md)

#### Returns

[`ARTextureCameraImage`](ue_ue.ARTextureCameraImage.md)

___

### GetCurrentLightEstimate

▸ `Static` **GetCurrentLightEstimate**(): [`ARLightEstimate`](ue_ue.ARLightEstimate.md)

#### Returns

[`ARLightEstimate`](ue_ue.ARLightEstimate.md)

___

### GetPersonSegmentationDepthImage

▸ `Static` **GetPersonSegmentationDepthImage**(): [`ARTextureCameraImage`](ue_ue.ARTextureCameraImage.md)

#### Returns

[`ARTextureCameraImage`](ue_ue.ARTextureCameraImage.md)

___

### GetPersonSegmentationImage

▸ `Static` **GetPersonSegmentationImage**(): [`ARTextureCameraImage`](ue_ue.ARTextureCameraImage.md)

#### Returns

[`ARTextureCameraImage`](ue_ue.ARTextureCameraImage.md)

___

### GetPointCloud

▸ `Static` **GetPointCloud**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### GetSessionConfig

▸ `Static` **GetSessionConfig**(): [`ARSessionConfig`](ue_ue.ARSessionConfig.md)

#### Returns

[`ARSessionConfig`](ue_ue.ARSessionConfig.md)

___

### GetSupportedVideoFormats

▸ `Static` **GetSupportedVideoFormats**(`SessionType`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARVideoFormat`](ue_ue.ARVideoFormat.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `SessionType` | [`EARSessionType`](../enums/ue_ue.EARSessionType.md) |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARVideoFormat`](ue_ue.ARVideoFormat.md)\>

___

### GetTrackingQuality

▸ `Static` **GetTrackingQuality**(): [`EARTrackingQuality`](../enums/ue_ue.EARTrackingQuality.md)

#### Returns

[`EARTrackingQuality`](../enums/ue_ue.EARTrackingQuality.md)

___

### GetTrackingQualityReason

▸ `Static` **GetTrackingQualityReason**(): [`EARTrackingQualityReason`](../enums/ue_ue.EARTrackingQualityReason.md)

#### Returns

[`EARTrackingQualityReason`](../enums/ue_ue.EARTrackingQualityReason.md)

___

### GetWorldMappingStatus

▸ `Static` **GetWorldMappingStatus**(): [`EARWorldMappingState`](../enums/ue_ue.EARWorldMappingState.md)

#### Returns

[`EARWorldMappingState`](../enums/ue_ue.EARWorldMappingState.md)

___

### IsARSupported

▸ `Static` **IsARSupported**(): `boolean`

#### Returns

`boolean`

___

### IsSessionTrackingFeatureSupported

▸ `Static` **IsSessionTrackingFeatureSupported**(`SessionType`, `SessionTrackingFeature`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SessionType` | [`EARSessionType`](../enums/ue_ue.EARSessionType.md) |
| `SessionTrackingFeature` | [`EARSessionTrackingFeature`](../enums/ue_ue.EARSessionTrackingFeature.md) |

#### Returns

`boolean`

___

### IsSessionTypeSupported

▸ `Static` **IsSessionTypeSupported**(`SessionType`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SessionType` | [`EARSessionType`](../enums/ue_ue.EARSessionType.md) |

#### Returns

`boolean`

___

### LineTraceTrackedObjects

▸ `Static` **LineTraceTrackedObjects**(`ScreenCoord`, `bTestFeaturePoints?`, `bTestGroundPlane?`, `bTestPlaneExtents?`, `bTestPlaneBoundaryPolygon?`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARTraceResult`](ue_ue.ARTraceResult.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScreenCoord` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `bTestFeaturePoints?` | `boolean` |
| `bTestGroundPlane?` | `boolean` |
| `bTestPlaneExtents?` | `boolean` |
| `bTestPlaneBoundaryPolygon?` | `boolean` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARTraceResult`](ue_ue.ARTraceResult.md)\>

___

### LineTraceTrackedObjects3D

▸ `Static` **LineTraceTrackedObjects3D**(`Start`, `End`, `bTestFeaturePoints?`, `bTestGroundPlane?`, `bTestPlaneExtents?`, `bTestPlaneBoundaryPolygon?`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARTraceResult`](ue_ue.ARTraceResult.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Start` | [`Vector`](ue_ue_s.Vector.md) |
| `End` | [`Vector`](ue_ue_s.Vector.md) |
| `bTestFeaturePoints?` | `boolean` |
| `bTestGroundPlane?` | `boolean` |
| `bTestPlaneExtents?` | `boolean` |
| `bTestPlaneBoundaryPolygon?` | `boolean` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARTraceResult`](ue_ue.ARTraceResult.md)\>

___

### Load

▸ `Static` **Load**(`InName`): [`ARBlueprintLibrary`](ue_ue.ARBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARBlueprintLibrary`](ue_ue.ARBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### PauseARSession

▸ `Static` **PauseARSession**(): `void`

#### Returns

`void`

___

### PinComponent

▸ `Static` **PinComponent**(`ComponentToPin`, `PinToWorldTransform`, `TrackedGeometry?`, `DebugName?`): [`ARPin`](ue_ue.ARPin.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentToPin` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `PinToWorldTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `TrackedGeometry?` | [`ARTrackedGeometry`](ue_ue.ARTrackedGeometry.md) |
| `DebugName?` | `string` |

#### Returns

[`ARPin`](ue_ue.ARPin.md)

___

### PinComponentToTraceResult

▸ `Static` **PinComponentToTraceResult**(`ComponentToPin`, `TraceResult`, `DebugName?`): [`ARPin`](ue_ue.ARPin.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentToPin` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `TraceResult` | [`ARTraceResult`](ue_ue.ARTraceResult.md) |
| `DebugName?` | `string` |

#### Returns

[`ARPin`](ue_ue.ARPin.md)

___

### RemovePin

▸ `Static` **RemovePin**(`PinToRemove`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PinToRemove` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ARPin`](ue_ue.ARPin.md)\> |

#### Returns

`void`

___

### SetAlignmentTransform

▸ `Static` **SetAlignmentTransform**(`InAlignmentTransform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAlignmentTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

___

### StartARSession

▸ `Static` **StartARSession**(`SessionConfig`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SessionConfig` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ARSessionConfig`](ue_ue.ARSessionConfig.md)\> |

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

### StopARSession

▸ `Static` **StopARSession**(): `void`

#### Returns

`void`

___

### UnpinComponent

▸ `Static` **UnpinComponent**(`ComponentToUnpin`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentToUnpin` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |

#### Returns

`void`
