[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithLightComponentTemplate

# Class: DatasmithLightComponentTemplate

[ue/ue](../modules/ue_ue.md).DatasmithLightComponentTemplate

## Hierarchy

- [`DatasmithObjectTemplate`](ue_ue.DatasmithObjectTemplate.md)

  ↳ **`DatasmithLightComponentTemplate`**

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithLightComponentTemplate.md#constructor)

### Properties

- [CastShadows](ue_ue.DatasmithLightComponentTemplate.md#castshadows)
- [IESBrightnessScale](ue_ue.DatasmithLightComponentTemplate.md#iesbrightnessscale)
- [IESTexture](ue_ue.DatasmithLightComponentTemplate.md#iestexture)
- [Intensity](ue_ue.DatasmithLightComponentTemplate.md#intensity)
- [LightColor](ue_ue.DatasmithLightComponentTemplate.md#lightcolor)
- [LightFunctionMaterial](ue_ue.DatasmithLightComponentTemplate.md#lightfunctionmaterial)
- [Temperature](ue_ue.DatasmithLightComponentTemplate.md#temperature)
- [\_\_tid\_DatasmithLightComponentTemplate\_\_](ue_ue.DatasmithLightComponentTemplate.md#__tid_datasmithlightcomponenttemplate__)
- [\_\_tid\_DatasmithObjectTemplate\_\_](ue_ue.DatasmithLightComponentTemplate.md#__tid_datasmithobjecttemplate__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithLightComponentTemplate.md#__tid_object__)
- [bUseIESBrightness](ue_ue.DatasmithLightComponentTemplate.md#buseiesbrightness)
- [bUseTemperature](ue_ue.DatasmithLightComponentTemplate.md#busetemperature)
- [bVisible](ue_ue.DatasmithLightComponentTemplate.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithLightComponentTemplate.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithLightComponentTemplate.md#executeubergraph)
- [GetClass](ue_ue.DatasmithLightComponentTemplate.md#getclass)
- [GetName](ue_ue.DatasmithLightComponentTemplate.md#getname)
- [GetOuter](ue_ue.DatasmithLightComponentTemplate.md#getouter)
- [GetWorld](ue_ue.DatasmithLightComponentTemplate.md#getworld)
- [Find](ue_ue.DatasmithLightComponentTemplate.md#find)
- [Load](ue_ue.DatasmithLightComponentTemplate.md#load)
- [StaticClass](ue_ue.DatasmithLightComponentTemplate.md#staticclass)

## Constructors

### constructor

• **new DatasmithLightComponentTemplate**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[constructor](ue_ue.DatasmithObjectTemplate.md#constructor)

## Properties

### CastShadows

• **CastShadows**: `boolean`

___

### IESBrightnessScale

• **IESBrightnessScale**: `number`

___

### IESTexture

• **IESTexture**: [`TextureLightProfile`](ue_ue.TextureLightProfile.md)

___

### Intensity

• **Intensity**: `number`

___

### LightColor

• **LightColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### LightFunctionMaterial

• **LightFunctionMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### Temperature

• **Temperature**: `number`

___

### \_\_tid\_DatasmithLightComponentTemplate\_\_

• **\_\_tid\_DatasmithLightComponentTemplate\_\_**: `boolean`

___

### \_\_tid\_DatasmithObjectTemplate\_\_

• **\_\_tid\_DatasmithObjectTemplate\_\_**: `boolean`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[__tid_DatasmithObjectTemplate__](ue_ue.DatasmithObjectTemplate.md#__tid_datasmithobjecttemplate__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[__tid_Object__](ue_ue.DatasmithObjectTemplate.md#__tid_object__)

___

### bUseIESBrightness

• **bUseIESBrightness**: `boolean`

___

### bUseTemperature

• **bUseTemperature**: `boolean`

___

### bVisible

• **bVisible**: `boolean`

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

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[CreateDefaultSubobject](ue_ue.DatasmithObjectTemplate.md#createdefaultsubobject)

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

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[ExecuteUbergraph](ue_ue.DatasmithObjectTemplate.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetClass](ue_ue.DatasmithObjectTemplate.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetName](ue_ue.DatasmithObjectTemplate.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetOuter](ue_ue.DatasmithObjectTemplate.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetWorld](ue_ue.DatasmithObjectTemplate.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithLightComponentTemplate`](ue_ue.DatasmithLightComponentTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithLightComponentTemplate`](ue_ue.DatasmithLightComponentTemplate.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[Find](ue_ue.DatasmithObjectTemplate.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithLightComponentTemplate`](ue_ue.DatasmithLightComponentTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithLightComponentTemplate`](ue_ue.DatasmithLightComponentTemplate.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[Load](ue_ue.DatasmithObjectTemplate.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[StaticClass](ue_ue.DatasmithObjectTemplate.md#staticclass)
