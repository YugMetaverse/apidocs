[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UnrealEdOptions

# Class: UnrealEdOptions

[ue/ue](../modules/ue_ue.md).UnrealEdOptions

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`UnrealEdOptions`**

## Table of contents

### Constructors

- [constructor](ue_ue.UnrealEdOptions.md#constructor)

### Properties

- [EditorCategories](ue_ue.UnrealEdOptions.md#editorcategories)
- [EditorCommands](ue_ue.UnrealEdOptions.md#editorcommands)
- [EditorKeyBindings](ue_ue.UnrealEdOptions.md#editorkeybindings)
- [NewAssetDefaultClasses](ue_ue.UnrealEdOptions.md#newassetdefaultclasses)
- [\_\_tid\_Object\_\_](ue_ue.UnrealEdOptions.md#__tid_object__)
- [\_\_tid\_UnrealEdOptions\_\_](ue_ue.UnrealEdOptions.md#__tid_unrealedoptions__)
- [bExpandClassPickerClassList](ue_ue.UnrealEdOptions.md#bexpandclasspickerclasslist)

### Methods

- [CreateDefaultSubobject](ue_ue.UnrealEdOptions.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UnrealEdOptions.md#executeubergraph)
- [GetClass](ue_ue.UnrealEdOptions.md#getclass)
- [GetName](ue_ue.UnrealEdOptions.md#getname)
- [GetOuter](ue_ue.UnrealEdOptions.md#getouter)
- [GetWorld](ue_ue.UnrealEdOptions.md#getworld)
- [Find](ue_ue.UnrealEdOptions.md#find)
- [Load](ue_ue.UnrealEdOptions.md#load)
- [StaticClass](ue_ue.UnrealEdOptions.md#staticclass)

## Constructors

### constructor

• **new UnrealEdOptions**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:64717](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64717)

## Properties

### EditorCategories

• **EditorCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditorCommandCategory`](ue_ue.EditorCommandCategory.md)\>

#### Defined in

[ue/ue.d.ts:64718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64718)

___

### EditorCommands

• **EditorCommands**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditorCommand`](ue_ue.EditorCommand.md)\>

#### Defined in

[ue/ue.d.ts:64719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64719)

___

### EditorKeyBindings

• **EditorKeyBindings**: [`UnrealEdKeyBindings`](ue_ue.UnrealEdKeyBindings.md)

#### Defined in

[ue/ue.d.ts:64720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64720)

___

### NewAssetDefaultClasses

• **NewAssetDefaultClasses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClassPickerDefaults`](ue_ue.ClassPickerDefaults.md)\>

#### Defined in

[ue/ue.d.ts:64722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64722)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_UnrealEdOptions\_\_

• **\_\_tid\_UnrealEdOptions\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64727](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64727)

___

### bExpandClassPickerClassList

• **bExpandClassPickerClassList**: `boolean`

#### Defined in

[ue/ue.d.ts:64721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64721)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UnrealEdOptions`](ue_ue.UnrealEdOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UnrealEdOptions`](ue_ue.UnrealEdOptions.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:64724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64724)

___

### Load

▸ `Static` **Load**(`InName`): [`UnrealEdOptions`](ue_ue.UnrealEdOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UnrealEdOptions`](ue_ue.UnrealEdOptions.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:64725](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64725)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:64723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64723)
