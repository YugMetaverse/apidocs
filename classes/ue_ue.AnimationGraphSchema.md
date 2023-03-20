[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimationGraphSchema

# Class: AnimationGraphSchema

[ue/ue](../modules/ue_ue.md).AnimationGraphSchema

## Hierarchy

- [`EdGraphSchema_K2`](ue_ue.EdGraphSchema_K2.md)

  ↳ **`AnimationGraphSchema`**

  ↳↳ [`AnimationCustomTransitionSchema`](ue_ue.AnimationCustomTransitionSchema.md)

  ↳↳ [`AnimationStateGraphSchema`](ue_ue.AnimationStateGraphSchema.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimationGraphSchema.md#constructor)

### Properties

- [DefaultEvaluationHandlerName](ue_ue.AnimationGraphSchema.md#defaultevaluationhandlername)
- [EditoronlyBPFunctionRedirects](ue_ue.AnimationGraphSchema.md#editoronlybpfunctionredirects)
- [NAME\_AlwaysAsPin](ue_ue.AnimationGraphSchema.md#name_alwaysaspin)
- [NAME\_CustomizeProperty](ue_ue.AnimationGraphSchema.md#name_customizeproperty)
- [NAME\_NeverAsPin](ue_ue.AnimationGraphSchema.md#name_neveraspin)
- [NAME\_OnEvaluate](ue_ue.AnimationGraphSchema.md#name_onevaluate)
- [NAME\_PinHiddenByDefault](ue_ue.AnimationGraphSchema.md#name_pinhiddenbydefault)
- [NAME\_PinShownByDefault](ue_ue.AnimationGraphSchema.md#name_pinshownbydefault)
- [PN\_SequenceName](ue_ue.AnimationGraphSchema.md#pn_sequencename)
- [\_\_tid\_AnimationGraphSchema\_\_](ue_ue.AnimationGraphSchema.md#__tid_animationgraphschema__)
- [\_\_tid\_EdGraphSchema\_K2\_\_](ue_ue.AnimationGraphSchema.md#__tid_edgraphschema_k2__)
- [\_\_tid\_EdGraphSchema\_\_](ue_ue.AnimationGraphSchema.md#__tid_edgraphschema__)
- [\_\_tid\_Object\_\_](ue_ue.AnimationGraphSchema.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimationGraphSchema.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimationGraphSchema.md#executeubergraph)
- [GetClass](ue_ue.AnimationGraphSchema.md#getclass)
- [GetName](ue_ue.AnimationGraphSchema.md#getname)
- [GetOuter](ue_ue.AnimationGraphSchema.md#getouter)
- [GetWorld](ue_ue.AnimationGraphSchema.md#getworld)
- [Find](ue_ue.AnimationGraphSchema.md#find)
- [Load](ue_ue.AnimationGraphSchema.md#load)
- [StaticClass](ue_ue.AnimationGraphSchema.md#staticclass)

## Constructors

### constructor

• **new AnimationGraphSchema**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[constructor](ue_ue.EdGraphSchema_K2.md#constructor)

#### Defined in

[ue/ue.d.ts:16874](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16874)

## Properties

### DefaultEvaluationHandlerName

• **DefaultEvaluationHandlerName**: `string`

#### Defined in

[ue/ue.d.ts:16882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16882)

___

### EditoronlyBPFunctionRedirects

• **EditoronlyBPFunctionRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlueprintCallableFunctionRedirect`](ue_ue.BlueprintCallableFunctionRedirect.md)\>

#### Inherited from

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[EditoronlyBPFunctionRedirects](ue_ue.EdGraphSchema_K2.md#editoronlybpfunctionredirects)

#### Defined in

[ue/ue.d.ts:16716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16716)

___

### NAME\_AlwaysAsPin

• **NAME\_AlwaysAsPin**: `string`

#### Defined in

[ue/ue.d.ts:16879](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16879)

___

### NAME\_CustomizeProperty

• **NAME\_CustomizeProperty**: `string`

#### Defined in

[ue/ue.d.ts:16880](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16880)

___

### NAME\_NeverAsPin

• **NAME\_NeverAsPin**: `string`

#### Defined in

[ue/ue.d.ts:16876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16876)

___

### NAME\_OnEvaluate

• **NAME\_OnEvaluate**: `string`

#### Defined in

[ue/ue.d.ts:16881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16881)

___

### NAME\_PinHiddenByDefault

• **NAME\_PinHiddenByDefault**: `string`

#### Defined in

[ue/ue.d.ts:16877](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16877)

___

### NAME\_PinShownByDefault

• **NAME\_PinShownByDefault**: `string`

#### Defined in

[ue/ue.d.ts:16878](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16878)

___

### PN\_SequenceName

• **PN\_SequenceName**: `string`

#### Defined in

[ue/ue.d.ts:16875](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16875)

___

### \_\_tid\_AnimationGraphSchema\_\_

• **\_\_tid\_AnimationGraphSchema\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:16887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16887)

___

### \_\_tid\_EdGraphSchema\_K2\_\_

• **\_\_tid\_EdGraphSchema\_K2\_\_**: `boolean`

#### Inherited from

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[__tid_EdGraphSchema_K2__](ue_ue.EdGraphSchema_K2.md#__tid_edgraphschema_k2__)

#### Defined in

[ue/ue.d.ts:16721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16721)

___

### \_\_tid\_EdGraphSchema\_\_

• **\_\_tid\_EdGraphSchema\_\_**: `boolean`

#### Inherited from

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[__tid_EdGraphSchema__](ue_ue.EdGraphSchema_K2.md#__tid_edgraphschema__)

#### Defined in

[ue/ue.d.ts:15138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15138)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[__tid_Object__](ue_ue.EdGraphSchema_K2.md#__tid_object__)

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

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[CreateDefaultSubobject](ue_ue.EdGraphSchema_K2.md#createdefaultsubobject)

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

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[ExecuteUbergraph](ue_ue.EdGraphSchema_K2.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[GetClass](ue_ue.EdGraphSchema_K2.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[GetName](ue_ue.EdGraphSchema_K2.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[GetOuter](ue_ue.EdGraphSchema_K2.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[GetWorld](ue_ue.EdGraphSchema_K2.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimationGraphSchema`](ue_ue.AnimationGraphSchema.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimationGraphSchema`](ue_ue.AnimationGraphSchema.md)

#### Overrides

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[Find](ue_ue.EdGraphSchema_K2.md#find)

#### Defined in

[ue/ue.d.ts:16884](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16884)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimationGraphSchema`](ue_ue.AnimationGraphSchema.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimationGraphSchema`](ue_ue.AnimationGraphSchema.md)

#### Overrides

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[Load](ue_ue.EdGraphSchema_K2.md#load)

#### Defined in

[ue/ue.d.ts:16885](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16885)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EdGraphSchema_K2](ue_ue.EdGraphSchema_K2.md).[StaticClass](ue_ue.EdGraphSchema_K2.md#staticclass)

#### Defined in

[ue/ue.d.ts:16883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16883)
