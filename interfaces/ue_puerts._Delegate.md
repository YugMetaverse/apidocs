[yug_typings](../README.md) / [Modules](../modules.md) / [ue/puerts](../modules/ue_puerts.md) / $Delegate

# Interface: $Delegate<T\>

[ue/puerts](../modules/ue_puerts.md).$Delegate

## Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends (...`args`: `any`) => `any` |

## Table of contents

### Methods

- [Bind](ue_puerts._Delegate.md#bind)
- [Execute](ue_puerts._Delegate.md#execute)
- [IsBound](ue_puerts._Delegate.md#isbound)
- [Unbind](ue_puerts._Delegate.md#unbind)

## Methods

### Bind

▸ **Bind**(`fn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `fn` | `T` |

#### Returns

`void`

#### Defined in

[ue/puerts.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/puerts.d.ts#L14)

▸ **Bind**(`target`, `methodName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | [`Object`](../classes/ue_ue.Object.md) |
| `methodName` | `string` |

#### Returns

`void`

#### Defined in

[ue/puerts.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/puerts.d.ts#L15)

___

### Execute

▸ **Execute**(`...a`): `ReturnType`<`T`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `...a` | [`ArgumentTypes`](../modules/ue_puerts.md#argumenttypes)<`T`\> |

#### Returns

`ReturnType`<`T`\>

#### Defined in

[ue/puerts.d.ts:18](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/puerts.d.ts#L18)

___

### IsBound

▸ **IsBound**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/puerts.d.ts:17](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/puerts.d.ts#L17)

___

### Unbind

▸ **Unbind**(): `void`

#### Returns

`void`

#### Defined in

[ue/puerts.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/puerts.d.ts#L16)
