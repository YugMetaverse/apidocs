[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimLinkableElement

# Class: AnimLinkableElement

[ue/ue](../modules/ue_ue.md).AnimLinkableElement

## Hierarchy

- **`AnimLinkableElement`**

  ↳ [`CompositeSection`](ue_ue.CompositeSection.md)

  ↳ [`BranchingPoint`](ue_ue.BranchingPoint.md)

  ↳ [`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimLinkableElement.md#constructor)

### Properties

- [CachedLinkMethod](ue_ue.AnimLinkableElement.md#cachedlinkmethod)
- [LinkMethod](ue_ue.AnimLinkableElement.md#linkmethod)
- [LinkValue](ue_ue.AnimLinkableElement.md#linkvalue)
- [LinkedMontage](ue_ue.AnimLinkableElement.md#linkedmontage)
- [LinkedSequence](ue_ue.AnimLinkableElement.md#linkedsequence)
- [SegmentBeginTime](ue_ue.AnimLinkableElement.md#segmentbegintime)
- [SegmentIndex](ue_ue.AnimLinkableElement.md#segmentindex)
- [SegmentLength](ue_ue.AnimLinkableElement.md#segmentlength)
- [SlotIndex](ue_ue.AnimLinkableElement.md#slotindex)
- [\_\_tid\_AnimLinkableElement\_\_](ue_ue.AnimLinkableElement.md#__tid_animlinkableelement__)

### Methods

- [StaticClass](ue_ue.AnimLinkableElement.md#staticclass)
- [StaticStruct](ue_ue.AnimLinkableElement.md#staticstruct)

## Constructors

### constructor

• **new AnimLinkableElement**()

• **new AnimLinkableElement**(`LinkedMontage`, `SlotIndex`, `SegmentIndex`, `LinkMethod`, `CachedLinkMethod`, `SegmentBeginTime`, `SegmentLength`, `LinkValue`, `LinkedSequence`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LinkedMontage` | [`AnimMontage`](ue_ue.AnimMontage.md) |
| `SlotIndex` | `number` |
| `SegmentIndex` | `number` |
| `LinkMethod` | [`EAnimLinkMethod`](../enums/ue_ue.EAnimLinkMethod.md) |
| `CachedLinkMethod` | [`EAnimLinkMethod`](../enums/ue_ue.EAnimLinkMethod.md) |
| `SegmentBeginTime` | `number` |
| `SegmentLength` | `number` |
| `LinkValue` | `number` |
| `LinkedSequence` | [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md) |

## Properties

### CachedLinkMethod

• **CachedLinkMethod**: [`EAnimLinkMethod`](../enums/ue_ue.EAnimLinkMethod.md)

___

### LinkMethod

• **LinkMethod**: [`EAnimLinkMethod`](../enums/ue_ue.EAnimLinkMethod.md)

___

### LinkValue

• **LinkValue**: `number`

___

### LinkedMontage

• **LinkedMontage**: [`AnimMontage`](ue_ue.AnimMontage.md)

___

### LinkedSequence

• **LinkedSequence**: [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

___

### SegmentBeginTime

• **SegmentBeginTime**: `number`

___

### SegmentIndex

• **SegmentIndex**: `number`

___

### SegmentLength

• **SegmentLength**: `number`

___

### SlotIndex

• **SlotIndex**: `number`

___

### \_\_tid\_AnimLinkableElement\_\_

• `Private` **\_\_tid\_AnimLinkableElement\_\_**: `boolean`

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
