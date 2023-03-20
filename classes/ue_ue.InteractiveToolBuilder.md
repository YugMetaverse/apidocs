[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InteractiveToolBuilder

# Class: InteractiveToolBuilder

[ue/ue](../modules/ue_ue.md).InteractiveToolBuilder

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InteractiveToolBuilder`**

  ↳↳ [`ClickDragToolBuilder`](ue_ue.ClickDragToolBuilder.md)

  ↳↳ [`MeshSurfacePointToolBuilder`](ue_ue.MeshSurfacePointToolBuilder.md)

  ↳↳ [`SingleClickToolBuilder`](ue_ue.SingleClickToolBuilder.md)

## Table of contents

### Constructors

- [constructor](ue_ue.InteractiveToolBuilder.md#constructor)

### Properties

- [\_\_tid\_InteractiveToolBuilder\_\_](ue_ue.InteractiveToolBuilder.md#__tid_interactivetoolbuilder__)
- [\_\_tid\_Object\_\_](ue_ue.InteractiveToolBuilder.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.InteractiveToolBuilder.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InteractiveToolBuilder.md#executeubergraph)
- [GetClass](ue_ue.InteractiveToolBuilder.md#getclass)
- [GetName](ue_ue.InteractiveToolBuilder.md#getname)
- [GetOuter](ue_ue.InteractiveToolBuilder.md#getouter)
- [GetWorld](ue_ue.InteractiveToolBuilder.md#getworld)
- [Find](ue_ue.InteractiveToolBuilder.md#find)
- [Load](ue_ue.InteractiveToolBuilder.md#load)
- [StaticClass](ue_ue.InteractiveToolBuilder.md#staticclass)

## Constructors

### constructor

• **new InteractiveToolBuilder**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:27500](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27500)

## Properties

### \_\_tid\_InteractiveToolBuilder\_\_

• **\_\_tid\_InteractiveToolBuilder\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:27505](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27505)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InteractiveToolBuilder`](ue_ue.InteractiveToolBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InteractiveToolBuilder`](ue_ue.InteractiveToolBuilder.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:27502](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27502)

___

### Load

▸ `Static` **Load**(`InName`): [`InteractiveToolBuilder`](ue_ue.InteractiveToolBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InteractiveToolBuilder`](ue_ue.InteractiveToolBuilder.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:27503](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27503)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:27501](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27501)
