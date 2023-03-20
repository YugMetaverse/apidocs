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

#### Defined in

[ue/ue.d.ts:57138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57138)

## Properties

### Blueprint

• **Blueprint**: [`Blueprint`](ue_ue.Blueprint.md)

#### Defined in

[ue/ue.d.ts:57140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57140)

___

### GeneratedClass

• **GeneratedClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:57139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57139)

___

### HasConstructor

• **HasConstructor**: `boolean`

#### Defined in

[ue/ue.d.ts:57143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57143)

___

### NeedSave

• **NeedSave**: `boolean`

#### Defined in

[ue/ue.d.ts:57142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57142)

___

### Package

• **Package**: [`Package`](ue_ue.Package.md)

#### Defined in

[ue/ue.d.ts:57141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57141)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PEBlueprintAsset\_\_

• **\_\_tid\_PEBlueprintAsset\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:57161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57161)

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

#### Defined in

[ue/ue.d.ts:57144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57144)

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

#### Defined in

[ue/ue.d.ts:57145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57145)

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

#### Defined in

[ue/ue.d.ts:57146](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57146)

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

#### Defined in

[ue/ue.d.ts:57147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57147)

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

#### Defined in

[ue/ue.d.ts:57148](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57148)

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

#### Defined in

[ue/ue.d.ts:57149](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57149)

___

### ClearParameter

▸ **ClearParameter**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57150](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57150)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:57151](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57151)

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

#### Defined in

[ue/ue.d.ts:57152](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57152)

___

### RemoveNotExistedFunction

▸ **RemoveNotExistedFunction**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57153)

___

### RemoveNotExistedMemberVariable

▸ **RemoveNotExistedMemberVariable**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57154](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57154)

___

### Save

▸ **Save**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57155](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57155)

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

#### Defined in

[ue/ue.d.ts:57156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57156)

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

#### Defined in

[ue/ue.d.ts:57158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57158)

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

#### Defined in

[ue/ue.d.ts:57159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57159)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:57157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57157)
