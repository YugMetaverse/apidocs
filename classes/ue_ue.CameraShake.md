[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CameraShake

# Class: CameraShake

[ue/ue](../modules/ue_ue.md).CameraShake

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`CameraShake`**

## Table of contents

### Constructors

- [constructor](ue_ue.CameraShake.md#constructor)

### Properties

- [Anim](ue_ue.CameraShake.md#anim)
- [AnimBlendInTime](ue_ue.CameraShake.md#animblendintime)
- [AnimBlendOutTime](ue_ue.CameraShake.md#animblendouttime)
- [AnimInst](ue_ue.CameraShake.md#animinst)
- [AnimPlayRate](ue_ue.CameraShake.md#animplayrate)
- [AnimScale](ue_ue.CameraShake.md#animscale)
- [CameraOwner](ue_ue.CameraShake.md#cameraowner)
- [FOVOscillation](ue_ue.CameraShake.md#fovoscillation)
- [LocOscillation](ue_ue.CameraShake.md#locoscillation)
- [OscillationBlendInTime](ue_ue.CameraShake.md#oscillationblendintime)
- [OscillationBlendOutTime](ue_ue.CameraShake.md#oscillationblendouttime)
- [OscillationDuration](ue_ue.CameraShake.md#oscillationduration)
- [OscillatorTimeRemaining](ue_ue.CameraShake.md#oscillatortimeremaining)
- [RandomAnimSegmentDuration](ue_ue.CameraShake.md#randomanimsegmentduration)
- [RotOscillation](ue_ue.CameraShake.md#rotoscillation)
- [ShakeScale](ue_ue.CameraShake.md#shakescale)
- [\_\_tid\_CameraShake\_\_](ue_ue.CameraShake.md#__tid_camerashake__)
- [\_\_tid\_Object\_\_](ue_ue.CameraShake.md#__tid_object__)
- [bRandomAnimSegment](ue_ue.CameraShake.md#brandomanimsegment)
- [bSingleInstance](ue_ue.CameraShake.md#bsingleinstance)

### Methods

- [BlueprintUpdateCameraShake](ue_ue.CameraShake.md#blueprintupdatecamerashake)
- [CreateDefaultSubobject](ue_ue.CameraShake.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CameraShake.md#executeubergraph)
- [GetClass](ue_ue.CameraShake.md#getclass)
- [GetName](ue_ue.CameraShake.md#getname)
- [GetOuter](ue_ue.CameraShake.md#getouter)
- [GetWorld](ue_ue.CameraShake.md#getworld)
- [ReceiveIsFinished](ue_ue.CameraShake.md#receiveisfinished)
- [ReceivePlayShake](ue_ue.CameraShake.md#receiveplayshake)
- [ReceiveStopShake](ue_ue.CameraShake.md#receivestopshake)
- [Find](ue_ue.CameraShake.md#find)
- [Load](ue_ue.CameraShake.md#load)
- [StaticClass](ue_ue.CameraShake.md#staticclass)

## Constructors

### constructor

• **new CameraShake**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:7663](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7663)

## Properties

### Anim

• **Anim**: [`CameraAnim`](ue_ue.CameraAnim.md)

#### Defined in

[ue/ue.d.ts:7676](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7676)

___

### AnimBlendInTime

• **AnimBlendInTime**: `number`

#### Defined in

[ue/ue.d.ts:7673](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7673)

___

### AnimBlendOutTime

• **AnimBlendOutTime**: `number`

#### Defined in

[ue/ue.d.ts:7674](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7674)

___

### AnimInst

• **AnimInst**: [`CameraAnimInst`](ue_ue.CameraAnimInst.md)

#### Defined in

[ue/ue.d.ts:7681](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7681)

___

### AnimPlayRate

• **AnimPlayRate**: `number`

#### Defined in

[ue/ue.d.ts:7671](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7671)

___

### AnimScale

• **AnimScale**: `number`

#### Defined in

[ue/ue.d.ts:7672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7672)

___

### CameraOwner

• **CameraOwner**: [`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

#### Defined in

[ue/ue.d.ts:7678](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7678)

___

### FOVOscillation

• **FOVOscillation**: [`FOscillator`](ue_ue.FOscillator.md)

#### Defined in

[ue/ue.d.ts:7670](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7670)

___

### LocOscillation

• **LocOscillation**: [`VOscillator`](ue_ue.VOscillator.md)

#### Defined in

[ue/ue.d.ts:7669](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7669)

___

### OscillationBlendInTime

• **OscillationBlendInTime**: `number`

#### Defined in

[ue/ue.d.ts:7666](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7666)

___

### OscillationBlendOutTime

• **OscillationBlendOutTime**: `number`

#### Defined in

[ue/ue.d.ts:7667](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7667)

___

### OscillationDuration

• **OscillationDuration**: `number`

#### Defined in

[ue/ue.d.ts:7665](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7665)

___

### OscillatorTimeRemaining

• **OscillatorTimeRemaining**: `number`

#### Defined in

[ue/ue.d.ts:7680](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7680)

___

### RandomAnimSegmentDuration

• **RandomAnimSegmentDuration**: `number`

#### Defined in

[ue/ue.d.ts:7675](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7675)

___

### RotOscillation

• **RotOscillation**: [`ROscillator`](ue_ue.ROscillator.md)

#### Defined in

[ue/ue.d.ts:7668](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7668)

___

### ShakeScale

• **ShakeScale**: `number`

#### Defined in

[ue/ue.d.ts:7679](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7679)

___

### \_\_tid\_CameraShake\_\_

• **\_\_tid\_CameraShake\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7690](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7690)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bRandomAnimSegment

• **bRandomAnimSegment**: `boolean`

#### Defined in

[ue/ue.d.ts:7677](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7677)

___

### bSingleInstance

• **bSingleInstance**: `boolean`

#### Defined in

[ue/ue.d.ts:7664](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7664)

## Methods

### BlueprintUpdateCameraShake

▸ **BlueprintUpdateCameraShake**(`DeltaTime`, `Alpha`, `POV`, `ModifiedPOV`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTime` | `number` |
| `Alpha` | `number` |
| `POV` | [`MinimalViewInfo`](ue_ue.MinimalViewInfo.md) |
| `ModifiedPOV` | [`$Ref`](../interfaces/puerts._Ref.md)<[`MinimalViewInfo`](ue_ue.MinimalViewInfo.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:7682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7682)

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

### ReceiveIsFinished

▸ **ReceiveIsFinished**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:7683](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7683)

___

### ReceivePlayShake

▸ **ReceivePlayShake**(`Scale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:7684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7684)

___

### ReceiveStopShake

▸ **ReceiveStopShake**(`bImmediately`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bImmediately` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:7685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7685)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CameraShake`](ue_ue.CameraShake.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CameraShake`](ue_ue.CameraShake.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:7687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7687)

___

### Load

▸ `Static` **Load**(`InName`): [`CameraShake`](ue_ue.CameraShake.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CameraShake`](ue_ue.CameraShake.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:7688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7688)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:7686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7686)
