[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintCore

# Class: BlueprintCore

[ue/ue](../modules/ue_ue.md).BlueprintCore

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`BlueprintCore`**

  ↳↳ [`Blueprint`](ue_ue.Blueprint.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintCore.md#constructor)

### Properties

- [BlueprintGuid](ue_ue.BlueprintCore.md#blueprintguid)
- [GeneratedClass](ue_ue.BlueprintCore.md#generatedclass)
- [SkeletonGeneratedClass](ue_ue.BlueprintCore.md#skeletongeneratedclass)
- [\_\_tid\_BlueprintCore\_\_](ue_ue.BlueprintCore.md#__tid_blueprintcore__)
- [\_\_tid\_Object\_\_](ue_ue.BlueprintCore.md#__tid_object__)
- [bLegacyNeedToPurgeSkelRefs](ue_ue.BlueprintCore.md#blegacyneedtopurgeskelrefs)

### Methods

- [CreateDefaultSubobject](ue_ue.BlueprintCore.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlueprintCore.md#executeubergraph)
- [GetClass](ue_ue.BlueprintCore.md#getclass)
- [GetName](ue_ue.BlueprintCore.md#getname)
- [GetOuter](ue_ue.BlueprintCore.md#getouter)
- [GetWorld](ue_ue.BlueprintCore.md#getworld)
- [Find](ue_ue.BlueprintCore.md#find)
- [Load](ue_ue.BlueprintCore.md#load)
- [StaticClass](ue_ue.BlueprintCore.md#staticclass)

## Constructors

### constructor

• **new BlueprintCore**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### BlueprintGuid

• **BlueprintGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### GeneratedClass

• **GeneratedClass**: [`Class`](ue_ue.Class.md)

___

### SkeletonGeneratedClass

• **SkeletonGeneratedClass**: [`Class`](ue_ue.Class.md)

___

### \_\_tid\_BlueprintCore\_\_

• **\_\_tid\_BlueprintCore\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bLegacyNeedToPurgeSkelRefs

• **bLegacyNeedToPurgeSkelRefs**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlueprintCore`](ue_ue.BlueprintCore.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlueprintCore`](ue_ue.BlueprintCore.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BlueprintCore`](ue_ue.BlueprintCore.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlueprintCore`](ue_ue.BlueprintCore.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
