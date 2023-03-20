[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ToolMenu

# Class: ToolMenu

[ue/ue](../modules/ue_ue.md).ToolMenu

## Hierarchy

- [`ToolMenuBase`](ue_ue.ToolMenuBase.md)

  ↳ **`ToolMenu`**

## Table of contents

### Constructors

- [constructor](ue_ue.ToolMenu.md#constructor)

### Properties

- [Context](ue_ue.ToolMenu.md#context)
- [MenuName](ue_ue.ToolMenu.md#menuname)
- [MenuOwner](ue_ue.ToolMenu.md#menuowner)
- [MenuParent](ue_ue.ToolMenu.md#menuparent)
- [MenuType](ue_ue.ToolMenu.md#menutype)
- [Sections](ue_ue.ToolMenu.md#sections)
- [StyleName](ue_ue.ToolMenu.md#stylename)
- [SubMenuParent](ue_ue.ToolMenu.md#submenuparent)
- [SubMenuSourceEntryName](ue_ue.ToolMenu.md#submenusourceentryname)
- [TutorialHighlightName](ue_ue.ToolMenu.md#tutorialhighlightname)
- [\_\_tid\_Object\_\_](ue_ue.ToolMenu.md#__tid_object__)
- [\_\_tid\_ToolMenuBase\_\_](ue_ue.ToolMenu.md#__tid_toolmenubase__)
- [\_\_tid\_ToolMenu\_\_](ue_ue.ToolMenu.md#__tid_toolmenu__)
- [bCloseSelfOnly](ue_ue.ToolMenu.md#bcloseselfonly)
- [bPreventCustomization](ue_ue.ToolMenu.md#bpreventcustomization)
- [bSearchable](ue_ue.ToolMenu.md#bsearchable)
- [bShouldCloseWindowAfterMenuSelection](ue_ue.ToolMenu.md#bshouldclosewindowaftermenuselection)
- [bToolBarForceSmallIcons](ue_ue.ToolMenu.md#btoolbarforcesmallicons)
- [bToolBarIsFocusable](ue_ue.ToolMenu.md#btoolbarisfocusable)

### Methods

- [AddDynamicSectionScript](ue_ue.ToolMenu.md#adddynamicsectionscript)
- [AddMenuEntry](ue_ue.ToolMenu.md#addmenuentry)
- [AddMenuEntryObject](ue_ue.ToolMenu.md#addmenuentryobject)
- [AddSectionScript](ue_ue.ToolMenu.md#addsectionscript)
- [AddSubMenuScript](ue_ue.ToolMenu.md#addsubmenuscript)
- [CreateDefaultSubobject](ue_ue.ToolMenu.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ToolMenu.md#executeubergraph)
- [GetClass](ue_ue.ToolMenu.md#getclass)
- [GetName](ue_ue.ToolMenu.md#getname)
- [GetOuter](ue_ue.ToolMenu.md#getouter)
- [GetWorld](ue_ue.ToolMenu.md#getworld)
- [InitMenu](ue_ue.ToolMenu.md#initmenu)
- [Find](ue_ue.ToolMenu.md#find)
- [Load](ue_ue.ToolMenu.md#load)
- [StaticClass](ue_ue.ToolMenu.md#staticclass)

## Constructors

### constructor

• **new ToolMenu**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ToolMenuBase](ue_ue.ToolMenuBase.md).[constructor](ue_ue.ToolMenuBase.md#constructor)

#### Defined in

[ue/ue.d.ts:63903](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63903)

## Properties

### Context

• **Context**: [`ToolMenuContext`](ue_ue.ToolMenuContext.md)

#### Defined in

[ue/ue.d.ts:63916](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63916)

___

### MenuName

• **MenuName**: `string`

#### Defined in

[ue/ue.d.ts:63904](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63904)

___

### MenuOwner

• **MenuOwner**: [`ToolMenuOwner`](ue_ue.ToolMenuOwner.md)

#### Defined in

[ue/ue.d.ts:63915](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63915)

___

### MenuParent

• **MenuParent**: `string`

#### Defined in

[ue/ue.d.ts:63905](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63905)

___

### MenuType

• **MenuType**: [`EMultiBoxType`](../enums/ue_ue.EMultiBoxType.md)

#### Defined in

[ue/ue.d.ts:63908](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63908)

___

### Sections

• **Sections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ToolMenuSection`](ue_ue.ToolMenuSection.md)\>

#### Defined in

[ue/ue.d.ts:63917](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63917)

___

### StyleName

• **StyleName**: `string`

#### Defined in

[ue/ue.d.ts:63906](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63906)

___

### SubMenuParent

• **SubMenuParent**: [`ToolMenu`](ue_ue.ToolMenu.md)

#### Defined in

[ue/ue.d.ts:63918](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63918)

___

### SubMenuSourceEntryName

• **SubMenuSourceEntryName**: `string`

#### Defined in

[ue/ue.d.ts:63919](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63919)

___

### TutorialHighlightName

• **TutorialHighlightName**: `string`

#### Defined in

[ue/ue.d.ts:63907](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63907)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ToolMenuBase](ue_ue.ToolMenuBase.md).[__tid_Object__](ue_ue.ToolMenuBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ToolMenuBase\_\_

• **\_\_tid\_ToolMenuBase\_\_**: `boolean`

#### Inherited from

[ToolMenuBase](ue_ue.ToolMenuBase.md).[__tid_ToolMenuBase__](ue_ue.ToolMenuBase.md#__tid_toolmenubase__)

#### Defined in

[ue/ue.d.ts:63747](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63747)

___

### \_\_tid\_ToolMenu\_\_

• **\_\_tid\_ToolMenu\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:63930](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63930)

___

### bCloseSelfOnly

• **bCloseSelfOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:63910](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63910)

___

### bPreventCustomization

• **bPreventCustomization**: `boolean`

#### Defined in

[ue/ue.d.ts:63914](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63914)

___

### bSearchable

• **bSearchable**: `boolean`

#### Defined in

[ue/ue.d.ts:63911](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63911)

___

### bShouldCloseWindowAfterMenuSelection

• **bShouldCloseWindowAfterMenuSelection**: `boolean`

#### Defined in

[ue/ue.d.ts:63909](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63909)

___

### bToolBarForceSmallIcons

• **bToolBarForceSmallIcons**: `boolean`

#### Defined in

[ue/ue.d.ts:63913](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63913)

___

### bToolBarIsFocusable

• **bToolBarIsFocusable**: `boolean`

#### Defined in

[ue/ue.d.ts:63912](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63912)

## Methods

### AddDynamicSectionScript

▸ **AddDynamicSectionScript**(`SectionName`, `Object`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SectionName` | `string` |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ToolMenuSectionDynamic`](ue_ue.ToolMenuSectionDynamic.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63920](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63920)

___

### AddMenuEntry

▸ **AddMenuEntry**(`SectionName`, `Args`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SectionName` | `string` |
| `Args` | [`ToolMenuEntry`](ue_ue.ToolMenuEntry.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63921](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63921)

___

### AddMenuEntryObject

▸ **AddMenuEntryObject**(`InObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ToolMenuEntryScript`](ue_ue.ToolMenuEntryScript.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63922](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63922)

___

### AddSectionScript

▸ **AddSectionScript**(`SectionName`, `Label?`, `InsertName?`, `InsertType?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SectionName` | `string` |
| `Label?` | `string` |
| `InsertName?` | `string` |
| `InsertType?` | [`EToolMenuInsertType`](../enums/ue_ue.EToolMenuInsertType.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63923](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63923)

___

### AddSubMenuScript

▸ **AddSubMenuScript**(`Owner`, `SectionName`, `Name`, `Label`, `ToolTip?`): [`ToolMenu`](ue_ue.ToolMenu.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Owner` | `string` |
| `SectionName` | `string` |
| `Name` | `string` |
| `Label` | `string` |
| `ToolTip?` | `string` |

#### Returns

[`ToolMenu`](ue_ue.ToolMenu.md)

#### Defined in

[ue/ue.d.ts:63924](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63924)

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

[ToolMenuBase](ue_ue.ToolMenuBase.md).[CreateDefaultSubobject](ue_ue.ToolMenuBase.md#createdefaultsubobject)

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

[ToolMenuBase](ue_ue.ToolMenuBase.md).[ExecuteUbergraph](ue_ue.ToolMenuBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ToolMenuBase](ue_ue.ToolMenuBase.md).[GetClass](ue_ue.ToolMenuBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ToolMenuBase](ue_ue.ToolMenuBase.md).[GetName](ue_ue.ToolMenuBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ToolMenuBase](ue_ue.ToolMenuBase.md).[GetOuter](ue_ue.ToolMenuBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ToolMenuBase](ue_ue.ToolMenuBase.md).[GetWorld](ue_ue.ToolMenuBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### InitMenu

▸ **InitMenu**(`Owner`, `Name`, `Parent?`, `Type?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Owner` | [`ToolMenuOwner`](ue_ue.ToolMenuOwner.md) |
| `Name` | `string` |
| `Parent?` | `string` |
| `Type?` | [`EMultiBoxType`](../enums/ue_ue.EMultiBoxType.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:63925](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63925)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ToolMenu`](ue_ue.ToolMenu.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ToolMenu`](ue_ue.ToolMenu.md)

#### Overrides

[ToolMenuBase](ue_ue.ToolMenuBase.md).[Find](ue_ue.ToolMenuBase.md#find)

#### Defined in

[ue/ue.d.ts:63927](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63927)

___

### Load

▸ `Static` **Load**(`InName`): [`ToolMenu`](ue_ue.ToolMenu.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ToolMenu`](ue_ue.ToolMenu.md)

#### Overrides

[ToolMenuBase](ue_ue.ToolMenuBase.md).[Load](ue_ue.ToolMenuBase.md#load)

#### Defined in

[ue/ue.d.ts:63928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63928)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ToolMenuBase](ue_ue.ToolMenuBase.md).[StaticClass](ue_ue.ToolMenuBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:63926](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63926)
