[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithImportOptions

# Class: DatasmithImportOptions

[ue/ue](../modules/ue_ue.md).DatasmithImportOptions

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`DatasmithImportOptions`**

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithImportOptions.md#constructor)

### Properties

- [BaseOptions](ue_ue.DatasmithImportOptions.md#baseoptions)
- [CameraImportPolicy](ue_ue.DatasmithImportOptions.md#cameraimportpolicy)
- [FileName](ue_ue.DatasmithImportOptions.md#filename)
- [FilePath](ue_ue.DatasmithImportOptions.md#filepath)
- [LightImportPolicy](ue_ue.DatasmithImportOptions.md#lightimportpolicy)
- [MaterialConflictPolicy](ue_ue.DatasmithImportOptions.md#materialconflictpolicy)
- [MaterialQuality](ue_ue.DatasmithImportOptions.md#materialquality)
- [OtherActorImportPolicy](ue_ue.DatasmithImportOptions.md#otheractorimportpolicy)
- [ReimportOptions](ue_ue.DatasmithImportOptions.md#reimportoptions)
- [SearchPackagePolicy](ue_ue.DatasmithImportOptions.md#searchpackagepolicy)
- [StaticMeshActorImportPolicy](ue_ue.DatasmithImportOptions.md#staticmeshactorimportpolicy)
- [TextureConflictPolicy](ue_ue.DatasmithImportOptions.md#textureconflictpolicy)
- [\_\_tid\_DatasmithImportOptions\_\_](ue_ue.DatasmithImportOptions.md#__tid_datasmithimportoptions__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithImportOptions.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithImportOptions.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithImportOptions.md#executeubergraph)
- [GetClass](ue_ue.DatasmithImportOptions.md#getclass)
- [GetName](ue_ue.DatasmithImportOptions.md#getname)
- [GetOuter](ue_ue.DatasmithImportOptions.md#getouter)
- [GetWorld](ue_ue.DatasmithImportOptions.md#getworld)
- [Find](ue_ue.DatasmithImportOptions.md#find)
- [Load](ue_ue.DatasmithImportOptions.md#load)
- [StaticClass](ue_ue.DatasmithImportOptions.md#staticclass)

## Constructors

### constructor

• **new DatasmithImportOptions**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### BaseOptions

• **BaseOptions**: [`DatasmithImportBaseOptions`](ue_ue.DatasmithImportBaseOptions.md)

___

### CameraImportPolicy

• **CameraImportPolicy**: [`EDatasmithImportActorPolicy`](../enums/ue_ue.EDatasmithImportActorPolicy.md)

___

### FileName

• **FileName**: `string`

___

### FilePath

• **FilePath**: `string`

___

### LightImportPolicy

• **LightImportPolicy**: [`EDatasmithImportActorPolicy`](../enums/ue_ue.EDatasmithImportActorPolicy.md)

___

### MaterialConflictPolicy

• **MaterialConflictPolicy**: [`EDatasmithImportAssetConflictPolicy`](../enums/ue_ue.EDatasmithImportAssetConflictPolicy.md)

___

### MaterialQuality

• **MaterialQuality**: [`EDatasmithImportMaterialQuality`](../enums/ue_ue.EDatasmithImportMaterialQuality.md)

___

### OtherActorImportPolicy

• **OtherActorImportPolicy**: [`EDatasmithImportActorPolicy`](../enums/ue_ue.EDatasmithImportActorPolicy.md)

___

### ReimportOptions

• **ReimportOptions**: [`DatasmithReimportOptions`](ue_ue.DatasmithReimportOptions.md)

___

### SearchPackagePolicy

• **SearchPackagePolicy**: [`EDatasmithImportSearchPackagePolicy`](../enums/ue_ue.EDatasmithImportSearchPackagePolicy.md)

___

### StaticMeshActorImportPolicy

• **StaticMeshActorImportPolicy**: [`EDatasmithImportActorPolicy`](../enums/ue_ue.EDatasmithImportActorPolicy.md)

___

### TextureConflictPolicy

• **TextureConflictPolicy**: [`EDatasmithImportAssetConflictPolicy`](../enums/ue_ue.EDatasmithImportAssetConflictPolicy.md)

___

### \_\_tid\_DatasmithImportOptions\_\_

• **\_\_tid\_DatasmithImportOptions\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithImportOptions`](ue_ue.DatasmithImportOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithImportOptions`](ue_ue.DatasmithImportOptions.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithImportOptions`](ue_ue.DatasmithImportOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithImportOptions`](ue_ue.DatasmithImportOptions.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
