[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DeveloperSettings

# Class: DeveloperSettings

[ue/ue](../modules/ue_ue.md).DeveloperSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`DeveloperSettings`**

  ↳↳ [`AnimationSettings`](ue_ue.AnimationSettings.md)

  ↳↳ [`AssetManagerSettings`](ue_ue.AssetManagerSettings.md)

  ↳↳ [`AssetToolsSettings`](ue_ue.AssetToolsSettings.md)

  ↳↳ [`AudioSettings`](ue_ue.AudioSettings.md)

  ↳↳ [`BlueprintEditorProjectSettings`](ue_ue.BlueprintEditorProjectSettings.md)

  ↳↳ [`ChaosSolverSettings`](ue_ue.ChaosSolverSettings.md)

  ↳↳ [`CollisionProfile`](ue_ue.CollisionProfile.md)

  ↳↳ [`CookerSettings`](ue_ue.CookerSettings.md)

  ↳↳ [`DebugCameraControllerSettings`](ue_ue.DebugCameraControllerSettings.md)

  ↳↳ [`EditorKeyboardShortcutSettings`](ue_ue.EditorKeyboardShortcutSettings.md)

  ↳↳ [`EditorPerformanceSettings`](ue_ue.EditorPerformanceSettings.md)

  ↳↳ [`EditorProjectAppearanceSettings`](ue_ue.EditorProjectAppearanceSettings.md)

  ↳↳ [`GarbageCollectionSettings`](ue_ue.GarbageCollectionSettings.md)

  ↳↳ [`HierarchicalLODSettings`](ue_ue.HierarchicalLODSettings.md)

  ↳↳ [`LandscapeSettings`](ue_ue.LandscapeSettings.md)

  ↳↳ [`LevelEditor2DSettings`](ue_ue.LevelEditor2DSettings.md)

  ↳↳ [`LevelEditorMiscSettings`](ue_ue.LevelEditorMiscSettings.md)

  ↳↳ [`MeshSimplificationSettings`](ue_ue.MeshSimplificationSettings.md)

  ↳↳ [`NetworkSettings`](ue_ue.NetworkSettings.md)

  ↳↳ [`OnlinePIESettings`](ue_ue.OnlinePIESettings.md)

  ↳↳ [`PhysicsSettings`](ue_ue.PhysicsSettings.md)

  ↳↳ [`ProxyLODMeshSimplificationSettings`](ue_ue.ProxyLODMeshSimplificationSettings.md)

  ↳↳ [`RendererOverrideSettings`](ue_ue.RendererOverrideSettings.md)

  ↳↳ [`RendererSettings`](ue_ue.RendererSettings.md)

  ↳↳ [`SkeletalMeshSimplificationSettings`](ue_ue.SkeletalMeshSimplificationSettings.md)

  ↳↳ [`StreamingSettings`](ue_ue.StreamingSettings.md)

  ↳↳ [`TextureImportSettings`](ue_ue.TextureImportSettings.md)

  ↳↳ [`UMGEditorProjectSettings`](ue_ue.UMGEditorProjectSettings.md)

  ↳↳ [`UserInterfaceSettings`](ue_ue.UserInterfaceSettings.md)

  ↳↳ [`WidgetDesignerSettings`](ue_ue.WidgetDesignerSettings.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DeveloperSettings.md#constructor)

### Properties

- [\_\_tid\_DeveloperSettings\_\_](ue_ue.DeveloperSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.DeveloperSettings.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)
- [GetClass](ue_ue.DeveloperSettings.md#getclass)
- [GetName](ue_ue.DeveloperSettings.md#getname)
- [GetOuter](ue_ue.DeveloperSettings.md#getouter)
- [GetWorld](ue_ue.DeveloperSettings.md#getworld)
- [Find](ue_ue.DeveloperSettings.md#find)
- [Load](ue_ue.DeveloperSettings.md#load)
- [StaticClass](ue_ue.DeveloperSettings.md#staticclass)

## Constructors

### constructor

• **new DeveloperSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DeveloperSettings`](ue_ue.DeveloperSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DeveloperSettings`](ue_ue.DeveloperSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
