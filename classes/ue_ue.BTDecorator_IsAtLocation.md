[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTDecorator\_IsAtLocation

# Class: BTDecorator\_IsAtLocation

[ue/ue](../modules/ue_ue.md).BTDecorator_IsAtLocation

## Hierarchy

- [`BTDecorator_BlackboardBase`](ue_ue.BTDecorator_BlackboardBase.md)

  ↳ **`BTDecorator_IsAtLocation`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTDecorator_IsAtLocation.md#constructor)

### Properties

- [AcceptableRadius](ue_ue.BTDecorator_IsAtLocation.md#acceptableradius)
- [BlackboardKey](ue_ue.BTDecorator_IsAtLocation.md#blackboardkey)
- [FlowAbortMode](ue_ue.BTDecorator_IsAtLocation.md#flowabortmode)
- [GeometricDistanceType](ue_ue.BTDecorator_IsAtLocation.md#geometricdistancetype)
- [NodeName](ue_ue.BTDecorator_IsAtLocation.md#nodename)
- [ParametrizedAcceptableRadius](ue_ue.BTDecorator_IsAtLocation.md#parametrizedacceptableradius)
- [ParentNode](ue_ue.BTDecorator_IsAtLocation.md#parentnode)
- [TreeAsset](ue_ue.BTDecorator_IsAtLocation.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.BTDecorator_IsAtLocation.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTDecorator\_BlackboardBase\_\_](ue_ue.BTDecorator_IsAtLocation.md#__tid_btdecorator_blackboardbase__)
- [\_\_tid\_BTDecorator\_IsAtLocation\_\_](ue_ue.BTDecorator_IsAtLocation.md#__tid_btdecorator_isatlocation__)
- [\_\_tid\_BTDecorator\_\_](ue_ue.BTDecorator_IsAtLocation.md#__tid_btdecorator__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTDecorator_IsAtLocation.md#__tid_btnode__)
- [\_\_tid\_Object\_\_](ue_ue.BTDecorator_IsAtLocation.md#__tid_object__)
- [bInverseCondition](ue_ue.BTDecorator_IsAtLocation.md#binversecondition)
- [bPathFindingBasedTest](ue_ue.BTDecorator_IsAtLocation.md#bpathfindingbasedtest)
- [bUseNavAgentGoalLocation](ue_ue.BTDecorator_IsAtLocation.md#busenavagentgoallocation)
- [bUseParametrizedRadius](ue_ue.BTDecorator_IsAtLocation.md#buseparametrizedradius)

### Methods

- [CreateDefaultSubobject](ue_ue.BTDecorator_IsAtLocation.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTDecorator_IsAtLocation.md#executeubergraph)
- [GetClass](ue_ue.BTDecorator_IsAtLocation.md#getclass)
- [GetName](ue_ue.BTDecorator_IsAtLocation.md#getname)
- [GetOuter](ue_ue.BTDecorator_IsAtLocation.md#getouter)
- [GetWorld](ue_ue.BTDecorator_IsAtLocation.md#getworld)
- [Find](ue_ue.BTDecorator_IsAtLocation.md#find)
- [Load](ue_ue.BTDecorator_IsAtLocation.md#load)
- [StaticClass](ue_ue.BTDecorator_IsAtLocation.md#staticclass)

## Constructors

### constructor

• **new BTDecorator_IsAtLocation**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[constructor](ue_ue.BTDecorator_BlackboardBase.md#constructor)

## Properties

### AcceptableRadius

• **AcceptableRadius**: `number`

___

### BlackboardKey

• **BlackboardKey**: [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[BlackboardKey](ue_ue.BTDecorator_BlackboardBase.md#blackboardkey)

___

### FlowAbortMode

• **FlowAbortMode**: [`EBTFlowAbortMode`](../enums/ue_ue.EBTFlowAbortMode.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[FlowAbortMode](ue_ue.BTDecorator_BlackboardBase.md#flowabortmode)

___

### GeometricDistanceType

• **GeometricDistanceType**: [`FAIDistanceType`](../enums/ue_ue.FAIDistanceType.md)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[NodeName](ue_ue.BTDecorator_BlackboardBase.md#nodename)

___

### ParametrizedAcceptableRadius

• **ParametrizedAcceptableRadius**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[ParentNode](ue_ue.BTDecorator_BlackboardBase.md#parentnode)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[TreeAsset](ue_ue.BTDecorator_BlackboardBase.md#treeasset)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_BTAuxiliaryNode__](ue_ue.BTDecorator_BlackboardBase.md#__tid_btauxiliarynode__)

___

### \_\_tid\_BTDecorator\_BlackboardBase\_\_

• **\_\_tid\_BTDecorator\_BlackboardBase\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_BTDecorator_BlackboardBase__](ue_ue.BTDecorator_BlackboardBase.md#__tid_btdecorator_blackboardbase__)

___

### \_\_tid\_BTDecorator\_IsAtLocation\_\_

• **\_\_tid\_BTDecorator\_IsAtLocation\_\_**: `boolean`

___

### \_\_tid\_BTDecorator\_\_

• **\_\_tid\_BTDecorator\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_BTDecorator__](ue_ue.BTDecorator_BlackboardBase.md#__tid_btdecorator__)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_BTNode__](ue_ue.BTDecorator_BlackboardBase.md#__tid_btnode__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[__tid_Object__](ue_ue.BTDecorator_BlackboardBase.md#__tid_object__)

___

### bInverseCondition

• **bInverseCondition**: `boolean`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[bInverseCondition](ue_ue.BTDecorator_BlackboardBase.md#binversecondition)

___

### bPathFindingBasedTest

• **bPathFindingBasedTest**: `boolean`

___

### bUseNavAgentGoalLocation

• **bUseNavAgentGoalLocation**: `boolean`

___

### bUseParametrizedRadius

• **bUseParametrizedRadius**: `boolean`

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

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[CreateDefaultSubobject](ue_ue.BTDecorator_BlackboardBase.md#createdefaultsubobject)

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

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[ExecuteUbergraph](ue_ue.BTDecorator_BlackboardBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[GetClass](ue_ue.BTDecorator_BlackboardBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[GetName](ue_ue.BTDecorator_BlackboardBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[GetOuter](ue_ue.BTDecorator_BlackboardBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[GetWorld](ue_ue.BTDecorator_BlackboardBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTDecorator_IsAtLocation`](ue_ue.BTDecorator_IsAtLocation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTDecorator_IsAtLocation`](ue_ue.BTDecorator_IsAtLocation.md)

#### Overrides

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[Find](ue_ue.BTDecorator_BlackboardBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTDecorator_IsAtLocation`](ue_ue.BTDecorator_IsAtLocation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTDecorator_IsAtLocation`](ue_ue.BTDecorator_IsAtLocation.md)

#### Overrides

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[Load](ue_ue.BTDecorator_BlackboardBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTDecorator_BlackboardBase](ue_ue.BTDecorator_BlackboardBase.md).[StaticClass](ue_ue.BTDecorator_BlackboardBase.md#staticclass)
