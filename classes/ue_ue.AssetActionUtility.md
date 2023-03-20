[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetActionUtility

# Class: AssetActionUtility

[ue/ue](../modules/ue_ue.md).AssetActionUtility

## Hierarchy

- [`EditorUtilityObject`](ue_ue.EditorUtilityObject.md)

  ↳ **`AssetActionUtility`**

## Table of contents

### Constructors

- [constructor](ue_ue.AssetActionUtility.md#constructor)

### Properties

- [\_\_tid\_AssetActionUtility\_\_](ue_ue.AssetActionUtility.md#__tid_assetactionutility__)
- [\_\_tid\_EditorUtilityObject\_\_](ue_ue.AssetActionUtility.md#__tid_editorutilityobject__)
- [\_\_tid\_Object\_\_](ue_ue.AssetActionUtility.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AssetActionUtility.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AssetActionUtility.md#executeubergraph)
- [GetClass](ue_ue.AssetActionUtility.md#getclass)
- [GetName](ue_ue.AssetActionUtility.md#getname)
- [GetOuter](ue_ue.AssetActionUtility.md#getouter)
- [GetSupportedClass](ue_ue.AssetActionUtility.md#getsupportedclass)
- [GetWorld](ue_ue.AssetActionUtility.md#getworld)
- [IsActionForBlueprints](ue_ue.AssetActionUtility.md#isactionforblueprints)
- [Run](ue_ue.AssetActionUtility.md#run)
- [Find](ue_ue.AssetActionUtility.md#find)
- [Load](ue_ue.AssetActionUtility.md#load)
- [StaticClass](ue_ue.AssetActionUtility.md#staticclass)

## Constructors

### constructor

• **new AssetActionUtility**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorUtilityObject](ue_ue.EditorUtilityObject.md).[constructor](ue_ue.EditorUtilityObject.md#constructor)

## Properties

### \_\_tid\_AssetActionUtility\_\_

• **\_\_tid\_AssetActionUtility\_\_**: `boolean`

___

### \_\_tid\_EditorUtilityObject\_\_

• **\_\_tid\_EditorUtilityObject\_\_**: `boolean`

#### Inherited from

[EditorUtilityObject](ue_ue.EditorUtilityObject.md).[__tid_EditorUtilityObject__](ue_ue.EditorUtilityObject.md#__tid_editorutilityobject__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorUtilityObject](ue_ue.EditorUtilityObject.md).[__tid_Object__](ue_ue.EditorUtilityObject.md#__tid_object__)

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

[EditorUtilityObject](ue_ue.EditorUtilityObject.md).[CreateDefaultSubobject](ue_ue.EditorUtilityObject.md#createdefaultsubobject)

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

[EditorUtilityObject](ue_ue.EditorUtilityObject.md).[ExecuteUbergraph](ue_ue.EditorUtilityObject.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorUtilityObject](ue_ue.EditorUtilityObject.md).[GetClass](ue_ue.EditorUtilityObject.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorUtilityObject](ue_ue.EditorUtilityObject.md).[GetName](ue_ue.EditorUtilityObject.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorUtilityObject](ue_ue.EditorUtilityObject.md).[GetOuter](ue_ue.EditorUtilityObject.md#getouter)

___

### GetSupportedClass

▸ **GetSupportedClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditorUtilityObject](ue_ue.EditorUtilityObject.md).[GetWorld](ue_ue.EditorUtilityObject.md#getworld)

___

### IsActionForBlueprints

▸ **IsActionForBlueprints**(): `boolean`

#### Returns

`boolean`

___

### Run

▸ **Run**(): `void`

#### Returns

`void`

#### Inherited from

[EditorUtilityObject](ue_ue.EditorUtilityObject.md).[Run](ue_ue.EditorUtilityObject.md#run)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AssetActionUtility`](ue_ue.AssetActionUtility.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AssetActionUtility`](ue_ue.AssetActionUtility.md)

#### Overrides

[EditorUtilityObject](ue_ue.EditorUtilityObject.md).[Find](ue_ue.EditorUtilityObject.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AssetActionUtility`](ue_ue.AssetActionUtility.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AssetActionUtility`](ue_ue.AssetActionUtility.md)

#### Overrides

[EditorUtilityObject](ue_ue.EditorUtilityObject.md).[Load](ue_ue.EditorUtilityObject.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorUtilityObject](ue_ue.EditorUtilityObject.md).[StaticClass](ue_ue.EditorUtilityObject.md#staticclass)
