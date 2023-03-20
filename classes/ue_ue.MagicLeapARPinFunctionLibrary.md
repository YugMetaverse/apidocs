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

#### Defined in

[ue/ue.d.ts:46574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46574)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_MagicLeapARPinFunctionLibrary\_\_

• **\_\_tid\_MagicLeapARPinFunctionLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:46586](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46586)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

### CreateTracker

▸ `Static` **CreateTracker**(): [`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

#### Returns

[`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

#### Defined in

[ue/ue.d.ts:46575](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46575)

___

### DestroyTracker

▸ `Static` **DestroyTracker**(): [`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

#### Returns

[`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

#### Defined in

[ue/ue.d.ts:46576](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46576)

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

#### Defined in

[ue/ue.d.ts:46583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46583)

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

#### Defined in

[ue/ue.d.ts:46577](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46577)

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

#### Defined in

[ue/ue.d.ts:46578](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46578)

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

#### Defined in

[ue/ue.d.ts:46579](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46579)

___

### GetNumAvailableARPins

▸ `Static` **GetNumAvailableARPins**(`Count`): [`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Count` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

[`EMagicLeapPassableWorldError`](../enums/ue_ue.EMagicLeapPassableWorldError.md)

#### Defined in

[ue/ue.d.ts:46580](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46580)

___

### IsTrackerValid

▸ `Static` **IsTrackerValid**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46581](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46581)

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

#### Defined in

[ue/ue.d.ts:46584](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46584)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:46582](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46582)
