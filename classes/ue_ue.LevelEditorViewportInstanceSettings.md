[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelEditorViewportInstanceSettings

# Class: LevelEditorViewportInstanceSettings

[ue/ue](../modules/ue_ue.md).LevelEditorViewportInstanceSettings

## Table of contents

### Constructors

- [constructor](ue_ue.LevelEditorViewportInstanceSettings.md#constructor)

### Properties

- [BufferVisualizationMode](ue_ue.LevelEditorViewportInstanceSettings.md#buffervisualizationmode)
- [EditorShowFlagsString](ue_ue.LevelEditorViewportInstanceSettings.md#editorshowflagsstring)
- [EnabledStats](ue_ue.LevelEditorViewportInstanceSettings.md#enabledstats)
- [ExposureSettings](ue_ue.LevelEditorViewportInstanceSettings.md#exposuresettings)
- [FOVAngle](ue_ue.LevelEditorViewportInstanceSettings.md#fovangle)
- [FarViewPlane](ue_ue.LevelEditorViewportInstanceSettings.md#farviewplane)
- [GameShowFlagsString](ue_ue.LevelEditorViewportInstanceSettings.md#gameshowflagsstring)
- [OrthoViewModeIndex](ue_ue.LevelEditorViewportInstanceSettings.md#orthoviewmodeindex)
- [PerspViewModeIndex](ue_ue.LevelEditorViewportInstanceSettings.md#perspviewmodeindex)
- [RayTracingDebugVisualizationMode](ue_ue.LevelEditorViewportInstanceSettings.md#raytracingdebugvisualizationmode)
- [ViewportType](ue_ue.LevelEditorViewportInstanceSettings.md#viewporttype)
- [\_\_tid\_LevelEditorViewportInstanceSettings\_\_](ue_ue.LevelEditorViewportInstanceSettings.md#__tid_leveleditorviewportinstancesettings__)
- [bIsRealtime](ue_ue.LevelEditorViewportInstanceSettings.md#bisrealtime)
- [bShowFPS](ue_ue.LevelEditorViewportInstanceSettings.md#bshowfps)
- [bShowFullToolbar](ue_ue.LevelEditorViewportInstanceSettings.md#bshowfulltoolbar)
- [bShowOnScreenStats](ue_ue.LevelEditorViewportInstanceSettings.md#bshowonscreenstats)

### Methods

- [StaticClass](ue_ue.LevelEditorViewportInstanceSettings.md#staticclass)
- [StaticStruct](ue_ue.LevelEditorViewportInstanceSettings.md#staticstruct)

## Constructors

### constructor

• **new LevelEditorViewportInstanceSettings**()

#### Defined in

[ue/ue.d.ts:45004](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45004)

• **new LevelEditorViewportInstanceSettings**(`ViewportType`, `PerspViewModeIndex`, `OrthoViewModeIndex`, `EditorShowFlagsString`, `GameShowFlagsString`, `BufferVisualizationMode`, `RayTracingDebugVisualizationMode`, `ExposureSettings`, `FOVAngle`, `FarViewPlane`, `bIsRealtime`, `bShowFPS`, `bShowOnScreenStats`, `EnabledStats`, `bShowFullToolbar`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ViewportType` | [`ELevelViewportType`](../enums/ue_ue.ELevelViewportType.md) |
| `PerspViewModeIndex` | [`EViewModeIndex`](../enums/ue_ue.EViewModeIndex.md) |
| `OrthoViewModeIndex` | [`EViewModeIndex`](../enums/ue_ue.EViewModeIndex.md) |
| `EditorShowFlagsString` | `string` |
| `GameShowFlagsString` | `string` |
| `BufferVisualizationMode` | `string` |
| `RayTracingDebugVisualizationMode` | `string` |
| `ExposureSettings` | [`ExposureSettings`](ue_ue.ExposureSettings.md) |
| `FOVAngle` | `number` |
| `FarViewPlane` | `number` |
| `bIsRealtime` | `boolean` |
| `bShowFPS` | `boolean` |
| `bShowOnScreenStats` | `boolean` |
| `EnabledStats` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bShowFullToolbar` | `boolean` |

#### Defined in

[ue/ue.d.ts:45005](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45005)

## Properties

### BufferVisualizationMode

• **BufferVisualizationMode**: `string`

#### Defined in

[ue/ue.d.ts:45011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45011)

___

### EditorShowFlagsString

• **EditorShowFlagsString**: `string`

#### Defined in

[ue/ue.d.ts:45009](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45009)

___

### EnabledStats

• **EnabledStats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:45019](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45019)

___

### ExposureSettings

• **ExposureSettings**: [`ExposureSettings`](ue_ue.ExposureSettings.md)

#### Defined in

[ue/ue.d.ts:45013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45013)

___

### FOVAngle

• **FOVAngle**: `number`

#### Defined in

[ue/ue.d.ts:45014](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45014)

___

### FarViewPlane

• **FarViewPlane**: `number`

#### Defined in

[ue/ue.d.ts:45015](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45015)

___

### GameShowFlagsString

• **GameShowFlagsString**: `string`

#### Defined in

[ue/ue.d.ts:45010](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45010)

___

### OrthoViewModeIndex

• **OrthoViewModeIndex**: [`EViewModeIndex`](../enums/ue_ue.EViewModeIndex.md)

#### Defined in

[ue/ue.d.ts:45008](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45008)

___

### PerspViewModeIndex

• **PerspViewModeIndex**: [`EViewModeIndex`](../enums/ue_ue.EViewModeIndex.md)

#### Defined in

[ue/ue.d.ts:45007](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45007)

___

### RayTracingDebugVisualizationMode

• **RayTracingDebugVisualizationMode**: `string`

#### Defined in

[ue/ue.d.ts:45012](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45012)

___

### ViewportType

• **ViewportType**: [`ELevelViewportType`](../enums/ue_ue.ELevelViewportType.md)

#### Defined in

[ue/ue.d.ts:45006](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45006)

___

### \_\_tid\_LevelEditorViewportInstanceSettings\_\_

• `Private` **\_\_tid\_LevelEditorViewportInstanceSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:45026](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45026)

___

### bIsRealtime

• **bIsRealtime**: `boolean`

#### Defined in

[ue/ue.d.ts:45016](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45016)

___

### bShowFPS

• **bShowFPS**: `boolean`

#### Defined in

[ue/ue.d.ts:45017](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45017)

___

### bShowFullToolbar

• **bShowFullToolbar**: `boolean`

#### Defined in

[ue/ue.d.ts:45020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45020)

___

### bShowOnScreenStats

• **bShowOnScreenStats**: `boolean`

#### Defined in

[ue/ue.d.ts:45018](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45018)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:45024](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45024)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:45025](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45025)
