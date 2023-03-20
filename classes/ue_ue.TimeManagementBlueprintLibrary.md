[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TimeManagementBlueprintLibrary

# Class: TimeManagementBlueprintLibrary

[ue/ue](../modules/ue_ue.md).TimeManagementBlueprintLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`TimeManagementBlueprintLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.TimeManagementBlueprintLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.TimeManagementBlueprintLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.TimeManagementBlueprintLibrary.md#__tid_object__)
- [\_\_tid\_TimeManagementBlueprintLibrary\_\_](ue_ue.TimeManagementBlueprintLibrary.md#__tid_timemanagementblueprintlibrary__)

### Methods

- [CreateDefaultSubobject](ue_ue.TimeManagementBlueprintLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TimeManagementBlueprintLibrary.md#executeubergraph)
- [GetClass](ue_ue.TimeManagementBlueprintLibrary.md#getclass)
- [GetName](ue_ue.TimeManagementBlueprintLibrary.md#getname)
- [GetOuter](ue_ue.TimeManagementBlueprintLibrary.md#getouter)
- [GetWorld](ue_ue.TimeManagementBlueprintLibrary.md#getworld)
- [Add\_FrameNumberFrameNumber](ue_ue.TimeManagementBlueprintLibrary.md#add_framenumberframenumber)
- [Add\_FrameNumberInteger](ue_ue.TimeManagementBlueprintLibrary.md#add_framenumberinteger)
- [Conv\_FrameNumberToInteger](ue_ue.TimeManagementBlueprintLibrary.md#conv_framenumbertointeger)
- [Conv\_FrameRateToSeconds](ue_ue.TimeManagementBlueprintLibrary.md#conv_frameratetoseconds)
- [Conv\_QualifiedFrameTimeToSeconds](ue_ue.TimeManagementBlueprintLibrary.md#conv_qualifiedframetimetoseconds)
- [Conv\_TimecodeToString](ue_ue.TimeManagementBlueprintLibrary.md#conv_timecodetostring)
- [Divide\_FrameNumberInteger](ue_ue.TimeManagementBlueprintLibrary.md#divide_framenumberinteger)
- [Find](ue_ue.TimeManagementBlueprintLibrary.md#find)
- [GetTimecode](ue_ue.TimeManagementBlueprintLibrary.md#gettimecode)
- [GetTimecodeFrameRate](ue_ue.TimeManagementBlueprintLibrary.md#gettimecodeframerate)
- [IsValid\_Framerate](ue_ue.TimeManagementBlueprintLibrary.md#isvalid_framerate)
- [IsValid\_MultipleOf](ue_ue.TimeManagementBlueprintLibrary.md#isvalid_multipleof)
- [Load](ue_ue.TimeManagementBlueprintLibrary.md#load)
- [Multiply\_FrameNumberInteger](ue_ue.TimeManagementBlueprintLibrary.md#multiply_framenumberinteger)
- [Multiply\_SecondsFrameRate](ue_ue.TimeManagementBlueprintLibrary.md#multiply_secondsframerate)
- [SnapFrameTimeToRate](ue_ue.TimeManagementBlueprintLibrary.md#snapframetimetorate)
- [StaticClass](ue_ue.TimeManagementBlueprintLibrary.md#staticclass)
- [Subtract\_FrameNumberFrameNumber](ue_ue.TimeManagementBlueprintLibrary.md#subtract_framenumberframenumber)
- [Subtract\_FrameNumberInteger](ue_ue.TimeManagementBlueprintLibrary.md#subtract_framenumberinteger)
- [TransformTime](ue_ue.TimeManagementBlueprintLibrary.md#transformtime)

## Constructors

### constructor

• **new TimeManagementBlueprintLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:63662](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63662)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_TimeManagementBlueprintLibrary\_\_

• **\_\_tid\_TimeManagementBlueprintLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:63684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63684)

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

### Add\_FrameNumberFrameNumber

▸ `Static` **Add_FrameNumberFrameNumber**(`A`, `B`): [`FrameNumber`](ue_ue.FrameNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`FrameNumber`](ue_ue.FrameNumber.md) |
| `B` | [`FrameNumber`](ue_ue.FrameNumber.md) |

#### Returns

[`FrameNumber`](ue_ue.FrameNumber.md)

#### Defined in

[ue/ue.d.ts:63663](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63663)

___

### Add\_FrameNumberInteger

▸ `Static` **Add_FrameNumberInteger**(`A`, `B`): [`FrameNumber`](ue_ue.FrameNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`FrameNumber`](ue_ue.FrameNumber.md) |
| `B` | `number` |

#### Returns

[`FrameNumber`](ue_ue.FrameNumber.md)

#### Defined in

[ue/ue.d.ts:63664](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63664)

___

### Conv\_FrameNumberToInteger

▸ `Static` **Conv_FrameNumberToInteger**(`InFrameNumber`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFrameNumber` | [`FrameNumber`](ue_ue.FrameNumber.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:63665](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63665)

___

### Conv\_FrameRateToSeconds

▸ `Static` **Conv_FrameRateToSeconds**(`InFrameRate`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFrameRate` | [`FrameRate`](ue_ue.FrameRate.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:63666](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63666)

___

### Conv\_QualifiedFrameTimeToSeconds

▸ `Static` **Conv_QualifiedFrameTimeToSeconds**(`InFrameTime`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFrameTime` | [`QualifiedFrameTime`](ue_ue.QualifiedFrameTime.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:63667](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63667)

___

### Conv\_TimecodeToString

▸ `Static` **Conv_TimecodeToString**(`InTimecode`, `bForceSignDisplay?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTimecode` | [`Timecode`](ue_ue.Timecode.md) |
| `bForceSignDisplay?` | `boolean` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:63668](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63668)

___

### Divide\_FrameNumberInteger

▸ `Static` **Divide_FrameNumberInteger**(`A`, `B`): [`FrameNumber`](ue_ue.FrameNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`FrameNumber`](ue_ue.FrameNumber.md) |
| `B` | `number` |

#### Returns

[`FrameNumber`](ue_ue.FrameNumber.md)

#### Defined in

[ue/ue.d.ts:63669](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63669)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TimeManagementBlueprintLibrary`](ue_ue.TimeManagementBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TimeManagementBlueprintLibrary`](ue_ue.TimeManagementBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:63681](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63681)

___

### GetTimecode

▸ `Static` **GetTimecode**(): [`Timecode`](ue_ue.Timecode.md)

#### Returns

[`Timecode`](ue_ue.Timecode.md)

#### Defined in

[ue/ue.d.ts:63670](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63670)

___

### GetTimecodeFrameRate

▸ `Static` **GetTimecodeFrameRate**(): [`FrameRate`](ue_ue.FrameRate.md)

#### Returns

[`FrameRate`](ue_ue.FrameRate.md)

#### Defined in

[ue/ue.d.ts:63671](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63671)

___

### IsValid\_Framerate

▸ `Static` **IsValid_Framerate**(`InFrameRate`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFrameRate` | [`FrameRate`](ue_ue.FrameRate.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:63672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63672)

___

### IsValid\_MultipleOf

▸ `Static` **IsValid_MultipleOf**(`InFrameRate`, `OtherFramerate`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFrameRate` | [`FrameRate`](ue_ue.FrameRate.md) |
| `OtherFramerate` | [`FrameRate`](ue_ue.FrameRate.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:63673](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63673)

___

### Load

▸ `Static` **Load**(`InName`): [`TimeManagementBlueprintLibrary`](ue_ue.TimeManagementBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TimeManagementBlueprintLibrary`](ue_ue.TimeManagementBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:63682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63682)

___

### Multiply\_FrameNumberInteger

▸ `Static` **Multiply_FrameNumberInteger**(`A`, `B`): [`FrameNumber`](ue_ue.FrameNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`FrameNumber`](ue_ue.FrameNumber.md) |
| `B` | `number` |

#### Returns

[`FrameNumber`](ue_ue.FrameNumber.md)

#### Defined in

[ue/ue.d.ts:63674](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63674)

___

### Multiply\_SecondsFrameRate

▸ `Static` **Multiply_SecondsFrameRate**(`TimeInSeconds`, `FrameRate`): [`FrameTime`](ue_ue.FrameTime.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeInSeconds` | `number` |
| `FrameRate` | [`FrameRate`](ue_ue.FrameRate.md) |

#### Returns

[`FrameTime`](ue_ue.FrameTime.md)

#### Defined in

[ue/ue.d.ts:63675](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63675)

___

### SnapFrameTimeToRate

▸ `Static` **SnapFrameTimeToRate**(`SourceTime`, `SourceRate`, `SnapToRate`): [`FrameTime`](ue_ue.FrameTime.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceTime` | [`FrameTime`](ue_ue.FrameTime.md) |
| `SourceRate` | [`FrameRate`](ue_ue.FrameRate.md) |
| `SnapToRate` | [`FrameRate`](ue_ue.FrameRate.md) |

#### Returns

[`FrameTime`](ue_ue.FrameTime.md)

#### Defined in

[ue/ue.d.ts:63676](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63676)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:63680](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63680)

___

### Subtract\_FrameNumberFrameNumber

▸ `Static` **Subtract_FrameNumberFrameNumber**(`A`, `B`): [`FrameNumber`](ue_ue.FrameNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`FrameNumber`](ue_ue.FrameNumber.md) |
| `B` | [`FrameNumber`](ue_ue.FrameNumber.md) |

#### Returns

[`FrameNumber`](ue_ue.FrameNumber.md)

#### Defined in

[ue/ue.d.ts:63677](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63677)

___

### Subtract\_FrameNumberInteger

▸ `Static` **Subtract_FrameNumberInteger**(`A`, `B`): [`FrameNumber`](ue_ue.FrameNumber.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`FrameNumber`](ue_ue.FrameNumber.md) |
| `B` | `number` |

#### Returns

[`FrameNumber`](ue_ue.FrameNumber.md)

#### Defined in

[ue/ue.d.ts:63678](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63678)

___

### TransformTime

▸ `Static` **TransformTime**(`SourceTime`, `SourceRate`, `DestinationRate`): [`FrameTime`](ue_ue.FrameTime.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceTime` | [`FrameTime`](ue_ue.FrameTime.md) |
| `SourceRate` | [`FrameRate`](ue_ue.FrameRate.md) |
| `DestinationRate` | [`FrameRate`](ue_ue.FrameRate.md) |

#### Returns

[`FrameTime`](ue_ue.FrameTime.md)

#### Defined in

[ue/ue.d.ts:63679](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L63679)
