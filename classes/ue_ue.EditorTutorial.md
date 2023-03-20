[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorTutorial

# Class: EditorTutorial

[ue/ue](../modules/ue_ue.md).EditorTutorial

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EditorTutorial`**

  ↳↳ [`LevelEditorAttract_C`](ue_ue.Engine.Tutorial.Basics.LevelEditorAttract.LevelEditorAttract_C.md)

  ↳↳ [`LevelEditorOverview_C`](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md)

## Table of contents

### Constructors

- [constructor](ue_ue.EditorTutorial.md#constructor)

### Properties

- [AssetToUse](ue_ue.EditorTutorial.md#assettouse)
- [Category](ue_ue.EditorTutorial.md#category)
- [Icon](ue_ue.EditorTutorial.md#icon)
- [ImportPath](ue_ue.EditorTutorial.md#importpath)
- [NextTutorial](ue_ue.EditorTutorial.md#nexttutorial)
- [PreviousTutorial](ue_ue.EditorTutorial.md#previoustutorial)
- [SearchTags](ue_ue.EditorTutorial.md#searchtags)
- [SortOrder](ue_ue.EditorTutorial.md#sortorder)
- [Stages](ue_ue.EditorTutorial.md#stages)
- [SummaryContent](ue_ue.EditorTutorial.md#summarycontent)
- [Texture](ue_ue.EditorTutorial.md#texture)
- [Title](ue_ue.EditorTutorial.md#title)
- [\_\_tid\_EditorTutorial\_\_](ue_ue.EditorTutorial.md#__tid_editortutorial__)
- [\_\_tid\_Object\_\_](ue_ue.EditorTutorial.md#__tid_object__)
- [bHideInBrowser](ue_ue.EditorTutorial.md#bhideinbrowser)
- [bIsStandalone](ue_ue.EditorTutorial.md#bisstandalone)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorTutorial.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorTutorial.md#executeubergraph)
- [GetActorReference](ue_ue.EditorTutorial.md#getactorreference)
- [GetClass](ue_ue.EditorTutorial.md#getclass)
- [GetName](ue_ue.EditorTutorial.md#getname)
- [GetOuter](ue_ue.EditorTutorial.md#getouter)
- [GetWorld](ue_ue.EditorTutorial.md#getworld)
- [OnTutorialClosed](ue_ue.EditorTutorial.md#ontutorialclosed)
- [OnTutorialLaunched](ue_ue.EditorTutorial.md#ontutoriallaunched)
- [OnTutorialStageEnded](ue_ue.EditorTutorial.md#ontutorialstageended)
- [OnTutorialStageStarted](ue_ue.EditorTutorial.md#ontutorialstagestarted)
- [BeginTutorial](ue_ue.EditorTutorial.md#begintutorial)
- [Find](ue_ue.EditorTutorial.md#find)
- [GetEngineFolderVisibilty](ue_ue.EditorTutorial.md#getenginefoldervisibilty)
- [GoToNextTutorialStage](ue_ue.EditorTutorial.md#gotonexttutorialstage)
- [GoToPreviousTutorialStage](ue_ue.EditorTutorial.md#gotoprevioustutorialstage)
- [Load](ue_ue.EditorTutorial.md#load)
- [OpenAsset](ue_ue.EditorTutorial.md#openasset)
- [SetEngineFolderVisibilty](ue_ue.EditorTutorial.md#setenginefoldervisibilty)
- [StaticClass](ue_ue.EditorTutorial.md#staticclass)

## Constructors

### constructor

• **new EditorTutorial**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AssetToUse

• **AssetToUse**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### Category

• **Category**: `string`

___

### Icon

• **Icon**: `string`

___

### ImportPath

• **ImportPath**: `string`

___

### NextTutorial

• **NextTutorial**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### PreviousTutorial

• **PreviousTutorial**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### SearchTags

• **SearchTags**: `string`

___

### SortOrder

• **SortOrder**: `number`

___

### Stages

• **Stages**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TutorialStage`](ue_ue.TutorialStage.md)\>

___

### SummaryContent

• **SummaryContent**: [`TutorialContent`](ue_ue.TutorialContent.md)

___

### Texture

• **Texture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### Title

• **Title**: `string`

___

### \_\_tid\_EditorTutorial\_\_

• **\_\_tid\_EditorTutorial\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bHideInBrowser

• **bHideInBrowser**: `boolean`

___

### bIsStandalone

• **bIsStandalone**: `boolean`

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

### GetActorReference

▸ **GetActorReference**(`PathToActor`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PathToActor` | `string` |

#### Returns

[`Actor`](ue_ue.Actor.md)

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

### OnTutorialClosed

▸ **OnTutorialClosed**(): `void`

#### Returns

`void`

___

### OnTutorialLaunched

▸ **OnTutorialLaunched**(): `void`

#### Returns

`void`

___

### OnTutorialStageEnded

▸ **OnTutorialStageEnded**(`StageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StageName` | `string` |

#### Returns

`void`

___

### OnTutorialStageStarted

▸ **OnTutorialStageStarted**(`StageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StageName` | `string` |

#### Returns

`void`

___

### BeginTutorial

▸ `Static` **BeginTutorial**(`TutorialToStart`, `bRestart`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TutorialToStart` | [`$Nullable`](../modules/puerts.md#$nullable)<[`EditorTutorial`](ue_ue.EditorTutorial.md)\> |
| `bRestart` | `boolean` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorTutorial`](ue_ue.EditorTutorial.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorTutorial`](ue_ue.EditorTutorial.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### GetEngineFolderVisibilty

▸ `Static` **GetEngineFolderVisibilty**(): `boolean`

#### Returns

`boolean`

___

### GoToNextTutorialStage

▸ `Static` **GoToNextTutorialStage**(): `void`

#### Returns

`void`

___

### GoToPreviousTutorialStage

▸ `Static` **GoToPreviousTutorialStage**(): `void`

#### Returns

`void`

___

### Load

▸ `Static` **Load**(`InName`): [`EditorTutorial`](ue_ue.EditorTutorial.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorTutorial`](ue_ue.EditorTutorial.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### OpenAsset

▸ `Static` **OpenAsset**(`Asset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Asset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### SetEngineFolderVisibilty

▸ `Static` **SetEngineFolderVisibilty**(`bNewVisibility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewVisibility` | `boolean` |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
