[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CompositeCurveTable

# Class: CompositeCurveTable

[ue/ue](../modules/ue_ue.md).CompositeCurveTable

## Hierarchy

- [`CurveTable`](ue_ue.CurveTable.md)

  ↳ **`CompositeCurveTable`**

## Table of contents

### Constructors

- [constructor](ue_ue.CompositeCurveTable.md#constructor)

### Properties

- [AssetImportData](ue_ue.CompositeCurveTable.md#assetimportdata)
- [ImportPath](ue_ue.CompositeCurveTable.md#importpath)
- [OldParentTables](ue_ue.CompositeCurveTable.md#oldparenttables)
- [ParentTables](ue_ue.CompositeCurveTable.md#parenttables)
- [\_\_tid\_CompositeCurveTable\_\_](ue_ue.CompositeCurveTable.md#__tid_compositecurvetable__)
- [\_\_tid\_CurveTable\_\_](ue_ue.CompositeCurveTable.md#__tid_curvetable__)
- [\_\_tid\_Object\_\_](ue_ue.CompositeCurveTable.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.CompositeCurveTable.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CompositeCurveTable.md#executeubergraph)
- [GetClass](ue_ue.CompositeCurveTable.md#getclass)
- [GetName](ue_ue.CompositeCurveTable.md#getname)
- [GetOuter](ue_ue.CompositeCurveTable.md#getouter)
- [GetWorld](ue_ue.CompositeCurveTable.md#getworld)
- [Find](ue_ue.CompositeCurveTable.md#find)
- [Load](ue_ue.CompositeCurveTable.md#load)
- [StaticClass](ue_ue.CompositeCurveTable.md#staticclass)

## Constructors

### constructor

• **new CompositeCurveTable**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[CurveTable](ue_ue.CurveTable.md).[constructor](ue_ue.CurveTable.md#constructor)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[CurveTable](ue_ue.CurveTable.md).[AssetImportData](ue_ue.CurveTable.md#assetimportdata)

___

### ImportPath

• **ImportPath**: `string`

#### Inherited from

[CurveTable](ue_ue.CurveTable.md).[ImportPath](ue_ue.CurveTable.md#importpath)

___

### OldParentTables

• **OldParentTables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CurveTable`](ue_ue.CurveTable.md)\>

___

### ParentTables

• **ParentTables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CurveTable`](ue_ue.CurveTable.md)\>

___

### \_\_tid\_CompositeCurveTable\_\_

• **\_\_tid\_CompositeCurveTable\_\_**: `boolean`

___

### \_\_tid\_CurveTable\_\_

• **\_\_tid\_CurveTable\_\_**: `boolean`

#### Inherited from

[CurveTable](ue_ue.CurveTable.md).[__tid_CurveTable__](ue_ue.CurveTable.md#__tid_curvetable__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[CurveTable](ue_ue.CurveTable.md).[__tid_Object__](ue_ue.CurveTable.md#__tid_object__)

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

[CurveTable](ue_ue.CurveTable.md).[CreateDefaultSubobject](ue_ue.CurveTable.md#createdefaultsubobject)

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

[CurveTable](ue_ue.CurveTable.md).[ExecuteUbergraph](ue_ue.CurveTable.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[CurveTable](ue_ue.CurveTable.md).[GetClass](ue_ue.CurveTable.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[CurveTable](ue_ue.CurveTable.md).[GetName](ue_ue.CurveTable.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[CurveTable](ue_ue.CurveTable.md).[GetOuter](ue_ue.CurveTable.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[CurveTable](ue_ue.CurveTable.md).[GetWorld](ue_ue.CurveTable.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CompositeCurveTable`](ue_ue.CompositeCurveTable.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CompositeCurveTable`](ue_ue.CompositeCurveTable.md)

#### Overrides

[CurveTable](ue_ue.CurveTable.md).[Find](ue_ue.CurveTable.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CompositeCurveTable`](ue_ue.CompositeCurveTable.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CompositeCurveTable`](ue_ue.CompositeCurveTable.md)

#### Overrides

[CurveTable](ue_ue.CurveTable.md).[Load](ue_ue.CurveTable.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[CurveTable](ue_ue.CurveTable.md).[StaticClass](ue_ue.CurveTable.md#staticclass)
