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

#### Defined in

[ue/ue.d.ts:53632](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53632)

## Properties

### ObjectBaseClass

• **ObjectBaseClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:53633](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53633)

___

### Objects

• **Objects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:53635](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53635)

___

### WeakObjects

• **WeakObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>\>

#### Defined in

[ue/ue.d.ts:53636](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53636)

___

### \_\_tid\_ObjectLibrary\_\_

• **\_\_tid\_ObjectLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:53643](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53643)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bHasBlueprintClasses

• **bHasBlueprintClasses**: `boolean`

#### Defined in

[ue/ue.d.ts:53634](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53634)

___

### bIsFullyLoaded

• **bIsFullyLoaded**: `boolean`

#### Defined in

[ue/ue.d.ts:53638](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53638)

___

### bUseWeakReferences

• **bUseWeakReferences**: `boolean`

#### Defined in

[ue/ue.d.ts:53637](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53637)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:53640](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53640)

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

#### Defined in

[ue/ue.d.ts:53641](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53641)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:53639](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L53639)
