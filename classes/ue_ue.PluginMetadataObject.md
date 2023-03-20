[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PluginMetadataObject

# Class: PluginMetadataObject

[ue/ue](../modules/ue_ue.md).PluginMetadataObject

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PluginMetadataObject`**

## Table of contents

### Constructors

- [constructor](ue_ue.PluginMetadataObject.md#constructor)

### Properties

- [Category](ue_ue.PluginMetadataObject.md#category)
- [CreatedBy](ue_ue.PluginMetadataObject.md#createdby)
- [CreatedByURL](ue_ue.PluginMetadataObject.md#createdbyurl)
- [Description](ue_ue.PluginMetadataObject.md#description)
- [DocsURL](ue_ue.PluginMetadataObject.md#docsurl)
- [FriendlyName](ue_ue.PluginMetadataObject.md#friendlyname)
- [MarketplaceURL](ue_ue.PluginMetadataObject.md#marketplaceurl)
- [SupportURL](ue_ue.PluginMetadataObject.md#supporturl)
- [Version](ue_ue.PluginMetadataObject.md#version)
- [VersionName](ue_ue.PluginMetadataObject.md#versionname)
- [\_\_tid\_Object\_\_](ue_ue.PluginMetadataObject.md#__tid_object__)
- [\_\_tid\_PluginMetadataObject\_\_](ue_ue.PluginMetadataObject.md#__tid_pluginmetadataobject__)
- [bCanContainContent](ue_ue.PluginMetadataObject.md#bcancontaincontent)
- [bIsBetaVersion](ue_ue.PluginMetadataObject.md#bisbetaversion)

### Methods

- [CreateDefaultSubobject](ue_ue.PluginMetadataObject.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PluginMetadataObject.md#executeubergraph)
- [GetClass](ue_ue.PluginMetadataObject.md#getclass)
- [GetName](ue_ue.PluginMetadataObject.md#getname)
- [GetOuter](ue_ue.PluginMetadataObject.md#getouter)
- [GetWorld](ue_ue.PluginMetadataObject.md#getworld)
- [Find](ue_ue.PluginMetadataObject.md#find)
- [Load](ue_ue.PluginMetadataObject.md#load)
- [StaticClass](ue_ue.PluginMetadataObject.md#staticclass)

## Constructors

### constructor

• **new PluginMetadataObject**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Category

• **Category**: `string`

___

### CreatedBy

• **CreatedBy**: `string`

___

### CreatedByURL

• **CreatedByURL**: `string`

___

### Description

• **Description**: `string`

___

### DocsURL

• **DocsURL**: `string`

___

### FriendlyName

• **FriendlyName**: `string`

___

### MarketplaceURL

• **MarketplaceURL**: `string`

___

### SupportURL

• **SupportURL**: `string`

___

### Version

• **Version**: `number`

___

### VersionName

• **VersionName**: `string`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PluginMetadataObject\_\_

• **\_\_tid\_PluginMetadataObject\_\_**: `boolean`

___

### bCanContainContent

• **bCanContainContent**: `boolean`

___

### bIsBetaVersion

• **bIsBetaVersion**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PluginMetadataObject`](ue_ue.PluginMetadataObject.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PluginMetadataObject`](ue_ue.PluginMetadataObject.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PluginMetadataObject`](ue_ue.PluginMetadataObject.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PluginMetadataObject`](ue_ue.PluginMetadataObject.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
