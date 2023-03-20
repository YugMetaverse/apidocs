[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WidgetDesignerSettings

# Class: WidgetDesignerSettings

[ue/ue](../modules/ue_ue.md).WidgetDesignerSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`WidgetDesignerSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.WidgetDesignerSettings.md#constructor)

### Properties

- [Favorites](ue_ue.WidgetDesignerSettings.md#favorites)
- [GridSnapEnabled](ue_ue.WidgetDesignerSettings.md#gridsnapenabled)
- [GridSnapSize](ue_ue.WidgetDesignerSettings.md#gridsnapsize)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.WidgetDesignerSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.WidgetDesignerSettings.md#__tid_object__)
- [\_\_tid\_WidgetDesignerSettings\_\_](ue_ue.WidgetDesignerSettings.md#__tid_widgetdesignersettings__)
- [bExecutePreConstructEvent](ue_ue.WidgetDesignerSettings.md#bexecutepreconstructevent)
- [bLockToPanelOnDragByDefault](ue_ue.WidgetDesignerSettings.md#blocktopanelondragbydefault)
- [bRespectLocks](ue_ue.WidgetDesignerSettings.md#brespectlocks)
- [bShowOutlines](ue_ue.WidgetDesignerSettings.md#bshowoutlines)

### Methods

- [CreateDefaultSubobject](ue_ue.WidgetDesignerSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.WidgetDesignerSettings.md#executeubergraph)
- [GetClass](ue_ue.WidgetDesignerSettings.md#getclass)
- [GetName](ue_ue.WidgetDesignerSettings.md#getname)
- [GetOuter](ue_ue.WidgetDesignerSettings.md#getouter)
- [GetWorld](ue_ue.WidgetDesignerSettings.md#getworld)
- [Find](ue_ue.WidgetDesignerSettings.md#find)
- [Load](ue_ue.WidgetDesignerSettings.md#load)
- [StaticClass](ue_ue.WidgetDesignerSettings.md#staticclass)

## Constructors

### constructor

• **new WidgetDesignerSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### Favorites

• **Favorites**: [`WidgetPaletteFavorites`](ue_ue.WidgetPaletteFavorites.md)

___

### GridSnapEnabled

• **GridSnapEnabled**: `boolean`

___

### GridSnapSize

• **GridSnapSize**: `number`

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### \_\_tid\_WidgetDesignerSettings\_\_

• **\_\_tid\_WidgetDesignerSettings\_\_**: `boolean`

___

### bExecutePreConstructEvent

• **bExecutePreConstructEvent**: `boolean`

___

### bLockToPanelOnDragByDefault

• **bLockToPanelOnDragByDefault**: `boolean`

___

### bRespectLocks

• **bRespectLocks**: `boolean`

___

### bShowOutlines

• **bShowOutlines**: `boolean`

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`WidgetDesignerSettings`](ue_ue.WidgetDesignerSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`WidgetDesignerSettings`](ue_ue.WidgetDesignerSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`WidgetDesignerSettings`](ue_ue.WidgetDesignerSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`WidgetDesignerSettings`](ue_ue.WidgetDesignerSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
