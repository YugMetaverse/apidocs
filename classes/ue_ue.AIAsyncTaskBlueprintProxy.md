[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AIAsyncTaskBlueprintProxy

# Class: AIAsyncTaskBlueprintProxy

[ue/ue](../modules/ue_ue.md).AIAsyncTaskBlueprintProxy

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AIAsyncTaskBlueprintProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.AIAsyncTaskBlueprintProxy.md#constructor)

### Properties

- [OnFail](ue_ue.AIAsyncTaskBlueprintProxy.md#onfail)
- [OnSuccess](ue_ue.AIAsyncTaskBlueprintProxy.md#onsuccess)
- [\_\_tid\_AIAsyncTaskBlueprintProxy\_\_](ue_ue.AIAsyncTaskBlueprintProxy.md#__tid_aiasynctaskblueprintproxy__)
- [\_\_tid\_Object\_\_](ue_ue.AIAsyncTaskBlueprintProxy.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AIAsyncTaskBlueprintProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AIAsyncTaskBlueprintProxy.md#executeubergraph)
- [GetClass](ue_ue.AIAsyncTaskBlueprintProxy.md#getclass)
- [GetName](ue_ue.AIAsyncTaskBlueprintProxy.md#getname)
- [GetOuter](ue_ue.AIAsyncTaskBlueprintProxy.md#getouter)
- [GetWorld](ue_ue.AIAsyncTaskBlueprintProxy.md#getworld)
- [OnMoveCompleted](ue_ue.AIAsyncTaskBlueprintProxy.md#onmovecompleted)
- [Find](ue_ue.AIAsyncTaskBlueprintProxy.md#find)
- [Load](ue_ue.AIAsyncTaskBlueprintProxy.md#load)
- [StaticClass](ue_ue.AIAsyncTaskBlueprintProxy.md#staticclass)

## Constructors

### constructor

• **new AIAsyncTaskBlueprintProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### OnFail

• **OnFail**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`MovementResult`: [`EPathFollowingResult`](../enums/ue_ue.EPathFollowingResult.md)) => `void`\>

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`MovementResult`: [`EPathFollowingResult`](../enums/ue_ue.EPathFollowingResult.md)) => `void`\>

___

### \_\_tid\_AIAsyncTaskBlueprintProxy\_\_

• **\_\_tid\_AIAsyncTaskBlueprintProxy\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### OnMoveCompleted

▸ **OnMoveCompleted**(`RequestID`, `MovementResult`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RequestID` | [`AIRequestID`](ue_ue.AIRequestID.md) |
| `MovementResult` | [`EPathFollowingResult`](../enums/ue_ue.EPathFollowingResult.md) |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AIAsyncTaskBlueprintProxy`](ue_ue.AIAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AIAsyncTaskBlueprintProxy`](ue_ue.AIAsyncTaskBlueprintProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AIAsyncTaskBlueprintProxy`](ue_ue.AIAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AIAsyncTaskBlueprintProxy`](ue_ue.AIAsyncTaskBlueprintProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
