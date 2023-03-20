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

#### Defined in

[cpp/index.d.ts:26](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L26)

• **new TestClass**()

#### Overrides

BaseClass.constructor

#### Defined in

[cpp/index.d.ts:27](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L27)

## Properties

### X

• **X**: `number`

#### Defined in

[cpp/index.d.ts:28](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L28)

___

### Y

• **Y**: `number`

#### Defined in

[cpp/index.d.ts:29](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L29)

___

### StaticInt

▪ `Static` **StaticInt**: `number`

#### Defined in

[cpp/index.d.ts:30](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L30)

___

### Ten

▪ `Static` `Readonly` **Ten**: `number`

#### Defined in

[cpp/index.d.ts:31](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L31)

## Methods

### CStr

▸ **CStr**(`p0`): [`cstring`](../modules/puerts.md#cstring)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`cstring`](../modules/puerts.md#cstring) |

#### Returns

[`cstring`](../modules/puerts.md#cstring)

#### Defined in

[cpp/index.d.ts:43](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L43)

___

### ConstRef

▸ **ConstRef**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `number` |

#### Returns

`void`

#### Defined in

[cpp/index.d.ts:45](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L45)

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

#### Defined in

[cpp/index.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L14)

___

### GetSelf

▸ **GetSelf**(): [`TestClass`](cpp.TestClass.md)

#### Returns

[`TestClass`](cpp.TestClass.md)

#### Defined in

[cpp/index.d.ts:38](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L38)

___

### NoEmptyRef

▸ **NoEmptyRef**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`$Ref`](../interfaces/puerts._Ref.md)<[`NoDeleteClass`](cpp.NoDeleteClass.md)\> |

#### Returns

`void`

#### Defined in

[cpp/index.d.ts:39](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L39)

___

### OverloadMethod

▸ **OverloadMethod**(): `number`

#### Returns

`number`

#### Defined in

[cpp/index.d.ts:46](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L46)

▸ **OverloadMethod**(`p0`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `number` |

#### Returns

`number`

#### Defined in

[cpp/index.d.ts:47](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L47)

▸ **OverloadMethod**(`p0`): `bigint`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `bigint` |

#### Returns

`bigint`

#### Defined in

[cpp/index.d.ts:48](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L48)

___

### Ptr

▸ **Ptr**(`p0`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`number`

#### Defined in

[cpp/index.d.ts:42](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L42)

___

### Ref

▸ **Ref**(`p0`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`number`

#### Defined in

[cpp/index.d.ts:40](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L40)

___

### StrPtr

▸ **StrPtr**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

#### Defined in

[cpp/index.d.ts:44](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L44)

___

### StrRef

▸ **StrRef**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

#### Defined in

[cpp/index.d.ts:41](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L41)

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

#### Defined in

[cpp/index.d.ts:32](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L32)

___

### Overload

▸ `Static` **Overload**(): `void`

#### Returns

`void`

#### Defined in

[cpp/index.d.ts:34](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L34)

▸ `Static` **Overload**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `number` |

#### Returns

`void`

#### Defined in

[cpp/index.d.ts:35](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L35)

▸ `Static` **Overload**(`p0`, `p1`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `number` |
| `p1` | `number` |

#### Returns

`void`

#### Defined in

[cpp/index.d.ts:36](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L36)

▸ `Static` **Overload**(`p0`, `p1`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | `number` |

#### Returns

`void`

#### Defined in

[cpp/index.d.ts:37](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L37)

___

### PrintInfo

▸ `Static` **PrintInfo**(`p0`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`TestClass`](cpp.TestClass.md) |

#### Returns

`void`

#### Defined in

[cpp/index.d.ts:33](https://github.com/YugMetaverse/yug_typings/blob/25cad34/cpp/index.d.ts#L33)
