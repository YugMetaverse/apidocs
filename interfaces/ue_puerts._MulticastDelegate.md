[yug_typings](../README.md) / [Modules](../modules.md) / [ue/puerts](../modules/ue_puerts.md) / $MulticastDelegate

# Interface: $MulticastDelegate<T\>

[ue/puerts](../modules/ue_puerts.md).$MulticastDelegate

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends (...`args`: `any`) => `any` |

## Table of contents

### Methods

- [Add](ue_puerts._MulticastDelegate.md#add)
- [Broadcast](ue_puerts._MulticastDelegate.md#broadcast)
- [Clear](ue_puerts._MulticastDelegate.md#clear)
- [Remove](ue_puerts._MulticastDelegate.md#remove)

## Methods

### Add

▸ **Add**(`fn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `fn` | `T` |

#### Returns

`void`

▸ **Add**(`target`, `methodName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | [`Object`](../classes/ue_ue.Object.md) |
| `methodName` | `string` |

#### Returns

`void`

___

### Broadcast

▸ **Broadcast**(`...a`): `ReturnType`<`T`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `...a` | [`ArgumentTypes`](../modules/ue_puerts.md#argumenttypes)<`T`\> |

#### Returns

`ReturnType`<`T`\>

___

### Clear

▸ **Clear**(): `void`

#### Returns

`void`

___

### Remove

▸ **Remove**(`fn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `fn` | `T` |

#### Returns

`void`
