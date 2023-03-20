[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LiveLinkBasicRole

# Class: LiveLinkBasicRole

[ue/ue](../modules/ue_ue.md).LiveLinkBasicRole

## Hierarchy

- [`LiveLinkRole`](ue_ue.LiveLinkRole.md)

  ↳ **`LiveLinkBasicRole`**

  ↳↳ [`LiveLinkAnimationRole`](ue_ue.LiveLinkAnimationRole.md)

  ↳↳ [`LiveLinkTransformRole`](ue_ue.LiveLinkTransformRole.md)

## Table of contents

### Constructors

- [constructor](ue_ue.LiveLinkBasicRole.md#constructor)

### Properties

- [\_\_tid\_LiveLinkBasicRole\_\_](ue_ue.LiveLinkBasicRole.md#__tid_livelinkbasicrole__)
- [\_\_tid\_LiveLinkRole\_\_](ue_ue.LiveLinkBasicRole.md#__tid_livelinkrole__)
- [\_\_tid\_Object\_\_](ue_ue.LiveLinkBasicRole.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LiveLinkBasicRole.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LiveLinkBasicRole.md#executeubergraph)
- [GetClass](ue_ue.LiveLinkBasicRole.md#getclass)
- [GetName](ue_ue.LiveLinkBasicRole.md#getname)
- [GetOuter](ue_ue.LiveLinkBasicRole.md#getouter)
- [GetWorld](ue_ue.LiveLinkBasicRole.md#getworld)
- [Find](ue_ue.LiveLinkBasicRole.md#find)
- [Load](ue_ue.LiveLinkBasicRole.md#load)
- [StaticClass](ue_ue.LiveLinkBasicRole.md#staticclass)

## Constructors

### constructor

• **new LiveLinkBasicRole**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[LiveLinkRole](ue_ue.LiveLinkRole.md).[constructor](ue_ue.LiveLinkRole.md#constructor)

## Properties

### \_\_tid\_LiveLinkBasicRole\_\_

• **\_\_tid\_LiveLinkBasicRole\_\_**: `boolean`

___

### \_\_tid\_LiveLinkRole\_\_

• **\_\_tid\_LiveLinkRole\_\_**: `boolean`

#### Inherited from

[LiveLinkRole](ue_ue.LiveLinkRole.md).[__tid_LiveLinkRole__](ue_ue.LiveLinkRole.md#__tid_livelinkrole__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[LiveLinkRole](ue_ue.LiveLinkRole.md).[__tid_Object__](ue_ue.LiveLinkRole.md#__tid_object__)

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

[LiveLinkRole](ue_ue.LiveLinkRole.md).[CreateDefaultSubobject](ue_ue.LiveLinkRole.md#createdefaultsubobject)

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

[LiveLinkRole](ue_ue.LiveLinkRole.md).[ExecuteUbergraph](ue_ue.LiveLinkRole.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[LiveLinkRole](ue_ue.LiveLinkRole.md).[GetClass](ue_ue.LiveLinkRole.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[LiveLinkRole](ue_ue.LiveLinkRole.md).[GetName](ue_ue.LiveLinkRole.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[LiveLinkRole](ue_ue.LiveLinkRole.md).[GetOuter](ue_ue.LiveLinkRole.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[LiveLinkRole](ue_ue.LiveLinkRole.md).[GetWorld](ue_ue.LiveLinkRole.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LiveLinkBasicRole`](ue_ue.LiveLinkBasicRole.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LiveLinkBasicRole`](ue_ue.LiveLinkBasicRole.md)

#### Overrides

[LiveLinkRole](ue_ue.LiveLinkRole.md).[Find](ue_ue.LiveLinkRole.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LiveLinkBasicRole`](ue_ue.LiveLinkBasicRole.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LiveLinkBasicRole`](ue_ue.LiveLinkBasicRole.md)

#### Overrides

[LiveLinkRole](ue_ue.LiveLinkRole.md).[Load](ue_ue.LiveLinkRole.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LiveLinkRole](ue_ue.LiveLinkRole.md).[StaticClass](ue_ue.LiveLinkRole.md#staticclass)
