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

#### Defined in

[ue/ue.d.ts:8698](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8698)

## Properties

### DefaultAgentName

• **DefaultAgentName**: `string`

#### Defined in

[ue/ue.d.ts:8701](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8701)

___

### NavigationSystemClass

• **NavigationSystemClass**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:8699](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8699)

___

### SupportedAgentsMask

• **SupportedAgentsMask**: [`NavAgentSelector`](ue_ue.NavAgentSelector.md)

#### Defined in

[ue/ue.d.ts:8700](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8700)

___

### \_\_tid\_NavigationSystemConfig\_\_

• **\_\_tid\_NavigationSystemConfig\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:8707](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8707)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bIsOverriden

• **bIsOverriden**: `boolean`

#### Defined in

[ue/ue.d.ts:8702](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8702)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:8704](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8704)

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

#### Defined in

[ue/ue.d.ts:8705](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8705)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:8703](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8703)
