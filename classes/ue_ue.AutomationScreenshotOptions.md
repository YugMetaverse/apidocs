[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AutomationScreenshotOptions

# Class: AutomationScreenshotOptions

[ue/ue](../modules/ue_ue.md).AutomationScreenshotOptions

## Table of contents

### Constructors

- [constructor](ue_ue.AutomationScreenshotOptions.md#constructor)

### Properties

- [Delay](ue_ue.AutomationScreenshotOptions.md#delay)
- [MaximumGlobalError](ue_ue.AutomationScreenshotOptions.md#maximumglobalerror)
- [MaximumLocalError](ue_ue.AutomationScreenshotOptions.md#maximumlocalerror)
- [OverrideTimeTo](ue_ue.AutomationScreenshotOptions.md#overridetimeto)
- [Resolution](ue_ue.AutomationScreenshotOptions.md#resolution)
- [Tolerance](ue_ue.AutomationScreenshotOptions.md#tolerance)
- [ToleranceAmount](ue_ue.AutomationScreenshotOptions.md#toleranceamount)
- [ViewSettings](ue_ue.AutomationScreenshotOptions.md#viewsettings)
- [VisualizeBuffer](ue_ue.AutomationScreenshotOptions.md#visualizebuffer)
- [\_\_tid\_AutomationScreenshotOptions\_\_](ue_ue.AutomationScreenshotOptions.md#__tid_automationscreenshotoptions__)
- [bDisableNoisyRenderingFeatures](ue_ue.AutomationScreenshotOptions.md#bdisablenoisyrenderingfeatures)
- [bDisableTonemapping](ue_ue.AutomationScreenshotOptions.md#bdisabletonemapping)
- [bIgnoreAntiAliasing](ue_ue.AutomationScreenshotOptions.md#bignoreantialiasing)
- [bIgnoreColors](ue_ue.AutomationScreenshotOptions.md#bignorecolors)
- [bOverride\_OverrideTimeTo](ue_ue.AutomationScreenshotOptions.md#boverride_overridetimeto)

### Methods

- [StaticClass](ue_ue.AutomationScreenshotOptions.md#staticclass)
- [StaticStruct](ue_ue.AutomationScreenshotOptions.md#staticstruct)

## Constructors

### constructor

• **new AutomationScreenshotOptions**()

• **new AutomationScreenshotOptions**(`Resolution`, `Delay`, `bOverride_OverrideTimeTo`, `OverrideTimeTo`, `bDisableNoisyRenderingFeatures`, `bDisableTonemapping`, `ViewSettings`, `VisualizeBuffer`, `Tolerance`, `ToleranceAmount`, `MaximumLocalError`, `MaximumGlobalError`, `bIgnoreAntiAliasing`, `bIgnoreColors`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Resolution` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Delay` | `number` |
| `bOverride_OverrideTimeTo` | `boolean` |
| `OverrideTimeTo` | `number` |
| `bDisableNoisyRenderingFeatures` | `boolean` |
| `bDisableTonemapping` | `boolean` |
| `ViewSettings` | [`AutomationViewSettings`](ue_ue.AutomationViewSettings.md) |
| `VisualizeBuffer` | `string` |
| `Tolerance` | [`EComparisonTolerance`](../enums/ue_ue.EComparisonTolerance.md) |
| `ToleranceAmount` | [`ComparisonToleranceAmount`](ue_ue.ComparisonToleranceAmount.md) |
| `MaximumLocalError` | `number` |
| `MaximumGlobalError` | `number` |
| `bIgnoreAntiAliasing` | `boolean` |
| `bIgnoreColors` | `boolean` |

## Properties

### Delay

• **Delay**: `number`

___

### MaximumGlobalError

• **MaximumGlobalError**: `number`

___

### MaximumLocalError

• **MaximumLocalError**: `number`

___

### OverrideTimeTo

• **OverrideTimeTo**: `number`

___

### Resolution

• **Resolution**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### Tolerance

• **Tolerance**: [`EComparisonTolerance`](../enums/ue_ue.EComparisonTolerance.md)

___

### ToleranceAmount

• **ToleranceAmount**: [`ComparisonToleranceAmount`](ue_ue.ComparisonToleranceAmount.md)

___

### ViewSettings

• **ViewSettings**: [`AutomationViewSettings`](ue_ue.AutomationViewSettings.md)

___

### VisualizeBuffer

• **VisualizeBuffer**: `string`

___

### \_\_tid\_AutomationScreenshotOptions\_\_

• `Private` **\_\_tid\_AutomationScreenshotOptions\_\_**: `boolean`

___

### bDisableNoisyRenderingFeatures

• **bDisableNoisyRenderingFeatures**: `boolean`

___

### bDisableTonemapping

• **bDisableTonemapping**: `boolean`

___

### bIgnoreAntiAliasing

• **bIgnoreAntiAliasing**: `boolean`

___

### bIgnoreColors

• **bIgnoreColors**: `boolean`

___

### bOverride\_OverrideTimeTo

• **bOverride\_OverrideTimeTo**: `boolean`

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
