[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorSubsystem

# Class: EditorSubsystem

[ue/ue](../modules/ue_ue.md).EditorSubsystem

## Hierarchy

- [`DynamicSubsystem`](ue_ue.DynamicSubsystem.md)

  ↳ **`EditorSubsystem`**

  ↳↳ [`AssetEditorSubsystem`](ue_ue.AssetEditorSubsystem.md)

  ↳↳ [`EditorUtilitySubsystem`](ue_ue.EditorUtilitySubsystem.md)

  ↳↳ [`EditorValidatorSubsystem`](ue_ue.EditorValidatorSubsystem.md)

  ↳↳ [`ImportSubsystem`](ue_ue.ImportSubsystem.md)

  ↳↳ [`LayersSubsystem`](ue_ue.LayersSubsystem.md)

## Table of contents

### Constructors

- [constructor](ue_ue.EditorSubsystem.md#constructor)

### Properties

- [\_\_tid\_DynamicSubsystem\_\_](ue_ue.EditorSubsystem.md#__tid_dynamicsubsystem__)
- [\_\_tid\_EditorSubsystem\_\_](ue_ue.EditorSubsystem.md#__tid_editorsubsystem__)
- [\_\_tid\_Object\_\_](ue_ue.EditorSubsystem.md#__tid_object__)
- [\_\_tid\_Subsystem\_\_](ue_ue.EditorSubsystem.md#__tid_subsystem__)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorSubsystem.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorSubsystem.md#executeubergraph)
- [GetClass](ue_ue.EditorSubsystem.md#getclass)
- [GetName](ue_ue.EditorSubsystem.md#getname)
- [GetOuter](ue_ue.EditorSubsystem.md#getouter)
- [GetWorld](ue_ue.EditorSubsystem.md#getworld)
- [Find](ue_ue.EditorSubsystem.md#find)
- [Load](ue_ue.EditorSubsystem.md#load)
- [StaticClass](ue_ue.EditorSubsystem.md#staticclass)

## Constructors

### constructor

• **new EditorSubsystem**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[constructor](ue_ue.DynamicSubsystem.md#constructor)

#### Defined in

[ue/ue.d.ts:21577](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21577)

## Properties

### \_\_tid\_DynamicSubsystem\_\_

• **\_\_tid\_DynamicSubsystem\_\_**: `boolean`

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[__tid_DynamicSubsystem__](ue_ue.DynamicSubsystem.md#__tid_dynamicsubsystem__)

#### Defined in

[ue/ue.d.ts:21573](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21573)

___

### \_\_tid\_EditorSubsystem\_\_

• **\_\_tid\_EditorSubsystem\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21582)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[__tid_Object__](ue_ue.DynamicSubsystem.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_Subsystem\_\_

• **\_\_tid\_Subsystem\_\_**: `boolean`

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[__tid_Subsystem__](ue_ue.DynamicSubsystem.md#__tid_subsystem__)

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

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[CreateDefaultSubobject](ue_ue.DynamicSubsystem.md#createdefaultsubobject)

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

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[ExecuteUbergraph](ue_ue.DynamicSubsystem.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[GetClass](ue_ue.DynamicSubsystem.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[GetName](ue_ue.DynamicSubsystem.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[GetOuter](ue_ue.DynamicSubsystem.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[GetWorld](ue_ue.DynamicSubsystem.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorSubsystem`](ue_ue.EditorSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorSubsystem`](ue_ue.EditorSubsystem.md)

#### Overrides

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[Find](ue_ue.DynamicSubsystem.md#find)

#### Defined in

[ue/ue.d.ts:21579](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21579)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorSubsystem`](ue_ue.EditorSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorSubsystem`](ue_ue.EditorSubsystem.md)

#### Overrides

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[Load](ue_ue.DynamicSubsystem.md#load)

#### Defined in

[ue/ue.d.ts:21580](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21580)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DynamicSubsystem](ue_ue.DynamicSubsystem.md).[StaticClass](ue_ue.DynamicSubsystem.md#staticclass)

#### Defined in

[ue/ue.d.ts:21578](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21578)
