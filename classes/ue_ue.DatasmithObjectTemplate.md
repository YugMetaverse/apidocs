[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithObjectTemplate

# Class: DatasmithObjectTemplate

[ue/ue](../modules/ue_ue.md).DatasmithObjectTemplate

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`DatasmithObjectTemplate`**

  ↳↳ [`DatasmithActorTemplate`](ue_ue.DatasmithActorTemplate.md)

  ↳↳ [`DatasmithAreaLightActorTemplate`](ue_ue.DatasmithAreaLightActorTemplate.md)

  ↳↳ [`DatasmithCineCameraActorTemplate`](ue_ue.DatasmithCineCameraActorTemplate.md)

  ↳↳ [`DatasmithCineCameraComponentTemplate`](ue_ue.DatasmithCineCameraComponentTemplate.md)

  ↳↳ [`DatasmithLandscapeTemplate`](ue_ue.DatasmithLandscapeTemplate.md)

  ↳↳ [`DatasmithLightComponentTemplate`](ue_ue.DatasmithLightComponentTemplate.md)

  ↳↳ [`DatasmithMaterialInstanceTemplate`](ue_ue.DatasmithMaterialInstanceTemplate.md)

  ↳↳ [`DatasmithPointLightComponentTemplate`](ue_ue.DatasmithPointLightComponentTemplate.md)

  ↳↳ [`DatasmithPostProcessVolumeTemplate`](ue_ue.DatasmithPostProcessVolumeTemplate.md)

  ↳↳ [`DatasmithSceneComponentTemplate`](ue_ue.DatasmithSceneComponentTemplate.md)

  ↳↳ [`DatasmithSkyLightComponentTemplate`](ue_ue.DatasmithSkyLightComponentTemplate.md)

  ↳↳ [`DatasmithSpotLightComponentTemplate`](ue_ue.DatasmithSpotLightComponentTemplate.md)

  ↳↳ [`DatasmithStaticMeshComponentTemplate`](ue_ue.DatasmithStaticMeshComponentTemplate.md)

  ↳↳ [`DatasmithStaticMeshTemplate`](ue_ue.DatasmithStaticMeshTemplate.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithObjectTemplate.md#constructor)

### Properties

- [\_\_tid\_DatasmithObjectTemplate\_\_](ue_ue.DatasmithObjectTemplate.md#__tid_datasmithobjecttemplate__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithObjectTemplate.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithObjectTemplate.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithObjectTemplate.md#executeubergraph)
- [GetClass](ue_ue.DatasmithObjectTemplate.md#getclass)
- [GetName](ue_ue.DatasmithObjectTemplate.md#getname)
- [GetOuter](ue_ue.DatasmithObjectTemplate.md#getouter)
- [GetWorld](ue_ue.DatasmithObjectTemplate.md#getworld)
- [Find](ue_ue.DatasmithObjectTemplate.md#find)
- [Load](ue_ue.DatasmithObjectTemplate.md#load)
- [StaticClass](ue_ue.DatasmithObjectTemplate.md#staticclass)

## Constructors

### constructor

• **new DatasmithObjectTemplate**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_DatasmithObjectTemplate\_\_

• **\_\_tid\_DatasmithObjectTemplate\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithObjectTemplate`](ue_ue.DatasmithObjectTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithObjectTemplate`](ue_ue.DatasmithObjectTemplate.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithObjectTemplate`](ue_ue.DatasmithObjectTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithObjectTemplate`](ue_ue.DatasmithObjectTemplate.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
