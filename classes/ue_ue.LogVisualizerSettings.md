[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LogVisualizerSettings

# Class: LogVisualizerSettings

[ue/ue](../modules/ue_ue.md).LogVisualizerSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LogVisualizerSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.LogVisualizerSettings.md#constructor)

### Properties

- [DebugMeshMaterialFakeLight](ue_ue.LogVisualizerSettings.md#debugmeshmaterialfakelight)
- [DebugMeshMaterialFakeLightName](ue_ue.LogVisualizerSettings.md#debugmeshmaterialfakelightname)
- [DefaultCameraDistance](ue_ue.LogVisualizerSettings.md#defaultcameradistance)
- [GraphsBackgroundColor](ue_ue.LogVisualizerSettings.md#graphsbackgroundcolor)
- [PresistentFilters](ue_ue.LogVisualizerSettings.md#presistentfilters)
- [TrivialLogsThreshold](ue_ue.LogVisualizerSettings.md#triviallogsthreshold)
- [\_\_tid\_LogVisualizerSettings\_\_](ue_ue.LogVisualizerSettings.md#__tid_logvisualizersettings__)
- [\_\_tid\_Object\_\_](ue_ue.LogVisualizerSettings.md#__tid_object__)
- [bConstrainGraphToLocalMinMax](ue_ue.LogVisualizerSettings.md#bconstraingraphtolocalminmax)
- [bDrawExtremesOnGraphs](ue_ue.LogVisualizerSettings.md#bdrawextremesongraphs)
- [bIgnoreTrivialLogs](ue_ue.LogVisualizerSettings.md#bignoretriviallogs)
- [bLogNavOctreeOnStop](ue_ue.LogVisualizerSettings.md#blognavoctreeonstop)
- [bPresistentFilters](ue_ue.LogVisualizerSettings.md#bpresistentfilters)
- [bResetDataWithNewSession](ue_ue.LogVisualizerSettings.md#bresetdatawithnewsession)
- [bSearchInsideLogs](ue_ue.LogVisualizerSettings.md#bsearchinsidelogs)
- [bShowHistogramLabelsOutside](ue_ue.LogVisualizerSettings.md#bshowhistogramlabelsoutside)
- [bStickToRecentData](ue_ue.LogVisualizerSettings.md#bsticktorecentdata)
- [bUsePlayersOnlyForPause](ue_ue.LogVisualizerSettings.md#buseplayersonlyforpause)

### Methods

- [CreateDefaultSubobject](ue_ue.LogVisualizerSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LogVisualizerSettings.md#executeubergraph)
- [GetClass](ue_ue.LogVisualizerSettings.md#getclass)
- [GetName](ue_ue.LogVisualizerSettings.md#getname)
- [GetOuter](ue_ue.LogVisualizerSettings.md#getouter)
- [GetWorld](ue_ue.LogVisualizerSettings.md#getworld)
- [Find](ue_ue.LogVisualizerSettings.md#find)
- [Load](ue_ue.LogVisualizerSettings.md#load)
- [StaticClass](ue_ue.LogVisualizerSettings.md#staticclass)

## Constructors

### constructor

• **new LogVisualizerSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### DebugMeshMaterialFakeLight

• **DebugMeshMaterialFakeLight**: [`Material`](ue_ue.Material.md)

___

### DebugMeshMaterialFakeLightName

• **DebugMeshMaterialFakeLightName**: `string`

___

### DefaultCameraDistance

• **DefaultCameraDistance**: `number`

___

### GraphsBackgroundColor

• **GraphsBackgroundColor**: [`Color`](ue_ue_s.Color.md)

___

### PresistentFilters

• **PresistentFilters**: [`VisualLoggerFiltersData`](ue_ue.VisualLoggerFiltersData.md)

___

### TrivialLogsThreshold

• **TrivialLogsThreshold**: `number`

___

### \_\_tid\_LogVisualizerSettings\_\_

• **\_\_tid\_LogVisualizerSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bConstrainGraphToLocalMinMax

• **bConstrainGraphToLocalMinMax**: `boolean`

___

### bDrawExtremesOnGraphs

• **bDrawExtremesOnGraphs**: `boolean`

___

### bIgnoreTrivialLogs

• **bIgnoreTrivialLogs**: `boolean`

___

### bLogNavOctreeOnStop

• **bLogNavOctreeOnStop**: `boolean`

___

### bPresistentFilters

• **bPresistentFilters**: `boolean`

___

### bResetDataWithNewSession

• **bResetDataWithNewSession**: `boolean`

___

### bSearchInsideLogs

• **bSearchInsideLogs**: `boolean`

___

### bShowHistogramLabelsOutside

• **bShowHistogramLabelsOutside**: `boolean`

___

### bStickToRecentData

• **bStickToRecentData**: `boolean`

___

### bUsePlayersOnlyForPause

• **bUsePlayersOnlyForPause**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LogVisualizerSettings`](ue_ue.LogVisualizerSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LogVisualizerSettings`](ue_ue.LogVisualizerSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LogVisualizerSettings`](ue_ue.LogVisualizerSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LogVisualizerSettings`](ue_ue.LogVisualizerSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
