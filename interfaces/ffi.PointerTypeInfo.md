[yug_typings](../README.md) / [Modules](../modules.md) / [ffi](../modules/ffi.md) / PointerTypeInfo

# Interface: PointerTypeInfo

[ffi](../modules/ffi.md).PointerTypeInfo

## Hierarchy

- [`TypeInfo`](ffi.TypeInfo.md)

  ↳ **`PointerTypeInfo`**

## Table of contents

### Constructors

- [constructor](ffi.PointerTypeInfo.md#constructor)

### Properties

- [size](ffi.PointerTypeInfo.md#size)

### Methods

- [alloc](ffi.PointerTypeInfo.md#alloc)
- [get](ffi.PointerTypeInfo.md#get)
- [read](ffi.PointerTypeInfo.md#read)
- [ref](ffi.PointerTypeInfo.md#ref)
- [set](ffi.PointerTypeInfo.md#set)
- [unref](ffi.PointerTypeInfo.md#unref)
- [write](ffi.PointerTypeInfo.md#write)

## Constructors

### constructor

• **new PointerTypeInfo**(`...args`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `any`[] |

#### Inherited from

[TypeInfo](ffi.TypeInfo.md).[constructor](ffi.TypeInfo.md#constructor)

## Properties

### size

• **size**: `number`

#### Inherited from

[TypeInfo](ffi.TypeInfo.md).[size](ffi.TypeInfo.md#size)

## Methods

### alloc

▸ **alloc**(`...data`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...data` | `any`[] |

#### Returns

`Uint8Array`

#### Inherited from

[TypeInfo](ffi.TypeInfo.md).[alloc](ffi.TypeInfo.md#alloc)

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

#### Inherited from

[TypeInfo](ffi.TypeInfo.md).[get](ffi.TypeInfo.md#get)

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

#### Inherited from

[TypeInfo](ffi.TypeInfo.md).[read](ffi.TypeInfo.md#read)

___

### ref

▸ **ref**(`val`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `any` |

#### Returns

`Uint8Array`

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

#### Inherited from

[TypeInfo](ffi.TypeInfo.md).[set](ffi.TypeInfo.md#set)

___

### unref

▸ **unref**(`buff`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `buff` | `Uint8Array` |

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

#### Inherited from

[TypeInfo](ffi.TypeInfo.md).[write](ffi.TypeInfo.md#write)
