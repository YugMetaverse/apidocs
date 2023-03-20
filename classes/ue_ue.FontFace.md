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

#### Defined in

[ue/ue.d.ts:36080](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36080)

## Properties

### FontFaceData

• **FontFaceData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:36085](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36085)

___

### Hinting

• **Hinting**: [`EFontHinting`](../enums/ue_ue.EFontHinting.md)

#### Defined in

[ue/ue.d.ts:36082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36082)

___

### LayoutMethod

• **LayoutMethod**: [`EFontLayoutMethod`](../enums/ue_ue.EFontLayoutMethod.md)

#### Defined in

[ue/ue.d.ts:36084](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36084)

___

### LoadingPolicy

• **LoadingPolicy**: [`EFontLoadingPolicy`](../enums/ue_ue.EFontLoadingPolicy.md)

#### Defined in

[ue/ue.d.ts:36083](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36083)

___

### SourceFilename

• **SourceFilename**: `string`

#### Defined in

[ue/ue.d.ts:36081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36081)

___

### SubFaces

• **SubFaces**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:36086](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36086)

___

### \_\_tid\_FontFace\_\_

• **\_\_tid\_FontFace\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:36091](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36091)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:36088](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36088)

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

#### Defined in

[ue/ue.d.ts:36089](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36089)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:36087](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36087)
