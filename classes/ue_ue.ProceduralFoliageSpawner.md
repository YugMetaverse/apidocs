[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ProceduralFoliageSpawner

# Class: ProceduralFoliageSpawner

[ue/ue](../modules/ue_ue.md).ProceduralFoliageSpawner

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ProceduralFoliageSpawner`**

## Table of contents

### Constructors

- [constructor](ue_ue.ProceduralFoliageSpawner.md#constructor)

### Properties

- [FoliageTypes](ue_ue.ProceduralFoliageSpawner.md#foliagetypes)
- [MinimumQuadTreeSize](ue_ue.ProceduralFoliageSpawner.md#minimumquadtreesize)
- [NumUniqueTiles](ue_ue.ProceduralFoliageSpawner.md#numuniquetiles)
- [RandomSeed](ue_ue.ProceduralFoliageSpawner.md#randomseed)
- [TileSize](ue_ue.ProceduralFoliageSpawner.md#tilesize)
- [\_\_tid\_Object\_\_](ue_ue.ProceduralFoliageSpawner.md#__tid_object__)
- [\_\_tid\_ProceduralFoliageSpawner\_\_](ue_ue.ProceduralFoliageSpawner.md#__tid_proceduralfoliagespawner__)
- [bNeedsSimulation](ue_ue.ProceduralFoliageSpawner.md#bneedssimulation)

### Methods

- [CreateDefaultSubobject](ue_ue.ProceduralFoliageSpawner.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ProceduralFoliageSpawner.md#executeubergraph)
- [GetClass](ue_ue.ProceduralFoliageSpawner.md#getclass)
- [GetName](ue_ue.ProceduralFoliageSpawner.md#getname)
- [GetOuter](ue_ue.ProceduralFoliageSpawner.md#getouter)
- [GetWorld](ue_ue.ProceduralFoliageSpawner.md#getworld)
- [Simulate](ue_ue.ProceduralFoliageSpawner.md#simulate)
- [Find](ue_ue.ProceduralFoliageSpawner.md#find)
- [Load](ue_ue.ProceduralFoliageSpawner.md#load)
- [StaticClass](ue_ue.ProceduralFoliageSpawner.md#staticclass)

## Constructors

### constructor

• **new ProceduralFoliageSpawner**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### FoliageTypes

• **FoliageTypes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FoliageTypeObject`](ue_ue.FoliageTypeObject.md)\>

___

### MinimumQuadTreeSize

• **MinimumQuadTreeSize**: `number`

___

### NumUniqueTiles

• **NumUniqueTiles**: `number`

___

### RandomSeed

• **RandomSeed**: `number`

___

### TileSize

• **TileSize**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_ProceduralFoliageSpawner\_\_

• **\_\_tid\_ProceduralFoliageSpawner\_\_**: `boolean`

___

### bNeedsSimulation

• **bNeedsSimulation**: `boolean`

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

### Simulate

▸ **Simulate**(`NumSteps?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumSteps?` | `number` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ProceduralFoliageSpawner`](ue_ue.ProceduralFoliageSpawner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ProceduralFoliageSpawner`](ue_ue.ProceduralFoliageSpawner.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ProceduralFoliageSpawner`](ue_ue.ProceduralFoliageSpawner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ProceduralFoliageSpawner`](ue_ue.ProceduralFoliageSpawner.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
