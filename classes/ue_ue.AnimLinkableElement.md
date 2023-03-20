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

#### Defined in

[ue/ue.d.ts:2987](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2987)

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

#### Defined in

[ue/ue.d.ts:2988](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2988)

## Properties

### CachedLinkMethod

• **CachedLinkMethod**: [`EAnimLinkMethod`](../enums/ue_ue.EAnimLinkMethod.md)

#### Defined in

[ue/ue.d.ts:2993](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2993)

___

### LinkMethod

• **LinkMethod**: [`EAnimLinkMethod`](../enums/ue_ue.EAnimLinkMethod.md)

#### Defined in

[ue/ue.d.ts:2992](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2992)

___

### LinkValue

• **LinkValue**: `number`

#### Defined in

[ue/ue.d.ts:2996](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2996)

___

### LinkedMontage

• **LinkedMontage**: [`AnimMontage`](ue_ue.AnimMontage.md)

#### Defined in

[ue/ue.d.ts:2989](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2989)

___

### LinkedSequence

• **LinkedSequence**: [`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)

#### Defined in

[ue/ue.d.ts:2997](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2997)

___

### SegmentBeginTime

• **SegmentBeginTime**: `number`

#### Defined in

[ue/ue.d.ts:2994](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2994)

___

### SegmentIndex

• **SegmentIndex**: `number`

#### Defined in

[ue/ue.d.ts:2991](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2991)

___

### SegmentLength

• **SegmentLength**: `number`

#### Defined in

[ue/ue.d.ts:2995](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2995)

___

### SlotIndex

• **SlotIndex**: `number`

#### Defined in

[ue/ue.d.ts:2990](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2990)

___

### \_\_tid\_AnimLinkableElement\_\_

• `Private` **\_\_tid\_AnimLinkableElement\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3003](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3003)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:3001](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3001)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:3002](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3002)
