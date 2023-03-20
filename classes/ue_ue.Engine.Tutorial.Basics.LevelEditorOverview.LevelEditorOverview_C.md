[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / [Engine](../modules/ue_ue.Engine.md) / [Tutorial](../modules/ue_ue.Engine.Tutorial.md) / [Basics](../modules/ue_ue.Engine.Tutorial.Basics.md) / [LevelEditorOverview](../modules/ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.md) / LevelEditorOverview\_C

# Class: LevelEditorOverview\_C

[Basics](../modules/ue_ue.Engine.Tutorial.Basics.md).[LevelEditorOverview](../modules/ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.md).LevelEditorOverview_C

## Hierarchy

- [`EditorTutorial`](ue_ue.EditorTutorial.md)

  ↳ **`LevelEditorOverview_C`**

## Table of contents

### Constructors

- [constructor](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#constructor)

### Properties

- [AssetToUse](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#assettouse)
- [Category](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#category)
- [Icon](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#icon)
- [ImportPath](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#importpath)
- [NextTutorial](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#nexttutorial)
- [PreviousTutorial](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#previoustutorial)
- [SearchTags](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#searchtags)
- [SortOrder](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#sortorder)
- [Stages](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#stages)
- [SummaryContent](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#summarycontent)
- [Texture](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#texture)
- [Title](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#title)
- [\_\_tid\_EditorTutorial\_\_](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#__tid_editortutorial__)
- [\_\_tid\_LevelEditorOverview\_C\_\_](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#__tid_leveleditoroverview_c__)
- [\_\_tid\_Object\_\_](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#__tid_object__)
- [bHideInBrowser](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#bhideinbrowser)
- [bIsStandalone](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#bisstandalone)

### Methods

- [CreateDefaultSubobject](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#executeubergraph)
- [GetActorReference](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#getactorreference)
- [GetClass](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#getclass)
- [GetName](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#getname)
- [GetOuter](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#getouter)
- [GetWorld](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#getworld)
- [OnTutorialClosed](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#ontutorialclosed)
- [OnTutorialLaunched](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#ontutoriallaunched)
- [OnTutorialStageEnded](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#ontutorialstageended)
- [OnTutorialStageStarted](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#ontutorialstagestarted)
- [BeginTutorial](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#begintutorial)
- [Find](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#find)
- [GetEngineFolderVisibilty](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#getenginefoldervisibilty)
- [GoToNextTutorialStage](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#gotonexttutorialstage)
- [GoToPreviousTutorialStage](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#gotoprevioustutorialstage)
- [Load](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#load)
- [OpenAsset](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#openasset)
- [SetEngineFolderVisibilty](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#setenginefoldervisibilty)
- [StaticClass](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md#staticclass)

## Constructors

### constructor

• **new LevelEditorOverview_C**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorTutorial](ue_ue.EditorTutorial.md).[constructor](ue_ue.EditorTutorial.md#constructor)

#### Defined in

[ue/ue.d.ts:44853](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44853)

## Properties

### AssetToUse

• **AssetToUse**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[AssetToUse](ue_ue.EditorTutorial.md#assettouse)

#### Defined in

[ue/ue.d.ts:33429](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33429)

___

### Category

• **Category**: `string`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[Category](ue_ue.EditorTutorial.md#category)

#### Defined in

[ue/ue.d.ts:33423](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33423)

___

### Icon

• **Icon**: `string`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[Icon](ue_ue.EditorTutorial.md#icon)

#### Defined in

[ue/ue.d.ts:33421](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33421)

___

### ImportPath

• **ImportPath**: `string`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[ImportPath](ue_ue.EditorTutorial.md#importpath)

#### Defined in

[ue/ue.d.ts:33430](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33430)

___

### NextTutorial

• **NextTutorial**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[NextTutorial](ue_ue.EditorTutorial.md#nexttutorial)

#### Defined in

[ue/ue.d.ts:33427](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33427)

___

### PreviousTutorial

• **PreviousTutorial**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[PreviousTutorial](ue_ue.EditorTutorial.md#previoustutorial)

#### Defined in

[ue/ue.d.ts:33426](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33426)

___

### SearchTags

• **SearchTags**: `string`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[SearchTags](ue_ue.EditorTutorial.md#searchtags)

#### Defined in

[ue/ue.d.ts:33432](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33432)

___

### SortOrder

• **SortOrder**: `number`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[SortOrder](ue_ue.EditorTutorial.md#sortorder)

#### Defined in

[ue/ue.d.ts:33420](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33420)

___

### Stages

• **Stages**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TutorialStage`](ue_ue.TutorialStage.md)\>

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[Stages](ue_ue.EditorTutorial.md#stages)

#### Defined in

[ue/ue.d.ts:33425](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33425)

___

### SummaryContent

• **SummaryContent**: [`TutorialContent`](ue_ue.TutorialContent.md)

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[SummaryContent](ue_ue.EditorTutorial.md#summarycontent)

#### Defined in

[ue/ue.d.ts:33424](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33424)

___

### Texture

• **Texture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[Texture](ue_ue.EditorTutorial.md#texture)

#### Defined in

[ue/ue.d.ts:33422](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33422)

___

### Title

• **Title**: `string`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[Title](ue_ue.EditorTutorial.md#title)

#### Defined in

[ue/ue.d.ts:33419](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33419)

___

### \_\_tid\_EditorTutorial\_\_

• **\_\_tid\_EditorTutorial\_\_**: `boolean`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[__tid_EditorTutorial__](ue_ue.EditorTutorial.md#__tid_editortutorial__)

#### Defined in

[ue/ue.d.ts:33448](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33448)

___

### \_\_tid\_LevelEditorOverview\_C\_\_

• **\_\_tid\_LevelEditorOverview\_C\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:44858](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44858)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[__tid_Object__](ue_ue.EditorTutorial.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bHideInBrowser

• **bHideInBrowser**: `boolean`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[bHideInBrowser](ue_ue.EditorTutorial.md#bhideinbrowser)

#### Defined in

[ue/ue.d.ts:33431](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33431)

___

### bIsStandalone

• **bIsStandalone**: `boolean`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[bIsStandalone](ue_ue.EditorTutorial.md#bisstandalone)

#### Defined in

[ue/ue.d.ts:33428](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33428)

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

[EditorTutorial](ue_ue.EditorTutorial.md).[CreateDefaultSubobject](ue_ue.EditorTutorial.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[EditorTutorial](ue_ue.EditorTutorial.md).[ExecuteUbergraph](ue_ue.EditorTutorial.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetActorReference

▸ **GetActorReference**(`PathToActor`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PathToActor` | `string` |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[GetActorReference](ue_ue.EditorTutorial.md#getactorreference)

#### Defined in

[ue/ue.d.ts:33433](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33433)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[GetClass](ue_ue.EditorTutorial.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[GetName](ue_ue.EditorTutorial.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[GetOuter](ue_ue.EditorTutorial.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[GetWorld](ue_ue.EditorTutorial.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### OnTutorialClosed

▸ **OnTutorialClosed**(): `void`

#### Returns

`void`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[OnTutorialClosed](ue_ue.EditorTutorial.md#ontutorialclosed)

#### Defined in

[ue/ue.d.ts:33434](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33434)

___

### OnTutorialLaunched

▸ **OnTutorialLaunched**(): `void`

#### Returns

`void`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[OnTutorialLaunched](ue_ue.EditorTutorial.md#ontutoriallaunched)

#### Defined in

[ue/ue.d.ts:33435](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33435)

___

### OnTutorialStageEnded

▸ **OnTutorialStageEnded**(`StageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StageName` | `string` |

#### Returns

`void`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[OnTutorialStageEnded](ue_ue.EditorTutorial.md#ontutorialstageended)

#### Defined in

[ue/ue.d.ts:33436](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33436)

___

### OnTutorialStageStarted

▸ **OnTutorialStageStarted**(`StageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StageName` | `string` |

#### Returns

`void`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[OnTutorialStageStarted](ue_ue.EditorTutorial.md#ontutorialstagestarted)

#### Defined in

[ue/ue.d.ts:33437](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33437)

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

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[BeginTutorial](ue_ue.EditorTutorial.md#begintutorial)

#### Defined in

[ue/ue.d.ts:33438](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33438)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelEditorOverview_C`](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelEditorOverview_C`](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md)

#### Overrides

[EditorTutorial](ue_ue.EditorTutorial.md).[Find](ue_ue.EditorTutorial.md#find)

#### Defined in

[ue/ue.d.ts:44855](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44855)

___

### GetEngineFolderVisibilty

▸ `Static` **GetEngineFolderVisibilty**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[GetEngineFolderVisibilty](ue_ue.EditorTutorial.md#getenginefoldervisibilty)

#### Defined in

[ue/ue.d.ts:33439](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33439)

___

### GoToNextTutorialStage

▸ `Static` **GoToNextTutorialStage**(): `void`

#### Returns

`void`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[GoToNextTutorialStage](ue_ue.EditorTutorial.md#gotonexttutorialstage)

#### Defined in

[ue/ue.d.ts:33440](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33440)

___

### GoToPreviousTutorialStage

▸ `Static` **GoToPreviousTutorialStage**(): `void`

#### Returns

`void`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[GoToPreviousTutorialStage](ue_ue.EditorTutorial.md#gotoprevioustutorialstage)

#### Defined in

[ue/ue.d.ts:33441](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33441)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelEditorOverview_C`](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelEditorOverview_C`](ue_ue.Engine.Tutorial.Basics.LevelEditorOverview.LevelEditorOverview_C.md)

#### Overrides

[EditorTutorial](ue_ue.EditorTutorial.md).[Load](ue_ue.EditorTutorial.md#load)

#### Defined in

[ue/ue.d.ts:44856](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44856)

___

### OpenAsset

▸ `Static` **OpenAsset**(`Asset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Asset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[OpenAsset](ue_ue.EditorTutorial.md#openasset)

#### Defined in

[ue/ue.d.ts:33442](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33442)

___

### SetEngineFolderVisibilty

▸ `Static` **SetEngineFolderVisibilty**(`bNewVisibility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewVisibility` | `boolean` |

#### Returns

`void`

#### Inherited from

[EditorTutorial](ue_ue.EditorTutorial.md).[SetEngineFolderVisibilty](ue_ue.EditorTutorial.md#setenginefoldervisibilty)

#### Defined in

[ue/ue.d.ts:33443](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33443)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorTutorial](ue_ue.EditorTutorial.md).[StaticClass](ue_ue.EditorTutorial.md#staticclass)

#### Defined in

[ue/ue.d.ts:44854](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44854)
