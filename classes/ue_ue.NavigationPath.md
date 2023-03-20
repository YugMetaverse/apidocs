[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavigationPath

# Class: NavigationPath

[ue/ue](../modules/ue_ue.md).NavigationPath

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`NavigationPath`**

## Table of contents

### Constructors

- [constructor](ue_ue.NavigationPath.md#constructor)

### Properties

- [PathPoints](ue_ue.NavigationPath.md#pathpoints)
- [PathUpdatedNotifier](ue_ue.NavigationPath.md#pathupdatednotifier)
- [RecalculateOnInvalidation](ue_ue.NavigationPath.md#recalculateoninvalidation)
- [\_\_tid\_NavigationPath\_\_](ue_ue.NavigationPath.md#__tid_navigationpath__)
- [\_\_tid\_Object\_\_](ue_ue.NavigationPath.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.NavigationPath.md#createdefaultsubobject)
- [EnableDebugDrawing](ue_ue.NavigationPath.md#enabledebugdrawing)
- [EnableRecalculationOnInvalidation](ue_ue.NavigationPath.md#enablerecalculationoninvalidation)
- [ExecuteUbergraph](ue_ue.NavigationPath.md#executeubergraph)
- [GetClass](ue_ue.NavigationPath.md#getclass)
- [GetDebugString](ue_ue.NavigationPath.md#getdebugstring)
- [GetName](ue_ue.NavigationPath.md#getname)
- [GetOuter](ue_ue.NavigationPath.md#getouter)
- [GetPathCost](ue_ue.NavigationPath.md#getpathcost)
- [GetPathLength](ue_ue.NavigationPath.md#getpathlength)
- [GetWorld](ue_ue.NavigationPath.md#getworld)
- [IsPartial](ue_ue.NavigationPath.md#ispartial)
- [IsStringPulled](ue_ue.NavigationPath.md#isstringpulled)
- [IsValid](ue_ue.NavigationPath.md#isvalid)
- [Find](ue_ue.NavigationPath.md#find)
- [Load](ue_ue.NavigationPath.md#load)
- [StaticClass](ue_ue.NavigationPath.md#staticclass)

## Constructors

### constructor

• **new NavigationPath**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### PathPoints

• **PathPoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### PathUpdatedNotifier

• **PathUpdatedNotifier**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`AffectedPath`: [`$Nullable`](../modules/puerts.md#$nullable)<[`NavigationPath`](ue_ue.NavigationPath.md)\>, `PathEvent`: [`ENavPathEvent`](../enums/ue_ue.ENavPathEvent.md)) => `void`\>

___

### RecalculateOnInvalidation

• **RecalculateOnInvalidation**: [`ENavigationOptionFlag`](../enums/ue_ue.ENavigationOptionFlag.md)

___

### \_\_tid\_NavigationPath\_\_

• **\_\_tid\_NavigationPath\_\_**: `boolean`

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

### EnableDebugDrawing

▸ **EnableDebugDrawing**(`bShouldDrawDebugData`, `PathColor?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bShouldDrawDebugData` | `boolean` |
| `PathColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

___

### EnableRecalculationOnInvalidation

▸ **EnableRecalculationOnInvalidation**(`DoRecalculation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DoRecalculation` | [`ENavigationOptionFlag`](../enums/ue_ue.ENavigationOptionFlag.md) |

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

### GetDebugString

▸ **GetDebugString**(): `string`

#### Returns

`string`

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

### GetPathCost

▸ **GetPathCost**(): `number`

#### Returns

`number`

___

### GetPathLength

▸ **GetPathLength**(): `number`

#### Returns

`number`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### IsPartial

▸ **IsPartial**(): `boolean`

#### Returns

`boolean`

___

### IsStringPulled

▸ **IsStringPulled**(): `boolean`

#### Returns

`boolean`

___

### IsValid

▸ **IsValid**(): `boolean`

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NavigationPath`](ue_ue.NavigationPath.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NavigationPath`](ue_ue.NavigationPath.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`NavigationPath`](ue_ue.NavigationPath.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NavigationPath`](ue_ue.NavigationPath.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
