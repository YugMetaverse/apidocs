[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlackboardKeyType

# Class: BlackboardKeyType

[ue/ue](../modules/ue_ue.md).BlackboardKeyType

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`BlackboardKeyType`**

  ↳↳ [`BlackboardKeyType_Bool`](ue_ue.BlackboardKeyType_Bool.md)

  ↳↳ [`BlackboardKeyType_Class`](ue_ue.BlackboardKeyType_Class.md)

  ↳↳ [`BlackboardKeyType_Enum`](ue_ue.BlackboardKeyType_Enum.md)

  ↳↳ [`BlackboardKeyType_Float`](ue_ue.BlackboardKeyType_Float.md)

  ↳↳ [`BlackboardKeyType_Int`](ue_ue.BlackboardKeyType_Int.md)

  ↳↳ [`BlackboardKeyType_Name`](ue_ue.BlackboardKeyType_Name.md)

  ↳↳ [`BlackboardKeyType_NativeEnum`](ue_ue.BlackboardKeyType_NativeEnum.md)

  ↳↳ [`BlackboardKeyType_Object`](ue_ue.BlackboardKeyType_Object.md)

  ↳↳ [`BlackboardKeyType_Rotator`](ue_ue.BlackboardKeyType_Rotator.md)

  ↳↳ [`BlackboardKeyType_String`](ue_ue.BlackboardKeyType_String.md)

  ↳↳ [`BlackboardKeyType_Vector`](ue_ue.BlackboardKeyType_Vector.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BlackboardKeyType.md#constructor)

### Properties

- [\_\_tid\_BlackboardKeyType\_\_](ue_ue.BlackboardKeyType.md#__tid_blackboardkeytype__)
- [\_\_tid\_Object\_\_](ue_ue.BlackboardKeyType.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BlackboardKeyType.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlackboardKeyType.md#executeubergraph)
- [GetClass](ue_ue.BlackboardKeyType.md#getclass)
- [GetName](ue_ue.BlackboardKeyType.md#getname)
- [GetOuter](ue_ue.BlackboardKeyType.md#getouter)
- [GetWorld](ue_ue.BlackboardKeyType.md#getworld)
- [Find](ue_ue.BlackboardKeyType.md#find)
- [Load](ue_ue.BlackboardKeyType.md#load)
- [StaticClass](ue_ue.BlackboardKeyType.md#staticclass)

## Constructors

### constructor

• **new BlackboardKeyType**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_BlackboardKeyType\_\_

• **\_\_tid\_BlackboardKeyType\_\_**: `boolean`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlackboardKeyType`](ue_ue.BlackboardKeyType.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlackboardKeyType`](ue_ue.BlackboardKeyType.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BlackboardKeyType`](ue_ue.BlackboardKeyType.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlackboardKeyType`](ue_ue.BlackboardKeyType.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
