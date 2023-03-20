[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClassViewerProjectSettings

# Class: ClassViewerProjectSettings

[ue/ue](../modules/ue_ue.md).ClassViewerProjectSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ClassViewerProjectSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.ClassViewerProjectSettings.md#constructor)

### Properties

- [InternalOnlyClasses](ue_ue.ClassViewerProjectSettings.md#internalonlyclasses)
- [InternalOnlyPaths](ue_ue.ClassViewerProjectSettings.md#internalonlypaths)
- [\_\_tid\_ClassViewerProjectSettings\_\_](ue_ue.ClassViewerProjectSettings.md#__tid_classviewerprojectsettings__)
- [\_\_tid\_Object\_\_](ue_ue.ClassViewerProjectSettings.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ClassViewerProjectSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ClassViewerProjectSettings.md#executeubergraph)
- [GetClass](ue_ue.ClassViewerProjectSettings.md#getclass)
- [GetName](ue_ue.ClassViewerProjectSettings.md#getname)
- [GetOuter](ue_ue.ClassViewerProjectSettings.md#getouter)
- [GetWorld](ue_ue.ClassViewerProjectSettings.md#getworld)
- [Find](ue_ue.ClassViewerProjectSettings.md#find)
- [Load](ue_ue.ClassViewerProjectSettings.md#load)
- [StaticClass](ue_ue.ClassViewerProjectSettings.md#staticclass)

## Constructors

### constructor

• **new ClassViewerProjectSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:27448](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27448)

## Properties

### InternalOnlyClasses

• **InternalOnlyClasses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftClassPath`](ue_ue.SoftClassPath.md)\>

#### Defined in

[ue/ue.d.ts:27450](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27450)

___

### InternalOnlyPaths

• **InternalOnlyPaths**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

#### Defined in

[ue/ue.d.ts:27449](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27449)

___

### \_\_tid\_ClassViewerProjectSettings\_\_

• **\_\_tid\_ClassViewerProjectSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:27455](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27455)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ClassViewerProjectSettings`](ue_ue.ClassViewerProjectSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ClassViewerProjectSettings`](ue_ue.ClassViewerProjectSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:27452](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27452)

___

### Load

▸ `Static` **Load**(`InName`): [`ClassViewerProjectSettings`](ue_ue.ClassViewerProjectSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ClassViewerProjectSettings`](ue_ue.ClassViewerProjectSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:27453](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27453)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:27451](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27451)
