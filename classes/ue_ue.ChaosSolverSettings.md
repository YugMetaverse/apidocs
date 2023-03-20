[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ChaosSolverSettings

# Class: ChaosSolverSettings

[ue/ue](../modules/ue_ue.md).ChaosSolverSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`ChaosSolverSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.ChaosSolverSettings.md#constructor)

### Properties

- [DefaultChaosSolverActorClass](ue_ue.ChaosSolverSettings.md#defaultchaossolveractorclass)
- [\_\_tid\_ChaosSolverSettings\_\_](ue_ue.ChaosSolverSettings.md#__tid_chaossolversettings__)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.ChaosSolverSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.ChaosSolverSettings.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ChaosSolverSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ChaosSolverSettings.md#executeubergraph)
- [GetClass](ue_ue.ChaosSolverSettings.md#getclass)
- [GetName](ue_ue.ChaosSolverSettings.md#getname)
- [GetOuter](ue_ue.ChaosSolverSettings.md#getouter)
- [GetWorld](ue_ue.ChaosSolverSettings.md#getworld)
- [Find](ue_ue.ChaosSolverSettings.md#find)
- [Load](ue_ue.ChaosSolverSettings.md#load)
- [StaticClass](ue_ue.ChaosSolverSettings.md#staticclass)

## Constructors

### constructor

• **new ChaosSolverSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### DefaultChaosSolverActorClass

• **DefaultChaosSolverActorClass**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### \_\_tid\_ChaosSolverSettings\_\_

• **\_\_tid\_ChaosSolverSettings\_\_**: `boolean`

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ChaosSolverSettings`](ue_ue.ChaosSolverSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ChaosSolverSettings`](ue_ue.ChaosSolverSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ChaosSolverSettings`](ue_ue.ChaosSolverSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ChaosSolverSettings`](ue_ue.ChaosSolverSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
