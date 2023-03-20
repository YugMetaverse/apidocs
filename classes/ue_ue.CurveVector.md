[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CurveVector

# Class: CurveVector

[ue/ue](../modules/ue_ue.md).CurveVector

## Hierarchy

- [`CurveBase`](ue_ue.CurveBase.md)

  ↳ **`CurveVector`**

## Table of contents

### Constructors

- [constructor](ue_ue.CurveVector.md#constructor)

### Properties

- [AssetImportData](ue_ue.CurveVector.md#assetimportdata)
- [FloatCurves](ue_ue.CurveVector.md#floatcurves)
- [ImportPath](ue_ue.CurveVector.md#importpath)
- [\_\_tid\_CurveBase\_\_](ue_ue.CurveVector.md#__tid_curvebase__)
- [\_\_tid\_CurveVector\_\_](ue_ue.CurveVector.md#__tid_curvevector__)
- [\_\_tid\_Object\_\_](ue_ue.CurveVector.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.CurveVector.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CurveVector.md#executeubergraph)
- [GetClass](ue_ue.CurveVector.md#getclass)
- [GetName](ue_ue.CurveVector.md#getname)
- [GetOuter](ue_ue.CurveVector.md#getouter)
- [GetTimeRange](ue_ue.CurveVector.md#gettimerange)
- [GetValueRange](ue_ue.CurveVector.md#getvaluerange)
- [GetVectorValue](ue_ue.CurveVector.md#getvectorvalue)
- [GetWorld](ue_ue.CurveVector.md#getworld)
- [Find](ue_ue.CurveVector.md#find)
- [Load](ue_ue.CurveVector.md#load)
- [StaticClass](ue_ue.CurveVector.md#staticclass)

## Constructors

### constructor

• **new CurveVector**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[CurveBase](ue_ue.CurveBase.md).[constructor](ue_ue.CurveBase.md#constructor)

#### Defined in

[ue/ue.d.ts:4246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4246)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[AssetImportData](ue_ue.CurveBase.md#assetimportdata)

#### Defined in

[ue/ue.d.ts:1584](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1584)

___

### FloatCurves

• **FloatCurves**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`RichCurve`](ue_ue.RichCurve.md)\>

#### Defined in

[ue/ue.d.ts:4247](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4247)

___

### ImportPath

• **ImportPath**: `string`

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[ImportPath](ue_ue.CurveBase.md#importpath)

#### Defined in

[ue/ue.d.ts:1585](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1585)

___

### \_\_tid\_CurveBase\_\_

• **\_\_tid\_CurveBase\_\_**: `boolean`

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[__tid_CurveBase__](ue_ue.CurveBase.md#__tid_curvebase__)

#### Defined in

[ue/ue.d.ts:1592](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1592)

___

### \_\_tid\_CurveVector\_\_

• **\_\_tid\_CurveVector\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:4253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4253)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[__tid_Object__](ue_ue.CurveBase.md#__tid_object__)

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

[CurveBase](ue_ue.CurveBase.md).[CreateDefaultSubobject](ue_ue.CurveBase.md#createdefaultsubobject)

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

[CurveBase](ue_ue.CurveBase.md).[ExecuteUbergraph](ue_ue.CurveBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[GetClass](ue_ue.CurveBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[GetName](ue_ue.CurveBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[GetOuter](ue_ue.CurveBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

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

#### Defined in

[ue/ue.d.ts:1586](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1586)

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

#### Defined in

[ue/ue.d.ts:1587](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1587)

___

### GetVectorValue

▸ **GetVectorValue**(`InTime`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTime` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:4248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4248)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[CurveBase](ue_ue.CurveBase.md).[GetWorld](ue_ue.CurveBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CurveVector`](ue_ue.CurveVector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CurveVector`](ue_ue.CurveVector.md)

#### Overrides

[CurveBase](ue_ue.CurveBase.md).[Find](ue_ue.CurveBase.md#find)

#### Defined in

[ue/ue.d.ts:4250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4250)

___

### Load

▸ `Static` **Load**(`InName`): [`CurveVector`](ue_ue.CurveVector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CurveVector`](ue_ue.CurveVector.md)

#### Overrides

[CurveBase](ue_ue.CurveBase.md).[Load](ue_ue.CurveBase.md#load)

#### Defined in

[ue/ue.d.ts:4251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4251)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[CurveBase](ue_ue.CurveBase.md).[StaticClass](ue_ue.CurveBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:4249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4249)
