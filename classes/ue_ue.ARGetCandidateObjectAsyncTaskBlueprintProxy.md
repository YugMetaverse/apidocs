[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARGetCandidateObjectAsyncTaskBlueprintProxy

# Class: ARGetCandidateObjectAsyncTaskBlueprintProxy

[ue/ue](../modules/ue_ue.md).ARGetCandidateObjectAsyncTaskBlueprintProxy

## Hierarchy

- [`ARBaseAsyncTaskBlueprintProxy`](ue_ue.ARBaseAsyncTaskBlueprintProxy.md)

  ↳ **`ARGetCandidateObjectAsyncTaskBlueprintProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#constructor)

### Properties

- [OnFailed](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#onfailed)
- [OnSuccess](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#onsuccess)
- [\_\_tid\_ARBaseAsyncTaskBlueprintProxy\_\_](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#__tid_arbaseasynctaskblueprintproxy__)
- [\_\_tid\_ARGetCandidateObjectAsyncTaskBlueprintProxy\_\_](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#__tid_argetcandidateobjectasynctaskblueprintproxy__)
- [\_\_tid\_BlueprintAsyncActionBase\_\_](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#__tid_blueprintasyncactionbase__)
- [\_\_tid\_Object\_\_](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#__tid_object__)

### Methods

- [Activate](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#activate)
- [CreateDefaultSubobject](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#executeubergraph)
- [GetClass](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#getclass)
- [GetName](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#getname)
- [GetOuter](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#getouter)
- [GetWorld](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#getworld)
- [ARGetCandidateObject](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#argetcandidateobject)
- [Find](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#find)
- [Load](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#load)
- [StaticClass](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md#staticclass)

## Constructors

### constructor

• **new ARGetCandidateObjectAsyncTaskBlueprintProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[constructor](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#constructor)

#### Defined in

[ue/ue.d.ts:21222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21222)

## Properties

### OnFailed

• **OnFailed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SavedObject`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARCandidateObject`](ue_ue.ARCandidateObject.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:21224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21224)

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SavedObject`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ARCandidateObject`](ue_ue.ARCandidateObject.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:21223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21223)

___

### \_\_tid\_ARBaseAsyncTaskBlueprintProxy\_\_

• **\_\_tid\_ARBaseAsyncTaskBlueprintProxy\_\_**: `boolean`

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[__tid_ARBaseAsyncTaskBlueprintProxy__](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#__tid_arbaseasynctaskblueprintproxy__)

#### Defined in

[ue/ue.d.ts:20681](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20681)

___

### \_\_tid\_ARGetCandidateObjectAsyncTaskBlueprintProxy\_\_

• **\_\_tid\_ARGetCandidateObjectAsyncTaskBlueprintProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21230](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21230)

___

### \_\_tid\_BlueprintAsyncActionBase\_\_

• **\_\_tid\_BlueprintAsyncActionBase\_\_**: `boolean`

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[__tid_BlueprintAsyncActionBase__](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#__tid_blueprintasyncactionbase__)

#### Defined in

[ue/ue.d.ts:20672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20672)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[__tid_Object__](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[Activate](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#activate)

#### Defined in

[ue/ue.d.ts:20667](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20667)

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

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[CreateDefaultSubobject](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#createdefaultsubobject)

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

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[ExecuteUbergraph](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[GetClass](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[GetName](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[GetOuter](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[GetWorld](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### ARGetCandidateObject

▸ `Static` **ARGetCandidateObject**(`WorldContextObject`, `Location`, `Extent`): [`ARGetCandidateObjectAsyncTaskBlueprintProxy`](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Extent` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`ARGetCandidateObjectAsyncTaskBlueprintProxy`](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md)

#### Defined in

[ue/ue.d.ts:21225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21225)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARGetCandidateObjectAsyncTaskBlueprintProxy`](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARGetCandidateObjectAsyncTaskBlueprintProxy`](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md)

#### Overrides

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[Find](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#find)

#### Defined in

[ue/ue.d.ts:21227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21227)

___

### Load

▸ `Static` **Load**(`InName`): [`ARGetCandidateObjectAsyncTaskBlueprintProxy`](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARGetCandidateObjectAsyncTaskBlueprintProxy`](ue_ue.ARGetCandidateObjectAsyncTaskBlueprintProxy.md)

#### Overrides

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[Load](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#load)

#### Defined in

[ue/ue.d.ts:21228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21228)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[StaticClass](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#staticclass)

#### Defined in

[ue/ue.d.ts:21226](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21226)
