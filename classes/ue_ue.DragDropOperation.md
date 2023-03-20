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

## Properties

### DefaultDragVisual

• **DefaultDragVisual**: [`Widget`](ue_ue.Widget.md)

___

### Offset

• **Offset**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### OnDragCancelled

• **OnDragCancelled**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Operation`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DragDropOperation`](ue_ue.DragDropOperation.md)\>) => `void`\>

___

### OnDragged

• **OnDragged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Operation`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DragDropOperation`](ue_ue.DragDropOperation.md)\>) => `void`\>

___

### OnDrop

• **OnDrop**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Operation`: [`$Nullable`](../modules/puerts.md#$nullable)<[`DragDropOperation`](ue_ue.DragDropOperation.md)\>) => `void`\>

___

### Payload

• **Payload**: [`Object`](ue_ue.Object.md)

___

### Pivot

• **Pivot**: [`EDragPivot`](../enums/ue_ue.EDragPivot.md)

___

### Tag

• **Tag**: `string`

___

### \_\_tid\_DragDropOperation\_\_

• **\_\_tid\_DragDropOperation\_\_**: `boolean`

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

### DragCancelled

▸ **DragCancelled**(`PointerEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointerEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`void`

___

### Dragged

▸ **Dragged**(`PointerEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointerEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`void`

___

### Drop

▸ **Drop**(`PointerEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointerEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`void`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
