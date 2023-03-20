[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ViewportInteractionAssetContainer

# Class: ViewportInteractionAssetContainer

[ue/ue](../modules/ue_ue.md).ViewportInteractionAssetContainer

## Hierarchy

- [`DataAsset`](ue_ue.DataAsset.md)

  ↳ **`ViewportInteractionAssetContainer`**

## Table of contents

### Constructors

- [constructor](ue_ue.ViewportInteractionAssetContainer.md#constructor)

### Properties

- [ActorSnapSound](ue_ue.ViewportInteractionAssetContainer.md#actorsnapsound)
- [CurrentRotationIndicatorMesh](ue_ue.ViewportInteractionAssetContainer.md#currentrotationindicatormesh)
- [FreeRotationHandleMesh](ue_ue.ViewportInteractionAssetContainer.md#freerotationhandlemesh)
- [GizmoHandleDropSound](ue_ue.ViewportInteractionAssetContainer.md#gizmohandledropsound)
- [GizmoHandleSelectedSound](ue_ue.ViewportInteractionAssetContainer.md#gizmohandleselectedsound)
- [GridMaterial](ue_ue.ViewportInteractionAssetContainer.md#gridmaterial)
- [GridMesh](ue_ue.ViewportInteractionAssetContainer.md#gridmesh)
- [GridSnapSound](ue_ue.ViewportInteractionAssetContainer.md#gridsnapsound)
- [NativeClass](ue_ue.ViewportInteractionAssetContainer.md#nativeclass)
- [PlaneTranslationHandleMesh](ue_ue.ViewportInteractionAssetContainer.md#planetranslationhandlemesh)
- [RedoSound](ue_ue.ViewportInteractionAssetContainer.md#redosound)
- [RotationHandleMesh](ue_ue.ViewportInteractionAssetContainer.md#rotationhandlemesh)
- [RotationHandleSelectedMesh](ue_ue.ViewportInteractionAssetContainer.md#rotationhandleselectedmesh)
- [ScaleHandleMesh](ue_ue.ViewportInteractionAssetContainer.md#scalehandlemesh)
- [SelectionChangeSound](ue_ue.ViewportInteractionAssetContainer.md#selectionchangesound)
- [SelectionDropSound](ue_ue.ViewportInteractionAssetContainer.md#selectiondropsound)
- [SelectionStartDragSound](ue_ue.ViewportInteractionAssetContainer.md#selectionstartdragsound)
- [StartRotationIndicatorMesh](ue_ue.ViewportInteractionAssetContainer.md#startrotationindicatormesh)
- [TransformGizmoMaterial](ue_ue.ViewportInteractionAssetContainer.md#transformgizmomaterial)
- [TranslationHandleMesh](ue_ue.ViewportInteractionAssetContainer.md#translationhandlemesh)
- [TranslucentTransformGizmoMaterial](ue_ue.ViewportInteractionAssetContainer.md#translucenttransformgizmomaterial)
- [UndoSound](ue_ue.ViewportInteractionAssetContainer.md#undosound)
- [UniformScaleHandleMesh](ue_ue.ViewportInteractionAssetContainer.md#uniformscalehandlemesh)
- [\_\_tid\_DataAsset\_\_](ue_ue.ViewportInteractionAssetContainer.md#__tid_dataasset__)
- [\_\_tid\_Object\_\_](ue_ue.ViewportInteractionAssetContainer.md#__tid_object__)
- [\_\_tid\_ViewportInteractionAssetContainer\_\_](ue_ue.ViewportInteractionAssetContainer.md#__tid_viewportinteractionassetcontainer__)

### Methods

- [CreateDefaultSubobject](ue_ue.ViewportInteractionAssetContainer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ViewportInteractionAssetContainer.md#executeubergraph)
- [GetClass](ue_ue.ViewportInteractionAssetContainer.md#getclass)
- [GetName](ue_ue.ViewportInteractionAssetContainer.md#getname)
- [GetOuter](ue_ue.ViewportInteractionAssetContainer.md#getouter)
- [GetWorld](ue_ue.ViewportInteractionAssetContainer.md#getworld)
- [Find](ue_ue.ViewportInteractionAssetContainer.md#find)
- [Load](ue_ue.ViewportInteractionAssetContainer.md#load)
- [StaticClass](ue_ue.ViewportInteractionAssetContainer.md#staticclass)

## Constructors

### constructor

• **new ViewportInteractionAssetContainer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[constructor](ue_ue.DataAsset.md#constructor)

#### Defined in

[ue/ue.d.ts:14446](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14446)

## Properties

### ActorSnapSound

• **ActorSnapSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:14453](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14453)

___

### CurrentRotationIndicatorMesh

• **CurrentRotationIndicatorMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:14464](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14464)

___

### FreeRotationHandleMesh

• **FreeRotationHandleMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:14465](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14465)

___

### GizmoHandleDropSound

• **GizmoHandleDropSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:14448](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14448)

___

### GizmoHandleSelectedSound

• **GizmoHandleSelectedSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:14447](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14447)

___

### GridMaterial

• **GridMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:14466](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14466)

___

### GridMesh

• **GridMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:14456](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14456)

___

### GridSnapSound

• **GridSnapSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:14452](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14452)

___

### NativeClass

• **NativeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[NativeClass](ue_ue.DataAsset.md#nativeclass)

#### Defined in

[ue/ue.d.ts:724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L724)

___

### PlaneTranslationHandleMesh

• **PlaneTranslationHandleMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:14460](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14460)

___

### RedoSound

• **RedoSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:14455](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14455)

___

### RotationHandleMesh

• **RotationHandleMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:14461](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14461)

___

### RotationHandleSelectedMesh

• **RotationHandleSelectedMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:14462](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14462)

___

### ScaleHandleMesh

• **ScaleHandleMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:14459](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14459)

___

### SelectionChangeSound

• **SelectionChangeSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:14449](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14449)

___

### SelectionDropSound

• **SelectionDropSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:14450](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14450)

___

### SelectionStartDragSound

• **SelectionStartDragSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:14451](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14451)

___

### StartRotationIndicatorMesh

• **StartRotationIndicatorMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:14463](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14463)

___

### TransformGizmoMaterial

• **TransformGizmoMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:14467](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14467)

___

### TranslationHandleMesh

• **TranslationHandleMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:14457](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14457)

___

### TranslucentTransformGizmoMaterial

• **TranslucentTransformGizmoMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:14468](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14468)

___

### UndoSound

• **UndoSound**: [`SoundBase`](ue_ue.SoundBase.md)

#### Defined in

[ue/ue.d.ts:14454](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14454)

___

### UniformScaleHandleMesh

• **UniformScaleHandleMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:14458](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14458)

___

### \_\_tid\_DataAsset\_\_

• **\_\_tid\_DataAsset\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_DataAsset__](ue_ue.DataAsset.md#__tid_dataasset__)

#### Defined in

[ue/ue.d.ts:729](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L729)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_Object__](ue_ue.DataAsset.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ViewportInteractionAssetContainer\_\_

• **\_\_tid\_ViewportInteractionAssetContainer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14473](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14473)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetClass](ue_ue.DataAsset.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetName](ue_ue.DataAsset.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetOuter](ue_ue.DataAsset.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetWorld](ue_ue.DataAsset.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ViewportInteractionAssetContainer`](ue_ue.ViewportInteractionAssetContainer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ViewportInteractionAssetContainer`](ue_ue.ViewportInteractionAssetContainer.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Find](ue_ue.DataAsset.md#find)

#### Defined in

[ue/ue.d.ts:14470](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14470)

___

### Load

▸ `Static` **Load**(`InName`): [`ViewportInteractionAssetContainer`](ue_ue.ViewportInteractionAssetContainer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ViewportInteractionAssetContainer`](ue_ue.ViewportInteractionAssetContainer.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Load](ue_ue.DataAsset.md#load)

#### Defined in

[ue/ue.d.ts:14471](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14471)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[StaticClass](ue_ue.DataAsset.md#staticclass)

#### Defined in

[ue/ue.d.ts:14469](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14469)
