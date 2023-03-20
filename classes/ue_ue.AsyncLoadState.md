[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AsyncLoadState

# Class: AsyncLoadState

[ue/ue](../modules/ue_ue.md).AsyncLoadState

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AsyncLoadState`**

## Table of contents

### Constructors

- [constructor](ue_ue.AsyncLoadState.md#constructor)

### Properties

- [LoadedCallback](ue_ue.AsyncLoadState.md#loadedcallback)
- [\_\_tid\_AsyncLoadState\_\_](ue_ue.AsyncLoadState.md#__tid_asyncloadstate__)
- [\_\_tid\_Object\_\_](ue_ue.AsyncLoadState.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AsyncLoadState.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AsyncLoadState.md#executeubergraph)
- [GetClass](ue_ue.AsyncLoadState.md#getclass)
- [GetName](ue_ue.AsyncLoadState.md#getname)
- [GetOuter](ue_ue.AsyncLoadState.md#getouter)
- [GetWorld](ue_ue.AsyncLoadState.md#getworld)
- [StartLoad](ue_ue.AsyncLoadState.md#startload)
- [Find](ue_ue.AsyncLoadState.md#find)
- [Load](ue_ue.AsyncLoadState.md#load)
- [StaticClass](ue_ue.AsyncLoadState.md#staticclass)

## Constructors

### constructor

• **new AsyncLoadState**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:22136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22136)

## Properties

### LoadedCallback

• **LoadedCallback**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Obj`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:22137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22137)

___

### \_\_tid\_AsyncLoadState\_\_

• **\_\_tid\_AsyncLoadState\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22143)

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

### StartLoad

▸ **StartLoad**(`InPath`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPath` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22138)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AsyncLoadState`](ue_ue.AsyncLoadState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AsyncLoadState`](ue_ue.AsyncLoadState.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:22140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22140)

___

### Load

▸ `Static` **Load**(`InName`): [`AsyncLoadState`](ue_ue.AsyncLoadState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AsyncLoadState`](ue_ue.AsyncLoadState.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:22141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22141)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:22139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22139)
