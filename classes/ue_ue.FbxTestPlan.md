[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FbxTestPlan

# Class: FbxTestPlan

[ue/ue](../modules/ue_ue.md).FbxTestPlan

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`FbxTestPlan`**

## Table of contents

### Constructors

- [constructor](ue_ue.FbxTestPlan.md#constructor)

### Properties

- [Action](ue_ue.FbxTestPlan.md#action)
- [ExpectedResult](ue_ue.FbxTestPlan.md#expectedresult)
- [ImportUI](ue_ue.FbxTestPlan.md#importui)
- [LodIndex](ue_ue.FbxTestPlan.md#lodindex)
- [TestPlanName](ue_ue.FbxTestPlan.md#testplanname)
- [\_\_tid\_FbxTestPlan\_\_](ue_ue.FbxTestPlan.md#__tid_fbxtestplan__)
- [\_\_tid\_Object\_\_](ue_ue.FbxTestPlan.md#__tid_object__)
- [bDeleteFolderAssets](ue_ue.FbxTestPlan.md#bdeletefolderassets)

### Methods

- [CreateDefaultSubobject](ue_ue.FbxTestPlan.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FbxTestPlan.md#executeubergraph)
- [GetClass](ue_ue.FbxTestPlan.md#getclass)
- [GetName](ue_ue.FbxTestPlan.md#getname)
- [GetOuter](ue_ue.FbxTestPlan.md#getouter)
- [GetWorld](ue_ue.FbxTestPlan.md#getworld)
- [Find](ue_ue.FbxTestPlan.md#find)
- [Load](ue_ue.FbxTestPlan.md#load)
- [StaticClass](ue_ue.FbxTestPlan.md#staticclass)

## Constructors

### constructor

• **new FbxTestPlan**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Action

• **Action**: [`EFBXTestPlanActionType`](../enums/ue_ue.EFBXTestPlanActionType.md)

___

### ExpectedResult

• **ExpectedResult**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FbxTestPlanExpectedResult`](ue_ue.FbxTestPlanExpectedResult.md)\>

___

### ImportUI

• **ImportUI**: [`FbxImportUI`](ue_ue.FbxImportUI.md)

___

### LodIndex

• **LodIndex**: `number`

___

### TestPlanName

• **TestPlanName**: `string`

___

### \_\_tid\_FbxTestPlan\_\_

• **\_\_tid\_FbxTestPlan\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bDeleteFolderAssets

• **bDeleteFolderAssets**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FbxTestPlan`](ue_ue.FbxTestPlan.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FbxTestPlan`](ue_ue.FbxTestPlan.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FbxTestPlan`](ue_ue.FbxTestPlan.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FbxTestPlan`](ue_ue.FbxTestPlan.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
