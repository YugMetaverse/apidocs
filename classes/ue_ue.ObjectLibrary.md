[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ObjectLibrary

# Class: ObjectLibrary

[ue/ue](../modules/ue_ue.md).ObjectLibrary

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ObjectLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.ObjectLibrary.md#constructor)

### Properties

- [ObjectBaseClass](ue_ue.ObjectLibrary.md#objectbaseclass)
- [Objects](ue_ue.ObjectLibrary.md#objects)
- [WeakObjects](ue_ue.ObjectLibrary.md#weakobjects)
- [\_\_tid\_ObjectLibrary\_\_](ue_ue.ObjectLibrary.md#__tid_objectlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.ObjectLibrary.md#__tid_object__)
- [bHasBlueprintClasses](ue_ue.ObjectLibrary.md#bhasblueprintclasses)
- [bIsFullyLoaded](ue_ue.ObjectLibrary.md#bisfullyloaded)
- [bUseWeakReferences](ue_ue.ObjectLibrary.md#buseweakreferences)

### Methods

- [CreateDefaultSubobject](ue_ue.ObjectLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ObjectLibrary.md#executeubergraph)
- [GetClass](ue_ue.ObjectLibrary.md#getclass)
- [GetName](ue_ue.ObjectLibrary.md#getname)
- [GetOuter](ue_ue.ObjectLibrary.md#getouter)
- [GetWorld](ue_ue.ObjectLibrary.md#getworld)
- [Find](ue_ue.ObjectLibrary.md#find)
- [Load](ue_ue.ObjectLibrary.md#load)
- [StaticClass](ue_ue.ObjectLibrary.md#staticclass)

## Constructors

### constructor

• **new ObjectLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ObjectBaseClass

• **ObjectBaseClass**: [`Class`](ue_ue.Class.md)

___

### Objects

• **Objects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### WeakObjects

• **WeakObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>\>

___

### \_\_tid\_ObjectLibrary\_\_

• **\_\_tid\_ObjectLibrary\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bHasBlueprintClasses

• **bHasBlueprintClasses**: `boolean`

___

### bIsFullyLoaded

• **bIsFullyLoaded**: `boolean`

___

### bUseWeakReferences

• **bUseWeakReferences**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ObjectLibrary`](ue_ue.ObjectLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ObjectLibrary`](ue_ue.ObjectLibrary.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ObjectLibrary`](ue_ue.ObjectLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ObjectLibrary`](ue_ue.ObjectLibrary.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
