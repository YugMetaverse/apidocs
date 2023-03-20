[yug_typings](../README.md) / [Modules](../modules.md) / [cpp](../modules/cpp.md) / TestClass

# Class: TestClass

[cpp](../modules/cpp.md).TestClass

## Hierarchy

- [`BaseClass`](cpp.BaseClass.md)

  ↳ **`TestClass`**

## Table of contents

### Constructors

- [constructor](cpp.TestClass.md#constructor)

### Properties

- [X](cpp.TestClass.md#x)
- [Y](cpp.TestClass.md#y)
- [StaticInt](cpp.TestClass.md#staticint)
- [Ten](cpp.TestClass.md#ten)

### Methods

- [CStr](cpp.TestClass.md#cstr)
- [ConstRef](cpp.TestClass.md#constref)
- [Foo](cpp.TestClass.md#foo)
- [GetSelf](cpp.TestClass.md#getself)
- [NoEmptyRef](cpp.TestClass.md#noemptyref)
- [OverloadMethod](cpp.TestClass.md#overloadmethod)
- [Ptr](cpp.TestClass.md#ptr)
- [Ref](cpp.TestClass.md#ref)
- [StrPtr](cpp.TestClass.md#strptr)
- [StrRef](cpp.TestClass.md#strref)
- [Add](cpp.TestClass.md#add)
- [Overload](cpp.TestClass.md#overload)
- [PrintInfo](cpp.TestClass.md#printinfo)

## Constructors

### constructor

• **new TestClass**(`p0`, `p1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `number` |
| `p1` | `number` |

#### Overrides

[BaseClass](cpp.BaseClass.md).[constructor](cpp.BaseClass.md#constructor)

• **new TestClass**()

#### Overrides

BaseClass.constructor

## Properties

### X

• **X**: `number`

___

### Y

• **Y**: `number`

___

### StaticInt

▪ `Static` **StaticInt**: `number`

___

### Ten

▪ `Static` `Readonly` **Ten**: `number`

## Methods

### CStr

▸ **CStr**(`p0`): [`cstring`](../modules/puerts.md#cstring)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`cstring`](../modules/puerts.md#cstring) |

#### Returns

[`cstring`](../modules/puerts.md#cstring)

___

### ConstRef

▸ **ConstRef**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `number` |

#### Returns

`void`

___

### Foo

▸ **Foo**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `number` |

#### Returns

`void`

#### Inherited from

[BaseClass](cpp.BaseClass.md).[Foo](cpp.BaseClass.md#foo)

___

### GetSelf

▸ **GetSelf**(): [`TestClass`](cpp.TestClass.md)

#### Returns

[`TestClass`](cpp.TestClass.md)

___

### NoEmptyRef

▸ **NoEmptyRef**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`$Ref`](../interfaces/puerts._Ref.md)<[`NoDeleteClass`](cpp.NoDeleteClass.md)\> |

#### Returns

`void`

___

### OverloadMethod

▸ **OverloadMethod**(): `number`

#### Returns

`number`

▸ **OverloadMethod**(`p0`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `number` |

#### Returns

`number`

▸ **OverloadMethod**(`p0`): `bigint`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `bigint` |

#### Returns

`bigint`

___

### Ptr

▸ **Ptr**(`p0`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`number`

___

### Ref

▸ **Ref**(`p0`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`number`

___

### StrPtr

▸ **StrPtr**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

___

### StrRef

▸ **StrRef**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

___

### Add

▸ `Static` **Add**(`p0`, `p1`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `number` |
| `p1` | `number` |

#### Returns

`number`

___

### Overload

▸ `Static` **Overload**(): `void`

#### Returns

`void`

▸ `Static` **Overload**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `number` |

#### Returns

`void`

▸ `Static` **Overload**(`p0`, `p1`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `number` |
| `p1` | `number` |

#### Returns

`void`

▸ `Static` **Overload**(`p0`, `p1`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | `number` |

#### Returns

`void`

___

### PrintInfo

▸ `Static` **PrintInfo**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`TestClass`](cpp.TestClass.md) |

#### Returns

`void`
