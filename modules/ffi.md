[yug_typings](../README.md) / [Modules](../modules.md) / ffi

# Module: ffi

## Table of contents

### Namespaces

- [closure](ffi.closure.md)

### Classes

- [CFunctionPointer](../classes/ffi.CFunctionPointer.md)
- [Closure](../classes/ffi.Closure-1.md)

### Interfaces

- [PointerTypeInfo](../interfaces/ffi.PointerTypeInfo.md)
- [TypeInfo](../interfaces/ffi.TypeInfo.md)

### Type Aliases

- [AnyTypeInfo](ffi.md#anytypeinfo)
- [PrimitiveTypes](ffi.md#primitivetypes)

### Functions

- [binding](ffi.md#binding)
- [makePointer](ffi.md#makepointer)
- [makeStruct](ffi.md#makestruct)
- [typeInfo](ffi.md#typeinfo)

## Type Aliases

### AnyTypeInfo

Ƭ **AnyTypeInfo**: [`PrimitiveTypes`](ffi.md#primitivetypes) \| [`TypeInfo`](../interfaces/ffi.TypeInfo.md)

___

### PrimitiveTypes

Ƭ **PrimitiveTypes**: ``"void"`` \| ``"uint8"`` \| ``"int8"`` \| ``"uint16"`` \| ``"int16"`` \| ``"uint32"`` \| ``"int32"`` \| ``"uint64"`` \| ``"int64"`` \| ``"float"`` \| ``"double"`` \| ``"pointer"`` \| ``"size_t"`` \| ``"cstring"``

## Functions

### binding

▸ **binding**(`funcIndex`, `abi`, `returnType`, `parameterTypes`, `fixArgNum`): `Function`

#### Parameters

| Name | Type |
| :------ | :------ |
| `funcIndex` | `number` |
| `abi` | `number` |
| `returnType` | [`AnyTypeInfo`](ffi.md#anytypeinfo) |
| `parameterTypes` | [`AnyTypeInfo`](ffi.md#anytypeinfo)[] |
| `fixArgNum` | `number` |

#### Returns

`Function`

▸ **binding**(`funcIndex`, `returnType`, `parameterTypes`, `fixArgNum?`): `Function`

#### Parameters

| Name | Type |
| :------ | :------ |
| `funcIndex` | `number` |
| `returnType` | [`AnyTypeInfo`](ffi.md#anytypeinfo) |
| `parameterTypes` | [`AnyTypeInfo`](ffi.md#anytypeinfo)[] |
| `fixArgNum?` | `number` |

#### Returns

`Function`

___

### makePointer

▸ **makePointer**(`info`): [`PointerTypeInfo`](../interfaces/ffi.PointerTypeInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `info` | [`AnyTypeInfo`](ffi.md#anytypeinfo) |

#### Returns

[`PointerTypeInfo`](../interfaces/ffi.PointerTypeInfo.md)

___

### makeStruct

▸ **makeStruct**(`description`): [`TypeInfo`](../interfaces/ffi.TypeInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `description` | `Object` |

#### Returns

[`TypeInfo`](../interfaces/ffi.TypeInfo.md)

___

### typeInfo

▸ **typeInfo**(`info`): [`TypeInfo`](../interfaces/ffi.TypeInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `info` | [`AnyTypeInfo`](ffi.md#anytypeinfo) |

#### Returns

[`TypeInfo`](../interfaces/ffi.TypeInfo.md)
