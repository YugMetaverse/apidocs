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

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

___

### \_\_tid\_UMGManager\_\_

• **\_\_tid\_UMGManager\_\_**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### CreateReactWidget

▸ `Static` **CreateReactWidget**(`World`): [`ReactWidget`](ue_ue.ReactWidget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `World` | [`$Nullable`](../modules/puerts.md#$nullable)<[`World`](ue_ue.World.md)\> |

#### Returns

[`ReactWidget`](ue_ue.ReactWidget.md)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

___

### SynchronizeSlotProperties

▸ `Static` **SynchronizeSlotProperties**(`Slot`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Slot` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PanelSlot`](ue_ue.PanelSlot.md)\> |

#### Returns

`void`

___

### SynchronizeWidgetProperties

▸ `Static` **SynchronizeWidgetProperties**(`Widget`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

`void`
