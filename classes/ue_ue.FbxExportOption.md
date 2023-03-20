[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FbxExportOption

# Class: FbxExportOption

[ue/ue](../modules/ue_ue.md).FbxExportOption

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`FbxExportOption`**

## Table of contents

### Constructors

- [constructor](ue_ue.FbxExportOption.md#constructor)

### Properties

- [Collision](ue_ue.FbxExportOption.md#collision)
- [FbxExportCompatibility](ue_ue.FbxExportOption.md#fbxexportcompatibility)
- [LevelOfDetail](ue_ue.FbxExportOption.md#levelofdetail)
- [MapSkeletalMotionToRoot](ue_ue.FbxExportOption.md#mapskeletalmotiontoroot)
- [VertexColor](ue_ue.FbxExportOption.md#vertexcolor)
- [\_\_tid\_FbxExportOption\_\_](ue_ue.FbxExportOption.md#__tid_fbxexportoption__)
- [\_\_tid\_Object\_\_](ue_ue.FbxExportOption.md#__tid_object__)
- [bASCII](ue_ue.FbxExportOption.md#bascii)
- [bExportLocalTime](ue_ue.FbxExportOption.md#bexportlocaltime)
- [bExportMorphTargets](ue_ue.FbxExportOption.md#bexportmorphtargets)
- [bExportPreviewMesh](ue_ue.FbxExportOption.md#bexportpreviewmesh)
- [bForceFrontXAxis](ue_ue.FbxExportOption.md#bforcefrontxaxis)

### Methods

- [CreateDefaultSubobject](ue_ue.FbxExportOption.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FbxExportOption.md#executeubergraph)
- [GetClass](ue_ue.FbxExportOption.md#getclass)
- [GetName](ue_ue.FbxExportOption.md#getname)
- [GetOuter](ue_ue.FbxExportOption.md#getouter)
- [GetWorld](ue_ue.FbxExportOption.md#getworld)
- [Find](ue_ue.FbxExportOption.md#find)
- [Load](ue_ue.FbxExportOption.md#load)
- [StaticClass](ue_ue.FbxExportOption.md#staticclass)

## Constructors

### constructor

• **new FbxExportOption**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Collision

• **Collision**: `boolean`

___

### FbxExportCompatibility

• **FbxExportCompatibility**: [`EFbxExportCompatibility`](../enums/ue_ue.EFbxExportCompatibility.md)

___

### LevelOfDetail

• **LevelOfDetail**: `boolean`

___

### MapSkeletalMotionToRoot

• **MapSkeletalMotionToRoot**: `boolean`

___

### VertexColor

• **VertexColor**: `boolean`

___

### \_\_tid\_FbxExportOption\_\_

• **\_\_tid\_FbxExportOption\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bASCII

• **bASCII**: `boolean`

___

### bExportLocalTime

• **bExportLocalTime**: `boolean`

___

### bExportMorphTargets

• **bExportMorphTargets**: `boolean`

___

### bExportPreviewMesh

• **bExportPreviewMesh**: `boolean`

___

### bForceFrontXAxis

• **bForceFrontXAxis**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FbxExportOption`](ue_ue.FbxExportOption.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FbxExportOption`](ue_ue.FbxExportOption.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FbxExportOption`](ue_ue.FbxExportOption.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FbxExportOption`](ue_ue.FbxExportOption.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
