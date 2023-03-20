[yug_typings](../README.md) / [Modules](../modules.md) / [ue/puerts\_decorators](ue_puerts_decorators.md) / rpc

# Namespace: rpc

[ue/puerts_decorators](ue_puerts_decorators.md).rpc

## Table of contents

### Enumerations

- [ELifetimeCondition](../enums/ue_puerts_decorators.rpc.ELifetimeCondition.md)
- [FunctionFlags](../enums/ue_puerts_decorators.rpc.FunctionFlags.md)
- [PropertyFlags](../enums/ue_puerts_decorators.rpc.PropertyFlags.md)

### Functions

- [condition](ue_puerts_decorators.rpc.md#condition)
- [flags](ue_puerts_decorators.rpc.md#flags)

## Functions

### condition

▸ **condition**(`f`): (`target`: [`Object`](../classes/ue_ue.Object.md), `propertyKey`: `string`) => `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `f` | [`ELifetimeCondition`](../enums/ue_puerts_decorators.rpc.ELifetimeCondition.md) |

#### Returns

`fn`

▸ (`target`, `propertyKey`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `target` | [`Object`](../classes/ue_ue.Object.md) |
| `propertyKey` | `string` |

##### Returns

`void`

___

### flags

▸ **flags**(`f`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `f` | [`FunctionFlags`](../enums/ue_puerts_decorators.rpc.FunctionFlags.md) \| [`PropertyFlags`](../enums/ue_puerts_decorators.rpc.PropertyFlags.md) |

#### Returns

`any`
