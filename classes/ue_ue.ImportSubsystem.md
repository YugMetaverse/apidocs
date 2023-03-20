[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ImportSubsystem

# Class: ImportSubsystem

[ue/ue](../modules/ue_ue.md).ImportSubsystem

## Hierarchy

- [`EditorSubsystem`](ue_ue.EditorSubsystem.md)

  ↳ **`ImportSubsystem`**

## Table of contents

### Constructors

- [constructor](ue_ue.ImportSubsystem.md#constructor)

### Properties

- [OnAssetPostImport\_BP](ue_ue.ImportSubsystem.md#onassetpostimport_bp)
- [OnAssetPostLODImport\_BP](ue_ue.ImportSubsystem.md#onassetpostlodimport_bp)
- [OnAssetPreImport\_BP](ue_ue.ImportSubsystem.md#onassetpreimport_bp)
- [OnAssetReimport\_BP](ue_ue.ImportSubsystem.md#onassetreimport_bp)
- [\_\_tid\_DynamicSubsystem\_\_](ue_ue.ImportSubsystem.md#__tid_dynamicsubsystem__)
- [\_\_tid\_EditorSubsystem\_\_](ue_ue.ImportSubsystem.md#__tid_editorsubsystem__)
- [\_\_tid\_ImportSubsystem\_\_](ue_ue.ImportSubsystem.md#__tid_importsubsystem__)
- [\_\_tid\_Object\_\_](ue_ue.ImportSubsystem.md#__tid_object__)
- [\_\_tid\_Subsystem\_\_](ue_ue.ImportSubsystem.md#__tid_subsystem__)

### Methods

- [CreateDefaultSubobject](ue_ue.ImportSubsystem.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ImportSubsystem.md#executeubergraph)
- [GetClass](ue_ue.ImportSubsystem.md#getclass)
- [GetName](ue_ue.ImportSubsystem.md#getname)
- [GetOuter](ue_ue.ImportSubsystem.md#getouter)
- [GetWorld](ue_ue.ImportSubsystem.md#getworld)
- [OnAssetPostImport\_Dyn\_\_DelegateSignature](ue_ue.ImportSubsystem.md#onassetpostimport_dyn__delegatesignature)
- [OnAssetPostLODImport\_Dyn\_\_DelegateSignature](ue_ue.ImportSubsystem.md#onassetpostlodimport_dyn__delegatesignature)
- [OnAssetPreImport\_Dyn\_\_DelegateSignature](ue_ue.ImportSubsystem.md#onassetpreimport_dyn__delegatesignature)
- [OnAssetReimport\_Dyn\_\_DelegateSignature](ue_ue.ImportSubsystem.md#onassetreimport_dyn__delegatesignature)
- [Find](ue_ue.ImportSubsystem.md#find)
- [Load](ue_ue.ImportSubsystem.md#load)
- [StaticClass](ue_ue.ImportSubsystem.md#staticclass)

## Constructors

### constructor

• **new ImportSubsystem**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[constructor](ue_ue.EditorSubsystem.md#constructor)

#### Defined in

[ue/ue.d.ts:38924](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38924)

## Properties

### OnAssetPostImport\_BP

• **OnAssetPostImport\_BP**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`InFactory`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Factory`](ue_ue.Factory.md)\>, `InCreatedObject`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:38926](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38926)

___

### OnAssetPostLODImport\_BP

• **OnAssetPostLODImport\_BP**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`InObject`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `InLODIndex`: `number`) => `void`\>

#### Defined in

[ue/ue.d.ts:38928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38928)

___

### OnAssetPreImport\_BP

• **OnAssetPreImport\_BP**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`InFactory`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Factory`](ue_ue.Factory.md)\>, `InClass`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\>, `InParent`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `Name`: `string`, `Type`: `string`) => `void`\>

#### Defined in

[ue/ue.d.ts:38925](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38925)

___

### OnAssetReimport\_BP

• **OnAssetReimport\_BP**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`InCreatedObject`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:38927](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38927)

___

### \_\_tid\_DynamicSubsystem\_\_

• **\_\_tid\_DynamicSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_DynamicSubsystem__](ue_ue.EditorSubsystem.md#__tid_dynamicsubsystem__)

#### Defined in

[ue/ue.d.ts:21573](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21573)

___

### \_\_tid\_EditorSubsystem\_\_

• **\_\_tid\_EditorSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_EditorSubsystem__](ue_ue.EditorSubsystem.md#__tid_editorsubsystem__)

#### Defined in

[ue/ue.d.ts:21582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21582)

___

### \_\_tid\_ImportSubsystem\_\_

• **\_\_tid\_ImportSubsystem\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:38937](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38937)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Object__](ue_ue.EditorSubsystem.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_Subsystem\_\_

• **\_\_tid\_Subsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Subsystem__](ue_ue.EditorSubsystem.md#__tid_subsystem__)

#### Defined in

[ue/ue.d.ts:21564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21564)

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

[EditorSubsystem](ue_ue.EditorSubsystem.md).[CreateDefaultSubobject](ue_ue.EditorSubsystem.md#createdefaultsubobject)

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

[EditorSubsystem](ue_ue.EditorSubsystem.md).[ExecuteUbergraph](ue_ue.EditorSubsystem.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetClass](ue_ue.EditorSubsystem.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetName](ue_ue.EditorSubsystem.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetOuter](ue_ue.EditorSubsystem.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetWorld](ue_ue.EditorSubsystem.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### OnAssetPostImport\_Dyn\_\_DelegateSignature

▸ **OnAssetPostImport_Dyn__DelegateSignature**(`InFactory`, `InCreatedObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFactory` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Factory`](ue_ue.Factory.md)\> |
| `InCreatedObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38929](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38929)

___

### OnAssetPostLODImport\_Dyn\_\_DelegateSignature

▸ **OnAssetPostLODImport_Dyn__DelegateSignature**(`InObject`, `InLODIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `InLODIndex` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38930](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38930)

___

### OnAssetPreImport\_Dyn\_\_DelegateSignature

▸ **OnAssetPreImport_Dyn__DelegateSignature**(`InFactory`, `InClass`, `InParent`, `Name`, `Type`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFactory` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Factory`](ue_ue.Factory.md)\> |
| `InClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `InParent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Name` | `string` |
| `Type` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38931](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38931)

___

### OnAssetReimport\_Dyn\_\_DelegateSignature

▸ **OnAssetReimport_Dyn__DelegateSignature**(`InCreatedObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCreatedObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38932](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38932)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ImportSubsystem`](ue_ue.ImportSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ImportSubsystem`](ue_ue.ImportSubsystem.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[Find](ue_ue.EditorSubsystem.md#find)

#### Defined in

[ue/ue.d.ts:38934](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38934)

___

### Load

▸ `Static` **Load**(`InName`): [`ImportSubsystem`](ue_ue.ImportSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ImportSubsystem`](ue_ue.ImportSubsystem.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[Load](ue_ue.EditorSubsystem.md#load)

#### Defined in

[ue/ue.d.ts:38935](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38935)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[StaticClass](ue_ue.EditorSubsystem.md#staticclass)

#### Defined in

[ue/ue.d.ts:38933](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38933)
