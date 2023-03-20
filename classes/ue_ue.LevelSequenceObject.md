[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelSequenceObject

# Class: LevelSequenceObject

[ue/ue](../modules/ue_ue.md).LevelSequenceObject

## Table of contents

### Constructors

- [constructor](ue_ue.LevelSequenceObject.md#constructor)

### Properties

- [CachedComponent](ue_ue.LevelSequenceObject.md#cachedcomponent)
- [ComponentName](ue_ue.LevelSequenceObject.md#componentname)
- [ObjectOrOwner](ue_ue.LevelSequenceObject.md#objectorowner)
- [\_\_tid\_LevelSequenceObject\_\_](ue_ue.LevelSequenceObject.md#__tid_levelsequenceobject__)

### Methods

- [StaticClass](ue_ue.LevelSequenceObject.md#staticclass)
- [StaticStruct](ue_ue.LevelSequenceObject.md#staticstruct)

## Constructors

### constructor

• **new LevelSequenceObject**()

• **new LevelSequenceObject**(`ObjectOrOwner`, `ComponentName`, `CachedComponent`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ObjectOrOwner` | [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`Object`](ue_ue.Object.md)\> |
| `ComponentName` | `string` |
| `CachedComponent` | [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\> |

## Properties

### CachedComponent

• **CachedComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

___

### ComponentName

• **ComponentName**: `string`

___

### ObjectOrOwner

• **ObjectOrOwner**: [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`Object`](ue_ue.Object.md)\>

___

### \_\_tid\_LevelSequenceObject\_\_

• `Private` **\_\_tid\_LevelSequenceObject\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
