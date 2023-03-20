[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SteamVRFunctionLibrary

# Class: SteamVRFunctionLibrary

[ue/ue](../modules/ue_ue.md).SteamVRFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`SteamVRFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.SteamVRFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.SteamVRFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.SteamVRFunctionLibrary.md#__tid_object__)
- [\_\_tid\_SteamVRFunctionLibrary\_\_](ue_ue.SteamVRFunctionLibrary.md#__tid_steamvrfunctionlibrary__)

### Methods

- [CreateDefaultSubobject](ue_ue.SteamVRFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SteamVRFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.SteamVRFunctionLibrary.md#getclass)
- [GetName](ue_ue.SteamVRFunctionLibrary.md#getname)
- [GetOuter](ue_ue.SteamVRFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.SteamVRFunctionLibrary.md#getworld)
- [Find](ue_ue.SteamVRFunctionLibrary.md#find)
- [GetHandPositionAndOrientation](ue_ue.SteamVRFunctionLibrary.md#gethandpositionandorientation)
- [GetTrackedDevicePositionAndOrientation](ue_ue.SteamVRFunctionLibrary.md#gettrackeddevicepositionandorientation)
- [GetValidTrackedDeviceIds](ue_ue.SteamVRFunctionLibrary.md#getvalidtrackeddeviceids)
- [Load](ue_ue.SteamVRFunctionLibrary.md#load)
- [StaticClass](ue_ue.SteamVRFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new SteamVRFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_SteamVRFunctionLibrary\_\_

• **\_\_tid\_SteamVRFunctionLibrary\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SteamVRFunctionLibrary`](ue_ue.SteamVRFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SteamVRFunctionLibrary`](ue_ue.SteamVRFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetHandPositionAndOrientation

▸ `Static` **GetHandPositionAndOrientation**(`ControllerIndex`, `Hand`, `OutPosition`, `OutOrientation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ControllerIndex` | `number` |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `OutPosition` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `OutOrientation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |

#### Returns

`boolean`

___

### GetTrackedDevicePositionAndOrientation

▸ `Static` **GetTrackedDevicePositionAndOrientation**(`DeviceId`, `OutPosition`, `OutOrientation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeviceId` | `number` |
| `OutPosition` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `OutOrientation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |

#### Returns

`boolean`

___

### GetValidTrackedDeviceIds

▸ `Static` **GetValidTrackedDeviceIds**(`DeviceType`, `OutTrackedDeviceIds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeviceType` | [`ESteamVRTrackedDeviceType`](../enums/ue_ue.ESteamVRTrackedDeviceType.md) |
| `OutTrackedDeviceIds` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |

#### Returns

`void`

___

### Load

▸ `Static` **Load**(`InName`): [`SteamVRFunctionLibrary`](ue_ue.SteamVRFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SteamVRFunctionLibrary`](ue_ue.SteamVRFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
