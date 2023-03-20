[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TouchInterface

# Class: TouchInterface

[ue/ue](../modules/ue_ue.md).TouchInterface

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`TouchInterface`**

## Table of contents

### Constructors

- [constructor](ue_ue.TouchInterface.md#constructor)

### Properties

- [ActivationDelay](ue_ue.TouchInterface.md#activationdelay)
- [ActiveOpacity](ue_ue.TouchInterface.md#activeopacity)
- [Controls](ue_ue.TouchInterface.md#controls)
- [InactiveOpacity](ue_ue.TouchInterface.md#inactiveopacity)
- [StartupDelay](ue_ue.TouchInterface.md#startupdelay)
- [TimeUntilDeactive](ue_ue.TouchInterface.md#timeuntildeactive)
- [TimeUntilReset](ue_ue.TouchInterface.md#timeuntilreset)
- [\_\_tid\_Object\_\_](ue_ue.TouchInterface.md#__tid_object__)
- [\_\_tid\_TouchInterface\_\_](ue_ue.TouchInterface.md#__tid_touchinterface__)
- [bPreventRecenter](ue_ue.TouchInterface.md#bpreventrecenter)

### Methods

- [CreateDefaultSubobject](ue_ue.TouchInterface.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TouchInterface.md#executeubergraph)
- [GetClass](ue_ue.TouchInterface.md#getclass)
- [GetName](ue_ue.TouchInterface.md#getname)
- [GetOuter](ue_ue.TouchInterface.md#getouter)
- [GetWorld](ue_ue.TouchInterface.md#getworld)
- [Find](ue_ue.TouchInterface.md#find)
- [Load](ue_ue.TouchInterface.md#load)
- [StaticClass](ue_ue.TouchInterface.md#staticclass)

## Constructors

### constructor

• **new TouchInterface**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ActivationDelay

• **ActivationDelay**: `number`

___

### ActiveOpacity

• **ActiveOpacity**: `number`

___

### Controls

• **Controls**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TouchInputControl`](ue_ue.TouchInputControl.md)\>

___

### InactiveOpacity

• **InactiveOpacity**: `number`

___

### StartupDelay

• **StartupDelay**: `number`

___

### TimeUntilDeactive

• **TimeUntilDeactive**: `number`

___

### TimeUntilReset

• **TimeUntilReset**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_TouchInterface\_\_

• **\_\_tid\_TouchInterface\_\_**: `boolean`

___

### bPreventRecenter

• **bPreventRecenter**: `boolean`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TouchInterface`](ue_ue.TouchInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TouchInterface`](ue_ue.TouchInterface.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TouchInterface`](ue_ue.TouchInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TouchInterface`](ue_ue.TouchInterface.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
