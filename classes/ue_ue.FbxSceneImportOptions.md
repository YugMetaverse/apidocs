[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FbxSceneImportOptions

# Class: FbxSceneImportOptions

[ue/ue](../modules/ue_ue.md).FbxSceneImportOptions

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`FbxSceneImportOptions`**

## Table of contents

### Constructors

- [constructor](ue_ue.FbxSceneImportOptions.md#constructor)

### Properties

- [HierarchyType](ue_ue.FbxSceneImportOptions.md#hierarchytype)
- [ImportRotation](ue_ue.FbxSceneImportOptions.md#importrotation)
- [ImportTranslation](ue_ue.FbxSceneImportOptions.md#importtranslation)
- [ImportUniformScale](ue_ue.FbxSceneImportOptions.md#importuniformscale)
- [\_\_tid\_FbxSceneImportOptions\_\_](ue_ue.FbxSceneImportOptions.md#__tid_fbxsceneimportoptions__)
- [\_\_tid\_Object\_\_](ue_ue.FbxSceneImportOptions.md#__tid_object__)
- [bBakePivotInVertex](ue_ue.FbxSceneImportOptions.md#bbakepivotinvertex)
- [bCreateContentFolderHierarchy](ue_ue.FbxSceneImportOptions.md#bcreatecontentfolderhierarchy)
- [bForceFrontXAxis](ue_ue.FbxSceneImportOptions.md#bforcefrontxaxis)
- [bImportAsDynamic](ue_ue.FbxSceneImportOptions.md#bimportasdynamic)
- [bImportSkeletalMeshLODs](ue_ue.FbxSceneImportOptions.md#bimportskeletalmeshlods)
- [bImportStaticMeshLODs](ue_ue.FbxSceneImportOptions.md#bimportstaticmeshlods)
- [bInvertNormalMaps](ue_ue.FbxSceneImportOptions.md#binvertnormalmaps)
- [bTransformVertexToAbsolute](ue_ue.FbxSceneImportOptions.md#btransformvertextoabsolute)

### Methods

- [CreateDefaultSubobject](ue_ue.FbxSceneImportOptions.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FbxSceneImportOptions.md#executeubergraph)
- [GetClass](ue_ue.FbxSceneImportOptions.md#getclass)
- [GetName](ue_ue.FbxSceneImportOptions.md#getname)
- [GetOuter](ue_ue.FbxSceneImportOptions.md#getouter)
- [GetWorld](ue_ue.FbxSceneImportOptions.md#getworld)
- [Find](ue_ue.FbxSceneImportOptions.md#find)
- [Load](ue_ue.FbxSceneImportOptions.md#load)
- [StaticClass](ue_ue.FbxSceneImportOptions.md#staticclass)

## Constructors

### constructor

• **new FbxSceneImportOptions**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:35352](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35352)

## Properties

### HierarchyType

• **HierarchyType**: [`EFBXSceneOptionsCreateHierarchyType`](../enums/ue_ue.EFBXSceneOptionsCreateHierarchyType.md)

#### Defined in

[ue/ue.d.ts:35355](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35355)

___

### ImportRotation

• **ImportRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:35358](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35358)

___

### ImportTranslation

• **ImportTranslation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:35357](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35357)

___

### ImportUniformScale

• **ImportUniformScale**: `number`

#### Defined in

[ue/ue.d.ts:35359](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35359)

___

### \_\_tid\_FbxSceneImportOptions\_\_

• **\_\_tid\_FbxSceneImportOptions\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:35369](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35369)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bBakePivotInVertex

• **bBakePivotInVertex**: `boolean`

#### Defined in

[ue/ue.d.ts:35361](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35361)

___

### bCreateContentFolderHierarchy

• **bCreateContentFolderHierarchy**: `boolean`

#### Defined in

[ue/ue.d.ts:35353](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35353)

___

### bForceFrontXAxis

• **bForceFrontXAxis**: `boolean`

#### Defined in

[ue/ue.d.ts:35356](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35356)

___

### bImportAsDynamic

• **bImportAsDynamic**: `boolean`

#### Defined in

[ue/ue.d.ts:35354](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35354)

___

### bImportSkeletalMeshLODs

• **bImportSkeletalMeshLODs**: `boolean`

#### Defined in

[ue/ue.d.ts:35363](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35363)

___

### bImportStaticMeshLODs

• **bImportStaticMeshLODs**: `boolean`

#### Defined in

[ue/ue.d.ts:35362](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35362)

___

### bInvertNormalMaps

• **bInvertNormalMaps**: `boolean`

#### Defined in

[ue/ue.d.ts:35364](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35364)

___

### bTransformVertexToAbsolute

• **bTransformVertexToAbsolute**: `boolean`

#### Defined in

[ue/ue.d.ts:35360](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35360)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FbxSceneImportOptions`](ue_ue.FbxSceneImportOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FbxSceneImportOptions`](ue_ue.FbxSceneImportOptions.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:35366](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35366)

___

### Load

▸ `Static` **Load**(`InName`): [`FbxSceneImportOptions`](ue_ue.FbxSceneImportOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FbxSceneImportOptions`](ue_ue.FbxSceneImportOptions.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:35367](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35367)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:35365](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35365)
