[yug_typings](../README.md) / [Modules](../modules.md) / [ue/puerts\_decorators](ue_puerts_decorators.md) / uparam

# Namespace: uparam

[ue/puerts_decorators](ue_puerts_decorators.md).uparam

**`Brief`**

the functionality to add meta data for function parameters

## Table of contents

### Classes

- [ParamKey](../classes/ue_puerts_decorators.uparam.ParamKey.md)

### Variables

- [Const](ue_puerts_decorators.uparam.md#const)
- [DisplayName](ue_puerts_decorators.uparam.md#displayname)
- [NotReplicated](ue_puerts_decorators.uparam.md#notreplicated)
- [Ref](ue_puerts_decorators.uparam.md#ref)

### Functions

- [uparam](ue_puerts_decorators.uparam.md#uparam)

## Variables

### Const

• **Const**: [`ParamKey`](../classes/ue_puerts_decorators.uparam.ParamKey.md)

**`Brief`**

This property is const and should be exported as const

___

### DisplayName

• **DisplayName**: [`ParamKey`](../classes/ue_puerts_decorators.uparam.ParamKey.md)

**`Brief`**

the display name

**`Deprecated`**

no where to add this to pin type

___

### NotReplicated

• **NotReplicated**: [`ParamKey`](../classes/ue_puerts_decorators.uparam.ParamKey.md)

**`Brief`**

Skip replication (only for struct members and parameters in service request functions).

**`Deprecated`**

ServiceRequest/ServiceResponse is not supported

___

### Ref

• **Ref**: [`ParamKey`](../classes/ue_puerts_decorators.uparam.ParamKey.md)

**`Brief`**

Value is copied out after function call. Only valid on function param declaration

## Functions

### uparam

▸ **uparam**(`...InValues`): `any`

decorator to add parameters metadata

#### Parameters

| Name | Type |
| :------ | :------ |
| `...InValues` | [`ParamKey`](../classes/ue_puerts_decorators.uparam.ParamKey.md)[] |

#### Returns

`any`
