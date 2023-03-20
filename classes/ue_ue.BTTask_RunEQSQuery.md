[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTTask\_RunEQSQuery

# Class: BTTask\_RunEQSQuery

[ue/ue](../modules/ue_ue.md).BTTask_RunEQSQuery

## Hierarchy

- [`BTTask_BlackboardBase`](ue_ue.BTTask_BlackboardBase.md)

  ↳ **`BTTask_RunEQSQuery`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTTask_RunEQSQuery.md#constructor)

### Properties

- [BlackboardKey](ue_ue.BTTask_RunEQSQuery.md#blackboardkey)
- [EQSQueryBlackboardKey](ue_ue.BTTask_RunEQSQuery.md#eqsqueryblackboardkey)
- [EQSRequest](ue_ue.BTTask_RunEQSQuery.md#eqsrequest)
- [NodeName](ue_ue.BTTask_RunEQSQuery.md#nodename)
- [ParentNode](ue_ue.BTTask_RunEQSQuery.md#parentnode)
- [QueryConfig](ue_ue.BTTask_RunEQSQuery.md#queryconfig)
- [QueryParams](ue_ue.BTTask_RunEQSQuery.md#queryparams)
- [QueryTemplate](ue_ue.BTTask_RunEQSQuery.md#querytemplate)
- [RunMode](ue_ue.BTTask_RunEQSQuery.md#runmode)
- [Services](ue_ue.BTTask_RunEQSQuery.md#services)
- [TreeAsset](ue_ue.BTTask_RunEQSQuery.md#treeasset)
- [\_\_tid\_BTNode\_\_](ue_ue.BTTask_RunEQSQuery.md#__tid_btnode__)
- [\_\_tid\_BTTaskNode\_\_](ue_ue.BTTask_RunEQSQuery.md#__tid_bttasknode__)
- [\_\_tid\_BTTask\_BlackboardBase\_\_](ue_ue.BTTask_RunEQSQuery.md#__tid_bttask_blackboardbase__)
- [\_\_tid\_BTTask\_RunEQSQuery\_\_](ue_ue.BTTask_RunEQSQuery.md#__tid_bttask_runeqsquery__)
- [\_\_tid\_Object\_\_](ue_ue.BTTask_RunEQSQuery.md#__tid_object__)
- [bIgnoreRestartSelf](ue_ue.BTTask_RunEQSQuery.md#bignorerestartself)
- [bUseBBKey](ue_ue.BTTask_RunEQSQuery.md#busebbkey)

### Methods

- [CreateDefaultSubobject](ue_ue.BTTask_RunEQSQuery.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTTask_RunEQSQuery.md#executeubergraph)
- [GetClass](ue_ue.BTTask_RunEQSQuery.md#getclass)
- [GetName](ue_ue.BTTask_RunEQSQuery.md#getname)
- [GetOuter](ue_ue.BTTask_RunEQSQuery.md#getouter)
- [GetWorld](ue_ue.BTTask_RunEQSQuery.md#getworld)
- [Find](ue_ue.BTTask_RunEQSQuery.md#find)
- [Load](ue_ue.BTTask_RunEQSQuery.md#load)
- [StaticClass](ue_ue.BTTask_RunEQSQuery.md#staticclass)

## Constructors

### constructor

• **new BTTask_RunEQSQuery**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[constructor](ue_ue.BTTask_BlackboardBase.md#constructor)

#### Defined in

[ue/ue.d.ts:25420](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25420)

## Properties

### BlackboardKey

• **BlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[BlackboardKey](ue_ue.BTTask_BlackboardBase.md#blackboardkey)

#### Defined in

[ue/ue.d.ts:25222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25222)

___

### EQSQueryBlackboardKey

• **EQSQueryBlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

#### Defined in

[ue/ue.d.ts:25425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25425)

___

### EQSRequest

• **EQSRequest**: [`EQSParametrizedQueryExecutionRequest`](ue_ue.EQSParametrizedQueryExecutionRequest.md)

#### Defined in

[ue/ue.d.ts:25427](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25427)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[NodeName](ue_ue.BTTask_BlackboardBase.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14567)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[ParentNode](ue_ue.BTTask_BlackboardBase.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14569)

___

### QueryConfig

• **QueryConfig**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIDynamicParam`](ue_ue.AIDynamicParam.md)\>

#### Defined in

[ue/ue.d.ts:25423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25423)

___

### QueryParams

• **QueryParams**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EnvNamedValue`](ue_ue.EnvNamedValue.md)\>

#### Defined in

[ue/ue.d.ts:25422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25422)

___

### QueryTemplate

• **QueryTemplate**: [`EnvQuery`](ue_ue.EnvQuery.md)

#### Defined in

[ue/ue.d.ts:25421](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25421)

___

### RunMode

• **RunMode**: [`EEnvQueryRunMode`](../enums/ue_ue.EEnvQueryRunMode.md)

#### Defined in

[ue/ue.d.ts:25424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25424)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[Services](ue_ue.BTTask_BlackboardBase.md#services)

#### Defined in

[ue/ue.d.ts:14601](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14601)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[TreeAsset](ue_ue.BTTask_BlackboardBase.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[__tid_BTNode__](ue_ue.BTTask_BlackboardBase.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14574)

___

### \_\_tid\_BTTaskNode\_\_

• **\_\_tid\_BTTaskNode\_\_**: `boolean`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[__tid_BTTaskNode__](ue_ue.BTTask_BlackboardBase.md#__tid_bttasknode__)

#### Defined in

[ue/ue.d.ts:14607](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14607)

___

### \_\_tid\_BTTask\_BlackboardBase\_\_

• **\_\_tid\_BTTask\_BlackboardBase\_\_**: `boolean`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[__tid_BTTask_BlackboardBase__](ue_ue.BTTask_BlackboardBase.md#__tid_bttask_blackboardbase__)

#### Defined in

[ue/ue.d.ts:25227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25227)

___

### \_\_tid\_BTTask\_RunEQSQuery\_\_

• **\_\_tid\_BTTask\_RunEQSQuery\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:25432](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25432)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[__tid_Object__](ue_ue.BTTask_BlackboardBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bIgnoreRestartSelf

• **bIgnoreRestartSelf**: `boolean`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[bIgnoreRestartSelf](ue_ue.BTTask_BlackboardBase.md#bignorerestartself)

#### Defined in

[ue/ue.d.ts:14602](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14602)

___

### bUseBBKey

• **bUseBBKey**: `boolean`

#### Defined in

[ue/ue.d.ts:25426](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25426)

## Methods

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[CreateDefaultSubobject](ue_ue.BTTask_BlackboardBase.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[ExecuteUbergraph](ue_ue.BTTask_BlackboardBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[GetClass](ue_ue.BTTask_BlackboardBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[GetName](ue_ue.BTTask_BlackboardBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[GetOuter](ue_ue.BTTask_BlackboardBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[GetWorld](ue_ue.BTTask_BlackboardBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTTask_RunEQSQuery`](ue_ue.BTTask_RunEQSQuery.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTTask_RunEQSQuery`](ue_ue.BTTask_RunEQSQuery.md)

#### Overrides

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[Find](ue_ue.BTTask_BlackboardBase.md#find)

#### Defined in

[ue/ue.d.ts:25429](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25429)

___

### Load

▸ `Static` **Load**(`InName`): [`BTTask_RunEQSQuery`](ue_ue.BTTask_RunEQSQuery.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTTask_RunEQSQuery`](ue_ue.BTTask_RunEQSQuery.md)

#### Overrides

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[Load](ue_ue.BTTask_BlackboardBase.md#load)

#### Defined in

[ue/ue.d.ts:25430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25430)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTTask_BlackboardBase](ue_ue.BTTask_BlackboardBase.md).[StaticClass](ue_ue.BTTask_BlackboardBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:25428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25428)
