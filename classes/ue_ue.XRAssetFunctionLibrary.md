[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / XRAssetFunctionLibrary

# Class: XRAssetFunctionLibrary

[ue/ue](../modules/ue_ue.md).XRAssetFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`XRAssetFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.XRAssetFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.XRAssetFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.XRAssetFunctionLibrary.md#__tid_object__)
- [\_\_tid\_XRAssetFunctionLibrary\_\_](ue_ue.XRAssetFunctionLibrary.md#__tid_xrassetfunctionlibrary__)

### Methods

- [CreateDefaultSubobject](ue_ue.XRAssetFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.XRAssetFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.XRAssetFunctionLibrary.md#getclass)
- [GetName](ue_ue.XRAssetFunctionLibrary.md#getname)
- [GetOuter](ue_ue.XRAssetFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.XRAssetFunctionLibrary.md#getworld)
- [AddDeviceVisualizationComponentBlocking](ue_ue.XRAssetFunctionLibrary.md#adddevicevisualizationcomponentblocking)
- [AddNamedDeviceVisualizationComponentBlocking](ue_ue.XRAssetFunctionLibrary.md#addnameddevicevisualizationcomponentblocking)
- [Find](ue_ue.XRAssetFunctionLibrary.md#find)
- [Load](ue_ue.XRAssetFunctionLibrary.md#load)
- [StaticClass](ue_ue.XRAssetFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new XRAssetFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

___

### \_\_tid\_XRAssetFunctionLibrary\_\_

• **\_\_tid\_XRAssetFunctionLibrary\_\_**: `boolean`

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

### AddDeviceVisualizationComponentBlocking

▸ `Static` **AddDeviceVisualizationComponentBlocking**(`Target`, `XRDeviceId`, `bManualAttachment`, `RelativeTransform`): [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Target` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `XRDeviceId` | [`XRDeviceId`](ue_ue.XRDeviceId.md) |
| `bManualAttachment` | `boolean` |
| `RelativeTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

___

### AddNamedDeviceVisualizationComponentBlocking

▸ `Static` **AddNamedDeviceVisualizationComponentBlocking**(`Target`, `SystemName`, `DeviceName`, `bManualAttachment`, `RelativeTransform`, `XRDeviceId`): [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Target` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `SystemName` | `string` |
| `DeviceName` | `string` |
| `bManualAttachment` | `boolean` |
| `RelativeTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `XRDeviceId` | [`$Ref`](../interfaces/puerts._Ref.md)<[`XRDeviceId`](ue_ue.XRDeviceId.md)\> |

#### Returns

[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`XRAssetFunctionLibrary`](ue_ue.XRAssetFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`XRAssetFunctionLibrary`](ue_ue.XRAssetFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`XRAssetFunctionLibrary`](ue_ue.XRAssetFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`XRAssetFunctionLibrary`](ue_ue.XRAssetFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
