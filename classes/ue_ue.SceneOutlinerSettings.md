[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SceneOutlinerSettings

# Class: SceneOutlinerSettings

[ue/ue](../modules/ue_ue.md).SceneOutlinerSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SceneOutlinerSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.SceneOutlinerSettings.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.SceneOutlinerSettings.md#__tid_object__)
- [\_\_tid\_SceneOutlinerSettings\_\_](ue_ue.SceneOutlinerSettings.md#__tid_sceneoutlinersettings__)
- [bHideFoldersContainingHiddenActors](ue_ue.SceneOutlinerSettings.md#bhidefolderscontaininghiddenactors)
- [bHideTemporaryActors](ue_ue.SceneOutlinerSettings.md#bhidetemporaryactors)
- [bShowActorComponents](ue_ue.SceneOutlinerSettings.md#bshowactorcomponents)
- [bShowOnlyActorsInCurrentLevel](ue_ue.SceneOutlinerSettings.md#bshowonlyactorsincurrentlevel)
- [bShowOnlySelectedActors](ue_ue.SceneOutlinerSettings.md#bshowonlyselectedactors)

### Methods

- [CreateDefaultSubobject](ue_ue.SceneOutlinerSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SceneOutlinerSettings.md#executeubergraph)
- [GetClass](ue_ue.SceneOutlinerSettings.md#getclass)
- [GetName](ue_ue.SceneOutlinerSettings.md#getname)
- [GetOuter](ue_ue.SceneOutlinerSettings.md#getouter)
- [GetWorld](ue_ue.SceneOutlinerSettings.md#getworld)
- [Find](ue_ue.SceneOutlinerSettings.md#find)
- [Load](ue_ue.SceneOutlinerSettings.md#load)
- [StaticClass](ue_ue.SceneOutlinerSettings.md#staticclass)

## Constructors

### constructor

• **new SceneOutlinerSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_SceneOutlinerSettings\_\_

• **\_\_tid\_SceneOutlinerSettings\_\_**: `boolean`

___

### bHideFoldersContainingHiddenActors

• **bHideFoldersContainingHiddenActors**: `boolean`

___

### bHideTemporaryActors

• **bHideTemporaryActors**: `boolean`

___

### bShowActorComponents

• **bShowActorComponents**: `boolean`

___

### bShowOnlyActorsInCurrentLevel

• **bShowOnlyActorsInCurrentLevel**: `boolean`

___

### bShowOnlySelectedActors

• **bShowOnlySelectedActors**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SceneOutlinerSettings`](ue_ue.SceneOutlinerSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SceneOutlinerSettings`](ue_ue.SceneOutlinerSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SceneOutlinerSettings`](ue_ue.SceneOutlinerSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SceneOutlinerSettings`](ue_ue.SceneOutlinerSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
