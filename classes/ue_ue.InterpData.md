[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpData

# Class: InterpData

[ue/ue](../modules/ue_ue.md).InterpData

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InterpData`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpData.md#constructor)

### Properties

- [AllEventNames](ue_ue.InterpData.md#alleventnames)
- [CachedDirectorGroup](ue_ue.InterpData.md#cacheddirectorgroup)
- [CurveEdSetup](ue_ue.InterpData.md#curveedsetup)
- [DefaultFilters](ue_ue.InterpData.md#defaultfilters)
- [EdSectionEnd](ue_ue.InterpData.md#edsectionend)
- [EdSectionStart](ue_ue.InterpData.md#edsectionstart)
- [InterpFilters](ue_ue.InterpData.md#interpfilters)
- [InterpGroups](ue_ue.InterpData.md#interpgroups)
- [InterpLength](ue_ue.InterpData.md#interplength)
- [PathBuildTime](ue_ue.InterpData.md#pathbuildtime)
- [SelectedFilter](ue_ue.InterpData.md#selectedfilter)
- [\_\_tid\_InterpData\_\_](ue_ue.InterpData.md#__tid_interpdata__)
- [\_\_tid\_Object\_\_](ue_ue.InterpData.md#__tid_object__)
- [bShouldBakeAndPrune](ue_ue.InterpData.md#bshouldbakeandprune)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpData.md#executeubergraph)
- [GetClass](ue_ue.InterpData.md#getclass)
- [GetName](ue_ue.InterpData.md#getname)
- [GetOuter](ue_ue.InterpData.md#getouter)
- [GetWorld](ue_ue.InterpData.md#getworld)
- [Find](ue_ue.InterpData.md#find)
- [Load](ue_ue.InterpData.md#load)
- [StaticClass](ue_ue.InterpData.md#staticclass)

## Constructors

### constructor

• **new InterpData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AllEventNames

• **AllEventNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### CachedDirectorGroup

• **CachedDirectorGroup**: [`InterpGroupDirector`](ue_ue.InterpGroupDirector.md)

___

### CurveEdSetup

• **CurveEdSetup**: [`InterpCurveEdSetup`](ue_ue.InterpCurveEdSetup.md)

___

### DefaultFilters

• **DefaultFilters**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpFilter`](ue_ue.InterpFilter.md)\>

___

### EdSectionEnd

• **EdSectionEnd**: `number`

___

### EdSectionStart

• **EdSectionStart**: `number`

___

### InterpFilters

• **InterpFilters**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpFilter`](ue_ue.InterpFilter.md)\>

___

### InterpGroups

• **InterpGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpGroup`](ue_ue.InterpGroup.md)\>

___

### InterpLength

• **InterpLength**: `number`

___

### PathBuildTime

• **PathBuildTime**: `number`

___

### SelectedFilter

• **SelectedFilter**: [`InterpFilter`](ue_ue.InterpFilter.md)

___

### \_\_tid\_InterpData\_\_

• **\_\_tid\_InterpData\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bShouldBakeAndPrune

• **bShouldBakeAndPrune**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpData`](ue_ue.InterpData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpData`](ue_ue.InterpData.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpData`](ue_ue.InterpData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpData`](ue_ue.InterpData.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
