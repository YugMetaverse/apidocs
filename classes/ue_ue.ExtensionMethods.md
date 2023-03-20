[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ExtensionMethods

# Class: ExtensionMethods

[ue/ue](../modules/ue_ue.md).ExtensionMethods

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`ExtensionMethods`**

  ↳↳ [`VectorExtensionMethods`](ue_ue.VectorExtensionMethods.md)

  ↳↳ [`WorldExtensionMethods`](ue_ue.WorldExtensionMethods.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ExtensionMethods.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.ExtensionMethods.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_ExtensionMethods\_\_](ue_ue.ExtensionMethods.md#__tid_extensionmethods__)
- [\_\_tid\_Object\_\_](ue_ue.ExtensionMethods.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ExtensionMethods.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ExtensionMethods.md#executeubergraph)
- [GetClass](ue_ue.ExtensionMethods.md#getclass)
- [GetName](ue_ue.ExtensionMethods.md#getname)
- [GetOuter](ue_ue.ExtensionMethods.md#getouter)
- [GetWorld](ue_ue.ExtensionMethods.md#getworld)
- [Find](ue_ue.ExtensionMethods.md#find)
- [Load](ue_ue.ExtensionMethods.md#load)
- [StaticClass](ue_ue.ExtensionMethods.md#staticclass)

## Constructors

### constructor

• **new ExtensionMethods**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:35044](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35044)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_ExtensionMethods\_\_

• **\_\_tid\_ExtensionMethods\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:35049](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35049)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ExtensionMethods`](ue_ue.ExtensionMethods.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ExtensionMethods`](ue_ue.ExtensionMethods.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:35046](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35046)

___

### Load

▸ `Static` **Load**(`InName`): [`ExtensionMethods`](ue_ue.ExtensionMethods.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ExtensionMethods`](ue_ue.ExtensionMethods.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:35047](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35047)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:35045](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35045)
