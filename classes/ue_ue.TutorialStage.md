[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TutorialStage

# Class: TutorialStage

[ue/ue](../modules/ue_ue.md).TutorialStage

## Table of contents

### Constructors

- [constructor](ue_ue.TutorialStage.md#constructor)

### Properties

- [BackButtonText](ue_ue.TutorialStage.md#backbuttontext)
- [Content](ue_ue.TutorialStage.md#content)
- [Name](ue_ue.TutorialStage.md#name)
- [NextButtonText](ue_ue.TutorialStage.md#nextbuttontext)
- [PlatformsToTest](ue_ue.TutorialStage.md#platformstotest)
- [WidgetContent](ue_ue.TutorialStage.md#widgetcontent)
- [\_\_tid\_TutorialStage\_\_](ue_ue.TutorialStage.md#__tid_tutorialstage__)
- [bInvertPlatformTest](ue_ue.TutorialStage.md#binvertplatformtest)

### Methods

- [StaticClass](ue_ue.TutorialStage.md#staticclass)
- [StaticStruct](ue_ue.TutorialStage.md#staticstruct)

## Constructors

### constructor

• **new TutorialStage**()

• **new TutorialStage**(`Name`, `Content`, `WidgetContent`, `NextButtonText`, `BackButtonText`, `PlatformsToTest`, `bInvertPlatformTest`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `Content` | [`TutorialContent`](ue_ue.TutorialContent.md) |
| `WidgetContent` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TutorialWidgetContent`](ue_ue.TutorialWidgetContent.md)\> |
| `NextButtonText` | `string` |
| `BackButtonText` | `string` |
| `PlatformsToTest` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bInvertPlatformTest` | `boolean` |

## Properties

### BackButtonText

• **BackButtonText**: `string`

___

### Content

• **Content**: [`TutorialContent`](ue_ue.TutorialContent.md)

___

### Name

• **Name**: `string`

___

### NextButtonText

• **NextButtonText**: `string`

___

### PlatformsToTest

• **PlatformsToTest**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### WidgetContent

• **WidgetContent**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TutorialWidgetContent`](ue_ue.TutorialWidgetContent.md)\>

___

### \_\_tid\_TutorialStage\_\_

• `Private` **\_\_tid\_TutorialStage\_\_**: `boolean`

___

### bInvertPlatformTest

• **bInvertPlatformTest**: `boolean`

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
