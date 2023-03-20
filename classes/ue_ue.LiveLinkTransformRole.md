[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LiveLinkTransformRole

# Class: LiveLinkTransformRole

[ue/ue](../modules/ue_ue.md).LiveLinkTransformRole

## Hierarchy

- [`LiveLinkBasicRole`](ue_ue.LiveLinkBasicRole.md)

  ↳ **`LiveLinkTransformRole`**

  ↳↳ [`LiveLinkCameraRole`](ue_ue.LiveLinkCameraRole.md)

  ↳↳ [`LiveLinkLightRole`](ue_ue.LiveLinkLightRole.md)

## Table of contents

### Constructors

- [constructor](ue_ue.LiveLinkTransformRole.md#constructor)

### Properties

- [\_\_tid\_LiveLinkBasicRole\_\_](ue_ue.LiveLinkTransformRole.md#__tid_livelinkbasicrole__)
- [\_\_tid\_LiveLinkRole\_\_](ue_ue.LiveLinkTransformRole.md#__tid_livelinkrole__)
- [\_\_tid\_LiveLinkTransformRole\_\_](ue_ue.LiveLinkTransformRole.md#__tid_livelinktransformrole__)
- [\_\_tid\_Object\_\_](ue_ue.LiveLinkTransformRole.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LiveLinkTransformRole.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LiveLinkTransformRole.md#executeubergraph)
- [GetClass](ue_ue.LiveLinkTransformRole.md#getclass)
- [GetName](ue_ue.LiveLinkTransformRole.md#getname)
- [GetOuter](ue_ue.LiveLinkTransformRole.md#getouter)
- [GetWorld](ue_ue.LiveLinkTransformRole.md#getworld)
- [Find](ue_ue.LiveLinkTransformRole.md#find)
- [Load](ue_ue.LiveLinkTransformRole.md#load)
- [StaticClass](ue_ue.LiveLinkTransformRole.md#staticclass)

## Constructors

### constructor

• **new LiveLinkTransformRole**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[LiveLinkBasicRole](ue_ue.LiveLinkBasicRole.md).[constructor](ue_ue.LiveLinkBasicRole.md#constructor)

## Properties

### \_\_tid\_LiveLinkBasicRole\_\_

• **\_\_tid\_LiveLinkBasicRole\_\_**: `boolean`

#### Inherited from

[LiveLinkBasicRole](ue_ue.LiveLinkBasicRole.md).[__tid_LiveLinkBasicRole__](ue_ue.LiveLinkBasicRole.md#__tid_livelinkbasicrole__)

___

### \_\_tid\_LiveLinkRole\_\_

• **\_\_tid\_LiveLinkRole\_\_**: `boolean`

#### Inherited from

[LiveLinkBasicRole](ue_ue.LiveLinkBasicRole.md).[__tid_LiveLinkRole__](ue_ue.LiveLinkBasicRole.md#__tid_livelinkrole__)

___

### \_\_tid\_LiveLinkTransformRole\_\_

• **\_\_tid\_LiveLinkTransformRole\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[LiveLinkBasicRole](ue_ue.LiveLinkBasicRole.md).[__tid_Object__](ue_ue.LiveLinkBasicRole.md#__tid_object__)

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

[LiveLinkBasicRole](ue_ue.LiveLinkBasicRole.md).[CreateDefaultSubobject](ue_ue.LiveLinkBasicRole.md#createdefaultsubobject)

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

[LiveLinkBasicRole](ue_ue.LiveLinkBasicRole.md).[ExecuteUbergraph](ue_ue.LiveLinkBasicRole.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[LiveLinkBasicRole](ue_ue.LiveLinkBasicRole.md).[GetClass](ue_ue.LiveLinkBasicRole.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[LiveLinkBasicRole](ue_ue.LiveLinkBasicRole.md).[GetName](ue_ue.LiveLinkBasicRole.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[LiveLinkBasicRole](ue_ue.LiveLinkBasicRole.md).[GetOuter](ue_ue.LiveLinkBasicRole.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[LiveLinkBasicRole](ue_ue.LiveLinkBasicRole.md).[GetWorld](ue_ue.LiveLinkBasicRole.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LiveLinkTransformRole`](ue_ue.LiveLinkTransformRole.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LiveLinkTransformRole`](ue_ue.LiveLinkTransformRole.md)

#### Overrides

[LiveLinkBasicRole](ue_ue.LiveLinkBasicRole.md).[Find](ue_ue.LiveLinkBasicRole.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LiveLinkTransformRole`](ue_ue.LiveLinkTransformRole.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LiveLinkTransformRole`](ue_ue.LiveLinkTransformRole.md)

#### Overrides

[LiveLinkBasicRole](ue_ue.LiveLinkBasicRole.md).[Load](ue_ue.LiveLinkBasicRole.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LiveLinkBasicRole](ue_ue.LiveLinkBasicRole.md).[StaticClass](ue_ue.LiveLinkBasicRole.md#staticclass)
