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

#### Defined in

[ue/ue.d.ts:44419](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44419)

## Properties

### ComponentNumSubsections

• **ComponentNumSubsections**: `number`

#### Defined in

[ue/ue.d.ts:44424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44424)

___

### ComponentSizeQuads

• **ComponentSizeQuads**: `number`

#### Defined in

[ue/ue.d.ts:44422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44422)

___

### DrawScale

• **DrawScale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:44425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44425)

___

### LandscapeActor

• **LandscapeActor**: [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`Landscape`](ue_ue.Landscape.md)\>

#### Defined in

[ue/ue.d.ts:44420](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44420)

___

### LandscapeGuid

• **LandscapeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:44421](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44421)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeInfoLayerSettings`](ue_ue.LandscapeInfoLayerSettings.md)\>

#### Defined in

[ue/ue.d.ts:44426](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44426)

___

### Proxies

• **Proxies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeStreamingProxy`](ue_ue.LandscapeStreamingProxy.md)\>

#### Defined in

[ue/ue.d.ts:44427](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44427)

___

### SubsectionSizeQuads

• **SubsectionSizeQuads**: `number`

#### Defined in

[ue/ue.d.ts:44423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44423)

___

### \_\_tid\_LandscapeInfo\_\_

• **\_\_tid\_LandscapeInfo\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:44432](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44432)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:44429](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44429)

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

#### Defined in

[ue/ue.d.ts:44430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44430)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:44428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44428)
