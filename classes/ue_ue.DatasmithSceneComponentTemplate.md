[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithSceneComponentTemplate

# Class: DatasmithSceneComponentTemplate

[ue/ue](../modules/ue_ue.md).DatasmithSceneComponentTemplate

## Hierarchy

- [`DatasmithObjectTemplate`](ue_ue.DatasmithObjectTemplate.md)

  ↳ **`DatasmithSceneComponentTemplate`**

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithSceneComponentTemplate.md#constructor)

### Properties

- [AttachParent](ue_ue.DatasmithSceneComponentTemplate.md#attachparent)
- [Mobility](ue_ue.DatasmithSceneComponentTemplate.md#mobility)
- [RelativeTransform](ue_ue.DatasmithSceneComponentTemplate.md#relativetransform)
- [Tags](ue_ue.DatasmithSceneComponentTemplate.md#tags)
- [\_\_tid\_DatasmithObjectTemplate\_\_](ue_ue.DatasmithSceneComponentTemplate.md#__tid_datasmithobjecttemplate__)
- [\_\_tid\_DatasmithSceneComponentTemplate\_\_](ue_ue.DatasmithSceneComponentTemplate.md#__tid_datasmithscenecomponenttemplate__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithSceneComponentTemplate.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithSceneComponentTemplate.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithSceneComponentTemplate.md#executeubergraph)
- [GetClass](ue_ue.DatasmithSceneComponentTemplate.md#getclass)
- [GetName](ue_ue.DatasmithSceneComponentTemplate.md#getname)
- [GetOuter](ue_ue.DatasmithSceneComponentTemplate.md#getouter)
- [GetWorld](ue_ue.DatasmithSceneComponentTemplate.md#getworld)
- [Find](ue_ue.DatasmithSceneComponentTemplate.md#find)
- [Load](ue_ue.DatasmithSceneComponentTemplate.md#load)
- [StaticClass](ue_ue.DatasmithSceneComponentTemplate.md#staticclass)

## Constructors

### constructor

• **new DatasmithSceneComponentTemplate**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[constructor](ue_ue.DatasmithObjectTemplate.md#constructor)

#### Defined in

[ue/ue.d.ts:29980](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29980)

## Properties

### AttachParent

• **AttachParent**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Defined in

[ue/ue.d.ts:29983](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29983)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Defined in

[ue/ue.d.ts:29982](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29982)

___

### RelativeTransform

• **RelativeTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:29981](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29981)

___

### Tags

• **Tags**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`string`\>

#### Defined in

[ue/ue.d.ts:29984](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29984)

___

### \_\_tid\_DatasmithObjectTemplate\_\_

• **\_\_tid\_DatasmithObjectTemplate\_\_**: `boolean`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[__tid_DatasmithObjectTemplate__](ue_ue.DatasmithObjectTemplate.md#__tid_datasmithobjecttemplate__)

#### Defined in

[ue/ue.d.ts:29319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29319)

___

### \_\_tid\_DatasmithSceneComponentTemplate\_\_

• **\_\_tid\_DatasmithSceneComponentTemplate\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:29989](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29989)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[__tid_Object__](ue_ue.DatasmithObjectTemplate.md#__tid_object__)

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

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[CreateDefaultSubobject](ue_ue.DatasmithObjectTemplate.md#createdefaultsubobject)

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

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[ExecuteUbergraph](ue_ue.DatasmithObjectTemplate.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetClass](ue_ue.DatasmithObjectTemplate.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetName](ue_ue.DatasmithObjectTemplate.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetOuter](ue_ue.DatasmithObjectTemplate.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetWorld](ue_ue.DatasmithObjectTemplate.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithSceneComponentTemplate`](ue_ue.DatasmithSceneComponentTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithSceneComponentTemplate`](ue_ue.DatasmithSceneComponentTemplate.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[Find](ue_ue.DatasmithObjectTemplate.md#find)

#### Defined in

[ue/ue.d.ts:29986](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29986)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithSceneComponentTemplate`](ue_ue.DatasmithSceneComponentTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithSceneComponentTemplate`](ue_ue.DatasmithSceneComponentTemplate.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[Load](ue_ue.DatasmithObjectTemplate.md#load)

#### Defined in

[ue/ue.d.ts:29987](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29987)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[StaticClass](ue_ue.DatasmithObjectTemplate.md#staticclass)

#### Defined in

[ue/ue.d.ts:29985](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29985)
