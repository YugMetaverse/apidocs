[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorLevelUtils

# Class: EditorLevelUtils

[ue/ue](../modules/ue_ue.md).EditorLevelUtils

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EditorLevelUtils`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorLevelUtils.md#constructor)

### Properties

- [\_\_tid\_EditorLevelUtils\_\_](ue_ue.EditorLevelUtils.md#__tid_editorlevelutils__)
- [\_\_tid\_Object\_\_](ue_ue.EditorLevelUtils.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorLevelUtils.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorLevelUtils.md#executeubergraph)
- [GetClass](ue_ue.EditorLevelUtils.md#getclass)
- [GetName](ue_ue.EditorLevelUtils.md#getname)
- [GetOuter](ue_ue.EditorLevelUtils.md#getouter)
- [GetWorld](ue_ue.EditorLevelUtils.md#getworld)
- [CreateNewStreamingLevel](ue_ue.EditorLevelUtils.md#createnewstreaminglevel)
- [Find](ue_ue.EditorLevelUtils.md#find)
- [Load](ue_ue.EditorLevelUtils.md#load)
- [MakeLevelCurrent](ue_ue.EditorLevelUtils.md#makelevelcurrent)
- [MoveActorsToLevel](ue_ue.EditorLevelUtils.md#moveactorstolevel)
- [MoveSelectedActorsToLevel](ue_ue.EditorLevelUtils.md#moveselectedactorstolevel)
- [SetLevelVisibility](ue_ue.EditorLevelUtils.md#setlevelvisibility)
- [SetLevelsVisibility](ue_ue.EditorLevelUtils.md#setlevelsvisibility)
- [StaticClass](ue_ue.EditorLevelUtils.md#staticclass)

## Constructors

### constructor

• **new EditorLevelUtils**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_EditorLevelUtils\_\_

• **\_\_tid\_EditorLevelUtils\_\_**: `boolean`

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

### CreateNewStreamingLevel

▸ `Static` **CreateNewStreamingLevel**(`LevelStreamingClass`, `NewLevelPath?`, `bMoveSelectedActorsIntoNewLevel?`): [`LevelStreaming`](ue_ue.LevelStreaming.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LevelStreamingClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `NewLevelPath?` | `string` |
| `bMoveSelectedActorsIntoNewLevel?` | `boolean` |

#### Returns

[`LevelStreaming`](ue_ue.LevelStreaming.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorLevelUtils`](ue_ue.EditorLevelUtils.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorLevelUtils`](ue_ue.EditorLevelUtils.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorLevelUtils`](ue_ue.EditorLevelUtils.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorLevelUtils`](ue_ue.EditorLevelUtils.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### MakeLevelCurrent

▸ `Static` **MakeLevelCurrent**(`InStreamingLevel`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InStreamingLevel` | [`$Nullable`](../modules/puerts.md#$nullable)<[`LevelStreaming`](ue_ue.LevelStreaming.md)\> |

#### Returns

`void`

___

### MoveActorsToLevel

▸ `Static` **MoveActorsToLevel**(`ActorsToMove`, `DestStreamingLevel`, `bWarnAboutReferences?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorsToMove` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |
| `DestStreamingLevel` | [`$Nullable`](../modules/puerts.md#$nullable)<[`LevelStreaming`](ue_ue.LevelStreaming.md)\> |
| `bWarnAboutReferences?` | `boolean` |

#### Returns

`number`

___

### MoveSelectedActorsToLevel

▸ `Static` **MoveSelectedActorsToLevel**(`DestLevel`, `bWarnAboutReferences?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DestLevel` | [`$Nullable`](../modules/puerts.md#$nullable)<[`LevelStreaming`](ue_ue.LevelStreaming.md)\> |
| `bWarnAboutReferences?` | `boolean` |

#### Returns

`number`

___

### SetLevelVisibility

▸ `Static` **SetLevelVisibility**(`Level`, `bShouldBeVisible`, `bForceLayersVisible`, `ModifyMode?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Level` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Level`](ue_ue.Level.md)\> |
| `bShouldBeVisible` | `boolean` |
| `bForceLayersVisible` | `boolean` |
| `ModifyMode?` | [`ELevelVisibilityDirtyMode`](../enums/ue_ue.ELevelVisibilityDirtyMode.md) |

#### Returns

`void`

___

### SetLevelsVisibility

▸ `Static` **SetLevelsVisibility**(`Levels`, `bShouldBeVisible`, `bForceLayersVisible`, `ModifyMode?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Levels` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Level`](ue_ue.Level.md)\> |
| `bShouldBeVisible` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\> |
| `bForceLayersVisible` | `boolean` |
| `ModifyMode?` | [`ELevelVisibilityDirtyMode`](../enums/ue_ue.ELevelVisibilityDirtyMode.md) |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
