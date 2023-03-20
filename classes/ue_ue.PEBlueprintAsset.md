[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PEBlueprintAsset

# Class: PEBlueprintAsset

[ue/ue](../modules/ue_ue.md).PEBlueprintAsset

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PEBlueprintAsset`**

## Table of contents

### Constructors

- [constructor](ue_ue.PEBlueprintAsset.md#constructor)

### Properties

- [Blueprint](ue_ue.PEBlueprintAsset.md#blueprint)
- [GeneratedClass](ue_ue.PEBlueprintAsset.md#generatedclass)
- [HasConstructor](ue_ue.PEBlueprintAsset.md#hasconstructor)
- [NeedSave](ue_ue.PEBlueprintAsset.md#needsave)
- [Package](ue_ue.PEBlueprintAsset.md#package)
- [\_\_tid\_Object\_\_](ue_ue.PEBlueprintAsset.md#__tid_object__)
- [\_\_tid\_PEBlueprintAsset\_\_](ue_ue.PEBlueprintAsset.md#__tid_peblueprintasset__)

### Methods

- [AddFunction](ue_ue.PEBlueprintAsset.md#addfunction)
- [AddFunctionWithMetaData](ue_ue.PEBlueprintAsset.md#addfunctionwithmetadata)
- [AddMemberVariable](ue_ue.PEBlueprintAsset.md#addmembervariable)
- [AddMemberVariableWithMetaData](ue_ue.PEBlueprintAsset.md#addmembervariablewithmetadata)
- [AddParameter](ue_ue.PEBlueprintAsset.md#addparameter)
- [AddParameterWithMetaData](ue_ue.PEBlueprintAsset.md#addparameterwithmetadata)
- [ClearParameter](ue_ue.PEBlueprintAsset.md#clearparameter)
- [CreateDefaultSubobject](ue_ue.PEBlueprintAsset.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PEBlueprintAsset.md#executeubergraph)
- [GetClass](ue_ue.PEBlueprintAsset.md#getclass)
- [GetName](ue_ue.PEBlueprintAsset.md#getname)
- [GetOuter](ue_ue.PEBlueprintAsset.md#getouter)
- [GetWorld](ue_ue.PEBlueprintAsset.md#getworld)
- [LoadOrCreate](ue_ue.PEBlueprintAsset.md#loadorcreate)
- [LoadOrCreateWithMetaData](ue_ue.PEBlueprintAsset.md#loadorcreatewithmetadata)
- [RemoveNotExistedFunction](ue_ue.PEBlueprintAsset.md#removenotexistedfunction)
- [RemoveNotExistedMemberVariable](ue_ue.PEBlueprintAsset.md#removenotexistedmembervariable)
- [Save](ue_ue.PEBlueprintAsset.md#save)
- [Existed](ue_ue.PEBlueprintAsset.md#existed)
- [Find](ue_ue.PEBlueprintAsset.md#find)
- [Load](ue_ue.PEBlueprintAsset.md#load)
- [StaticClass](ue_ue.PEBlueprintAsset.md#staticclass)

## Constructors

### constructor

• **new PEBlueprintAsset**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Blueprint

• **Blueprint**: [`Blueprint`](ue_ue.Blueprint.md)

___

### GeneratedClass

• **GeneratedClass**: [`Class`](ue_ue.Class.md)

___

### HasConstructor

• **HasConstructor**: `boolean`

___

### NeedSave

• **NeedSave**: `boolean`

___

### Package

• **Package**: [`Package`](ue_ue.Package.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PEBlueprintAsset\_\_

• **\_\_tid\_PEBlueprintAsset\_\_**: `boolean`

## Methods

### AddFunction

▸ **AddFunction**(`InName`, `IsVoid`, `InGraphPinType`, `InPinValueType`, `InSetFlags`, `InClearFlags`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |
| `IsVoid` | `boolean` |
| `InGraphPinType` | [`PEGraphPinType`](ue_ue.PEGraphPinType.md) |
| `InPinValueType` | [`PEGraphTerminalType`](ue_ue.PEGraphTerminalType.md) |
| `InSetFlags` | `number` |
| `InClearFlags` | `number` |

#### Returns

`void`

___

### AddFunctionWithMetaData

▸ **AddFunctionWithMetaData**(`InName`, `IsVoid`, `InGraphPinType`, `InPinValueType`, `InSetFlags`, `InClearFlags`, `InMetaData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |
| `IsVoid` | `boolean` |
| `InGraphPinType` | [`PEGraphPinType`](ue_ue.PEGraphPinType.md) |
| `InPinValueType` | [`PEGraphTerminalType`](ue_ue.PEGraphTerminalType.md) |
| `InSetFlags` | `number` |
| `InClearFlags` | `number` |
| `InMetaData` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PEFunctionMetaData`](ue_ue.PEFunctionMetaData.md)\> |

#### Returns

`void`

___

### AddMemberVariable

▸ **AddMemberVariable**(`NewVarName`, `InGraphPinType`, `InPinValueType`, `InLFlags`, `InHFlags`, `InLifetimeCondition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewVarName` | `string` |
| `InGraphPinType` | [`PEGraphPinType`](ue_ue.PEGraphPinType.md) |
| `InPinValueType` | [`PEGraphTerminalType`](ue_ue.PEGraphTerminalType.md) |
| `InLFlags` | `number` |
| `InHFlags` | `number` |
| `InLifetimeCondition` | `number` |

#### Returns

`void`

___

### AddMemberVariableWithMetaData

▸ **AddMemberVariableWithMetaData**(`InNewVarName`, `InGraphPinType`, `InPinValueType`, `InLFlags`, `InHFLags`, `InLifetimeCondition`, `InMetaData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InNewVarName` | `string` |
| `InGraphPinType` | [`PEGraphPinType`](ue_ue.PEGraphPinType.md) |
| `InPinValueType` | [`PEGraphTerminalType`](ue_ue.PEGraphTerminalType.md) |
| `InLFlags` | `number` |
| `InHFLags` | `number` |
| `InLifetimeCondition` | `number` |
| `InMetaData` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PEPropertyMetaData`](ue_ue.PEPropertyMetaData.md)\> |

#### Returns

`void`

___

### AddParameter

▸ **AddParameter**(`InParameterName`, `InGraphPinType`, `InPinValueType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InParameterName` | `string` |
| `InGraphPinType` | [`PEGraphPinType`](ue_ue.PEGraphPinType.md) |
| `InPinValueType` | [`PEGraphTerminalType`](ue_ue.PEGraphTerminalType.md) |

#### Returns

`void`

___

### AddParameterWithMetaData

▸ **AddParameterWithMetaData**(`InParameterName`, `InGraphPinType`, `InPinValueType`, `InMetaData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InParameterName` | `string` |
| `InGraphPinType` | [`PEGraphPinType`](ue_ue.PEGraphPinType.md) |
| `InPinValueType` | [`PEGraphTerminalType`](ue_ue.PEGraphTerminalType.md) |
| `InMetaData` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PEParamMetaData`](ue_ue.PEParamMetaData.md)\> |

#### Returns

`void`

___

### ClearParameter

▸ **ClearParameter**(): `void`

#### Returns

`void`

___

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

### LoadOrCreate

▸ **LoadOrCreate**(`InName`, `InPath`, `ParentClass`, `InSetFlags`, `InClearFlags`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |
| `InPath` | `string` |
| `ParentClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `InSetFlags` | `number` |
| `InClearFlags` | `number` |

#### Returns

`boolean`

___

### LoadOrCreateWithMetaData

▸ **LoadOrCreateWithMetaData**(`InName`, `InPath`, `InParentClass`, `InSetFlags`, `InClearFlags`, `InMetaData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |
| `InPath` | `string` |
| `InParentClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `InSetFlags` | `number` |
| `InClearFlags` | `number` |
| `InMetaData` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PEClassMetaData`](ue_ue.PEClassMetaData.md)\> |

#### Returns

`boolean`

___

### RemoveNotExistedFunction

▸ **RemoveNotExistedFunction**(): `void`

#### Returns

`void`

___

### RemoveNotExistedMemberVariable

▸ **RemoveNotExistedMemberVariable**(): `void`

#### Returns

`void`

___

### Save

▸ **Save**(): `void`

#### Returns

`void`

___

### Existed

▸ `Static` **Existed**(`InName`, `InPath`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |
| `InPath` | `string` |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PEBlueprintAsset`](ue_ue.PEBlueprintAsset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PEBlueprintAsset`](ue_ue.PEBlueprintAsset.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PEBlueprintAsset`](ue_ue.PEBlueprintAsset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PEBlueprintAsset`](ue_ue.PEBlueprintAsset.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
