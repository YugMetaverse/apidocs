[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FoliageStatistics

# Class: FoliageStatistics

[ue/ue](../modules/ue_ue.md).FoliageStatistics

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`FoliageStatistics`**

## Table of contents

### Constructors

- [constructor](ue_ue.FoliageStatistics.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.FoliageStatistics.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_FoliageStatistics\_\_](ue_ue.FoliageStatistics.md#__tid_foliagestatistics__)
- [\_\_tid\_Object\_\_](ue_ue.FoliageStatistics.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.FoliageStatistics.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FoliageStatistics.md#executeubergraph)
- [GetClass](ue_ue.FoliageStatistics.md#getclass)
- [GetName](ue_ue.FoliageStatistics.md#getname)
- [GetOuter](ue_ue.FoliageStatistics.md#getouter)
- [GetWorld](ue_ue.FoliageStatistics.md#getworld)
- [Find](ue_ue.FoliageStatistics.md#find)
- [FoliageOverlappingBoxCount](ue_ue.FoliageStatistics.md#foliageoverlappingboxcount)
- [FoliageOverlappingSphereCount](ue_ue.FoliageStatistics.md#foliageoverlappingspherecount)
- [Load](ue_ue.FoliageStatistics.md#load)
- [StaticClass](ue_ue.FoliageStatistics.md#staticclass)

## Constructors

### constructor

• **new FoliageStatistics**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_FoliageStatistics\_\_

• **\_\_tid\_FoliageStatistics\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FoliageStatistics`](ue_ue.FoliageStatistics.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FoliageStatistics`](ue_ue.FoliageStatistics.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### FoliageOverlappingBoxCount

▸ `Static` **FoliageOverlappingBoxCount**(`WorldContextObject`, `StaticMesh`, `Box`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `StaticMesh` | [`$Nullable`](../modules/puerts.md#$nullable)<[`StaticMesh`](ue_ue.StaticMesh.md)\> |
| `Box` | [`Box`](ue_ue.Box.md) |

#### Returns

`number`

___

### FoliageOverlappingSphereCount

▸ `Static` **FoliageOverlappingSphereCount**(`WorldContextObject`, `StaticMesh`, `CenterPosition`, `Radius`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `StaticMesh` | [`$Nullable`](../modules/puerts.md#$nullable)<[`StaticMesh`](ue_ue.StaticMesh.md)\> |
| `CenterPosition` | [`Vector`](ue_ue_s.Vector.md) |
| `Radius` | `number` |

#### Returns

`number`

___

### Load

▸ `Static` **Load**(`InName`): [`FoliageStatistics`](ue_ue.FoliageStatistics.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FoliageStatistics`](ue_ue.FoliageStatistics.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
