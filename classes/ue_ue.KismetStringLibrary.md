[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KismetStringLibrary

# Class: KismetStringLibrary

[ue/ue](../modules/ue_ue.md).KismetStringLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`KismetStringLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.KismetStringLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.KismetStringLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_KismetStringLibrary\_\_](ue_ue.KismetStringLibrary.md#__tid_kismetstringlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.KismetStringLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.KismetStringLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.KismetStringLibrary.md#executeubergraph)
- [GetClass](ue_ue.KismetStringLibrary.md#getclass)
- [GetName](ue_ue.KismetStringLibrary.md#getname)
- [GetOuter](ue_ue.KismetStringLibrary.md#getouter)
- [GetWorld](ue_ue.KismetStringLibrary.md#getworld)
- [BuildString\_Bool](ue_ue.KismetStringLibrary.md#buildstring_bool)
- [BuildString\_Color](ue_ue.KismetStringLibrary.md#buildstring_color)
- [BuildString\_Float](ue_ue.KismetStringLibrary.md#buildstring_float)
- [BuildString\_Int](ue_ue.KismetStringLibrary.md#buildstring_int)
- [BuildString\_IntVector](ue_ue.KismetStringLibrary.md#buildstring_intvector)
- [BuildString\_Name](ue_ue.KismetStringLibrary.md#buildstring_name)
- [BuildString\_Object](ue_ue.KismetStringLibrary.md#buildstring_object)
- [BuildString\_Rotator](ue_ue.KismetStringLibrary.md#buildstring_rotator)
- [BuildString\_Vector](ue_ue.KismetStringLibrary.md#buildstring_vector)
- [BuildString\_Vector2d](ue_ue.KismetStringLibrary.md#buildstring_vector2d)
- [Concat\_StrStr](ue_ue.KismetStringLibrary.md#concat_strstr)
- [Contains](ue_ue.KismetStringLibrary.md#contains)
- [Conv\_BoolToString](ue_ue.KismetStringLibrary.md#conv_booltostring)
- [Conv\_ByteToString](ue_ue.KismetStringLibrary.md#conv_bytetostring)
- [Conv\_ColorToString](ue_ue.KismetStringLibrary.md#conv_colortostring)
- [Conv\_FloatToString](ue_ue.KismetStringLibrary.md#conv_floattostring)
- [Conv\_IntToString](ue_ue.KismetStringLibrary.md#conv_inttostring)
- [Conv\_IntVectorToString](ue_ue.KismetStringLibrary.md#conv_intvectortostring)
- [Conv\_MatrixToString](ue_ue.KismetStringLibrary.md#conv_matrixtostring)
- [Conv\_NameToString](ue_ue.KismetStringLibrary.md#conv_nametostring)
- [Conv\_ObjectToString](ue_ue.KismetStringLibrary.md#conv_objecttostring)
- [Conv\_RotatorToString](ue_ue.KismetStringLibrary.md#conv_rotatortostring)
- [Conv\_StringToColor](ue_ue.KismetStringLibrary.md#conv_stringtocolor)
- [Conv\_StringToFloat](ue_ue.KismetStringLibrary.md#conv_stringtofloat)
- [Conv\_StringToInt](ue_ue.KismetStringLibrary.md#conv_stringtoint)
- [Conv\_StringToName](ue_ue.KismetStringLibrary.md#conv_stringtoname)
- [Conv\_StringToRotator](ue_ue.KismetStringLibrary.md#conv_stringtorotator)
- [Conv\_StringToVector](ue_ue.KismetStringLibrary.md#conv_stringtovector)
- [Conv\_StringToVector2D](ue_ue.KismetStringLibrary.md#conv_stringtovector2d)
- [Conv\_TransformToString](ue_ue.KismetStringLibrary.md#conv_transformtostring)
- [Conv\_Vector2dToString](ue_ue.KismetStringLibrary.md#conv_vector2dtostring)
- [Conv\_VectorToString](ue_ue.KismetStringLibrary.md#conv_vectortostring)
- [CullArray](ue_ue.KismetStringLibrary.md#cullarray)
- [EndsWith](ue_ue.KismetStringLibrary.md#endswith)
- [EqualEqual\_StrStr](ue_ue.KismetStringLibrary.md#equalequal_strstr)
- [EqualEqual\_StriStri](ue_ue.KismetStringLibrary.md#equalequal_stristri)
- [Find](ue_ue.KismetStringLibrary.md#find)
- [FindSubstring](ue_ue.KismetStringLibrary.md#findsubstring)
- [GetCharacterArrayFromString](ue_ue.KismetStringLibrary.md#getcharacterarrayfromstring)
- [GetCharacterAsNumber](ue_ue.KismetStringLibrary.md#getcharacterasnumber)
- [GetSubstring](ue_ue.KismetStringLibrary.md#getsubstring)
- [IsNumeric](ue_ue.KismetStringLibrary.md#isnumeric)
- [JoinStringArray](ue_ue.KismetStringLibrary.md#joinstringarray)
- [Left](ue_ue.KismetStringLibrary.md#left)
- [LeftChop](ue_ue.KismetStringLibrary.md#leftchop)
- [LeftPad](ue_ue.KismetStringLibrary.md#leftpad)
- [Len](ue_ue.KismetStringLibrary.md#len)
- [Load](ue_ue.KismetStringLibrary.md#load)
- [MatchesWildcard](ue_ue.KismetStringLibrary.md#matcheswildcard)
- [Mid](ue_ue.KismetStringLibrary.md#mid)
- [NotEqual\_StrStr](ue_ue.KismetStringLibrary.md#notequal_strstr)
- [NotEqual\_StriStri](ue_ue.KismetStringLibrary.md#notequal_stristri)
- [ParseIntoArray](ue_ue.KismetStringLibrary.md#parseintoarray)
- [Replace](ue_ue.KismetStringLibrary.md#replace)
- [ReplaceInline](ue_ue.KismetStringLibrary.md#replaceinline)
- [Reverse](ue_ue.KismetStringLibrary.md#reverse)
- [Right](ue_ue.KismetStringLibrary.md#right)
- [RightChop](ue_ue.KismetStringLibrary.md#rightchop)
- [RightPad](ue_ue.KismetStringLibrary.md#rightpad)
- [Split](ue_ue.KismetStringLibrary.md#split)
- [StartsWith](ue_ue.KismetStringLibrary.md#startswith)
- [StaticClass](ue_ue.KismetStringLibrary.md#staticclass)
- [TimeSecondsToString](ue_ue.KismetStringLibrary.md#timesecondstostring)
- [ToLower](ue_ue.KismetStringLibrary.md#tolower)
- [ToUpper](ue_ue.KismetStringLibrary.md#toupper)
- [Trim](ue_ue.KismetStringLibrary.md#trim)
- [TrimTrailing](ue_ue.KismetStringLibrary.md#trimtrailing)

## Constructors

### constructor

• **new KismetStringLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:43110](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43110)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13418)

___

### \_\_tid\_KismetStringLibrary\_\_

• **\_\_tid\_KismetStringLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:43179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43179)

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

### BuildString\_Bool

▸ `Static` **BuildString_Bool**(`AppendTo`, `Prefix`, `InBool`, `Suffix`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AppendTo` | `string` |
| `Prefix` | `string` |
| `InBool` | `boolean` |
| `Suffix` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43111](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43111)

___

### BuildString\_Color

▸ `Static` **BuildString_Color**(`AppendTo`, `Prefix`, `InColor`, `Suffix`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AppendTo` | `string` |
| `Prefix` | `string` |
| `InColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `Suffix` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43112](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43112)

___

### BuildString\_Float

▸ `Static` **BuildString_Float**(`AppendTo`, `Prefix`, `InFloat`, `Suffix`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AppendTo` | `string` |
| `Prefix` | `string` |
| `InFloat` | `number` |
| `Suffix` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43113](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43113)

___

### BuildString\_Int

▸ `Static` **BuildString_Int**(`AppendTo`, `Prefix`, `InInt`, `Suffix`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AppendTo` | `string` |
| `Prefix` | `string` |
| `InInt` | `number` |
| `Suffix` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43114](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43114)

___

### BuildString\_IntVector

▸ `Static` **BuildString_IntVector**(`AppendTo`, `Prefix`, `InIntVector`, `Suffix`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AppendTo` | `string` |
| `Prefix` | `string` |
| `InIntVector` | [`IntVector`](ue_ue_s.IntVector.md) |
| `Suffix` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43115](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43115)

___

### BuildString\_Name

▸ `Static` **BuildString_Name**(`AppendTo`, `Prefix`, `InName`, `Suffix`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AppendTo` | `string` |
| `Prefix` | `string` |
| `InName` | `string` |
| `Suffix` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43116](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43116)

___

### BuildString\_Object

▸ `Static` **BuildString_Object**(`AppendTo`, `Prefix`, `InObj`, `Suffix`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AppendTo` | `string` |
| `Prefix` | `string` |
| `InObj` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Suffix` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43117](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43117)

___

### BuildString\_Rotator

▸ `Static` **BuildString_Rotator**(`AppendTo`, `Prefix`, `InRot`, `Suffix`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AppendTo` | `string` |
| `Prefix` | `string` |
| `InRot` | [`Rotator`](ue_ue_s.Rotator.md) |
| `Suffix` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43118](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43118)

___

### BuildString\_Vector

▸ `Static` **BuildString_Vector**(`AppendTo`, `Prefix`, `InVector`, `Suffix`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AppendTo` | `string` |
| `Prefix` | `string` |
| `InVector` | [`Vector`](ue_ue_s.Vector.md) |
| `Suffix` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43119](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43119)

___

### BuildString\_Vector2d

▸ `Static` **BuildString_Vector2d**(`AppendTo`, `Prefix`, `InVector2d`, `Suffix`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AppendTo` | `string` |
| `Prefix` | `string` |
| `InVector2d` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Suffix` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43120](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43120)

___

### Concat\_StrStr

▸ `Static` **Concat_StrStr**(`A`, `B`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `string` |
| `B` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43121](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43121)

___

### Contains

▸ `Static` **Contains**(`SearchIn`, `Substring`, `bUseCase?`, `bSearchFromEnd?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SearchIn` | `string` |
| `Substring` | `string` |
| `bUseCase?` | `boolean` |
| `bSearchFromEnd?` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43122](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43122)

___

### Conv\_BoolToString

▸ `Static` **Conv_BoolToString**(`InBool`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBool` | `boolean` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43123](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43123)

___

### Conv\_ByteToString

▸ `Static` **Conv_ByteToString**(`InByte`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InByte` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43124](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43124)

___

### Conv\_ColorToString

▸ `Static` **Conv_ColorToString**(`InColor`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43125](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43125)

___

### Conv\_FloatToString

▸ `Static` **Conv_FloatToString**(`InFloat`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFloat` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43126](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43126)

___

### Conv\_IntToString

▸ `Static` **Conv_IntToString**(`InInt`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InInt` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43127](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43127)

___

### Conv\_IntVectorToString

▸ `Static` **Conv_IntVectorToString**(`InIntVec`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InIntVec` | [`IntVector`](ue_ue_s.IntVector.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43128](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43128)

___

### Conv\_MatrixToString

▸ `Static` **Conv_MatrixToString**(`InMatrix`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMatrix` | [`Matrix`](ue_ue.Matrix.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43129](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43129)

___

### Conv\_NameToString

▸ `Static` **Conv_NameToString**(`InName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43130](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43130)

___

### Conv\_ObjectToString

▸ `Static` **Conv_ObjectToString**(`InObj`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InObj` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43131)

___

### Conv\_RotatorToString

▸ `Static` **Conv_RotatorToString**(`InRot`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRot` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43132](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43132)

___

### Conv\_StringToColor

▸ `Static` **Conv_StringToColor**(`InString`, `OutConvertedColor`, `OutIsValid`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InString` | `string` |
| `OutConvertedColor` | [`$Ref`](../interfaces/puerts._Ref.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\> |
| `OutIsValid` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43133)

___

### Conv\_StringToFloat

▸ `Static` **Conv_StringToFloat**(`InString`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InString` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:43134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43134)

___

### Conv\_StringToInt

▸ `Static` **Conv_StringToInt**(`InString`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InString` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:43135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43135)

___

### Conv\_StringToName

▸ `Static` **Conv_StringToName**(`InString`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InString` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43136)

___

### Conv\_StringToRotator

▸ `Static` **Conv_StringToRotator**(`InString`, `OutConvertedRotator`, `OutIsValid`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InString` | `string` |
| `OutConvertedRotator` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |
| `OutIsValid` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43137)

___

### Conv\_StringToVector

▸ `Static` **Conv_StringToVector**(`InString`, `OutConvertedVector`, `OutIsValid`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InString` | `string` |
| `OutConvertedVector` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `OutIsValid` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43138)

___

### Conv\_StringToVector2D

▸ `Static` **Conv_StringToVector2D**(`InString`, `OutConvertedVector2D`, `OutIsValid`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InString` | `string` |
| `OutConvertedVector2D` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |
| `OutIsValid` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43139)

___

### Conv\_TransformToString

▸ `Static` **Conv_TransformToString**(`InTrans`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTrans` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43140)

___

### Conv\_Vector2dToString

▸ `Static` **Conv_Vector2dToString**(`InVec`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVec` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43141)

___

### Conv\_VectorToString

▸ `Static` **Conv_VectorToString**(`InVec`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVec` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43142)

___

### CullArray

▸ `Static` **CullArray**(`SourceString`, `InArray`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `InArray` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:43143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43143)

___

### EndsWith

▸ `Static` **EndsWith**(`SourceString`, `InSuffix`, `SearchCase?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `InSuffix` | `string` |
| `SearchCase?` | [`ESearchCase`](../enums/ue_ue.ESearchCase.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43144)

___

### EqualEqual\_StrStr

▸ `Static` **EqualEqual_StrStr**(`A`, `B`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `string` |
| `B` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43146](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43146)

___

### EqualEqual\_StriStri

▸ `Static` **EqualEqual_StriStri**(`A`, `B`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `string` |
| `B` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43145)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`KismetStringLibrary`](ue_ue.KismetStringLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`KismetStringLibrary`](ue_ue.KismetStringLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:43176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43176)

___

### FindSubstring

▸ `Static` **FindSubstring**(`SearchIn`, `Substring`, `bUseCase?`, `bSearchFromEnd?`, `StartPosition?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SearchIn` | `string` |
| `Substring` | `string` |
| `bUseCase?` | `boolean` |
| `bSearchFromEnd?` | `boolean` |
| `StartPosition?` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:43147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43147)

___

### GetCharacterArrayFromString

▸ `Static` **GetCharacterArrayFromString**(`SourceString`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:43148](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43148)

___

### GetCharacterAsNumber

▸ `Static` **GetCharacterAsNumber**(`SourceString`, `Index?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `Index?` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:43149](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43149)

___

### GetSubstring

▸ `Static` **GetSubstring**(`SourceString`, `StartIndex?`, `Length?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `StartIndex?` | `number` |
| `Length?` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43150](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43150)

___

### IsNumeric

▸ `Static` **IsNumeric**(`SourceString`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43151](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43151)

___

### JoinStringArray

▸ `Static` **JoinStringArray**(`SourceArray`, `Separator?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `Separator?` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43152](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43152)

___

### Left

▸ `Static` **Left**(`SourceString`, `Count`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `Count` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43153)

___

### LeftChop

▸ `Static` **LeftChop**(`SourceString`, `Count`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `Count` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43154](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43154)

___

### LeftPad

▸ `Static` **LeftPad**(`SourceString`, `ChCount`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `ChCount` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43155](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43155)

___

### Len

▸ `Static` **Len**(`S`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `S` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:43156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43156)

___

### Load

▸ `Static` **Load**(`InName`): [`KismetStringLibrary`](ue_ue.KismetStringLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`KismetStringLibrary`](ue_ue.KismetStringLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:43177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43177)

___

### MatchesWildcard

▸ `Static` **MatchesWildcard**(`SourceString`, `Wildcard`, `SearchCase?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `Wildcard` | `string` |
| `SearchCase?` | [`ESearchCase`](../enums/ue_ue.ESearchCase.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43157)

___

### Mid

▸ `Static` **Mid**(`SourceString`, `Start`, `Count`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `Start` | `number` |
| `Count` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43158)

___

### NotEqual\_StrStr

▸ `Static` **NotEqual_StrStr**(`A`, `B`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `string` |
| `B` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43160)

___

### NotEqual\_StriStri

▸ `Static` **NotEqual_StriStri**(`A`, `B`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `string` |
| `B` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43159)

___

### ParseIntoArray

▸ `Static` **ParseIntoArray**(`SourceString`, `Delimiter?`, `CullEmptyStrings?`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `Delimiter?` | `string` |
| `CullEmptyStrings?` | `boolean` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:43161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43161)

___

### Replace

▸ `Static` **Replace**(`SourceString`, `From`, `To`, `SearchCase?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `From` | `string` |
| `To` | `string` |
| `SearchCase?` | [`ESearchCase`](../enums/ue_ue.ESearchCase.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43162)

___

### ReplaceInline

▸ `Static` **ReplaceInline**(`SourceString`, `SearchText`, `ReplacementText`, `SearchCase?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `SearchText` | `string` |
| `ReplacementText` | `string` |
| `SearchCase?` | [`ESearchCase`](../enums/ue_ue.ESearchCase.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:43163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43163)

___

### Reverse

▸ `Static` **Reverse**(`SourceString`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43164)

___

### Right

▸ `Static` **Right**(`SourceString`, `Count`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `Count` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43165)

___

### RightChop

▸ `Static` **RightChop**(`SourceString`, `Count`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `Count` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43166)

___

### RightPad

▸ `Static` **RightPad**(`SourceString`, `ChCount`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `ChCount` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43167)

___

### Split

▸ `Static` **Split**(`SourceString`, `InStr`, `LeftS`, `RightS`, `SearchCase?`, `SearchDir?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `InStr` | `string` |
| `LeftS` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `RightS` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `SearchCase?` | [`ESearchCase`](../enums/ue_ue.ESearchCase.md) |
| `SearchDir?` | [`ESearchDir`](../enums/ue_ue.ESearchDir.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43168)

___

### StartsWith

▸ `Static` **StartsWith**(`SourceString`, `InPrefix`, `SearchCase?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |
| `InPrefix` | `string` |
| `SearchCase?` | [`ESearchCase`](../enums/ue_ue.ESearchCase.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:43169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43169)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:43175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43175)

___

### TimeSecondsToString

▸ `Static` **TimeSecondsToString**(`InSeconds`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSeconds` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43170)

___

### ToLower

▸ `Static` **ToLower**(`SourceString`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43171)

___

### ToUpper

▸ `Static` **ToUpper**(`SourceString`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43172)

___

### Trim

▸ `Static` **Trim**(`SourceString`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43173)

___

### TrimTrailing

▸ `Static` **TrimTrailing**(`SourceString`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:43174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43174)
