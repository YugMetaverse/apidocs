[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / HudSettings

# Class: HudSettings

[ue/ue](../modules/ue_ue.md).HudSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`HudSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.HudSettings.md#constructor)

### Properties

- [DebugDisplay](ue_ue.HudSettings.md#debugdisplay)
- [\_\_tid\_HudSettings\_\_](ue_ue.HudSettings.md#__tid_hudsettings__)
- [\_\_tid\_Object\_\_](ue_ue.HudSettings.md#__tid_object__)
- [bShowHUD](ue_ue.HudSettings.md#bshowhud)

### Methods

- [CreateDefaultSubobject](ue_ue.HudSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.HudSettings.md#executeubergraph)
- [GetClass](ue_ue.HudSettings.md#getclass)
- [GetName](ue_ue.HudSettings.md#getname)
- [GetOuter](ue_ue.HudSettings.md#getouter)
- [GetWorld](ue_ue.HudSettings.md#getworld)
- [Find](ue_ue.HudSettings.md#find)
- [Load](ue_ue.HudSettings.md#load)
- [StaticClass](ue_ue.HudSettings.md#staticclass)

## Constructors

### constructor

• **new HudSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:38684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38684)

## Properties

### DebugDisplay

• **DebugDisplay**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:38686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38686)

___

### \_\_tid\_HudSettings\_\_

• **\_\_tid\_HudSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:38691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38691)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bShowHUD

• **bShowHUD**: `boolean`

#### Defined in

[ue/ue.d.ts:38685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38685)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`HudSettings`](ue_ue.HudSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`HudSettings`](ue_ue.HudSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:38688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38688)

___

### Load

▸ `Static` **Load**(`InName`): [`HudSettings`](ue_ue.HudSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`HudSettings`](ue_ue.HudSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:38689](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38689)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:38687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L38687)
