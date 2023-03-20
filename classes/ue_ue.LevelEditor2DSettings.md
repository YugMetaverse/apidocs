[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelEditor2DSettings

# Class: LevelEditor2DSettings

[ue/ue](../modules/ue_ue.md).LevelEditor2DSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`LevelEditor2DSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelEditor2DSettings.md#constructor)

### Properties

- [SnapAxis](ue_ue.LevelEditor2DSettings.md#snapaxis)
- [SnapLayers](ue_ue.LevelEditor2DSettings.md#snaplayers)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.LevelEditor2DSettings.md#__tid_developersettings__)
- [\_\_tid\_LevelEditor2DSettings\_\_](ue_ue.LevelEditor2DSettings.md#__tid_leveleditor2dsettings__)
- [\_\_tid\_Object\_\_](ue_ue.LevelEditor2DSettings.md#__tid_object__)
- [bEnable2DWidget](ue_ue.LevelEditor2DSettings.md#benable2dwidget)
- [bEnableSnapLayers](ue_ue.LevelEditor2DSettings.md#benablesnaplayers)

### Methods

- [CreateDefaultSubobject](ue_ue.LevelEditor2DSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LevelEditor2DSettings.md#executeubergraph)
- [GetClass](ue_ue.LevelEditor2DSettings.md#getclass)
- [GetName](ue_ue.LevelEditor2DSettings.md#getname)
- [GetOuter](ue_ue.LevelEditor2DSettings.md#getouter)
- [GetWorld](ue_ue.LevelEditor2DSettings.md#getworld)
- [Find](ue_ue.LevelEditor2DSettings.md#find)
- [Load](ue_ue.LevelEditor2DSettings.md#load)
- [StaticClass](ue_ue.LevelEditor2DSettings.md#staticclass)

## Constructors

### constructor

• **new LevelEditor2DSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### SnapAxis

• **SnapAxis**: [`ELevelEditor2DAxis`](../enums/ue_ue.ELevelEditor2DAxis.md)

___

### SnapLayers

• **SnapLayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Mode2DLayer`](ue_ue.Mode2DLayer.md)\>

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_LevelEditor2DSettings\_\_

• **\_\_tid\_LevelEditor2DSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### bEnable2DWidget

• **bEnable2DWidget**: `boolean`

___

### bEnableSnapLayers

• **bEnableSnapLayers**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelEditor2DSettings`](ue_ue.LevelEditor2DSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelEditor2DSettings`](ue_ue.LevelEditor2DSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelEditor2DSettings`](ue_ue.LevelEditor2DSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelEditor2DSettings`](ue_ue.LevelEditor2DSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
