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

#### Defined in

[ue/ue_s.d.ts:5](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L5)

• **new Guid**(`InA`, `InB`, `InC`, `InD`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InA` | `number` |
| `InB` | `number` |
| `InC` | `number` |
| `InD` | `number` |

#### Defined in

[ue/ue_s.d.ts:6](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L6)

## Properties

### A

• **A**: `number`

#### Defined in

[ue/ue_s.d.ts:7](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L7)

___

### B

• **B**: `number`

#### Defined in

[ue/ue_s.d.ts:8](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L8)

___

### C

• **C**: `number`

#### Defined in

[ue/ue_s.d.ts:9](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L9)

___

### D

• **D**: `number`

#### Defined in

[ue/ue_s.d.ts:10](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L10)

___

### \_\_tid\_Guid\_\_

• `Private` **\_\_tid\_Guid\_\_**: `boolean`

#### Defined in

[ue/ue_s.d.ts:27](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L27)

## Methods

### Invalidate

▸ **Invalidate**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L13)

___

### IsValid

▸ **IsValid**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L14)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L15)

▸ **ToString**(`Format`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Format` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L16)

___

### get\_Item

▸ **get_Item**(`Index`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L12)

___

### set\_Item

▸ **set_Item**(`Index`): [`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Defined in

[ue/ue_s.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L11)

___

### NewGuid

▸ `Static` **NewGuid**(): [`Guid`](ue_ue_s.Guid.md)

#### Returns

[`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue_s.d.ts:17](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L17)

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

#### Defined in

[ue/ue_s.d.ts:18](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L18)

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

#### Defined in

[ue/ue_s.d.ts:19](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L19)

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:24](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L24)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:25](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L25)
