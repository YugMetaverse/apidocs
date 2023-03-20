[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VectorFieldStatic

# Class: VectorFieldStatic

[ue/ue](../modules/ue_ue.md).VectorFieldStatic

## Hierarchy

- [`VectorField`](ue_ue.VectorField.md)

  ↳ **`VectorFieldStatic`**

## Table of contents

### Constructors

- [constructor](ue_ue.VectorFieldStatic.md#constructor)

### Properties

- [AssetImportData](ue_ue.VectorFieldStatic.md#assetimportdata)
- [Bounds](ue_ue.VectorFieldStatic.md#bounds)
- [CPUData](ue_ue.VectorFieldStatic.md#cpudata)
- [Intensity](ue_ue.VectorFieldStatic.md#intensity)
- [SizeX](ue_ue.VectorFieldStatic.md#sizex)
- [SizeY](ue_ue.VectorFieldStatic.md#sizey)
- [SizeZ](ue_ue.VectorFieldStatic.md#sizez)
- [SourceFilePath](ue_ue.VectorFieldStatic.md#sourcefilepath)
- [\_\_tid\_Object\_\_](ue_ue.VectorFieldStatic.md#__tid_object__)
- [\_\_tid\_VectorFieldStatic\_\_](ue_ue.VectorFieldStatic.md#__tid_vectorfieldstatic__)
- [\_\_tid\_VectorField\_\_](ue_ue.VectorFieldStatic.md#__tid_vectorfield__)
- [bAllowCPUAccess](ue_ue.VectorFieldStatic.md#ballowcpuaccess)

### Methods

- [CreateDefaultSubobject](ue_ue.VectorFieldStatic.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VectorFieldStatic.md#executeubergraph)
- [GetClass](ue_ue.VectorFieldStatic.md#getclass)
- [GetName](ue_ue.VectorFieldStatic.md#getname)
- [GetOuter](ue_ue.VectorFieldStatic.md#getouter)
- [GetWorld](ue_ue.VectorFieldStatic.md#getworld)
- [Find](ue_ue.VectorFieldStatic.md#find)
- [Load](ue_ue.VectorFieldStatic.md#load)
- [StaticClass](ue_ue.VectorFieldStatic.md#staticclass)

## Constructors

### constructor

• **new VectorFieldStatic**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[VectorField](ue_ue.VectorField.md).[constructor](ue_ue.VectorField.md#constructor)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

___

### Bounds

• **Bounds**: [`Box`](ue_ue.Box.md)

#### Inherited from

[VectorField](ue_ue.VectorField.md).[Bounds](ue_ue.VectorField.md#bounds)

___

### CPUData

• **CPUData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector4`](ue_ue_s.Vector4.md)\>

___

### Intensity

• **Intensity**: `number`

#### Inherited from

[VectorField](ue_ue.VectorField.md).[Intensity](ue_ue.VectorField.md#intensity)

___

### SizeX

• **SizeX**: `number`

___

### SizeY

• **SizeY**: `number`

___

### SizeZ

• **SizeZ**: `number`

___

### SourceFilePath

• **SourceFilePath**: `string`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[VectorField](ue_ue.VectorField.md).[__tid_Object__](ue_ue.VectorField.md#__tid_object__)

___

### \_\_tid\_VectorFieldStatic\_\_

• **\_\_tid\_VectorFieldStatic\_\_**: `boolean`

___

### \_\_tid\_VectorField\_\_

• **\_\_tid\_VectorField\_\_**: `boolean`

#### Inherited from

[VectorField](ue_ue.VectorField.md).[__tid_VectorField__](ue_ue.VectorField.md#__tid_vectorfield__)

___

### bAllowCPUAccess

• **bAllowCPUAccess**: `boolean`

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

[VectorField](ue_ue.VectorField.md).[CreateDefaultSubobject](ue_ue.VectorField.md#createdefaultsubobject)

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

[VectorField](ue_ue.VectorField.md).[ExecuteUbergraph](ue_ue.VectorField.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[VectorField](ue_ue.VectorField.md).[GetClass](ue_ue.VectorField.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[VectorField](ue_ue.VectorField.md).[GetName](ue_ue.VectorField.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[VectorField](ue_ue.VectorField.md).[GetOuter](ue_ue.VectorField.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[VectorField](ue_ue.VectorField.md).[GetWorld](ue_ue.VectorField.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VectorFieldStatic`](ue_ue.VectorFieldStatic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VectorFieldStatic`](ue_ue.VectorFieldStatic.md)

#### Overrides

[VectorField](ue_ue.VectorField.md).[Find](ue_ue.VectorField.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`VectorFieldStatic`](ue_ue.VectorFieldStatic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VectorFieldStatic`](ue_ue.VectorFieldStatic.md)

#### Overrides

[VectorField](ue_ue.VectorField.md).[Load](ue_ue.VectorField.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[VectorField](ue_ue.VectorField.md).[StaticClass](ue_ue.VectorField.md#staticclass)
