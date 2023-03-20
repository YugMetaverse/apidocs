[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CameraAnim

# Class: CameraAnim

[ue/ue](../modules/ue_ue.md).CameraAnim

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`CameraAnim`**

## Table of contents

### Constructors

- [constructor](ue_ue.CameraAnim.md#constructor)

### Properties

- [AnimLength](ue_ue.CameraAnim.md#animlength)
- [BaseFOV](ue_ue.CameraAnim.md#basefov)
- [BasePostProcessBlendWeight](ue_ue.CameraAnim.md#basepostprocessblendweight)
- [BasePostProcessSettings](ue_ue.CameraAnim.md#basepostprocesssettings)
- [BoundingBox](ue_ue.CameraAnim.md#boundingbox)
- [CameraInterpGroup](ue_ue.CameraAnim.md#camerainterpgroup)
- [PreviewInterpGroup](ue_ue.CameraAnim.md#previewinterpgroup)
- [\_\_tid\_CameraAnim\_\_](ue_ue.CameraAnim.md#__tid_cameraanim__)
- [\_\_tid\_Object\_\_](ue_ue.CameraAnim.md#__tid_object__)
- [bRelativeToInitialFOV](ue_ue.CameraAnim.md#brelativetoinitialfov)
- [bRelativeToInitialTransform](ue_ue.CameraAnim.md#brelativetoinitialtransform)

### Methods

- [CreateDefaultSubobject](ue_ue.CameraAnim.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CameraAnim.md#executeubergraph)
- [GetClass](ue_ue.CameraAnim.md#getclass)
- [GetName](ue_ue.CameraAnim.md#getname)
- [GetOuter](ue_ue.CameraAnim.md#getouter)
- [GetWorld](ue_ue.CameraAnim.md#getworld)
- [Find](ue_ue.CameraAnim.md#find)
- [Load](ue_ue.CameraAnim.md#load)
- [StaticClass](ue_ue.CameraAnim.md#staticclass)

## Constructors

### constructor

• **new CameraAnim**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:7524](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7524)

## Properties

### AnimLength

• **AnimLength**: `number`

#### Defined in

[ue/ue.d.ts:7527](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7527)

___

### BaseFOV

• **BaseFOV**: `number`

#### Defined in

[ue/ue.d.ts:7531](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7531)

___

### BasePostProcessBlendWeight

• **BasePostProcessBlendWeight**: `number`

#### Defined in

[ue/ue.d.ts:7533](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7533)

___

### BasePostProcessSettings

• **BasePostProcessSettings**: [`PostProcessSettings`](ue_ue.PostProcessSettings.md)

#### Defined in

[ue/ue.d.ts:7532](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7532)

___

### BoundingBox

• **BoundingBox**: [`Box`](ue_ue.Box.md)

#### Defined in

[ue/ue.d.ts:7528](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7528)

___

### CameraInterpGroup

• **CameraInterpGroup**: [`InterpGroup`](ue_ue.InterpGroup.md)

#### Defined in

[ue/ue.d.ts:7525](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7525)

___

### PreviewInterpGroup

• **PreviewInterpGroup**: [`InterpGroup`](ue_ue.InterpGroup.md)

#### Defined in

[ue/ue.d.ts:7526](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7526)

___

### \_\_tid\_CameraAnim\_\_

• **\_\_tid\_CameraAnim\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7538)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bRelativeToInitialFOV

• **bRelativeToInitialFOV**: `boolean`

#### Defined in

[ue/ue.d.ts:7530](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7530)

___

### bRelativeToInitialTransform

• **bRelativeToInitialTransform**: `boolean`

#### Defined in

[ue/ue.d.ts:7529](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7529)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CameraAnim`](ue_ue.CameraAnim.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CameraAnim`](ue_ue.CameraAnim.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:7535](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7535)

___

### Load

▸ `Static` **Load**(`InName`): [`CameraAnim`](ue_ue.CameraAnim.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CameraAnim`](ue_ue.CameraAnim.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:7536](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7536)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:7534](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7534)
