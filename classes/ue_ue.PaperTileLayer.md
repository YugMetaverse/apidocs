[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PaperTileLayer

# Class: PaperTileLayer

[ue/ue](../modules/ue_ue.md).PaperTileLayer

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PaperTileLayer`**

## Table of contents

### Constructors

- [constructor](ue_ue.PaperTileLayer.md#constructor)

### Properties

- [AllocatedCells](ue_ue.PaperTileLayer.md#allocatedcells)
- [AllocatedGrid](ue_ue.PaperTileLayer.md#allocatedgrid)
- [AllocatedHeight](ue_ue.PaperTileLayer.md#allocatedheight)
- [AllocatedWidth](ue_ue.PaperTileLayer.md#allocatedwidth)
- [CollisionOffsetOverride](ue_ue.PaperTileLayer.md#collisionoffsetoverride)
- [CollisionThicknessOverride](ue_ue.PaperTileLayer.md#collisionthicknessoverride)
- [LayerColor](ue_ue.PaperTileLayer.md#layercolor)
- [LayerHeight](ue_ue.PaperTileLayer.md#layerheight)
- [LayerName](ue_ue.PaperTileLayer.md#layername)
- [LayerWidth](ue_ue.PaperTileLayer.md#layerwidth)
- [TileSet](ue_ue.PaperTileLayer.md#tileset)
- [\_\_tid\_Object\_\_](ue_ue.PaperTileLayer.md#__tid_object__)
- [\_\_tid\_PaperTileLayer\_\_](ue_ue.PaperTileLayer.md#__tid_papertilelayer__)
- [bHiddenInEditor](ue_ue.PaperTileLayer.md#bhiddenineditor)
- [bHiddenInGame](ue_ue.PaperTileLayer.md#bhiddeningame)
- [bLayerCollides](ue_ue.PaperTileLayer.md#blayercollides)
- [bOverrideCollisionOffset](ue_ue.PaperTileLayer.md#boverridecollisionoffset)
- [bOverrideCollisionThickness](ue_ue.PaperTileLayer.md#boverridecollisionthickness)

### Methods

- [CreateDefaultSubobject](ue_ue.PaperTileLayer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PaperTileLayer.md#executeubergraph)
- [GetClass](ue_ue.PaperTileLayer.md#getclass)
- [GetName](ue_ue.PaperTileLayer.md#getname)
- [GetOuter](ue_ue.PaperTileLayer.md#getouter)
- [GetWorld](ue_ue.PaperTileLayer.md#getworld)
- [Find](ue_ue.PaperTileLayer.md#find)
- [Load](ue_ue.PaperTileLayer.md#load)
- [StaticClass](ue_ue.PaperTileLayer.md#staticclass)

## Constructors

### constructor

• **new PaperTileLayer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AllocatedCells

• **AllocatedCells**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PaperTileInfo`](ue_ue.PaperTileInfo.md)\>

___

### AllocatedGrid

• **AllocatedGrid**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### AllocatedHeight

• **AllocatedHeight**: `number`

___

### AllocatedWidth

• **AllocatedWidth**: `number`

___

### CollisionOffsetOverride

• **CollisionOffsetOverride**: `number`

___

### CollisionThicknessOverride

• **CollisionThicknessOverride**: `number`

___

### LayerColor

• **LayerColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### LayerHeight

• **LayerHeight**: `number`

___

### LayerName

• **LayerName**: `string`

___

### LayerWidth

• **LayerWidth**: `number`

___

### TileSet

• **TileSet**: [`PaperTileSet`](ue_ue.PaperTileSet.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PaperTileLayer\_\_

• **\_\_tid\_PaperTileLayer\_\_**: `boolean`

___

### bHiddenInEditor

• **bHiddenInEditor**: `boolean`

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

___

### bLayerCollides

• **bLayerCollides**: `boolean`

___

### bOverrideCollisionOffset

• **bOverrideCollisionOffset**: `boolean`

___

### bOverrideCollisionThickness

• **bOverrideCollisionThickness**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PaperTileLayer`](ue_ue.PaperTileLayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PaperTileLayer`](ue_ue.PaperTileLayer.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PaperTileLayer`](ue_ue.PaperTileLayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PaperTileLayer`](ue_ue.PaperTileLayer.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
