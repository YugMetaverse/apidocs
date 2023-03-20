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

#### Defined in

[ue/ue.d.ts:65532](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65532)

## Properties

### AutoScaleSound

• **AutoScaleSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:65542](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65542)

___

### ButtonPressSound

• **ButtonPressSound**: [`SoundCue`](ue_ue.SoundCue.md)

#### Defined in

[ue/ue.d.ts:65541](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65541)

___

### CylinderMesh

• **CylinderMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65545)

___

### DockableWindowCloseSound

• **DockableWindowCloseSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:65533](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65533)

___

### DockableWindowDragSound

• **DockableWindowDragSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:65536](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65536)

___

### DockableWindowDropSound

• **DockableWindowDropSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:65535](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65535)

___

### DockableWindowOpenSound

• **DockableWindowOpenSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:65534](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65534)

___

### DockingButtonMesh

• **DockingButtonMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65562](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65562)

___

### DropFromContentBrowserSound

• **DropFromContentBrowserSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:65537](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65537)

___

### GenericControllerMesh

• **GenericControllerMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65552](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65552)

___

### GenericHMDMesh

• **GenericHMDMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65543](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65543)

___

### GridMaterial

• **GridMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:65563](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65563)

___

### JointSphereMesh

• **JointSphereMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65561](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65561)

___

### LaserPointerEndMesh

• **LaserPointerEndMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65548](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65548)

___

### LaserPointerHoverMesh

• **LaserPointerHoverMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65549](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65549)

___

### LaserPointerMaterial

• **LaserPointerMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:65564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65564)

___

### LaserPointerMesh

• **LaserPointerMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65547)

___

### LaserPointerStartMesh

• **LaserPointerStartMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65546](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65546)

___

### LaserPointerTranslucentMaterial

• **LaserPointerTranslucentMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:65565](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65565)

___

### LineMaterial

• **LineMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:65573](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65573)

___

### LineSegmentCylinderMesh

• **LineSegmentCylinderMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65560](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65560)

___

### NativeClass

• **NativeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[NativeClass](ue_ue.DataAsset.md#nativeclass)

#### Defined in

[ue/ue.d.ts:724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L724)

___

### OculusControllerMaterial

• **OculusControllerMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:65569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65569)

___

### OculusControllerMesh

• **OculusControllerMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65551](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65551)

___

### PlaneMesh

• **PlaneMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65544](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65544)

___

### PointerCursorMesh

• **PointerCursorMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65559)

___

### RadialMenuCloseSound

• **RadialMenuCloseSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:65539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65539)

___

### RadialMenuMainMesh

• **RadialMenuMainMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65557)

___

### RadialMenuOpenSound

• **RadialMenuOpenSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:65538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65538)

___

### RadialMenuPointerMesh

• **RadialMenuPointerMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65558)

___

### TeleportMaterial

• **TeleportMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:65570](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65570)

___

### TeleportRootMesh

• **TeleportRootMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65553](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65553)

___

### TeleportSound

• **TeleportSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:65540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65540)

___

### TextFont

• **TextFont**: [`Font`](ue_ue.Font.md)

#### Defined in

[ue/ue.d.ts:65575](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65575)

___

### TextMaterial

• **TextMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:65567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65567)

___

### TranslucentTextMaterial

• **TranslucentTextMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:65574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65574)

___

### VivePreControllerMaterial

• **VivePreControllerMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:65568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65568)

___

### VivePreControllerMesh

• **VivePreControllerMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65550](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65550)

___

### WindowCloseButtonMesh

• **WindowCloseButtonMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65556)

___

### WindowMaterial

• **WindowMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:65571](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65571)

___

### WindowMesh

• **WindowMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65554)

___

### WindowSelectionBarMesh

• **WindowSelectionBarMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:65555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65555)

___

### WindowTranslucentMaterial

• **WindowTranslucentMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:65572](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65572)

___

### WorldMovementPostProcessMaterial

• **WorldMovementPostProcessMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:65566](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65566)

___

### \_\_tid\_DataAsset\_\_

• **\_\_tid\_DataAsset\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_DataAsset__](ue_ue.DataAsset.md#__tid_dataasset__)

#### Defined in

[ue/ue.d.ts:729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L729)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_Object__](ue_ue.DataAsset.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_VREditorAssetContainer\_\_

• **\_\_tid\_VREditorAssetContainer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:65580](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65580)

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

[DataAsset](ue_ue.DataAsset.md).[ExecuteUbergraph](ue_ue.DataAsset.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetClass](ue_ue.DataAsset.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetName](ue_ue.DataAsset.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetOuter](ue_ue.DataAsset.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetWorld](ue_ue.DataAsset.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:65577](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65577)

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

#### Defined in

[ue/ue.d.ts:65578](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65578)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[StaticClass](ue_ue.DataAsset.md#staticclass)

#### Defined in

[ue/ue.d.ts:65576](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65576)
