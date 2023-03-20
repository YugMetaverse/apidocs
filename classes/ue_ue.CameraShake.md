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

## Properties

### Anim

• **Anim**: [`CameraAnim`](ue_ue.CameraAnim.md)

___

### AnimBlendInTime

• **AnimBlendInTime**: `number`

___

### AnimBlendOutTime

• **AnimBlendOutTime**: `number`

___

### AnimInst

• **AnimInst**: [`CameraAnimInst`](ue_ue.CameraAnimInst.md)

___

### AnimPlayRate

• **AnimPlayRate**: `number`

___

### AnimScale

• **AnimScale**: `number`

___

### CameraOwner

• **CameraOwner**: [`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

___

### FOVOscillation

• **FOVOscillation**: [`FOscillator`](ue_ue.FOscillator.md)

___

### LocOscillation

• **LocOscillation**: [`VOscillator`](ue_ue.VOscillator.md)

___

### OscillationBlendInTime

• **OscillationBlendInTime**: `number`

___

### OscillationBlendOutTime

• **OscillationBlendOutTime**: `number`

___

### OscillationDuration

• **OscillationDuration**: `number`

___

### OscillatorTimeRemaining

• **OscillatorTimeRemaining**: `number`

___

### RandomAnimSegmentDuration

• **RandomAnimSegmentDuration**: `number`

___

### RotOscillation

• **RotOscillation**: [`ROscillator`](ue_ue.ROscillator.md)

___

### ShakeScale

• **ShakeScale**: `number`

___

### \_\_tid\_CameraShake\_\_

• **\_\_tid\_CameraShake\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bRandomAnimSegment

• **bRandomAnimSegment**: `boolean`

___

### bSingleInstance

• **bSingleInstance**: `boolean`

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

### ReceiveIsFinished

▸ **ReceiveIsFinished**(): `boolean`

#### Returns

`boolean`

___

### ReceivePlayShake

▸ **ReceivePlayShake**(`Scale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

`void`

___

### ReceiveStopShake

▸ **ReceiveStopShake**(`bImmediately`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bImmediately` | `boolean` |

#### Returns

`void`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
