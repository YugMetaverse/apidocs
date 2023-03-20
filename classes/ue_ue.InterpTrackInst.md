[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrackInst

# Class: InterpTrackInst

[ue/ue](../modules/ue_ue.md).InterpTrackInst

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InterpTrackInst`**

  ↳↳ [`InterpTrackInstDirector`](ue_ue.InterpTrackInstDirector.md)

  ↳↳ [`InterpTrackInstMove`](ue_ue.InterpTrackInstMove.md)

  ↳↳ [`InterpTrackInstAnimControl`](ue_ue.InterpTrackInstAnimControl.md)

  ↳↳ [`InterpTrackInstAudioMaster`](ue_ue.InterpTrackInstAudioMaster.md)

  ↳↳ [`InterpTrackInstProperty`](ue_ue.InterpTrackInstProperty.md)

  ↳↳ [`InterpTrackInstColorScale`](ue_ue.InterpTrackInstColorScale.md)

  ↳↳ [`InterpTrackInstEvent`](ue_ue.InterpTrackInstEvent.md)

  ↳↳ [`InterpTrackInstFade`](ue_ue.InterpTrackInstFade.md)

  ↳↳ [`InterpTrackInstFloatAnimBPParam`](ue_ue.InterpTrackInstFloatAnimBPParam.md)

  ↳↳ [`InterpTrackInstFloatMaterialParam`](ue_ue.InterpTrackInstFloatMaterialParam.md)

  ↳↳ [`InterpTrackInstFloatParticleParam`](ue_ue.InterpTrackInstFloatParticleParam.md)

  ↳↳ [`InterpTrackInstParticleReplay`](ue_ue.InterpTrackInstParticleReplay.md)

  ↳↳ [`InterpTrackInstSlomo`](ue_ue.InterpTrackInstSlomo.md)

  ↳↳ [`InterpTrackInstSound`](ue_ue.InterpTrackInstSound.md)

  ↳↳ [`InterpTrackInstToggle`](ue_ue.InterpTrackInstToggle.md)

  ↳↳ [`InterpTrackInstVectorMaterialParam`](ue_ue.InterpTrackInstVectorMaterialParam.md)

  ↳↳ [`InterpTrackInstVisibility`](ue_ue.InterpTrackInstVisibility.md)

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrackInst.md#constructor)

### Properties

- [\_\_tid\_InterpTrackInst\_\_](ue_ue.InterpTrackInst.md#__tid_interptrackinst__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrackInst.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrackInst.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrackInst.md#executeubergraph)
- [GetClass](ue_ue.InterpTrackInst.md#getclass)
- [GetName](ue_ue.InterpTrackInst.md#getname)
- [GetOuter](ue_ue.InterpTrackInst.md#getouter)
- [GetWorld](ue_ue.InterpTrackInst.md#getworld)
- [Find](ue_ue.InterpTrackInst.md#find)
- [Load](ue_ue.InterpTrackInst.md#load)
- [StaticClass](ue_ue.InterpTrackInst.md#staticclass)

## Constructors

### constructor

• **new InterpTrackInst**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_InterpTrackInst\_\_

• **\_\_tid\_InterpTrackInst\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrackInst`](ue_ue.InterpTrackInst.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrackInst`](ue_ue.InterpTrackInst.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrackInst`](ue_ue.InterpTrackInst.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrackInst`](ue_ue.InterpTrackInst.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
