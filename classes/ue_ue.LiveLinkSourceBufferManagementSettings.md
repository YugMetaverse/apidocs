[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LiveLinkSourceBufferManagementSettings

# Class: LiveLinkSourceBufferManagementSettings

[ue/ue](../modules/ue_ue.md).LiveLinkSourceBufferManagementSettings

## Table of contents

### Constructors

- [constructor](ue_ue.LiveLinkSourceBufferManagementSettings.md#constructor)

### Properties

- [EngineTimeOffset](ue_ue.LiveLinkSourceBufferManagementSettings.md#enginetimeoffset)
- [LatestOffset](ue_ue.LiveLinkSourceBufferManagementSettings.md#latestoffset)
- [MaxNumberOfFrameToBuffered](ue_ue.LiveLinkSourceBufferManagementSettings.md#maxnumberofframetobuffered)
- [SourceTimecodeFrameRate](ue_ue.LiveLinkSourceBufferManagementSettings.md#sourcetimecodeframerate)
- [TimecodeFrameOffset](ue_ue.LiveLinkSourceBufferManagementSettings.md#timecodeframeoffset)
- [TimecodeFrameRate](ue_ue.LiveLinkSourceBufferManagementSettings.md#timecodeframerate)
- [ValidEngineTime](ue_ue.LiveLinkSourceBufferManagementSettings.md#validenginetime)
- [ValidTimecodeFrame](ue_ue.LiveLinkSourceBufferManagementSettings.md#validtimecodeframe)
- [\_\_tid\_LiveLinkSourceBufferManagementSettings\_\_](ue_ue.LiveLinkSourceBufferManagementSettings.md#__tid_livelinksourcebuffermanagementsettings__)
- [bGenerateSubFrame](ue_ue.LiveLinkSourceBufferManagementSettings.md#bgeneratesubframe)
- [bKeepAtLeastOneFrame](ue_ue.LiveLinkSourceBufferManagementSettings.md#bkeepatleastoneframe)

### Methods

- [StaticClass](ue_ue.LiveLinkSourceBufferManagementSettings.md#staticclass)
- [StaticStruct](ue_ue.LiveLinkSourceBufferManagementSettings.md#staticstruct)

## Constructors

### constructor

• **new LiveLinkSourceBufferManagementSettings**()

• **new LiveLinkSourceBufferManagementSettings**(`ValidEngineTime`, `EngineTimeOffset`, `TimecodeFrameRate`, `bGenerateSubFrame`, `SourceTimecodeFrameRate`, `ValidTimecodeFrame`, `TimecodeFrameOffset`, `LatestOffset`, `MaxNumberOfFrameToBuffered`, `bKeepAtLeastOneFrame`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ValidEngineTime` | `number` |
| `EngineTimeOffset` | `number` |
| `TimecodeFrameRate` | [`FrameRate`](ue_ue.FrameRate.md) |
| `bGenerateSubFrame` | `boolean` |
| `SourceTimecodeFrameRate` | [`FrameRate`](ue_ue.FrameRate.md) |
| `ValidTimecodeFrame` | `number` |
| `TimecodeFrameOffset` | `number` |
| `LatestOffset` | `number` |
| `MaxNumberOfFrameToBuffered` | `number` |
| `bKeepAtLeastOneFrame` | `boolean` |

## Properties

### EngineTimeOffset

• **EngineTimeOffset**: `number`

___

### LatestOffset

• **LatestOffset**: `number`

___

### MaxNumberOfFrameToBuffered

• **MaxNumberOfFrameToBuffered**: `number`

___

### SourceTimecodeFrameRate

• **SourceTimecodeFrameRate**: [`FrameRate`](ue_ue.FrameRate.md)

___

### TimecodeFrameOffset

• **TimecodeFrameOffset**: `number`

___

### TimecodeFrameRate

• **TimecodeFrameRate**: [`FrameRate`](ue_ue.FrameRate.md)

___

### ValidEngineTime

• **ValidEngineTime**: `number`

___

### ValidTimecodeFrame

• **ValidTimecodeFrame**: `number`

___

### \_\_tid\_LiveLinkSourceBufferManagementSettings\_\_

• `Private` **\_\_tid\_LiveLinkSourceBufferManagementSettings\_\_**: `boolean`

___

### bGenerateSubFrame

• **bGenerateSubFrame**: `boolean`

___

### bKeepAtLeastOneFrame

• **bKeepAtLeastOneFrame**: `boolean`

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
