[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CurveBase

# Class: CurveBase

[ue/ue](../modules/ue_ue.md).CurveBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`CurveBase`**

  ↳↳ [`CurveLinearColor`](ue_ue.CurveLinearColor.md)

  ↳↳ [`CurveFloat`](ue_ue.CurveFloat.md)

  ↳↳ [`CurveVector`](ue_ue.CurveVector.md)

## Table of contents

### Constructors

- [constructor](ue_ue.CurveBase.md#constructor)

### Properties

- [AssetImportData](ue_ue.CurveBase.md#assetimportdata)
- [ImportPath](ue_ue.CurveBase.md#importpath)
- [\_\_tid\_CurveBase\_\_](ue_ue.CurveBase.md#__tid_curvebase__)
- [\_\_tid\_Object\_\_](ue_ue.CurveBase.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.CurveBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CurveBase.md#executeubergraph)
- [GetClass](ue_ue.CurveBase.md#getclass)
- [GetName](ue_ue.CurveBase.md#getname)
- [GetOuter](ue_ue.CurveBase.md#getouter)
- [GetTimeRange](ue_ue.CurveBase.md#gettimerange)
- [GetValueRange](ue_ue.CurveBase.md#getvaluerange)
- [GetWorld](ue_ue.CurveBase.md#getworld)
- [Find](ue_ue.CurveBase.md#find)
- [Load](ue_ue.CurveBase.md#load)
- [StaticClass](ue_ue.CurveBase.md#staticclass)

## Constructors

### constructor

• **new CurveBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

___

### ImportPath

• **ImportPath**: `string`

___

### \_\_tid\_CurveBase\_\_

• **\_\_tid\_CurveBase\_\_**: `boolean`

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

### GetTimeRange

▸ **GetTimeRange**(`MinTime`, `MaxTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MinTime` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `MaxTime` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### GetValueRange

▸ **GetValueRange**(`MinValue`, `MaxValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MinValue` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `MaxValue` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CurveBase`](ue_ue.CurveBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CurveBase`](ue_ue.CurveBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CurveBase`](ue_ue.CurveBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CurveBase`](ue_ue.CurveBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
