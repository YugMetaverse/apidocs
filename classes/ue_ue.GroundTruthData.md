[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GroundTruthData

# Class: GroundTruthData

[ue/ue](../modules/ue_ue.md).GroundTruthData

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`GroundTruthData`**

## Table of contents

### Constructors

- [constructor](ue_ue.GroundTruthData.md#constructor)

### Properties

- [ObjectData](ue_ue.GroundTruthData.md#objectdata)
- [\_\_tid\_GroundTruthData\_\_](ue_ue.GroundTruthData.md#__tid_groundtruthdata__)
- [\_\_tid\_Object\_\_](ue_ue.GroundTruthData.md#__tid_object__)
- [bResetGroundTruth](ue_ue.GroundTruthData.md#bresetgroundtruth)

### Methods

- [CanModify](ue_ue.GroundTruthData.md#canmodify)
- [CreateDefaultSubobject](ue_ue.GroundTruthData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GroundTruthData.md#executeubergraph)
- [GetClass](ue_ue.GroundTruthData.md#getclass)
- [GetName](ue_ue.GroundTruthData.md#getname)
- [GetOuter](ue_ue.GroundTruthData.md#getouter)
- [GetWorld](ue_ue.GroundTruthData.md#getworld)
- [LoadObject](ue_ue.GroundTruthData.md#loadobject)
- [SaveObject](ue_ue.GroundTruthData.md#saveobject)
- [Find](ue_ue.GroundTruthData.md#find)
- [Load](ue_ue.GroundTruthData.md#load)
- [StaticClass](ue_ue.GroundTruthData.md#staticclass)

## Constructors

### constructor

• **new GroundTruthData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ObjectData

• **ObjectData**: [`Object`](ue_ue.Object.md)

___

### \_\_tid\_GroundTruthData\_\_

• **\_\_tid\_GroundTruthData\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bResetGroundTruth

• **bResetGroundTruth**: `boolean`

## Methods

### CanModify

▸ **CanModify**(): `boolean`

#### Returns

`boolean`

___

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

### LoadObject

▸ **LoadObject**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

___

### SaveObject

▸ **SaveObject**(`GroundTruth`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroundTruth` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GroundTruthData`](ue_ue.GroundTruthData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GroundTruthData`](ue_ue.GroundTruthData.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GroundTruthData`](ue_ue.GroundTruthData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GroundTruthData`](ue_ue.GroundTruthData.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
