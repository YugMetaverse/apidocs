[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetToolsSettings

# Class: AssetToolsSettings

[ue/ue](../modules/ue_ue.md).AssetToolsSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`AssetToolsSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.AssetToolsSettings.md#constructor)

### Properties

- [AdvancedCopyCustomizations](ue_ue.AssetToolsSettings.md#advancedcopycustomizations)
- [\_\_tid\_AssetToolsSettings\_\_](ue_ue.AssetToolsSettings.md#__tid_assettoolssettings__)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.AssetToolsSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.AssetToolsSettings.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AssetToolsSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AssetToolsSettings.md#executeubergraph)
- [GetClass](ue_ue.AssetToolsSettings.md#getclass)
- [GetName](ue_ue.AssetToolsSettings.md#getname)
- [GetOuter](ue_ue.AssetToolsSettings.md#getouter)
- [GetWorld](ue_ue.AssetToolsSettings.md#getworld)
- [Find](ue_ue.AssetToolsSettings.md#find)
- [Load](ue_ue.AssetToolsSettings.md#load)
- [StaticClass](ue_ue.AssetToolsSettings.md#staticclass)

## Constructors

### constructor

• **new AssetToolsSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### AdvancedCopyCustomizations

• **AdvancedCopyCustomizations**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AdvancedCopyMap`](ue_ue.AdvancedCopyMap.md)\>

___

### \_\_tid\_AssetToolsSettings\_\_

• **\_\_tid\_AssetToolsSettings\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AssetToolsSettings`](ue_ue.AssetToolsSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AssetToolsSettings`](ue_ue.AssetToolsSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AssetToolsSettings`](ue_ue.AssetToolsSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AssetToolsSettings`](ue_ue.AssetToolsSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
