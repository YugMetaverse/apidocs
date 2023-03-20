[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ToolMenuSectionExtensions

# Class: ToolMenuSectionExtensions

[ue/ue](../modules/ue_ue.md).ToolMenuSectionExtensions

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ToolMenuSectionExtensions`**

## Table of contents

### Constructors

- [constructor](ue_ue.ToolMenuSectionExtensions.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.ToolMenuSectionExtensions.md#__tid_object__)
- [\_\_tid\_ToolMenuSectionExtensions\_\_](ue_ue.ToolMenuSectionExtensions.md#__tid_toolmenusectionextensions__)

### Methods

- [CreateDefaultSubobject](ue_ue.ToolMenuSectionExtensions.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ToolMenuSectionExtensions.md#executeubergraph)
- [GetClass](ue_ue.ToolMenuSectionExtensions.md#getclass)
- [GetName](ue_ue.ToolMenuSectionExtensions.md#getname)
- [GetOuter](ue_ue.ToolMenuSectionExtensions.md#getouter)
- [GetWorld](ue_ue.ToolMenuSectionExtensions.md#getworld)
- [AddEntry](ue_ue.ToolMenuSectionExtensions.md#addentry)
- [AddEntryObject](ue_ue.ToolMenuSectionExtensions.md#addentryobject)
- [Find](ue_ue.ToolMenuSectionExtensions.md#find)
- [GetLabel](ue_ue.ToolMenuSectionExtensions.md#getlabel)
- [Load](ue_ue.ToolMenuSectionExtensions.md#load)
- [SetLabel](ue_ue.ToolMenuSectionExtensions.md#setlabel)
- [StaticClass](ue_ue.ToolMenuSectionExtensions.md#staticclass)

## Constructors

### constructor

• **new ToolMenuSectionExtensions**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_ToolMenuSectionExtensions\_\_

• **\_\_tid\_ToolMenuSectionExtensions\_\_**: `boolean`

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

### AddEntry

▸ `Static` **AddEntry**(`Section`, `Args`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Section` | [`$Ref`](../interfaces/puerts._Ref.md)<[`ToolMenuSection`](ue_ue.ToolMenuSection.md)\> |
| `Args` | [`ToolMenuEntry`](ue_ue.ToolMenuEntry.md) |

#### Returns

`void`

___

### AddEntryObject

▸ `Static` **AddEntryObject**(`Section`, `InObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Section` | [`$Ref`](../interfaces/puerts._Ref.md)<[`ToolMenuSection`](ue_ue.ToolMenuSection.md)\> |
| `InObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ToolMenuEntryScript`](ue_ue.ToolMenuEntryScript.md)\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ToolMenuSectionExtensions`](ue_ue.ToolMenuSectionExtensions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ToolMenuSectionExtensions`](ue_ue.ToolMenuSectionExtensions.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### GetLabel

▸ `Static` **GetLabel**(`Section`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Section` | [`ToolMenuSection`](ue_ue.ToolMenuSection.md) |

#### Returns

`string`

___

### Load

▸ `Static` **Load**(`InName`): [`ToolMenuSectionExtensions`](ue_ue.ToolMenuSectionExtensions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ToolMenuSectionExtensions`](ue_ue.ToolMenuSectionExtensions.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### SetLabel

▸ `Static` **SetLabel**(`Section`, `Label`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Section` | [`$Ref`](../interfaces/puerts._Ref.md)<[`ToolMenuSection`](ue_ue.ToolMenuSection.md)\> |
| `Label` | `string` |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
