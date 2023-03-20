[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavigationSystemModuleConfig

# Class: NavigationSystemModuleConfig

[ue/ue](../modules/ue_ue.md).NavigationSystemModuleConfig

## Hierarchy

- [`NavigationSystemConfig`](ue_ue.NavigationSystemConfig.md)

  ↳ **`NavigationSystemModuleConfig`**

## Table of contents

### Constructors

- [constructor](ue_ue.NavigationSystemModuleConfig.md#constructor)

### Properties

- [DefaultAgentName](ue_ue.NavigationSystemModuleConfig.md#defaultagentname)
- [NavigationSystemClass](ue_ue.NavigationSystemModuleConfig.md#navigationsystemclass)
- [SupportedAgentsMask](ue_ue.NavigationSystemModuleConfig.md#supportedagentsmask)
- [\_\_tid\_NavigationSystemConfig\_\_](ue_ue.NavigationSystemModuleConfig.md#__tid_navigationsystemconfig__)
- [\_\_tid\_NavigationSystemModuleConfig\_\_](ue_ue.NavigationSystemModuleConfig.md#__tid_navigationsystemmoduleconfig__)
- [\_\_tid\_Object\_\_](ue_ue.NavigationSystemModuleConfig.md#__tid_object__)
- [bAutoSpawnMissingNavData](ue_ue.NavigationSystemModuleConfig.md#bautospawnmissingnavdata)
- [bCreateOnClient](ue_ue.NavigationSystemModuleConfig.md#bcreateonclient)
- [bIsOverriden](ue_ue.NavigationSystemModuleConfig.md#bisoverriden)
- [bSpawnNavDataInNavBoundsLevel](ue_ue.NavigationSystemModuleConfig.md#bspawnnavdatainnavboundslevel)
- [bStrictlyStatic](ue_ue.NavigationSystemModuleConfig.md#bstrictlystatic)

### Methods

- [CreateDefaultSubobject](ue_ue.NavigationSystemModuleConfig.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NavigationSystemModuleConfig.md#executeubergraph)
- [GetClass](ue_ue.NavigationSystemModuleConfig.md#getclass)
- [GetName](ue_ue.NavigationSystemModuleConfig.md#getname)
- [GetOuter](ue_ue.NavigationSystemModuleConfig.md#getouter)
- [GetWorld](ue_ue.NavigationSystemModuleConfig.md#getworld)
- [Find](ue_ue.NavigationSystemModuleConfig.md#find)
- [Load](ue_ue.NavigationSystemModuleConfig.md#load)
- [StaticClass](ue_ue.NavigationSystemModuleConfig.md#staticclass)

## Constructors

### constructor

• **new NavigationSystemModuleConfig**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[constructor](ue_ue.NavigationSystemConfig.md#constructor)

## Properties

### DefaultAgentName

• **DefaultAgentName**: `string`

#### Inherited from

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[DefaultAgentName](ue_ue.NavigationSystemConfig.md#defaultagentname)

___

### NavigationSystemClass

• **NavigationSystemClass**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[NavigationSystemClass](ue_ue.NavigationSystemConfig.md#navigationsystemclass)

___

### SupportedAgentsMask

• **SupportedAgentsMask**: [`NavAgentSelector`](ue_ue.NavAgentSelector.md)

#### Inherited from

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[SupportedAgentsMask](ue_ue.NavigationSystemConfig.md#supportedagentsmask)

___

### \_\_tid\_NavigationSystemConfig\_\_

• **\_\_tid\_NavigationSystemConfig\_\_**: `boolean`

#### Inherited from

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[__tid_NavigationSystemConfig__](ue_ue.NavigationSystemConfig.md#__tid_navigationsystemconfig__)

___

### \_\_tid\_NavigationSystemModuleConfig\_\_

• **\_\_tid\_NavigationSystemModuleConfig\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[__tid_Object__](ue_ue.NavigationSystemConfig.md#__tid_object__)

___

### bAutoSpawnMissingNavData

• **bAutoSpawnMissingNavData**: `boolean`

___

### bCreateOnClient

• **bCreateOnClient**: `boolean`

___

### bIsOverriden

• **bIsOverriden**: `boolean`

#### Inherited from

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[bIsOverriden](ue_ue.NavigationSystemConfig.md#bisoverriden)

___

### bSpawnNavDataInNavBoundsLevel

• **bSpawnNavDataInNavBoundsLevel**: `boolean`

___

### bStrictlyStatic

• **bStrictlyStatic**: `boolean`

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

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[CreateDefaultSubobject](ue_ue.NavigationSystemConfig.md#createdefaultsubobject)

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

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[ExecuteUbergraph](ue_ue.NavigationSystemConfig.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[GetClass](ue_ue.NavigationSystemConfig.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[GetName](ue_ue.NavigationSystemConfig.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[GetOuter](ue_ue.NavigationSystemConfig.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[GetWorld](ue_ue.NavigationSystemConfig.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NavigationSystemModuleConfig`](ue_ue.NavigationSystemModuleConfig.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NavigationSystemModuleConfig`](ue_ue.NavigationSystemModuleConfig.md)

#### Overrides

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[Find](ue_ue.NavigationSystemConfig.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`NavigationSystemModuleConfig`](ue_ue.NavigationSystemModuleConfig.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NavigationSystemModuleConfig`](ue_ue.NavigationSystemModuleConfig.md)

#### Overrides

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[Load](ue_ue.NavigationSystemConfig.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NavigationSystemConfig](ue_ue.NavigationSystemConfig.md).[StaticClass](ue_ue.NavigationSystemConfig.md#staticclass)
