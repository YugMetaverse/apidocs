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

## Properties

### AnimLength

• **AnimLength**: `number`

___

### BaseFOV

• **BaseFOV**: `number`

___

### BasePostProcessBlendWeight

• **BasePostProcessBlendWeight**: `number`

___

### BasePostProcessSettings

• **BasePostProcessSettings**: [`PostProcessSettings`](ue_ue.PostProcessSettings.md)

___

### BoundingBox

• **BoundingBox**: [`Box`](ue_ue.Box.md)

___

### CameraInterpGroup

• **CameraInterpGroup**: [`InterpGroup`](ue_ue.InterpGroup.md)

___

### PreviewInterpGroup

• **PreviewInterpGroup**: [`InterpGroup`](ue_ue.InterpGroup.md)

___

### \_\_tid\_CameraAnim\_\_

• **\_\_tid\_CameraAnim\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bRelativeToInitialFOV

• **bRelativeToInitialFOV**: `boolean`

___

### bRelativeToInitialTransform

• **bRelativeToInitialTransform**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
