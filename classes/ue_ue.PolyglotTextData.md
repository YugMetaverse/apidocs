[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PolyglotTextData

# Class: PolyglotTextData

[ue/ue](../modules/ue_ue.md).PolyglotTextData

## Table of contents

### Constructors

- [constructor](ue_ue.PolyglotTextData.md#constructor)

### Properties

- [CachedText](ue_ue.PolyglotTextData.md#cachedtext)
- [Category](ue_ue.PolyglotTextData.md#category)
- [Key](ue_ue.PolyglotTextData.md#key)
- [LocalizedStrings](ue_ue.PolyglotTextData.md#localizedstrings)
- [Namespace](ue_ue.PolyglotTextData.md#namespace)
- [NativeCulture](ue_ue.PolyglotTextData.md#nativeculture)
- [NativeString](ue_ue.PolyglotTextData.md#nativestring)
- [\_\_tid\_PolyglotTextData\_\_](ue_ue.PolyglotTextData.md#__tid_polyglottextdata__)
- [bIsMinimalPatch](ue_ue.PolyglotTextData.md#bisminimalpatch)

### Methods

- [StaticClass](ue_ue.PolyglotTextData.md#staticclass)
- [StaticStruct](ue_ue.PolyglotTextData.md#staticstruct)

## Constructors

### constructor

• **new PolyglotTextData**()

• **new PolyglotTextData**(`Category`, `NativeCulture`, `Namespace`, `Key`, `NativeString`, `LocalizedStrings`, `bIsMinimalPatch`, `CachedText`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Category` | [`ELocalizedTextSourceCategory`](../enums/ue_ue.ELocalizedTextSourceCategory.md) |
| `NativeCulture` | `string` |
| `Namespace` | `string` |
| `Key` | `string` |
| `NativeString` | `string` |
| `LocalizedStrings` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\> |
| `bIsMinimalPatch` | `boolean` |
| `CachedText` | `string` |

## Properties

### CachedText

• **CachedText**: `string`

___

### Category

• **Category**: [`ELocalizedTextSourceCategory`](../enums/ue_ue.ELocalizedTextSourceCategory.md)

___

### Key

• **Key**: `string`

___

### LocalizedStrings

• **LocalizedStrings**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

___

### Namespace

• **Namespace**: `string`

___

### NativeCulture

• **NativeCulture**: `string`

___

### NativeString

• **NativeString**: `string`

___

### \_\_tid\_PolyglotTextData\_\_

• `Private` **\_\_tid\_PolyglotTextData\_\_**: `boolean`

___

### bIsMinimalPatch

• **bIsMinimalPatch**: `boolean`

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
