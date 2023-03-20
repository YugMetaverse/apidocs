[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WidgetLayoutLibrary

# Class: WidgetLayoutLibrary

[ue/ue](../modules/ue_ue.md).WidgetLayoutLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`WidgetLayoutLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.WidgetLayoutLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.WidgetLayoutLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.WidgetLayoutLibrary.md#__tid_object__)
- [\_\_tid\_WidgetLayoutLibrary\_\_](ue_ue.WidgetLayoutLibrary.md#__tid_widgetlayoutlibrary__)

### Methods

- [CreateDefaultSubobject](ue_ue.WidgetLayoutLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.WidgetLayoutLibrary.md#executeubergraph)
- [GetClass](ue_ue.WidgetLayoutLibrary.md#getclass)
- [GetName](ue_ue.WidgetLayoutLibrary.md#getname)
- [GetOuter](ue_ue.WidgetLayoutLibrary.md#getouter)
- [GetWorld](ue_ue.WidgetLayoutLibrary.md#getworld)
- [Find](ue_ue.WidgetLayoutLibrary.md#find)
- [GetMousePositionOnPlatform](ue_ue.WidgetLayoutLibrary.md#getmousepositiononplatform)
- [GetMousePositionOnViewport](ue_ue.WidgetLayoutLibrary.md#getmousepositiononviewport)
- [GetMousePositionScaledByDPI](ue_ue.WidgetLayoutLibrary.md#getmousepositionscaledbydpi)
- [GetPlayerScreenWidgetGeometry](ue_ue.WidgetLayoutLibrary.md#getplayerscreenwidgetgeometry)
- [GetViewportScale](ue_ue.WidgetLayoutLibrary.md#getviewportscale)
- [GetViewportSize](ue_ue.WidgetLayoutLibrary.md#getviewportsize)
- [GetViewportWidgetGeometry](ue_ue.WidgetLayoutLibrary.md#getviewportwidgetgeometry)
- [Load](ue_ue.WidgetLayoutLibrary.md#load)
- [ProjectWorldLocationToWidgetPosition](ue_ue.WidgetLayoutLibrary.md#projectworldlocationtowidgetposition)
- [RemoveAllWidgets](ue_ue.WidgetLayoutLibrary.md#removeallwidgets)
- [SlotAsBorderSlot](ue_ue.WidgetLayoutLibrary.md#slotasborderslot)
- [SlotAsCanvasSlot](ue_ue.WidgetLayoutLibrary.md#slotascanvasslot)
- [SlotAsGridSlot](ue_ue.WidgetLayoutLibrary.md#slotasgridslot)
- [SlotAsHorizontalBoxSlot](ue_ue.WidgetLayoutLibrary.md#slotashorizontalboxslot)
- [SlotAsOverlaySlot](ue_ue.WidgetLayoutLibrary.md#slotasoverlayslot)
- [SlotAsSafeBoxSlot](ue_ue.WidgetLayoutLibrary.md#slotassafeboxslot)
- [SlotAsScaleBoxSlot](ue_ue.WidgetLayoutLibrary.md#slotasscaleboxslot)
- [SlotAsScrollBoxSlot](ue_ue.WidgetLayoutLibrary.md#slotasscrollboxslot)
- [SlotAsSizeBoxSlot](ue_ue.WidgetLayoutLibrary.md#slotassizeboxslot)
- [SlotAsUniformGridSlot](ue_ue.WidgetLayoutLibrary.md#slotasuniformgridslot)
- [SlotAsVerticalBoxSlot](ue_ue.WidgetLayoutLibrary.md#slotasverticalboxslot)
- [SlotAsWidgetSwitcherSlot](ue_ue.WidgetLayoutLibrary.md#slotaswidgetswitcherslot)
- [SlotAsWrapBoxSlot](ue_ue.WidgetLayoutLibrary.md#slotaswrapboxslot)
- [StaticClass](ue_ue.WidgetLayoutLibrary.md#staticclass)

## Constructors

### constructor

• **new WidgetLayoutLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:66370](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66370)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_WidgetLayoutLibrary\_\_

• **\_\_tid\_WidgetLayoutLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:66397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66397)

## Methods

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`WidgetLayoutLibrary`](ue_ue.WidgetLayoutLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`WidgetLayoutLibrary`](ue_ue.WidgetLayoutLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:66394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66394)

___

### GetMousePositionOnPlatform

▸ `Static` **GetMousePositionOnPlatform**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:66371](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66371)

___

### GetMousePositionOnViewport

▸ `Static` **GetMousePositionOnViewport**(`WorldContextObject`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:66372](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66372)

___

### GetMousePositionScaledByDPI

▸ `Static` **GetMousePositionScaledByDPI**(`Player`, `LocationX`, `LocationY`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Player` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `LocationX` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `LocationY` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:66373](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66373)

___

### GetPlayerScreenWidgetGeometry

▸ `Static` **GetPlayerScreenWidgetGeometry**(`PlayerController`): [`Geometry`](ue_ue.Geometry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Defined in

[ue/ue.d.ts:66374](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66374)

___

### GetViewportScale

▸ `Static` **GetViewportScale**(`WorldContextObject`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:66375](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66375)

___

### GetViewportSize

▸ `Static` **GetViewportSize**(`WorldContextObject`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:66376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66376)

___

### GetViewportWidgetGeometry

▸ `Static` **GetViewportWidgetGeometry**(`WorldContextObject`): [`Geometry`](ue_ue.Geometry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Defined in

[ue/ue.d.ts:66377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66377)

___

### Load

▸ `Static` **Load**(`InName`): [`WidgetLayoutLibrary`](ue_ue.WidgetLayoutLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`WidgetLayoutLibrary`](ue_ue.WidgetLayoutLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:66395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66395)

___

### ProjectWorldLocationToWidgetPosition

▸ `Static` **ProjectWorldLocationToWidgetPosition**(`PlayerController`, `WorldLocation`, `ScreenPosition`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `ScreenPosition` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:66378](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66378)

___

### RemoveAllWidgets

▸ `Static` **RemoveAllWidgets**(`WorldContextObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:66379](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66379)

___

### SlotAsBorderSlot

▸ `Static` **SlotAsBorderSlot**(`Widget`): [`BorderSlot`](ue_ue.BorderSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`BorderSlot`](ue_ue.BorderSlot.md)

#### Defined in

[ue/ue.d.ts:66380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66380)

___

### SlotAsCanvasSlot

▸ `Static` **SlotAsCanvasSlot**(`Widget`): [`CanvasPanelSlot`](ue_ue.CanvasPanelSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`CanvasPanelSlot`](ue_ue.CanvasPanelSlot.md)

#### Defined in

[ue/ue.d.ts:66381](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66381)

___

### SlotAsGridSlot

▸ `Static` **SlotAsGridSlot**(`Widget`): [`GridSlot`](ue_ue.GridSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`GridSlot`](ue_ue.GridSlot.md)

#### Defined in

[ue/ue.d.ts:66382](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66382)

___

### SlotAsHorizontalBoxSlot

▸ `Static` **SlotAsHorizontalBoxSlot**(`Widget`): [`HorizontalBoxSlot`](ue_ue.HorizontalBoxSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`HorizontalBoxSlot`](ue_ue.HorizontalBoxSlot.md)

#### Defined in

[ue/ue.d.ts:66383](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66383)

___

### SlotAsOverlaySlot

▸ `Static` **SlotAsOverlaySlot**(`Widget`): [`OverlaySlot`](ue_ue.OverlaySlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`OverlaySlot`](ue_ue.OverlaySlot.md)

#### Defined in

[ue/ue.d.ts:66384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66384)

___

### SlotAsSafeBoxSlot

▸ `Static` **SlotAsSafeBoxSlot**(`Widget`): [`SafeZoneSlot`](ue_ue.SafeZoneSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`SafeZoneSlot`](ue_ue.SafeZoneSlot.md)

#### Defined in

[ue/ue.d.ts:66385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66385)

___

### SlotAsScaleBoxSlot

▸ `Static` **SlotAsScaleBoxSlot**(`Widget`): [`ScaleBoxSlot`](ue_ue.ScaleBoxSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`ScaleBoxSlot`](ue_ue.ScaleBoxSlot.md)

#### Defined in

[ue/ue.d.ts:66386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66386)

___

### SlotAsScrollBoxSlot

▸ `Static` **SlotAsScrollBoxSlot**(`Widget`): [`ScrollBoxSlot`](ue_ue.ScrollBoxSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`ScrollBoxSlot`](ue_ue.ScrollBoxSlot.md)

#### Defined in

[ue/ue.d.ts:66387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66387)

___

### SlotAsSizeBoxSlot

▸ `Static` **SlotAsSizeBoxSlot**(`Widget`): [`SizeBoxSlot`](ue_ue.SizeBoxSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`SizeBoxSlot`](ue_ue.SizeBoxSlot.md)

#### Defined in

[ue/ue.d.ts:66388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66388)

___

### SlotAsUniformGridSlot

▸ `Static` **SlotAsUniformGridSlot**(`Widget`): [`UniformGridSlot`](ue_ue.UniformGridSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`UniformGridSlot`](ue_ue.UniformGridSlot.md)

#### Defined in

[ue/ue.d.ts:66389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66389)

___

### SlotAsVerticalBoxSlot

▸ `Static` **SlotAsVerticalBoxSlot**(`Widget`): [`VerticalBoxSlot`](ue_ue.VerticalBoxSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`VerticalBoxSlot`](ue_ue.VerticalBoxSlot.md)

#### Defined in

[ue/ue.d.ts:66390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66390)

___

### SlotAsWidgetSwitcherSlot

▸ `Static` **SlotAsWidgetSwitcherSlot**(`Widget`): [`WidgetSwitcherSlot`](ue_ue.WidgetSwitcherSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`WidgetSwitcherSlot`](ue_ue.WidgetSwitcherSlot.md)

#### Defined in

[ue/ue.d.ts:66391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66391)

___

### SlotAsWrapBoxSlot

▸ `Static` **SlotAsWrapBoxSlot**(`Widget`): [`WrapBoxSlot`](ue_ue.WrapBoxSlot.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

[`WrapBoxSlot`](ue_ue.WrapBoxSlot.md)

#### Defined in

[ue/ue.d.ts:66392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66392)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:66393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66393)
