[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DragDropOperation

# Class: DragDropOperation

[ue/ue](../modules/ue_ue.md).DragDropOperation

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`DragDropOperation`**

## Table of contents

### Constructors

- [constructor](ue_ue.DragDropOperation.md#constructor)

### Properties

- [DefaultDragVisual](ue_ue.DragDropOperation.md#defaultdragvisual)
- [Offset](ue_ue.DragDropOperation.md#offset)
- [OnDragCancelled](ue_ue.DragDropOperation.md#ondragcancelled)
- [OnDragged](ue_ue.DragDropOperation.md#ondragged)
- [OnDrop](ue_ue.DragDropOperation.md#ondrop)
- [Payload](ue_ue.DragDropOperation.md#payload)
- [Pivot](ue_ue.DragDropOperation.md#pivot)
- [Tag](ue_ue.DragDropOperation.md#tag)
- [\_\_tid\_DragDropOperation\_\_](ue_ue.DragDropOperation.md#__tid_dragdropoperation__)
- [\_\_tid\_Object\_\_](ue_ue.DragDropOperation.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DragDropOperation.md#createdefaultsubobject)
- [DragCancelled](ue_ue.DragDropOperation.md#dragcancelled)
- [Dragged](ue_ue.DragDropOperation.md#dragged)
- [Drop](ue_ue.DragDropOperation.md#drop)
- [ExecuteUbergraph](ue_ue.DragDropOperation.md#executeubergraph)
- [GetClass](ue_ue.DragDropOperation.md#getclass)
- [GetName](ue_ue.DragDropOperation.md#getname)
- [GetOuter](ue_ue.DragDropOperation.md#getouter)
- [GetWorld](ue_ue.DragDropOperation.md#getworld)
- [Find](ue_ue.DragDropOperation.md#find)
- [Load](ue_ue.DragDropOperation.md#load)
- [StaticClass](ue_ue.DragDropOperation.md#staticclass)

## Constructors

### constructor

• **new DragDropOperation**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:12029](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12029)

## Properties

### DefaultDragVisual

• **DefaultDragVisual**: [`Widget`](ue_ue.Widget.md)

#### Defined in

[ue/ue.d.ts:12032](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12032)

___

### Offset

• **Offset**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:12034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12034)

___

### OnDragCancelled

• **OnDragCancelled**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Operation`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DragDropOperation`](ue_ue.DragDropOperation.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:12036](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12036)

___

### OnDragged

• **OnDragged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Operation`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DragDropOperation`](ue_ue.DragDropOperation.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:12037](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12037)

___

### OnDrop

• **OnDrop**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Operation`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DragDropOperation`](ue_ue.DragDropOperation.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:12035](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12035)

___

### Payload

• **Payload**: [`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:12031](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12031)

___

### Pivot

• **Pivot**: [`EDragPivot`](../enums/ue_ue.EDragPivot.md)

#### Defined in

[ue/ue.d.ts:12033](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12033)

___

### Tag

• **Tag**: `string`

#### Defined in

[ue/ue.d.ts:12030](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12030)

___

### \_\_tid\_DragDropOperation\_\_

• **\_\_tid\_DragDropOperation\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:12045](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12045)

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

### DragCancelled

▸ **DragCancelled**(`PointerEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointerEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12038](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12038)

___

### Dragged

▸ **Dragged**(`PointerEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointerEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12039)

___

### Drop

▸ **Drop**(`PointerEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointerEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:12040](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12040)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DragDropOperation`](ue_ue.DragDropOperation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DragDropOperation`](ue_ue.DragDropOperation.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:12042](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12042)

___

### Load

▸ `Static` **Load**(`InName`): [`DragDropOperation`](ue_ue.DragDropOperation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DragDropOperation`](ue_ue.DragDropOperation.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:12043](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12043)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:12041](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12041)
