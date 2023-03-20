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

## Properties

### AllowEditsMode

• **AllowEditsMode**: [`EAllowEditsMode`](../enums/ue_ue.EAllowEditsMode.md)

___

### AutoChangeMode

• **AutoChangeMode**: [`EAutoChangeMode`](../enums/ue_ue.EAutoChangeMode.md)

___

### FrameNumberDisplayFormat

• **FrameNumberDisplayFormat**: [`EFrameNumberDisplayFormats`](../enums/ue_ue.EFrameNumberDisplayFormats.md)

___

### KeyGroupMode

• **KeyGroupMode**: [`EKeyGroupMode`](../enums/ue_ue.EKeyGroupMode.md)

___

### KeyInterpolation

• **KeyInterpolation**: [`EMovieSceneKeyInterpolation`](../enums/ue_ue.EMovieSceneKeyInterpolation.md)

___

### LoopMode

• **LoopMode**: [`ESequencerLoopMode`](../enums/ue_ue.ESequencerLoopMode.md)

___

### SpawnPosition

• **SpawnPosition**: [`ESequencerSpawnPosition`](../enums/ue_ue.ESequencerSpawnPosition.md)

___

### TrajectoryPathCap

• **TrajectoryPathCap**: `number`

___

### ZeroPadFrames

• **ZeroPadFrames**: `number`

___

### ZoomPosition

• **ZoomPosition**: [`ESequencerZoomPosition`](../enums/ue_ue.ESequencerZoomPosition.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_SequencerSettings\_\_

• **\_\_tid\_SequencerSettings\_\_**: `boolean`

___

### bActivateRealtimeViewports

• **bActivateRealtimeViewports**: `boolean`

___

### bAutoScrollEnabled

• **bAutoScrollEnabled**: `boolean`

___

### bAutoSetTrackDefaults

• **bAutoSetTrackDefaults**: `boolean`

___

### bCompileDirectorOnEvaluate

• **bCompileDirectorOnEvaluate**: `boolean`

___

### bCreateSpawnableCameras

• **bCreateSpawnableCameras**: `boolean`

___

### bDeleteKeysWhenTrimming

• **bDeleteKeysWhenTrimming**: `boolean`

___

### bEvaluateSubSequencesInIsolation

• **bEvaluateSubSequencesInIsolation**: `boolean`

___

### bInfiniteKeyAreas

• **bInfiniteKeyAreas**: `boolean`

___

### bIsSnapEnabled

• **bIsSnapEnabled**: `boolean`

___

### bIsolateCurveEditorToSelection

• **bIsolateCurveEditorToSelection**: `boolean`

___

### bKeepCursorInPlayRange

• **bKeepCursorInPlayRange**: `boolean`

___

### bKeepCursorInPlayRangeWhileScrubbing

• **bKeepCursorInPlayRangeWhileScrubbing**: `boolean`

___

### bKeepPlayRangeInSectionBounds

• **bKeepPlayRangeInSectionBounds**: `boolean`

___

### bKeyInterpPropertiesOnly

• **bKeyInterpPropertiesOnly**: `boolean`

___

### bLabelBrowserVisible

• **bLabelBrowserVisible**: `boolean`

___

### bLinkCurveEditorTimeRange

• **bLinkCurveEditorTimeRange**: `boolean`

___

### bRerunConstructionScripts

• **bRerunConstructionScripts**: `boolean`

___

### bRewindOnRecord

• **bRewindOnRecord**: `boolean`

___

### bShowChannelColors

• **bShowChannelColors**: `boolean`

___

### bShowCombinedKeyframes

• **bShowCombinedKeyframes**: `boolean`

___

### bShowDebugVisualization

• **bShowDebugVisualization**: `boolean`

___

### bShowOutlinerInfoColumn

• **bShowOutlinerInfoColumn**: `boolean`

___

### bShowRangeSlider

• **bShowRangeSlider**: `boolean`

___

### bShowSelectedNodesOnly

• **bShowSelectedNodesOnly**: `boolean`

___

### bSnapCurveValueToInterval

• **bSnapCurveValueToInterval**: `boolean`

___

### bSnapKeyTimesToInterval

• **bSnapKeyTimesToInterval**: `boolean`

___

### bSnapKeyTimesToKeys

• **bSnapKeyTimesToKeys**: `boolean`

___

### bSnapKeysAndSectionsToPlayRange

• **bSnapKeysAndSectionsToPlayRange**: `boolean`

___

### bSnapPlayTimeToDraggedKey

• **bSnapPlayTimeToDraggedKey**: `boolean`

___

### bSnapPlayTimeToInterval

• **bSnapPlayTimeToInterval**: `boolean`

___

### bSnapPlayTimeToKeys

• **bSnapPlayTimeToKeys**: `boolean`

___

### bSnapPlayTimeToPressedKey

• **bSnapPlayTimeToPressedKey**: `boolean`

___

### bSnapSectionTimesToInterval

• **bSnapSectionTimesToInterval**: `boolean`

___

### bSnapSectionTimesToSections

• **bSnapSectionTimesToSections**: `boolean`

___

### bSynchronizeCurveEditorSelection

• **bSynchronizeCurveEditorSelection**: `boolean`

___

### bVisualizePreAndPostRoll

• **bVisualizePreAndPostRoll**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
