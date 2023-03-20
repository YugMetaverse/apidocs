[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AIResource\_Logic

# Class: AIResource\_Logic

[ue/ue](../modules/ue_ue.md).AIResource_Logic

## Hierarchy

- [`GameplayTaskResource`](ue_ue.GameplayTaskResource.md)

  ↳ **`AIResource_Logic`**

## Table of contents

### Constructors

- [constructor](ue_ue.AIResource_Logic.md#constructor)

### Properties

- [AutoResourceID](ue_ue.AIResource_Logic.md#autoresourceid)
- [ManualResourceID](ue_ue.AIResource_Logic.md#manualresourceid)
- [\_\_tid\_AIResource\_Logic\_\_](ue_ue.AIResource_Logic.md#__tid_airesource_logic__)
- [\_\_tid\_GameplayTaskResource\_\_](ue_ue.AIResource_Logic.md#__tid_gameplaytaskresource__)
- [\_\_tid\_Object\_\_](ue_ue.AIResource_Logic.md#__tid_object__)
- [bManuallySetID](ue_ue.AIResource_Logic.md#bmanuallysetid)

### Methods

- [CreateDefaultSubobject](ue_ue.AIResource_Logic.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AIResource_Logic.md#executeubergraph)
- [GetClass](ue_ue.AIResource_Logic.md#getclass)
- [GetName](ue_ue.AIResource_Logic.md#getname)
- [GetOuter](ue_ue.AIResource_Logic.md#getouter)
- [GetWorld](ue_ue.AIResource_Logic.md#getworld)
- [Find](ue_ue.AIResource_Logic.md#find)
- [Load](ue_ue.AIResource_Logic.md#load)
- [StaticClass](ue_ue.AIResource_Logic.md#staticclass)

## Constructors

### constructor

• **new AIResource_Logic**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[constructor](ue_ue.GameplayTaskResource.md#constructor)

## Properties

### AutoResourceID

• **AutoResourceID**: `number`

#### Inherited from

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[AutoResourceID](ue_ue.GameplayTaskResource.md#autoresourceid)

___

### ManualResourceID

• **ManualResourceID**: `number`

#### Inherited from

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[ManualResourceID](ue_ue.GameplayTaskResource.md#manualresourceid)

___

### \_\_tid\_AIResource\_Logic\_\_

• **\_\_tid\_AIResource\_Logic\_\_**: `boolean`

___

### \_\_tid\_GameplayTaskResource\_\_

• **\_\_tid\_GameplayTaskResource\_\_**: `boolean`

#### Inherited from

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[__tid_GameplayTaskResource__](ue_ue.GameplayTaskResource.md#__tid_gameplaytaskresource__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[__tid_Object__](ue_ue.GameplayTaskResource.md#__tid_object__)

___

### bManuallySetID

• **bManuallySetID**: `boolean`

#### Inherited from

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[bManuallySetID](ue_ue.GameplayTaskResource.md#bmanuallysetid)

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

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[CreateDefaultSubobject](ue_ue.GameplayTaskResource.md#createdefaultsubobject)

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

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[ExecuteUbergraph](ue_ue.GameplayTaskResource.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[GetClass](ue_ue.GameplayTaskResource.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[GetName](ue_ue.GameplayTaskResource.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[GetOuter](ue_ue.GameplayTaskResource.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[GetWorld](ue_ue.GameplayTaskResource.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AIResource_Logic`](ue_ue.AIResource_Logic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AIResource_Logic`](ue_ue.AIResource_Logic.md)

#### Overrides

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[Find](ue_ue.GameplayTaskResource.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AIResource_Logic`](ue_ue.AIResource_Logic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AIResource_Logic`](ue_ue.AIResource_Logic.md)

#### Overrides

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[Load](ue_ue.GameplayTaskResource.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameplayTaskResource](ue_ue.GameplayTaskResource.md).[StaticClass](ue_ue.GameplayTaskResource.md#staticclass)
