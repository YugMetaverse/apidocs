[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MeshSelectionSet

# Class: MeshSelectionSet

[ue/ue](../modules/ue_ue.md).MeshSelectionSet

## Hierarchy

- [`SelectionSet`](ue_ue.SelectionSet.md)

  ↳ **`MeshSelectionSet`**

## Table of contents

### Constructors

- [constructor](ue_ue.MeshSelectionSet.md#constructor)

### Properties

- [Edges](ue_ue.MeshSelectionSet.md#edges)
- [Faces](ue_ue.MeshSelectionSet.md#faces)
- [Groups](ue_ue.MeshSelectionSet.md#groups)
- [Vertices](ue_ue.MeshSelectionSet.md#vertices)
- [\_\_tid\_MeshSelectionSet\_\_](ue_ue.MeshSelectionSet.md#__tid_meshselectionset__)
- [\_\_tid\_Object\_\_](ue_ue.MeshSelectionSet.md#__tid_object__)
- [\_\_tid\_SelectionSet\_\_](ue_ue.MeshSelectionSet.md#__tid_selectionset__)

### Methods

- [CreateDefaultSubobject](ue_ue.MeshSelectionSet.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MeshSelectionSet.md#executeubergraph)
- [GetClass](ue_ue.MeshSelectionSet.md#getclass)
- [GetName](ue_ue.MeshSelectionSet.md#getname)
- [GetOuter](ue_ue.MeshSelectionSet.md#getouter)
- [GetWorld](ue_ue.MeshSelectionSet.md#getworld)
- [Find](ue_ue.MeshSelectionSet.md#find)
- [Load](ue_ue.MeshSelectionSet.md#load)
- [StaticClass](ue_ue.MeshSelectionSet.md#staticclass)

## Constructors

### constructor

• **new MeshSelectionSet**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SelectionSet](ue_ue.SelectionSet.md).[constructor](ue_ue.SelectionSet.md#constructor)

#### Defined in

[ue/ue.d.ts:50560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50560)

## Properties

### Edges

• **Edges**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:50562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50562)

___

### Faces

• **Faces**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:50563](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50563)

___

### Groups

• **Groups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:50564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50564)

___

### Vertices

• **Vertices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:50561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50561)

___

### \_\_tid\_MeshSelectionSet\_\_

• **\_\_tid\_MeshSelectionSet\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:50569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50569)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SelectionSet](ue_ue.SelectionSet.md).[__tid_Object__](ue_ue.SelectionSet.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SelectionSet\_\_

• **\_\_tid\_SelectionSet\_\_**: `boolean`

#### Inherited from

[SelectionSet](ue_ue.SelectionSet.md).[__tid_SelectionSet__](ue_ue.SelectionSet.md#__tid_selectionset__)

#### Defined in

[ue/ue.d.ts:50556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50556)

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

[SelectionSet](ue_ue.SelectionSet.md).[CreateDefaultSubobject](ue_ue.SelectionSet.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[SelectionSet](ue_ue.SelectionSet.md).[ExecuteUbergraph](ue_ue.SelectionSet.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SelectionSet](ue_ue.SelectionSet.md).[GetClass](ue_ue.SelectionSet.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SelectionSet](ue_ue.SelectionSet.md).[GetName](ue_ue.SelectionSet.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SelectionSet](ue_ue.SelectionSet.md).[GetOuter](ue_ue.SelectionSet.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SelectionSet](ue_ue.SelectionSet.md).[GetWorld](ue_ue.SelectionSet.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MeshSelectionSet`](ue_ue.MeshSelectionSet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MeshSelectionSet`](ue_ue.MeshSelectionSet.md)

#### Overrides

[SelectionSet](ue_ue.SelectionSet.md).[Find](ue_ue.SelectionSet.md#find)

#### Defined in

[ue/ue.d.ts:50566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50566)

___

### Load

▸ `Static` **Load**(`InName`): [`MeshSelectionSet`](ue_ue.MeshSelectionSet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MeshSelectionSet`](ue_ue.MeshSelectionSet.md)

#### Overrides

[SelectionSet](ue_ue.SelectionSet.md).[Load](ue_ue.SelectionSet.md#load)

#### Defined in

[ue/ue.d.ts:50567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50567)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SelectionSet](ue_ue.SelectionSet.md).[StaticClass](ue_ue.SelectionSet.md#staticclass)

#### Defined in

[ue/ue.d.ts:50565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50565)
