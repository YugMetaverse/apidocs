[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KismetTextLibrary

# Class: KismetTextLibrary

[ue/ue](../modules/ue_ue.md).KismetTextLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`KismetTextLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.KismetTextLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.KismetTextLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_KismetTextLibrary\_\_](ue_ue.KismetTextLibrary.md#__tid_kismettextlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.KismetTextLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.KismetTextLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.KismetTextLibrary.md#executeubergraph)
- [GetClass](ue_ue.KismetTextLibrary.md#getclass)
- [GetName](ue_ue.KismetTextLibrary.md#getname)
- [GetOuter](ue_ue.KismetTextLibrary.md#getouter)
- [GetWorld](ue_ue.KismetTextLibrary.md#getworld)
- [AsCurrencyBase](ue_ue.KismetTextLibrary.md#ascurrencybase)
- [AsCurrency\_Float](ue_ue.KismetTextLibrary.md#ascurrency_float)
- [AsCurrency\_Integer](ue_ue.KismetTextLibrary.md#ascurrency_integer)
- [AsDateTime\_DateTime](ue_ue.KismetTextLibrary.md#asdatetime_datetime)
- [AsDate\_DateTime](ue_ue.KismetTextLibrary.md#asdate_datetime)
- [AsPercent\_Float](ue_ue.KismetTextLibrary.md#aspercent_float)
- [AsTimeZoneDateTime\_DateTime](ue_ue.KismetTextLibrary.md#astimezonedatetime_datetime)
- [AsTimeZoneDate\_DateTime](ue_ue.KismetTextLibrary.md#astimezonedate_datetime)
- [AsTimeZoneTime\_DateTime](ue_ue.KismetTextLibrary.md#astimezonetime_datetime)
- [AsTime\_DateTime](ue_ue.KismetTextLibrary.md#astime_datetime)
- [AsTimespan\_Timespan](ue_ue.KismetTextLibrary.md#astimespan_timespan)
- [Conv\_BoolToText](ue_ue.KismetTextLibrary.md#conv_booltotext)
- [Conv\_ByteToText](ue_ue.KismetTextLibrary.md#conv_bytetotext)
- [Conv\_ColorToText](ue_ue.KismetTextLibrary.md#conv_colortotext)
- [Conv\_FloatToText](ue_ue.KismetTextLibrary.md#conv_floattotext)
- [Conv\_Int64ToText](ue_ue.KismetTextLibrary.md#conv_int64totext)
- [Conv\_IntToText](ue_ue.KismetTextLibrary.md#conv_inttotext)
- [Conv\_NameToText](ue_ue.KismetTextLibrary.md#conv_nametotext)
- [Conv\_ObjectToText](ue_ue.KismetTextLibrary.md#conv_objecttotext)
- [Conv\_RotatorToText](ue_ue.KismetTextLibrary.md#conv_rotatortotext)
- [Conv\_StringToText](ue_ue.KismetTextLibrary.md#conv_stringtotext)
- [Conv\_TextToString](ue_ue.KismetTextLibrary.md#conv_texttostring)
- [Conv\_TransformToText](ue_ue.KismetTextLibrary.md#conv_transformtotext)
- [Conv\_Vector2dToText](ue_ue.KismetTextLibrary.md#conv_vector2dtotext)
- [Conv\_VectorToText](ue_ue.KismetTextLibrary.md#conv_vectortotext)
- [EqualEqual\_IgnoreCase\_TextText](ue_ue.KismetTextLibrary.md#equalequal_ignorecase_texttext)
- [EqualEqual\_TextText](ue_ue.KismetTextLibrary.md#equalequal_texttext)
- [Find](ue_ue.KismetTextLibrary.md#find)
- [FindTextInLocalizationTable](ue_ue.KismetTextLibrary.md#findtextinlocalizationtable)
- [Format](ue_ue.KismetTextLibrary.md#format)
- [GetEmptyText](ue_ue.KismetTextLibrary.md#getemptytext)
- [IsPolyglotDataValid](ue_ue.KismetTextLibrary.md#ispolyglotdatavalid)
- [Load](ue_ue.KismetTextLibrary.md#load)
- [NotEqual\_IgnoreCase\_TextText](ue_ue.KismetTextLibrary.md#notequal_ignorecase_texttext)
- [NotEqual\_TextText](ue_ue.KismetTextLibrary.md#notequal_texttext)
- [PolyglotDataToText](ue_ue.KismetTextLibrary.md#polyglotdatatotext)
- [StaticClass](ue_ue.KismetTextLibrary.md#staticclass)
- [StringTableIdAndKeyFromText](ue_ue.KismetTextLibrary.md#stringtableidandkeyfromtext)
- [TextFromStringTable](ue_ue.KismetTextLibrary.md#textfromstringtable)
- [TextIsCultureInvariant](ue_ue.KismetTextLibrary.md#textiscultureinvariant)
- [TextIsEmpty](ue_ue.KismetTextLibrary.md#textisempty)
- [TextIsFromStringTable](ue_ue.KismetTextLibrary.md#textisfromstringtable)
- [TextIsTransient](ue_ue.KismetTextLibrary.md#textistransient)
- [TextToLower](ue_ue.KismetTextLibrary.md#texttolower)
- [TextToUpper](ue_ue.KismetTextLibrary.md#texttoupper)
- [TextTrimPreceding](ue_ue.KismetTextLibrary.md#texttrimpreceding)
- [TextTrimPrecedingAndTrailing](ue_ue.KismetTextLibrary.md#texttrimprecedingandtrailing)
- [TextTrimTrailing](ue_ue.KismetTextLibrary.md#texttrimtrailing)

## Constructors

### constructor

• **new KismetTextLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:43550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43550)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13418)

___

### \_\_tid\_KismetTextLibrary\_\_

• **\_\_tid\_KismetTextLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:43600](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43600)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### AsCurrencyBase

▸ `Static` **AsCurrencyBase**(`BaseValue`, `CurrencyCode`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BaseValue` | `number` |
| `CurrencyCode` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43553](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43553)

___

### AsCurrency\_Float

▸ `Static` **AsCurrency_Float**(`Value`, `RoundingMode`, `bAlwaysSign?`, `bUseGrouping?`, `MinimumIntegralDigits?`, `MaximumIntegralDigits?`, `MinimumFractionalDigits?`, `MaximumFractionalDigits?`, `CurrencyCode?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |
| `RoundingMode` | [`ERoundingMode`](../enums/ue_ue.ERoundingMode.md) |
| `bAlwaysSign?` | `boolean` |
| `bUseGrouping?` | `boolean` |
| `MinimumIntegralDigits?` | `number` |
| `MaximumIntegralDigits?` | `number` |
| `MinimumFractionalDigits?` | `number` |
| `MaximumFractionalDigits?` | `number` |
| `CurrencyCode?` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43551](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43551)

___

### AsCurrency\_Integer

▸ `Static` **AsCurrency_Integer**(`Value`, `RoundingMode`, `bAlwaysSign?`, `bUseGrouping?`, `MinimumIntegralDigits?`, `MaximumIntegralDigits?`, `MinimumFractionalDigits?`, `MaximumFractionalDigits?`, `CurrencyCode?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |
| `RoundingMode` | [`ERoundingMode`](../enums/ue_ue.ERoundingMode.md) |
| `bAlwaysSign?` | `boolean` |
| `bUseGrouping?` | `boolean` |
| `MinimumIntegralDigits?` | `number` |
| `MaximumIntegralDigits?` | `number` |
| `MinimumFractionalDigits?` | `number` |
| `MaximumFractionalDigits?` | `number` |
| `CurrencyCode?` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43552](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43552)

___

### AsDateTime\_DateTime

▸ `Static` **AsDateTime_DateTime**(`In`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `In` | [`DateTime`](ue_ue.DateTime.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43555)

___

### AsDate\_DateTime

▸ `Static` **AsDate_DateTime**(`InDateTime`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InDateTime` | [`DateTime`](ue_ue.DateTime.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43554)

___

### AsPercent\_Float

▸ `Static` **AsPercent_Float**(`Value`, `RoundingMode`, `bAlwaysSign?`, `bUseGrouping?`, `MinimumIntegralDigits?`, `MaximumIntegralDigits?`, `MinimumFractionalDigits?`, `MaximumFractionalDigits?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |
| `RoundingMode` | [`ERoundingMode`](../enums/ue_ue.ERoundingMode.md) |
| `bAlwaysSign?` | `boolean` |
| `bUseGrouping?` | `boolean` |
| `MinimumIntegralDigits?` | `number` |
| `MaximumIntegralDigits?` | `number` |
| `MinimumFractionalDigits?` | `number` |
| `MaximumFractionalDigits?` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43556)

___

### AsTimeZoneDateTime\_DateTime

▸ `Static` **AsTimeZoneDateTime_DateTime**(`InDateTime`, `InTimeZone?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InDateTime` | [`DateTime`](ue_ue.DateTime.md) |
| `InTimeZone?` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43560)

___

### AsTimeZoneDate\_DateTime

▸ `Static` **AsTimeZoneDate_DateTime**(`InDateTime`, `InTimeZone?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InDateTime` | [`DateTime`](ue_ue.DateTime.md) |
| `InTimeZone?` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43559)

___

### AsTimeZoneTime\_DateTime

▸ `Static` **AsTimeZoneTime_DateTime**(`InDateTime`, `InTimeZone?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InDateTime` | [`DateTime`](ue_ue.DateTime.md) |
| `InTimeZone?` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43561)

___

### AsTime\_DateTime

▸ `Static` **AsTime_DateTime**(`In`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `In` | [`DateTime`](ue_ue.DateTime.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43557)

___

### AsTimespan\_Timespan

▸ `Static` **AsTimespan_Timespan**(`InTimespan`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTimespan` | [`Timespan`](ue_ue.Timespan.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43558)

___

### Conv\_BoolToText

▸ `Static` **Conv_BoolToText**(`InBool`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBool` | `boolean` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43562)

___

### Conv\_ByteToText

▸ `Static` **Conv_ByteToText**(`Value`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43563](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43563)

___

### Conv\_ColorToText

▸ `Static` **Conv_ColorToText**(`InColor`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43564)

___

### Conv\_FloatToText

▸ `Static` **Conv_FloatToText**(`Value`, `RoundingMode`, `bAlwaysSign?`, `bUseGrouping?`, `MinimumIntegralDigits?`, `MaximumIntegralDigits?`, `MinimumFractionalDigits?`, `MaximumFractionalDigits?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |
| `RoundingMode` | [`ERoundingMode`](../enums/ue_ue.ERoundingMode.md) |
| `bAlwaysSign?` | `boolean` |
| `bUseGrouping?` | `boolean` |
| `MinimumIntegralDigits?` | `number` |
| `MaximumIntegralDigits?` | `number` |
| `MinimumFractionalDigits?` | `number` |
| `MaximumFractionalDigits?` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43565)

___

### Conv\_Int64ToText

▸ `Static` **Conv_Int64ToText**(`Value`, `bAlwaysSign?`, `bUseGrouping?`, `MinimumIntegralDigits?`, `MaximumIntegralDigits?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `bigint` |
| `bAlwaysSign?` | `boolean` |
| `bUseGrouping?` | `boolean` |
| `MinimumIntegralDigits?` | `number` |
| `MaximumIntegralDigits?` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43566)

___

### Conv\_IntToText

▸ `Static` **Conv_IntToText**(`Value`, `bAlwaysSign?`, `bUseGrouping?`, `MinimumIntegralDigits?`, `MaximumIntegralDigits?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Value` | `number` |
| `bAlwaysSign?` | `boolean` |
| `bUseGrouping?` | `boolean` |
| `MinimumIntegralDigits?` | `number` |
| `MaximumIntegralDigits?` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43567)

___

### Conv\_NameToText

▸ `Static` **Conv_NameToText**(`InName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43568)

___

### Conv\_ObjectToText

▸ `Static` **Conv_ObjectToText**(`InObj`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InObj` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43569)

___

### Conv\_RotatorToText

▸ `Static` **Conv_RotatorToText**(`InRot`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRot` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43570)

___

### Conv\_StringToText

▸ `Static` **Conv_StringToText**(`InString`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InString` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43571](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43571)

___

### Conv\_TextToString

▸ `Static` **Conv_TextToString**(`InText`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InText` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43572](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43572)

___

### Conv\_TransformToText

▸ `Static` **Conv_TransformToText**(`InTrans`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTrans` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43573](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43573)

___

### Conv\_Vector2dToText

▸ `Static` **Conv_Vector2dToText**(`InVec`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVec` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43574)

___

### Conv\_VectorToText

▸ `Static` **Conv_VectorToText**(`InVec`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVec` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43575](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43575)

___

### EqualEqual\_IgnoreCase\_TextText

▸ `Static` **EqualEqual_IgnoreCase_TextText**(`A`, `B`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `string` |
| `B` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43576](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43576)

___

### EqualEqual\_TextText

▸ `Static` **EqualEqual_TextText**(`A`, `B`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `string` |
| `B` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43577](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43577)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`KismetTextLibrary`](ue_ue.KismetTextLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`KismetTextLibrary`](ue_ue.KismetTextLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:43597](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43597)

___

### FindTextInLocalizationTable

▸ `Static` **FindTextInLocalizationTable**(`Namespace`, `Key`, `OutText`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Namespace` | `string` |
| `Key` | `string` |
| `OutText` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43578](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43578)

___

### Format

▸ `Static` **Format**(`InPattern`, `InArgs`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPattern` | `string` |
| `InArgs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FormatArgumentData`](ue_ue.FormatArgumentData.md)\> |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43579](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43579)

___

### GetEmptyText

▸ `Static` **GetEmptyText**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43580](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43580)

___

### IsPolyglotDataValid

▸ `Static` **IsPolyglotDataValid**(`PolyglotData`, `IsValid`, `ErrorMessage`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolyglotData` | [`PolyglotTextData`](ue_ue.PolyglotTextData.md) |
| `IsValid` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `ErrorMessage` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43581](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43581)

___

### Load

▸ `Static` **Load**(`InName`): [`KismetTextLibrary`](ue_ue.KismetTextLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`KismetTextLibrary`](ue_ue.KismetTextLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:43598](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43598)

___

### NotEqual\_IgnoreCase\_TextText

▸ `Static` **NotEqual_IgnoreCase_TextText**(`A`, `B`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `string` |
| `B` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43582)

___

### NotEqual\_TextText

▸ `Static` **NotEqual_TextText**(`A`, `B`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `string` |
| `B` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43583)

___

### PolyglotDataToText

▸ `Static` **PolyglotDataToText**(`PolyglotData`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolyglotData` | [`PolyglotTextData`](ue_ue.PolyglotTextData.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43584](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43584)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:43596](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43596)

___

### StringTableIdAndKeyFromText

▸ `Static` **StringTableIdAndKeyFromText**(`Text`, `OutTableId`, `OutKey`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Text` | `string` |
| `OutTableId` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `OutKey` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43585](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43585)

___

### TextFromStringTable

▸ `Static` **TextFromStringTable**(`TableId`, `Key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TableId` | `string` |
| `Key` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43586](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43586)

___

### TextIsCultureInvariant

▸ `Static` **TextIsCultureInvariant**(`InText`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InText` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43587](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43587)

___

### TextIsEmpty

▸ `Static` **TextIsEmpty**(`InText`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InText` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43588)

___

### TextIsFromStringTable

▸ `Static` **TextIsFromStringTable**(`Text`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Text` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43589)

___

### TextIsTransient

▸ `Static` **TextIsTransient**(`InText`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InText` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43590)

___

### TextToLower

▸ `Static` **TextToLower**(`InText`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InText` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43591](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43591)

___

### TextToUpper

▸ `Static` **TextToUpper**(`InText`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InText` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43592](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43592)

___

### TextTrimPreceding

▸ `Static` **TextTrimPreceding**(`InText`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InText` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43593](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43593)

___

### TextTrimPrecedingAndTrailing

▸ `Static` **TextTrimPrecedingAndTrailing**(`InText`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InText` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43594](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43594)

___

### TextTrimTrailing

▸ `Static` **TextTrimTrailing**(`InText`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InText` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43595](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43595)