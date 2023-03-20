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

#### Defined in

[ue/ue.d.ts:22955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22955)

## Properties

### \_\_tid\_AutomationPerformaceHelper\_\_

• **\_\_tid\_AutomationPerformaceHelper\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22978](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22978)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

#### Defined in

[ue/ue.d.ts:22956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22956)

___

### BeginRecordingBaseline

▸ **BeginRecordingBaseline**(`RecordName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RecordName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22957](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22957)

___

### BeginStatsFile

▸ **BeginStatsFile**(`RecordName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RecordName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22958)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### EndRecording

▸ **EndRecording**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22959](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22959)

___

### EndRecordingBaseline

▸ **EndRecordingBaseline**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22960](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22960)

___

### EndStatsFile

▸ **EndStatsFile**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22961)

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

### IsCurrentRecordWithinGPUBudget

▸ **IsCurrentRecordWithinGPUBudget**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:22963](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22963)

___

### IsCurrentRecordWithinGameThreadBudget

▸ **IsCurrentRecordWithinGameThreadBudget**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:22962](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22962)

___

### IsCurrentRecordWithinRenderThreadBudget

▸ **IsCurrentRecordWithinRenderThreadBudget**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:22964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22964)

___

### IsRecording

▸ **IsRecording**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:22965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22965)

___

### OnAllTestsComplete

▸ **OnAllTestsComplete**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22966)

___

### OnBeginTests

▸ **OnBeginTests**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22967)

___

### Sample

▸ **Sample**(`DeltaSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaSeconds` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22968)

___

### StartCPUProfiling

▸ **StartCPUProfiling**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22969)

___

### StopCPUProfiling

▸ **StopCPUProfiling**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22970)

___

### Tick

▸ **Tick**(`DeltaSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaSeconds` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22971)

___

### TriggerGPUTraceIfRecordFallsBelowBudget

▸ **TriggerGPUTraceIfRecordFallsBelowBudget**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22972)

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

#### Defined in

[ue/ue.d.ts:22973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22973)

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

#### Defined in

[ue/ue.d.ts:22975](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22975)

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

#### Defined in

[ue/ue.d.ts:22976](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22976)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:22974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22974)
