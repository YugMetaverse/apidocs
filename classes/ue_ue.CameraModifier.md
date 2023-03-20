[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CameraModifier

# Class: CameraModifier

[ue/ue](../modules/ue_ue.md).CameraModifier

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`CameraModifier`**

  ↳↳ [`CameraModifier_CameraShake`](ue_ue.CameraModifier_CameraShake.md)

## Table of contents

### Constructors

- [constructor](ue_ue.CameraModifier.md#constructor)

### Properties

- [Alpha](ue_ue.CameraModifier.md#alpha)
- [AlphaInTime](ue_ue.CameraModifier.md#alphaintime)
- [AlphaOutTime](ue_ue.CameraModifier.md#alphaouttime)
- [CameraOwner](ue_ue.CameraModifier.md#cameraowner)
- [Priority](ue_ue.CameraModifier.md#priority)
- [\_\_tid\_CameraModifier\_\_](ue_ue.CameraModifier.md#__tid_cameramodifier__)
- [\_\_tid\_Object\_\_](ue_ue.CameraModifier.md#__tid_object__)
- [bDebug](ue_ue.CameraModifier.md#bdebug)
- [bExclusive](ue_ue.CameraModifier.md#bexclusive)

### Methods

- [BlueprintModifyCamera](ue_ue.CameraModifier.md#blueprintmodifycamera)
- [BlueprintModifyPostProcess](ue_ue.CameraModifier.md#blueprintmodifypostprocess)
- [CreateDefaultSubobject](ue_ue.CameraModifier.md#createdefaultsubobject)
- [DisableModifier](ue_ue.CameraModifier.md#disablemodifier)
- [EnableModifier](ue_ue.CameraModifier.md#enablemodifier)
- [ExecuteUbergraph](ue_ue.CameraModifier.md#executeubergraph)
- [GetClass](ue_ue.CameraModifier.md#getclass)
- [GetName](ue_ue.CameraModifier.md#getname)
- [GetOuter](ue_ue.CameraModifier.md#getouter)
- [GetViewTarget](ue_ue.CameraModifier.md#getviewtarget)
- [GetWorld](ue_ue.CameraModifier.md#getworld)
- [IsDisabled](ue_ue.CameraModifier.md#isdisabled)
- [Find](ue_ue.CameraModifier.md#find)
- [Load](ue_ue.CameraModifier.md#load)
- [StaticClass](ue_ue.CameraModifier.md#staticclass)

## Constructors

### constructor

• **new CameraModifier**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:6681](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6681)

## Properties

### Alpha

• **Alpha**: `number`

#### Defined in

[ue/ue.d.ts:6688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6688)

___

### AlphaInTime

• **AlphaInTime**: `number`

#### Defined in

[ue/ue.d.ts:6686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6686)

___

### AlphaOutTime

• **AlphaOutTime**: `number`

#### Defined in

[ue/ue.d.ts:6687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6687)

___

### CameraOwner

• **CameraOwner**: [`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

#### Defined in

[ue/ue.d.ts:6685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6685)

___

### Priority

• **Priority**: `number`

#### Defined in

[ue/ue.d.ts:6684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6684)

___

### \_\_tid\_CameraModifier\_\_

• **\_\_tid\_CameraModifier\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:6699](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6699)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bDebug

• **bDebug**: `boolean`

#### Defined in

[ue/ue.d.ts:6682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6682)

___

### bExclusive

• **bExclusive**: `boolean`

#### Defined in

[ue/ue.d.ts:6683](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6683)

## Methods

### BlueprintModifyCamera

▸ **BlueprintModifyCamera**(`DeltaTime`, `ViewLocation`, `ViewRotation`, `FOV`, `NewViewLocation`, `NewViewRotation`, `NewFOV`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTime` | `number` |
| `ViewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `ViewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `FOV` | `number` |
| `NewViewLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `NewViewRotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |
| `NewFOV` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6689](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6689)

___

### BlueprintModifyPostProcess

▸ **BlueprintModifyPostProcess**(`DeltaTime`, `PostProcessBlendWeight`, `PostProcessSettings`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTime` | `number` |
| `PostProcessBlendWeight` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `PostProcessSettings` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PostProcessSettings`](ue_ue.PostProcessSettings.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6690](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6690)

___

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

### DisableModifier

▸ **DisableModifier**(`bImmediate?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bImmediate?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6691)

___

### EnableModifier

▸ **EnableModifier**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:6692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6692)

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

### GetViewTarget

▸ **GetViewTarget**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:6693](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6693)

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

### IsDisabled

▸ **IsDisabled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:6694](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6694)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CameraModifier`](ue_ue.CameraModifier.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CameraModifier`](ue_ue.CameraModifier.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:6696](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6696)

___

### Load

▸ `Static` **Load**(`InName`): [`CameraModifier`](ue_ue.CameraModifier.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CameraModifier`](ue_ue.CameraModifier.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:6697](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6697)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:6695](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6695)
