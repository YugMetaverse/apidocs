[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TimelineTemplate

# Class: TimelineTemplate

[ue/ue](../modules/ue_ue.md).TimelineTemplate

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`TimelineTemplate`**

## Table of contents

### Constructors

- [constructor](ue_ue.TimelineTemplate.md#constructor)

### Properties

- [DirectionPropertyName](ue_ue.TimelineTemplate.md#directionpropertyname)
- [EventTracks](ue_ue.TimelineTemplate.md#eventtracks)
- [FinishedFunctionName](ue_ue.TimelineTemplate.md#finishedfunctionname)
- [FloatTracks](ue_ue.TimelineTemplate.md#floattracks)
- [LengthMode](ue_ue.TimelineTemplate.md#lengthmode)
- [LinearColorTracks](ue_ue.TimelineTemplate.md#linearcolortracks)
- [MetaDataArray](ue_ue.TimelineTemplate.md#metadataarray)
- [TimelineGuid](ue_ue.TimelineTemplate.md#timelineguid)
- [TimelineLength](ue_ue.TimelineTemplate.md#timelinelength)
- [UpdateFunctionName](ue_ue.TimelineTemplate.md#updatefunctionname)
- [VariableName](ue_ue.TimelineTemplate.md#variablename)
- [VectorTracks](ue_ue.TimelineTemplate.md#vectortracks)
- [\_\_tid\_Object\_\_](ue_ue.TimelineTemplate.md#__tid_object__)
- [\_\_tid\_TimelineTemplate\_\_](ue_ue.TimelineTemplate.md#__tid_timelinetemplate__)
- [bAutoPlay](ue_ue.TimelineTemplate.md#bautoplay)
- [bIgnoreTimeDilation](ue_ue.TimelineTemplate.md#bignoretimedilation)
- [bLoop](ue_ue.TimelineTemplate.md#bloop)
- [bReplicated](ue_ue.TimelineTemplate.md#breplicated)

### Methods

- [CreateDefaultSubobject](ue_ue.TimelineTemplate.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TimelineTemplate.md#executeubergraph)
- [GetClass](ue_ue.TimelineTemplate.md#getclass)
- [GetName](ue_ue.TimelineTemplate.md#getname)
- [GetOuter](ue_ue.TimelineTemplate.md#getouter)
- [GetWorld](ue_ue.TimelineTemplate.md#getworld)
- [Find](ue_ue.TimelineTemplate.md#find)
- [Load](ue_ue.TimelineTemplate.md#load)
- [StaticClass](ue_ue.TimelineTemplate.md#staticclass)

## Constructors

### constructor

• **new TimelineTemplate**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:4281](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4281)

## Properties

### DirectionPropertyName

• **DirectionPropertyName**: `string`

#### Defined in

[ue/ue.d.ts:4295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4295)

___

### EventTracks

• **EventTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TTEventTrack`](ue_ue.TTEventTrack.md)\>

#### Defined in

[ue/ue.d.ts:4288](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4288)

___

### FinishedFunctionName

• **FinishedFunctionName**: `string`

#### Defined in

[ue/ue.d.ts:4297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4297)

___

### FloatTracks

• **FloatTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TTFloatTrack`](ue_ue.TTFloatTrack.md)\>

#### Defined in

[ue/ue.d.ts:4289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4289)

___

### LengthMode

• **LengthMode**: [`ETimelineLengthMode`](../enums/ue_ue.ETimelineLengthMode.md)

#### Defined in

[ue/ue.d.ts:4283](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4283)

___

### LinearColorTracks

• **LinearColorTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TTLinearColorTrack`](ue_ue.TTLinearColorTrack.md)\>

#### Defined in

[ue/ue.d.ts:4291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4291)

___

### MetaDataArray

• **MetaDataArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPVariableMetaDataEntry`](ue_ue.BPVariableMetaDataEntry.md)\>

#### Defined in

[ue/ue.d.ts:4292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4292)

___

### TimelineGuid

• **TimelineGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:4293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4293)

___

### TimelineLength

• **TimelineLength**: `number`

#### Defined in

[ue/ue.d.ts:4282](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4282)

___

### UpdateFunctionName

• **UpdateFunctionName**: `string`

#### Defined in

[ue/ue.d.ts:4296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4296)

___

### VariableName

• **VariableName**: `string`

#### Defined in

[ue/ue.d.ts:4294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4294)

___

### VectorTracks

• **VectorTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TTVectorTrack`](ue_ue.TTVectorTrack.md)\>

#### Defined in

[ue/ue.d.ts:4290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4290)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_TimelineTemplate\_\_

• **\_\_tid\_TimelineTemplate\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:4302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4302)

___

### bAutoPlay

• **bAutoPlay**: `boolean`

#### Defined in

[ue/ue.d.ts:4284](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4284)

___

### bIgnoreTimeDilation

• **bIgnoreTimeDilation**: `boolean`

#### Defined in

[ue/ue.d.ts:4287](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4287)

___

### bLoop

• **bLoop**: `boolean`

#### Defined in

[ue/ue.d.ts:4285](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4285)

___

### bReplicated

• **bReplicated**: `boolean`

#### Defined in

[ue/ue.d.ts:4286](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4286)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TimelineTemplate`](ue_ue.TimelineTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TimelineTemplate`](ue_ue.TimelineTemplate.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:4299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4299)

___

### Load

▸ `Static` **Load**(`InName`): [`TimelineTemplate`](ue_ue.TimelineTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TimelineTemplate`](ue_ue.TimelineTemplate.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:4300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4300)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:4298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4298)
