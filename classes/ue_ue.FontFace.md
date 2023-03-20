[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FontFace

# Class: FontFace

[ue/ue](../modules/ue_ue.md).FontFace

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`FontFace`**

## Table of contents

### Constructors

- [constructor](ue_ue.FontFace.md#constructor)

### Properties

- [FontFaceData](ue_ue.FontFace.md#fontfacedata)
- [Hinting](ue_ue.FontFace.md#hinting)
- [LayoutMethod](ue_ue.FontFace.md#layoutmethod)
- [LoadingPolicy](ue_ue.FontFace.md#loadingpolicy)
- [SourceFilename](ue_ue.FontFace.md#sourcefilename)
- [SubFaces](ue_ue.FontFace.md#subfaces)
- [\_\_tid\_FontFace\_\_](ue_ue.FontFace.md#__tid_fontface__)
- [\_\_tid\_Object\_\_](ue_ue.FontFace.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.FontFace.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FontFace.md#executeubergraph)
- [GetClass](ue_ue.FontFace.md#getclass)
- [GetName](ue_ue.FontFace.md#getname)
- [GetOuter](ue_ue.FontFace.md#getouter)
- [GetWorld](ue_ue.FontFace.md#getworld)
- [Find](ue_ue.FontFace.md#find)
- [Load](ue_ue.FontFace.md#load)
- [StaticClass](ue_ue.FontFace.md#staticclass)

## Constructors

### constructor

• **new FontFace**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### FontFaceData

• **FontFaceData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### Hinting

• **Hinting**: [`EFontHinting`](../enums/ue_ue.EFontHinting.md)

___

### LayoutMethod

• **LayoutMethod**: [`EFontLayoutMethod`](../enums/ue_ue.EFontLayoutMethod.md)

___

### LoadingPolicy

• **LoadingPolicy**: [`EFontLoadingPolicy`](../enums/ue_ue.EFontLoadingPolicy.md)

___

### SourceFilename

• **SourceFilename**: `string`

___

### SubFaces

• **SubFaces**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### \_\_tid\_FontFace\_\_

• **\_\_tid\_FontFace\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FontFace`](ue_ue.FontFace.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FontFace`](ue_ue.FontFace.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FontFace`](ue_ue.FontFace.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FontFace`](ue_ue.FontFace.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
