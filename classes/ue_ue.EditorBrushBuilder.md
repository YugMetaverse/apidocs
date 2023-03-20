[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorBrushBuilder

# Class: EditorBrushBuilder

[ue/ue](../modules/ue_ue.md).EditorBrushBuilder

## Hierarchy

- [`BrushBuilder`](ue_ue.BrushBuilder.md)

  ↳ **`EditorBrushBuilder`**

  ↳↳ [`ConeBuilder`](ue_ue.ConeBuilder.md)

  ↳↳ [`CubeBuilder`](ue_ue.CubeBuilder.md)

  ↳↳ [`CurvedStairBuilder`](ue_ue.CurvedStairBuilder.md)

  ↳↳ [`CylinderBuilder`](ue_ue.CylinderBuilder.md)

  ↳↳ [`LinearStairBuilder`](ue_ue.LinearStairBuilder.md)

  ↳↳ [`SheetBuilder`](ue_ue.SheetBuilder.md)

  ↳↳ [`SpiralStairBuilder`](ue_ue.SpiralStairBuilder.md)

  ↳↳ [`TetrahedronBuilder`](ue_ue.TetrahedronBuilder.md)

  ↳↳ [`VolumetricBuilder`](ue_ue.VolumetricBuilder.md)

## Table of contents

### Constructors

- [constructor](ue_ue.EditorBrushBuilder.md#constructor)

### Properties

- [BitmapFilename](ue_ue.EditorBrushBuilder.md#bitmapfilename)
- [Layer](ue_ue.EditorBrushBuilder.md#layer)
- [MergeCoplanars](ue_ue.EditorBrushBuilder.md#mergecoplanars)
- [NotifyBadParams](ue_ue.EditorBrushBuilder.md#notifybadparams)
- [Polys](ue_ue.EditorBrushBuilder.md#polys)
- [ToolTip](ue_ue.EditorBrushBuilder.md#tooltip)
- [Vertices](ue_ue.EditorBrushBuilder.md#vertices)
- [\_\_tid\_BrushBuilder\_\_](ue_ue.EditorBrushBuilder.md#__tid_brushbuilder__)
- [\_\_tid\_EditorBrushBuilder\_\_](ue_ue.EditorBrushBuilder.md#__tid_editorbrushbuilder__)
- [\_\_tid\_Object\_\_](ue_ue.EditorBrushBuilder.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorBrushBuilder.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorBrushBuilder.md#executeubergraph)
- [GetClass](ue_ue.EditorBrushBuilder.md#getclass)
- [GetName](ue_ue.EditorBrushBuilder.md#getname)
- [GetOuter](ue_ue.EditorBrushBuilder.md#getouter)
- [GetWorld](ue_ue.EditorBrushBuilder.md#getworld)
- [Find](ue_ue.EditorBrushBuilder.md#find)
- [Load](ue_ue.EditorBrushBuilder.md#load)
- [StaticClass](ue_ue.EditorBrushBuilder.md#staticclass)

## Constructors

### constructor

• **new EditorBrushBuilder**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BrushBuilder](ue_ue.BrushBuilder.md).[constructor](ue_ue.BrushBuilder.md#constructor)

## Properties

### BitmapFilename

• **BitmapFilename**: `string`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[BitmapFilename](ue_ue.BrushBuilder.md#bitmapfilename)

___

### Layer

• **Layer**: `string`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[Layer](ue_ue.BrushBuilder.md#layer)

___

### MergeCoplanars

• **MergeCoplanars**: `boolean`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[MergeCoplanars](ue_ue.BrushBuilder.md#mergecoplanars)

___

### NotifyBadParams

• **NotifyBadParams**: `boolean`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[NotifyBadParams](ue_ue.BrushBuilder.md#notifybadparams)

___

### Polys

• **Polys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BuilderPoly`](ue_ue.BuilderPoly.md)\>

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[Polys](ue_ue.BrushBuilder.md#polys)

___

### ToolTip

• **ToolTip**: `string`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[ToolTip](ue_ue.BrushBuilder.md#tooltip)

___

### Vertices

• **Vertices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[Vertices](ue_ue.BrushBuilder.md#vertices)

___

### \_\_tid\_BrushBuilder\_\_

• **\_\_tid\_BrushBuilder\_\_**: `boolean`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[__tid_BrushBuilder__](ue_ue.BrushBuilder.md#__tid_brushbuilder__)

___

### \_\_tid\_EditorBrushBuilder\_\_

• **\_\_tid\_EditorBrushBuilder\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[__tid_Object__](ue_ue.BrushBuilder.md#__tid_object__)

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

[BrushBuilder](ue_ue.BrushBuilder.md).[CreateDefaultSubobject](ue_ue.BrushBuilder.md#createdefaultsubobject)

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

[BrushBuilder](ue_ue.BrushBuilder.md).[ExecuteUbergraph](ue_ue.BrushBuilder.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[GetClass](ue_ue.BrushBuilder.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[GetName](ue_ue.BrushBuilder.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[GetOuter](ue_ue.BrushBuilder.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BrushBuilder](ue_ue.BrushBuilder.md).[GetWorld](ue_ue.BrushBuilder.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorBrushBuilder`](ue_ue.EditorBrushBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorBrushBuilder`](ue_ue.EditorBrushBuilder.md)

#### Overrides

[BrushBuilder](ue_ue.BrushBuilder.md).[Find](ue_ue.BrushBuilder.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorBrushBuilder`](ue_ue.EditorBrushBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorBrushBuilder`](ue_ue.EditorBrushBuilder.md)

#### Overrides

[BrushBuilder](ue_ue.BrushBuilder.md).[Load](ue_ue.BrushBuilder.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BrushBuilder](ue_ue.BrushBuilder.md).[StaticClass](ue_ue.BrushBuilder.md#staticclass)
