[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RendererOverrideSettings

# Class: RendererOverrideSettings

[ue/ue](../modules/ue_ue.md).RendererOverrideSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`RendererOverrideSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.RendererOverrideSettings.md#constructor)

### Properties

- [\_\_tid\_DeveloperSettings\_\_](ue_ue.RendererOverrideSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.RendererOverrideSettings.md#__tid_object__)
- [\_\_tid\_RendererOverrideSettings\_\_](ue_ue.RendererOverrideSettings.md#__tid_rendereroverridesettings__)
- [bForceRecomputeTangents](ue_ue.RendererOverrideSettings.md#bforcerecomputetangents)
- [bSupportAllShaderPermutations](ue_ue.RendererOverrideSettings.md#bsupportallshaderpermutations)

### Methods

- [CreateDefaultSubobject](ue_ue.RendererOverrideSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.RendererOverrideSettings.md#executeubergraph)
- [GetClass](ue_ue.RendererOverrideSettings.md#getclass)
- [GetName](ue_ue.RendererOverrideSettings.md#getname)
- [GetOuter](ue_ue.RendererOverrideSettings.md#getouter)
- [GetWorld](ue_ue.RendererOverrideSettings.md#getworld)
- [Find](ue_ue.RendererOverrideSettings.md#find)
- [Load](ue_ue.RendererOverrideSettings.md#load)
- [StaticClass](ue_ue.RendererOverrideSettings.md#staticclass)

## Constructors

### constructor

• **new RendererOverrideSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### \_\_tid\_RendererOverrideSettings\_\_

• **\_\_tid\_RendererOverrideSettings\_\_**: `boolean`

___

### bForceRecomputeTangents

• **bForceRecomputeTangents**: `boolean`

___

### bSupportAllShaderPermutations

• **bSupportAllShaderPermutations**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`RendererOverrideSettings`](ue_ue.RendererOverrideSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`RendererOverrideSettings`](ue_ue.RendererOverrideSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`RendererOverrideSettings`](ue_ue.RendererOverrideSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`RendererOverrideSettings`](ue_ue.RendererOverrideSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
