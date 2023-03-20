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

## Properties

### size

• **size**: `number`

## Methods

### alloc

▸ **alloc**(`...data`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...data` | `any`[] |

#### Returns

`Uint8Array`

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
