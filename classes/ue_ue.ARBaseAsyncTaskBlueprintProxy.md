[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARBaseAsyncTaskBlueprintProxy

# Class: ARBaseAsyncTaskBlueprintProxy

[ue/ue](../modules/ue_ue.md).ARBaseAsyncTaskBlueprintProxy

## Hierarchy

- [`BlueprintAsyncActionBase`](ue_ue.BlueprintAsyncActionBase.md)

  ↳ **`ARBaseAsyncTaskBlueprintProxy`**

  ↳↳ [`ARGetCandidateObjectAsyncTaskBlueprintProxy`](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md)

  ↳↳ [`ARSaveWorldAsyncTaskBlueprintProxy`](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#constructor)

### Properties

- [\_\_tid\_ARBaseAsyncTaskBlueprintProxy\_\_](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#__tid_arbaseasynctaskblueprintproxy__)
- [\_\_tid\_BlueprintAsyncActionBase\_\_](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#__tid_blueprintasyncactionbase__)
- [\_\_tid\_Object\_\_](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#__tid_object__)

### Methods

- [Activate](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#activate)
- [CreateDefaultSubobject](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#executeubergraph)
- [GetClass](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#getclass)
- [GetName](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#getname)
- [GetOuter](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#getouter)
- [GetWorld](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#getworld)
- [Find](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#find)
- [Load](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#load)
- [StaticClass](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#staticclass)

## Constructors

### constructor

• **new ARBaseAsyncTaskBlueprintProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[constructor](ue_ue.BlueprintAsyncActionBase.md#constructor)

## Properties

### \_\_tid\_ARBaseAsyncTaskBlueprintProxy\_\_

• **\_\_tid\_ARBaseAsyncTaskBlueprintProxy\_\_**: `boolean`

___

### \_\_tid\_BlueprintAsyncActionBase\_\_

• **\_\_tid\_BlueprintAsyncActionBase\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_BlueprintAsyncActionBase__](ue_ue.BlueprintAsyncActionBase.md#__tid_blueprintasyncactionbase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_Object__](ue_ue.BlueprintAsyncActionBase.md#__tid_object__)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Activate](ue_ue.BlueprintAsyncActionBase.md#activate)

___

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

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[CreateDefaultSubobject](ue_ue.BlueprintAsyncActionBase.md#createdefaultsubobject)

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

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[ExecuteUbergraph](ue_ue.BlueprintAsyncActionBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetClass](ue_ue.BlueprintAsyncActionBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetName](ue_ue.BlueprintAsyncActionBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetOuter](ue_ue.BlueprintAsyncActionBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetWorld](ue_ue.BlueprintAsyncActionBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARBaseAsyncTaskBlueprintProxy`](ue_ue.ARBaseAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARBaseAsyncTaskBlueprintProxy`](ue_ue.ARBaseAsyncTaskBlueprintProxy.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Find](ue_ue.BlueprintAsyncActionBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ARBaseAsyncTaskBlueprintProxy`](ue_ue.ARBaseAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARBaseAsyncTaskBlueprintProxy`](ue_ue.ARBaseAsyncTaskBlueprintProxy.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Load](ue_ue.BlueprintAsyncActionBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[StaticClass](ue_ue.BlueprintAsyncActionBase.md#staticclass)
