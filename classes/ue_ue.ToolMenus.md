[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ToolMenus

# Class: ToolMenus

[ue/ue](../modules/ue_ue.md).ToolMenus

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ToolMenus`**

## Table of contents

### Constructors

- [constructor](ue_ue.ToolMenus.md#constructor)

### Properties

- [CustomizedMenus](ue_ue.ToolMenus.md#customizedmenus)
- [Menus](ue_ue.ToolMenus.md#menus)
- [\_\_tid\_Object\_\_](ue_ue.ToolMenus.md#__tid_object__)
- [\_\_tid\_ToolMenus\_\_](ue_ue.ToolMenus.md#__tid_toolmenus__)

### Methods

- [CreateDefaultSubobject](ue_ue.ToolMenus.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ToolMenus.md#executeubergraph)
- [ExtendMenu](ue_ue.ToolMenus.md#extendmenu)
- [FindMenu](ue_ue.ToolMenus.md#findmenu)
- [GetClass](ue_ue.ToolMenus.md#getclass)
- [GetName](ue_ue.ToolMenus.md#getname)
- [GetOuter](ue_ue.ToolMenus.md#getouter)
- [GetWorld](ue_ue.ToolMenus.md#getworld)
- [IsMenuRegistered](ue_ue.ToolMenus.md#ismenuregistered)
- [RefreshAllWidgets](ue_ue.ToolMenus.md#refreshallwidgets)
- [RefreshMenuWidget](ue_ue.ToolMenus.md#refreshmenuwidget)
- [RegisterMenu](ue_ue.ToolMenus.md#registermenu)
- [RemoveEntry](ue_ue.ToolMenus.md#removeentry)
- [RemoveMenu](ue_ue.ToolMenus.md#removemenu)
- [RemoveSection](ue_ue.ToolMenus.md#removesection)
- [SetSectionLabel](ue_ue.ToolMenus.md#setsectionlabel)
- [SetSectionPosition](ue_ue.ToolMenus.md#setsectionposition)
- [UnregisterOwnerByName](ue_ue.ToolMenus.md#unregisterownerbyname)
- [AddMenuEntryObject](ue_ue.ToolMenus.md#addmenuentryobject)
- [Find](ue_ue.ToolMenus.md#find)
- [FindContext](ue_ue.ToolMenus.md#findcontext)
- [Get](ue_ue.ToolMenus.md#get)
- [Load](ue_ue.ToolMenus.md#load)
- [StaticClass](ue_ue.ToolMenus.md#staticclass)

## Constructors

### constructor

• **new ToolMenus**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:64032](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64032)

## Properties

### CustomizedMenus

• **CustomizedMenus**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CustomizedToolMenu`](ue_ue.CustomizedToolMenu.md)\>

#### Defined in

[ue/ue.d.ts:64033](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64033)

___

### Menus

• **Menus**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`ToolMenu`](ue_ue.ToolMenu.md)\>

#### Defined in

[ue/ue.d.ts:64034](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64034)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ToolMenus\_\_

• **\_\_tid\_ToolMenus\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64054](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64054)

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

### ExtendMenu

▸ **ExtendMenu**(`Name`): [`ToolMenu`](ue_ue.ToolMenu.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

[`ToolMenu`](ue_ue.ToolMenu.md)

#### Defined in

[ue/ue.d.ts:64035](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64035)

___

### FindMenu

▸ **FindMenu**(`Name`): [`ToolMenu`](ue_ue.ToolMenu.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

[`ToolMenu`](ue_ue.ToolMenu.md)

#### Defined in

[ue/ue.d.ts:64036](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64036)

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

### IsMenuRegistered

▸ **IsMenuRegistered**(`Name`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:64037](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64037)

___

### RefreshAllWidgets

▸ **RefreshAllWidgets**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64038](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64038)

___

### RefreshMenuWidget

▸ **RefreshMenuWidget**(`Name`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:64039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64039)

___

### RegisterMenu

▸ **RegisterMenu**(`Name`, `Parent?`, `Type?`, `bWarnIfAlreadyRegistered?`): [`ToolMenu`](ue_ue.ToolMenu.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `Parent?` | `string` |
| `Type?` | [`EMultiBoxType`](../enums/ue_ue.EMultiBoxType.md) |
| `bWarnIfAlreadyRegistered?` | `boolean` |

#### Returns

[`ToolMenu`](ue_ue.ToolMenu.md)

#### Defined in

[ue/ue.d.ts:64040](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64040)

___

### RemoveEntry

▸ **RemoveEntry**(`MenuName`, `Section`, `Name`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MenuName` | `string` |
| `Section` | `string` |
| `Name` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64041](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64041)

___

### RemoveMenu

▸ **RemoveMenu**(`MenuName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MenuName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64042](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64042)

___

### RemoveSection

▸ **RemoveSection**(`MenuName`, `Section`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MenuName` | `string` |
| `Section` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64043](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64043)

___

### SetSectionLabel

▸ **SetSectionLabel**(`MenuName`, `SectionName`, `Label`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MenuName` | `string` |
| `SectionName` | `string` |
| `Label` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64044](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64044)

___

### SetSectionPosition

▸ **SetSectionPosition**(`MenuName`, `SectionName`, `OtherSectionName`, `PositionType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MenuName` | `string` |
| `SectionName` | `string` |
| `OtherSectionName` | `string` |
| `PositionType` | [`EToolMenuInsertType`](../enums/ue_ue.EToolMenuInsertType.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64045](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64045)

___

### UnregisterOwnerByName

▸ **UnregisterOwnerByName**(`InOwnerName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOwnerName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64046](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64046)

___

### AddMenuEntryObject

▸ `Static` **AddMenuEntryObject**(`MenuEntryObject`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MenuEntryObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ToolMenuEntryScript`](ue_ue.ToolMenuEntryScript.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:64047](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64047)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ToolMenus`](ue_ue.ToolMenus.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ToolMenus`](ue_ue.ToolMenus.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:64051](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64051)

___

### FindContext

▸ `Static` **FindContext**(`InContext`, `InClass`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InContext` | [`ToolMenuContext`](ue_ue.ToolMenuContext.md) |
| `InClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:64048](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64048)

___

### Get

▸ `Static` **Get**(): [`ToolMenus`](ue_ue.ToolMenus.md)

#### Returns

[`ToolMenus`](ue_ue.ToolMenus.md)

#### Defined in

[ue/ue.d.ts:64049](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64049)

___

### Load

▸ `Static` **Load**(`InName`): [`ToolMenus`](ue_ue.ToolMenus.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ToolMenus`](ue_ue.ToolMenus.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:64052](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64052)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:64050](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64050)
