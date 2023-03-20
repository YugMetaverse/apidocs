[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapARPinFunctionLibrary

# Class: MagicLeapARPinFunctionLibrary

[ue/ue](../modules/ue_ue.md).MagicLeapARPinFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`MagicLeapARPinFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapARPinFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.MagicLeapARPinFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_MagicLeapARPinFunctionLibrary\_\_](ue_ue.MagicLeapARPinFunctionLibrary.md#__tid_magicleaparpinfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.MagicLeapARPinFunctionLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MagicLeapARPinFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MagicLeapARPinFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.MagicLeapARPinFunctionLibrary.md#getclass)
- [GetName](ue_ue.MagicLeapARPinFunctionLibrary.md#getname)
- [GetOuter](ue_ue.MagicLeapARPinFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.MagicLeapARPinFunctionLibrary.md#getworld)
- [CreateTracker](ue_ue.MagicLeapARPinFunctionLibrary.md#createtracker)
- [DestroyTracker](ue_ue.MagicLeapARPinFunctionLibrary.md#destroytracker)
- [Find](ue_ue.MagicLeapARPinFunctionLibrary.md#find)
- [GetARPinPositionAndOrientation](ue_ue.MagicLeapARPinFunctionLibrary.md#getarpinpositionandorientation)
- [GetAvailableARPins](ue_ue.MagicLeapARPinFunctionLibrary.md#getavailablearpins)
- [GetClosestARPin](ue_ue.MagicLeapARPinFunctionLibrary.md#getclosestarpin)
- [GetNumAvailableARPins](ue_ue.MagicLeapARPinFunctionLibrary.md#getnumavailablearpins)
- [IsTrackerValid](ue_ue.MagicLeapARPinFunctionLibrary.md#istrackervalid)
- [Load](ue_ue.MagicLeapARPinFunctionLibrary.md#load)
- [StaticClass](ue_ue.MagicLeapARPinFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new MagicLeapARPinFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_MagicLeapARPinFunctionLibrary\_\_

• **\_\_tid\_MagicLeapARPinFunctionLibrary\_\_**: `boolean`

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

### CreateTracker

▸ `Static` **CreateTracker**(): [`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

#### Returns

[`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

___

### DestroyTracker

▸ `Static` **DestroyTracker**(): [`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

#### Returns

[`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MagicLeapARPinFunctionLibrary`](ue_ue.MagicLeapARPinFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MagicLeapARPinFunctionLibrary`](ue_ue.MagicLeapARPinFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetARPinPositionAndOrientation

▸ `Static` **GetARPinPositionAndOrientation**(`PinID`, `Position`, `Orientation`, `PinFoundInEnvironment`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PinID` | [`Guid`](ue_ue_s.Guid.md) |
| `Position` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Orientation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |
| `PinFoundInEnvironment` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`boolean`

___

### GetAvailableARPins

▸ `Static` **GetAvailableARPins**(`NumRequested`, `Pins`): [`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumRequested` | `number` |
| `Pins` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>\> |

#### Returns

[`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

___

### GetClosestARPin

▸ `Static` **GetClosestARPin**(`SearchPoint`, `PinID`): [`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SearchPoint` | [`Vector`](ue_ue_s.Vector.md) |
| `PinID` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Guid`](ue_ue_s.Guid.md)\> |

#### Returns

[`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

___

### GetNumAvailableARPins

▸ `Static` **GetNumAvailableARPins**(`Count`): [`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Count` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

[`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

___

### IsTrackerValid

▸ `Static` **IsTrackerValid**(): `boolean`

#### Returns

`boolean`

___

### Load

▸ `Static` **Load**(`InName`): [`MagicLeapARPinFunctionLibrary`](ue_ue.MagicLeapARPinFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MagicLeapARPinFunctionLibrary`](ue_ue.MagicLeapARPinFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
