[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ActorFactoryDeferredDecal

# Class: ActorFactoryDeferredDecal

[ue/ue](../modules/ue_ue.md).ActorFactoryDeferredDecal

## Hierarchy

- [`ActorFactory`](ue_ue.ActorFactory.md)

  ↳ **`ActorFactoryDeferredDecal`**

## Table of contents

### Constructors

- [constructor](ue_ue.ActorFactoryDeferredDecal.md#constructor)

### Properties

- [DisplayName](ue_ue.ActorFactoryDeferredDecal.md#displayname)
- [MenuPriority](ue_ue.ActorFactoryDeferredDecal.md#menupriority)
- [NewActorClass](ue_ue.ActorFactoryDeferredDecal.md#newactorclass)
- [NewActorClassName](ue_ue.ActorFactoryDeferredDecal.md#newactorclassname)
- [SpawnPositionOffset](ue_ue.ActorFactoryDeferredDecal.md#spawnpositionoffset)
- [\_\_tid\_ActorFactoryDeferredDecal\_\_](ue_ue.ActorFactoryDeferredDecal.md#__tid_actorfactorydeferreddecal__)
- [\_\_tid\_ActorFactory\_\_](ue_ue.ActorFactoryDeferredDecal.md#__tid_actorfactory__)
- [\_\_tid\_Object\_\_](ue_ue.ActorFactoryDeferredDecal.md#__tid_object__)
- [bShowInEditorQuickMenu](ue_ue.ActorFactoryDeferredDecal.md#bshowineditorquickmenu)
- [bUseSurfaceOrientation](ue_ue.ActorFactoryDeferredDecal.md#busesurfaceorientation)

### Methods

- [CreateDefaultSubobject](ue_ue.ActorFactoryDeferredDecal.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ActorFactoryDeferredDecal.md#executeubergraph)
- [GetClass](ue_ue.ActorFactoryDeferredDecal.md#getclass)
- [GetName](ue_ue.ActorFactoryDeferredDecal.md#getname)
- [GetOuter](ue_ue.ActorFactoryDeferredDecal.md#getouter)
- [GetWorld](ue_ue.ActorFactoryDeferredDecal.md#getworld)
- [Find](ue_ue.ActorFactoryDeferredDecal.md#find)
- [Load](ue_ue.ActorFactoryDeferredDecal.md#load)
- [StaticClass](ue_ue.ActorFactoryDeferredDecal.md#staticclass)

## Constructors

### constructor

• **new ActorFactoryDeferredDecal**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ActorFactory](ue_ue.ActorFactory.md).[constructor](ue_ue.ActorFactory.md#constructor)

## Properties

### DisplayName

• **DisplayName**: `string`

#### Inherited from

[ActorFactory](ue_ue.ActorFactory.md).[DisplayName](ue_ue.ActorFactory.md#displayname)

___

### MenuPriority

• **MenuPriority**: `number`

#### Inherited from

[ActorFactory](ue_ue.ActorFactory.md).[MenuPriority](ue_ue.ActorFactory.md#menupriority)

___

### NewActorClass

• **NewActorClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[ActorFactory](ue_ue.ActorFactory.md).[NewActorClass](ue_ue.ActorFactory.md#newactorclass)

___

### NewActorClassName

• **NewActorClassName**: `string`

#### Inherited from

[ActorFactory](ue_ue.ActorFactory.md).[NewActorClassName](ue_ue.ActorFactory.md#newactorclassname)

___

### SpawnPositionOffset

• **SpawnPositionOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ActorFactory](ue_ue.ActorFactory.md).[SpawnPositionOffset](ue_ue.ActorFactory.md#spawnpositionoffset)

___

### \_\_tid\_ActorFactoryDeferredDecal\_\_

• **\_\_tid\_ActorFactoryDeferredDecal\_\_**: `boolean`

___

### \_\_tid\_ActorFactory\_\_

• **\_\_tid\_ActorFactory\_\_**: `boolean`

#### Inherited from

[ActorFactory](ue_ue.ActorFactory.md).[__tid_ActorFactory__](ue_ue.ActorFactory.md#__tid_actorfactory__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ActorFactory](ue_ue.ActorFactory.md).[__tid_Object__](ue_ue.ActorFactory.md#__tid_object__)

___

### bShowInEditorQuickMenu

• **bShowInEditorQuickMenu**: `boolean`

#### Inherited from

[ActorFactory](ue_ue.ActorFactory.md).[bShowInEditorQuickMenu](ue_ue.ActorFactory.md#bshowineditorquickmenu)

___

### bUseSurfaceOrientation

• **bUseSurfaceOrientation**: `boolean`

#### Inherited from

[ActorFactory](ue_ue.ActorFactory.md).[bUseSurfaceOrientation](ue_ue.ActorFactory.md#busesurfaceorientation)

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

[ActorFactory](ue_ue.ActorFactory.md).[CreateDefaultSubobject](ue_ue.ActorFactory.md#createdefaultsubobject)

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

[ActorFactory](ue_ue.ActorFactory.md).[ExecuteUbergraph](ue_ue.ActorFactory.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ActorFactory](ue_ue.ActorFactory.md).[GetClass](ue_ue.ActorFactory.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ActorFactory](ue_ue.ActorFactory.md).[GetName](ue_ue.ActorFactory.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ActorFactory](ue_ue.ActorFactory.md).[GetOuter](ue_ue.ActorFactory.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ActorFactory](ue_ue.ActorFactory.md).[GetWorld](ue_ue.ActorFactory.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ActorFactoryDeferredDecal`](ue_ue.ActorFactoryDeferredDecal.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ActorFactoryDeferredDecal`](ue_ue.ActorFactoryDeferredDecal.md)

#### Overrides

[ActorFactory](ue_ue.ActorFactory.md).[Find](ue_ue.ActorFactory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ActorFactoryDeferredDecal`](ue_ue.ActorFactoryDeferredDecal.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ActorFactoryDeferredDecal`](ue_ue.ActorFactoryDeferredDecal.md)

#### Overrides

[ActorFactory](ue_ue.ActorFactory.md).[Load](ue_ue.ActorFactory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorFactory](ue_ue.ActorFactory.md).[StaticClass](ue_ue.ActorFactory.md#staticclass)
