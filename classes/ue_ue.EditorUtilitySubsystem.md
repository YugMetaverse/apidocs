[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorUtilitySubsystem

# Class: EditorUtilitySubsystem

[ue/ue](../modules/ue_ue.md).EditorUtilitySubsystem

## Hierarchy

- [`EditorSubsystem`](ue_ue.EditorSubsystem.md)

  ↳ **`EditorUtilitySubsystem`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorUtilitySubsystem.md#constructor)

### Properties

- [LoadedUIs](ue_ue.EditorUtilitySubsystem.md#loadeduis)
- [ObjectInstances](ue_ue.EditorUtilitySubsystem.md#objectinstances)
- [StartupObjects](ue_ue.EditorUtilitySubsystem.md#startupobjects)
- [\_\_tid\_DynamicSubsystem\_\_](ue_ue.EditorUtilitySubsystem.md#__tid_dynamicsubsystem__)
- [\_\_tid\_EditorSubsystem\_\_](ue_ue.EditorUtilitySubsystem.md#__tid_editorsubsystem__)
- [\_\_tid\_EditorUtilitySubsystem\_\_](ue_ue.EditorUtilitySubsystem.md#__tid_editorutilitysubsystem__)
- [\_\_tid\_Object\_\_](ue_ue.EditorUtilitySubsystem.md#__tid_object__)
- [\_\_tid\_Subsystem\_\_](ue_ue.EditorUtilitySubsystem.md#__tid_subsystem__)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorUtilitySubsystem.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorUtilitySubsystem.md#executeubergraph)
- [GetClass](ue_ue.EditorUtilitySubsystem.md#getclass)
- [GetName](ue_ue.EditorUtilitySubsystem.md#getname)
- [GetOuter](ue_ue.EditorUtilitySubsystem.md#getouter)
- [GetWorld](ue_ue.EditorUtilitySubsystem.md#getworld)
- [ReleaseInstanceOfAsset](ue_ue.EditorUtilitySubsystem.md#releaseinstanceofasset)
- [SpawnAndRegisterTab](ue_ue.EditorUtilitySubsystem.md#spawnandregistertab)
- [TryRun](ue_ue.EditorUtilitySubsystem.md#tryrun)
- [Find](ue_ue.EditorUtilitySubsystem.md#find)
- [Load](ue_ue.EditorUtilitySubsystem.md#load)
- [StaticClass](ue_ue.EditorUtilitySubsystem.md#staticclass)

## Constructors

### constructor

• **new EditorUtilitySubsystem**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[constructor](ue_ue.EditorSubsystem.md#constructor)

#### Defined in

[ue/ue.d.ts:33691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33691)

## Properties

### LoadedUIs

• **LoadedUIs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\>

#### Defined in

[ue/ue.d.ts:33692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33692)

___

### ObjectInstances

• **ObjectInstances**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Object`](ue_ue.Object.md), [`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:33694](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33694)

___

### StartupObjects

• **StartupObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\>

#### Defined in

[ue/ue.d.ts:33693](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33693)

___

### \_\_tid\_DynamicSubsystem\_\_

• **\_\_tid\_DynamicSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_DynamicSubsystem__](ue_ue.EditorSubsystem.md#__tid_dynamicsubsystem__)

#### Defined in

[ue/ue.d.ts:21573](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21573)

___

### \_\_tid\_EditorSubsystem\_\_

• **\_\_tid\_EditorSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_EditorSubsystem__](ue_ue.EditorSubsystem.md#__tid_editorsubsystem__)

#### Defined in

[ue/ue.d.ts:21582](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21582)

___

### \_\_tid\_EditorUtilitySubsystem\_\_

• **\_\_tid\_EditorUtilitySubsystem\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:33702](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33702)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Object__](ue_ue.EditorSubsystem.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_Subsystem\_\_

• **\_\_tid\_Subsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Subsystem__](ue_ue.EditorSubsystem.md#__tid_subsystem__)

#### Defined in

[ue/ue.d.ts:21564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21564)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetClass](ue_ue.EditorSubsystem.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetName](ue_ue.EditorSubsystem.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetOuter](ue_ue.EditorSubsystem.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetWorld](ue_ue.EditorSubsystem.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### ReleaseInstanceOfAsset

▸ **ReleaseInstanceOfAsset**(`Asset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Asset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33695](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33695)

___

### SpawnAndRegisterTab

▸ **SpawnAndRegisterTab**(`InBlueprint`): [`EditorUtilityWidget`](ue_ue.EditorUtilityWidget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBlueprint` | [`$Nullable`](../modules/puerts.md#$nullable)<[`EditorUtilityWidgetBlueprint`](ue_ue.EditorUtilityWidgetBlueprint.md)\> |

#### Returns

[`EditorUtilityWidget`](ue_ue.EditorUtilityWidget.md)

#### Defined in

[ue/ue.d.ts:33696](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33696)

___

### TryRun

▸ **TryRun**(`Asset`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Asset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:33697](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33697)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorUtilitySubsystem`](ue_ue.EditorUtilitySubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorUtilitySubsystem`](ue_ue.EditorUtilitySubsystem.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[Find](ue_ue.EditorSubsystem.md#find)

#### Defined in

[ue/ue.d.ts:33699](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33699)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorUtilitySubsystem`](ue_ue.EditorUtilitySubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorUtilitySubsystem`](ue_ue.EditorUtilitySubsystem.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[Load](ue_ue.EditorSubsystem.md#load)

#### Defined in

[ue/ue.d.ts:33700](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33700)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[StaticClass](ue_ue.EditorSubsystem.md#staticclass)

#### Defined in

[ue/ue.d.ts:33698](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33698)
