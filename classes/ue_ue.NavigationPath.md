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

#### Defined in

[ue/ue.d.ts:14718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14718)

## Properties

### PathPoints

• **PathPoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:14720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14720)

___

### PathUpdatedNotifier

• **PathUpdatedNotifier**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`AffectedPath`: [`$Nullable`](../modules/puerts.md#$nullable)<[`NavigationPath`](ue_ue.NavigationPath.md)\>, `PathEvent`: [`ENavPathEvent`](../enums/ue_ue.ENavPathEvent.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:14719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14719)

___

### RecalculateOnInvalidation

• **RecalculateOnInvalidation**: [`ENavigationOptionFlag`](../enums/ue_ue.ENavigationOptionFlag.md)

#### Defined in

[ue/ue.d.ts:14721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14721)

___

### \_\_tid\_NavigationPath\_\_

• **\_\_tid\_NavigationPath\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14734)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

### EnableDebugDrawing

▸ **EnableDebugDrawing**(`bShouldDrawDebugData`, `PathColor?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bShouldDrawDebugData` | `boolean` |
| `PathColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14722)

___

### EnableRecalculationOnInvalidation

▸ **EnableRecalculationOnInvalidation**(`DoRecalculation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DoRecalculation` | [`ENavigationOptionFlag`](../enums/ue_ue.ENavigationOptionFlag.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14723)

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

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetDebugString

▸ **GetDebugString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:14724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14724)

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

### GetPathCost

▸ **GetPathCost**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:14725](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14725)

___

### GetPathLength

▸ **GetPathLength**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:14726](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14726)

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

### IsPartial

▸ **IsPartial**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14727](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14727)

___

### IsStringPulled

▸ **IsStringPulled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14728](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14728)

___

### IsValid

▸ **IsValid**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14729)

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

#### Defined in

[ue/ue.d.ts:14731](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14731)

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

#### Defined in

[ue/ue.d.ts:14732](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14732)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:14730](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14730)
