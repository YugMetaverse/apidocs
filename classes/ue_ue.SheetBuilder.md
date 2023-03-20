[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SheetBuilder

# Class: SheetBuilder

[ue/ue](../modules/ue_ue.md).SheetBuilder

## Hierarchy

- [`EditorBrushBuilder`](ue_ue.EditorBrushBuilder.md)

  ↳ **`SheetBuilder`**

## Table of contents

### Constructors

- [constructor](ue_ue.SheetBuilder.md#constructor)

### Properties

- [Axis](ue_ue.SheetBuilder.md#axis)
- [BitmapFilename](ue_ue.SheetBuilder.md#bitmapfilename)
- [GroupName](ue_ue.SheetBuilder.md#groupname)
- [Layer](ue_ue.SheetBuilder.md#layer)
- [MergeCoplanars](ue_ue.SheetBuilder.md#mergecoplanars)
- [NotifyBadParams](ue_ue.SheetBuilder.md#notifybadparams)
- [Polys](ue_ue.SheetBuilder.md#polys)
- [ToolTip](ue_ue.SheetBuilder.md#tooltip)
- [Vertices](ue_ue.SheetBuilder.md#vertices)
- [X](ue_ue.SheetBuilder.md#x)
- [XSegments](ue_ue.SheetBuilder.md#xsegments)
- [Y](ue_ue.SheetBuilder.md#y)
- [YSegments](ue_ue.SheetBuilder.md#ysegments)
- [\_\_tid\_BrushBuilder\_\_](ue_ue.SheetBuilder.md#__tid_brushbuilder__)
- [\_\_tid\_EditorBrushBuilder\_\_](ue_ue.SheetBuilder.md#__tid_editorbrushbuilder__)
- [\_\_tid\_Object\_\_](ue_ue.SheetBuilder.md#__tid_object__)
- [\_\_tid\_SheetBuilder\_\_](ue_ue.SheetBuilder.md#__tid_sheetbuilder__)

### Methods

- [CreateDefaultSubobject](ue_ue.SheetBuilder.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SheetBuilder.md#executeubergraph)
- [GetClass](ue_ue.SheetBuilder.md#getclass)
- [GetName](ue_ue.SheetBuilder.md#getname)
- [GetOuter](ue_ue.SheetBuilder.md#getouter)
- [GetWorld](ue_ue.SheetBuilder.md#getworld)
- [Find](ue_ue.SheetBuilder.md#find)
- [Load](ue_ue.SheetBuilder.md#load)
- [StaticClass](ue_ue.SheetBuilder.md#staticclass)

## Constructors

### constructor

• **new SheetBuilder**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[constructor](ue_ue.EditorBrushBuilder.md#constructor)

#### Defined in

[ue/ue.d.ts:60357](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60357)

## Properties

### Axis

• **Axis**: [`ESheetAxis`](../enums/ue_ue.ESheetAxis.md)

#### Defined in

[ue/ue.d.ts:60362](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60362)

___

### BitmapFilename

• **BitmapFilename**: `string`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[BitmapFilename](ue_ue.EditorBrushBuilder.md#bitmapfilename)

#### Defined in

[ue/ue.d.ts:12793](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12793)

___

### GroupName

• **GroupName**: `string`

#### Defined in

[ue/ue.d.ts:60363](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60363)

___

### Layer

• **Layer**: `string`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Layer](ue_ue.EditorBrushBuilder.md#layer)

#### Defined in

[ue/ue.d.ts:12798](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12798)

___

### MergeCoplanars

• **MergeCoplanars**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[MergeCoplanars](ue_ue.EditorBrushBuilder.md#mergecoplanars)

#### Defined in

[ue/ue.d.ts:12799](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12799)

___

### NotifyBadParams

• **NotifyBadParams**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[NotifyBadParams](ue_ue.EditorBrushBuilder.md#notifybadparams)

#### Defined in

[ue/ue.d.ts:12795](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12795)

___

### Polys

• **Polys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BuilderPoly`](ue_ue.BuilderPoly.md)\>

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Polys](ue_ue.EditorBrushBuilder.md#polys)

#### Defined in

[ue/ue.d.ts:12797](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12797)

___

### ToolTip

• **ToolTip**: `string`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[ToolTip](ue_ue.EditorBrushBuilder.md#tooltip)

#### Defined in

[ue/ue.d.ts:12794](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12794)

___

### Vertices

• **Vertices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Vertices](ue_ue.EditorBrushBuilder.md#vertices)

#### Defined in

[ue/ue.d.ts:12796](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12796)

___

### X

• **X**: `number`

#### Defined in

[ue/ue.d.ts:60358](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60358)

___

### XSegments

• **XSegments**: `number`

#### Defined in

[ue/ue.d.ts:60360](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60360)

___

### Y

• **Y**: `number`

#### Defined in

[ue/ue.d.ts:60359](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60359)

___

### YSegments

• **YSegments**: `number`

#### Defined in

[ue/ue.d.ts:60361](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60361)

___

### \_\_tid\_BrushBuilder\_\_

• **\_\_tid\_BrushBuilder\_\_**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[__tid_BrushBuilder__](ue_ue.EditorBrushBuilder.md#__tid_brushbuilder__)

#### Defined in

[ue/ue.d.ts:12804](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12804)

___

### \_\_tid\_EditorBrushBuilder\_\_

• **\_\_tid\_EditorBrushBuilder\_\_**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[__tid_EditorBrushBuilder__](ue_ue.EditorBrushBuilder.md#__tid_editorbrushbuilder__)

#### Defined in

[ue/ue.d.ts:28545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28545)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[__tid_Object__](ue_ue.EditorBrushBuilder.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SheetBuilder\_\_

• **\_\_tid\_SheetBuilder\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:60368](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60368)

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

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[CreateDefaultSubobject](ue_ue.EditorBrushBuilder.md#createdefaultsubobject)

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

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[ExecuteUbergraph](ue_ue.EditorBrushBuilder.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[GetClass](ue_ue.EditorBrushBuilder.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[GetName](ue_ue.EditorBrushBuilder.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[GetOuter](ue_ue.EditorBrushBuilder.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[GetWorld](ue_ue.EditorBrushBuilder.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SheetBuilder`](ue_ue.SheetBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SheetBuilder`](ue_ue.SheetBuilder.md)

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Find](ue_ue.EditorBrushBuilder.md#find)

#### Defined in

[ue/ue.d.ts:60365](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60365)

___

### Load

▸ `Static` **Load**(`InName`): [`SheetBuilder`](ue_ue.SheetBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SheetBuilder`](ue_ue.SheetBuilder.md)

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Load](ue_ue.EditorBrushBuilder.md#load)

#### Defined in

[ue/ue.d.ts:60366](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60366)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[StaticClass](ue_ue.EditorBrushBuilder.md#staticclass)

#### Defined in

[ue/ue.d.ts:60364](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60364)
