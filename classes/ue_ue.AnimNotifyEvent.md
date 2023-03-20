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

## Properties

### CachedLinkMethod

• **CachedLinkMethod**: [`EAnimLinkMethod`](../enums/ue_ue.EAnimLinkMethod.md)

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[CachedLinkMethod](ue_ue.AnimLinkableElement.md#cachedlinkmethod)

___

### DisplayTime

• **DisplayTime**: `number`

___

### Duration

• **Duration**: `number`

___

### EndLink

• **EndLink**: [`AnimLinkableElement`](ue_ue.AnimLinkableElement.md)

___

### EndTriggerTimeOffset

• **EndTriggerTimeOffset**: `number`

___

### LinkMethod

• **LinkMethod**: [`EAnimLinkMethod`](../enums/ue_ue.EAnimLinkMethod.md)

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[LinkMethod](ue_ue.AnimLinkableElement.md#linkmethod)

___

### LinkValue

• **LinkValue**: `number`

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[LinkValue](ue_ue.AnimLinkableElement.md#linkvalue)

___

### LinkedMontage

• **LinkedMontage**: [`AnimMontage`](ue_ue.AnimMontage.md)

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[LinkedMontage](ue_ue.AnimLinkableElement.md#linkedmontage)

___

### LinkedSequence

• **LinkedSequence**: [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[LinkedSequence](ue_ue.AnimLinkableElement.md#linkedsequence)

___

### MontageTickType

• **MontageTickType**: [`EMontageNotifyTickType`](../enums/ue_ue.EMontageNotifyTickType.md)

___

### Notify

• **Notify**: [`AnimNotify`](ue_ue.AnimNotify.md)

___

### NotifyColor

• **NotifyColor**: [`Color`](ue_ue_s.Color.md)

___

### NotifyFilterLOD

• **NotifyFilterLOD**: `number`

___

### NotifyFilterType

• **NotifyFilterType**: [`ENotifyFilterType`](../enums/ue_ue.ENotifyFilterType.md)

___

### NotifyName

• **NotifyName**: `string`

___

### NotifyStateClass

• **NotifyStateClass**: [`AnimNotifyState`](ue_ue.AnimNotifyState.md)

___

### NotifyTriggerChance

• **NotifyTriggerChance**: `number`

___

### SegmentBeginTime

• **SegmentBeginTime**: `number`

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[SegmentBeginTime](ue_ue.AnimLinkableElement.md#segmentbegintime)

___

### SegmentIndex

• **SegmentIndex**: `number`

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[SegmentIndex](ue_ue.AnimLinkableElement.md#segmentindex)

___

### SegmentLength

• **SegmentLength**: `number`

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[SegmentLength](ue_ue.AnimLinkableElement.md#segmentlength)

___

### SlotIndex

• **SlotIndex**: `number`

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[SlotIndex](ue_ue.AnimLinkableElement.md#slotindex)

___

### TrackIndex

• **TrackIndex**: `number`

___

### TriggerTimeOffset

• **TriggerTimeOffset**: `number`

___

### TriggerWeightThreshold

• **TriggerWeightThreshold**: `number`

___

### \_\_tid\_AnimNotifyEvent\_\_

• `Private` **\_\_tid\_AnimNotifyEvent\_\_**: `boolean`

___

### bConvertedFromBranchingPoint

• **bConvertedFromBranchingPoint**: `boolean`

___

### bTriggerOnDedicatedServer

• **bTriggerOnDedicatedServer**: `boolean`

___

### bTriggerOnFollower

• **bTriggerOnFollower**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[StaticClass](ue_ue.AnimLinkableElement.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[StaticStruct](ue_ue.AnimLinkableElement.md#staticstruct)
