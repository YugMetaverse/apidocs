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

#### Defined in

[ue/ue.d.ts:21586](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21586)

## Properties

### \_\_tid\_AssetEditorSubsystem\_\_

• **\_\_tid\_AssetEditorSubsystem\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21593](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21593)

___

### \_\_tid\_DynamicSubsystem\_\_

• **\_\_tid\_DynamicSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_DynamicSubsystem__](ue_ue.EditorSubsystem.md#__tid_dynamicsubsystem__)

#### Defined in

[ue/ue.d.ts:21573](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21573)

___

### \_\_tid\_EditorSubsystem\_\_

• **\_\_tid\_EditorSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_EditorSubsystem__](ue_ue.EditorSubsystem.md#__tid_editorsubsystem__)

#### Defined in

[ue/ue.d.ts:21582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21582)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Object__](ue_ue.EditorSubsystem.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_Subsystem\_\_

• **\_\_tid\_Subsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Subsystem__](ue_ue.EditorSubsystem.md#__tid_subsystem__)

#### Defined in

[ue/ue.d.ts:21564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21564)

## Methods

### CloseAllEditorsForAsset

▸ **CloseAllEditorsForAsset**(`Asset`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Asset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:21587](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21587)

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

[EditorSubsystem](ue_ue.EditorSubsystem.md).[ExecuteUbergraph](ue_ue.EditorSubsystem.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetClass](ue_ue.EditorSubsystem.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetName](ue_ue.EditorSubsystem.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetOuter](ue_ue.EditorSubsystem.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetWorld](ue_ue.EditorSubsystem.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### OpenEditorForAssets

▸ **OpenEditorForAssets**(`Assets`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Assets` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:21588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21588)

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

#### Defined in

[ue/ue.d.ts:21590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21590)

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

#### Defined in

[ue/ue.d.ts:21591](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21591)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[StaticClass](ue_ue.EditorSubsystem.md#staticclass)

#### Defined in

[ue/ue.d.ts:21589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21589)
