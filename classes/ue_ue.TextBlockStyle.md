[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TextBlockStyle

# Class: TextBlockStyle

[ue/ue](../modules/ue_ue.md).TextBlockStyle

## Hierarchy

- [`SlateWidgetStyle`](ue_ue.SlateWidgetStyle.md)

  ↳ **`TextBlockStyle`**

## Table of contents

### Constructors

- [constructor](ue_ue.TextBlockStyle.md#constructor)

### Properties

- [ColorAndOpacity](ue_ue.TextBlockStyle.md#colorandopacity)
- [Font](ue_ue.TextBlockStyle.md#font)
- [HighlightColor](ue_ue.TextBlockStyle.md#highlightcolor)
- [HighlightShape](ue_ue.TextBlockStyle.md#highlightshape)
- [SelectedBackgroundColor](ue_ue.TextBlockStyle.md#selectedbackgroundcolor)
- [ShadowColorAndOpacity](ue_ue.TextBlockStyle.md#shadowcolorandopacity)
- [ShadowOffset](ue_ue.TextBlockStyle.md#shadowoffset)
- [StrikeBrush](ue_ue.TextBlockStyle.md#strikebrush)
- [UnderlineBrush](ue_ue.TextBlockStyle.md#underlinebrush)
- [\_\_tid\_TextBlockStyle\_\_](ue_ue.TextBlockStyle.md#__tid_textblockstyle__)

### Methods

- [StaticClass](ue_ue.TextBlockStyle.md#staticclass)
- [StaticStruct](ue_ue.TextBlockStyle.md#staticstruct)

## Constructors

### constructor

• **new TextBlockStyle**()

#### Overrides

[SlateWidgetStyle](ue_ue.SlateWidgetStyle.md).[constructor](ue_ue.SlateWidgetStyle.md#constructor)

#### Defined in

[ue/ue.d.ts:39243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39243)

• **new TextBlockStyle**(`Font`, `ColorAndOpacity`, `ShadowOffset`, `ShadowColorAndOpacity`, `SelectedBackgroundColor`, `HighlightColor`, `HighlightShape`, `StrikeBrush`, `UnderlineBrush`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Font` | [`SlateFontInfo`](ue_ue.SlateFontInfo.md) |
| `ColorAndOpacity` | [`SlateColor`](ue_ue.SlateColor.md) |
| `ShadowOffset` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `ShadowColorAndOpacity` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `SelectedBackgroundColor` | [`SlateColor`](ue_ue.SlateColor.md) |
| `HighlightColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `HighlightShape` | [`SlateBrush`](ue_ue.SlateBrush.md) |
| `StrikeBrush` | [`SlateBrush`](ue_ue.SlateBrush.md) |
| `UnderlineBrush` | [`SlateBrush`](ue_ue.SlateBrush.md) |

#### Overrides

UE.SlateWidgetStyle.constructor

#### Defined in

[ue/ue.d.ts:39244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39244)

## Properties

### ColorAndOpacity

• **ColorAndOpacity**: [`SlateColor`](ue_ue.SlateColor.md)

#### Defined in

[ue/ue.d.ts:39246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39246)

___

### Font

• **Font**: [`SlateFontInfo`](ue_ue.SlateFontInfo.md)

#### Defined in

[ue/ue.d.ts:39245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39245)

___

### HighlightColor

• **HighlightColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:39250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39250)

___

### HighlightShape

• **HighlightShape**: [`SlateBrush`](ue_ue.SlateBrush.md)

#### Defined in

[ue/ue.d.ts:39251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39251)

___

### SelectedBackgroundColor

• **SelectedBackgroundColor**: [`SlateColor`](ue_ue.SlateColor.md)

#### Defined in

[ue/ue.d.ts:39249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39249)

___

### ShadowColorAndOpacity

• **ShadowColorAndOpacity**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:39248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39248)

___

### ShadowOffset

• **ShadowOffset**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:39247](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39247)

___

### StrikeBrush

• **StrikeBrush**: [`SlateBrush`](ue_ue.SlateBrush.md)

#### Defined in

[ue/ue.d.ts:39252](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39252)

___

### UnderlineBrush

• **UnderlineBrush**: [`SlateBrush`](ue_ue.SlateBrush.md)

#### Defined in

[ue/ue.d.ts:39253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39253)

___

### \_\_tid\_TextBlockStyle\_\_

• `Private` **\_\_tid\_TextBlockStyle\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:39259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39259)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[SlateWidgetStyle](ue_ue.SlateWidgetStyle.md).[StaticClass](ue_ue.SlateWidgetStyle.md#staticclass)

#### Defined in

[ue/ue.d.ts:39257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39257)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[SlateWidgetStyle](ue_ue.SlateWidgetStyle.md).[StaticStruct](ue_ue.SlateWidgetStyle.md#staticstruct)

#### Defined in

[ue/ue.d.ts:39258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39258)
