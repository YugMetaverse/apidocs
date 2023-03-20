[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorTutorialSettings

# Class: EditorTutorialSettings

[ue/ue](../modules/ue_ue.md).EditorTutorialSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EditorTutorialSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorTutorialSettings.md#constructor)

### Properties

- [Categories](ue_ue.EditorTutorialSettings.md#categories)
- [StartupTutorial](ue_ue.EditorTutorialSettings.md#startuptutorial)
- [TutorialContexts](ue_ue.EditorTutorialSettings.md#tutorialcontexts)
- [\_\_tid\_EditorTutorialSettings\_\_](ue_ue.EditorTutorialSettings.md#__tid_editortutorialsettings__)
- [\_\_tid\_Object\_\_](ue_ue.EditorTutorialSettings.md#__tid_object__)
- [bDisableAllTutorialAlerts](ue_ue.EditorTutorialSettings.md#bdisablealltutorialalerts)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorTutorialSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorTutorialSettings.md#executeubergraph)
- [GetClass](ue_ue.EditorTutorialSettings.md#getclass)
- [GetName](ue_ue.EditorTutorialSettings.md#getname)
- [GetOuter](ue_ue.EditorTutorialSettings.md#getouter)
- [GetWorld](ue_ue.EditorTutorialSettings.md#getworld)
- [Find](ue_ue.EditorTutorialSettings.md#find)
- [Load](ue_ue.EditorTutorialSettings.md#load)
- [StaticClass](ue_ue.EditorTutorialSettings.md#staticclass)

## Constructors

### constructor

• **new EditorTutorialSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Categories

• **Categories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TutorialCategory`](ue_ue.TutorialCategory.md)\>

___

### StartupTutorial

• **StartupTutorial**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### TutorialContexts

• **TutorialContexts**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TutorialContext`](ue_ue.TutorialContext.md)\>

___

### \_\_tid\_EditorTutorialSettings\_\_

• **\_\_tid\_EditorTutorialSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bDisableAllTutorialAlerts

• **bDisableAllTutorialAlerts**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorTutorialSettings`](ue_ue.EditorTutorialSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorTutorialSettings`](ue_ue.EditorTutorialSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorTutorialSettings`](ue_ue.EditorTutorialSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorTutorialSettings`](ue_ue.EditorTutorialSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
