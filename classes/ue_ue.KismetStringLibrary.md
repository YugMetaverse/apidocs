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

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_KismetStringLibrary\_\_

• **\_\_tid\_KismetStringLibrary\_\_**: `boolean`

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

___

### Conv\_BoolToString

▸ `Static` **Conv_BoolToString**(`InBool`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBool` | `boolean` |

#### Returns

`string`

___

### Conv\_ByteToString

▸ `Static` **Conv_ByteToString**(`InByte`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InByte` | `number` |

#### Returns

`string`

___

### Conv\_ColorToString

▸ `Static` **Conv_ColorToString**(`InColor`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`string`

___

### Conv\_FloatToString

▸ `Static` **Conv_FloatToString**(`InFloat`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFloat` | `number` |

#### Returns

`string`

___

### Conv\_IntToString

▸ `Static` **Conv_IntToString**(`InInt`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InInt` | `number` |

#### Returns

`string`

___

### Conv\_IntVectorToString

▸ `Static` **Conv_IntVectorToString**(`InIntVec`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InIntVec` | [`IntVector`](ue_ue_s.IntVector.md) |

#### Returns

`string`

___

### Conv\_MatrixToString

▸ `Static` **Conv_MatrixToString**(`InMatrix`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMatrix` | [`Matrix`](ue_ue.Matrix.md) |

#### Returns

`string`

___

### Conv\_NameToString

▸ `Static` **Conv_NameToString**(`InName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

`string`

___

### Conv\_ObjectToString

▸ `Static` **Conv_ObjectToString**(`InObj`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InObj` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`string`

___

### Conv\_RotatorToString

▸ `Static` **Conv_RotatorToString**(`InRot`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRot` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`string`

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

___

### Conv\_StringToFloat

▸ `Static` **Conv_StringToFloat**(`InString`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InString` | `string` |

#### Returns

`number`

___

### Conv\_StringToInt

▸ `Static` **Conv_StringToInt**(`InString`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InString` | `string` |

#### Returns

`number`

___

### Conv\_StringToName

▸ `Static` **Conv_StringToName**(`InString`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InString` | `string` |

#### Returns

`string`

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

___

### Conv\_TransformToString

▸ `Static` **Conv_TransformToString**(`InTrans`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTrans` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`string`

___

### Conv\_Vector2dToString

▸ `Static` **Conv_Vector2dToString**(`InVec`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVec` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`string`

___

### Conv\_VectorToString

▸ `Static` **Conv_VectorToString**(`InVec`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVec` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`string`

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

___

### GetCharacterArrayFromString

▸ `Static` **GetCharacterArrayFromString**(`SourceString`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

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

___

### IsNumeric

▸ `Static` **IsNumeric**(`SourceString`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

`boolean`

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

___

### Len

▸ `Static` **Len**(`S`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `S` | `string` |

#### Returns

`number`

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

___

### Reverse

▸ `Static` **Reverse**(`SourceString`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

`string`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

___

### TimeSecondsToString

▸ `Static` **TimeSecondsToString**(`InSeconds`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSeconds` | `number` |

#### Returns

`string`

___

### ToLower

▸ `Static` **ToLower**(`SourceString`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

`string`

___

### ToUpper

▸ `Static` **ToUpper**(`SourceString`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

`string`

___

### Trim

▸ `Static` **Trim**(`SourceString`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

`string`

___

### TrimTrailing

▸ `Static` **TrimTrailing**(`SourceString`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceString` | `string` |

#### Returns

`string`
