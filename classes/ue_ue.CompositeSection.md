[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CompositeSection

# Class: CompositeSection

[ue/ue](../modules/ue_ue.md).CompositeSection

## Hierarchy

- [`AnimLinkableElement`](ue_ue.AnimLinkableElement.md)

  ↳ **`CompositeSection`**

## Table of contents

### Constructors

- [constructor](ue_ue.CompositeSection.md#constructor)

### Properties

- [CachedLinkMethod](ue_ue.CompositeSection.md#cachedlinkmethod)
- [LinkMethod](ue_ue.CompositeSection.md#linkmethod)
- [LinkValue](ue_ue.CompositeSection.md#linkvalue)
- [LinkedMontage](ue_ue.CompositeSection.md#linkedmontage)
- [LinkedSequence](ue_ue.CompositeSection.md#linkedsequence)
- [MetaData](ue_ue.CompositeSection.md#metadata)
- [NextSectionName](ue_ue.CompositeSection.md#nextsectionname)
- [SectionName](ue_ue.CompositeSection.md#sectionname)
- [SegmentBeginTime](ue_ue.CompositeSection.md#segmentbegintime)
- [SegmentIndex](ue_ue.CompositeSection.md#segmentindex)
- [SegmentLength](ue_ue.CompositeSection.md#segmentlength)
- [SlotIndex](ue_ue.CompositeSection.md#slotindex)
- [StartTime](ue_ue.CompositeSection.md#starttime)
- [\_\_tid\_CompositeSection\_\_](ue_ue.CompositeSection.md#__tid_compositesection__)

### Methods

- [StaticClass](ue_ue.CompositeSection.md#staticclass)
- [StaticStruct](ue_ue.CompositeSection.md#staticstruct)

## Constructors

### constructor

• **new CompositeSection**()

#### Overrides

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[constructor](ue_ue.AnimLinkableElement.md#constructor)

• **new CompositeSection**(`SectionName`, `StartTime`, `NextSectionName`, `MetaData`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SectionName` | `string` |
| `StartTime` | `number` |
| `NextSectionName` | `string` |
| `MetaData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\> |

#### Overrides

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[constructor](ue_ue.AnimLinkableElement.md#constructor)

## Properties

### CachedLinkMethod

• **CachedLinkMethod**: [`EAnimLinkMethod`](../enums/ue_ue.EAnimLinkMethod.md)

#### Inherited from

[AnimLinkableElement](ue_ue.AnimLinkableElement.md).[CachedLinkMethod](ue_ue.AnimLinkableElement.md#cachedlinkmethod)

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

### MetaData

• **MetaData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\>

___

### NextSectionName

• **NextSectionName**: `string`

___

### SectionName

• **SectionName**: `string`

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

### StartTime

• **StartTime**: `number`

___

### \_\_tid\_CompositeSection\_\_

• `Private` **\_\_tid\_CompositeSection\_\_**: `boolean`

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
