[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialFunctionInterface

# Class: MaterialFunctionInterface

[ue/ue](../modules/ue_ue.md).MaterialFunctionInterface

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MaterialFunctionInterface`**

  ↳↳ [`MaterialFunction`](ue_ue.MaterialFunction.md)

  ↳↳ [`MaterialFunctionInstance`](ue_ue.MaterialFunctionInstance.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialFunctionInterface.md#constructor)

### Properties

- [CombinedInputTypes](ue_ue.MaterialFunctionInterface.md#combinedinputtypes)
- [CombinedOutputTypes](ue_ue.MaterialFunctionInterface.md#combinedoutputtypes)
- [MaterialFunctionUsage](ue_ue.MaterialFunctionInterface.md#materialfunctionusage)
- [StateId](ue_ue.MaterialFunctionInterface.md#stateid)
- [ThumbnailInfo](ue_ue.MaterialFunctionInterface.md#thumbnailinfo)
- [\_\_tid\_MaterialFunctionInterface\_\_](ue_ue.MaterialFunctionInterface.md#__tid_materialfunctioninterface__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialFunctionInterface.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialFunctionInterface.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialFunctionInterface.md#executeubergraph)
- [GetClass](ue_ue.MaterialFunctionInterface.md#getclass)
- [GetName](ue_ue.MaterialFunctionInterface.md#getname)
- [GetOuter](ue_ue.MaterialFunctionInterface.md#getouter)
- [GetWorld](ue_ue.MaterialFunctionInterface.md#getworld)
- [Find](ue_ue.MaterialFunctionInterface.md#find)
- [Load](ue_ue.MaterialFunctionInterface.md#load)
- [StaticClass](ue_ue.MaterialFunctionInterface.md#staticclass)

## Constructors

### constructor

• **new MaterialFunctionInterface**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:1092](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1092)

## Properties

### CombinedInputTypes

• **CombinedInputTypes**: `number`

#### Defined in

[ue/ue.d.ts:1095](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1095)

___

### CombinedOutputTypes

• **CombinedOutputTypes**: `number`

#### Defined in

[ue/ue.d.ts:1096](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1096)

___

### MaterialFunctionUsage

• **MaterialFunctionUsage**: [`EMaterialFunctionUsage`](../enums/ue_ue.EMaterialFunctionUsage.md)

#### Defined in

[ue/ue.d.ts:1094](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1094)

___

### StateId

• **StateId**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:1093](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1093)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Defined in

[ue/ue.d.ts:1097](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1097)

___

### \_\_tid\_MaterialFunctionInterface\_\_

• **\_\_tid\_MaterialFunctionInterface\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:1102](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1102)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialFunctionInterface`](ue_ue.MaterialFunctionInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialFunctionInterface`](ue_ue.MaterialFunctionInterface.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:1099](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1099)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialFunctionInterface`](ue_ue.MaterialFunctionInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialFunctionInterface`](ue_ue.MaterialFunctionInterface.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:1100](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1100)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:1098](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1098)
