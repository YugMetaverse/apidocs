[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ConeBuilder

# Class: ConeBuilder

[ue/ue](../modules/ue_ue.md).ConeBuilder

## Hierarchy

- [`EditorBrushBuilder`](ue_ue.EditorBrushBuilder.md)

  ↳ **`ConeBuilder`**

## Table of contents

### Constructors

- [constructor](ue_ue.ConeBuilder.md#constructor)

### Properties

- [AlignToSide](ue_ue.ConeBuilder.md#aligntoside)
- [BitmapFilename](ue_ue.ConeBuilder.md#bitmapfilename)
- [CapZ](ue_ue.ConeBuilder.md#capz)
- [GroupName](ue_ue.ConeBuilder.md#groupname)
- [Hollow](ue_ue.ConeBuilder.md#hollow)
- [InnerRadius](ue_ue.ConeBuilder.md#innerradius)
- [Layer](ue_ue.ConeBuilder.md#layer)
- [MergeCoplanars](ue_ue.ConeBuilder.md#mergecoplanars)
- [NotifyBadParams](ue_ue.ConeBuilder.md#notifybadparams)
- [OuterRadius](ue_ue.ConeBuilder.md#outerradius)
- [Polys](ue_ue.ConeBuilder.md#polys)
- [Sides](ue_ue.ConeBuilder.md#sides)
- [ToolTip](ue_ue.ConeBuilder.md#tooltip)
- [Vertices](ue_ue.ConeBuilder.md#vertices)
- [Z](ue_ue.ConeBuilder.md#z)
- [\_\_tid\_BrushBuilder\_\_](ue_ue.ConeBuilder.md#__tid_brushbuilder__)
- [\_\_tid\_ConeBuilder\_\_](ue_ue.ConeBuilder.md#__tid_conebuilder__)
- [\_\_tid\_EditorBrushBuilder\_\_](ue_ue.ConeBuilder.md#__tid_editorbrushbuilder__)
- [\_\_tid\_Object\_\_](ue_ue.ConeBuilder.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ConeBuilder.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ConeBuilder.md#executeubergraph)
- [GetClass](ue_ue.ConeBuilder.md#getclass)
- [GetName](ue_ue.ConeBuilder.md#getname)
- [GetOuter](ue_ue.ConeBuilder.md#getouter)
- [GetWorld](ue_ue.ConeBuilder.md#getworld)
- [Find](ue_ue.ConeBuilder.md#find)
- [Load](ue_ue.ConeBuilder.md#load)
- [StaticClass](ue_ue.ConeBuilder.md#staticclass)

## Constructors

### constructor

• **new ConeBuilder**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[constructor](ue_ue.EditorBrushBuilder.md#constructor)

#### Defined in

[ue/ue.d.ts:28549](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28549)

## Properties

### AlignToSide

• **AlignToSide**: `boolean`

#### Defined in

[ue/ue.d.ts:28556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28556)

___

### BitmapFilename

• **BitmapFilename**: `string`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[BitmapFilename](ue_ue.EditorBrushBuilder.md#bitmapfilename)

#### Defined in

[ue/ue.d.ts:12793](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12793)

___

### CapZ

• **CapZ**: `number`

#### Defined in

[ue/ue.d.ts:28551](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28551)

___

### GroupName

• **GroupName**: `string`

#### Defined in

[ue/ue.d.ts:28555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28555)

___

### Hollow

• **Hollow**: `boolean`

#### Defined in

[ue/ue.d.ts:28557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28557)

___

### InnerRadius

• **InnerRadius**: `number`

#### Defined in

[ue/ue.d.ts:28553](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28553)

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

### OuterRadius

• **OuterRadius**: `number`

#### Defined in

[ue/ue.d.ts:28552](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28552)

___

### Polys

• **Polys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BuilderPoly`](ue_ue.BuilderPoly.md)\>

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Polys](ue_ue.EditorBrushBuilder.md#polys)

#### Defined in

[ue/ue.d.ts:12797](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12797)

___

### Sides

• **Sides**: `number`

#### Defined in

[ue/ue.d.ts:28554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28554)

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

### Z

• **Z**: `number`

#### Defined in

[ue/ue.d.ts:28550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28550)

___

### \_\_tid\_BrushBuilder\_\_

• **\_\_tid\_BrushBuilder\_\_**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[__tid_BrushBuilder__](ue_ue.EditorBrushBuilder.md#__tid_brushbuilder__)

#### Defined in

[ue/ue.d.ts:12804](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12804)

___

### \_\_tid\_ConeBuilder\_\_

• **\_\_tid\_ConeBuilder\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28562)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ConeBuilder`](ue_ue.ConeBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ConeBuilder`](ue_ue.ConeBuilder.md)

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Find](ue_ue.EditorBrushBuilder.md#find)

#### Defined in

[ue/ue.d.ts:28559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28559)

___

### Load

▸ `Static` **Load**(`InName`): [`ConeBuilder`](ue_ue.ConeBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ConeBuilder`](ue_ue.ConeBuilder.md)

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Load](ue_ue.EditorBrushBuilder.md#load)

#### Defined in

[ue/ue.d.ts:28560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28560)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[StaticClass](ue_ue.EditorBrushBuilder.md#staticclass)

#### Defined in

[ue/ue.d.ts:28558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28558)
