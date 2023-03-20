[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_s](../modules/ue_ue_s.md) / Guid

# Class: Guid

[ue/ue_s](../modules/ue_ue_s.md).Guid

## Table of contents

### Constructors

- [constructor](ue_ue_s.Guid.md#constructor)

### Properties

- [A](ue_ue_s.Guid.md#a)
- [B](ue_ue_s.Guid.md#b)
- [C](ue_ue_s.Guid.md#c)
- [D](ue_ue_s.Guid.md#d)
- [\_\_tid\_Guid\_\_](ue_ue_s.Guid.md#__tid_guid__)

### Methods

- [Invalidate](ue_ue_s.Guid.md#invalidate)
- [IsValid](ue_ue_s.Guid.md#isvalid)
- [ToString](ue_ue_s.Guid.md#tostring)
- [get\_Item](ue_ue_s.Guid.md#get_item)
- [set\_Item](ue_ue_s.Guid.md#set_item)
- [NewGuid](ue_ue_s.Guid.md#newguid)
- [Parse](ue_ue_s.Guid.md#parse)
- [ParseExact](ue_ue_s.Guid.md#parseexact)
- [StaticClass](ue_ue_s.Guid.md#staticclass)
- [StaticStruct](ue_ue_s.Guid.md#staticstruct)

## Constructors

### constructor

• **new Guid**()

• **new Guid**(`InA`, `InB`, `InC`, `InD`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InA` | `number` |
| `InB` | `number` |
| `InC` | `number` |
| `InD` | `number` |

## Properties

### A

• **A**: `number`

___

### B

• **B**: `number`

___

### C

• **C**: `number`

___

### D

• **D**: `number`

___

### \_\_tid\_Guid\_\_

• `Private` **\_\_tid\_Guid\_\_**: `boolean`

## Methods

### Invalidate

▸ **Invalidate**(): `void`

#### Returns

`void`

___

### IsValid

▸ **IsValid**(): `boolean`

#### Returns

`boolean`

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

▸ **ToString**(`Format`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Format` | `number` |

#### Returns

`string`

___

### get\_Item

▸ **get_Item**(`Index`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`number`

___

### set\_Item

▸ **set_Item**(`Index`): [`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

___

### NewGuid

▸ `Static` **NewGuid**(): [`Guid`](ue_ue_s.Guid.md)

#### Returns

[`Guid`](ue_ue_s.Guid.md)

___

### Parse

▸ `Static` **Parse**(`GuidString`, `OutGuid`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GuidString` | `string` |
| `OutGuid` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Guid`](ue_ue_s.Guid.md)\> |

#### Returns

`boolean`

___

### ParseExact

▸ `Static` **ParseExact**(`GuidString`, `Format`, `OutGuid`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GuidString` | `string` |
| `Format` | `number` |
| `OutGuid` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Guid`](ue_ue_s.Guid.md)\> |

#### Returns

`boolean`

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
