[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNotifyEvent

# Class: AnimNotifyEvent

[ue/ue](../modules/ue_ue.md).AnimNotifyEvent

## Hierarchy

- [`AnimLinkableElement`](ue_ue.AnimLinkableElement.md)

  ↳ **`AnimNotifyEvent`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNotifyEvent.md#constructor)

### Properties

- [CachedLinkMethod](ue_ue.AnimNotifyEvent.md#cachedlinkmethod)
- [DisplayTime](ue_ue.AnimNotifyEvent.md#displaytime)
- [Duration](ue_ue.AnimNotifyEvent.md#duration)
- [EndLink](ue_ue.AnimNotifyEvent.md#endlink)
- [EndTriggerTimeOffset](ue_ue.AnimNotifyEvent.md#endtriggertimeoffset)
- [LinkMethod](ue_ue.AnimNotifyEvent.md#linkmethod)
- [LinkValue](ue_ue.AnimNotifyEvent.md#linkvalue)
- [LinkedMontage](ue_ue.AnimNotifyEvent.md#linkedmontage)
- [LinkedSequence](ue_ue.AnimNotifyEvent.md#linkedsequence)
- [MontageTickType](ue_ue.AnimNotifyEvent.md#montageticktype)
- [Notify](ue_ue.AnimNotifyEvent.md#notify)
- [NotifyColor](ue_ue.AnimNotifyEvent.md#notifycolor)
- [NotifyFilterLOD](ue_ue.AnimNotifyEvent.md#notifyfilterlod)
- [NotifyFilterType](ue_ue.AnimNotifyEvent.md#notifyfiltertype)
- [NotifyName](ue_ue.AnimNotifyEvent.md#notifyname)
- [NotifyStateClass](ue_ue.AnimNotifyEvent.md#notifystateclass)
- [NotifyTriggerChance](ue_ue.AnimNotifyEvent.md#notifytriggerchance)
- [SegmentBeginTime](ue_ue.AnimNotifyEvent.md#segmentbegintime)
- [SegmentIndex](ue_ue.AnimNotifyEvent.md#segmentindex)
- [SegmentLength](ue_ue.AnimNotifyEvent.md#segmentlength)
- [SlotIndex](ue_ue.AnimNotifyEvent.md#slotindex)
- [TrackIndex](ue_ue.AnimNotifyEvent.md#trackindex)
- [TriggerTimeOffset](ue_ue.AnimNotifyEvent.md#triggertimeoffset)
- [TriggerWeightThreshold](ue_ue.AnimNotifyEvent.md#triggerweightthreshold)
- [\_\_tid\_AnimNotifyEvent\_\_](ue_ue.AnimNotifyEvent.md#__tid_animnotifyevent__)
- [bConvertedFromBranchingPoint](ue_ue.AnimNotifyEvent.md#bconvertedfrombranchingpoint)
- [bTriggerOnDedicatedServer](ue_ue.AnimNotifyEvent.md#btriggerondedicatedserver)
- [bTriggerOnFollower](ue_ue.AnimNotifyEvent.md#btriggeronfollower)

### Methods

- [StaticClass](ue_ue.AnimNotifyEvent.md#staticclass)
- [StaticStruct](ue_ue.AnimNotifyEvent.md#staticstruct)

## Constructors

### constructor

• **new AnimNotifyEvent**()

#### Overrides

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[constructor](ue_ue.AnimLinkableElement.md#constructor)

#### Defined in

[ue/ue.d.ts:3035](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3035)

• **new AnimNotifyEvent**(`DisplayTime`, `TriggerTimeOffset`, `EndTriggerTimeOffset`, `TriggerWeightThreshold`, `NotifyName`, `Notify`, `NotifyStateClass`, `Duration`, `EndLink`, `bConvertedFromBranchingPoint`, `MontageTickType`, `NotifyTriggerChance`, `NotifyFilterType`, `NotifyFilterLOD`, `bTriggerOnDedicatedServer`, `bTriggerOnFollower`, `NotifyColor`, `TrackIndex`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `DisplayTime` | `number` |
| `TriggerTimeOffset` | `number` |
| `EndTriggerTimeOffset` | `number` |
| `TriggerWeightThreshold` | `number` |
| `NotifyName` | `string` |
| `Notify` | [`AnimNotify`](ue_ue.AnimNotify.md) |
| `NotifyStateClass` | [`AnimNotifyState`](ue_ue.AnimNotifyState.md) |
| `Duration` | `number` |
| `EndLink` | [`AnimLinkableElement`](ue_ue.AnimLinkableElement.md) |
| `bConvertedFromBranchingPoint` | `boolean` |
| `MontageTickType` | [`EMontageNotifyTickType`](../enums/ue_ue.EMontageNotifyTickType.md) |
| `NotifyTriggerChance` | `number` |
| `NotifyFilterType` | [`ENotifyFilterType`](../enums/ue_ue.ENotifyFilterType.md) |
| `NotifyFilterLOD` | `number` |
| `bTriggerOnDedicatedServer` | `boolean` |
| `bTriggerOnFollower` | `boolean` |
| `NotifyColor` | [`Color`](ue_ue_s.Color.md) |
| `TrackIndex` | `number` |

#### Overrides

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[constructor](ue_ue.AnimLinkableElement.md#constructor)

#### Defined in

[ue/ue.d.ts:3036](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3036)

## Properties

### CachedLinkMethod

• **CachedLinkMethod**: [`EAnimLinkMethod`](../enums/ue_ue.EAnimLinkMethod.md)

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[CachedLinkMethod](ue_ue.AnimLinkableElement.md#cachedlinkmethod)

#### Defined in

[ue/ue.d.ts:2993](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2993)

___

### DisplayTime

• **DisplayTime**: `number`

#### Defined in

[ue/ue.d.ts:3037](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3037)

___

### Duration

• **Duration**: `number`

#### Defined in

[ue/ue.d.ts:3044](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3044)

___

### EndLink

• **EndLink**: [`AnimLinkableElement`](ue_ue.AnimLinkableElement.md)

#### Defined in

[ue/ue.d.ts:3045](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3045)

___

### EndTriggerTimeOffset

• **EndTriggerTimeOffset**: `number`

#### Defined in

[ue/ue.d.ts:3039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3039)

___

### LinkMethod

• **LinkMethod**: [`EAnimLinkMethod`](../enums/ue_ue.EAnimLinkMethod.md)

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[LinkMethod](ue_ue.AnimLinkableElement.md#linkmethod)

#### Defined in

[ue/ue.d.ts:2992](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2992)

___

### LinkValue

• **LinkValue**: `number`

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[LinkValue](ue_ue.AnimLinkableElement.md#linkvalue)

#### Defined in

[ue/ue.d.ts:2996](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2996)

___

### LinkedMontage

• **LinkedMontage**: [`AnimMontage`](ue_ue.AnimMontage.md)

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[LinkedMontage](ue_ue.AnimLinkableElement.md#linkedmontage)

#### Defined in

[ue/ue.d.ts:2989](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2989)

___

### LinkedSequence

• **LinkedSequence**: [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[LinkedSequence](ue_ue.AnimLinkableElement.md#linkedsequence)

#### Defined in

[ue/ue.d.ts:2997](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2997)

___

### MontageTickType

• **MontageTickType**: [`EMontageNotifyTickType`](../enums/ue_ue.EMontageNotifyTickType.md)

#### Defined in

[ue/ue.d.ts:3047](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3047)

___

### Notify

• **Notify**: [`AnimNotify`](ue_ue.AnimNotify.md)

#### Defined in

[ue/ue.d.ts:3042](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3042)

___

### NotifyColor

• **NotifyColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:3053](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3053)

___

### NotifyFilterLOD

• **NotifyFilterLOD**: `number`

#### Defined in

[ue/ue.d.ts:3050](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3050)

___

### NotifyFilterType

• **NotifyFilterType**: [`ENotifyFilterType`](../enums/ue_ue.ENotifyFilterType.md)

#### Defined in

[ue/ue.d.ts:3049](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3049)

___

### NotifyName

• **NotifyName**: `string`

#### Defined in

[ue/ue.d.ts:3041](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3041)

___

### NotifyStateClass

• **NotifyStateClass**: [`AnimNotifyState`](ue_ue.AnimNotifyState.md)

#### Defined in

[ue/ue.d.ts:3043](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3043)

___

### NotifyTriggerChance

• **NotifyTriggerChance**: `number`

#### Defined in

[ue/ue.d.ts:3048](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3048)

___

### SegmentBeginTime

• **SegmentBeginTime**: `number`

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[SegmentBeginTime](ue_ue.AnimLinkableElement.md#segmentbegintime)

#### Defined in

[ue/ue.d.ts:2994](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2994)

___

### SegmentIndex

• **SegmentIndex**: `number`

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[SegmentIndex](ue_ue.AnimLinkableElement.md#segmentindex)

#### Defined in

[ue/ue.d.ts:2991](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2991)

___

### SegmentLength

• **SegmentLength**: `number`

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[SegmentLength](ue_ue.AnimLinkableElement.md#segmentlength)

#### Defined in

[ue/ue.d.ts:2995](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2995)

___

### SlotIndex

• **SlotIndex**: `number`

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[SlotIndex](ue_ue.AnimLinkableElement.md#slotindex)

#### Defined in

[ue/ue.d.ts:2990](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2990)

___

### TrackIndex

• **TrackIndex**: `number`

#### Defined in

[ue/ue.d.ts:3054](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3054)

___

### TriggerTimeOffset

• **TriggerTimeOffset**: `number`

#### Defined in

[ue/ue.d.ts:3038](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3038)

___

### TriggerWeightThreshold

• **TriggerWeightThreshold**: `number`

#### Defined in

[ue/ue.d.ts:3040](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3040)

___

### \_\_tid\_AnimNotifyEvent\_\_

• `Private` **\_\_tid\_AnimNotifyEvent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3060](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3060)

___

### bConvertedFromBranchingPoint

• **bConvertedFromBranchingPoint**: `boolean`

#### Defined in

[ue/ue.d.ts:3046](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3046)

___

### bTriggerOnDedicatedServer

• **bTriggerOnDedicatedServer**: `boolean`

#### Defined in

[ue/ue.d.ts:3051](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3051)

___

### bTriggerOnFollower

• **bTriggerOnFollower**: `boolean`

#### Defined in

[ue/ue.d.ts:3052](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3052)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[StaticClass](ue_ue.AnimLinkableElement.md#staticclass)

#### Defined in

[ue/ue.d.ts:3058](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3058)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[StaticStruct](ue_ue.AnimLinkableElement.md#staticstruct)

#### Defined in

[ue/ue.d.ts:3059](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3059)
