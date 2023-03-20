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

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_LevelSequenceEditorBlueprintLibrary\_\_

• **\_\_tid\_LevelSequenceEditorBlueprintLibrary\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### CloseLevelSequence

▸ `Static` **CloseLevelSequence**(): `void`

#### Returns

`void`

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

___

### GetCurrentLevelSequence

▸ `Static` **GetCurrentLevelSequence**(): [`LevelSequence`](ue_ue.LevelSequence.md)

#### Returns

[`LevelSequence`](ue_ue.LevelSequence.md)

___

### GetCurrentTime

▸ `Static` **GetCurrentTime**(): `number`

#### Returns

`number`

___

### IsLevelSequenceLocked

▸ `Static` **IsLevelSequenceLocked**(): `boolean`

#### Returns

`boolean`

___

### IsPlaying

▸ `Static` **IsPlaying**(): `boolean`

#### Returns

`boolean`

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

___

### OpenLevelSequence

▸ `Static` **OpenLevelSequence**(`LevelSequence`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LevelSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`LevelSequence`](ue_ue.LevelSequence.md)\> |

#### Returns

`boolean`

___

### Pause

▸ `Static` **Pause**(): `void`

#### Returns

`void`

___

### Play

▸ `Static` **Play**(): `void`

#### Returns

`void`

___

### SetCurrentTime

▸ `Static` **SetCurrentTime**(`NewFrame`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewFrame` | `number` |

#### Returns

`void`

___

### SetLockLevelSequence

▸ `Static` **SetLockLevelSequence**(`bLock`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bLock` | `boolean` |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
