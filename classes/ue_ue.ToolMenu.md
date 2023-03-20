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

## Properties

### Context

• **Context**: [`ToolMenuContext`](ue_ue.ToolMenuContext.md)

___

### MenuName

• **MenuName**: `string`

___

### MenuOwner

• **MenuOwner**: [`ToolMenuOwner`](ue_ue.ToolMenuOwner.md)

___

### MenuParent

• **MenuParent**: `string`

___

### MenuType

• **MenuType**: [`EMultiBoxType`](../enums/ue_ue.EMultiBoxType.md)

___

### Sections

• **Sections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ToolMenuSection`](ue_ue.ToolMenuSection.md)\>

___

### StyleName

• **StyleName**: `string`

___

### SubMenuParent

• **SubMenuParent**: [`ToolMenu`](ue_ue.ToolMenu.md)

___

### SubMenuSourceEntryName

• **SubMenuSourceEntryName**: `string`

___

### TutorialHighlightName

• **TutorialHighlightName**: `string`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ToolMenuBase](ue_ue.ToolMenuBase.md).[__tid_Object__](ue_ue.ToolMenuBase.md#__tid_object__)

___

### \_\_tid\_ToolMenuBase\_\_

• **\_\_tid\_ToolMenuBase\_\_**: `boolean`

#### Inherited from

[ToolMenuBase](ue_ue.ToolMenuBase.md).[__tid_ToolMenuBase__](ue_ue.ToolMenuBase.md#__tid_toolmenubase__)

___

### \_\_tid\_ToolMenu\_\_

• **\_\_tid\_ToolMenu\_\_**: `boolean`

___

### bCloseSelfOnly

• **bCloseSelfOnly**: `boolean`

___

### bPreventCustomization

• **bPreventCustomization**: `boolean`

___

### bSearchable

• **bSearchable**: `boolean`

___

### bShouldCloseWindowAfterMenuSelection

• **bShouldCloseWindowAfterMenuSelection**: `boolean`

___

### bToolBarForceSmallIcons

• **bToolBarForceSmallIcons**: `boolean`

___

### bToolBarIsFocusable

• **bToolBarIsFocusable**: `boolean`

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

___

### AddMenuEntryObject

▸ **AddMenuEntryObject**(`InObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ToolMenuEntryScript`](ue_ue.ToolMenuEntryScript.md)\> |

#### Returns

`void`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ToolMenuBase](ue_ue.ToolMenuBase.md).[GetClass](ue_ue.ToolMenuBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ToolMenuBase](ue_ue.ToolMenuBase.md).[GetName](ue_ue.ToolMenuBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ToolMenuBase](ue_ue.ToolMenuBase.md).[GetOuter](ue_ue.ToolMenuBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ToolMenuBase](ue_ue.ToolMenuBase.md).[GetWorld](ue_ue.ToolMenuBase.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ToolMenuBase](ue_ue.ToolMenuBase.md).[StaticClass](ue_ue.ToolMenuBase.md#staticclass)
