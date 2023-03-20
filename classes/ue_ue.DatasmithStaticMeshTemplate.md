[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithStaticMeshTemplate

# Class: DatasmithStaticMeshTemplate

[ue/ue](../modules/ue_ue.md).DatasmithStaticMeshTemplate

## Hierarchy

- [`DatasmithObjectTemplate`](ue_ue.DatasmithObjectTemplate.md)

  ↳ **`DatasmithStaticMeshTemplate`**

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithStaticMeshTemplate.md#constructor)

### Properties

- [BuildSettings](ue_ue.DatasmithStaticMeshTemplate.md#buildsettings)
- [LightMapCoordinateIndex](ue_ue.DatasmithStaticMeshTemplate.md#lightmapcoordinateindex)
- [LightMapResolution](ue_ue.DatasmithStaticMeshTemplate.md#lightmapresolution)
- [SectionInfoMap](ue_ue.DatasmithStaticMeshTemplate.md#sectioninfomap)
- [StaticMaterials](ue_ue.DatasmithStaticMeshTemplate.md#staticmaterials)
- [\_\_tid\_DatasmithObjectTemplate\_\_](ue_ue.DatasmithStaticMeshTemplate.md#__tid_datasmithobjecttemplate__)
- [\_\_tid\_DatasmithStaticMeshTemplate\_\_](ue_ue.DatasmithStaticMeshTemplate.md#__tid_datasmithstaticmeshtemplate__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithStaticMeshTemplate.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithStaticMeshTemplate.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithStaticMeshTemplate.md#executeubergraph)
- [GetClass](ue_ue.DatasmithStaticMeshTemplate.md#getclass)
- [GetName](ue_ue.DatasmithStaticMeshTemplate.md#getname)
- [GetOuter](ue_ue.DatasmithStaticMeshTemplate.md#getouter)
- [GetWorld](ue_ue.DatasmithStaticMeshTemplate.md#getworld)
- [Find](ue_ue.DatasmithStaticMeshTemplate.md#find)
- [Load](ue_ue.DatasmithStaticMeshTemplate.md#load)
- [StaticClass](ue_ue.DatasmithStaticMeshTemplate.md#staticclass)

## Constructors

### constructor

• **new DatasmithStaticMeshTemplate**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[constructor](ue_ue.DatasmithObjectTemplate.md#constructor)

#### Defined in

[ue/ue.d.ts:30131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30131)

## Properties

### BuildSettings

• **BuildSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DatasmithMeshBuildSettingsTemplate`](ue_ue.DatasmithMeshBuildSettingsTemplate.md)\>

#### Defined in

[ue/ue.d.ts:30135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30135)

___

### LightMapCoordinateIndex

• **LightMapCoordinateIndex**: `number`

#### Defined in

[ue/ue.d.ts:30133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30133)

___

### LightMapResolution

• **LightMapResolution**: `number`

#### Defined in

[ue/ue.d.ts:30134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30134)

___

### SectionInfoMap

• **SectionInfoMap**: [`DatasmithMeshSectionInfoMapTemplate`](ue_ue.DatasmithMeshSectionInfoMapTemplate.md)

#### Defined in

[ue/ue.d.ts:30132](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30132)

___

### StaticMaterials

• **StaticMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DatasmithStaticMaterialTemplate`](ue_ue.DatasmithStaticMaterialTemplate.md)\>

#### Defined in

[ue/ue.d.ts:30136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30136)

___

### \_\_tid\_DatasmithObjectTemplate\_\_

• **\_\_tid\_DatasmithObjectTemplate\_\_**: `boolean`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[__tid_DatasmithObjectTemplate__](ue_ue.DatasmithObjectTemplate.md#__tid_datasmithobjecttemplate__)

#### Defined in

[ue/ue.d.ts:29319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29319)

___

### \_\_tid\_DatasmithStaticMeshTemplate\_\_

• **\_\_tid\_DatasmithStaticMeshTemplate\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:30141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30141)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[__tid_Object__](ue_ue.DatasmithObjectTemplate.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[CreateDefaultSubobject](ue_ue.DatasmithObjectTemplate.md#createdefaultsubobject)

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

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[ExecuteUbergraph](ue_ue.DatasmithObjectTemplate.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetClass](ue_ue.DatasmithObjectTemplate.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetName](ue_ue.DatasmithObjectTemplate.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetOuter](ue_ue.DatasmithObjectTemplate.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetWorld](ue_ue.DatasmithObjectTemplate.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithStaticMeshTemplate`](ue_ue.DatasmithStaticMeshTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithStaticMeshTemplate`](ue_ue.DatasmithStaticMeshTemplate.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[Find](ue_ue.DatasmithObjectTemplate.md#find)

#### Defined in

[ue/ue.d.ts:30138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30138)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithStaticMeshTemplate`](ue_ue.DatasmithStaticMeshTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithStaticMeshTemplate`](ue_ue.DatasmithStaticMeshTemplate.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[Load](ue_ue.DatasmithObjectTemplate.md#load)

#### Defined in

[ue/ue.d.ts:30139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30139)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[StaticClass](ue_ue.DatasmithObjectTemplate.md#staticclass)

#### Defined in

[ue/ue.d.ts:30137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30137)
