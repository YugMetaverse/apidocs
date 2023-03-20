[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LocationServices

# Class: LocationServices

[ue/ue](../modules/ue_ue.md).LocationServices

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`LocationServices`**

## Table of contents

### Constructors

- [constructor](ue_ue.LocationServices.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.LocationServices.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_LocationServices\_\_](ue_ue.LocationServices.md#__tid_locationservices__)
- [\_\_tid\_Object\_\_](ue_ue.LocationServices.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LocationServices.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LocationServices.md#executeubergraph)
- [GetClass](ue_ue.LocationServices.md#getclass)
- [GetName](ue_ue.LocationServices.md#getname)
- [GetOuter](ue_ue.LocationServices.md#getouter)
- [GetWorld](ue_ue.LocationServices.md#getworld)
- [AreLocationServicesEnabled](ue_ue.LocationServices.md#arelocationservicesenabled)
- [Find](ue_ue.LocationServices.md#find)
- [GetLastKnownLocation](ue_ue.LocationServices.md#getlastknownlocation)
- [GetLocationServicesImpl](ue_ue.LocationServices.md#getlocationservicesimpl)
- [InitLocationServices](ue_ue.LocationServices.md#initlocationservices)
- [IsLocationAccuracyAvailable](ue_ue.LocationServices.md#islocationaccuracyavailable)
- [Load](ue_ue.LocationServices.md#load)
- [StartLocationServices](ue_ue.LocationServices.md#startlocationservices)
- [StaticClass](ue_ue.LocationServices.md#staticclass)
- [StopLocationServices](ue_ue.LocationServices.md#stoplocationservices)

## Constructors

### constructor

• **new LocationServices**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_LocationServices\_\_

• **\_\_tid\_LocationServices\_\_**: `boolean`

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

### AreLocationServicesEnabled

▸ `Static` **AreLocationServicesEnabled**(): `boolean`

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LocationServices`](ue_ue.LocationServices.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LocationServices`](ue_ue.LocationServices.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetLastKnownLocation

▸ `Static` **GetLastKnownLocation**(): [`LocationServicesData`](ue_ue.LocationServicesData.md)

#### Returns

[`LocationServicesData`](ue_ue.LocationServicesData.md)

___

### GetLocationServicesImpl

▸ `Static` **GetLocationServicesImpl**(): [`LocationServicesImpl`](ue_ue.LocationServicesImpl.md)

#### Returns

[`LocationServicesImpl`](ue_ue.LocationServicesImpl.md)

___

### InitLocationServices

▸ `Static` **InitLocationServices**(`Accuracy`, `UpdateFrequency`, `MinDistanceFilter`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Accuracy` | [`ELocationAccuracy`](../enums/ue_ue.ELocationAccuracy.md) |
| `UpdateFrequency` | `number` |
| `MinDistanceFilter` | `number` |

#### Returns

`boolean`

___

### IsLocationAccuracyAvailable

▸ `Static` **IsLocationAccuracyAvailable**(`Accuracy`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Accuracy` | [`ELocationAccuracy`](../enums/ue_ue.ELocationAccuracy.md) |

#### Returns

`boolean`

___

### Load

▸ `Static` **Load**(`InName`): [`LocationServices`](ue_ue.LocationServices.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LocationServices`](ue_ue.LocationServices.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StartLocationServices

▸ `Static` **StartLocationServices**(): `boolean`

#### Returns

`boolean`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

___

### StopLocationServices

▸ `Static` **StopLocationServices**(): `boolean`

#### Returns

`boolean`
