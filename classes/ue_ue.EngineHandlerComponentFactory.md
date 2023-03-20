[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EngineHandlerComponentFactory

# Class: EngineHandlerComponentFactory

[ue/ue](../modules/ue_ue.md).EngineHandlerComponentFactory

## Hierarchy

- [`HandlerComponentFactory`](ue_ue.HandlerComponentFactory.md)

  ↳ **`EngineHandlerComponentFactory`**

## Table of contents

### Constructors

- [constructor](ue_ue.EngineHandlerComponentFactory.md#constructor)

### Properties

- [\_\_tid\_EngineHandlerComponentFactory\_\_](ue_ue.EngineHandlerComponentFactory.md#__tid_enginehandlercomponentfactory__)
- [\_\_tid\_HandlerComponentFactory\_\_](ue_ue.EngineHandlerComponentFactory.md#__tid_handlercomponentfactory__)
- [\_\_tid\_Object\_\_](ue_ue.EngineHandlerComponentFactory.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EngineHandlerComponentFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EngineHandlerComponentFactory.md#executeubergraph)
- [GetClass](ue_ue.EngineHandlerComponentFactory.md#getclass)
- [GetName](ue_ue.EngineHandlerComponentFactory.md#getname)
- [GetOuter](ue_ue.EngineHandlerComponentFactory.md#getouter)
- [GetWorld](ue_ue.EngineHandlerComponentFactory.md#getworld)
- [Find](ue_ue.EngineHandlerComponentFactory.md#find)
- [Load](ue_ue.EngineHandlerComponentFactory.md#load)
- [StaticClass](ue_ue.EngineHandlerComponentFactory.md#staticclass)

## Constructors

### constructor

• **new EngineHandlerComponentFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[HandlerComponentFactory](ue_ue.HandlerComponentFactory.md).[constructor](ue_ue.HandlerComponentFactory.md#constructor)

## Properties

### \_\_tid\_EngineHandlerComponentFactory\_\_

• **\_\_tid\_EngineHandlerComponentFactory\_\_**: `boolean`

___

### \_\_tid\_HandlerComponentFactory\_\_

• **\_\_tid\_HandlerComponentFactory\_\_**: `boolean`

#### Inherited from

[HandlerComponentFactory](ue_ue.HandlerComponentFactory.md).[__tid_HandlerComponentFactory__](ue_ue.HandlerComponentFactory.md#__tid_handlercomponentfactory__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[HandlerComponentFactory](ue_ue.HandlerComponentFactory.md).[__tid_Object__](ue_ue.HandlerComponentFactory.md#__tid_object__)

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

[HandlerComponentFactory](ue_ue.HandlerComponentFactory.md).[CreateDefaultSubobject](ue_ue.HandlerComponentFactory.md#createdefaultsubobject)

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

[HandlerComponentFactory](ue_ue.HandlerComponentFactory.md).[ExecuteUbergraph](ue_ue.HandlerComponentFactory.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[HandlerComponentFactory](ue_ue.HandlerComponentFactory.md).[GetClass](ue_ue.HandlerComponentFactory.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[HandlerComponentFactory](ue_ue.HandlerComponentFactory.md).[GetName](ue_ue.HandlerComponentFactory.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[HandlerComponentFactory](ue_ue.HandlerComponentFactory.md).[GetOuter](ue_ue.HandlerComponentFactory.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[HandlerComponentFactory](ue_ue.HandlerComponentFactory.md).[GetWorld](ue_ue.HandlerComponentFactory.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EngineHandlerComponentFactory`](ue_ue.EngineHandlerComponentFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EngineHandlerComponentFactory`](ue_ue.EngineHandlerComponentFactory.md)

#### Overrides

[HandlerComponentFactory](ue_ue.HandlerComponentFactory.md).[Find](ue_ue.HandlerComponentFactory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EngineHandlerComponentFactory`](ue_ue.EngineHandlerComponentFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EngineHandlerComponentFactory`](ue_ue.EngineHandlerComponentFactory.md)

#### Overrides

[HandlerComponentFactory](ue_ue.HandlerComponentFactory.md).[Load](ue_ue.HandlerComponentFactory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[HandlerComponentFactory](ue_ue.HandlerComponentFactory.md).[StaticClass](ue_ue.HandlerComponentFactory.md#staticclass)
