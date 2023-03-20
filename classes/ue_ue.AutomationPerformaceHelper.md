[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AutomationPerformaceHelper

# Class: AutomationPerformaceHelper

[ue/ue](../modules/ue_ue.md).AutomationPerformaceHelper

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AutomationPerformaceHelper`**

## Table of contents

### Constructors

- [constructor](ue_ue.AutomationPerformaceHelper.md#constructor)

### Properties

- [\_\_tid\_AutomationPerformaceHelper\_\_](ue_ue.AutomationPerformaceHelper.md#__tid_automationperformacehelper__)
- [\_\_tid\_Object\_\_](ue_ue.AutomationPerformaceHelper.md#__tid_object__)

### Methods

- [BeginRecording](ue_ue.AutomationPerformaceHelper.md#beginrecording)
- [BeginRecordingBaseline](ue_ue.AutomationPerformaceHelper.md#beginrecordingbaseline)
- [BeginStatsFile](ue_ue.AutomationPerformaceHelper.md#beginstatsfile)
- [CreateDefaultSubobject](ue_ue.AutomationPerformaceHelper.md#createdefaultsubobject)
- [EndRecording](ue_ue.AutomationPerformaceHelper.md#endrecording)
- [EndRecordingBaseline](ue_ue.AutomationPerformaceHelper.md#endrecordingbaseline)
- [EndStatsFile](ue_ue.AutomationPerformaceHelper.md#endstatsfile)
- [ExecuteUbergraph](ue_ue.AutomationPerformaceHelper.md#executeubergraph)
- [GetClass](ue_ue.AutomationPerformaceHelper.md#getclass)
- [GetName](ue_ue.AutomationPerformaceHelper.md#getname)
- [GetOuter](ue_ue.AutomationPerformaceHelper.md#getouter)
- [GetWorld](ue_ue.AutomationPerformaceHelper.md#getworld)
- [IsCurrentRecordWithinGPUBudget](ue_ue.AutomationPerformaceHelper.md#iscurrentrecordwithingpubudget)
- [IsCurrentRecordWithinGameThreadBudget](ue_ue.AutomationPerformaceHelper.md#iscurrentrecordwithingamethreadbudget)
- [IsCurrentRecordWithinRenderThreadBudget](ue_ue.AutomationPerformaceHelper.md#iscurrentrecordwithinrenderthreadbudget)
- [IsRecording](ue_ue.AutomationPerformaceHelper.md#isrecording)
- [OnAllTestsComplete](ue_ue.AutomationPerformaceHelper.md#onalltestscomplete)
- [OnBeginTests](ue_ue.AutomationPerformaceHelper.md#onbegintests)
- [Sample](ue_ue.AutomationPerformaceHelper.md#sample)
- [StartCPUProfiling](ue_ue.AutomationPerformaceHelper.md#startcpuprofiling)
- [StopCPUProfiling](ue_ue.AutomationPerformaceHelper.md#stopcpuprofiling)
- [Tick](ue_ue.AutomationPerformaceHelper.md#tick)
- [TriggerGPUTraceIfRecordFallsBelowBudget](ue_ue.AutomationPerformaceHelper.md#triggergputraceifrecordfallsbelowbudget)
- [WriteLogFile](ue_ue.AutomationPerformaceHelper.md#writelogfile)
- [Find](ue_ue.AutomationPerformaceHelper.md#find)
- [Load](ue_ue.AutomationPerformaceHelper.md#load)
- [StaticClass](ue_ue.AutomationPerformaceHelper.md#staticclass)

## Constructors

### constructor

• **new AutomationPerformaceHelper**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_AutomationPerformaceHelper\_\_

• **\_\_tid\_AutomationPerformaceHelper\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

## Methods

### BeginRecording

▸ **BeginRecording**(`RecordName`, `InGPUBudget`, `InRenderThreadBudget`, `InGameThreadBudget`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RecordName` | `string` |
| `InGPUBudget` | `number` |
| `InRenderThreadBudget` | `number` |
| `InGameThreadBudget` | `number` |

#### Returns

`void`

___

### BeginRecordingBaseline

▸ **BeginRecordingBaseline**(`RecordName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RecordName` | `string` |

#### Returns

`void`

___

### BeginStatsFile

▸ **BeginStatsFile**(`RecordName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RecordName` | `string` |

#### Returns

`void`

___

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

### EndRecording

▸ **EndRecording**(): `void`

#### Returns

`void`

___

### EndRecordingBaseline

▸ **EndRecordingBaseline**(): `void`

#### Returns

`void`

___

### EndStatsFile

▸ **EndStatsFile**(): `void`

#### Returns

`void`

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

### IsCurrentRecordWithinGPUBudget

▸ **IsCurrentRecordWithinGPUBudget**(): `boolean`

#### Returns

`boolean`

___

### IsCurrentRecordWithinGameThreadBudget

▸ **IsCurrentRecordWithinGameThreadBudget**(): `boolean`

#### Returns

`boolean`

___

### IsCurrentRecordWithinRenderThreadBudget

▸ **IsCurrentRecordWithinRenderThreadBudget**(): `boolean`

#### Returns

`boolean`

___

### IsRecording

▸ **IsRecording**(): `boolean`

#### Returns

`boolean`

___

### OnAllTestsComplete

▸ **OnAllTestsComplete**(): `void`

#### Returns

`void`

___

### OnBeginTests

▸ **OnBeginTests**(): `void`

#### Returns

`void`

___

### Sample

▸ **Sample**(`DeltaSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaSeconds` | `number` |

#### Returns

`void`

___

### StartCPUProfiling

▸ **StartCPUProfiling**(): `void`

#### Returns

`void`

___

### StopCPUProfiling

▸ **StopCPUProfiling**(): `void`

#### Returns

`void`

___

### Tick

▸ **Tick**(`DeltaSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaSeconds` | `number` |

#### Returns

`void`

___

### TriggerGPUTraceIfRecordFallsBelowBudget

▸ **TriggerGPUTraceIfRecordFallsBelowBudget**(): `void`

#### Returns

`void`

___

### WriteLogFile

▸ **WriteLogFile**(`CaptureDir`, `CaptureExtension`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CaptureDir` | `string` |
| `CaptureExtension` | `string` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AutomationPerformaceHelper`](ue_ue.AutomationPerformaceHelper.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AutomationPerformaceHelper`](ue_ue.AutomationPerformaceHelper.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AutomationPerformaceHelper`](ue_ue.AutomationPerformaceHelper.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AutomationPerformaceHelper`](ue_ue.AutomationPerformaceHelper.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
