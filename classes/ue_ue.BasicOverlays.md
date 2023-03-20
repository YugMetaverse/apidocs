[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BasicOverlays

# Class: BasicOverlays

[ue/ue](../modules/ue_ue.md).BasicOverlays

## Hierarchy

- [`Overlays`](ue_ue.Overlays.md)

  ↳ **`BasicOverlays`**

## Table of contents

### Constructors

- [constructor](ue_ue.BasicOverlays.md#constructor)

### Properties

- [AssetImportData](ue_ue.BasicOverlays.md#assetimportdata)
- [Overlays](ue_ue.BasicOverlays.md#overlays)
- [\_\_tid\_BasicOverlays\_\_](ue_ue.BasicOverlays.md#__tid_basicoverlays__)
- [\_\_tid\_Object\_\_](ue_ue.BasicOverlays.md#__tid_object__)
- [\_\_tid\_Overlays\_\_](ue_ue.BasicOverlays.md#__tid_overlays__)

### Methods

- [CreateDefaultSubobject](ue_ue.BasicOverlays.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BasicOverlays.md#executeubergraph)
- [GetClass](ue_ue.BasicOverlays.md#getclass)
- [GetName](ue_ue.BasicOverlays.md#getname)
- [GetOuter](ue_ue.BasicOverlays.md#getouter)
- [GetWorld](ue_ue.BasicOverlays.md#getworld)
- [Find](ue_ue.BasicOverlays.md#find)
- [Load](ue_ue.BasicOverlays.md#load)
- [StaticClass](ue_ue.BasicOverlays.md#staticclass)

## Constructors

### constructor

• **new BasicOverlays**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Overlays](ue_ue.Overlays.md).[constructor](ue_ue.Overlays.md#constructor)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

___

### Overlays

• **Overlays**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`OverlayItem`](ue_ue.OverlayItem.md)\>

___

### \_\_tid\_BasicOverlays\_\_

• **\_\_tid\_BasicOverlays\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Overlays](ue_ue.Overlays.md).[__tid_Object__](ue_ue.Overlays.md#__tid_object__)

___

### \_\_tid\_Overlays\_\_

• **\_\_tid\_Overlays\_\_**: `boolean`

#### Inherited from

[Overlays](ue_ue.Overlays.md).[__tid_Overlays__](ue_ue.Overlays.md#__tid_overlays__)

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

[Overlays](ue_ue.Overlays.md).[CreateDefaultSubobject](ue_ue.Overlays.md#createdefaultsubobject)

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

[Overlays](ue_ue.Overlays.md).[ExecuteUbergraph](ue_ue.Overlays.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Overlays](ue_ue.Overlays.md).[GetClass](ue_ue.Overlays.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Overlays](ue_ue.Overlays.md).[GetName](ue_ue.Overlays.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Overlays](ue_ue.Overlays.md).[GetOuter](ue_ue.Overlays.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Overlays](ue_ue.Overlays.md).[GetWorld](ue_ue.Overlays.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BasicOverlays`](ue_ue.BasicOverlays.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BasicOverlays`](ue_ue.BasicOverlays.md)

#### Overrides

[Overlays](ue_ue.Overlays.md).[Find](ue_ue.Overlays.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BasicOverlays`](ue_ue.BasicOverlays.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BasicOverlays`](ue_ue.BasicOverlays.md)

#### Overrides

[Overlays](ue_ue.Overlays.md).[Load](ue_ue.Overlays.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Overlays](ue_ue.Overlays.md).[StaticClass](ue_ue.Overlays.md#staticclass)
