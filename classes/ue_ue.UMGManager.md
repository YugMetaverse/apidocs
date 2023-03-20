[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UMGManager

# Class: UMGManager

[ue/ue](../modules/ue_ue.md).UMGManager

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`UMGManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.UMGManager.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.UMGManager.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.UMGManager.md#__tid_object__)
- [\_\_tid\_UMGManager\_\_](ue_ue.UMGManager.md#__tid_umgmanager__)

### Methods

- [CreateDefaultSubobject](ue_ue.UMGManager.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UMGManager.md#executeubergraph)
- [GetClass](ue_ue.UMGManager.md#getclass)
- [GetName](ue_ue.UMGManager.md#getname)
- [GetOuter](ue_ue.UMGManager.md#getouter)
- [GetWorld](ue_ue.UMGManager.md#getworld)
- [CreateReactWidget](ue_ue.UMGManager.md#createreactwidget)
- [CreateWidget](ue_ue.UMGManager.md#createwidget)
- [Find](ue_ue.UMGManager.md#find)
- [Load](ue_ue.UMGManager.md#load)
- [StaticClass](ue_ue.UMGManager.md#staticclass)
- [SynchronizeSlotProperties](ue_ue.UMGManager.md#synchronizeslotproperties)
- [SynchronizeWidgetProperties](ue_ue.UMGManager.md#synchronizewidgetproperties)

## Constructors

### constructor

• **new UMGManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:64496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64496)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_UMGManager\_\_

• **\_\_tid\_UMGManager\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64505](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64505)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### CreateReactWidget

▸ `Static` **CreateReactWidget**(`World`): [`ReactWidget`](ue_ue.ReactWidget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `World` | [`$Nullable`](../modules/puerts.md#$nullable)<[`World`](ue_ue.World.md)\> |

#### Returns

[`ReactWidget`](ue_ue.ReactWidget.md)

#### Defined in

[ue/ue.d.ts:64497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64497)

___

### CreateWidget

▸ `Static` **CreateWidget**(`World`, `Class`): [`UserWidget`](ue_ue.UserWidget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `World` | [`$Nullable`](../modules/puerts.md#$nullable)<[`World`](ue_ue.World.md)\> |
| `Class` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`UserWidget`](ue_ue.UserWidget.md)

#### Defined in

[ue/ue.d.ts:64498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64498)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UMGManager`](ue_ue.UMGManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UMGManager`](ue_ue.UMGManager.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:64502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64502)

___

### Load

▸ `Static` **Load**(`InName`): [`UMGManager`](ue_ue.UMGManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UMGManager`](ue_ue.UMGManager.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:64503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64503)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:64501](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64501)

___

### SynchronizeSlotProperties

▸ `Static` **SynchronizeSlotProperties**(`Slot`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Slot` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PanelSlot`](ue_ue.PanelSlot.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64499](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64499)

___

### SynchronizeWidgetProperties

▸ `Static` **SynchronizeWidgetProperties**(`Widget`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64500](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64500)
