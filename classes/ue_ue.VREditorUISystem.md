[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VREditorUISystem

# Class: VREditorUISystem

[ue/ue](../modules/ue_ue.md).VREditorUISystem

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`VREditorUISystem`**

## Table of contents

### Constructors

- [constructor](ue_ue.VREditorUISystem.md#constructor)

### Properties

- [ColorPickerUI](ue_ue.VREditorUISystem.md#colorpickerui)
- [DraggingUI](ue_ue.VREditorUISystem.md#draggingui)
- [FloatingUIs](ue_ue.VREditorUISystem.md#floatinguis)
- [InfoDisplayPanel](ue_ue.VREditorUISystem.md#infodisplaypanel)
- [LaserInteractor](ue_ue.VREditorUISystem.md#laserinteractor)
- [PreviewWindowInfo](ue_ue.VREditorUISystem.md#previewwindowinfo)
- [QuickRadialMenu](ue_ue.VREditorUISystem.md#quickradialmenu)
- [RadialMenuHandler](ue_ue.VREditorUISystem.md#radialmenuhandler)
- [UIInteractor](ue_ue.VREditorUISystem.md#uiinteractor)
- [VRButtons](ue_ue.VREditorUISystem.md#vrbuttons)
- [VRMode](ue_ue.VREditorUISystem.md#vrmode)
- [\_\_tid\_Object\_\_](ue_ue.VREditorUISystem.md#__tid_object__)
- [\_\_tid\_VREditorUISystem\_\_](ue_ue.VREditorUISystem.md#__tid_vreditoruisystem__)

### Methods

- [CreateDefaultSubobject](ue_ue.VREditorUISystem.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VREditorUISystem.md#executeubergraph)
- [GetClass](ue_ue.VREditorUISystem.md#getclass)
- [GetName](ue_ue.VREditorUISystem.md#getname)
- [GetOuter](ue_ue.VREditorUISystem.md#getouter)
- [GetWorld](ue_ue.VREditorUISystem.md#getworld)
- [Find](ue_ue.VREditorUISystem.md#find)
- [Load](ue_ue.VREditorUISystem.md#load)
- [StaticClass](ue_ue.VREditorUISystem.md#staticclass)

## Constructors

### constructor

• **new VREditorUISystem**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:65873](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65873)

## Properties

### ColorPickerUI

• **ColorPickerUI**: [`VREditorDockableWindow`](ue_ue.VREditorDockableWindow.md)

#### Defined in

[ue/ue.d.ts:65880](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65880)

___

### DraggingUI

• **DraggingUI**: [`VREditorDockableWindow`](ue_ue.VREditorDockableWindow.md)

#### Defined in

[ue/ue.d.ts:65879](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65879)

___

### FloatingUIs

• **FloatingUIs**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`VREditorFloatingUI`](ue_ue.VREditorFloatingUI.md)\>

#### Defined in

[ue/ue.d.ts:65875](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65875)

___

### InfoDisplayPanel

• **InfoDisplayPanel**: [`VREditorFloatingUI`](ue_ue.VREditorFloatingUI.md)

#### Defined in

[ue/ue.d.ts:65877](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65877)

___

### LaserInteractor

• **LaserInteractor**: [`VREditorInteractor`](ue_ue.VREditorInteractor.md)

#### Defined in

[ue/ue.d.ts:65881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65881)

___

### PreviewWindowInfo

• **PreviewWindowInfo**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:65876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65876)

___

### QuickRadialMenu

• **QuickRadialMenu**: [`VREditorRadialFloatingUI`](ue_ue.VREditorRadialFloatingUI.md)

#### Defined in

[ue/ue.d.ts:65878](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65878)

___

### RadialMenuHandler

• **RadialMenuHandler**: [`VRRadialMenuHandler`](ue_ue.VRRadialMenuHandler.md)

#### Defined in

[ue/ue.d.ts:65884](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65884)

___

### UIInteractor

• **UIInteractor**: [`VREditorInteractor`](ue_ue.VREditorInteractor.md)

#### Defined in

[ue/ue.d.ts:65882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65882)

___

### VRButtons

• **VRButtons**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VRButton`](ue_ue.VRButton.md)\>

#### Defined in

[ue/ue.d.ts:65883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65883)

___

### VRMode

• **VRMode**: [`VREditorMode`](ue_ue.VREditorMode.md)

#### Defined in

[ue/ue.d.ts:65874](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65874)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_VREditorUISystem\_\_

• **\_\_tid\_VREditorUISystem\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:65889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65889)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VREditorUISystem`](ue_ue.VREditorUISystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VREditorUISystem`](ue_ue.VREditorUISystem.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:65886](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65886)

___

### Load

▸ `Static` **Load**(`InName`): [`VREditorUISystem`](ue_ue.VREditorUISystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VREditorUISystem`](ue_ue.VREditorUISystem.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:65887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65887)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:65885](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65885)
