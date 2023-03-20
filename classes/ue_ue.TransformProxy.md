[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TransformProxy

# Class: TransformProxy

[ue/ue](../modules/ue_ue.md).TransformProxy

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`TransformProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.TransformProxy.md#constructor)

### Properties

- [InitialSharedTransform](ue_ue.TransformProxy.md#initialsharedtransform)
- [SharedTransform](ue_ue.TransformProxy.md#sharedtransform)
- [\_\_tid\_Object\_\_](ue_ue.TransformProxy.md#__tid_object__)
- [\_\_tid\_TransformProxy\_\_](ue_ue.TransformProxy.md#__tid_transformproxy__)
- [bRotatePerObject](ue_ue.TransformProxy.md#brotateperobject)
- [bSetPivotMode](ue_ue.TransformProxy.md#bsetpivotmode)

### Methods

- [CreateDefaultSubobject](ue_ue.TransformProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TransformProxy.md#executeubergraph)
- [GetClass](ue_ue.TransformProxy.md#getclass)
- [GetName](ue_ue.TransformProxy.md#getname)
- [GetOuter](ue_ue.TransformProxy.md#getouter)
- [GetWorld](ue_ue.TransformProxy.md#getworld)
- [Find](ue_ue.TransformProxy.md#find)
- [Load](ue_ue.TransformProxy.md#load)
- [StaticClass](ue_ue.TransformProxy.md#staticclass)

## Constructors

### constructor

• **new TransformProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:38187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38187)

## Properties

### InitialSharedTransform

• **InitialSharedTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:38191](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38191)

___

### SharedTransform

• **SharedTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:38190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38190)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_TransformProxy\_\_

• **\_\_tid\_TransformProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:38196](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38196)

___

### bRotatePerObject

• **bRotatePerObject**: `boolean`

#### Defined in

[ue/ue.d.ts:38188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38188)

___

### bSetPivotMode

• **bSetPivotMode**: `boolean`

#### Defined in

[ue/ue.d.ts:38189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38189)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TransformProxy`](ue_ue.TransformProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TransformProxy`](ue_ue.TransformProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:38193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38193)

___

### Load

▸ `Static` **Load**(`InName`): [`TransformProxy`](ue_ue.TransformProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TransformProxy`](ue_ue.TransformProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:38194](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38194)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:38192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38192)