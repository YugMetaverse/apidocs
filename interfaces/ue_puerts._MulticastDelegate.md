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

#### Defined in

[ue/puerts.d.ts:22](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/puerts.d.ts#L22)

▸ **Add**(`target`, `methodName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | [`Object`](../classes/ue_ue.Object.md) |
| `methodName` | `string` |

#### Returns

`void`

#### Defined in

[ue/puerts.d.ts:23](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/puerts.d.ts#L23)

___

### Broadcast

▸ **Broadcast**(`...a`): `ReturnType`<`T`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `...a` | [`ArgumentTypes`](../modules/ue_puerts.md#argumenttypes)<`T`\> |

#### Returns

`ReturnType`<`T`\>

#### Defined in

[ue/puerts.d.ts:25](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/puerts.d.ts#L25)

___

### Clear

▸ **Clear**(): `void`

#### Returns

`void`

#### Defined in

[ue/puerts.d.ts:26](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/puerts.d.ts#L26)

___

### Remove

▸ **Remove**(`fn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `fn` | `T` |

#### Returns

`void`

#### Defined in

[ue/puerts.d.ts:24](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/puerts.d.ts#L24)
