[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EnvQueryGenerator\_PathingGrid

# Class: EnvQueryGenerator\_PathingGrid

[ue/ue](../modules/ue_ue.md).EnvQueryGenerator_PathingGrid

## Hierarchy

- [`EnvQueryGenerator_SimpleGrid`](ue_ue.EnvQueryGenerator_SimpleGrid.md)

  ↳ **`EnvQueryGenerator_PathingGrid`**

## Table of contents

### Constructors

- [constructor](ue_ue.EnvQueryGenerator_PathingGrid.md#constructor)

### Properties

- [GenerateAround](ue_ue.EnvQueryGenerator_PathingGrid.md#generatearound)
- [GridSize](ue_ue.EnvQueryGenerator_PathingGrid.md#gridsize)
- [ItemType](ue_ue.EnvQueryGenerator_PathingGrid.md#itemtype)
- [NavigationFilter](ue_ue.EnvQueryGenerator_PathingGrid.md#navigationfilter)
- [OptionName](ue_ue.EnvQueryGenerator_PathingGrid.md#optionname)
- [PathToItem](ue_ue.EnvQueryGenerator_PathingGrid.md#pathtoitem)
- [ProjectionData](ue_ue.EnvQueryGenerator_PathingGrid.md#projectiondata)
- [ScanRangeMultiplier](ue_ue.EnvQueryGenerator_PathingGrid.md#scanrangemultiplier)
- [SpaceBetween](ue_ue.EnvQueryGenerator_PathingGrid.md#spacebetween)
- [VerNum](ue_ue.EnvQueryGenerator_PathingGrid.md#vernum)
- [\_\_tid\_EnvQueryGenerator\_PathingGrid\_\_](ue_ue.EnvQueryGenerator_PathingGrid.md#__tid_envquerygenerator_pathinggrid__)
- [\_\_tid\_EnvQueryGenerator\_ProjectedPoints\_\_](ue_ue.EnvQueryGenerator_PathingGrid.md#__tid_envquerygenerator_projectedpoints__)
- [\_\_tid\_EnvQueryGenerator\_SimpleGrid\_\_](ue_ue.EnvQueryGenerator_PathingGrid.md#__tid_envquerygenerator_simplegrid__)
- [\_\_tid\_EnvQueryGenerator\_\_](ue_ue.EnvQueryGenerator_PathingGrid.md#__tid_envquerygenerator__)
- [\_\_tid\_EnvQueryNode\_\_](ue_ue.EnvQueryGenerator_PathingGrid.md#__tid_envquerynode__)
- [\_\_tid\_Object\_\_](ue_ue.EnvQueryGenerator_PathingGrid.md#__tid_object__)
- [bAutoSortTests](ue_ue.EnvQueryGenerator_PathingGrid.md#bautosorttests)

### Methods

- [CreateDefaultSubobject](ue_ue.EnvQueryGenerator_PathingGrid.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EnvQueryGenerator_PathingGrid.md#executeubergraph)
- [GetClass](ue_ue.EnvQueryGenerator_PathingGrid.md#getclass)
- [GetName](ue_ue.EnvQueryGenerator_PathingGrid.md#getname)
- [GetOuter](ue_ue.EnvQueryGenerator_PathingGrid.md#getouter)
- [GetWorld](ue_ue.EnvQueryGenerator_PathingGrid.md#getworld)
- [Find](ue_ue.EnvQueryGenerator_PathingGrid.md#find)
- [Load](ue_ue.EnvQueryGenerator_PathingGrid.md#load)
- [StaticClass](ue_ue.EnvQueryGenerator_PathingGrid.md#staticclass)

## Constructors

### constructor

• **new EnvQueryGenerator_PathingGrid**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[constructor](ue_ue.EnvQueryGenerator_SimpleGrid.md#constructor)

#### Defined in

[ue/ue.d.ts:34427](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34427)

## Properties

### GenerateAround

• **GenerateAround**: [`Class`](ue_ue.Class.md)

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[GenerateAround](ue_ue.EnvQueryGenerator_SimpleGrid.md#generatearound)

#### Defined in

[ue/ue.d.ts:34418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34418)

___

### GridSize

• **GridSize**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[GridSize](ue_ue.EnvQueryGenerator_SimpleGrid.md#gridsize)

#### Defined in

[ue/ue.d.ts:34416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34416)

___

### ItemType

• **ItemType**: [`Class`](ue_ue.Class.md)

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[ItemType](ue_ue.EnvQueryGenerator_SimpleGrid.md#itemtype)

#### Defined in

[ue/ue.d.ts:15476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15476)

___

### NavigationFilter

• **NavigationFilter**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:34429](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34429)

___

### OptionName

• **OptionName**: `string`

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[OptionName](ue_ue.EnvQueryGenerator_SimpleGrid.md#optionname)

#### Defined in

[ue/ue.d.ts:15475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15475)

___

### PathToItem

• **PathToItem**: [`AIDataProviderBoolValue`](ue_ue.AIDataProviderBoolValue.md)

#### Defined in

[ue/ue.d.ts:34428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34428)

___

### ProjectionData

• **ProjectionData**: [`EnvTraceData`](ue_ue.EnvTraceData.md)

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[ProjectionData](ue_ue.EnvQueryGenerator_SimpleGrid.md#projectiondata)

#### Defined in

[ue/ue.d.ts:34314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34314)

___

### ScanRangeMultiplier

• **ScanRangeMultiplier**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Defined in

[ue/ue.d.ts:34430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34430)

___

### SpaceBetween

• **SpaceBetween**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[SpaceBetween](ue_ue.EnvQueryGenerator_SimpleGrid.md#spacebetween)

#### Defined in

[ue/ue.d.ts:34417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34417)

___

### VerNum

• **VerNum**: `number`

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[VerNum](ue_ue.EnvQueryGenerator_SimpleGrid.md#vernum)

#### Defined in

[ue/ue.d.ts:15465](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15465)

___

### \_\_tid\_EnvQueryGenerator\_PathingGrid\_\_

• **\_\_tid\_EnvQueryGenerator\_PathingGrid\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:34435](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34435)

___

### \_\_tid\_EnvQueryGenerator\_ProjectedPoints\_\_

• **\_\_tid\_EnvQueryGenerator\_ProjectedPoints\_\_**: `boolean`

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[__tid_EnvQueryGenerator_ProjectedPoints__](ue_ue.EnvQueryGenerator_SimpleGrid.md#__tid_envquerygenerator_projectedpoints__)

#### Defined in

[ue/ue.d.ts:34319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34319)

___

### \_\_tid\_EnvQueryGenerator\_SimpleGrid\_\_

• **\_\_tid\_EnvQueryGenerator\_SimpleGrid\_\_**: `boolean`

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[__tid_EnvQueryGenerator_SimpleGrid__](ue_ue.EnvQueryGenerator_SimpleGrid.md#__tid_envquerygenerator_simplegrid__)

#### Defined in

[ue/ue.d.ts:34423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34423)

___

### \_\_tid\_EnvQueryGenerator\_\_

• **\_\_tid\_EnvQueryGenerator\_\_**: `boolean`

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[__tid_EnvQueryGenerator__](ue_ue.EnvQueryGenerator_SimpleGrid.md#__tid_envquerygenerator__)

#### Defined in

[ue/ue.d.ts:15482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15482)

___

### \_\_tid\_EnvQueryNode\_\_

• **\_\_tid\_EnvQueryNode\_\_**: `boolean`

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[__tid_EnvQueryNode__](ue_ue.EnvQueryGenerator_SimpleGrid.md#__tid_envquerynode__)

#### Defined in

[ue/ue.d.ts:15470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15470)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[__tid_Object__](ue_ue.EnvQueryGenerator_SimpleGrid.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAutoSortTests

• **bAutoSortTests**: `boolean`

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[bAutoSortTests](ue_ue.EnvQueryGenerator_SimpleGrid.md#bautosorttests)

#### Defined in

[ue/ue.d.ts:15477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15477)

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

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[CreateDefaultSubobject](ue_ue.EnvQueryGenerator_SimpleGrid.md#createdefaultsubobject)

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

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[ExecuteUbergraph](ue_ue.EnvQueryGenerator_SimpleGrid.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[GetClass](ue_ue.EnvQueryGenerator_SimpleGrid.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[GetName](ue_ue.EnvQueryGenerator_SimpleGrid.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[GetOuter](ue_ue.EnvQueryGenerator_SimpleGrid.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[GetWorld](ue_ue.EnvQueryGenerator_SimpleGrid.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EnvQueryGenerator_PathingGrid`](ue_ue.EnvQueryGenerator_PathingGrid.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EnvQueryGenerator_PathingGrid`](ue_ue.EnvQueryGenerator_PathingGrid.md)

#### Overrides

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[Find](ue_ue.EnvQueryGenerator_SimpleGrid.md#find)

#### Defined in

[ue/ue.d.ts:34432](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34432)

___

### Load

▸ `Static` **Load**(`InName`): [`EnvQueryGenerator_PathingGrid`](ue_ue.EnvQueryGenerator_PathingGrid.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EnvQueryGenerator_PathingGrid`](ue_ue.EnvQueryGenerator_PathingGrid.md)

#### Overrides

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[Load](ue_ue.EnvQueryGenerator_SimpleGrid.md#load)

#### Defined in

[ue/ue.d.ts:34433](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34433)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EnvQueryGenerator_SimpleGrid](ue_ue.EnvQueryGenerator_SimpleGrid.md).[StaticClass](ue_ue.EnvQueryGenerator_SimpleGrid.md#staticclass)

#### Defined in

[ue/ue.d.ts:34431](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34431)
