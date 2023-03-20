[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / OculusMR\_Settings

# Class: OculusMR\_Settings

[ue/ue](../modules/ue_ue.md).OculusMR_Settings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`OculusMR_Settings`**

## Table of contents

### Constructors

- [constructor](ue_ue.OculusMR_Settings.md#constructor)

### Properties

- [BackdropColor](ue_ue.OculusMR_Settings.md#backdropcolor)
- [CapturingCamera](ue_ue.OculusMR_Settings.md#capturingcamera)
- [CastingLatency](ue_ue.OculusMR_Settings.md#castinglatency)
- [ChromaKeyColor](ue_ue.OculusMR_Settings.md#chromakeycolor)
- [ChromaKeySimilarity](ue_ue.OculusMR_Settings.md#chromakeysimilarity)
- [ChromaKeySmoothRange](ue_ue.OculusMR_Settings.md#chromakeysmoothrange)
- [ChromaKeySpillRange](ue_ue.OculusMR_Settings.md#chromakeyspillrange)
- [ClippingReference](ue_ue.OculusMR_Settings.md#clippingreference)
- [CompositionMethod](ue_ue.OculusMR_Settings.md#compositionmethod)
- [DepthQuality](ue_ue.OculusMR_Settings.md#depthquality)
- [DynamicLightingDepthSmoothFactor](ue_ue.OculusMR_Settings.md#dynamiclightingdepthsmoothfactor)
- [DynamicLightingDepthVariationClampingValue](ue_ue.OculusMR_Settings.md#dynamiclightingdepthvariationclampingvalue)
- [ExternalCompositionPostProcessEffects](ue_ue.OculusMR_Settings.md#externalcompositionpostprocesseffects)
- [HandPoseStateLatency](ue_ue.OculusMR_Settings.md#handposestatelatency)
- [HeightPerView](ue_ue.OculusMR_Settings.md#heightperview)
- [VirtualGreenScreenType](ue_ue.OculusMR_Settings.md#virtualgreenscreentype)
- [WidthPerView](ue_ue.OculusMR_Settings.md#widthperview)
- [\_\_tid\_Object\_\_](ue_ue.OculusMR_Settings.md#__tid_object__)
- [\_\_tid\_OculusMR\_Settings\_\_](ue_ue.OculusMR_Settings.md#__tid_oculusmr_settings__)
- [bIsCasting](ue_ue.OculusMR_Settings.md#biscasting)
- [bUseDynamicLighting](ue_ue.OculusMR_Settings.md#busedynamiclighting)
- [bUseTrackedCameraResolution](ue_ue.OculusMR_Settings.md#busetrackedcameraresolution)

### Methods

- [BindToTrackedCameraIndexIfAvailable](ue_ue.OculusMR_Settings.md#bindtotrackedcameraindexifavailable)
- [CreateDefaultSubobject](ue_ue.OculusMR_Settings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.OculusMR_Settings.md#executeubergraph)
- [GetBindToTrackedCameraIndex](ue_ue.OculusMR_Settings.md#getbindtotrackedcameraindex)
- [GetCapturingCamera](ue_ue.OculusMR_Settings.md#getcapturingcamera)
- [GetClass](ue_ue.OculusMR_Settings.md#getclass)
- [GetCompositionMethod](ue_ue.OculusMR_Settings.md#getcompositionmethod)
- [GetDepthQuality](ue_ue.OculusMR_Settings.md#getdepthquality)
- [GetIsCasting](ue_ue.OculusMR_Settings.md#getiscasting)
- [GetName](ue_ue.OculusMR_Settings.md#getname)
- [GetOuter](ue_ue.OculusMR_Settings.md#getouter)
- [GetUseDynamicLighting](ue_ue.OculusMR_Settings.md#getusedynamiclighting)
- [GetWorld](ue_ue.OculusMR_Settings.md#getworld)
- [LoadFromIni](ue_ue.OculusMR_Settings.md#loadfromini)
- [SaveToIni](ue_ue.OculusMR_Settings.md#savetoini)
- [SetCapturingCamera](ue_ue.OculusMR_Settings.md#setcapturingcamera)
- [SetCompositionMethod](ue_ue.OculusMR_Settings.md#setcompositionmethod)
- [SetDepthQuality](ue_ue.OculusMR_Settings.md#setdepthquality)
- [SetIsCasting](ue_ue.OculusMR_Settings.md#setiscasting)
- [SetUseDynamicLighting](ue_ue.OculusMR_Settings.md#setusedynamiclighting)
- [Find](ue_ue.OculusMR_Settings.md#find)
- [Load](ue_ue.OculusMR_Settings.md#load)
- [StaticClass](ue_ue.OculusMR_Settings.md#staticclass)

## Constructors

### constructor

• **new OculusMR_Settings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### BackdropColor

• **BackdropColor**: [`Color`](ue_ue_s.Color.md)

___

### CapturingCamera

• **CapturingCamera**: [`EOculusMR_CameraDeviceEnum`](../enums/ue_ue.EOculusMR_CameraDeviceEnum.md)

___

### CastingLatency

• **CastingLatency**: `number`

___

### ChromaKeyColor

• **ChromaKeyColor**: [`Color`](ue_ue_s.Color.md)

___

### ChromaKeySimilarity

• **ChromaKeySimilarity**: `number`

___

### ChromaKeySmoothRange

• **ChromaKeySmoothRange**: `number`

___

### ChromaKeySpillRange

• **ChromaKeySpillRange**: `number`

___

### ClippingReference

• **ClippingReference**: [`EOculusMR_ClippingReference`](../enums/ue_ue.EOculusMR_ClippingReference.md)

___

### CompositionMethod

• **CompositionMethod**: [`EOculusMR_CompositionMethod`](../enums/ue_ue.EOculusMR_CompositionMethod.md)

___

### DepthQuality

• **DepthQuality**: [`EOculusMR_DepthQuality`](../enums/ue_ue.EOculusMR_DepthQuality.md)

___

### DynamicLightingDepthSmoothFactor

• **DynamicLightingDepthSmoothFactor**: `number`

___

### DynamicLightingDepthVariationClampingValue

• **DynamicLightingDepthVariationClampingValue**: `number`

___

### ExternalCompositionPostProcessEffects

• **ExternalCompositionPostProcessEffects**: [`EOculusMR_PostProcessEffects`](../enums/ue_ue.EOculusMR_PostProcessEffects.md)

___

### HandPoseStateLatency

• **HandPoseStateLatency**: `number`

___

### HeightPerView

• **HeightPerView**: `number`

___

### VirtualGreenScreenType

• **VirtualGreenScreenType**: [`EOculusMR_VirtualGreenScreenType`](../enums/ue_ue.EOculusMR_VirtualGreenScreenType.md)

___

### WidthPerView

• **WidthPerView**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_OculusMR\_Settings\_\_

• **\_\_tid\_OculusMR\_Settings\_\_**: `boolean`

___

### bIsCasting

• **bIsCasting**: `boolean`

___

### bUseDynamicLighting

• **bUseDynamicLighting**: `boolean`

___

### bUseTrackedCameraResolution

• **bUseTrackedCameraResolution**: `boolean`

## Methods

### BindToTrackedCameraIndexIfAvailable

▸ **BindToTrackedCameraIndexIfAvailable**(`InTrackedCameraIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTrackedCameraIndex` | `number` |

#### Returns

`void`

___

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

### GetBindToTrackedCameraIndex

▸ **GetBindToTrackedCameraIndex**(): `number`

#### Returns

`number`

___

### GetCapturingCamera

▸ **GetCapturingCamera**(): [`EOculusMR_CameraDeviceEnum`](../enums/ue_ue.EOculusMR_CameraDeviceEnum.md)

#### Returns

[`EOculusMR_CameraDeviceEnum`](../enums/ue_ue.EOculusMR_CameraDeviceEnum.md)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetCompositionMethod

▸ **GetCompositionMethod**(): [`EOculusMR_CompositionMethod`](../enums/ue_ue.EOculusMR_CompositionMethod.md)

#### Returns

[`EOculusMR_CompositionMethod`](../enums/ue_ue.EOculusMR_CompositionMethod.md)

___

### GetDepthQuality

▸ **GetDepthQuality**(): [`EOculusMR_DepthQuality`](../enums/ue_ue.EOculusMR_DepthQuality.md)

#### Returns

[`EOculusMR_DepthQuality`](../enums/ue_ue.EOculusMR_DepthQuality.md)

___

### GetIsCasting

▸ **GetIsCasting**(): `boolean`

#### Returns

`boolean`

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

### GetUseDynamicLighting

▸ **GetUseDynamicLighting**(): `boolean`

#### Returns

`boolean`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### LoadFromIni

▸ **LoadFromIni**(): `void`

#### Returns

`void`

___

### SaveToIni

▸ **SaveToIni**(): `void`

#### Returns

`void`

___

### SetCapturingCamera

▸ **SetCapturingCamera**(`val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | [`EOculusMR_CameraDeviceEnum`](../enums/ue_ue.EOculusMR_CameraDeviceEnum.md) |

#### Returns

`void`

___

### SetCompositionMethod

▸ **SetCompositionMethod**(`val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | [`EOculusMR_CompositionMethod`](../enums/ue_ue.EOculusMR_CompositionMethod.md) |

#### Returns

`void`

___

### SetDepthQuality

▸ **SetDepthQuality**(`val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | [`EOculusMR_DepthQuality`](../enums/ue_ue.EOculusMR_DepthQuality.md) |

#### Returns

`void`

___

### SetIsCasting

▸ **SetIsCasting**(`val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `boolean` |

#### Returns

`void`

___

### SetUseDynamicLighting

▸ **SetUseDynamicLighting**(`val`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `boolean` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`OculusMR_Settings`](ue_ue.OculusMR_Settings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`OculusMR_Settings`](ue_ue.OculusMR_Settings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`OculusMR_Settings`](ue_ue.OculusMR_Settings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`OculusMR_Settings`](ue_ue.OculusMR_Settings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
