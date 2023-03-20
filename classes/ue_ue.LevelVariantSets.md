[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelVariantSets

# Class: LevelVariantSets

[ue/ue](../modules/ue_ue.md).LevelVariantSets

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LevelVariantSets`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelVariantSets.md#constructor)

### Properties

- [DirectorBlueprint](ue_ue.LevelVariantSets.md#directorblueprint)
- [DirectorClass](ue_ue.LevelVariantSets.md#directorclass)
- [VariantSets](ue_ue.LevelVariantSets.md#variantsets)
- [\_\_tid\_LevelVariantSets\_\_](ue_ue.LevelVariantSets.md#__tid_levelvariantsets__)
- [\_\_tid\_Object\_\_](ue_ue.LevelVariantSets.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LevelVariantSets.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LevelVariantSets.md#executeubergraph)
- [GetClass](ue_ue.LevelVariantSets.md#getclass)
- [GetName](ue_ue.LevelVariantSets.md#getname)
- [GetNumVariantSets](ue_ue.LevelVariantSets.md#getnumvariantsets)
- [GetOuter](ue_ue.LevelVariantSets.md#getouter)
- [GetVariantSet](ue_ue.LevelVariantSets.md#getvariantset)
- [GetVariantSetByName](ue_ue.LevelVariantSets.md#getvariantsetbyname)
- [GetWorld](ue_ue.LevelVariantSets.md#getworld)
- [Find](ue_ue.LevelVariantSets.md#find)
- [Load](ue_ue.LevelVariantSets.md#load)
- [StaticClass](ue_ue.LevelVariantSets.md#staticclass)

## Constructors

### constructor

• **new LevelVariantSets**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### DirectorBlueprint

• **DirectorBlueprint**: [`Object`](ue_ue.Object.md)

___

### DirectorClass

• **DirectorClass**: [`BlueprintGeneratedClass`](ue_ue.BlueprintGeneratedClass.md)

___

### VariantSets

• **VariantSets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VariantSet`](ue_ue.VariantSet.md)\>

___

### \_\_tid\_LevelVariantSets\_\_

• **\_\_tid\_LevelVariantSets\_\_**: `boolean`

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

### GetNumVariantSets

▸ **GetNumVariantSets**(): `number`

#### Returns

`number`

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetVariantSet

▸ **GetVariantSet**(`VariantSetIndex`): [`VariantSet`](ue_ue.VariantSet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VariantSetIndex` | `number` |

#### Returns

[`VariantSet`](ue_ue.VariantSet.md)

___

### GetVariantSetByName

▸ **GetVariantSetByName**(`VariantSetName`): [`VariantSet`](ue_ue.VariantSet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VariantSetName` | `string` |

#### Returns

[`VariantSet`](ue_ue.VariantSet.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelVariantSets`](ue_ue.LevelVariantSets.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelVariantSets`](ue_ue.LevelVariantSets.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelVariantSets`](ue_ue.LevelVariantSets.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelVariantSets`](ue_ue.LevelVariantSets.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
