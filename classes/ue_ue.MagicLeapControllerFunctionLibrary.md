[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapControllerFunctionLibrary

# Class: MagicLeapControllerFunctionLibrary

[ue/ue](../modules/ue_ue.md).MagicLeapControllerFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`MagicLeapControllerFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapControllerFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.MagicLeapControllerFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_MagicLeapControllerFunctionLibrary\_\_](ue_ue.MagicLeapControllerFunctionLibrary.md#__tid_magicleapcontrollerfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.MagicLeapControllerFunctionLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MagicLeapControllerFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MagicLeapControllerFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.MagicLeapControllerFunctionLibrary.md#getclass)
- [GetName](ue_ue.MagicLeapControllerFunctionLibrary.md#getname)
- [GetOuter](ue_ue.MagicLeapControllerFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.MagicLeapControllerFunctionLibrary.md#getworld)
- [Find](ue_ue.MagicLeapControllerFunctionLibrary.md#find)
- [GetControllerMapping](ue_ue.MagicLeapControllerFunctionLibrary.md#getcontrollermapping)
- [GetControllerTrackingMode](ue_ue.MagicLeapControllerFunctionLibrary.md#getcontrollertrackingmode)
- [GetControllerType](ue_ue.MagicLeapControllerFunctionLibrary.md#getcontrollertype)
- [GetHandForMotionSource](ue_ue.MagicLeapControllerFunctionLibrary.md#gethandformotionsource)
- [GetMLControllerType](ue_ue.MagicLeapControllerFunctionLibrary.md#getmlcontrollertype)
- [GetMotionSourceForHand](ue_ue.MagicLeapControllerFunctionLibrary.md#getmotionsourceforhand)
- [InvertControllerMapping](ue_ue.MagicLeapControllerFunctionLibrary.md#invertcontrollermapping)
- [IsMLControllerConnected](ue_ue.MagicLeapControllerFunctionLibrary.md#ismlcontrollerconnected)
- [Load](ue_ue.MagicLeapControllerFunctionLibrary.md#load)
- [MaxSupportedMagicLeapControllers](ue_ue.MagicLeapControllerFunctionLibrary.md#maxsupportedmagicleapcontrollers)
- [PlayControllerHapticFeedback](ue_ue.MagicLeapControllerFunctionLibrary.md#playcontrollerhapticfeedback)
- [PlayControllerLED](ue_ue.MagicLeapControllerFunctionLibrary.md#playcontrollerled)
- [PlayControllerLEDEffect](ue_ue.MagicLeapControllerFunctionLibrary.md#playcontrollerledeffect)
- [PlayHapticPattern](ue_ue.MagicLeapControllerFunctionLibrary.md#playhapticpattern)
- [PlayLEDEffect](ue_ue.MagicLeapControllerFunctionLibrary.md#playledeffect)
- [PlayLEDPattern](ue_ue.MagicLeapControllerFunctionLibrary.md#playledpattern)
- [SetControllerTrackingMode](ue_ue.MagicLeapControllerFunctionLibrary.md#setcontrollertrackingmode)
- [SetMotionSourceForHand](ue_ue.MagicLeapControllerFunctionLibrary.md#setmotionsourceforhand)
- [StaticClass](ue_ue.MagicLeapControllerFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new MagicLeapControllerFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:46601](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46601)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_MagicLeapControllerFunctionLibrary\_\_

• **\_\_tid\_MagicLeapControllerFunctionLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:46623](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46623)

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MagicLeapControllerFunctionLibrary`](ue_ue.MagicLeapControllerFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MagicLeapControllerFunctionLibrary`](ue_ue.MagicLeapControllerFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:46620](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46620)

___

### GetControllerMapping

▸ `Static` **GetControllerMapping**(`ControllerIndex`, `Hand`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ControllerIndex` | `number` |
| `Hand` | [`$Ref`](../interfaces/puerts._Ref.md)<[`EControllerHand`](../enums/ue_ue.EControllerHand.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46602](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46602)

___

### GetControllerTrackingMode

▸ `Static` **GetControllerTrackingMode**(): [`EMagicLeapControllerTrackingMode`](../enums/ue_ue.EMagicLeapControllerTrackingMode.md)

#### Returns

[`EMagicLeapControllerTrackingMode`](../enums/ue_ue.EMagicLeapControllerTrackingMode.md)

#### Defined in

[ue/ue.d.ts:46603](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46603)

___

### GetControllerType

▸ `Static` **GetControllerType**(`MotionSource`): [`EMagicLeapControllerType`](../enums/ue_ue.EMagicLeapControllerType.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MotionSource` | `string` |

#### Returns

[`EMagicLeapControllerType`](../enums/ue_ue.EMagicLeapControllerType.md)

#### Defined in

[ue/ue.d.ts:46604](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46604)

___

### GetHandForMotionSource

▸ `Static` **GetHandForMotionSource**(`MotionSource`): [`EControllerHand`](../enums/ue_ue.EControllerHand.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MotionSource` | `string` |

#### Returns

[`EControllerHand`](../enums/ue_ue.EControllerHand.md)

#### Defined in

[ue/ue.d.ts:46605](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46605)

___

### GetMLControllerType

▸ `Static` **GetMLControllerType**(`Hand`): [`EMagicLeapControllerType`](../enums/ue_ue.EMagicLeapControllerType.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |

#### Returns

[`EMagicLeapControllerType`](../enums/ue_ue.EMagicLeapControllerType.md)

#### Defined in

[ue/ue.d.ts:46606](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46606)

___

### GetMotionSourceForHand

▸ `Static` **GetMotionSourceForHand**(`Hand`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:46607](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46607)

___

### InvertControllerMapping

▸ `Static` **InvertControllerMapping**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:46608](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46608)

___

### IsMLControllerConnected

▸ `Static` **IsMLControllerConnected**(`MotionSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MotionSource` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46609](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46609)

___

### Load

▸ `Static` **Load**(`InName`): [`MagicLeapControllerFunctionLibrary`](ue_ue.MagicLeapControllerFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MagicLeapControllerFunctionLibrary`](ue_ue.MagicLeapControllerFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:46621](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46621)

___

### MaxSupportedMagicLeapControllers

▸ `Static` **MaxSupportedMagicLeapControllers**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:46610](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46610)

___

### PlayControllerHapticFeedback

▸ `Static` **PlayControllerHapticFeedback**(`Hand`, `HapticPattern`, `Intensity`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `HapticPattern` | [`EMagicLeapControllerHapticPattern`](../enums/ue_ue.EMagicLeapControllerHapticPattern.md) |
| `Intensity` | [`EMagicLeapControllerHapticIntensity`](../enums/ue_ue.EMagicLeapControllerHapticIntensity.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46611](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46611)

___

### PlayControllerLED

▸ `Static` **PlayControllerLED**(`Hand`, `LEDPattern`, `LEDColor`, `DurationInSec`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `LEDPattern` | [`EMagicLeapControllerLEDPattern`](../enums/ue_ue.EMagicLeapControllerLEDPattern.md) |
| `LEDColor` | [`EMagicLeapControllerLEDColor`](../enums/ue_ue.EMagicLeapControllerLEDColor.md) |
| `DurationInSec` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46612](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46612)

___

### PlayControllerLEDEffect

▸ `Static` **PlayControllerLEDEffect**(`Hand`, `LEDEffect`, `LEDSpeed`, `LEDPattern`, `LEDColor`, `DurationInSec`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `LEDEffect` | [`EMagicLeapControllerLEDEffect`](../enums/ue_ue.EMagicLeapControllerLEDEffect.md) |
| `LEDSpeed` | [`EMagicLeapControllerLEDSpeed`](../enums/ue_ue.EMagicLeapControllerLEDSpeed.md) |
| `LEDPattern` | [`EMagicLeapControllerLEDPattern`](../enums/ue_ue.EMagicLeapControllerLEDPattern.md) |
| `LEDColor` | [`EMagicLeapControllerLEDColor`](../enums/ue_ue.EMagicLeapControllerLEDColor.md) |
| `DurationInSec` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46613](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46613)

___

### PlayHapticPattern

▸ `Static` **PlayHapticPattern**(`MotionSource`, `HapticPattern`, `Intensity`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MotionSource` | `string` |
| `HapticPattern` | [`EMagicLeapControllerHapticPattern`](../enums/ue_ue.EMagicLeapControllerHapticPattern.md) |
| `Intensity` | [`EMagicLeapControllerHapticIntensity`](../enums/ue_ue.EMagicLeapControllerHapticIntensity.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46614](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46614)

___

### PlayLEDEffect

▸ `Static` **PlayLEDEffect**(`MotionSource`, `LEDEffect`, `LEDSpeed`, `LEDPattern`, `LEDColor`, `DurationInSec`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MotionSource` | `string` |
| `LEDEffect` | [`EMagicLeapControllerLEDEffect`](../enums/ue_ue.EMagicLeapControllerLEDEffect.md) |
| `LEDSpeed` | [`EMagicLeapControllerLEDSpeed`](../enums/ue_ue.EMagicLeapControllerLEDSpeed.md) |
| `LEDPattern` | [`EMagicLeapControllerLEDPattern`](../enums/ue_ue.EMagicLeapControllerLEDPattern.md) |
| `LEDColor` | [`EMagicLeapControllerLEDColor`](../enums/ue_ue.EMagicLeapControllerLEDColor.md) |
| `DurationInSec` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46615](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46615)

___

### PlayLEDPattern

▸ `Static` **PlayLEDPattern**(`MotionSource`, `LEDPattern`, `LEDColor`, `DurationInSec`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MotionSource` | `string` |
| `LEDPattern` | [`EMagicLeapControllerLEDPattern`](../enums/ue_ue.EMagicLeapControllerLEDPattern.md) |
| `LEDColor` | [`EMagicLeapControllerLEDColor`](../enums/ue_ue.EMagicLeapControllerLEDColor.md) |
| `DurationInSec` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46616](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46616)

___

### SetControllerTrackingMode

▸ `Static` **SetControllerTrackingMode**(`TrackingMode`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackingMode` | [`EMagicLeapControllerTrackingMode`](../enums/ue_ue.EMagicLeapControllerTrackingMode.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46617](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46617)

___

### SetMotionSourceForHand

▸ `Static` **SetMotionSourceForHand**(`Hand`, `MotionSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `MotionSource` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46618](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46618)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:46619](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46619)
