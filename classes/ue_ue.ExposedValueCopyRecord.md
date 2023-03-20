[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ExposedValueCopyRecord

# Class: ExposedValueCopyRecord

[ue/ue](../modules/ue_ue.md).ExposedValueCopyRecord

## Table of contents

### Constructors

- [constructor](ue_ue.ExposedValueCopyRecord.md#constructor)

### Properties

- [CachedSourceProperty](ue_ue.ExposedValueCopyRecord.md#cachedsourceproperty)
- [CachedSourceStructSubProperty](ue_ue.ExposedValueCopyRecord.md#cachedsourcestructsubproperty)
- [CopyType](ue_ue.ExposedValueCopyRecord.md#copytype)
- [DestArrayIndex](ue_ue.ExposedValueCopyRecord.md#destarrayindex)
- [DestProperty](ue_ue.ExposedValueCopyRecord.md#destproperty)
- [PostCopyOperation](ue_ue.ExposedValueCopyRecord.md#postcopyoperation)
- [Size](ue_ue.ExposedValueCopyRecord.md#size)
- [SourceArrayIndex](ue_ue.ExposedValueCopyRecord.md#sourcearrayindex)
- [SourceProperty](ue_ue.ExposedValueCopyRecord.md#sourceproperty)
- [SourcePropertyName](ue_ue.ExposedValueCopyRecord.md#sourcepropertyname)
- [SourceSubPropertyName](ue_ue.ExposedValueCopyRecord.md#sourcesubpropertyname)
- [\_\_tid\_ExposedValueCopyRecord\_\_](ue_ue.ExposedValueCopyRecord.md#__tid_exposedvaluecopyrecord__)
- [bInstanceIsTarget](ue_ue.ExposedValueCopyRecord.md#binstanceistarget)

### Methods

- [StaticClass](ue_ue.ExposedValueCopyRecord.md#staticclass)
- [StaticStruct](ue_ue.ExposedValueCopyRecord.md#staticstruct)

## Constructors

### constructor

• **new ExposedValueCopyRecord**()

• **new ExposedValueCopyRecord**(`SourceProperty`, `SourcePropertyName`, `SourceSubPropertyName`, `SourceArrayIndex`, `bInstanceIsTarget`, `PostCopyOperation`, `CopyType`, `DestProperty`, `DestArrayIndex`, `Size`, `CachedSourceProperty`, `CachedSourceStructSubProperty`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceProperty` | [`Property`](ue_ue.Property.md) |
| `SourcePropertyName` | `string` |
| `SourceSubPropertyName` | `string` |
| `SourceArrayIndex` | `number` |
| `bInstanceIsTarget` | `boolean` |
| `PostCopyOperation` | [`EPostCopyOperation`](../enums/ue_ue.EPostCopyOperation.md) |
| `CopyType` | [`ECopyType`](../enums/ue_ue.ECopyType.md) |
| `DestProperty` | [`Property`](ue_ue.Property.md) |
| `DestArrayIndex` | `number` |
| `Size` | `number` |
| `CachedSourceProperty` | [`Property`](ue_ue.Property.md) |
| `CachedSourceStructSubProperty` | [`Property`](ue_ue.Property.md) |

## Properties

### CachedSourceProperty

• **CachedSourceProperty**: [`Property`](ue_ue.Property.md)

___

### CachedSourceStructSubProperty

• **CachedSourceStructSubProperty**: [`Property`](ue_ue.Property.md)

___

### CopyType

• **CopyType**: [`ECopyType`](../enums/ue_ue.ECopyType.md)

___

### DestArrayIndex

• **DestArrayIndex**: `number`

___

### DestProperty

• **DestProperty**: [`Property`](ue_ue.Property.md)

___

### PostCopyOperation

• **PostCopyOperation**: [`EPostCopyOperation`](../enums/ue_ue.EPostCopyOperation.md)

___

### Size

• **Size**: `number`

___

### SourceArrayIndex

• **SourceArrayIndex**: `number`

___

### SourceProperty

• **SourceProperty**: [`Property`](ue_ue.Property.md)

___

### SourcePropertyName

• **SourcePropertyName**: `string`

___

### SourceSubPropertyName

• **SourceSubPropertyName**: `string`

___

### \_\_tid\_ExposedValueCopyRecord\_\_

• `Private` **\_\_tid\_ExposedValueCopyRecord\_\_**: `boolean`

___

### bInstanceIsTarget

• **bInstanceIsTarget**: `boolean`

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
