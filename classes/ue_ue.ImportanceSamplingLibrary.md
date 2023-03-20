[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ImportanceSamplingLibrary

# Class: ImportanceSamplingLibrary

[ue/ue](../modules/ue_ue.md).ImportanceSamplingLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`ImportanceSamplingLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.ImportanceSamplingLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.ImportanceSamplingLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_ImportanceSamplingLibrary\_\_](ue_ue.ImportanceSamplingLibrary.md#__tid_importancesamplinglibrary__)
- [\_\_tid\_Object\_\_](ue_ue.ImportanceSamplingLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ImportanceSamplingLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ImportanceSamplingLibrary.md#executeubergraph)
- [GetClass](ue_ue.ImportanceSamplingLibrary.md#getclass)
- [GetName](ue_ue.ImportanceSamplingLibrary.md#getname)
- [GetOuter](ue_ue.ImportanceSamplingLibrary.md#getouter)
- [GetWorld](ue_ue.ImportanceSamplingLibrary.md#getworld)
- [BreakImportanceTexture](ue_ue.ImportanceSamplingLibrary.md#breakimportancetexture)
- [Find](ue_ue.ImportanceSamplingLibrary.md#find)
- [ImportanceSample](ue_ue.ImportanceSamplingLibrary.md#importancesample)
- [Load](ue_ue.ImportanceSamplingLibrary.md#load)
- [MakeImportanceTexture](ue_ue.ImportanceSamplingLibrary.md#makeimportancetexture)
- [NextSobolCell2D](ue_ue.ImportanceSamplingLibrary.md#nextsobolcell2d)
- [NextSobolCell3D](ue_ue.ImportanceSamplingLibrary.md#nextsobolcell3d)
- [NextSobolFloat](ue_ue.ImportanceSamplingLibrary.md#nextsobolfloat)
- [RandomSobolCell2D](ue_ue.ImportanceSamplingLibrary.md#randomsobolcell2d)
- [RandomSobolCell3D](ue_ue.ImportanceSamplingLibrary.md#randomsobolcell3d)
- [RandomSobolFloat](ue_ue.ImportanceSamplingLibrary.md#randomsobolfloat)
- [StaticClass](ue_ue.ImportanceSamplingLibrary.md#staticclass)

## Constructors

### constructor

• **new ImportanceSamplingLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_ImportanceSamplingLibrary\_\_

• **\_\_tid\_ImportanceSamplingLibrary\_\_**: `boolean`

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

### BreakImportanceTexture

▸ `Static` **BreakImportanceTexture**(`ImportanceTexture`, `Texture`, `WeightingFunc`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImportanceTexture` | [`ImportanceTexture`](ue_ue.ImportanceTexture.md) |
| `Texture` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Texture2D`](ue_ue.Texture2D.md)\> |
| `WeightingFunc` | [`$Ref`](../interfaces/puerts._Ref.md)<[`EImportanceWeight`](../enums/ue_ue.EImportanceWeight.md)\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ImportanceSamplingLibrary`](ue_ue.ImportanceSamplingLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ImportanceSamplingLibrary`](ue_ue.ImportanceSamplingLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### ImportanceSample

▸ `Static` **ImportanceSample**(`Texture`, `Rand`, `Samples`, `Intensity`, `SamplePosition`, `SampleColor`, `SampleIntensity`, `SampleSize`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Texture` | [`ImportanceTexture`](ue_ue.ImportanceTexture.md) |
| `Rand` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Samples` | `number` |
| `Intensity` | `number` |
| `SamplePosition` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |
| `SampleColor` | [`$Ref`](../interfaces/puerts._Ref.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\> |
| `SampleIntensity` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `SampleSize` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### Load

▸ `Static` **Load**(`InName`): [`ImportanceSamplingLibrary`](ue_ue.ImportanceSamplingLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ImportanceSamplingLibrary`](ue_ue.ImportanceSamplingLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### MakeImportanceTexture

▸ `Static` **MakeImportanceTexture**(`Texture`, `WeightingFunc`): [`ImportanceTexture`](ue_ue.ImportanceTexture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Texture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture2D`](ue_ue.Texture2D.md)\> |
| `WeightingFunc` | [`EImportanceWeight`](../enums/ue_ue.EImportanceWeight.md) |

#### Returns

[`ImportanceTexture`](ue_ue.ImportanceTexture.md)

___

### NextSobolCell2D

▸ `Static` **NextSobolCell2D**(`Index`, `NumCells?`, `PreviousValue?`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |
| `NumCells?` | `number` |
| `PreviousValue?` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### NextSobolCell3D

▸ `Static` **NextSobolCell3D**(`Index`, `NumCells?`, `PreviousValue?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |
| `NumCells?` | `number` |
| `PreviousValue?` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### NextSobolFloat

▸ `Static` **NextSobolFloat**(`Index`, `Dimension`, `PreviousValue`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |
| `Dimension` | `number` |
| `PreviousValue` | `number` |

#### Returns

`number`

___

### RandomSobolCell2D

▸ `Static` **RandomSobolCell2D**(`Index`, `NumCells?`, `Cell?`, `Seed?`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |
| `NumCells?` | `number` |
| `Cell?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Seed?` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### RandomSobolCell3D

▸ `Static` **RandomSobolCell3D**(`Index`, `NumCells?`, `Cell?`, `Seed?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |
| `NumCells?` | `number` |
| `Cell?` | [`Vector`](ue_ue_s.Vector.md) |
| `Seed?` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### RandomSobolFloat

▸ `Static` **RandomSobolFloat**(`Index`, `Dimension`, `Seed`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |
| `Dimension` | `number` |
| `Seed` | `number` |

#### Returns

`number`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
