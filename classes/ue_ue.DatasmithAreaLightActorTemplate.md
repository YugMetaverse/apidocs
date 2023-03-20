[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithAreaLightActorTemplate

# Class: DatasmithAreaLightActorTemplate

[ue/ue](../modules/ue_ue.md).DatasmithAreaLightActorTemplate

## Hierarchy

- [`DatasmithObjectTemplate`](ue_ue.DatasmithObjectTemplate.md)

  ↳ **`DatasmithAreaLightActorTemplate`**

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithAreaLightActorTemplate.md#constructor)

### Properties

- [AttenuationRadius](ue_ue.DatasmithAreaLightActorTemplate.md#attenuationradius)
- [Color](ue_ue.DatasmithAreaLightActorTemplate.md#color)
- [Dimensions](ue_ue.DatasmithAreaLightActorTemplate.md#dimensions)
- [IESBrightnessScale](ue_ue.DatasmithAreaLightActorTemplate.md#iesbrightnessscale)
- [IESTexture](ue_ue.DatasmithAreaLightActorTemplate.md#iestexture)
- [Intensity](ue_ue.DatasmithAreaLightActorTemplate.md#intensity)
- [IntensityUnits](ue_ue.DatasmithAreaLightActorTemplate.md#intensityunits)
- [LightShape](ue_ue.DatasmithAreaLightActorTemplate.md#lightshape)
- [LightType](ue_ue.DatasmithAreaLightActorTemplate.md#lighttype)
- [Rotation](ue_ue.DatasmithAreaLightActorTemplate.md#rotation)
- [SourceLength](ue_ue.DatasmithAreaLightActorTemplate.md#sourcelength)
- [SourceRadius](ue_ue.DatasmithAreaLightActorTemplate.md#sourceradius)
- [Temperature](ue_ue.DatasmithAreaLightActorTemplate.md#temperature)
- [\_\_tid\_DatasmithAreaLightActorTemplate\_\_](ue_ue.DatasmithAreaLightActorTemplate.md#__tid_datasmitharealightactortemplate__)
- [\_\_tid\_DatasmithObjectTemplate\_\_](ue_ue.DatasmithAreaLightActorTemplate.md#__tid_datasmithobjecttemplate__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithAreaLightActorTemplate.md#__tid_object__)
- [bUseIESBrightness](ue_ue.DatasmithAreaLightActorTemplate.md#buseiesbrightness)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithAreaLightActorTemplate.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithAreaLightActorTemplate.md#executeubergraph)
- [GetClass](ue_ue.DatasmithAreaLightActorTemplate.md#getclass)
- [GetName](ue_ue.DatasmithAreaLightActorTemplate.md#getname)
- [GetOuter](ue_ue.DatasmithAreaLightActorTemplate.md#getouter)
- [GetWorld](ue_ue.DatasmithAreaLightActorTemplate.md#getworld)
- [Find](ue_ue.DatasmithAreaLightActorTemplate.md#find)
- [Load](ue_ue.DatasmithAreaLightActorTemplate.md#load)
- [StaticClass](ue_ue.DatasmithAreaLightActorTemplate.md#staticclass)

## Constructors

### constructor

• **new DatasmithAreaLightActorTemplate**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[constructor](ue_ue.DatasmithObjectTemplate.md#constructor)

## Properties

### AttenuationRadius

• **AttenuationRadius**: `number`

___

### Color

• **Color**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### Dimensions

• **Dimensions**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### IESBrightnessScale

• **IESBrightnessScale**: `number`

___

### IESTexture

• **IESTexture**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`TextureLightProfile`](ue_ue.TextureLightProfile.md)\>

___

### Intensity

• **Intensity**: `number`

___

### IntensityUnits

• **IntensityUnits**: [`ELightUnits`](../enums/ue_ue.ELightUnits.md)

___

### LightShape

• **LightShape**: [`EDatasmithAreaLightActorShape`](../enums/ue_ue.EDatasmithAreaLightActorShape.md)

___

### LightType

• **LightType**: [`EDatasmithAreaLightActorType`](../enums/ue_ue.EDatasmithAreaLightActorType.md)

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### SourceLength

• **SourceLength**: `number`

___

### SourceRadius

• **SourceRadius**: `number`

___

### Temperature

• **Temperature**: `number`

___

### \_\_tid\_DatasmithAreaLightActorTemplate\_\_

• **\_\_tid\_DatasmithAreaLightActorTemplate\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithAreaLightActorTemplate`](ue_ue.DatasmithAreaLightActorTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithAreaLightActorTemplate`](ue_ue.DatasmithAreaLightActorTemplate.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[Find](ue_ue.DatasmithObjectTemplate.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithAreaLightActorTemplate`](ue_ue.DatasmithAreaLightActorTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithAreaLightActorTemplate`](ue_ue.DatasmithAreaLightActorTemplate.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[Load](ue_ue.DatasmithObjectTemplate.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[StaticClass](ue_ue.DatasmithObjectTemplate.md#staticclass)
