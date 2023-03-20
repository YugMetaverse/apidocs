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

## Properties

### AmbientCubemap

• **AmbientCubemap**: [`TextureCube`](ue_ue.TextureCube.md)

___

### CheckerboardTexture

• **CheckerboardTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### EditorCube

• **EditorCube**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### EditorCylinder

• **EditorCylinder**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### EditorPlane

• **EditorPlane**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### EditorSkySphere

• **EditorSkySphere**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### EditorSphere

• **EditorSphere**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### FloorPlaneMaterial

• **FloorPlaneMaterial**: [`Material`](ue_ue.Material.md)

___

### NotSupported

• **NotSupported**: [`ThumbnailRenderingInfo`](ue_ue.ThumbnailRenderingInfo.md)

___

### RenderableThumbnailTypes

• **RenderableThumbnailTypes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ThumbnailRenderingInfo`](ue_ue.ThumbnailRenderingInfo.md)\>

___

### ThumbnailManagerClassName

• **ThumbnailManagerClassName**: `string`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_ThumbnailManager\_\_

• **\_\_tid\_ThumbnailManager\_\_**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
