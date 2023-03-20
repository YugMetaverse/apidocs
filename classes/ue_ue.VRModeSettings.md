[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VRModeSettings

# Class: VRModeSettings

[ue/ue](../modules/ue_ue.md).VRModeSettings

## Hierarchy

- [`VISettings`](ue_ue.VISettings.md)

  ↳ **`VRModeSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.VRModeSettings.md#constructor)

### Properties

- [DoubleClickTime](ue_ue.VRModeSettings.md#doubleclicktime)
- [GizmoScale](ue_ue.VRModeSettings.md#gizmoscale)
- [InteractorClass](ue_ue.VRModeSettings.md#interactorclass)
- [InteractorHand](ue_ue.VRModeSettings.md#interactorhand)
- [TeleporterClass](ue_ue.VRModeSettings.md#teleporterclass)
- [TriggerPressedThreshold\_Rift](ue_ue.VRModeSettings.md#triggerpressedthreshold_rift)
- [TriggerPressedThreshold\_Vive](ue_ue.VRModeSettings.md#triggerpressedthreshold_vive)
- [UIBrightness](ue_ue.VRModeSettings.md#uibrightness)
- [\_\_tid\_Object\_\_](ue_ue.VRModeSettings.md#__tid_object__)
- [\_\_tid\_VISettings\_\_](ue_ue.VRModeSettings.md#__tid_visettings__)
- [\_\_tid\_VRModeSettings\_\_](ue_ue.VRModeSettings.md#__tid_vrmodesettings__)
- [bAllowSimultaneousWorldScalingAndRotation](ue_ue.VRModeSettings.md#ballowsimultaneousworldscalingandrotation)
- [bAutokeySequences](ue_ue.VRModeSettings.md#bautokeysequences)
- [bEnableAutoVREditMode](ue_ue.VRModeSettings.md#benableautovreditmode)
- [bScaleWorldFromFloor](ue_ue.VRModeSettings.md#bscaleworldfromfloor)
- [bScaleWorldWithDynamicPivot](ue_ue.VRModeSettings.md#bscaleworldwithdynamicpivot)
- [bShowWorldMovementGrid](ue_ue.VRModeSettings.md#bshowworldmovementgrid)
- [bShowWorldMovementPostProcess](ue_ue.VRModeSettings.md#bshowworldmovementpostprocess)
- [bShowWorldScaleProgressBar](ue_ue.VRModeSettings.md#bshowworldscaleprogressbar)

### Methods

- [CreateDefaultSubobject](ue_ue.VRModeSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VRModeSettings.md#executeubergraph)
- [GetClass](ue_ue.VRModeSettings.md#getclass)
- [GetName](ue_ue.VRModeSettings.md#getname)
- [GetOuter](ue_ue.VRModeSettings.md#getouter)
- [GetWorld](ue_ue.VRModeSettings.md#getworld)
- [Find](ue_ue.VRModeSettings.md#find)
- [Load](ue_ue.VRModeSettings.md#load)
- [StaticClass](ue_ue.VRModeSettings.md#staticclass)

## Constructors

### constructor

• **new VRModeSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[VISettings](ue_ue.VISettings.md).[constructor](ue_ue.VISettings.md#constructor)

#### Defined in

[ue/ue.d.ts:65973](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65973)

## Properties

### DoubleClickTime

• **DoubleClickTime**: `number`

#### Defined in

[ue/ue.d.ts:65982](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65982)

___

### GizmoScale

• **GizmoScale**: `number`

#### Defined in

[ue/ue.d.ts:65981](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65981)

___

### InteractorClass

• **InteractorClass**: [`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`VREditorInteractor`](ue_ue.VREditorInteractor.md)\>

#### Defined in

[ue/ue.d.ts:65985](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65985)

___

### InteractorHand

• **InteractorHand**: [`EInteractorHand`](../enums/ue_ue.EInteractorHand.md)

#### Defined in

[ue/ue.d.ts:65976](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65976)

___

### TeleporterClass

• **TeleporterClass**: [`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`VREditorTeleporter`](ue_ue.VREditorTeleporter.md)\>

#### Defined in

[ue/ue.d.ts:65986](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65986)

___

### TriggerPressedThreshold\_Rift

• **TriggerPressedThreshold\_Rift**: `number`

#### Defined in

[ue/ue.d.ts:65984](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65984)

___

### TriggerPressedThreshold\_Vive

• **TriggerPressedThreshold\_Vive**: `number`

#### Defined in

[ue/ue.d.ts:65983](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65983)

___

### UIBrightness

• **UIBrightness**: `number`

#### Defined in

[ue/ue.d.ts:65980](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65980)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[VISettings](ue_ue.VISettings.md).[__tid_Object__](ue_ue.VISettings.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_VISettings\_\_

• **\_\_tid\_VISettings\_\_**: `boolean`

#### Inherited from

[VISettings](ue_ue.VISettings.md).[__tid_VISettings__](ue_ue.VISettings.md#__tid_visettings__)

#### Defined in

[ue/ue.d.ts:65269](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65269)

___

### \_\_tid\_VRModeSettings\_\_

• **\_\_tid\_VRModeSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:65991](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65991)

___

### bAllowSimultaneousWorldScalingAndRotation

• **bAllowSimultaneousWorldScalingAndRotation**: `boolean`

#### Inherited from

[VISettings](ue_ue.VISettings.md).[bAllowSimultaneousWorldScalingAndRotation](ue_ue.VISettings.md#ballowsimultaneousworldscalingandrotation)

#### Defined in

[ue/ue.d.ts:65264](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65264)

___

### bAutokeySequences

• **bAutokeySequences**: `boolean`

#### Defined in

[ue/ue.d.ts:65975](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65975)

___

### bEnableAutoVREditMode

• **bEnableAutoVREditMode**: `boolean`

#### Defined in

[ue/ue.d.ts:65974](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65974)

___

### bScaleWorldFromFloor

• **bScaleWorldFromFloor**: `boolean`

#### Inherited from

[VISettings](ue_ue.VISettings.md).[bScaleWorldFromFloor](ue_ue.VISettings.md#bscaleworldfromfloor)

#### Defined in

[ue/ue.d.ts:65262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65262)

___

### bScaleWorldWithDynamicPivot

• **bScaleWorldWithDynamicPivot**: `boolean`

#### Inherited from

[VISettings](ue_ue.VISettings.md).[bScaleWorldWithDynamicPivot](ue_ue.VISettings.md#bscaleworldwithdynamicpivot)

#### Defined in

[ue/ue.d.ts:65263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65263)

___

### bShowWorldMovementGrid

• **bShowWorldMovementGrid**: `boolean`

#### Defined in

[ue/ue.d.ts:65977](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65977)

___

### bShowWorldMovementPostProcess

• **bShowWorldMovementPostProcess**: `boolean`

#### Defined in

[ue/ue.d.ts:65978](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65978)

___

### bShowWorldScaleProgressBar

• **bShowWorldScaleProgressBar**: `boolean`

#### Defined in

[ue/ue.d.ts:65979](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65979)

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

[VISettings](ue_ue.VISettings.md).[CreateDefaultSubobject](ue_ue.VISettings.md#createdefaultsubobject)

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

[VISettings](ue_ue.VISettings.md).[ExecuteUbergraph](ue_ue.VISettings.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[VISettings](ue_ue.VISettings.md).[GetClass](ue_ue.VISettings.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[VISettings](ue_ue.VISettings.md).[GetName](ue_ue.VISettings.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[VISettings](ue_ue.VISettings.md).[GetOuter](ue_ue.VISettings.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[VISettings](ue_ue.VISettings.md).[GetWorld](ue_ue.VISettings.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VRModeSettings`](ue_ue.VRModeSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VRModeSettings`](ue_ue.VRModeSettings.md)

#### Overrides

[VISettings](ue_ue.VISettings.md).[Find](ue_ue.VISettings.md#find)

#### Defined in

[ue/ue.d.ts:65988](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65988)

___

### Load

▸ `Static` **Load**(`InName`): [`VRModeSettings`](ue_ue.VRModeSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VRModeSettings`](ue_ue.VRModeSettings.md)

#### Overrides

[VISettings](ue_ue.VISettings.md).[Load](ue_ue.VISettings.md#load)

#### Defined in

[ue/ue.d.ts:65989](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65989)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[VISettings](ue_ue.VISettings.md).[StaticClass](ue_ue.VISettings.md#staticclass)

#### Defined in

[ue/ue.d.ts:65987](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65987)
