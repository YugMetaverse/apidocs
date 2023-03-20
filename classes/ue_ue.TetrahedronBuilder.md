[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TetrahedronBuilder

# Class: TetrahedronBuilder

[ue/ue](../modules/ue_ue.md).TetrahedronBuilder

## Hierarchy

- [`EditorBrushBuilder`](ue_ue.EditorBrushBuilder.md)

  ↳ **`TetrahedronBuilder`**

## Table of contents

### Constructors

- [constructor](ue_ue.TetrahedronBuilder.md#constructor)

### Properties

- [BitmapFilename](ue_ue.TetrahedronBuilder.md#bitmapfilename)
- [GroupName](ue_ue.TetrahedronBuilder.md#groupname)
- [Layer](ue_ue.TetrahedronBuilder.md#layer)
- [MergeCoplanars](ue_ue.TetrahedronBuilder.md#mergecoplanars)
- [NotifyBadParams](ue_ue.TetrahedronBuilder.md#notifybadparams)
- [Polys](ue_ue.TetrahedronBuilder.md#polys)
- [Radius](ue_ue.TetrahedronBuilder.md#radius)
- [SphereExtrapolation](ue_ue.TetrahedronBuilder.md#sphereextrapolation)
- [ToolTip](ue_ue.TetrahedronBuilder.md#tooltip)
- [Vertices](ue_ue.TetrahedronBuilder.md#vertices)
- [\_\_tid\_BrushBuilder\_\_](ue_ue.TetrahedronBuilder.md#__tid_brushbuilder__)
- [\_\_tid\_EditorBrushBuilder\_\_](ue_ue.TetrahedronBuilder.md#__tid_editorbrushbuilder__)
- [\_\_tid\_Object\_\_](ue_ue.TetrahedronBuilder.md#__tid_object__)
- [\_\_tid\_TetrahedronBuilder\_\_](ue_ue.TetrahedronBuilder.md#__tid_tetrahedronbuilder__)

### Methods

- [CreateDefaultSubobject](ue_ue.TetrahedronBuilder.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TetrahedronBuilder.md#executeubergraph)
- [GetClass](ue_ue.TetrahedronBuilder.md#getclass)
- [GetName](ue_ue.TetrahedronBuilder.md#getname)
- [GetOuter](ue_ue.TetrahedronBuilder.md#getouter)
- [GetWorld](ue_ue.TetrahedronBuilder.md#getworld)
- [Find](ue_ue.TetrahedronBuilder.md#find)
- [Load](ue_ue.TetrahedronBuilder.md#load)
- [StaticClass](ue_ue.TetrahedronBuilder.md#staticclass)

## Constructors

### constructor

• **new TetrahedronBuilder**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[constructor](ue_ue.EditorBrushBuilder.md#constructor)

## Properties

### BitmapFilename

• **BitmapFilename**: `string`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[BitmapFilename](ue_ue.EditorBrushBuilder.md#bitmapfilename)

___

### GroupName

• **GroupName**: `string`

___

### Layer

• **Layer**: `string`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Layer](ue_ue.EditorBrushBuilder.md#layer)

___

### MergeCoplanars

• **MergeCoplanars**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[MergeCoplanars](ue_ue.EditorBrushBuilder.md#mergecoplanars)

___

### NotifyBadParams

• **NotifyBadParams**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[NotifyBadParams](ue_ue.EditorBrushBuilder.md#notifybadparams)

___

### Polys

• **Polys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BuilderPoly`](ue_ue.BuilderPoly.md)\>

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Polys](ue_ue.EditorBrushBuilder.md#polys)

___

### Radius

• **Radius**: `number`

___

### SphereExtrapolation

• **SphereExtrapolation**: `number`

___

### ToolTip

• **ToolTip**: `string`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[ToolTip](ue_ue.EditorBrushBuilder.md#tooltip)

___

### Vertices

• **Vertices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Vertices](ue_ue.EditorBrushBuilder.md#vertices)

___

### \_\_tid\_BrushBuilder\_\_

• **\_\_tid\_BrushBuilder\_\_**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[__tid_BrushBuilder__](ue_ue.EditorBrushBuilder.md#__tid_brushbuilder__)

___

### \_\_tid\_EditorBrushBuilder\_\_

• **\_\_tid\_EditorBrushBuilder\_\_**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[__tid_EditorBrushBuilder__](ue_ue.EditorBrushBuilder.md#__tid_editorbrushbuilder__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[__tid_Object__](ue_ue.EditorBrushBuilder.md#__tid_object__)

___

### \_\_tid\_TetrahedronBuilder\_\_

• **\_\_tid\_TetrahedronBuilder\_\_**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[GetClass](ue_ue.EditorBrushBuilder.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[GetName](ue_ue.EditorBrushBuilder.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[GetOuter](ue_ue.EditorBrushBuilder.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[GetWorld](ue_ue.EditorBrushBuilder.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TetrahedronBuilder`](ue_ue.TetrahedronBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TetrahedronBuilder`](ue_ue.TetrahedronBuilder.md)

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Find](ue_ue.EditorBrushBuilder.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TetrahedronBuilder`](ue_ue.TetrahedronBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TetrahedronBuilder`](ue_ue.TetrahedronBuilder.md)

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Load](ue_ue.EditorBrushBuilder.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[StaticClass](ue_ue.EditorBrushBuilder.md#staticclass)
