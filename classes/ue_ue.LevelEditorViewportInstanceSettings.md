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

## Properties

### BufferVisualizationMode

• **BufferVisualizationMode**: `string`

___

### EditorShowFlagsString

• **EditorShowFlagsString**: `string`

___

### EnabledStats

• **EnabledStats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ExposureSettings

• **ExposureSettings**: [`ExposureSettings`](ue_ue.ExposureSettings.md)

___

### FOVAngle

• **FOVAngle**: `number`

___

### FarViewPlane

• **FarViewPlane**: `number`

___

### GameShowFlagsString

• **GameShowFlagsString**: `string`

___

### OrthoViewModeIndex

• **OrthoViewModeIndex**: [`EViewModeIndex`](../enums/ue_ue.EViewModeIndex.md)

___

### PerspViewModeIndex

• **PerspViewModeIndex**: [`EViewModeIndex`](../enums/ue_ue.EViewModeIndex.md)

___

### RayTracingDebugVisualizationMode

• **RayTracingDebugVisualizationMode**: `string`

___

### ViewportType

• **ViewportType**: [`ELevelViewportType`](../enums/ue_ue.ELevelViewportType.md)

___

### \_\_tid\_LevelEditorViewportInstanceSettings\_\_

• `Private` **\_\_tid\_LevelEditorViewportInstanceSettings\_\_**: `boolean`

___

### bIsRealtime

• **bIsRealtime**: `boolean`

___

### bShowFPS

• **bShowFPS**: `boolean`

___

### bShowFullToolbar

• **bShowFullToolbar**: `boolean`

___

### bShowOnScreenStats

• **bShowOnScreenStats**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
