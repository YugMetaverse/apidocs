[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ThumbnailManager

# Class: ThumbnailManager

[ue/ue](../modules/ue_ue.md).ThumbnailManager

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ThumbnailManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.ThumbnailManager.md#constructor)

### Properties

- [AmbientCubemap](ue_ue.ThumbnailManager.md#ambientcubemap)
- [CheckerboardTexture](ue_ue.ThumbnailManager.md#checkerboardtexture)
- [EditorCube](ue_ue.ThumbnailManager.md#editorcube)
- [EditorCylinder](ue_ue.ThumbnailManager.md#editorcylinder)
- [EditorPlane](ue_ue.ThumbnailManager.md#editorplane)
- [EditorSkySphere](ue_ue.ThumbnailManager.md#editorskysphere)
- [EditorSphere](ue_ue.ThumbnailManager.md#editorsphere)
- [FloorPlaneMaterial](ue_ue.ThumbnailManager.md#floorplanematerial)
- [NotSupported](ue_ue.ThumbnailManager.md#notsupported)
- [RenderableThumbnailTypes](ue_ue.ThumbnailManager.md#renderablethumbnailtypes)
- [ThumbnailManagerClassName](ue_ue.ThumbnailManager.md#thumbnailmanagerclassname)
- [\_\_tid\_Object\_\_](ue_ue.ThumbnailManager.md#__tid_object__)
- [\_\_tid\_ThumbnailManager\_\_](ue_ue.ThumbnailManager.md#__tid_thumbnailmanager__)

### Methods

- [CreateDefaultSubobject](ue_ue.ThumbnailManager.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ThumbnailManager.md#executeubergraph)
- [GetClass](ue_ue.ThumbnailManager.md#getclass)
- [GetName](ue_ue.ThumbnailManager.md#getname)
- [GetOuter](ue_ue.ThumbnailManager.md#getouter)
- [GetWorld](ue_ue.ThumbnailManager.md#getworld)
- [Find](ue_ue.ThumbnailManager.md#find)
- [Load](ue_ue.ThumbnailManager.md#load)
- [StaticClass](ue_ue.ThumbnailManager.md#staticclass)

## Constructors

### constructor

• **new ThumbnailManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:63414](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63414)

## Properties

### AmbientCubemap

• **AmbientCubemap**: [`TextureCube`](ue_ue.TextureCube.md)

#### Defined in

[ue/ue.d.ts:63423](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63423)

___

### CheckerboardTexture

• **CheckerboardTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:63424](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63424)

___

### EditorCube

• **EditorCube**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:63417](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63417)

___

### EditorCylinder

• **EditorCylinder**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:63419](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63419)

___

### EditorPlane

• **EditorPlane**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:63420](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63420)

___

### EditorSkySphere

• **EditorSkySphere**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:63421](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63421)

___

### EditorSphere

• **EditorSphere**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:63418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63418)

___

### FloorPlaneMaterial

• **FloorPlaneMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:63422](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63422)

___

### NotSupported

• **NotSupported**: [`ThumbnailRenderingInfo`](ue_ue.ThumbnailRenderingInfo.md)

#### Defined in

[ue/ue.d.ts:63416](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63416)

___

### RenderableThumbnailTypes

• **RenderableThumbnailTypes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ThumbnailRenderingInfo`](ue_ue.ThumbnailRenderingInfo.md)\>

#### Defined in

[ue/ue.d.ts:63415](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63415)

___

### ThumbnailManagerClassName

• **ThumbnailManagerClassName**: `string`

#### Defined in

[ue/ue.d.ts:63425](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63425)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ThumbnailManager\_\_

• **\_\_tid\_ThumbnailManager\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:63430](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63430)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ThumbnailManager`](ue_ue.ThumbnailManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ThumbnailManager`](ue_ue.ThumbnailManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:63427](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63427)

___

### Load

▸ `Static` **Load**(`InName`): [`ThumbnailManager`](ue_ue.ThumbnailManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ThumbnailManager`](ue_ue.ThumbnailManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:63428](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63428)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:63426](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63426)
