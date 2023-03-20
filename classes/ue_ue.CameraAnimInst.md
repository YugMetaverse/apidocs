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

#### Defined in

[ue/ue.d.ts:7645](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7645)

## Properties

### CamAnim

• **CamAnim**: [`CameraAnim`](ue_ue.CameraAnim.md)

#### Defined in

[ue/ue.d.ts:7646](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7646)

___

### InterpGroupInst

• **InterpGroupInst**: [`InterpGroupInst`](ue_ue.InterpGroupInst.md)

#### Defined in

[ue/ue.d.ts:7647](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7647)

___

### MoveInst

• **MoveInst**: [`InterpTrackInstMove`](ue_ue.InterpTrackInstMove.md)

#### Defined in

[ue/ue.d.ts:7650](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7650)

___

### MoveTrack

• **MoveTrack**: [`InterpTrackMove`](ue_ue.InterpTrackMove.md)

#### Defined in

[ue/ue.d.ts:7649](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7649)

___

### PlayRate

• **PlayRate**: `number`

#### Defined in

[ue/ue.d.ts:7648](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7648)

___

### PlaySpace

• **PlaySpace**: [`ECameraAnimPlaySpace`](../enums/ue_ue.ECameraAnimPlaySpace.md)

#### Defined in

[ue/ue.d.ts:7651](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7651)

___

### \_\_tid\_CameraAnimInst\_\_

• **\_\_tid\_CameraAnimInst\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7659](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7659)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

### SetDuration

▸ **SetDuration**(`NewDuration`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewDuration` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:7652](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7652)

___

### SetScale

▸ **SetScale**(`NewDuration`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewDuration` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:7653](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7653)

___

### Stop

▸ **Stop**(`bImmediate?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bImmediate?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:7654](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7654)

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

#### Defined in

[ue/ue.d.ts:7656](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7656)

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

#### Defined in

[ue/ue.d.ts:7657](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7657)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:7655](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7655)
