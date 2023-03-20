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

#### Defined in

[ffi/index.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ffi/index.d.ts#L13)

## Properties

### size

• **size**: `number`

#### Inherited from

[TypeInfo](ffi.TypeInfo.md).[size](ffi.TypeInfo.md#size)

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

#### Inherited from

[TypeInfo](ffi.TypeInfo.md).[alloc](ffi.TypeInfo.md#alloc)

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

#### Inherited from

[TypeInfo](ffi.TypeInfo.md).[get](ffi.TypeInfo.md#get)

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

#### Inherited from

[TypeInfo](ffi.TypeInfo.md).[read](ffi.TypeInfo.md#read)

#### Defined in

[ffi/index.d.ts:19](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ffi/index.d.ts#L19)

___

### ref

▸ **ref**(`val`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `any` |

#### Returns

`Uint8Array`

#### Defined in

[ffi/index.d.ts:29](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ffi/index.d.ts#L29)

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

#### Defined in

[ffi/index.d.ts:25](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ffi/index.d.ts#L25)

___

### unref

▸ **unref**(`buff`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `buff` | `Uint8Array` |

#### Returns

`any`

#### Defined in

[ffi/index.d.ts:30](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ffi/index.d.ts#L30)

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

#### Defined in

[ffi/index.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ffi/index.d.ts#L21)
