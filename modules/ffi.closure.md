[yug_typings](../README.md) / [Modules](../modules.md) / [ffi](ffi.md) / closure

# Namespace: closure

[ffi](ffi.md).closure

## Table of contents

### Functions

- [alloc](ffi.closure.md#alloc)
- [free](ffi.closure.md#free)
- [func](ffi.closure.md#func)

## Functions

### alloc

▸ **alloc**(`func`, `abi`, `returnType`, `parameterTypes`): [`Closure`](../classes/ffi.Closure-1.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `func` | `Function` |
| `abi` | `number` |
| `returnType` | [`AnyTypeInfo`](ffi.md#anytypeinfo) |
| `parameterTypes` | [`AnyTypeInfo`](ffi.md#anytypeinfo)[] |

#### Returns

[`Closure`](../classes/ffi.Closure-1.md)

▸ **alloc**(`func`, `returnType`, `parameterTypes`): [`Closure`](../classes/ffi.Closure-1.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `func` | `Function` |
| `returnType` | [`AnyTypeInfo`](ffi.md#anytypeinfo) |
| `parameterTypes` | [`AnyTypeInfo`](ffi.md#anytypeinfo)[] |

#### Returns

[`Closure`](../classes/ffi.Closure-1.md)

___

### free

▸ **free**(`cl`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `cl` | [`Closure`](../classes/ffi.Closure-1.md) |

#### Returns

`void`

___

### func

▸ **func**(`cl`): [`CFunctionPointer`](../classes/ffi.CFunctionPointer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `cl` | [`Closure`](../classes/ffi.Closure-1.md) |

#### Returns

[`CFunctionPointer`](../classes/ffi.CFunctionPointer.md)
