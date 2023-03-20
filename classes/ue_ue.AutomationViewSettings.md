[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AutomationViewSettings

# Class: AutomationViewSettings

[ue/ue](../modules/ue_ue.md).AutomationViewSettings

## Hierarchy

- [`DataAsset`](ue_ue.DataAsset.md)

  ↳ **`AutomationViewSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.AutomationViewSettings.md#constructor)

### Properties

- [AntiAliasing](ue_ue.AutomationViewSettings.md#antialiasing)
- [Bloom](ue_ue.AutomationViewSettings.md#bloom)
- [ContactShadows](ue_ue.AutomationViewSettings.md#contactshadows)
- [DistanceFieldAO](ue_ue.AutomationViewSettings.md#distancefieldao)
- [EyeAdaptation](ue_ue.AutomationViewSettings.md#eyeadaptation)
- [MotionBlur](ue_ue.AutomationViewSettings.md#motionblur)
- [NativeClass](ue_ue.AutomationViewSettings.md#nativeclass)
- [ScreenSpaceAO](ue_ue.AutomationViewSettings.md#screenspaceao)
- [ScreenSpaceReflections](ue_ue.AutomationViewSettings.md#screenspacereflections)
- [TemporalAA](ue_ue.AutomationViewSettings.md#temporalaa)
- [\_\_tid\_AutomationViewSettings\_\_](ue_ue.AutomationViewSettings.md#__tid_automationviewsettings__)
- [\_\_tid\_DataAsset\_\_](ue_ue.AutomationViewSettings.md#__tid_dataasset__)
- [\_\_tid\_Object\_\_](ue_ue.AutomationViewSettings.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AutomationViewSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AutomationViewSettings.md#executeubergraph)
- [GetClass](ue_ue.AutomationViewSettings.md#getclass)
- [GetName](ue_ue.AutomationViewSettings.md#getname)
- [GetOuter](ue_ue.AutomationViewSettings.md#getouter)
- [GetWorld](ue_ue.AutomationViewSettings.md#getworld)
- [Find](ue_ue.AutomationViewSettings.md#find)
- [Load](ue_ue.AutomationViewSettings.md#load)
- [StaticClass](ue_ue.AutomationViewSettings.md#staticclass)

## Constructors

### constructor

• **new AutomationViewSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[constructor](ue_ue.DataAsset.md#constructor)

## Properties

### AntiAliasing

• **AntiAliasing**: `boolean`

___

### Bloom

• **Bloom**: `boolean`

___

### ContactShadows

• **ContactShadows**: `boolean`

___

### DistanceFieldAO

• **DistanceFieldAO**: `boolean`

___

### EyeAdaptation

• **EyeAdaptation**: `boolean`

___

### MotionBlur

• **MotionBlur**: `boolean`

___

### NativeClass

• **NativeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[NativeClass](ue_ue.DataAsset.md#nativeclass)

___

### ScreenSpaceAO

• **ScreenSpaceAO**: `boolean`

___

### ScreenSpaceReflections

• **ScreenSpaceReflections**: `boolean`

___

### TemporalAA

• **TemporalAA**: `boolean`

___

### \_\_tid\_AutomationViewSettings\_\_

• **\_\_tid\_AutomationViewSettings\_\_**: `boolean`

___

### \_\_tid\_DataAsset\_\_

• **\_\_tid\_DataAsset\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_DataAsset__](ue_ue.DataAsset.md#__tid_dataasset__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_Object__](ue_ue.DataAsset.md#__tid_object__)

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

[DataAsset](ue_ue.DataAsset.md).[CreateDefaultSubobject](ue_ue.DataAsset.md#createdefaultsubobject)

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

[DataAsset](ue_ue.DataAsset.md).[ExecuteUbergraph](ue_ue.DataAsset.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetClass](ue_ue.DataAsset.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetName](ue_ue.DataAsset.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetOuter](ue_ue.DataAsset.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetWorld](ue_ue.DataAsset.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AutomationViewSettings`](ue_ue.AutomationViewSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AutomationViewSettings`](ue_ue.AutomationViewSettings.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Find](ue_ue.DataAsset.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AutomationViewSettings`](ue_ue.AutomationViewSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AutomationViewSettings`](ue_ue.AutomationViewSettings.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Load](ue_ue.DataAsset.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[StaticClass](ue_ue.DataAsset.md#staticclass)
