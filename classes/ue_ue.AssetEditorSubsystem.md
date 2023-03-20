[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetEditorSubsystem

# Class: AssetEditorSubsystem

[ue/ue](../modules/ue_ue.md).AssetEditorSubsystem

## Hierarchy

- [`EditorSubsystem`](ue_ue.EditorSubsystem.md)

  ↳ **`AssetEditorSubsystem`**

## Table of contents

### Constructors

- [constructor](ue_ue.AssetEditorSubsystem.md#constructor)

### Properties

- [\_\_tid\_AssetEditorSubsystem\_\_](ue_ue.AssetEditorSubsystem.md#__tid_asseteditorsubsystem__)
- [\_\_tid\_DynamicSubsystem\_\_](ue_ue.AssetEditorSubsystem.md#__tid_dynamicsubsystem__)
- [\_\_tid\_EditorSubsystem\_\_](ue_ue.AssetEditorSubsystem.md#__tid_editorsubsystem__)
- [\_\_tid\_Object\_\_](ue_ue.AssetEditorSubsystem.md#__tid_object__)
- [\_\_tid\_Subsystem\_\_](ue_ue.AssetEditorSubsystem.md#__tid_subsystem__)

### Methods

- [CloseAllEditorsForAsset](ue_ue.AssetEditorSubsystem.md#closealleditorsforasset)
- [CreateDefaultSubobject](ue_ue.AssetEditorSubsystem.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AssetEditorSubsystem.md#executeubergraph)
- [GetClass](ue_ue.AssetEditorSubsystem.md#getclass)
- [GetName](ue_ue.AssetEditorSubsystem.md#getname)
- [GetOuter](ue_ue.AssetEditorSubsystem.md#getouter)
- [GetWorld](ue_ue.AssetEditorSubsystem.md#getworld)
- [OpenEditorForAssets](ue_ue.AssetEditorSubsystem.md#openeditorforassets)
- [Find](ue_ue.AssetEditorSubsystem.md#find)
- [Load](ue_ue.AssetEditorSubsystem.md#load)
- [StaticClass](ue_ue.AssetEditorSubsystem.md#staticclass)

## Constructors

### constructor

• **new AssetEditorSubsystem**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[constructor](ue_ue.EditorSubsystem.md#constructor)

## Properties

### \_\_tid\_AssetEditorSubsystem\_\_

• **\_\_tid\_AssetEditorSubsystem\_\_**: `boolean`

___

### \_\_tid\_DynamicSubsystem\_\_

• **\_\_tid\_DynamicSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_DynamicSubsystem__](ue_ue.EditorSubsystem.md#__tid_dynamicsubsystem__)

___

### \_\_tid\_EditorSubsystem\_\_

• **\_\_tid\_EditorSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_EditorSubsystem__](ue_ue.EditorSubsystem.md#__tid_editorsubsystem__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Object__](ue_ue.EditorSubsystem.md#__tid_object__)

___

### \_\_tid\_Subsystem\_\_

• **\_\_tid\_Subsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Subsystem__](ue_ue.EditorSubsystem.md#__tid_subsystem__)

## Methods

### CloseAllEditorsForAsset

▸ **CloseAllEditorsForAsset**(`Asset`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Asset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

___

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

[EditorSubsystem](ue_ue.EditorSubsystem.md).[CreateDefaultSubobject](ue_ue.EditorSubsystem.md#createdefaultsubobject)

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

[EditorSubsystem](ue_ue.EditorSubsystem.md).[ExecuteUbergraph](ue_ue.EditorSubsystem.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetClass](ue_ue.EditorSubsystem.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetName](ue_ue.EditorSubsystem.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetOuter](ue_ue.EditorSubsystem.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetWorld](ue_ue.EditorSubsystem.md#getworld)

___

### OpenEditorForAssets

▸ **OpenEditorForAssets**(`Assets`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Assets` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AssetEditorSubsystem`](ue_ue.AssetEditorSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AssetEditorSubsystem`](ue_ue.AssetEditorSubsystem.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[Find](ue_ue.EditorSubsystem.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AssetEditorSubsystem`](ue_ue.AssetEditorSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AssetEditorSubsystem`](ue_ue.AssetEditorSubsystem.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[Load](ue_ue.EditorSubsystem.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[StaticClass](ue_ue.EditorSubsystem.md#staticclass)
