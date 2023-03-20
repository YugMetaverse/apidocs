[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LocalizationSettings

# Class: LocalizationSettings

[ue/ue](../modules/ue_ue.md).LocalizationSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LocalizationSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.LocalizationSettings.md#constructor)

### Properties

- [EngineTargetSet](ue_ue.LocalizationSettings.md#enginetargetset)
- [EngineTargetsSettings](ue_ue.LocalizationSettings.md#enginetargetssettings)
- [GameTargetSet](ue_ue.LocalizationSettings.md#gametargetset)
- [GameTargetsSettings](ue_ue.LocalizationSettings.md#gametargetssettings)
- [\_\_tid\_LocalizationSettings\_\_](ue_ue.LocalizationSettings.md#__tid_localizationsettings__)
- [\_\_tid\_Object\_\_](ue_ue.LocalizationSettings.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LocalizationSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LocalizationSettings.md#executeubergraph)
- [GetClass](ue_ue.LocalizationSettings.md#getclass)
- [GetName](ue_ue.LocalizationSettings.md#getname)
- [GetOuter](ue_ue.LocalizationSettings.md#getouter)
- [GetWorld](ue_ue.LocalizationSettings.md#getworld)
- [Find](ue_ue.LocalizationSettings.md#find)
- [Load](ue_ue.LocalizationSettings.md#load)
- [StaticClass](ue_ue.LocalizationSettings.md#staticclass)

## Constructors

### constructor

• **new LocalizationSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### EngineTargetSet

• **EngineTargetSet**: [`LocalizationTargetSet`](ue_ue.LocalizationTargetSet.md)

___

### EngineTargetsSettings

• **EngineTargetsSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LocalizationTargetSettings`](ue_ue.LocalizationTargetSettings.md)\>

___

### GameTargetSet

• **GameTargetSet**: [`LocalizationTargetSet`](ue_ue.LocalizationTargetSet.md)

___

### GameTargetsSettings

• **GameTargetsSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LocalizationTargetSettings`](ue_ue.LocalizationTargetSettings.md)\>

___

### \_\_tid\_LocalizationSettings\_\_

• **\_\_tid\_LocalizationSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LocalizationSettings`](ue_ue.LocalizationSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LocalizationSettings`](ue_ue.LocalizationSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LocalizationSettings`](ue_ue.LocalizationSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LocalizationSettings`](ue_ue.LocalizationSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
