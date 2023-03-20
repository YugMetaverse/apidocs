[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LiveCodingSettings

# Class: LiveCodingSettings

[ue/ue](../modules/ue_ue.md).LiveCodingSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LiveCodingSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.LiveCodingSettings.md#constructor)

### Properties

- [PreloadNamedModules](ue_ue.LiveCodingSettings.md#preloadnamedmodules)
- [Startup](ue_ue.LiveCodingSettings.md#startup)
- [\_\_tid\_LiveCodingSettings\_\_](ue_ue.LiveCodingSettings.md#__tid_livecodingsettings__)
- [\_\_tid\_Object\_\_](ue_ue.LiveCodingSettings.md#__tid_object__)
- [bEnabled](ue_ue.LiveCodingSettings.md#benabled)
- [bPreloadEngineModules](ue_ue.LiveCodingSettings.md#bpreloadenginemodules)
- [bPreloadEnginePluginModules](ue_ue.LiveCodingSettings.md#bpreloadenginepluginmodules)
- [bPreloadProjectModules](ue_ue.LiveCodingSettings.md#bpreloadprojectmodules)
- [bPreloadProjectPluginModules](ue_ue.LiveCodingSettings.md#bpreloadprojectpluginmodules)

### Methods

- [CreateDefaultSubobject](ue_ue.LiveCodingSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LiveCodingSettings.md#executeubergraph)
- [GetClass](ue_ue.LiveCodingSettings.md#getclass)
- [GetName](ue_ue.LiveCodingSettings.md#getname)
- [GetOuter](ue_ue.LiveCodingSettings.md#getouter)
- [GetWorld](ue_ue.LiveCodingSettings.md#getworld)
- [Find](ue_ue.LiveCodingSettings.md#find)
- [Load](ue_ue.LiveCodingSettings.md#load)
- [StaticClass](ue_ue.LiveCodingSettings.md#staticclass)

## Constructors

### constructor

• **new LiveCodingSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:45729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45729)

## Properties

### PreloadNamedModules

• **PreloadNamedModules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:45736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45736)

___

### Startup

• **Startup**: [`ELiveCodingStartupMode`](../enums/ue_ue.ELiveCodingStartupMode.md)

#### Defined in

[ue/ue.d.ts:45731](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45731)

___

### \_\_tid\_LiveCodingSettings\_\_

• **\_\_tid\_LiveCodingSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:45741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45741)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bEnabled

• **bEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:45730](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45730)

___

### bPreloadEngineModules

• **bPreloadEngineModules**: `boolean`

#### Defined in

[ue/ue.d.ts:45732](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45732)

___

### bPreloadEnginePluginModules

• **bPreloadEnginePluginModules**: `boolean`

#### Defined in

[ue/ue.d.ts:45733](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45733)

___

### bPreloadProjectModules

• **bPreloadProjectModules**: `boolean`

#### Defined in

[ue/ue.d.ts:45734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45734)

___

### bPreloadProjectPluginModules

• **bPreloadProjectPluginModules**: `boolean`

#### Defined in

[ue/ue.d.ts:45735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45735)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LiveCodingSettings`](ue_ue.LiveCodingSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LiveCodingSettings`](ue_ue.LiveCodingSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:45738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45738)

___

### Load

▸ `Static` **Load**(`InName`): [`LiveCodingSettings`](ue_ue.LiveCodingSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LiveCodingSettings`](ue_ue.LiveCodingSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:45739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45739)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:45737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45737)
