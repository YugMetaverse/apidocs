[yug_typings](../README.md) / [Modules](../modules.md) / [ffi](../modules/ffi.md) / TypeInfo

# Interface: TypeInfo

[ffi](../modules/ffi.md).TypeInfo

## Hierarchy

- **`TypeInfo`**

  ↳ [`PointerTypeInfo`](ffi.PointerTypeInfo.md)

## Table of contents

### Constructors

- [constructor](ffi.TypeInfo.md#constructor)

### Properties

- [size](ffi.TypeInfo.md#size)

### Methods

- [alloc](ffi.TypeInfo.md#alloc)
- [get](ffi.TypeInfo.md#get)
- [read](ffi.TypeInfo.md#read)
- [set](ffi.TypeInfo.md#set)
- [write](ffi.TypeInfo.md#write)

## Constructors

### constructor

• **new TypeInfo**(`...args`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `any`[] |

#### Defined in

[ffi/index.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ffi/index.d.ts#L13)

## Properties

### size

• **size**: `number`

#### Defined in

[ffi/index.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ffi/index.d.ts#L15)

## Methods

### alloc

▸ **alloc**(`...data`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...data` | `any`[] |

#### Returns

`Uint8Array`

#### Defined in

[ffi/index.d.ts:17](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ffi/index.d.ts#L17)

___

### get

▸ **get**(`pointer`, `index`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pointer` | `Uint8Array` |
| `index` | `number` |

#### Returns

`any`

#### Defined in

[ffi/index.d.ts:23](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ffi/index.d.ts#L23)

___

### read

▸ **read**(`pointer`, `offset?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pointer` | `Uint8Array` |
| `offset?` | `number` |

#### Returns

`any`

#### Defined in

[ffi/index.d.ts:19](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ffi/index.d.ts#L19)

___

### set

▸ **set**(`pointer`, `val`, `index`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pointer` | `Uint8Array` |
| `val` | `any` |
| `index` | `number` |

#### Returns

`any`

#### Defined in

[ffi/index.d.ts:25](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ffi/index.d.ts#L25)

___

### write

▸ **write**(`pointer`, `val`, `offset?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `pointer` | `Uint8Array` |
| `val` | `any` |
| `offset?` | `number` |

#### Returns

`number`

#### Defined in

[ffi/index.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ffi/index.d.ts#L21)
