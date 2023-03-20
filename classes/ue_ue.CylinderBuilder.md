[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CylinderBuilder

# Class: CylinderBuilder

[ue/ue](../modules/ue_ue.md).CylinderBuilder

## Hierarchy

- [`EditorBrushBuilder`](ue_ue.EditorBrushBuilder.md)

  ↳ **`CylinderBuilder`**

## Table of contents

### Constructors

- [constructor](ue_ue.CylinderBuilder.md#constructor)

### Properties

- [AlignToSide](ue_ue.CylinderBuilder.md#aligntoside)
- [BitmapFilename](ue_ue.CylinderBuilder.md#bitmapfilename)
- [GroupName](ue_ue.CylinderBuilder.md#groupname)
- [Hollow](ue_ue.CylinderBuilder.md#hollow)
- [InnerRadius](ue_ue.CylinderBuilder.md#innerradius)
- [Layer](ue_ue.CylinderBuilder.md#layer)
- [MergeCoplanars](ue_ue.CylinderBuilder.md#mergecoplanars)
- [NotifyBadParams](ue_ue.CylinderBuilder.md#notifybadparams)
- [OuterRadius](ue_ue.CylinderBuilder.md#outerradius)
- [Polys](ue_ue.CylinderBuilder.md#polys)
- [Sides](ue_ue.CylinderBuilder.md#sides)
- [ToolTip](ue_ue.CylinderBuilder.md#tooltip)
- [Vertices](ue_ue.CylinderBuilder.md#vertices)
- [Z](ue_ue.CylinderBuilder.md#z)
- [\_\_tid\_BrushBuilder\_\_](ue_ue.CylinderBuilder.md#__tid_brushbuilder__)
- [\_\_tid\_CylinderBuilder\_\_](ue_ue.CylinderBuilder.md#__tid_cylinderbuilder__)
- [\_\_tid\_EditorBrushBuilder\_\_](ue_ue.CylinderBuilder.md#__tid_editorbrushbuilder__)
- [\_\_tid\_Object\_\_](ue_ue.CylinderBuilder.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.CylinderBuilder.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CylinderBuilder.md#executeubergraph)
- [GetClass](ue_ue.CylinderBuilder.md#getclass)
- [GetName](ue_ue.CylinderBuilder.md#getname)
- [GetOuter](ue_ue.CylinderBuilder.md#getouter)
- [GetWorld](ue_ue.CylinderBuilder.md#getworld)
- [Find](ue_ue.CylinderBuilder.md#find)
- [Load](ue_ue.CylinderBuilder.md#load)
- [StaticClass](ue_ue.CylinderBuilder.md#staticclass)

## Constructors

### constructor

• **new CylinderBuilder**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[constructor](ue_ue.EditorBrushBuilder.md#constructor)

#### Defined in

[ue/ue.d.ts:29287](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29287)

## Properties

### AlignToSide

• **AlignToSide**: `boolean`

#### Defined in

[ue/ue.d.ts:29293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29293)

___

### BitmapFilename

• **BitmapFilename**: `string`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[BitmapFilename](ue_ue.EditorBrushBuilder.md#bitmapfilename)

#### Defined in

[ue/ue.d.ts:12793](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12793)

___

### GroupName

• **GroupName**: `string`

#### Defined in

[ue/ue.d.ts:29292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29292)

___

### Hollow

• **Hollow**: `boolean`

#### Defined in

[ue/ue.d.ts:29294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29294)

___

### InnerRadius

• **InnerRadius**: `number`

#### Defined in

[ue/ue.d.ts:29290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29290)

___

### Layer

• **Layer**: `string`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Layer](ue_ue.EditorBrushBuilder.md#layer)

#### Defined in

[ue/ue.d.ts:12798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12798)

___

### MergeCoplanars

• **MergeCoplanars**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[MergeCoplanars](ue_ue.EditorBrushBuilder.md#mergecoplanars)

#### Defined in

[ue/ue.d.ts:12799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12799)

___

### NotifyBadParams

• **NotifyBadParams**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[NotifyBadParams](ue_ue.EditorBrushBuilder.md#notifybadparams)

#### Defined in

[ue/ue.d.ts:12795](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12795)

___

### OuterRadius

• **OuterRadius**: `number`

#### Defined in

[ue/ue.d.ts:29289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29289)

___

### Polys

• **Polys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BuilderPoly`](ue_ue.BuilderPoly.md)\>

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Polys](ue_ue.EditorBrushBuilder.md#polys)

#### Defined in

[ue/ue.d.ts:12797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12797)

___

### Sides

• **Sides**: `number`

#### Defined in

[ue/ue.d.ts:29291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29291)

___

### ToolTip

• **ToolTip**: `string`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[ToolTip](ue_ue.EditorBrushBuilder.md#tooltip)

#### Defined in

[ue/ue.d.ts:12794](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12794)

___

### Vertices

• **Vertices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Vertices](ue_ue.EditorBrushBuilder.md#vertices)

#### Defined in

[ue/ue.d.ts:12796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12796)

___

### Z

• **Z**: `number`

#### Defined in

[ue/ue.d.ts:29288](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29288)

___

### \_\_tid\_BrushBuilder\_\_

• **\_\_tid\_BrushBuilder\_\_**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[__tid_BrushBuilder__](ue_ue.EditorBrushBuilder.md#__tid_brushbuilder__)

#### Defined in

[ue/ue.d.ts:12804](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12804)

___

### \_\_tid\_CylinderBuilder\_\_

• **\_\_tid\_CylinderBuilder\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:29299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29299)

___

### \_\_tid\_EditorBrushBuilder\_\_

• **\_\_tid\_EditorBrushBuilder\_\_**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[__tid_EditorBrushBuilder__](ue_ue.EditorBrushBuilder.md#__tid_editorbrushbuilder__)

#### Defined in

[ue/ue.d.ts:28545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28545)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[__tid_Object__](ue_ue.EditorBrushBuilder.md#__tid_object__)

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

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[CreateDefaultSubobject](ue_ue.EditorBrushBuilder.md#createdefaultsubobject)

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

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[ExecuteUbergraph](ue_ue.EditorBrushBuilder.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[GetClass](ue_ue.EditorBrushBuilder.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[GetName](ue_ue.EditorBrushBuilder.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[GetOuter](ue_ue.EditorBrushBuilder.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[GetWorld](ue_ue.EditorBrushBuilder.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CylinderBuilder`](ue_ue.CylinderBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CylinderBuilder`](ue_ue.CylinderBuilder.md)

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Find](ue_ue.EditorBrushBuilder.md#find)

#### Defined in

[ue/ue.d.ts:29296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29296)

___

### Load

▸ `Static` **Load**(`InName`): [`CylinderBuilder`](ue_ue.CylinderBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CylinderBuilder`](ue_ue.CylinderBuilder.md)

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[Load](ue_ue.EditorBrushBuilder.md#load)

#### Defined in

[ue/ue.d.ts:29297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29297)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorBrushBuilder](ue_ue.EditorBrushBuilder.md).[StaticClass](ue_ue.EditorBrushBuilder.md#staticclass)

#### Defined in

[ue/ue.d.ts:29295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29295)
