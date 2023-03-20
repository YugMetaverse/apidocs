[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CurveFloat

# Class: CurveFloat

[ue/ue](../modules/ue_ue.md).CurveFloat

## Hierarchy

- [`CurveBase`](ue_ue.CurveBase.md)

  ↳ **`CurveFloat`**

## Table of contents

### Constructors

- [constructor](ue_ue.CurveFloat.md#constructor)

### Properties

- [AssetImportData](ue_ue.CurveFloat.md#assetimportdata)
- [FloatCurve](ue_ue.CurveFloat.md#floatcurve)
- [ImportPath](ue_ue.CurveFloat.md#importpath)
- [\_\_tid\_CurveBase\_\_](ue_ue.CurveFloat.md#__tid_curvebase__)
- [\_\_tid\_CurveFloat\_\_](ue_ue.CurveFloat.md#__tid_curvefloat__)
- [\_\_tid\_Object\_\_](ue_ue.CurveFloat.md#__tid_object__)
- [bIsEventCurve](ue_ue.CurveFloat.md#biseventcurve)

### Methods

- [CreateDefaultSubobject](ue_ue.CurveFloat.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CurveFloat.md#executeubergraph)
- [GetClass](ue_ue.CurveFloat.md#getclass)
- [GetFloatValue](ue_ue.CurveFloat.md#getfloatvalue)
- [GetName](ue_ue.CurveFloat.md#getname)
- [GetOuter](ue_ue.CurveFloat.md#getouter)
- [GetTimeRange](ue_ue.CurveFloat.md#gettimerange)
- [GetValueRange](ue_ue.CurveFloat.md#getvaluerange)
- [GetWorld](ue_ue.CurveFloat.md#getworld)
- [Find](ue_ue.CurveFloat.md#find)
- [Load](ue_ue.CurveFloat.md#load)
- [StaticClass](ue_ue.CurveFloat.md#staticclass)

## Constructors

### constructor

• **new CurveFloat**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[CurveBase](ue_ue.CurveBase.md).[constructor](ue_ue.CurveBase.md#constructor)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[AssetImportData](ue_ue.CurveBase.md#assetimportdata)

___

### FloatCurve

• **FloatCurve**: [`RichCurve`](ue_ue.RichCurve.md)

___

### ImportPath

• **ImportPath**: `string`

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[ImportPath](ue_ue.CurveBase.md#importpath)

___

### \_\_tid\_CurveBase\_\_

• **\_\_tid\_CurveBase\_\_**: `boolean`

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[__tid_CurveBase__](ue_ue.CurveBase.md#__tid_curvebase__)

___

### \_\_tid\_CurveFloat\_\_

• **\_\_tid\_CurveFloat\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[__tid_Object__](ue_ue.CurveBase.md#__tid_object__)

___

### bIsEventCurve

• **bIsEventCurve**: `boolean`

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

[CurveBase](ue_ue.CurveBase.md).[CreateDefaultSubobject](ue_ue.CurveBase.md#createdefaultsubobject)

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

[CurveBase](ue_ue.CurveBase.md).[ExecuteUbergraph](ue_ue.CurveBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[GetClass](ue_ue.CurveBase.md#getclass)

___

### GetFloatValue

▸ **GetFloatValue**(`InTime`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTime` | `number` |

#### Returns

`number`

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[GetName](ue_ue.CurveBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[GetOuter](ue_ue.CurveBase.md#getouter)

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

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[GetTimeRange](ue_ue.CurveBase.md#gettimerange)

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

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[GetValueRange](ue_ue.CurveBase.md#getvaluerange)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[GetWorld](ue_ue.CurveBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CurveFloat`](ue_ue.CurveFloat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CurveFloat`](ue_ue.CurveFloat.md)

#### Overrides

[CurveBase](ue_ue.CurveBase.md).[Find](ue_ue.CurveBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CurveFloat`](ue_ue.CurveFloat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CurveFloat`](ue_ue.CurveFloat.md)

#### Overrides

[CurveBase](ue_ue.CurveBase.md).[Load](ue_ue.CurveBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[CurveBase](ue_ue.CurveBase.md).[StaticClass](ue_ue.CurveBase.md#staticclass)
