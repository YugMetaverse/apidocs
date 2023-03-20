[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AutomationBlueprintFunctionLibrary

# Class: AutomationBlueprintFunctionLibrary

[ue/ue](../modules/ue_ue.md).AutomationBlueprintFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`AutomationBlueprintFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.AutomationBlueprintFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_AutomationBlueprintFunctionLibrary\_\_](ue_ue.AutomationBlueprintFunctionLibrary.md#__tid_automationblueprintfunctionlibrary__)
- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.AutomationBlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.AutomationBlueprintFunctionLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AutomationBlueprintFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AutomationBlueprintFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.AutomationBlueprintFunctionLibrary.md#getclass)
- [GetName](ue_ue.AutomationBlueprintFunctionLibrary.md#getname)
- [GetOuter](ue_ue.AutomationBlueprintFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.AutomationBlueprintFunctionLibrary.md#getworld)
- [AddExpectedLogError](ue_ue.AutomationBlueprintFunctionLibrary.md#addexpectedlogerror)
- [AreAutomatedTestsRunning](ue_ue.AutomationBlueprintFunctionLibrary.md#areautomatedtestsrunning)
- [AutomationWaitForLoading](ue_ue.AutomationBlueprintFunctionLibrary.md#automationwaitforloading)
- [DisableStatGroup](ue_ue.AutomationBlueprintFunctionLibrary.md#disablestatgroup)
- [EnableStatGroup](ue_ue.AutomationBlueprintFunctionLibrary.md#enablestatgroup)
- [Find](ue_ue.AutomationBlueprintFunctionLibrary.md#find)
- [GetDefaultScreenshotOptionsForGameplay](ue_ue.AutomationBlueprintFunctionLibrary.md#getdefaultscreenshotoptionsforgameplay)
- [GetDefaultScreenshotOptionsForRendering](ue_ue.AutomationBlueprintFunctionLibrary.md#getdefaultscreenshotoptionsforrendering)
- [GetStatCallCount](ue_ue.AutomationBlueprintFunctionLibrary.md#getstatcallcount)
- [GetStatExcAverage](ue_ue.AutomationBlueprintFunctionLibrary.md#getstatexcaverage)
- [GetStatExcMax](ue_ue.AutomationBlueprintFunctionLibrary.md#getstatexcmax)
- [GetStatIncAverage](ue_ue.AutomationBlueprintFunctionLibrary.md#getstatincaverage)
- [GetStatIncMax](ue_ue.AutomationBlueprintFunctionLibrary.md#getstatincmax)
- [Load](ue_ue.AutomationBlueprintFunctionLibrary.md#load)
- [SetScalabilityQualityLevelRelativeToMax](ue_ue.AutomationBlueprintFunctionLibrary.md#setscalabilityqualitylevelrelativetomax)
- [SetScalabilityQualityToEpic](ue_ue.AutomationBlueprintFunctionLibrary.md#setscalabilityqualitytoepic)
- [SetScalabilityQualityToLow](ue_ue.AutomationBlueprintFunctionLibrary.md#setscalabilityqualitytolow)
- [StaticClass](ue_ue.AutomationBlueprintFunctionLibrary.md#staticclass)
- [TakeAutomationScreenshot](ue_ue.AutomationBlueprintFunctionLibrary.md#takeautomationscreenshot)
- [TakeAutomationScreenshotAtCamera](ue_ue.AutomationBlueprintFunctionLibrary.md#takeautomationscreenshotatcamera)
- [TakeAutomationScreenshotOfUI](ue_ue.AutomationBlueprintFunctionLibrary.md#takeautomationscreenshotofui)
- [TakeHighResScreenshot](ue_ue.AutomationBlueprintFunctionLibrary.md#takehighresscreenshot)

## Constructors

### constructor

• **new AutomationBlueprintFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:22889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22889)

## Properties

### \_\_tid\_AutomationBlueprintFunctionLibrary\_\_

• **\_\_tid\_AutomationBlueprintFunctionLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22913](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22913)

___

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### AddExpectedLogError

▸ `Static` **AddExpectedLogError**(`ExpectedPatternString`, `Occurrences?`, `ExactMatch?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ExpectedPatternString` | `string` |
| `Occurrences?` | `number` |
| `ExactMatch?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22890](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22890)

___

### AreAutomatedTestsRunning

▸ `Static` **AreAutomatedTestsRunning**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:22891](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22891)

___

### AutomationWaitForLoading

▸ `Static` **AutomationWaitForLoading**(`WorldContextObject`, `LatentInfo`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `LatentInfo` | [`LatentActionInfo`](ue_ue.LatentActionInfo.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22892](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22892)

___

### DisableStatGroup

▸ `Static` **DisableStatGroup**(`WorldContextObject`, `GroupName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `GroupName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22893](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22893)

___

### EnableStatGroup

▸ `Static` **EnableStatGroup**(`WorldContextObject`, `GroupName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `GroupName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22894](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22894)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AutomationBlueprintFunctionLibrary`](ue_ue.AutomationBlueprintFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AutomationBlueprintFunctionLibrary`](ue_ue.AutomationBlueprintFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:22910](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22910)

___

### GetDefaultScreenshotOptionsForGameplay

▸ `Static` **GetDefaultScreenshotOptionsForGameplay**(`Tolerance?`, `Delay?`): [`AutomationScreenshotOptions`](ue_ue.AutomationScreenshotOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance?` | [`EComparisonTolerance`](../enums/ue_ue.EComparisonTolerance.md) |
| `Delay?` | `number` |

#### Returns

[`AutomationScreenshotOptions`](ue_ue.AutomationScreenshotOptions.md)

#### Defined in

[ue/ue.d.ts:22895](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22895)

___

### GetDefaultScreenshotOptionsForRendering

▸ `Static` **GetDefaultScreenshotOptionsForRendering**(`Tolerance?`, `Delay?`): [`AutomationScreenshotOptions`](ue_ue.AutomationScreenshotOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance?` | [`EComparisonTolerance`](../enums/ue_ue.EComparisonTolerance.md) |
| `Delay?` | `number` |

#### Returns

[`AutomationScreenshotOptions`](ue_ue.AutomationScreenshotOptions.md)

#### Defined in

[ue/ue.d.ts:22896](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22896)

___

### GetStatCallCount

▸ `Static` **GetStatCallCount**(`StatName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StatName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:22897](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22897)

___

### GetStatExcAverage

▸ `Static` **GetStatExcAverage**(`StatName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StatName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:22898](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22898)

___

### GetStatExcMax

▸ `Static` **GetStatExcMax**(`StatName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StatName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:22899](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22899)

___

### GetStatIncAverage

▸ `Static` **GetStatIncAverage**(`StatName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StatName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:22900](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22900)

___

### GetStatIncMax

▸ `Static` **GetStatIncMax**(`StatName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StatName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:22901](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22901)

___

### Load

▸ `Static` **Load**(`InName`): [`AutomationBlueprintFunctionLibrary`](ue_ue.AutomationBlueprintFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AutomationBlueprintFunctionLibrary`](ue_ue.AutomationBlueprintFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:22911](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22911)

___

### SetScalabilityQualityLevelRelativeToMax

▸ `Static` **SetScalabilityQualityLevelRelativeToMax**(`WorldContextObject`, `Value?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Value?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22902](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22902)

___

### SetScalabilityQualityToEpic

▸ `Static` **SetScalabilityQualityToEpic**(`WorldContextObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22903](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22903)

___

### SetScalabilityQualityToLow

▸ `Static` **SetScalabilityQualityToLow**(`WorldContextObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22904](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22904)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:22909](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22909)

___

### TakeAutomationScreenshot

▸ `Static` **TakeAutomationScreenshot**(`WorldContextObject`, `LatentInfo`, `Name`, `Notes`, `Options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `LatentInfo` | [`LatentActionInfo`](ue_ue.LatentActionInfo.md) |
| `Name` | `string` |
| `Notes` | `string` |
| `Options` | [`AutomationScreenshotOptions`](ue_ue.AutomationScreenshotOptions.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22905](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22905)

___

### TakeAutomationScreenshotAtCamera

▸ `Static` **TakeAutomationScreenshotAtCamera**(`WorldContextObject`, `LatentInfo`, `Camera`, `NameOverride`, `Notes`, `Options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `LatentInfo` | [`LatentActionInfo`](ue_ue.LatentActionInfo.md) |
| `Camera` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CameraActor`](ue_ue.CameraActor.md)\> |
| `NameOverride` | `string` |
| `Notes` | `string` |
| `Options` | [`AutomationScreenshotOptions`](ue_ue.AutomationScreenshotOptions.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22906](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22906)

___

### TakeAutomationScreenshotOfUI

▸ `Static` **TakeAutomationScreenshotOfUI**(`WorldContextObject`, `LatentInfo`, `Name`, `Options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `LatentInfo` | [`LatentActionInfo`](ue_ue.LatentActionInfo.md) |
| `Name` | `string` |
| `Options` | [`AutomationScreenshotOptions`](ue_ue.AutomationScreenshotOptions.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22907](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22907)

___

### TakeHighResScreenshot

▸ `Static` **TakeHighResScreenshot**(`ResX`, `ResY`, `Filename`, `Camera?`, `bMaskEnabled?`, `bCaptureHDR?`, `ComparisonTolerance?`, `ComparisonNotes?`): [`AutomationEditorTask`](ue_ue.AutomationEditorTask.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ResX` | `number` |
| `ResY` | `number` |
| `Filename` | `string` |
| `Camera?` | [`CameraActor`](ue_ue.CameraActor.md) |
| `bMaskEnabled?` | `boolean` |
| `bCaptureHDR?` | `boolean` |
| `ComparisonTolerance?` | [`EComparisonTolerance`](../enums/ue_ue.EComparisonTolerance.md) |
| `ComparisonNotes?` | `string` |

#### Returns

[`AutomationEditorTask`](ue_ue.AutomationEditorTask.md)

#### Defined in

[ue/ue.d.ts:22908](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22908)
