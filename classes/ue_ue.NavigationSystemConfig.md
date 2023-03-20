[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavigationSystemConfig

# Class: NavigationSystemConfig

[ue/ue](../modules/ue_ue.md).NavigationSystemConfig

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`NavigationSystemConfig`**

  ↳↳ [`NavigationSystemModuleConfig`](ue_ue.NavigationSystemModuleConfig.md)

  ↳↳ [`NullNavSysConfig`](ue_ue.NullNavSysConfig.md)

## Table of contents

### Constructors

- [constructor](ue_ue.NavigationSystemConfig.md#constructor)

### Properties

- [DefaultAgentName](ue_ue.NavigationSystemConfig.md#defaultagentname)
- [NavigationSystemClass](ue_ue.NavigationSystemConfig.md#navigationsystemclass)
- [SupportedAgentsMask](ue_ue.NavigationSystemConfig.md#supportedagentsmask)
- [\_\_tid\_NavigationSystemConfig\_\_](ue_ue.NavigationSystemConfig.md#__tid_navigationsystemconfig__)
- [\_\_tid\_Object\_\_](ue_ue.NavigationSystemConfig.md#__tid_object__)
- [bIsOverriden](ue_ue.NavigationSystemConfig.md#bisoverriden)

### Methods

- [CreateDefaultSubobject](ue_ue.NavigationSystemConfig.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NavigationSystemConfig.md#executeubergraph)
- [GetClass](ue_ue.NavigationSystemConfig.md#getclass)
- [GetName](ue_ue.NavigationSystemConfig.md#getname)
- [GetOuter](ue_ue.NavigationSystemConfig.md#getouter)
- [GetWorld](ue_ue.NavigationSystemConfig.md#getworld)
- [Find](ue_ue.NavigationSystemConfig.md#find)
- [Load](ue_ue.NavigationSystemConfig.md#load)
- [StaticClass](ue_ue.NavigationSystemConfig.md#staticclass)

## Constructors

### constructor

• **new NavigationSystemConfig**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### DefaultAgentName

• **DefaultAgentName**: `string`

___

### NavigationSystemClass

• **NavigationSystemClass**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### SupportedAgentsMask

• **SupportedAgentsMask**: [`NavAgentSelector`](ue_ue.NavAgentSelector.md)

___

### \_\_tid\_NavigationSystemConfig\_\_

• **\_\_tid\_NavigationSystemConfig\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bIsOverriden

• **bIsOverriden**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NavigationSystemConfig`](ue_ue.NavigationSystemConfig.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NavigationSystemConfig`](ue_ue.NavigationSystemConfig.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`NavigationSystemConfig`](ue_ue.NavigationSystemConfig.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NavigationSystemConfig`](ue_ue.NavigationSystemConfig.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
