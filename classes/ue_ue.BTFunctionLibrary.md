[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTFunctionLibrary

# Class: BTFunctionLibrary

[ue/ue](../modules/ue_ue.md).BTFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`BTFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BTFunctionLibrary\_\_](ue_ue.BTFunctionLibrary.md#__tid_btfunctionlibrary__)
- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.BTFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.BTFunctionLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BTFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.BTFunctionLibrary.md#getclass)
- [GetName](ue_ue.BTFunctionLibrary.md#getname)
- [GetOuter](ue_ue.BTFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.BTFunctionLibrary.md#getworld)
- [ClearBlackboardValue](ue_ue.BTFunctionLibrary.md#clearblackboardvalue)
- [ClearBlackboardValueAsVector](ue_ue.BTFunctionLibrary.md#clearblackboardvalueasvector)
- [Find](ue_ue.BTFunctionLibrary.md#find)
- [GetBlackboardValueAsActor](ue_ue.BTFunctionLibrary.md#getblackboardvalueasactor)
- [GetBlackboardValueAsBool](ue_ue.BTFunctionLibrary.md#getblackboardvalueasbool)
- [GetBlackboardValueAsClass](ue_ue.BTFunctionLibrary.md#getblackboardvalueasclass)
- [GetBlackboardValueAsEnum](ue_ue.BTFunctionLibrary.md#getblackboardvalueasenum)
- [GetBlackboardValueAsFloat](ue_ue.BTFunctionLibrary.md#getblackboardvalueasfloat)
- [GetBlackboardValueAsInt](ue_ue.BTFunctionLibrary.md#getblackboardvalueasint)
- [GetBlackboardValueAsName](ue_ue.BTFunctionLibrary.md#getblackboardvalueasname)
- [GetBlackboardValueAsObject](ue_ue.BTFunctionLibrary.md#getblackboardvalueasobject)
- [GetBlackboardValueAsRotator](ue_ue.BTFunctionLibrary.md#getblackboardvalueasrotator)
- [GetBlackboardValueAsString](ue_ue.BTFunctionLibrary.md#getblackboardvalueasstring)
- [GetBlackboardValueAsVector](ue_ue.BTFunctionLibrary.md#getblackboardvalueasvector)
- [GetOwnerComponent](ue_ue.BTFunctionLibrary.md#getownercomponent)
- [GetOwnersBlackboard](ue_ue.BTFunctionLibrary.md#getownersblackboard)
- [Load](ue_ue.BTFunctionLibrary.md#load)
- [SetBlackboardValueAsBool](ue_ue.BTFunctionLibrary.md#setblackboardvalueasbool)
- [SetBlackboardValueAsClass](ue_ue.BTFunctionLibrary.md#setblackboardvalueasclass)
- [SetBlackboardValueAsEnum](ue_ue.BTFunctionLibrary.md#setblackboardvalueasenum)
- [SetBlackboardValueAsFloat](ue_ue.BTFunctionLibrary.md#setblackboardvalueasfloat)
- [SetBlackboardValueAsInt](ue_ue.BTFunctionLibrary.md#setblackboardvalueasint)
- [SetBlackboardValueAsName](ue_ue.BTFunctionLibrary.md#setblackboardvalueasname)
- [SetBlackboardValueAsObject](ue_ue.BTFunctionLibrary.md#setblackboardvalueasobject)
- [SetBlackboardValueAsRotator](ue_ue.BTFunctionLibrary.md#setblackboardvalueasrotator)
- [SetBlackboardValueAsString](ue_ue.BTFunctionLibrary.md#setblackboardvalueasstring)
- [SetBlackboardValueAsVector](ue_ue.BTFunctionLibrary.md#setblackboardvalueasvector)
- [StartUsingExternalEvent](ue_ue.BTFunctionLibrary.md#startusingexternalevent)
- [StaticClass](ue_ue.BTFunctionLibrary.md#staticclass)
- [StopUsingExternalEvent](ue_ue.BTFunctionLibrary.md#stopusingexternalevent)

## Constructors

### constructor

• **new BTFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_BTFunctionLibrary\_\_

• **\_\_tid\_BTFunctionLibrary\_\_**: `boolean`

___

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### ClearBlackboardValue

▸ `Static` **ClearBlackboardValue**(`NodeOwner`, `Key`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

#### Returns

`void`

___

### ClearBlackboardValueAsVector

▸ `Static` **ClearBlackboardValueAsVector**(`NodeOwner`, `Key`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTFunctionLibrary`](ue_ue.BTFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTFunctionLibrary`](ue_ue.BTFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetBlackboardValueAsActor

▸ `Static` **GetBlackboardValueAsActor**(`NodeOwner`, `Key`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### GetBlackboardValueAsBool

▸ `Static` **GetBlackboardValueAsBool**(`NodeOwner`, `Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

#### Returns

`boolean`

___

### GetBlackboardValueAsClass

▸ `Static` **GetBlackboardValueAsClass**(`NodeOwner`, `Key`): [`Class`](ue_ue.Class.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

#### Returns

[`Class`](ue_ue.Class.md)

___

### GetBlackboardValueAsEnum

▸ `Static` **GetBlackboardValueAsEnum**(`NodeOwner`, `Key`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

#### Returns

`number`

___

### GetBlackboardValueAsFloat

▸ `Static` **GetBlackboardValueAsFloat**(`NodeOwner`, `Key`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

#### Returns

`number`

___

### GetBlackboardValueAsInt

▸ `Static` **GetBlackboardValueAsInt**(`NodeOwner`, `Key`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

#### Returns

`number`

___

### GetBlackboardValueAsName

▸ `Static` **GetBlackboardValueAsName**(`NodeOwner`, `Key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

#### Returns

`string`

___

### GetBlackboardValueAsObject

▸ `Static` **GetBlackboardValueAsObject**(`NodeOwner`, `Key`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

#### Returns

[`Object`](ue_ue.Object.md)

___

### GetBlackboardValueAsRotator

▸ `Static` **GetBlackboardValueAsRotator**(`NodeOwner`, `Key`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### GetBlackboardValueAsString

▸ `Static` **GetBlackboardValueAsString**(`NodeOwner`, `Key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

#### Returns

`string`

___

### GetBlackboardValueAsVector

▸ `Static` **GetBlackboardValueAsVector**(`NodeOwner`, `Key`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetOwnerComponent

▸ `Static` **GetOwnerComponent**(`NodeOwner`): [`BehaviorTreeComponent`](ue_ue.BehaviorTreeComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |

#### Returns

[`BehaviorTreeComponent`](ue_ue.BehaviorTreeComponent.md)

___

### GetOwnersBlackboard

▸ `Static` **GetOwnersBlackboard**(`NodeOwner`): [`BlackboardComponent`](ue_ue.BlackboardComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |

#### Returns

[`BlackboardComponent`](ue_ue.BlackboardComponent.md)

___

### Load

▸ `Static` **Load**(`InName`): [`BTFunctionLibrary`](ue_ue.BTFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTFunctionLibrary`](ue_ue.BTFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### SetBlackboardValueAsBool

▸ `Static` **SetBlackboardValueAsBool**(`NodeOwner`, `Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |
| `Value` | `boolean` |

#### Returns

`void`

___

### SetBlackboardValueAsClass

▸ `Static` **SetBlackboardValueAsClass**(`NodeOwner`, `Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |
| `Value` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

___

### SetBlackboardValueAsEnum

▸ `Static` **SetBlackboardValueAsEnum**(`NodeOwner`, `Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |
| `Value` | `number` |

#### Returns

`void`

___

### SetBlackboardValueAsFloat

▸ `Static` **SetBlackboardValueAsFloat**(`NodeOwner`, `Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |
| `Value` | `number` |

#### Returns

`void`

___

### SetBlackboardValueAsInt

▸ `Static` **SetBlackboardValueAsInt**(`NodeOwner`, `Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |
| `Value` | `number` |

#### Returns

`void`

___

### SetBlackboardValueAsName

▸ `Static` **SetBlackboardValueAsName**(`NodeOwner`, `Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |
| `Value` | `string` |

#### Returns

`void`

___

### SetBlackboardValueAsObject

▸ `Static` **SetBlackboardValueAsObject**(`NodeOwner`, `Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |
| `Value` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### SetBlackboardValueAsRotator

▸ `Static` **SetBlackboardValueAsRotator**(`NodeOwner`, `Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |
| `Value` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

___

### SetBlackboardValueAsString

▸ `Static` **SetBlackboardValueAsString**(`NodeOwner`, `Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |
| `Value` | `string` |

#### Returns

`void`

___

### SetBlackboardValueAsVector

▸ `Static` **SetBlackboardValueAsVector**(`NodeOwner`, `Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `Key` | [`BlackboardKeySelector`](ue_ue.BlackboardKeySelector.md) |
| `Value` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### StartUsingExternalEvent

▸ `Static` **StartUsingExternalEvent**(`NodeOwner`, `OwningActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |
| `OwningActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

___

### StopUsingExternalEvent

▸ `Static` **StopUsingExternalEvent**(`NodeOwner`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NodeOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BTNode`](ue_ue.BTNode.md)\> |

#### Returns

`void`
