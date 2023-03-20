[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelSequenceEditorBlueprintLibrary

# Class: LevelSequenceEditorBlueprintLibrary

[ue/ue](../modules/ue_ue.md).LevelSequenceEditorBlueprintLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`LevelSequenceEditorBlueprintLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelSequenceEditorBlueprintLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.LevelSequenceEditorBlueprintLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_LevelSequenceEditorBlueprintLibrary\_\_](ue_ue.LevelSequenceEditorBlueprintLibrary.md#__tid_levelsequenceeditorblueprintlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.LevelSequenceEditorBlueprintLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LevelSequenceEditorBlueprintLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LevelSequenceEditorBlueprintLibrary.md#executeubergraph)
- [GetClass](ue_ue.LevelSequenceEditorBlueprintLibrary.md#getclass)
- [GetName](ue_ue.LevelSequenceEditorBlueprintLibrary.md#getname)
- [GetOuter](ue_ue.LevelSequenceEditorBlueprintLibrary.md#getouter)
- [GetWorld](ue_ue.LevelSequenceEditorBlueprintLibrary.md#getworld)
- [CloseLevelSequence](ue_ue.LevelSequenceEditorBlueprintLibrary.md#closelevelsequence)
- [Find](ue_ue.LevelSequenceEditorBlueprintLibrary.md#find)
- [GetCurrentLevelSequence](ue_ue.LevelSequenceEditorBlueprintLibrary.md#getcurrentlevelsequence)
- [GetCurrentTime](ue_ue.LevelSequenceEditorBlueprintLibrary.md#getcurrenttime)
- [IsLevelSequenceLocked](ue_ue.LevelSequenceEditorBlueprintLibrary.md#islevelsequencelocked)
- [IsPlaying](ue_ue.LevelSequenceEditorBlueprintLibrary.md#isplaying)
- [Load](ue_ue.LevelSequenceEditorBlueprintLibrary.md#load)
- [OpenLevelSequence](ue_ue.LevelSequenceEditorBlueprintLibrary.md#openlevelsequence)
- [Pause](ue_ue.LevelSequenceEditorBlueprintLibrary.md#pause)
- [Play](ue_ue.LevelSequenceEditorBlueprintLibrary.md#play)
- [SetCurrentTime](ue_ue.LevelSequenceEditorBlueprintLibrary.md#setcurrenttime)
- [SetLockLevelSequence](ue_ue.LevelSequenceEditorBlueprintLibrary.md#setlocklevelsequence)
- [StaticClass](ue_ue.LevelSequenceEditorBlueprintLibrary.md#staticclass)

## Constructors

### constructor

• **new LevelSequenceEditorBlueprintLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:45186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45186)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_LevelSequenceEditorBlueprintLibrary\_\_

• **\_\_tid\_LevelSequenceEditorBlueprintLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:45201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45201)

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

### CloseLevelSequence

▸ `Static` **CloseLevelSequence**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:45187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45187)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelSequenceEditorBlueprintLibrary`](ue_ue.LevelSequenceEditorBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelSequenceEditorBlueprintLibrary`](ue_ue.LevelSequenceEditorBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:45198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45198)

___

### GetCurrentLevelSequence

▸ `Static` **GetCurrentLevelSequence**(): [`LevelSequence`](ue_ue.LevelSequence.md)

#### Returns

[`LevelSequence`](ue_ue.LevelSequence.md)

#### Defined in

[ue/ue.d.ts:45188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45188)

___

### GetCurrentTime

▸ `Static` **GetCurrentTime**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:45189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45189)

___

### IsLevelSequenceLocked

▸ `Static` **IsLevelSequenceLocked**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:45190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45190)

___

### IsPlaying

▸ `Static` **IsPlaying**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:45191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45191)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelSequenceEditorBlueprintLibrary`](ue_ue.LevelSequenceEditorBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelSequenceEditorBlueprintLibrary`](ue_ue.LevelSequenceEditorBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:45199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45199)

___

### OpenLevelSequence

▸ `Static` **OpenLevelSequence**(`LevelSequence`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LevelSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`LevelSequence`](ue_ue.LevelSequence.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:45192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45192)

___

### Pause

▸ `Static` **Pause**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:45193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45193)

___

### Play

▸ `Static` **Play**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:45194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45194)

___

### SetCurrentTime

▸ `Static` **SetCurrentTime**(`NewFrame`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewFrame` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:45195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45195)

___

### SetLockLevelSequence

▸ `Static` **SetLockLevelSequence**(`bLock`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bLock` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:45196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45196)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:45197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45197)
