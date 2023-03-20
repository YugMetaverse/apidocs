[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorParentPlayerListObj

# Class: EditorParentPlayerListObj

[ue/ue](../modules/ue_ue.md).EditorParentPlayerListObj

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EditorParentPlayerListObj`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorParentPlayerListObj.md#constructor)

### Properties

- [Overrides](ue_ue.EditorParentPlayerListObj.md#overrides)
- [\_\_tid\_EditorParentPlayerListObj\_\_](ue_ue.EditorParentPlayerListObj.md#__tid_editorparentplayerlistobj__)
- [\_\_tid\_Object\_\_](ue_ue.EditorParentPlayerListObj.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorParentPlayerListObj.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorParentPlayerListObj.md#executeubergraph)
- [GetClass](ue_ue.EditorParentPlayerListObj.md#getclass)
- [GetName](ue_ue.EditorParentPlayerListObj.md#getname)
- [GetOuter](ue_ue.EditorParentPlayerListObj.md#getouter)
- [GetWorld](ue_ue.EditorParentPlayerListObj.md#getworld)
- [Find](ue_ue.EditorParentPlayerListObj.md#find)
- [Load](ue_ue.EditorParentPlayerListObj.md#load)
- [StaticClass](ue_ue.EditorParentPlayerListObj.md#staticclass)

## Constructors

### constructor

• **new EditorParentPlayerListObj**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:33168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33168)

## Properties

### Overrides

• **Overrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimParentNodeAssetOverride`](ue_ue.AnimParentNodeAssetOverride.md)\>

#### Defined in

[ue/ue.d.ts:33169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33169)

___

### \_\_tid\_EditorParentPlayerListObj\_\_

• **\_\_tid\_EditorParentPlayerListObj\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:33174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33174)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorParentPlayerListObj`](ue_ue.EditorParentPlayerListObj.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorParentPlayerListObj`](ue_ue.EditorParentPlayerListObj.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:33171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33171)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorParentPlayerListObj`](ue_ue.EditorParentPlayerListObj.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorParentPlayerListObj`](ue_ue.EditorParentPlayerListObj.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:33172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33172)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:33170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33170)
