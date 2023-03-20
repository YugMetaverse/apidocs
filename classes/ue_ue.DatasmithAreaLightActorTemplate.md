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

#### Defined in

[ue/ue.d.ts:29371](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29371)

## Properties

### AttenuationRadius

• **AttenuationRadius**: `number`

#### Defined in

[ue/ue.d.ts:29385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29385)

___

### Color

• **Color**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:29375](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29375)

___

### Dimensions

• **Dimensions**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:29374](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29374)

___

### IESBrightnessScale

• **IESBrightnessScale**: `number`

#### Defined in

[ue/ue.d.ts:29381](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29381)

___

### IESTexture

• **IESTexture**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`TextureLightProfile`](ue_ue.TextureLightProfile.md)\>

#### Defined in

[ue/ue.d.ts:29379](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29379)

___

### Intensity

• **Intensity**: `number`

#### Defined in

[ue/ue.d.ts:29376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29376)

___

### IntensityUnits

• **IntensityUnits**: [`ELightUnits`](../enums/ue_ue.ELightUnits.md)

#### Defined in

[ue/ue.d.ts:29377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29377)

___

### LightShape

• **LightShape**: [`EDatasmithAreaLightActorShape`](../enums/ue_ue.EDatasmithAreaLightActorShape.md)

#### Defined in

[ue/ue.d.ts:29373](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29373)

___

### LightType

• **LightType**: [`EDatasmithAreaLightActorType`](../enums/ue_ue.EDatasmithAreaLightActorType.md)

#### Defined in

[ue/ue.d.ts:29372](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29372)

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:29382](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29382)

___

### SourceLength

• **SourceLength**: `number`

#### Defined in

[ue/ue.d.ts:29384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29384)

___

### SourceRadius

• **SourceRadius**: `number`

#### Defined in

[ue/ue.d.ts:29383](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29383)

___

### Temperature

• **Temperature**: `number`

#### Defined in

[ue/ue.d.ts:29378](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29378)

___

### \_\_tid\_DatasmithAreaLightActorTemplate\_\_

• **\_\_tid\_DatasmithAreaLightActorTemplate\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:29390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29390)

___

### \_\_tid\_DatasmithObjectTemplate\_\_

• **\_\_tid\_DatasmithObjectTemplate\_\_**: `boolean`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[__tid_DatasmithObjectTemplate__](ue_ue.DatasmithObjectTemplate.md#__tid_datasmithobjecttemplate__)

#### Defined in

[ue/ue.d.ts:29319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29319)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[__tid_Object__](ue_ue.DatasmithObjectTemplate.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bUseIESBrightness

• **bUseIESBrightness**: `boolean`

#### Defined in

[ue/ue.d.ts:29380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29380)

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

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[ExecuteUbergraph](ue_ue.DatasmithObjectTemplate.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetClass](ue_ue.DatasmithObjectTemplate.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetName](ue_ue.DatasmithObjectTemplate.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetOuter](ue_ue.DatasmithObjectTemplate.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetWorld](ue_ue.DatasmithObjectTemplate.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:29387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29387)

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

#### Defined in

[ue/ue.d.ts:29388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29388)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[StaticClass](ue_ue.DatasmithObjectTemplate.md#staticclass)

#### Defined in

[ue/ue.d.ts:29386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29386)
