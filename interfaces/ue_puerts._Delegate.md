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

▸ **Bind**(`target`, `methodName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | [`Object`](../classes/ue_ue.Object.md) |
| `methodName` | `string` |

#### Returns

`void`

___

### Execute

▸ **Execute**(`...a`): `ReturnType`<`T`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `...a` | [`ArgumentTypes`](../modules/ue_puerts.md#argumenttypes)<`T`\> |

#### Returns

`ReturnType`<`T`\>

___

### IsBound

▸ **IsBound**(): `boolean`

#### Returns

`boolean`

___

### Unbind

▸ **Unbind**(): `void`

#### Returns

`void`
