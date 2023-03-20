[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UserDefinedStruct

# Class: UserDefinedStruct

[ue/ue](../modules/ue_ue.md).UserDefinedStruct

## Hierarchy

- [`ScriptStruct`](ue_ue.ScriptStruct.md)

  ↳ **`UserDefinedStruct`**

  ↳↳ [`AISenseBlueprintListener`](ue_ue.AISenseBlueprintListener.md)

## Table of contents

### Constructors

- [constructor](ue_ue.UserDefinedStruct.md#constructor)

### Properties

- [EditorData](ue_ue.UserDefinedStruct.md#editordata)
- [ErrorMessage](ue_ue.UserDefinedStruct.md#errormessage)
- [Guid](ue_ue.UserDefinedStruct.md#guid)
- [PrimaryStruct](ue_ue.UserDefinedStruct.md#primarystruct)
- [Status](ue_ue.UserDefinedStruct.md#status)
- [\_\_tid\_Field\_\_](ue_ue.UserDefinedStruct.md#__tid_field__)
- [\_\_tid\_Object\_\_](ue_ue.UserDefinedStruct.md#__tid_object__)
- [\_\_tid\_ScriptStruct\_\_](ue_ue.UserDefinedStruct.md#__tid_scriptstruct__)
- [\_\_tid\_Struct\_\_](ue_ue.UserDefinedStruct.md#__tid_struct__)
- [\_\_tid\_UserDefinedStruct\_\_](ue_ue.UserDefinedStruct.md#__tid_userdefinedstruct__)

### Methods

- [CreateDefaultSubobject](ue_ue.UserDefinedStruct.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UserDefinedStruct.md#executeubergraph)
- [GetClass](ue_ue.UserDefinedStruct.md#getclass)
- [GetName](ue_ue.UserDefinedStruct.md#getname)
- [GetOuter](ue_ue.UserDefinedStruct.md#getouter)
- [GetWorld](ue_ue.UserDefinedStruct.md#getworld)
- [IsChildOf](ue_ue.UserDefinedStruct.md#ischildof)
- [Find](ue_ue.UserDefinedStruct.md#find)
- [Load](ue_ue.UserDefinedStruct.md#load)
- [StaticClass](ue_ue.UserDefinedStruct.md#staticclass)

## Constructors

### constructor

• **new UserDefinedStruct**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ScriptStruct](ue_ue.ScriptStruct.md).[constructor](ue_ue.ScriptStruct.md#constructor)

#### Defined in

[ue/ue.d.ts:15958](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15958)

## Properties

### EditorData

• **EditorData**: [`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:15961](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15961)

___

### ErrorMessage

• **ErrorMessage**: `string`

#### Defined in

[ue/ue.d.ts:15960](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15960)

___

### Guid

• **Guid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:15963](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15963)

___

### PrimaryStruct

• **PrimaryStruct**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`UserDefinedStruct`](ue_ue.UserDefinedStruct.md)\>

#### Defined in

[ue/ue.d.ts:15959](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15959)

___

### Status

• **Status**: [`EUserDefinedStructureStatus`](../enums/ue_ue.EUserDefinedStructureStatus.md)

#### Defined in

[ue/ue.d.ts:15962](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15962)

___

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[__tid_Field__](ue_ue.ScriptStruct.md#__tid_field__)

#### Defined in

[ue/ue.d.ts:700](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L700)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[__tid_Object__](ue_ue.ScriptStruct.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ScriptStruct\_\_

• **\_\_tid\_ScriptStruct\_\_**: `boolean`

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[__tid_ScriptStruct__](ue_ue.ScriptStruct.md#__tid_scriptstruct__)

#### Defined in

[ue/ue.d.ts:15953](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15953)

___

### \_\_tid\_Struct\_\_

• **\_\_tid\_Struct\_\_**: `boolean`

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[__tid_Struct__](ue_ue.ScriptStruct.md#__tid_struct__)

#### Defined in

[ue/ue.d.ts:710](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L710)

___

### \_\_tid\_UserDefinedStruct\_\_

• **\_\_tid\_UserDefinedStruct\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15968](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15968)

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

[ScriptStruct](ue_ue.ScriptStruct.md).[CreateDefaultSubobject](ue_ue.ScriptStruct.md#createdefaultsubobject)

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

[ScriptStruct](ue_ue.ScriptStruct.md).[ExecuteUbergraph](ue_ue.ScriptStruct.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[GetClass](ue_ue.ScriptStruct.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[GetName](ue_ue.ScriptStruct.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[GetOuter](ue_ue.ScriptStruct.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[GetWorld](ue_ue.ScriptStruct.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsChildOf

▸ **IsChildOf**(`p0`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`Struct`](ue_ue.Struct.md) |

#### Returns

`boolean`

#### Inherited from

[ScriptStruct](ue_ue.ScriptStruct.md).[IsChildOf](ue_ue.ScriptStruct.md#ischildof)

#### Defined in

[ue/ue.d.ts:705](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L705)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UserDefinedStruct`](ue_ue.UserDefinedStruct.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UserDefinedStruct`](ue_ue.UserDefinedStruct.md)

#### Overrides

[ScriptStruct](ue_ue.ScriptStruct.md).[Find](ue_ue.ScriptStruct.md#find)

#### Defined in

[ue/ue.d.ts:15965](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15965)

___

### Load

▸ `Static` **Load**(`InName`): [`UserDefinedStruct`](ue_ue.UserDefinedStruct.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UserDefinedStruct`](ue_ue.UserDefinedStruct.md)

#### Overrides

[ScriptStruct](ue_ue.ScriptStruct.md).[Load](ue_ue.ScriptStruct.md#load)

#### Defined in

[ue/ue.d.ts:15966](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15966)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ScriptStruct](ue_ue.ScriptStruct.md).[StaticClass](ue_ue.ScriptStruct.md#staticclass)

#### Defined in

[ue/ue.d.ts:15964](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15964)
