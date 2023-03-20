[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / XRLoadingScreenFunctionLibrary

# Class: XRLoadingScreenFunctionLibrary

[ue/ue](../modules/ue_ue.md).XRLoadingScreenFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`XRLoadingScreenFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.XRLoadingScreenFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.XRLoadingScreenFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.XRLoadingScreenFunctionLibrary.md#__tid_object__)
- [\_\_tid\_XRLoadingScreenFunctionLibrary\_\_](ue_ue.XRLoadingScreenFunctionLibrary.md#__tid_xrloadingscreenfunctionlibrary__)

### Methods

- [CreateDefaultSubobject](ue_ue.XRLoadingScreenFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.XRLoadingScreenFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.XRLoadingScreenFunctionLibrary.md#getclass)
- [GetName](ue_ue.XRLoadingScreenFunctionLibrary.md#getname)
- [GetOuter](ue_ue.XRLoadingScreenFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.XRLoadingScreenFunctionLibrary.md#getworld)
- [AddLoadingScreenSplash](ue_ue.XRLoadingScreenFunctionLibrary.md#addloadingscreensplash)
- [ClearLoadingScreenSplashes](ue_ue.XRLoadingScreenFunctionLibrary.md#clearloadingscreensplashes)
- [Find](ue_ue.XRLoadingScreenFunctionLibrary.md#find)
- [HideLoadingScreen](ue_ue.XRLoadingScreenFunctionLibrary.md#hideloadingscreen)
- [Load](ue_ue.XRLoadingScreenFunctionLibrary.md#load)
- [SetLoadingScreen](ue_ue.XRLoadingScreenFunctionLibrary.md#setloadingscreen)
- [ShowLoadingScreen](ue_ue.XRLoadingScreenFunctionLibrary.md#showloadingscreen)
- [StaticClass](ue_ue.XRLoadingScreenFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new XRLoadingScreenFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

___

### \_\_tid\_XRLoadingScreenFunctionLibrary\_\_

• **\_\_tid\_XRLoadingScreenFunctionLibrary\_\_**: `boolean`

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### AddLoadingScreenSplash

▸ `Static` **AddLoadingScreenSplash**(`Texture`, `Translation`, `Rotation`, `Size?`, `DeltaRotation?`, `bClearBeforeAdd?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Texture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `Translation` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `Size?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `DeltaRotation?` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bClearBeforeAdd?` | `boolean` |

#### Returns

`void`

___

### ClearLoadingScreenSplashes

▸ `Static` **ClearLoadingScreenSplashes**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`XRLoadingScreenFunctionLibrary`](ue_ue.XRLoadingScreenFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`XRLoadingScreenFunctionLibrary`](ue_ue.XRLoadingScreenFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### HideLoadingScreen

▸ `Static` **HideLoadingScreen**(): `void`

#### Returns

`void`

___

### Load

▸ `Static` **Load**(`InName`): [`XRLoadingScreenFunctionLibrary`](ue_ue.XRLoadingScreenFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`XRLoadingScreenFunctionLibrary`](ue_ue.XRLoadingScreenFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### SetLoadingScreen

▸ `Static` **SetLoadingScreen**(`Texture`, `Scale`, `Offset`, `bShowLoadingMovie`, `bShowOnSet`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Texture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `Scale` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Offset` | [`Vector`](ue_ue_s.Vector.md) |
| `bShowLoadingMovie` | `boolean` |
| `bShowOnSet` | `boolean` |

#### Returns

`void`

___

### ShowLoadingScreen

▸ `Static` **ShowLoadingScreen**(): `void`

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
