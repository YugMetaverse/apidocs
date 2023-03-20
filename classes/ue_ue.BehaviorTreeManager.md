[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BehaviorTreeManager

# Class: BehaviorTreeManager

[ue/ue](../modules/ue_ue.md).BehaviorTreeManager

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`BehaviorTreeManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.BehaviorTreeManager.md#constructor)

### Properties

- [ActiveComponents](ue_ue.BehaviorTreeManager.md#activecomponents)
- [LoadedTemplates](ue_ue.BehaviorTreeManager.md#loadedtemplates)
- [MaxDebuggerSteps](ue_ue.BehaviorTreeManager.md#maxdebuggersteps)
- [\_\_tid\_BehaviorTreeManager\_\_](ue_ue.BehaviorTreeManager.md#__tid_behaviortreemanager__)
- [\_\_tid\_Object\_\_](ue_ue.BehaviorTreeManager.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BehaviorTreeManager.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BehaviorTreeManager.md#executeubergraph)
- [GetClass](ue_ue.BehaviorTreeManager.md#getclass)
- [GetName](ue_ue.BehaviorTreeManager.md#getname)
- [GetOuter](ue_ue.BehaviorTreeManager.md#getouter)
- [GetWorld](ue_ue.BehaviorTreeManager.md#getworld)
- [Find](ue_ue.BehaviorTreeManager.md#find)
- [Load](ue_ue.BehaviorTreeManager.md#load)
- [StaticClass](ue_ue.BehaviorTreeManager.md#staticclass)

## Constructors

### constructor

• **new BehaviorTreeManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:15452](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15452)

## Properties

### ActiveComponents

• **ActiveComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BehaviorTreeComponent`](ue_ue.BehaviorTreeComponent.md)\>

#### Defined in

[ue/ue.d.ts:15455](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15455)

___

### LoadedTemplates

• **LoadedTemplates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BehaviorTreeTemplateInfo`](ue_ue.BehaviorTreeTemplateInfo.md)\>

#### Defined in

[ue/ue.d.ts:15454](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15454)

___

### MaxDebuggerSteps

• **MaxDebuggerSteps**: `number`

#### Defined in

[ue/ue.d.ts:15453](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15453)

___

### \_\_tid\_BehaviorTreeManager\_\_

• **\_\_tid\_BehaviorTreeManager\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15460](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15460)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BehaviorTreeManager`](ue_ue.BehaviorTreeManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BehaviorTreeManager`](ue_ue.BehaviorTreeManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:15457](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15457)

___

### Load

▸ `Static` **Load**(`InName`): [`BehaviorTreeManager`](ue_ue.BehaviorTreeManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BehaviorTreeManager`](ue_ue.BehaviorTreeManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:15458](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15458)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:15456](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15456)
