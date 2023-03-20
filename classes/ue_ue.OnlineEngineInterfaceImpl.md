[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / OnlineEngineInterfaceImpl

# Class: OnlineEngineInterfaceImpl

[ue/ue](../modules/ue_ue.md).OnlineEngineInterfaceImpl

## Hierarchy

- [`OnlineEngineInterface`](ue_ue.OnlineEngineInterface.md)

  ↳ **`OnlineEngineInterfaceImpl`**

## Table of contents

### Constructors

- [constructor](ue_ue.OnlineEngineInterfaceImpl.md#constructor)

### Properties

- [VoiceSubsystemNameOverride](ue_ue.OnlineEngineInterfaceImpl.md#voicesubsystemnameoverride)
- [\_\_tid\_Object\_\_](ue_ue.OnlineEngineInterfaceImpl.md#__tid_object__)
- [\_\_tid\_OnlineEngineInterfaceImpl\_\_](ue_ue.OnlineEngineInterfaceImpl.md#__tid_onlineengineinterfaceimpl__)
- [\_\_tid\_OnlineEngineInterface\_\_](ue_ue.OnlineEngineInterfaceImpl.md#__tid_onlineengineinterface__)

### Methods

- [CreateDefaultSubobject](ue_ue.OnlineEngineInterfaceImpl.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.OnlineEngineInterfaceImpl.md#executeubergraph)
- [GetClass](ue_ue.OnlineEngineInterfaceImpl.md#getclass)
- [GetName](ue_ue.OnlineEngineInterfaceImpl.md#getname)
- [GetOuter](ue_ue.OnlineEngineInterfaceImpl.md#getouter)
- [GetWorld](ue_ue.OnlineEngineInterfaceImpl.md#getworld)
- [Find](ue_ue.OnlineEngineInterfaceImpl.md#find)
- [Load](ue_ue.OnlineEngineInterfaceImpl.md#load)
- [StaticClass](ue_ue.OnlineEngineInterfaceImpl.md#staticclass)

## Constructors

### constructor

• **new OnlineEngineInterfaceImpl**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[OnlineEngineInterface](ue_ue.OnlineEngineInterface.md).[constructor](ue_ue.OnlineEngineInterface.md#constructor)

## Properties

### VoiceSubsystemNameOverride

• **VoiceSubsystemNameOverride**: `string`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[OnlineEngineInterface](ue_ue.OnlineEngineInterface.md).[__tid_Object__](ue_ue.OnlineEngineInterface.md#__tid_object__)

___

### \_\_tid\_OnlineEngineInterfaceImpl\_\_

• **\_\_tid\_OnlineEngineInterfaceImpl\_\_**: `boolean`

___

### \_\_tid\_OnlineEngineInterface\_\_

• **\_\_tid\_OnlineEngineInterface\_\_**: `boolean`

#### Inherited from

[OnlineEngineInterface](ue_ue.OnlineEngineInterface.md).[__tid_OnlineEngineInterface__](ue_ue.OnlineEngineInterface.md#__tid_onlineengineinterface__)

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

[OnlineEngineInterface](ue_ue.OnlineEngineInterface.md).[CreateDefaultSubobject](ue_ue.OnlineEngineInterface.md#createdefaultsubobject)

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

[OnlineEngineInterface](ue_ue.OnlineEngineInterface.md).[ExecuteUbergraph](ue_ue.OnlineEngineInterface.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[OnlineEngineInterface](ue_ue.OnlineEngineInterface.md).[GetClass](ue_ue.OnlineEngineInterface.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineEngineInterface](ue_ue.OnlineEngineInterface.md).[GetName](ue_ue.OnlineEngineInterface.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[OnlineEngineInterface](ue_ue.OnlineEngineInterface.md).[GetOuter](ue_ue.OnlineEngineInterface.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[OnlineEngineInterface](ue_ue.OnlineEngineInterface.md).[GetWorld](ue_ue.OnlineEngineInterface.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`OnlineEngineInterfaceImpl`](ue_ue.OnlineEngineInterfaceImpl.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`OnlineEngineInterfaceImpl`](ue_ue.OnlineEngineInterfaceImpl.md)

#### Overrides

[OnlineEngineInterface](ue_ue.OnlineEngineInterface.md).[Find](ue_ue.OnlineEngineInterface.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`OnlineEngineInterfaceImpl`](ue_ue.OnlineEngineInterfaceImpl.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`OnlineEngineInterfaceImpl`](ue_ue.OnlineEngineInterfaceImpl.md)

#### Overrides

[OnlineEngineInterface](ue_ue.OnlineEngineInterface.md).[Load](ue_ue.OnlineEngineInterface.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[OnlineEngineInterface](ue_ue.OnlineEngineInterface.md).[StaticClass](ue_ue.OnlineEngineInterface.md#staticclass)
