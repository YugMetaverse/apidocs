[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneEventBlueprintExtension

# Class: MovieSceneEventBlueprintExtension

[ue/ue](../modules/ue_ue.md).MovieSceneEventBlueprintExtension

## Hierarchy

- [`BlueprintExtension`](ue_ue.BlueprintExtension.md)

  ↳ **`MovieSceneEventBlueprintExtension`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneEventBlueprintExtension.md#constructor)

### Properties

- [EventSections](ue_ue.MovieSceneEventBlueprintExtension.md#eventsections)
- [\_\_tid\_BlueprintExtension\_\_](ue_ue.MovieSceneEventBlueprintExtension.md#__tid_blueprintextension__)
- [\_\_tid\_MovieSceneEventBlueprintExtension\_\_](ue_ue.MovieSceneEventBlueprintExtension.md#__tid_moviesceneeventblueprintextension__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneEventBlueprintExtension.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneEventBlueprintExtension.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneEventBlueprintExtension.md#executeubergraph)
- [GetClass](ue_ue.MovieSceneEventBlueprintExtension.md#getclass)
- [GetName](ue_ue.MovieSceneEventBlueprintExtension.md#getname)
- [GetOuter](ue_ue.MovieSceneEventBlueprintExtension.md#getouter)
- [GetWorld](ue_ue.MovieSceneEventBlueprintExtension.md#getworld)
- [Find](ue_ue.MovieSceneEventBlueprintExtension.md#find)
- [Load](ue_ue.MovieSceneEventBlueprintExtension.md#load)
- [StaticClass](ue_ue.MovieSceneEventBlueprintExtension.md#staticclass)

## Constructors

### constructor

• **new MovieSceneEventBlueprintExtension**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintExtension](ue_ue.BlueprintExtension.md).[constructor](ue_ue.BlueprintExtension.md#constructor)

## Properties

### EventSections

• **EventSections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneEventSectionBase`](ue_ue.MovieSceneEventSectionBase.md)\>

___

### \_\_tid\_BlueprintExtension\_\_

• **\_\_tid\_BlueprintExtension\_\_**: `boolean`

#### Inherited from

[BlueprintExtension](ue_ue.BlueprintExtension.md).[__tid_BlueprintExtension__](ue_ue.BlueprintExtension.md#__tid_blueprintextension__)

___

### \_\_tid\_MovieSceneEventBlueprintExtension\_\_

• **\_\_tid\_MovieSceneEventBlueprintExtension\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintExtension](ue_ue.BlueprintExtension.md).[__tid_Object__](ue_ue.BlueprintExtension.md#__tid_object__)

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

[BlueprintExtension](ue_ue.BlueprintExtension.md).[CreateDefaultSubobject](ue_ue.BlueprintExtension.md#createdefaultsubobject)

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

[BlueprintExtension](ue_ue.BlueprintExtension.md).[ExecuteUbergraph](ue_ue.BlueprintExtension.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintExtension](ue_ue.BlueprintExtension.md).[GetClass](ue_ue.BlueprintExtension.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintExtension](ue_ue.BlueprintExtension.md).[GetName](ue_ue.BlueprintExtension.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintExtension](ue_ue.BlueprintExtension.md).[GetOuter](ue_ue.BlueprintExtension.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintExtension](ue_ue.BlueprintExtension.md).[GetWorld](ue_ue.BlueprintExtension.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneEventBlueprintExtension`](ue_ue.MovieSceneEventBlueprintExtension.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneEventBlueprintExtension`](ue_ue.MovieSceneEventBlueprintExtension.md)

#### Overrides

[BlueprintExtension](ue_ue.BlueprintExtension.md).[Find](ue_ue.BlueprintExtension.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneEventBlueprintExtension`](ue_ue.MovieSceneEventBlueprintExtension.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneEventBlueprintExtension`](ue_ue.MovieSceneEventBlueprintExtension.md)

#### Overrides

[BlueprintExtension](ue_ue.BlueprintExtension.md).[Load](ue_ue.BlueprintExtension.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintExtension](ue_ue.BlueprintExtension.md).[StaticClass](ue_ue.BlueprintExtension.md#staticclass)
