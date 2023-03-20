[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ButtonStyle

# Class: ButtonStyle

[ue/ue](../modules/ue_ue.md).ButtonStyle

## Hierarchy

- [`SlateWidgetStyle`](ue_ue.SlateWidgetStyle.md)

  ↳ **`ButtonStyle`**

## Table of contents

### Constructors

- [constructor](ue_ue.ButtonStyle.md#constructor)

### Properties

- [Disabled](ue_ue.ButtonStyle.md#disabled)
- [Hovered](ue_ue.ButtonStyle.md#hovered)
- [HoveredSlateSound](ue_ue.ButtonStyle.md#hoveredslatesound)
- [HoveredSound](ue_ue.ButtonStyle.md#hoveredsound)
- [Normal](ue_ue.ButtonStyle.md#normal)
- [NormalPadding](ue_ue.ButtonStyle.md#normalpadding)
- [Pressed](ue_ue.ButtonStyle.md#pressed)
- [PressedPadding](ue_ue.ButtonStyle.md#pressedpadding)
- [PressedSlateSound](ue_ue.ButtonStyle.md#pressedslatesound)
- [PressedSound](ue_ue.ButtonStyle.md#pressedsound)
- [\_\_tid\_ButtonStyle\_\_](ue_ue.ButtonStyle.md#__tid_buttonstyle__)

### Methods

- [StaticClass](ue_ue.ButtonStyle.md#staticclass)
- [StaticStruct](ue_ue.ButtonStyle.md#staticstruct)

## Constructors

### constructor

• **new ButtonStyle**()

#### Overrides

[SlateWidgetStyle](ue_ue.SlateWidgetStyle.md).[constructor](ue_ue.SlateWidgetStyle.md#constructor)

#### Defined in

[ue/ue.d.ts:25607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25607)

• **new ButtonStyle**(`Normal`, `Hovered`, `Pressed`, `Disabled`, `NormalPadding`, `PressedPadding`, `PressedSlateSound`, `HoveredSlateSound`, `PressedSound`, `HoveredSound`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Normal` | [`SlateBrush`](ue_ue.SlateBrush.md) |
| `Hovered` | [`SlateBrush`](ue_ue.SlateBrush.md) |
| `Pressed` | [`SlateBrush`](ue_ue.SlateBrush.md) |
| `Disabled` | [`SlateBrush`](ue_ue.SlateBrush.md) |
| `NormalPadding` | [`Margin`](ue_ue.Margin.md) |
| `PressedPadding` | [`Margin`](ue_ue.Margin.md) |
| `PressedSlateSound` | [`SlateSound`](ue_ue.SlateSound.md) |
| `HoveredSlateSound` | [`SlateSound`](ue_ue.SlateSound.md) |
| `PressedSound` | `string` |
| `HoveredSound` | `string` |

#### Overrides

UE.SlateWidgetStyle.constructor

#### Defined in

[ue/ue.d.ts:25608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25608)

## Properties

### Disabled

• **Disabled**: [`SlateBrush`](ue_ue.SlateBrush.md)

#### Defined in

[ue/ue.d.ts:25612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25612)

___

### Hovered

• **Hovered**: [`SlateBrush`](ue_ue.SlateBrush.md)

#### Defined in

[ue/ue.d.ts:25610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25610)

___

### HoveredSlateSound

• **HoveredSlateSound**: [`SlateSound`](ue_ue.SlateSound.md)

#### Defined in

[ue/ue.d.ts:25616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25616)

___

### HoveredSound

• **HoveredSound**: `string`

#### Defined in

[ue/ue.d.ts:25618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25618)

___

### Normal

• **Normal**: [`SlateBrush`](ue_ue.SlateBrush.md)

#### Defined in

[ue/ue.d.ts:25609](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25609)

___

### NormalPadding

• **NormalPadding**: [`Margin`](ue_ue.Margin.md)

#### Defined in

[ue/ue.d.ts:25613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25613)

___

### Pressed

• **Pressed**: [`SlateBrush`](ue_ue.SlateBrush.md)

#### Defined in

[ue/ue.d.ts:25611](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25611)

___

### PressedPadding

• **PressedPadding**: [`Margin`](ue_ue.Margin.md)

#### Defined in

[ue/ue.d.ts:25614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25614)

___

### PressedSlateSound

• **PressedSlateSound**: [`SlateSound`](ue_ue.SlateSound.md)

#### Defined in

[ue/ue.d.ts:25615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25615)

___

### PressedSound

• **PressedSound**: `string`

#### Defined in

[ue/ue.d.ts:25617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25617)

___

### \_\_tid\_ButtonStyle\_\_

• `Private` **\_\_tid\_ButtonStyle\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:25624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25624)

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

[ue/ue.d.ts:25622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25622)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[SlateWidgetStyle](ue_ue.SlateWidgetStyle.md).[StaticStruct](ue_ue.SlateWidgetStyle.md#staticstruct)

#### Defined in

[ue/ue.d.ts:25623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25623)
