---
id: "TestClass"
title: "Class: TestClass"
sidebar_label: "TestClass"
---

## Hierarchy

- [`BaseClass`](BaseClass.md)

  ↳ **`TestClass`**

## Constructors

### constructor

• **new TestClass**(`p0`, `p1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `number` |
| `p1` | `number` |

#### Overrides

[BaseClass](BaseClass.md).[constructor](BaseClass.md#constructor)

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

▸ **CStr**(`p0`): `cstring`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `cstring` |

#### Returns

`cstring`

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

[BaseClass](BaseClass.md).[Foo](BaseClass.md#foo)

___

### GetSelf

▸ **GetSelf**(): [`TestClass`](TestClass.md)

#### Returns

[`TestClass`](TestClass.md)

___

### NoEmptyRef

▸ **NoEmptyRef**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `$Ref`<[`NoDeleteClass`](NoDeleteClass.md)\> |

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
| `p0` | `$Ref`<`number`\> |

#### Returns

`number`

___

### Ref

▸ **Ref**(`p0`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `$Ref`<`number`\> |

#### Returns

`number`

___

### StrPtr

▸ **StrPtr**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `$Ref`<`string`\> |

#### Returns

`void`

___

### StrRef

▸ **StrRef**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `$Ref`<`string`\> |

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
| `p0` | [`TestClass`](TestClass.md) |

#### Returns

`void`
