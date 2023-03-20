[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / StreamingSettings

# Class: StreamingSettings

[ue/ue](../modules/ue_ue.md).StreamingSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`StreamingSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.StreamingSettings.md#constructor)

### Properties

- [AsyncLoadingThreadEnabled](ue_ue.StreamingSettings.md#asyncloadingthreadenabled)
- [AsyncLoadingTimeLimit](ue_ue.StreamingSettings.md#asyncloadingtimelimit)
- [AsyncLoadingUseFullTimeLimit](ue_ue.StreamingSettings.md#asyncloadingusefulltimelimit)
- [EventDrivenLoaderEnabled](ue_ue.StreamingSettings.md#eventdrivenloaderenabled)
- [FlushStreamingOnExit](ue_ue.StreamingSettings.md#flushstreamingonexit)
- [LevelStreamingActorsUpdateTimeLimit](ue_ue.StreamingSettings.md#levelstreamingactorsupdatetimelimit)
- [LevelStreamingComponentsRegistrationGranularity](ue_ue.StreamingSettings.md#levelstreamingcomponentsregistrationgranularity)
- [LevelStreamingComponentsUnregistrationGranularity](ue_ue.StreamingSettings.md#levelstreamingcomponentsunregistrationgranularity)
- [LevelStreamingUnregisterComponentsTimeLimit](ue_ue.StreamingSettings.md#levelstreamingunregistercomponentstimelimit)
- [MinBulkDataSizeForAsyncLoading](ue_ue.StreamingSettings.md#minbulkdatasizeforasyncloading)
- [PriorityAsyncLoadingExtraTime](ue_ue.StreamingSettings.md#priorityasyncloadingextratime)
- [PriorityLevelStreamingActorsUpdateExtraTime](ue_ue.StreamingSettings.md#prioritylevelstreamingactorsupdateextratime)
- [TimeLimitExceededMinTime](ue_ue.StreamingSettings.md#timelimitexceededmintime)
- [TimeLimitExceededMultiplier](ue_ue.StreamingSettings.md#timelimitexceededmultiplier)
- [UseBackgroundLevelStreaming](ue_ue.StreamingSettings.md#usebackgroundlevelstreaming)
- [WarnIfTimeLimitExceeded](ue_ue.StreamingSettings.md#warniftimelimitexceeded)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.StreamingSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.StreamingSettings.md#__tid_object__)
- [\_\_tid\_StreamingSettings\_\_](ue_ue.StreamingSettings.md#__tid_streamingsettings__)

### Methods

- [CreateDefaultSubobject](ue_ue.StreamingSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.StreamingSettings.md#executeubergraph)
- [GetClass](ue_ue.StreamingSettings.md#getclass)
- [GetName](ue_ue.StreamingSettings.md#getname)
- [GetOuter](ue_ue.StreamingSettings.md#getouter)
- [GetWorld](ue_ue.StreamingSettings.md#getworld)
- [Find](ue_ue.StreamingSettings.md#find)
- [Load](ue_ue.StreamingSettings.md#load)
- [StaticClass](ue_ue.StreamingSettings.md#staticclass)

## Constructors

### constructor

• **new StreamingSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### AsyncLoadingThreadEnabled

• **AsyncLoadingThreadEnabled**: `boolean`

___

### AsyncLoadingTimeLimit

• **AsyncLoadingTimeLimit**: `number`

___

### AsyncLoadingUseFullTimeLimit

• **AsyncLoadingUseFullTimeLimit**: `boolean`

___

### EventDrivenLoaderEnabled

• **EventDrivenLoaderEnabled**: `boolean`

___

### FlushStreamingOnExit

• **FlushStreamingOnExit**: `boolean`

___

### LevelStreamingActorsUpdateTimeLimit

• **LevelStreamingActorsUpdateTimeLimit**: `number`

___

### LevelStreamingComponentsRegistrationGranularity

• **LevelStreamingComponentsRegistrationGranularity**: `number`

___

### LevelStreamingComponentsUnregistrationGranularity

• **LevelStreamingComponentsUnregistrationGranularity**: `number`

___

### LevelStreamingUnregisterComponentsTimeLimit

• **LevelStreamingUnregisterComponentsTimeLimit**: `number`

___

### MinBulkDataSizeForAsyncLoading

• **MinBulkDataSizeForAsyncLoading**: `number`

___

### PriorityAsyncLoadingExtraTime

• **PriorityAsyncLoadingExtraTime**: `number`

___

### PriorityLevelStreamingActorsUpdateExtraTime

• **PriorityLevelStreamingActorsUpdateExtraTime**: `number`

___

### TimeLimitExceededMinTime

• **TimeLimitExceededMinTime**: `number`

___

### TimeLimitExceededMultiplier

• **TimeLimitExceededMultiplier**: `number`

___

### UseBackgroundLevelStreaming

• **UseBackgroundLevelStreaming**: `boolean`

___

### WarnIfTimeLimitExceeded

• **WarnIfTimeLimitExceeded**: `boolean`

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### \_\_tid\_StreamingSettings\_\_

• **\_\_tid\_StreamingSettings\_\_**: `boolean`

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`StreamingSettings`](ue_ue.StreamingSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`StreamingSettings`](ue_ue.StreamingSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`StreamingSettings`](ue_ue.StreamingSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`StreamingSettings`](ue_ue.StreamingSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
