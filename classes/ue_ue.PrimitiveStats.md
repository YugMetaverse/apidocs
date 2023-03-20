[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PrimitiveStats

# Class: PrimitiveStats

[ue/ue](../modules/ue_ue.md).PrimitiveStats

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PrimitiveStats`**

## Table of contents

### Constructors

- [constructor](ue_ue.PrimitiveStats.md#constructor)

### Properties

- [Actors](ue_ue.PrimitiveStats.md#actors)
- [Count](ue_ue.PrimitiveStats.md#count)
- [HWInstances](ue_ue.PrimitiveStats.md#hwinstances)
- [InstSections](ue_ue.PrimitiveStats.md#instsections)
- [InstTriangles](ue_ue.PrimitiveStats.md#insttriangles)
- [InstVertexColorMem](ue_ue.PrimitiveStats.md#instvertexcolormem)
- [LMSMResolution](ue_ue.PrimitiveStats.md#lmsmresolution)
- [LightMapData](ue_ue.PrimitiveStats.md#lightmapdata)
- [LightsLM](ue_ue.PrimitiveStats.md#lightslm)
- [LightsOther](ue_ue.PrimitiveStats.md#lightsother)
- [LightsTotal](ue_ue.PrimitiveStats.md#lightstotal)
- [ObjLightCost](ue_ue.PrimitiveStats.md#objlightcost)
- [Object](ue_ue.PrimitiveStats.md#object)
- [RadiusAvg](ue_ue.PrimitiveStats.md#radiusavg)
- [RadiusMax](ue_ue.PrimitiveStats.md#radiusmax)
- [RadiusMin](ue_ue.PrimitiveStats.md#radiusmin)
- [ResourceSize](ue_ue.PrimitiveStats.md#resourcesize)
- [Sections](ue_ue.PrimitiveStats.md#sections)
- [Triangles](ue_ue.PrimitiveStats.md#triangles)
- [Type](ue_ue.PrimitiveStats.md#type)
- [VertexColorMem](ue_ue.PrimitiveStats.md#vertexcolormem)
- [\_\_tid\_Object\_\_](ue_ue.PrimitiveStats.md#__tid_object__)
- [\_\_tid\_PrimitiveStats\_\_](ue_ue.PrimitiveStats.md#__tid_primitivestats__)

### Methods

- [CreateDefaultSubobject](ue_ue.PrimitiveStats.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PrimitiveStats.md#executeubergraph)
- [GetClass](ue_ue.PrimitiveStats.md#getclass)
- [GetName](ue_ue.PrimitiveStats.md#getname)
- [GetOuter](ue_ue.PrimitiveStats.md#getouter)
- [GetWorld](ue_ue.PrimitiveStats.md#getworld)
- [Find](ue_ue.PrimitiveStats.md#find)
- [Load](ue_ue.PrimitiveStats.md#load)
- [StaticClass](ue_ue.PrimitiveStats.md#staticclass)

## Constructors

### constructor

• **new PrimitiveStats**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Actors

• **Actors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>\>

___

### Count

• **Count**: `number`

___

### HWInstances

• **HWInstances**: `number`

___

### InstSections

• **InstSections**: `number`

___

### InstTriangles

• **InstTriangles**: `number`

___

### InstVertexColorMem

• **InstVertexColorMem**: `number`

___

### LMSMResolution

• **LMSMResolution**: `number`

___

### LightMapData

• **LightMapData**: `number`

___

### LightsLM

• **LightsLM**: `number`

___

### LightsOther

• **LightsOther**: `number`

___

### LightsTotal

• **LightsTotal**: `number`

___

### ObjLightCost

• **ObjLightCost**: `number`

___

### Object

• **Object**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

___

### RadiusAvg

• **RadiusAvg**: `number`

___

### RadiusMax

• **RadiusMax**: `number`

___

### RadiusMin

• **RadiusMin**: `number`

___

### ResourceSize

• **ResourceSize**: `number`

___

### Sections

• **Sections**: `number`

___

### Triangles

• **Triangles**: `number`

___

### Type

• **Type**: `string`

___

### VertexColorMem

• **VertexColorMem**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PrimitiveStats\_\_

• **\_\_tid\_PrimitiveStats\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PrimitiveStats`](ue_ue.PrimitiveStats.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PrimitiveStats`](ue_ue.PrimitiveStats.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PrimitiveStats`](ue_ue.PrimitiveStats.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PrimitiveStats`](ue_ue.PrimitiveStats.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
