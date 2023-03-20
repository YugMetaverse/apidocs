[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VREditorAssetContainer

# Class: VREditorAssetContainer

[ue/ue](../modules/ue_ue.md).VREditorAssetContainer

## Hierarchy

- [`DataAsset`](ue_ue.DataAsset.md)

  ↳ **`VREditorAssetContainer`**

## Table of contents

### Constructors

- [constructor](ue_ue.VREditorAssetContainer.md#constructor)

### Properties

- [AutoScaleSound](ue_ue.VREditorAssetContainer.md#autoscalesound)
- [ButtonPressSound](ue_ue.VREditorAssetContainer.md#buttonpresssound)
- [CylinderMesh](ue_ue.VREditorAssetContainer.md#cylindermesh)
- [DockableWindowCloseSound](ue_ue.VREditorAssetContainer.md#dockablewindowclosesound)
- [DockableWindowDragSound](ue_ue.VREditorAssetContainer.md#dockablewindowdragsound)
- [DockableWindowDropSound](ue_ue.VREditorAssetContainer.md#dockablewindowdropsound)
- [DockableWindowOpenSound](ue_ue.VREditorAssetContainer.md#dockablewindowopensound)
- [DockingButtonMesh](ue_ue.VREditorAssetContainer.md#dockingbuttonmesh)
- [DropFromContentBrowserSound](ue_ue.VREditorAssetContainer.md#dropfromcontentbrowsersound)
- [GenericControllerMesh](ue_ue.VREditorAssetContainer.md#genericcontrollermesh)
- [GenericHMDMesh](ue_ue.VREditorAssetContainer.md#generichmdmesh)
- [GridMaterial](ue_ue.VREditorAssetContainer.md#gridmaterial)
- [JointSphereMesh](ue_ue.VREditorAssetContainer.md#jointspheremesh)
- [LaserPointerEndMesh](ue_ue.VREditorAssetContainer.md#laserpointerendmesh)
- [LaserPointerHoverMesh](ue_ue.VREditorAssetContainer.md#laserpointerhovermesh)
- [LaserPointerMaterial](ue_ue.VREditorAssetContainer.md#laserpointermaterial)
- [LaserPointerMesh](ue_ue.VREditorAssetContainer.md#laserpointermesh)
- [LaserPointerStartMesh](ue_ue.VREditorAssetContainer.md#laserpointerstartmesh)
- [LaserPointerTranslucentMaterial](ue_ue.VREditorAssetContainer.md#laserpointertranslucentmaterial)
- [LineMaterial](ue_ue.VREditorAssetContainer.md#linematerial)
- [LineSegmentCylinderMesh](ue_ue.VREditorAssetContainer.md#linesegmentcylindermesh)
- [NativeClass](ue_ue.VREditorAssetContainer.md#nativeclass)
- [OculusControllerMaterial](ue_ue.VREditorAssetContainer.md#oculuscontrollermaterial)
- [OculusControllerMesh](ue_ue.VREditorAssetContainer.md#oculuscontrollermesh)
- [PlaneMesh](ue_ue.VREditorAssetContainer.md#planemesh)
- [PointerCursorMesh](ue_ue.VREditorAssetContainer.md#pointercursormesh)
- [RadialMenuCloseSound](ue_ue.VREditorAssetContainer.md#radialmenuclosesound)
- [RadialMenuMainMesh](ue_ue.VREditorAssetContainer.md#radialmenumainmesh)
- [RadialMenuOpenSound](ue_ue.VREditorAssetContainer.md#radialmenuopensound)
- [RadialMenuPointerMesh](ue_ue.VREditorAssetContainer.md#radialmenupointermesh)
- [TeleportMaterial](ue_ue.VREditorAssetContainer.md#teleportmaterial)
- [TeleportRootMesh](ue_ue.VREditorAssetContainer.md#teleportrootmesh)
- [TeleportSound](ue_ue.VREditorAssetContainer.md#teleportsound)
- [TextFont](ue_ue.VREditorAssetContainer.md#textfont)
- [TextMaterial](ue_ue.VREditorAssetContainer.md#textmaterial)
- [TranslucentTextMaterial](ue_ue.VREditorAssetContainer.md#translucenttextmaterial)
- [VivePreControllerMaterial](ue_ue.VREditorAssetContainer.md#viveprecontrollermaterial)
- [VivePreControllerMesh](ue_ue.VREditorAssetContainer.md#viveprecontrollermesh)
- [WindowCloseButtonMesh](ue_ue.VREditorAssetContainer.md#windowclosebuttonmesh)
- [WindowMaterial](ue_ue.VREditorAssetContainer.md#windowmaterial)
- [WindowMesh](ue_ue.VREditorAssetContainer.md#windowmesh)
- [WindowSelectionBarMesh](ue_ue.VREditorAssetContainer.md#windowselectionbarmesh)
- [WindowTranslucentMaterial](ue_ue.VREditorAssetContainer.md#windowtranslucentmaterial)
- [WorldMovementPostProcessMaterial](ue_ue.VREditorAssetContainer.md#worldmovementpostprocessmaterial)
- [\_\_tid\_DataAsset\_\_](ue_ue.VREditorAssetContainer.md#__tid_dataasset__)
- [\_\_tid\_Object\_\_](ue_ue.VREditorAssetContainer.md#__tid_object__)
- [\_\_tid\_VREditorAssetContainer\_\_](ue_ue.VREditorAssetContainer.md#__tid_vreditorassetcontainer__)

### Methods

- [CreateDefaultSubobject](ue_ue.VREditorAssetContainer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VREditorAssetContainer.md#executeubergraph)
- [GetClass](ue_ue.VREditorAssetContainer.md#getclass)
- [GetName](ue_ue.VREditorAssetContainer.md#getname)
- [GetOuter](ue_ue.VREditorAssetContainer.md#getouter)
- [GetWorld](ue_ue.VREditorAssetContainer.md#getworld)
- [Find](ue_ue.VREditorAssetContainer.md#find)
- [Load](ue_ue.VREditorAssetContainer.md#load)
- [StaticClass](ue_ue.VREditorAssetContainer.md#staticclass)

## Constructors

### constructor

• **new VREditorAssetContainer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[constructor](ue_ue.DataAsset.md#constructor)

## Properties

### AutoScaleSound

• **AutoScaleSound**: [`SoundBase`](ue_ue.SoundBase.md)

___

### ButtonPressSound

• **ButtonPressSound**: [`SoundCue`](ue_ue.SoundCue.md)

___

### CylinderMesh

• **CylinderMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### DockableWindowCloseSound

• **DockableWindowCloseSound**: [`SoundBase`](ue_ue.SoundBase.md)

___

### DockableWindowDragSound

• **DockableWindowDragSound**: [`SoundBase`](ue_ue.SoundBase.md)

___

### DockableWindowDropSound

• **DockableWindowDropSound**: [`SoundBase`](ue_ue.SoundBase.md)

___

### DockableWindowOpenSound

• **DockableWindowOpenSound**: [`SoundBase`](ue_ue.SoundBase.md)

___

### DockingButtonMesh

• **DockingButtonMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### DropFromContentBrowserSound

• **DropFromContentBrowserSound**: [`SoundBase`](ue_ue.SoundBase.md)

___

### GenericControllerMesh

• **GenericControllerMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### GenericHMDMesh

• **GenericHMDMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### GridMaterial

• **GridMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### JointSphereMesh

• **JointSphereMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### LaserPointerEndMesh

• **LaserPointerEndMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### LaserPointerHoverMesh

• **LaserPointerHoverMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### LaserPointerMaterial

• **LaserPointerMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### LaserPointerMesh

• **LaserPointerMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### LaserPointerStartMesh

• **LaserPointerStartMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### LaserPointerTranslucentMaterial

• **LaserPointerTranslucentMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### LineMaterial

• **LineMaterial**: [`Material`](ue_ue.Material.md)

___

### LineSegmentCylinderMesh

• **LineSegmentCylinderMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### NativeClass

• **NativeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[NativeClass](ue_ue.DataAsset.md#nativeclass)

___

### OculusControllerMaterial

• **OculusControllerMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### OculusControllerMesh

• **OculusControllerMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### PlaneMesh

• **PlaneMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### PointerCursorMesh

• **PointerCursorMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### RadialMenuCloseSound

• **RadialMenuCloseSound**: [`SoundBase`](ue_ue.SoundBase.md)

___

### RadialMenuMainMesh

• **RadialMenuMainMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### RadialMenuOpenSound

• **RadialMenuOpenSound**: [`SoundBase`](ue_ue.SoundBase.md)

___

### RadialMenuPointerMesh

• **RadialMenuPointerMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### TeleportMaterial

• **TeleportMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### TeleportRootMesh

• **TeleportRootMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### TeleportSound

• **TeleportSound**: [`SoundBase`](ue_ue.SoundBase.md)

___

### TextFont

• **TextFont**: [`Font`](ue_ue.Font.md)

___

### TextMaterial

• **TextMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### TranslucentTextMaterial

• **TranslucentTextMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### VivePreControllerMaterial

• **VivePreControllerMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### VivePreControllerMesh

• **VivePreControllerMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### WindowCloseButtonMesh

• **WindowCloseButtonMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### WindowMaterial

• **WindowMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### WindowMesh

• **WindowMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### WindowSelectionBarMesh

• **WindowSelectionBarMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### WindowTranslucentMaterial

• **WindowTranslucentMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### WorldMovementPostProcessMaterial

• **WorldMovementPostProcessMaterial**: [`Material`](ue_ue.Material.md)

___

### \_\_tid\_DataAsset\_\_

• **\_\_tid\_DataAsset\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_DataAsset__](ue_ue.DataAsset.md#__tid_dataasset__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_Object__](ue_ue.DataAsset.md#__tid_object__)

___

### \_\_tid\_VREditorAssetContainer\_\_

• **\_\_tid\_VREditorAssetContainer\_\_**: `boolean`

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

[DataAsset](ue_ue.DataAsset.md).[CreateDefaultSubobject](ue_ue.DataAsset.md#createdefaultsubobject)

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

[DataAsset](ue_ue.DataAsset.md).[ExecuteUbergraph](ue_ue.DataAsset.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetClass](ue_ue.DataAsset.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetName](ue_ue.DataAsset.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetOuter](ue_ue.DataAsset.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetWorld](ue_ue.DataAsset.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VREditorAssetContainer`](ue_ue.VREditorAssetContainer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VREditorAssetContainer`](ue_ue.VREditorAssetContainer.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Find](ue_ue.DataAsset.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`VREditorAssetContainer`](ue_ue.VREditorAssetContainer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VREditorAssetContainer`](ue_ue.VREditorAssetContainer.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Load](ue_ue.DataAsset.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[StaticClass](ue_ue.DataAsset.md#staticclass)
