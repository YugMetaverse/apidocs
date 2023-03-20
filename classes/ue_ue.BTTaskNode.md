[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTTaskNode

# Class: BTTaskNode

[ue/ue](../modules/ue_ue.md).BTTaskNode

## Hierarchy

- [`BTNode`](ue_ue.BTNode.md)

  ↳ **`BTTaskNode`**

  ↳↳ [`BTTask_BlackboardBase`](ue_ue.BTTask_BlackboardBase.md)

  ↳↳ [`BTTask_BlueprintBase`](ue_ue.BTTask_BlueprintBase.md)

  ↳↳ [`BTTask_FinishWithResult`](ue_ue.BTTask_FinishWithResult.md)

  ↳↳ [`BTTask_GameplayTaskBase`](ue_ue.BTTask_GameplayTaskBase.md)

  ↳↳ [`BTTask_MakeNoise`](ue_ue.BTTask_MakeNoise.md)

  ↳↳ [`BTTask_PawnActionBase`](ue_ue.BTTask_PawnActionBase.md)

  ↳↳ [`BTTask_PlayAnimation`](ue_ue.BTTask_PlayAnimation.md)

  ↳↳ [`BTTask_PlaySound`](ue_ue.BTTask_PlaySound.md)

  ↳↳ [`BTTask_RunBehavior`](ue_ue.BTTask_RunBehavior.md)

  ↳↳ [`BTTask_RunBehaviorDynamic`](ue_ue.BTTask_RunBehaviorDynamic.md)

  ↳↳ [`BTTask_SetTagCooldown`](ue_ue.BTTask_SetTagCooldown.md)

  ↳↳ [`BTTask_Wait`](ue_ue.BTTask_Wait.md)

  ↳↳ [`TestBTTask_LatentWithFlags`](ue_ue.TestBTTask_LatentWithFlags.md)

  ↳↳ [`TestBTTask_Log`](ue_ue.TestBTTask_Log.md)

  ↳↳ [`TestBTTask_SetFlag`](ue_ue.TestBTTask_SetFlag.md)

  ↳↳ [`TestBTTask_SetValue`](ue_ue.TestBTTask_SetValue.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BTTaskNode.md#constructor)

### Properties

- [NodeName](ue_ue.BTTaskNode.md#nodename)
- [ParentNode](ue_ue.BTTaskNode.md#parentnode)
- [Services](ue_ue.BTTaskNode.md#services)
- [TreeAsset](ue_ue.BTTaskNode.md#treeasset)
- [\_\_tid\_BTNode\_\_](ue_ue.BTTaskNode.md#__tid_btnode__)
- [\_\_tid\_BTTaskNode\_\_](ue_ue.BTTaskNode.md#__tid_bttasknode__)
- [\_\_tid\_Object\_\_](ue_ue.BTTaskNode.md#__tid_object__)
- [bIgnoreRestartSelf](ue_ue.BTTaskNode.md#bignorerestartself)

### Methods

- [CreateDefaultSubobject](ue_ue.BTTaskNode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTTaskNode.md#executeubergraph)
- [GetClass](ue_ue.BTTaskNode.md#getclass)
- [GetName](ue_ue.BTTaskNode.md#getname)
- [GetOuter](ue_ue.BTTaskNode.md#getouter)
- [GetWorld](ue_ue.BTTaskNode.md#getworld)
- [Find](ue_ue.BTTaskNode.md#find)
- [Load](ue_ue.BTTaskNode.md#load)
- [StaticClass](ue_ue.BTTaskNode.md#staticclass)

## Constructors

### constructor

• **new BTTaskNode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTNode](ue_ue.BTNode.md).[constructor](ue_ue.BTNode.md#constructor)

#### Defined in

[ue/ue.d.ts:14600](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14600)

## Properties

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTNode](ue_ue.BTNode.md).[NodeName](ue_ue.BTNode.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14567)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[ParentNode](ue_ue.BTNode.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14569)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Defined in

[ue/ue.d.ts:14601](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14601)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[TreeAsset](ue_ue.BTNode.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTNode](ue_ue.BTNode.md).[__tid_BTNode__](ue_ue.BTNode.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14574)

___

### \_\_tid\_BTTaskNode\_\_

• **\_\_tid\_BTTaskNode\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14607)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTNode](ue_ue.BTNode.md).[__tid_Object__](ue_ue.BTNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bIgnoreRestartSelf

• **bIgnoreRestartSelf**: `boolean`

#### Defined in

[ue/ue.d.ts:14602](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14602)

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

[BTNode](ue_ue.BTNode.md).[CreateDefaultSubobject](ue_ue.BTNode.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[BTNode](ue_ue.BTNode.md).[ExecuteUbergraph](ue_ue.BTNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[GetClass](ue_ue.BTNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTNode](ue_ue.BTNode.md).[GetName](ue_ue.BTNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[GetOuter](ue_ue.BTNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTNode](ue_ue.BTNode.md).[GetWorld](ue_ue.BTNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTTaskNode`](ue_ue.BTTaskNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTTaskNode`](ue_ue.BTTaskNode.md)

#### Overrides

[BTNode](ue_ue.BTNode.md).[Find](ue_ue.BTNode.md#find)

#### Defined in

[ue/ue.d.ts:14604](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14604)

___

### Load

▸ `Static` **Load**(`InName`): [`BTTaskNode`](ue_ue.BTTaskNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTTaskNode`](ue_ue.BTTaskNode.md)

#### Overrides

[BTNode](ue_ue.BTNode.md).[Load](ue_ue.BTNode.md#load)

#### Defined in

[ue/ue.d.ts:14605](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14605)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTNode](ue_ue.BTNode.md).[StaticClass](ue_ue.BTNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:14603](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14603)