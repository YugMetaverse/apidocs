[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TileMapBlueprintLibrary

# Class: TileMapBlueprintLibrary

[ue/ue](../modules/ue_ue.md).TileMapBlueprintLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`TileMapBlueprintLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.TileMapBlueprintLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.TileMapBlueprintLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.TileMapBlueprintLibrary.md#__tid_object__)
- [\_\_tid\_TileMapBlueprintLibrary\_\_](ue_ue.TileMapBlueprintLibrary.md#__tid_tilemapblueprintlibrary__)

### Methods

- [CreateDefaultSubobject](ue_ue.TileMapBlueprintLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TileMapBlueprintLibrary.md#executeubergraph)
- [GetClass](ue_ue.TileMapBlueprintLibrary.md#getclass)
- [GetName](ue_ue.TileMapBlueprintLibrary.md#getname)
- [GetOuter](ue_ue.TileMapBlueprintLibrary.md#getouter)
- [GetWorld](ue_ue.TileMapBlueprintLibrary.md#getworld)
- [BreakTile](ue_ue.TileMapBlueprintLibrary.md#breaktile)
- [Find](ue_ue.TileMapBlueprintLibrary.md#find)
- [GetTileTransform](ue_ue.TileMapBlueprintLibrary.md#gettiletransform)
- [GetTileUserData](ue_ue.TileMapBlueprintLibrary.md#gettileuserdata)
- [Load](ue_ue.TileMapBlueprintLibrary.md#load)
- [MakeTile](ue_ue.TileMapBlueprintLibrary.md#maketile)
- [StaticClass](ue_ue.TileMapBlueprintLibrary.md#staticclass)

## Constructors

### constructor

• **new TileMapBlueprintLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

___

### \_\_tid\_TileMapBlueprintLibrary\_\_

• **\_\_tid\_TileMapBlueprintLibrary\_\_**: `boolean`

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

### BreakTile

▸ `Static` **BreakTile**(`Tile`, `TileIndex`, `TileSet`, `bFlipH`, `bFlipV`, `bFlipD`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tile` | [`PaperTileInfo`](ue_ue.PaperTileInfo.md) |
| `TileIndex` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `TileSet` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PaperTileSet`](ue_ue.PaperTileSet.md)\> |
| `bFlipH` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `bFlipV` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `bFlipD` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TileMapBlueprintLibrary`](ue_ue.TileMapBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TileMapBlueprintLibrary`](ue_ue.TileMapBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetTileTransform

▸ `Static` **GetTileTransform**(`Tile`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tile` | [`PaperTileInfo`](ue_ue.PaperTileInfo.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### GetTileUserData

▸ `Static` **GetTileUserData**(`Tile`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tile` | [`PaperTileInfo`](ue_ue.PaperTileInfo.md) |

#### Returns

`string`

___

### Load

▸ `Static` **Load**(`InName`): [`TileMapBlueprintLibrary`](ue_ue.TileMapBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TileMapBlueprintLibrary`](ue_ue.TileMapBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### MakeTile

▸ `Static` **MakeTile**(`TileIndex`, `TileSet`, `bFlipH`, `bFlipV`, `bFlipD`): [`PaperTileInfo`](ue_ue.PaperTileInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TileIndex` | `number` |
| `TileSet` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PaperTileSet`](ue_ue.PaperTileSet.md)\> |
| `bFlipH` | `boolean` |
| `bFlipV` | `boolean` |
| `bFlipD` | `boolean` |

#### Returns

[`PaperTileInfo`](ue_ue.PaperTileInfo.md)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
