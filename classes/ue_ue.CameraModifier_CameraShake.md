[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CameraModifier\_CameraShake

# Class: CameraModifier\_CameraShake

[ue/ue](../modules/ue_ue.md).CameraModifier_CameraShake

## Hierarchy

- [`CameraModifier`](ue_ue.CameraModifier.md)

  ↳ **`CameraModifier_CameraShake`**

## Table of contents

### Constructors

- [constructor](ue_ue.CameraModifier_CameraShake.md#constructor)

### Properties

- [ActiveShakes](ue_ue.CameraModifier_CameraShake.md#activeshakes)
- [Alpha](ue_ue.CameraModifier_CameraShake.md#alpha)
- [AlphaInTime](ue_ue.CameraModifier_CameraShake.md#alphaintime)
- [AlphaOutTime](ue_ue.CameraModifier_CameraShake.md#alphaouttime)
- [CameraOwner](ue_ue.CameraModifier_CameraShake.md#cameraowner)
- [ExpiredPooledShakesMap](ue_ue.CameraModifier_CameraShake.md#expiredpooledshakesmap)
- [Priority](ue_ue.CameraModifier_CameraShake.md#priority)
- [SplitScreenShakeScale](ue_ue.CameraModifier_CameraShake.md#splitscreenshakescale)
- [\_\_tid\_CameraModifier\_CameraShake\_\_](ue_ue.CameraModifier_CameraShake.md#__tid_cameramodifier_camerashake__)
- [\_\_tid\_CameraModifier\_\_](ue_ue.CameraModifier_CameraShake.md#__tid_cameramodifier__)
- [\_\_tid\_Object\_\_](ue_ue.CameraModifier_CameraShake.md#__tid_object__)
- [bDebug](ue_ue.CameraModifier_CameraShake.md#bdebug)
- [bExclusive](ue_ue.CameraModifier_CameraShake.md#bexclusive)

### Methods

- [BlueprintModifyCamera](ue_ue.CameraModifier_CameraShake.md#blueprintmodifycamera)
- [BlueprintModifyPostProcess](ue_ue.CameraModifier_CameraShake.md#blueprintmodifypostprocess)
- [CreateDefaultSubobject](ue_ue.CameraModifier_CameraShake.md#createdefaultsubobject)
- [DisableModifier](ue_ue.CameraModifier_CameraShake.md#disablemodifier)
- [EnableModifier](ue_ue.CameraModifier_CameraShake.md#enablemodifier)
- [ExecuteUbergraph](ue_ue.CameraModifier_CameraShake.md#executeubergraph)
- [GetClass](ue_ue.CameraModifier_CameraShake.md#getclass)
- [GetName](ue_ue.CameraModifier_CameraShake.md#getname)
- [GetOuter](ue_ue.CameraModifier_CameraShake.md#getouter)
- [GetViewTarget](ue_ue.CameraModifier_CameraShake.md#getviewtarget)
- [GetWorld](ue_ue.CameraModifier_CameraShake.md#getworld)
- [IsDisabled](ue_ue.CameraModifier_CameraShake.md#isdisabled)
- [Find](ue_ue.CameraModifier_CameraShake.md#find)
- [Load](ue_ue.CameraModifier_CameraShake.md#load)
- [StaticClass](ue_ue.CameraModifier_CameraShake.md#staticclass)

## Constructors

### constructor

• **new CameraModifier_CameraShake**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[CameraModifier](ue_ue.CameraModifier.md).[constructor](ue_ue.CameraModifier.md#constructor)

#### Defined in

[ue/ue.d.ts:7706](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7706)

## Properties

### ActiveShakes

• **ActiveShakes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CameraShake`](ue_ue.CameraShake.md)\>

#### Defined in

[ue/ue.d.ts:7707](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7707)

___

### Alpha

• **Alpha**: `number`

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[Alpha](ue_ue.CameraModifier.md#alpha)

#### Defined in

[ue/ue.d.ts:6688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6688)

___

### AlphaInTime

• **AlphaInTime**: `number`

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[AlphaInTime](ue_ue.CameraModifier.md#alphaintime)

#### Defined in

[ue/ue.d.ts:6686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6686)

___

### AlphaOutTime

• **AlphaOutTime**: `number`

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[AlphaOutTime](ue_ue.CameraModifier.md#alphaouttime)

#### Defined in

[ue/ue.d.ts:6687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6687)

___

### CameraOwner

• **CameraOwner**: [`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[CameraOwner](ue_ue.CameraModifier.md#cameraowner)

#### Defined in

[ue/ue.d.ts:6685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6685)

___

### ExpiredPooledShakesMap

• **ExpiredPooledShakesMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Class`](ue_ue.Class.md), [`PooledCameraShakes`](ue_ue.PooledCameraShakes.md)\>

#### Defined in

[ue/ue.d.ts:7708](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7708)

___

### Priority

• **Priority**: `number`

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[Priority](ue_ue.CameraModifier.md#priority)

#### Defined in

[ue/ue.d.ts:6684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6684)

___

### SplitScreenShakeScale

• **SplitScreenShakeScale**: `number`

#### Defined in

[ue/ue.d.ts:7709](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7709)

___

### \_\_tid\_CameraModifier\_CameraShake\_\_

• **\_\_tid\_CameraModifier\_CameraShake\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7714](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7714)

___

### \_\_tid\_CameraModifier\_\_

• **\_\_tid\_CameraModifier\_\_**: `boolean`

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[__tid_CameraModifier__](ue_ue.CameraModifier.md#__tid_cameramodifier__)

#### Defined in

[ue/ue.d.ts:6699](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6699)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[__tid_Object__](ue_ue.CameraModifier.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bDebug

• **bDebug**: `boolean`

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[bDebug](ue_ue.CameraModifier.md#bdebug)

#### Defined in

[ue/ue.d.ts:6682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6682)

___

### bExclusive

• **bExclusive**: `boolean`

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[bExclusive](ue_ue.CameraModifier.md#bexclusive)

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

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[BlueprintModifyCamera](ue_ue.CameraModifier.md#blueprintmodifycamera)

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

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[BlueprintModifyPostProcess](ue_ue.CameraModifier.md#blueprintmodifypostprocess)

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

[CameraModifier](ue_ue.CameraModifier.md).[CreateDefaultSubobject](ue_ue.CameraModifier.md#createdefaultsubobject)

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

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[DisableModifier](ue_ue.CameraModifier.md#disablemodifier)

#### Defined in

[ue/ue.d.ts:6691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6691)

___

### EnableModifier

▸ **EnableModifier**(): `void`

#### Returns

`void`

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[EnableModifier](ue_ue.CameraModifier.md#enablemodifier)

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

[CameraModifier](ue_ue.CameraModifier.md).[ExecuteUbergraph](ue_ue.CameraModifier.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[GetClass](ue_ue.CameraModifier.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[GetName](ue_ue.CameraModifier.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[GetOuter](ue_ue.CameraModifier.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetViewTarget

▸ **GetViewTarget**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[GetViewTarget](ue_ue.CameraModifier.md#getviewtarget)

#### Defined in

[ue/ue.d.ts:6693](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6693)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[GetWorld](ue_ue.CameraModifier.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsDisabled

▸ **IsDisabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraModifier](ue_ue.CameraModifier.md).[IsDisabled](ue_ue.CameraModifier.md#isdisabled)

#### Defined in

[ue/ue.d.ts:6694](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6694)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CameraModifier_CameraShake`](ue_ue.CameraModifier_CameraShake.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CameraModifier_CameraShake`](ue_ue.CameraModifier_CameraShake.md)

#### Overrides

[CameraModifier](ue_ue.CameraModifier.md).[Find](ue_ue.CameraModifier.md#find)

#### Defined in

[ue/ue.d.ts:7711](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7711)

___

### Load

▸ `Static` **Load**(`InName`): [`CameraModifier_CameraShake`](ue_ue.CameraModifier_CameraShake.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CameraModifier_CameraShake`](ue_ue.CameraModifier_CameraShake.md)

#### Overrides

[CameraModifier](ue_ue.CameraModifier.md).[Load](ue_ue.CameraModifier.md#load)

#### Defined in

[ue/ue.d.ts:7712](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7712)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[CameraModifier](ue_ue.CameraModifier.md).[StaticClass](ue_ue.CameraModifier.md#staticclass)

#### Defined in

[ue/ue.d.ts:7710](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7710)
