[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavLinkTrivial

# Class: NavLinkTrivial

[ue/ue](../modules/ue_ue.md).NavLinkTrivial

## Hierarchy

- [`NavLinkDefinition`](ue_ue.NavLinkDefinition.md)

  ↳ **`NavLinkTrivial`**

## Table of contents

### Constructors

- [constructor](ue_ue.NavLinkTrivial.md#constructor)

### Properties

- [Links](ue_ue.NavLinkTrivial.md#links)
- [SegmentLinks](ue_ue.NavLinkTrivial.md#segmentlinks)
- [\_\_tid\_NavLinkDefinition\_\_](ue_ue.NavLinkTrivial.md#__tid_navlinkdefinition__)
- [\_\_tid\_NavLinkTrivial\_\_](ue_ue.NavLinkTrivial.md#__tid_navlinktrivial__)
- [\_\_tid\_Object\_\_](ue_ue.NavLinkTrivial.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.NavLinkTrivial.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NavLinkTrivial.md#executeubergraph)
- [GetClass](ue_ue.NavLinkTrivial.md#getclass)
- [GetName](ue_ue.NavLinkTrivial.md#getname)
- [GetOuter](ue_ue.NavLinkTrivial.md#getouter)
- [GetWorld](ue_ue.NavLinkTrivial.md#getworld)
- [Find](ue_ue.NavLinkTrivial.md#find)
- [Load](ue_ue.NavLinkTrivial.md#load)
- [StaticClass](ue_ue.NavLinkTrivial.md#staticclass)

## Constructors

### constructor

• **new NavLinkTrivial**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[constructor](ue_ue.NavLinkDefinition.md#constructor)

## Properties

### Links

• **Links**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NavigationLink`](ue_ue.NavigationLink.md)\>

#### Inherited from

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[Links](ue_ue.NavLinkDefinition.md#links)

___

### SegmentLinks

• **SegmentLinks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NavigationSegmentLink`](ue_ue.NavigationSegmentLink.md)\>

#### Inherited from

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[SegmentLinks](ue_ue.NavLinkDefinition.md#segmentlinks)

___

### \_\_tid\_NavLinkDefinition\_\_

• **\_\_tid\_NavLinkDefinition\_\_**: `boolean`

#### Inherited from

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[__tid_NavLinkDefinition__](ue_ue.NavLinkDefinition.md#__tid_navlinkdefinition__)

___

### \_\_tid\_NavLinkTrivial\_\_

• **\_\_tid\_NavLinkTrivial\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[__tid_Object__](ue_ue.NavLinkDefinition.md#__tid_object__)

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

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[CreateDefaultSubobject](ue_ue.NavLinkDefinition.md#createdefaultsubobject)

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

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[ExecuteUbergraph](ue_ue.NavLinkDefinition.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[GetClass](ue_ue.NavLinkDefinition.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[GetName](ue_ue.NavLinkDefinition.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[GetOuter](ue_ue.NavLinkDefinition.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[GetWorld](ue_ue.NavLinkDefinition.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NavLinkTrivial`](ue_ue.NavLinkTrivial.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NavLinkTrivial`](ue_ue.NavLinkTrivial.md)

#### Overrides

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[Find](ue_ue.NavLinkDefinition.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`NavLinkTrivial`](ue_ue.NavLinkTrivial.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NavLinkTrivial`](ue_ue.NavLinkTrivial.md)

#### Overrides

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[Load](ue_ue.NavLinkDefinition.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NavLinkDefinition](ue_ue.NavLinkDefinition.md).[StaticClass](ue_ue.NavLinkDefinition.md#staticclass)
