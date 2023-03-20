[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LandscapeInfo

# Class: LandscapeInfo

[ue/ue](../modules/ue_ue.md).LandscapeInfo

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LandscapeInfo`**

## Table of contents

### Constructors

- [constructor](ue_ue.LandscapeInfo.md#constructor)

### Properties

- [ComponentNumSubsections](ue_ue.LandscapeInfo.md#componentnumsubsections)
- [ComponentSizeQuads](ue_ue.LandscapeInfo.md#componentsizequads)
- [DrawScale](ue_ue.LandscapeInfo.md#drawscale)
- [LandscapeActor](ue_ue.LandscapeInfo.md#landscapeactor)
- [LandscapeGuid](ue_ue.LandscapeInfo.md#landscapeguid)
- [Layers](ue_ue.LandscapeInfo.md#layers)
- [Proxies](ue_ue.LandscapeInfo.md#proxies)
- [SubsectionSizeQuads](ue_ue.LandscapeInfo.md#subsectionsizequads)
- [\_\_tid\_LandscapeInfo\_\_](ue_ue.LandscapeInfo.md#__tid_landscapeinfo__)
- [\_\_tid\_Object\_\_](ue_ue.LandscapeInfo.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LandscapeInfo.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LandscapeInfo.md#executeubergraph)
- [GetClass](ue_ue.LandscapeInfo.md#getclass)
- [GetName](ue_ue.LandscapeInfo.md#getname)
- [GetOuter](ue_ue.LandscapeInfo.md#getouter)
- [GetWorld](ue_ue.LandscapeInfo.md#getworld)
- [Find](ue_ue.LandscapeInfo.md#find)
- [Load](ue_ue.LandscapeInfo.md#load)
- [StaticClass](ue_ue.LandscapeInfo.md#staticclass)

## Constructors

### constructor

• **new LandscapeInfo**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ComponentNumSubsections

• **ComponentNumSubsections**: `number`

___

### ComponentSizeQuads

• **ComponentSizeQuads**: `number`

___

### DrawScale

• **DrawScale**: [`Vector`](ue_ue_s.Vector.md)

___

### LandscapeActor

• **LandscapeActor**: [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`Landscape`](ue_ue.Landscape.md)\>

___

### LandscapeGuid

• **LandscapeGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeInfoLayerSettings`](ue_ue.LandscapeInfoLayerSettings.md)\>

___

### Proxies

• **Proxies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeStreamingProxy`](ue_ue.LandscapeStreamingProxy.md)\>

___

### SubsectionSizeQuads

• **SubsectionSizeQuads**: `number`

___

### \_\_tid\_LandscapeInfo\_\_

• **\_\_tid\_LandscapeInfo\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LandscapeInfo`](ue_ue.LandscapeInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LandscapeInfo`](ue_ue.LandscapeInfo.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LandscapeInfo`](ue_ue.LandscapeInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LandscapeInfo`](ue_ue.LandscapeInfo.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
