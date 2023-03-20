[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / StructViewerProjectSettings

# Class: StructViewerProjectSettings

[ue/ue](../modules/ue_ue.md).StructViewerProjectSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`StructViewerProjectSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.StructViewerProjectSettings.md#constructor)

### Properties

- [InternalOnlyPaths](ue_ue.StructViewerProjectSettings.md#internalonlypaths)
- [InternalOnlyStructs](ue_ue.StructViewerProjectSettings.md#internalonlystructs)
- [\_\_tid\_Object\_\_](ue_ue.StructViewerProjectSettings.md#__tid_object__)
- [\_\_tid\_StructViewerProjectSettings\_\_](ue_ue.StructViewerProjectSettings.md#__tid_structviewerprojectsettings__)

### Methods

- [CreateDefaultSubobject](ue_ue.StructViewerProjectSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.StructViewerProjectSettings.md#executeubergraph)
- [GetClass](ue_ue.StructViewerProjectSettings.md#getclass)
- [GetName](ue_ue.StructViewerProjectSettings.md#getname)
- [GetOuter](ue_ue.StructViewerProjectSettings.md#getouter)
- [GetWorld](ue_ue.StructViewerProjectSettings.md#getworld)
- [Find](ue_ue.StructViewerProjectSettings.md#find)
- [Load](ue_ue.StructViewerProjectSettings.md#load)
- [StaticClass](ue_ue.StructViewerProjectSettings.md#staticclass)

## Constructors

### constructor

• **new StructViewerProjectSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### InternalOnlyPaths

• **InternalOnlyPaths**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

___

### InternalOnlyStructs

• **InternalOnlyStructs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`ScriptStruct`](ue_ue.ScriptStruct.md)\>\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_StructViewerProjectSettings\_\_

• **\_\_tid\_StructViewerProjectSettings\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`StructViewerProjectSettings`](ue_ue.StructViewerProjectSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`StructViewerProjectSettings`](ue_ue.StructViewerProjectSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`StructViewerProjectSettings`](ue_ue.StructViewerProjectSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`StructViewerProjectSettings`](ue_ue.StructViewerProjectSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
