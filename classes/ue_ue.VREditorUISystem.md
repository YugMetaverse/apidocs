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

## Properties

### ColorPickerUI

• **ColorPickerUI**: [`VREditorDockableWindow`](ue_ue.VREditorDockableWindow.md)

___

### DraggingUI

• **DraggingUI**: [`VREditorDockableWindow`](ue_ue.VREditorDockableWindow.md)

___

### FloatingUIs

• **FloatingUIs**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`VREditorFloatingUI`](ue_ue.VREditorFloatingUI.md)\>

___

### InfoDisplayPanel

• **InfoDisplayPanel**: [`VREditorFloatingUI`](ue_ue.VREditorFloatingUI.md)

___

### LaserInteractor

• **LaserInteractor**: [`VREditorInteractor`](ue_ue.VREditorInteractor.md)

___

### PreviewWindowInfo

• **PreviewWindowInfo**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`Actor`](ue_ue.Actor.md)\>

___

### QuickRadialMenu

• **QuickRadialMenu**: [`VREditorRadialFloatingUI`](ue_ue.VREditorRadialFloatingUI.md)

___

### RadialMenuHandler

• **RadialMenuHandler**: [`VRRadialMenuHandler`](ue_ue.VRRadialMenuHandler.md)

___

### UIInteractor

• **UIInteractor**: [`VREditorInteractor`](ue_ue.VREditorInteractor.md)

___

### VRButtons

• **VRButtons**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VRButton`](ue_ue.VRButton.md)\>

___

### VRMode

• **VRMode**: [`VREditorMode`](ue_ue.VREditorMode.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_VREditorUISystem\_\_

• **\_\_tid\_VREditorUISystem\_\_**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
