[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CameraAnimInst

# Class: CameraAnimInst

[ue/ue](../modules/ue_ue.md).CameraAnimInst

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`CameraAnimInst`**

## Table of contents

### Constructors

- [constructor](ue_ue.CameraAnimInst.md#constructor)

### Properties

- [CamAnim](ue_ue.CameraAnimInst.md#camanim)
- [InterpGroupInst](ue_ue.CameraAnimInst.md#interpgroupinst)
- [MoveInst](ue_ue.CameraAnimInst.md#moveinst)
- [MoveTrack](ue_ue.CameraAnimInst.md#movetrack)
- [PlayRate](ue_ue.CameraAnimInst.md#playrate)
- [PlaySpace](ue_ue.CameraAnimInst.md#playspace)
- [\_\_tid\_CameraAnimInst\_\_](ue_ue.CameraAnimInst.md#__tid_cameraaniminst__)
- [\_\_tid\_Object\_\_](ue_ue.CameraAnimInst.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.CameraAnimInst.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CameraAnimInst.md#executeubergraph)
- [GetClass](ue_ue.CameraAnimInst.md#getclass)
- [GetName](ue_ue.CameraAnimInst.md#getname)
- [GetOuter](ue_ue.CameraAnimInst.md#getouter)
- [GetWorld](ue_ue.CameraAnimInst.md#getworld)
- [SetDuration](ue_ue.CameraAnimInst.md#setduration)
- [SetScale](ue_ue.CameraAnimInst.md#setscale)
- [Stop](ue_ue.CameraAnimInst.md#stop)
- [Find](ue_ue.CameraAnimInst.md#find)
- [Load](ue_ue.CameraAnimInst.md#load)
- [StaticClass](ue_ue.CameraAnimInst.md#staticclass)

## Constructors

### constructor

• **new CameraAnimInst**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### CamAnim

• **CamAnim**: [`CameraAnim`](ue_ue.CameraAnim.md)

___

### InterpGroupInst

• **InterpGroupInst**: [`InterpGroupInst`](ue_ue.InterpGroupInst.md)

___

### MoveInst

• **MoveInst**: [`InterpTrackInstMove`](ue_ue.InterpTrackInstMove.md)

___

### MoveTrack

• **MoveTrack**: [`InterpTrackMove`](ue_ue.InterpTrackMove.md)

___

### PlayRate

• **PlayRate**: `number`

___

### PlaySpace

• **PlaySpace**: [`ECameraAnimPlaySpace`](../enums/ue_ue.ECameraAnimPlaySpace.md)

___

### \_\_tid\_CameraAnimInst\_\_

• **\_\_tid\_CameraAnimInst\_\_**: `boolean`

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

### SetDuration

▸ **SetDuration**(`NewDuration`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewDuration` | `number` |

#### Returns

`void`

___

### SetScale

▸ **SetScale**(`NewDuration`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewDuration` | `number` |

#### Returns

`void`

___

### Stop

▸ **Stop**(`bImmediate?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bImmediate?` | `boolean` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CameraAnimInst`](ue_ue.CameraAnimInst.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CameraAnimInst`](ue_ue.CameraAnimInst.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CameraAnimInst`](ue_ue.CameraAnimInst.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CameraAnimInst`](ue_ue.CameraAnimInst.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
