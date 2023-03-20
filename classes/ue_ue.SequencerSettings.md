[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SequencerSettings

# Class: SequencerSettings

[ue/ue](../modules/ue_ue.md).SequencerSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SequencerSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.SequencerSettings.md#constructor)

### Properties

- [AllowEditsMode](ue_ue.SequencerSettings.md#alloweditsmode)
- [AutoChangeMode](ue_ue.SequencerSettings.md#autochangemode)
- [FrameNumberDisplayFormat](ue_ue.SequencerSettings.md#framenumberdisplayformat)
- [KeyGroupMode](ue_ue.SequencerSettings.md#keygroupmode)
- [KeyInterpolation](ue_ue.SequencerSettings.md#keyinterpolation)
- [LoopMode](ue_ue.SequencerSettings.md#loopmode)
- [SpawnPosition](ue_ue.SequencerSettings.md#spawnposition)
- [TrajectoryPathCap](ue_ue.SequencerSettings.md#trajectorypathcap)
- [ZeroPadFrames](ue_ue.SequencerSettings.md#zeropadframes)
- [ZoomPosition](ue_ue.SequencerSettings.md#zoomposition)
- [\_\_tid\_Object\_\_](ue_ue.SequencerSettings.md#__tid_object__)
- [\_\_tid\_SequencerSettings\_\_](ue_ue.SequencerSettings.md#__tid_sequencersettings__)
- [bActivateRealtimeViewports](ue_ue.SequencerSettings.md#bactivaterealtimeviewports)
- [bAutoScrollEnabled](ue_ue.SequencerSettings.md#bautoscrollenabled)
- [bAutoSetTrackDefaults](ue_ue.SequencerSettings.md#bautosettrackdefaults)
- [bCompileDirectorOnEvaluate](ue_ue.SequencerSettings.md#bcompiledirectoronevaluate)
- [bCreateSpawnableCameras](ue_ue.SequencerSettings.md#bcreatespawnablecameras)
- [bDeleteKeysWhenTrimming](ue_ue.SequencerSettings.md#bdeletekeyswhentrimming)
- [bEvaluateSubSequencesInIsolation](ue_ue.SequencerSettings.md#bevaluatesubsequencesinisolation)
- [bInfiniteKeyAreas](ue_ue.SequencerSettings.md#binfinitekeyareas)
- [bIsSnapEnabled](ue_ue.SequencerSettings.md#bissnapenabled)
- [bIsolateCurveEditorToSelection](ue_ue.SequencerSettings.md#bisolatecurveeditortoselection)
- [bKeepCursorInPlayRange](ue_ue.SequencerSettings.md#bkeepcursorinplayrange)
- [bKeepCursorInPlayRangeWhileScrubbing](ue_ue.SequencerSettings.md#bkeepcursorinplayrangewhilescrubbing)
- [bKeepPlayRangeInSectionBounds](ue_ue.SequencerSettings.md#bkeepplayrangeinsectionbounds)
- [bKeyInterpPropertiesOnly](ue_ue.SequencerSettings.md#bkeyinterppropertiesonly)
- [bLabelBrowserVisible](ue_ue.SequencerSettings.md#blabelbrowservisible)
- [bLinkCurveEditorTimeRange](ue_ue.SequencerSettings.md#blinkcurveeditortimerange)
- [bRerunConstructionScripts](ue_ue.SequencerSettings.md#brerunconstructionscripts)
- [bRewindOnRecord](ue_ue.SequencerSettings.md#brewindonrecord)
- [bShowChannelColors](ue_ue.SequencerSettings.md#bshowchannelcolors)
- [bShowCombinedKeyframes](ue_ue.SequencerSettings.md#bshowcombinedkeyframes)
- [bShowDebugVisualization](ue_ue.SequencerSettings.md#bshowdebugvisualization)
- [bShowOutlinerInfoColumn](ue_ue.SequencerSettings.md#bshowoutlinerinfocolumn)
- [bShowRangeSlider](ue_ue.SequencerSettings.md#bshowrangeslider)
- [bShowSelectedNodesOnly](ue_ue.SequencerSettings.md#bshowselectednodesonly)
- [bSnapCurveValueToInterval](ue_ue.SequencerSettings.md#bsnapcurvevaluetointerval)
- [bSnapKeyTimesToInterval](ue_ue.SequencerSettings.md#bsnapkeytimestointerval)
- [bSnapKeyTimesToKeys](ue_ue.SequencerSettings.md#bsnapkeytimestokeys)
- [bSnapKeysAndSectionsToPlayRange](ue_ue.SequencerSettings.md#bsnapkeysandsectionstoplayrange)
- [bSnapPlayTimeToDraggedKey](ue_ue.SequencerSettings.md#bsnapplaytimetodraggedkey)
- [bSnapPlayTimeToInterval](ue_ue.SequencerSettings.md#bsnapplaytimetointerval)
- [bSnapPlayTimeToKeys](ue_ue.SequencerSettings.md#bsnapplaytimetokeys)
- [bSnapPlayTimeToPressedKey](ue_ue.SequencerSettings.md#bsnapplaytimetopressedkey)
- [bSnapSectionTimesToInterval](ue_ue.SequencerSettings.md#bsnapsectiontimestointerval)
- [bSnapSectionTimesToSections](ue_ue.SequencerSettings.md#bsnapsectiontimestosections)
- [bSynchronizeCurveEditorSelection](ue_ue.SequencerSettings.md#bsynchronizecurveeditorselection)
- [bVisualizePreAndPostRoll](ue_ue.SequencerSettings.md#bvisualizepreandpostroll)

### Methods

- [CreateDefaultSubobject](ue_ue.SequencerSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SequencerSettings.md#executeubergraph)
- [GetClass](ue_ue.SequencerSettings.md#getclass)
- [GetName](ue_ue.SequencerSettings.md#getname)
- [GetOuter](ue_ue.SequencerSettings.md#getouter)
- [GetWorld](ue_ue.SequencerSettings.md#getworld)
- [Find](ue_ue.SequencerSettings.md#find)
- [Load](ue_ue.SequencerSettings.md#load)
- [StaticClass](ue_ue.SequencerSettings.md#staticclass)

## Constructors

### constructor

• **new SequencerSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:60237](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60237)

## Properties

### AllowEditsMode

• **AllowEditsMode**: [`EAllowEditsMode`](../enums/ue_ue.EAllowEditsMode.md)

#### Defined in

[ue/ue.d.ts:60239](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60239)

___

### AutoChangeMode

• **AutoChangeMode**: [`EAutoChangeMode`](../enums/ue_ue.EAutoChangeMode.md)

#### Defined in

[ue/ue.d.ts:60238](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60238)

___

### FrameNumberDisplayFormat

• **FrameNumberDisplayFormat**: [`EFrameNumberDisplayFormats`](../enums/ue_ue.EFrameNumberDisplayFormats.md)

#### Defined in

[ue/ue.d.ts:60283](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60283)

___

### KeyGroupMode

• **KeyGroupMode**: [`EKeyGroupMode`](../enums/ue_ue.EKeyGroupMode.md)

#### Defined in

[ue/ue.d.ts:60240](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60240)

___

### KeyInterpolation

• **KeyInterpolation**: [`EMovieSceneKeyInterpolation`](../enums/ue_ue.EMovieSceneKeyInterpolation.md)

#### Defined in

[ue/ue.d.ts:60242](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60242)

___

### LoopMode

• **LoopMode**: [`ESequencerLoopMode`](../enums/ue_ue.ESequencerLoopMode.md)

#### Defined in

[ue/ue.d.ts:60266](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60266)

___

### SpawnPosition

• **SpawnPosition**: [`ESequencerSpawnPosition`](../enums/ue_ue.ESequencerSpawnPosition.md)

#### Defined in

[ue/ue.d.ts:60244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60244)

___

### TrajectoryPathCap

• **TrajectoryPathCap**: `number`

#### Defined in

[ue/ue.d.ts:60281](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60281)

___

### ZeroPadFrames

• **ZeroPadFrames**: `number`

#### Defined in

[ue/ue.d.ts:60270](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60270)

___

### ZoomPosition

• **ZoomPosition**: [`ESequencerZoomPosition`](../enums/ue_ue.ESequencerZoomPosition.md)

#### Defined in

[ue/ue.d.ts:60261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60261)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SequencerSettings\_\_

• **\_\_tid\_SequencerSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:60288](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60288)

___

### bActivateRealtimeViewports

• **bActivateRealtimeViewports**: `boolean`

#### Defined in

[ue/ue.d.ts:60275](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60275)

___

### bAutoScrollEnabled

• **bAutoScrollEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:60262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60262)

___

### bAutoSetTrackDefaults

• **bAutoSetTrackDefaults**: `boolean`

#### Defined in

[ue/ue.d.ts:60243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60243)

___

### bCompileDirectorOnEvaluate

• **bCompileDirectorOnEvaluate**: `boolean`

#### Defined in

[ue/ue.d.ts:60280](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60280)

___

### bCreateSpawnableCameras

• **bCreateSpawnableCameras**: `boolean`

#### Defined in

[ue/ue.d.ts:60245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60245)

___

### bDeleteKeysWhenTrimming

• **bDeleteKeysWhenTrimming**: `boolean`

#### Defined in

[ue/ue.d.ts:60274](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60274)

___

### bEvaluateSubSequencesInIsolation

• **bEvaluateSubSequencesInIsolation**: `boolean`

#### Defined in

[ue/ue.d.ts:60276](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60276)

___

### bInfiniteKeyAreas

• **bInfiniteKeyAreas**: `boolean`

#### Defined in

[ue/ue.d.ts:60272](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60272)

___

### bIsSnapEnabled

• **bIsSnapEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:60247](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60247)

___

### bIsolateCurveEditorToSelection

• **bIsolateCurveEditorToSelection**: `boolean`

#### Defined in

[ue/ue.d.ts:60265](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60265)

___

### bKeepCursorInPlayRange

• **bKeepCursorInPlayRange**: `boolean`

#### Defined in

[ue/ue.d.ts:60268](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60268)

___

### bKeepCursorInPlayRangeWhileScrubbing

• **bKeepCursorInPlayRangeWhileScrubbing**: `boolean`

#### Defined in

[ue/ue.d.ts:60267](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60267)

___

### bKeepPlayRangeInSectionBounds

• **bKeepPlayRangeInSectionBounds**: `boolean`

#### Defined in

[ue/ue.d.ts:60269](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60269)

___

### bKeyInterpPropertiesOnly

• **bKeyInterpPropertiesOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:60241](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60241)

___

### bLabelBrowserVisible

• **bLabelBrowserVisible**: `boolean`

#### Defined in

[ue/ue.d.ts:60258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60258)

___

### bLinkCurveEditorTimeRange

• **bLinkCurveEditorTimeRange**: `boolean`

#### Defined in

[ue/ue.d.ts:60263](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60263)

___

### bRerunConstructionScripts

• **bRerunConstructionScripts**: `boolean`

#### Defined in

[ue/ue.d.ts:60277](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60277)

___

### bRewindOnRecord

• **bRewindOnRecord**: `boolean`

#### Defined in

[ue/ue.d.ts:60260](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60260)

___

### bShowChannelColors

• **bShowChannelColors**: `boolean`

#### Defined in

[ue/ue.d.ts:60273](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60273)

___

### bShowCombinedKeyframes

• **bShowCombinedKeyframes**: `boolean`

#### Defined in

[ue/ue.d.ts:60271](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60271)

___

### bShowDebugVisualization

• **bShowDebugVisualization**: `boolean`

#### Defined in

[ue/ue.d.ts:60278](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60278)

___

### bShowOutlinerInfoColumn

• **bShowOutlinerInfoColumn**: `boolean`

#### Defined in

[ue/ue.d.ts:60282](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60282)

___

### bShowRangeSlider

• **bShowRangeSlider**: `boolean`

#### Defined in

[ue/ue.d.ts:60246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60246)

___

### bShowSelectedNodesOnly

• **bShowSelectedNodesOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:60259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60259)

___

### bSnapCurveValueToInterval

• **bSnapCurveValueToInterval**: `boolean`

#### Defined in

[ue/ue.d.ts:60257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60257)

___

### bSnapKeyTimesToInterval

• **bSnapKeyTimesToInterval**: `boolean`

#### Defined in

[ue/ue.d.ts:60248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60248)

___

### bSnapKeyTimesToKeys

• **bSnapKeyTimesToKeys**: `boolean`

#### Defined in

[ue/ue.d.ts:60249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60249)

___

### bSnapKeysAndSectionsToPlayRange

• **bSnapKeysAndSectionsToPlayRange**: `boolean`

#### Defined in

[ue/ue.d.ts:60252](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60252)

___

### bSnapPlayTimeToDraggedKey

• **bSnapPlayTimeToDraggedKey**: `boolean`

#### Defined in

[ue/ue.d.ts:60256](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60256)

___

### bSnapPlayTimeToInterval

• **bSnapPlayTimeToInterval**: `boolean`

#### Defined in

[ue/ue.d.ts:60254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60254)

___

### bSnapPlayTimeToKeys

• **bSnapPlayTimeToKeys**: `boolean`

#### Defined in

[ue/ue.d.ts:60253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60253)

___

### bSnapPlayTimeToPressedKey

• **bSnapPlayTimeToPressedKey**: `boolean`

#### Defined in

[ue/ue.d.ts:60255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60255)

___

### bSnapSectionTimesToInterval

• **bSnapSectionTimesToInterval**: `boolean`

#### Defined in

[ue/ue.d.ts:60250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60250)

___

### bSnapSectionTimesToSections

• **bSnapSectionTimesToSections**: `boolean`

#### Defined in

[ue/ue.d.ts:60251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60251)

___

### bSynchronizeCurveEditorSelection

• **bSynchronizeCurveEditorSelection**: `boolean`

#### Defined in

[ue/ue.d.ts:60264](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60264)

___

### bVisualizePreAndPostRoll

• **bVisualizePreAndPostRoll**: `boolean`

#### Defined in

[ue/ue.d.ts:60279](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60279)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SequencerSettings`](ue_ue.SequencerSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SequencerSettings`](ue_ue.SequencerSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:60285](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60285)

___

### Load

▸ `Static` **Load**(`InName`): [`SequencerSettings`](ue_ue.SequencerSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SequencerSettings`](ue_ue.SequencerSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:60286](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60286)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:60284](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L60284)
