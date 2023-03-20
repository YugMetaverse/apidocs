[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PixelInspectorView

# Class: PixelInspectorView

[ue/ue](../modules/ue_ue.md).PixelInspectorView

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PixelInspectorView`**

## Table of contents

### Constructors

- [constructor](ue_ue.PixelInspectorView.md#constructor)

### Properties

- [AmbientOcclusion](ue_ue.PixelInspectorView.md#ambientocclusion)
- [BackLit](ue_ue.PixelInspectorView.md#backlit)
- [BaseColor](ue_ue.PixelInspectorView.md#basecolor)
- [ClearCoat](ue_ue.PixelInspectorView.md#clearcoat)
- [ClearCoatRoughness](ue_ue.PixelInspectorView.md#clearcoatroughness)
- [Cloth](ue_ue.PixelInspectorView.md#cloth)
- [EyeTangent](ue_ue.PixelInspectorView.md#eyetangent)
- [FinalColor](ue_ue.PixelInspectorView.md#finalcolor)
- [HdrColor](ue_ue.PixelInspectorView.md#hdrcolor)
- [IndirectIrradiance](ue_ue.PixelInspectorView.md#indirectirradiance)
- [IrisDistance](ue_ue.PixelInspectorView.md#irisdistance)
- [IrisMask](ue_ue.PixelInspectorView.md#irismask)
- [Luminance](ue_ue.PixelInspectorView.md#luminance)
- [MaterialShadingModel](ue_ue.PixelInspectorView.md#materialshadingmodel)
- [Metallic](ue_ue.PixelInspectorView.md#metallic)
- [Normal](ue_ue.PixelInspectorView.md#normal)
- [Opacity](ue_ue.PixelInspectorView.md#opacity)
- [PerObjectGBufferData](ue_ue.PixelInspectorView.md#perobjectgbufferdata)
- [PreExposure](ue_ue.PixelInspectorView.md#preexposure)
- [Roughness](ue_ue.PixelInspectorView.md#roughness)
- [SceneColor](ue_ue.PixelInspectorView.md#scenecolor)
- [SelectiveOutputMask](ue_ue.PixelInspectorView.md#selectiveoutputmask)
- [Specular](ue_ue.PixelInspectorView.md#specular)
- [SubSurfaceColor](ue_ue.PixelInspectorView.md#subsurfacecolor)
- [SubsurfaceProfile](ue_ue.PixelInspectorView.md#subsurfaceprofile)
- [WorldNormal](ue_ue.PixelInspectorView.md#worldnormal)
- [\_\_tid\_Object\_\_](ue_ue.PixelInspectorView.md#__tid_object__)
- [\_\_tid\_PixelInspectorView\_\_](ue_ue.PixelInspectorView.md#__tid_pixelinspectorview__)

### Methods

- [CreateDefaultSubobject](ue_ue.PixelInspectorView.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PixelInspectorView.md#executeubergraph)
- [GetClass](ue_ue.PixelInspectorView.md#getclass)
- [GetName](ue_ue.PixelInspectorView.md#getname)
- [GetOuter](ue_ue.PixelInspectorView.md#getouter)
- [GetWorld](ue_ue.PixelInspectorView.md#getworld)
- [Find](ue_ue.PixelInspectorView.md#find)
- [Load](ue_ue.PixelInspectorView.md#load)
- [StaticClass](ue_ue.PixelInspectorView.md#staticclass)

## Constructors

### constructor

• **new PixelInspectorView**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:57845](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57845)

## Properties

### AmbientOcclusion

• **AmbientOcclusion**: `number`

#### Defined in

[ue/ue.d.ts:57860](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57860)

___

### BackLit

• **BackLit**: `number`

#### Defined in

[ue/ue.d.ts:57867](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57867)

___

### BaseColor

• **BaseColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:57858](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57858)

___

### ClearCoat

• **ClearCoat**: `number`

#### Defined in

[ue/ue.d.ts:57864](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57864)

___

### ClearCoatRoughness

• **ClearCoatRoughness**: `number`

#### Defined in

[ue/ue.d.ts:57865](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57865)

___

### Cloth

• **Cloth**: `number`

#### Defined in

[ue/ue.d.ts:57868](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57868)

___

### EyeTangent

• **EyeTangent**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:57869](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57869)

___

### FinalColor

• **FinalColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:57846](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57846)

___

### HdrColor

• **HdrColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:57850](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57850)

___

### IndirectIrradiance

• **IndirectIrradiance**: `number`

#### Defined in

[ue/ue.d.ts:57859](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57859)

___

### IrisDistance

• **IrisDistance**: `number`

#### Defined in

[ue/ue.d.ts:57871](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57871)

___

### IrisMask

• **IrisMask**: `number`

#### Defined in

[ue/ue.d.ts:57870](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57870)

___

### Luminance

• **Luminance**: `number`

#### Defined in

[ue/ue.d.ts:57849](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57849)

___

### MaterialShadingModel

• **MaterialShadingModel**: [`EMaterialShadingModel`](../enums/ue_ue.EMaterialShadingModel.md)

#### Defined in

[ue/ue.d.ts:57856](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57856)

___

### Metallic

• **Metallic**: `number`

#### Defined in

[ue/ue.d.ts:57853](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57853)

___

### Normal

• **Normal**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:57851](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57851)

___

### Opacity

• **Opacity**: `number`

#### Defined in

[ue/ue.d.ts:57863](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57863)

___

### PerObjectGBufferData

• **PerObjectGBufferData**: `number`

#### Defined in

[ue/ue.d.ts:57852](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57852)

___

### PreExposure

• **PreExposure**: `number`

#### Defined in

[ue/ue.d.ts:57848](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57848)

___

### Roughness

• **Roughness**: `number`

#### Defined in

[ue/ue.d.ts:57855](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57855)

___

### SceneColor

• **SceneColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:57847](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57847)

___

### SelectiveOutputMask

• **SelectiveOutputMask**: `number`

#### Defined in

[ue/ue.d.ts:57857](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57857)

___

### Specular

• **Specular**: `number`

#### Defined in

[ue/ue.d.ts:57854](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57854)

___

### SubSurfaceColor

• **SubSurfaceColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:57861](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57861)

___

### SubsurfaceProfile

• **SubsurfaceProfile**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:57862](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57862)

___

### WorldNormal

• **WorldNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:57866](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57866)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PixelInspectorView\_\_

• **\_\_tid\_PixelInspectorView\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:57876](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57876)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PixelInspectorView`](ue_ue.PixelInspectorView.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PixelInspectorView`](ue_ue.PixelInspectorView.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:57873](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57873)

___

### Load

▸ `Static` **Load**(`InName`): [`PixelInspectorView`](ue_ue.PixelInspectorView.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PixelInspectorView`](ue_ue.PixelInspectorView.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:57874](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57874)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:57872](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57872)
