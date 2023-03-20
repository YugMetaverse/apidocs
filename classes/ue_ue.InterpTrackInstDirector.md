[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrackInstDirector

# Class: InterpTrackInstDirector

[ue/ue](../modules/ue_ue.md).InterpTrackInstDirector

## Hierarchy

- [`InterpTrackInst`](ue_ue.InterpTrackInst.md)

  ↳ **`InterpTrackInstDirector`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrackInstDirector.md#constructor)

### Properties

- [OldViewTarget](ue_ue.InterpTrackInstDirector.md#oldviewtarget)
- [\_\_tid\_InterpTrackInstDirector\_\_](ue_ue.InterpTrackInstDirector.md#__tid_interptrackinstdirector__)
- [\_\_tid\_InterpTrackInst\_\_](ue_ue.InterpTrackInstDirector.md#__tid_interptrackinst__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrackInstDirector.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrackInstDirector.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrackInstDirector.md#executeubergraph)
- [GetClass](ue_ue.InterpTrackInstDirector.md#getclass)
- [GetName](ue_ue.InterpTrackInstDirector.md#getname)
- [GetOuter](ue_ue.InterpTrackInstDirector.md#getouter)
- [GetWorld](ue_ue.InterpTrackInstDirector.md#getworld)
- [Find](ue_ue.InterpTrackInstDirector.md#find)
- [Load](ue_ue.InterpTrackInstDirector.md#load)
- [StaticClass](ue_ue.InterpTrackInstDirector.md#staticclass)

## Constructors

### constructor

• **new InterpTrackInstDirector**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InterpTrackInst](ue_ue.InterpTrackInst.md).[constructor](ue_ue.InterpTrackInst.md#constructor)

## Properties

### OldViewTarget

• **OldViewTarget**: [`Actor`](ue_ue.Actor.md)

___

### \_\_tid\_InterpTrackInstDirector\_\_

• **\_\_tid\_InterpTrackInstDirector\_\_**: `boolean`

___

### \_\_tid\_InterpTrackInst\_\_

• **\_\_tid\_InterpTrackInst\_\_**: `boolean`

#### Inherited from

[InterpTrackInst](ue_ue.InterpTrackInst.md).[__tid_InterpTrackInst__](ue_ue.InterpTrackInst.md#__tid_interptrackinst__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InterpTrackInst](ue_ue.InterpTrackInst.md).[__tid_Object__](ue_ue.InterpTrackInst.md#__tid_object__)

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

[InterpTrackInst](ue_ue.InterpTrackInst.md).[CreateDefaultSubobject](ue_ue.InterpTrackInst.md#createdefaultsubobject)

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

[InterpTrackInst](ue_ue.InterpTrackInst.md).[ExecuteUbergraph](ue_ue.InterpTrackInst.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrackInst](ue_ue.InterpTrackInst.md).[GetClass](ue_ue.InterpTrackInst.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InterpTrackInst](ue_ue.InterpTrackInst.md).[GetName](ue_ue.InterpTrackInst.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpTrackInst](ue_ue.InterpTrackInst.md).[GetOuter](ue_ue.InterpTrackInst.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InterpTrackInst](ue_ue.InterpTrackInst.md).[GetWorld](ue_ue.InterpTrackInst.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrackInstDirector`](ue_ue.InterpTrackInstDirector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrackInstDirector`](ue_ue.InterpTrackInstDirector.md)

#### Overrides

[InterpTrackInst](ue_ue.InterpTrackInst.md).[Find](ue_ue.InterpTrackInst.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrackInstDirector`](ue_ue.InterpTrackInstDirector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrackInstDirector`](ue_ue.InterpTrackInstDirector.md)

#### Overrides

[InterpTrackInst](ue_ue.InterpTrackInst.md).[Load](ue_ue.InterpTrackInst.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrackInst](ue_ue.InterpTrackInst.md).[StaticClass](ue_ue.InterpTrackInst.md#staticclass)
