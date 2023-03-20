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

#### Defined in

[ue/ue.d.ts:33418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33418)

## Properties

### AssetToUse

• **AssetToUse**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:33429](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33429)

___

### Category

• **Category**: `string`

#### Defined in

[ue/ue.d.ts:33423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33423)

___

### Icon

• **Icon**: `string`

#### Defined in

[ue/ue.d.ts:33421](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33421)

___

### ImportPath

• **ImportPath**: `string`

#### Defined in

[ue/ue.d.ts:33430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33430)

___

### NextTutorial

• **NextTutorial**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:33427](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33427)

___

### PreviousTutorial

• **PreviousTutorial**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:33426](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33426)

___

### SearchTags

• **SearchTags**: `string`

#### Defined in

[ue/ue.d.ts:33432](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33432)

___

### SortOrder

• **SortOrder**: `number`

#### Defined in

[ue/ue.d.ts:33420](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33420)

___

### Stages

• **Stages**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TutorialStage`](ue_ue.TutorialStage.md)\>

#### Defined in

[ue/ue.d.ts:33425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33425)

___

### SummaryContent

• **SummaryContent**: [`TutorialContent`](ue_ue.TutorialContent.md)

#### Defined in

[ue/ue.d.ts:33424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33424)

___

### Texture

• **Texture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:33422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33422)

___

### Title

• **Title**: `string`

#### Defined in

[ue/ue.d.ts:33419](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33419)

___

### \_\_tid\_EditorTutorial\_\_

• **\_\_tid\_EditorTutorial\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:33448](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33448)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bHideInBrowser

• **bHideInBrowser**: `boolean`

#### Defined in

[ue/ue.d.ts:33431](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33431)

___

### bIsStandalone

• **bIsStandalone**: `boolean`

#### Defined in

[ue/ue.d.ts:33428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33428)

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

### GetActorReference

▸ **GetActorReference**(`PathToActor`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PathToActor` | `string` |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:33433](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33433)

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

### OnTutorialClosed

▸ **OnTutorialClosed**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33434](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33434)

___

### OnTutorialLaunched

▸ **OnTutorialLaunched**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33435](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33435)

___

### OnTutorialStageEnded

▸ **OnTutorialStageEnded**(`StageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StageName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33436](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33436)

___

### OnTutorialStageStarted

▸ **OnTutorialStageStarted**(`StageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StageName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33437](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33437)

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

#### Defined in

[ue/ue.d.ts:33438](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33438)

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

#### Defined in

[ue/ue.d.ts:33445](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33445)

___

### GetEngineFolderVisibilty

▸ `Static` **GetEngineFolderVisibilty**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:33439](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33439)

___

### GoToNextTutorialStage

▸ `Static` **GoToNextTutorialStage**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33440](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33440)

___

### GoToPreviousTutorialStage

▸ `Static` **GoToPreviousTutorialStage**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33441](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33441)

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

#### Defined in

[ue/ue.d.ts:33446](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33446)

___

### OpenAsset

▸ `Static` **OpenAsset**(`Asset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Asset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33442](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33442)

___

### SetEngineFolderVisibilty

▸ `Static` **SetEngineFolderVisibilty**(`bNewVisibility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewVisibility` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33443](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33443)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:33444](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33444)
