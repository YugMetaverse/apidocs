[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ScriptStruct

# Class: ScriptStruct

[ue/ue](../modules/ue_ue.md).ScriptStruct

## Hierarchy

- [`Struct`](ue_ue.Struct.md)

  ↳ **`ScriptStruct`**

  ↳↳ [`UserDefinedStruct`](ue_ue.UserDefinedStruct.md)

  ↳↳ [`MovieSceneKeyStructType`](ue_ue.MovieSceneKeyStructType.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ScriptStruct.md#constructor)

### Properties

- [\_\_tid\_Field\_\_](ue_ue.ScriptStruct.md#__tid_field__)
- [\_\_tid\_Object\_\_](ue_ue.ScriptStruct.md#__tid_object__)
- [\_\_tid\_ScriptStruct\_\_](ue_ue.ScriptStruct.md#__tid_scriptstruct__)
- [\_\_tid\_Struct\_\_](ue_ue.ScriptStruct.md#__tid_struct__)

### Methods

- [CreateDefaultSubobject](ue_ue.ScriptStruct.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ScriptStruct.md#executeubergraph)
- [GetClass](ue_ue.ScriptStruct.md#getclass)
- [GetName](ue_ue.ScriptStruct.md#getname)
- [GetOuter](ue_ue.ScriptStruct.md#getouter)
- [GetWorld](ue_ue.ScriptStruct.md#getworld)
- [IsChildOf](ue_ue.ScriptStruct.md#ischildof)
- [Find](ue_ue.ScriptStruct.md#find)
- [Load](ue_ue.ScriptStruct.md#load)
- [StaticClass](ue_ue.ScriptStruct.md#staticclass)

## Constructors

### constructor

• **new ScriptStruct**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Struct](ue_ue.Struct.md).[constructor](ue_ue.Struct.md#constructor)

#### Defined in

[ue/ue.d.ts:15948](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15948)

## Properties

### \_\_tid\_Field\_\_

• **\_\_tid\_Field\_\_**: `boolean`

#### Inherited from

[Struct](ue_ue.Struct.md).[__tid_Field__](ue_ue.Struct.md#__tid_field__)

#### Defined in

[ue/ue.d.ts:700](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L700)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Struct](ue_ue.Struct.md).[__tid_Object__](ue_ue.Struct.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ScriptStruct\_\_

• **\_\_tid\_ScriptStruct\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15953](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15953)

___

### \_\_tid\_Struct\_\_

• **\_\_tid\_Struct\_\_**: `boolean`

#### Inherited from

[Struct](ue_ue.Struct.md).[__tid_Struct__](ue_ue.Struct.md#__tid_struct__)

#### Defined in

[ue/ue.d.ts:710](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L710)

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

[Struct](ue_ue.Struct.md).[CreateDefaultSubobject](ue_ue.Struct.md#createdefaultsubobject)

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

[Struct](ue_ue.Struct.md).[ExecuteUbergraph](ue_ue.Struct.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Struct](ue_ue.Struct.md).[GetClass](ue_ue.Struct.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Struct](ue_ue.Struct.md).[GetName](ue_ue.Struct.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Struct](ue_ue.Struct.md).[GetOuter](ue_ue.Struct.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Struct](ue_ue.Struct.md).[GetWorld](ue_ue.Struct.md#getworld)

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

[Struct](ue_ue.Struct.md).[IsChildOf](ue_ue.Struct.md#ischildof)

#### Defined in

[ue/ue.d.ts:705](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L705)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[Struct](ue_ue.Struct.md).[Find](ue_ue.Struct.md#find)

#### Defined in

[ue/ue.d.ts:15950](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15950)

___

### Load

▸ `Static` **Load**(`InName`): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[Struct](ue_ue.Struct.md).[Load](ue_ue.Struct.md#load)

#### Defined in

[ue/ue.d.ts:15951](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15951)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Struct](ue_ue.Struct.md).[StaticClass](ue_ue.Struct.md#staticclass)

#### Defined in

[ue/ue.d.ts:15949](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15949)
