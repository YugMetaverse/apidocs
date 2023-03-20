[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorAnimSegment

# Class: EditorAnimSegment

[ue/ue](../modules/ue_ue.md).EditorAnimSegment

## Hierarchy

- [`EditorAnimBaseObj`](ue_ue.EditorAnimBaseObj.md)

  ↳ **`EditorAnimSegment`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorAnimSegment.md#constructor)

### Properties

- [AnimSegment](ue_ue.EditorAnimSegment.md#animsegment)
- [\_\_tid\_EditorAnimBaseObj\_\_](ue_ue.EditorAnimSegment.md#__tid_editoranimbaseobj__)
- [\_\_tid\_EditorAnimSegment\_\_](ue_ue.EditorAnimSegment.md#__tid_editoranimsegment__)
- [\_\_tid\_Object\_\_](ue_ue.EditorAnimSegment.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorAnimSegment.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorAnimSegment.md#executeubergraph)
- [GetClass](ue_ue.EditorAnimSegment.md#getclass)
- [GetName](ue_ue.EditorAnimSegment.md#getname)
- [GetOuter](ue_ue.EditorAnimSegment.md#getouter)
- [GetWorld](ue_ue.EditorAnimSegment.md#getworld)
- [Find](ue_ue.EditorAnimSegment.md#find)
- [Load](ue_ue.EditorAnimSegment.md#load)
- [StaticClass](ue_ue.EditorAnimSegment.md#staticclass)

## Constructors

### constructor

• **new EditorAnimSegment**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorAnimBaseObj](ue_ue.EditorAnimBaseObj.md).[constructor](ue_ue.EditorAnimBaseObj.md#constructor)

## Properties

### AnimSegment

• **AnimSegment**: [`AnimSegment`](ue_ue.AnimSegment.md)

___

### \_\_tid\_EditorAnimBaseObj\_\_

• **\_\_tid\_EditorAnimBaseObj\_\_**: `boolean`

#### Inherited from

[EditorAnimBaseObj](ue_ue.EditorAnimBaseObj.md).[__tid_EditorAnimBaseObj__](ue_ue.EditorAnimBaseObj.md#__tid_editoranimbaseobj__)

___

### \_\_tid\_EditorAnimSegment\_\_

• **\_\_tid\_EditorAnimSegment\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorAnimBaseObj](ue_ue.EditorAnimBaseObj.md).[__tid_Object__](ue_ue.EditorAnimBaseObj.md#__tid_object__)

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

[EditorAnimBaseObj](ue_ue.EditorAnimBaseObj.md).[CreateDefaultSubobject](ue_ue.EditorAnimBaseObj.md#createdefaultsubobject)

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

[EditorAnimBaseObj](ue_ue.EditorAnimBaseObj.md).[ExecuteUbergraph](ue_ue.EditorAnimBaseObj.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorAnimBaseObj](ue_ue.EditorAnimBaseObj.md).[GetClass](ue_ue.EditorAnimBaseObj.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorAnimBaseObj](ue_ue.EditorAnimBaseObj.md).[GetName](ue_ue.EditorAnimBaseObj.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorAnimBaseObj](ue_ue.EditorAnimBaseObj.md).[GetOuter](ue_ue.EditorAnimBaseObj.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditorAnimBaseObj](ue_ue.EditorAnimBaseObj.md).[GetWorld](ue_ue.EditorAnimBaseObj.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorAnimSegment`](ue_ue.EditorAnimSegment.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorAnimSegment`](ue_ue.EditorAnimSegment.md)

#### Overrides

[EditorAnimBaseObj](ue_ue.EditorAnimBaseObj.md).[Find](ue_ue.EditorAnimBaseObj.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorAnimSegment`](ue_ue.EditorAnimSegment.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorAnimSegment`](ue_ue.EditorAnimSegment.md)

#### Overrides

[EditorAnimBaseObj](ue_ue.EditorAnimBaseObj.md).[Load](ue_ue.EditorAnimBaseObj.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorAnimBaseObj](ue_ue.EditorAnimBaseObj.md).[StaticClass](ue_ue.EditorAnimBaseObj.md#staticclass)
