[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorProjectAppearanceSettings

# Class: EditorProjectAppearanceSettings

[ue/ue](../modules/ue_ue.md).EditorProjectAppearanceSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`EditorProjectAppearanceSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorProjectAppearanceSettings.md#constructor)

### Properties

- [AngleUnits](ue_ue.EditorProjectAppearanceSettings.md#angleunits)
- [DefaultInputUnits](ue_ue.EditorProjectAppearanceSettings.md#defaultinputunits)
- [DistanceUnits](ue_ue.EditorProjectAppearanceSettings.md#distanceunits)
- [ForceUnits](ue_ue.EditorProjectAppearanceSettings.md#forceunits)
- [MassUnits](ue_ue.EditorProjectAppearanceSettings.md#massunits)
- [SpeedUnits](ue_ue.EditorProjectAppearanceSettings.md#speedunits)
- [TemperatureUnits](ue_ue.EditorProjectAppearanceSettings.md#temperatureunits)
- [TimeUnits](ue_ue.EditorProjectAppearanceSettings.md#timeunits)
- [UnitDisplay](ue_ue.EditorProjectAppearanceSettings.md#unitdisplay)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.EditorProjectAppearanceSettings.md#__tid_developersettings__)
- [\_\_tid\_EditorProjectAppearanceSettings\_\_](ue_ue.EditorProjectAppearanceSettings.md#__tid_editorprojectappearancesettings__)
- [\_\_tid\_Object\_\_](ue_ue.EditorProjectAppearanceSettings.md#__tid_object__)
- [bDisplayUnits](ue_ue.EditorProjectAppearanceSettings.md#bdisplayunits)
- [bDisplayUnitsOnComponentTransforms](ue_ue.EditorProjectAppearanceSettings.md#bdisplayunitsoncomponenttransforms)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorProjectAppearanceSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorProjectAppearanceSettings.md#executeubergraph)
- [GetClass](ue_ue.EditorProjectAppearanceSettings.md#getclass)
- [GetName](ue_ue.EditorProjectAppearanceSettings.md#getname)
- [GetOuter](ue_ue.EditorProjectAppearanceSettings.md#getouter)
- [GetWorld](ue_ue.EditorProjectAppearanceSettings.md#getworld)
- [Find](ue_ue.EditorProjectAppearanceSettings.md#find)
- [Load](ue_ue.EditorProjectAppearanceSettings.md#load)
- [StaticClass](ue_ue.EditorProjectAppearanceSettings.md#staticclass)

## Constructors

### constructor

• **new EditorProjectAppearanceSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### AngleUnits

• **AngleUnits**: [`EUnit`](../enums/ue_ue.EUnit.md)

___

### DefaultInputUnits

• **DefaultInputUnits**: [`EDefaultLocationUnit`](../enums/ue_ue.EDefaultLocationUnit.md)

___

### DistanceUnits

• **DistanceUnits**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EUnit`](../enums/ue_ue.EUnit.md)\>

___

### ForceUnits

• **ForceUnits**: [`EUnit`](../enums/ue_ue.EUnit.md)

___

### MassUnits

• **MassUnits**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EUnit`](../enums/ue_ue.EUnit.md)\>

___

### SpeedUnits

• **SpeedUnits**: [`EUnit`](../enums/ue_ue.EUnit.md)

___

### TemperatureUnits

• **TemperatureUnits**: [`EUnit`](../enums/ue_ue.EUnit.md)

___

### TimeUnits

• **TimeUnits**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EUnit`](../enums/ue_ue.EUnit.md)\>

___

### UnitDisplay

• **UnitDisplay**: [`EUnitDisplay`](../enums/ue_ue.EUnitDisplay.md)

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_EditorProjectAppearanceSettings\_\_

• **\_\_tid\_EditorProjectAppearanceSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### bDisplayUnits

• **bDisplayUnits**: `boolean`

___

### bDisplayUnitsOnComponentTransforms

• **bDisplayUnitsOnComponentTransforms**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorProjectAppearanceSettings`](ue_ue.EditorProjectAppearanceSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorProjectAppearanceSettings`](ue_ue.EditorProjectAppearanceSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorProjectAppearanceSettings`](ue_ue.EditorProjectAppearanceSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorProjectAppearanceSettings`](ue_ue.EditorProjectAppearanceSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
