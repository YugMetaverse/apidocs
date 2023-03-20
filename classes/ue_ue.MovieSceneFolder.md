[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneFolder

# Class: MovieSceneFolder

[ue/ue](../modules/ue_ue.md).MovieSceneFolder

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MovieSceneFolder`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneFolder.md#constructor)

### Properties

- [ChildFolders](ue_ue.MovieSceneFolder.md#childfolders)
- [ChildMasterTracks](ue_ue.MovieSceneFolder.md#childmastertracks)
- [ChildObjectBindingStrings](ue_ue.MovieSceneFolder.md#childobjectbindingstrings)
- [FolderColor](ue_ue.MovieSceneFolder.md#foldercolor)
- [FolderName](ue_ue.MovieSceneFolder.md#foldername)
- [SortingOrder](ue_ue.MovieSceneFolder.md#sortingorder)
- [\_\_tid\_MovieSceneFolder\_\_](ue_ue.MovieSceneFolder.md#__tid_moviescenefolder__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneFolder.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneFolder.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneFolder.md#executeubergraph)
- [GetClass](ue_ue.MovieSceneFolder.md#getclass)
- [GetName](ue_ue.MovieSceneFolder.md#getname)
- [GetOuter](ue_ue.MovieSceneFolder.md#getouter)
- [GetWorld](ue_ue.MovieSceneFolder.md#getworld)
- [Find](ue_ue.MovieSceneFolder.md#find)
- [Load](ue_ue.MovieSceneFolder.md#load)
- [StaticClass](ue_ue.MovieSceneFolder.md#staticclass)

## Constructors

### constructor

• **new MovieSceneFolder**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ChildFolders

• **ChildFolders**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneFolder`](ue_ue.MovieSceneFolder.md)\>

___

### ChildMasterTracks

• **ChildMasterTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)\>

___

### ChildObjectBindingStrings

• **ChildObjectBindingStrings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### FolderColor

• **FolderColor**: [`Color`](ue_ue_s.Color.md)

___

### FolderName

• **FolderName**: `string`

___

### SortingOrder

• **SortingOrder**: `number`

___

### \_\_tid\_MovieSceneFolder\_\_

• **\_\_tid\_MovieSceneFolder\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneFolder`](ue_ue.MovieSceneFolder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneFolder`](ue_ue.MovieSceneFolder.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneFolder`](ue_ue.MovieSceneFolder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneFolder`](ue_ue.MovieSceneFolder.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
