[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SlateAccessibleWidgetData

# Class: SlateAccessibleWidgetData

[ue/ue](../modules/ue_ue.md).SlateAccessibleWidgetData

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SlateAccessibleWidgetData`**

## Table of contents

### Constructors

- [constructor](ue_ue.SlateAccessibleWidgetData.md#constructor)

### Properties

- [AccessibleBehavior](ue_ue.SlateAccessibleWidgetData.md#accessiblebehavior)
- [AccessibleSummaryBehavior](ue_ue.SlateAccessibleWidgetData.md#accessiblesummarybehavior)
- [AccessibleSummaryText](ue_ue.SlateAccessibleWidgetData.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](ue_ue.SlateAccessibleWidgetData.md#accessiblesummarytextdelegate)
- [AccessibleText](ue_ue.SlateAccessibleWidgetData.md#accessibletext)
- [AccessibleTextDelegate](ue_ue.SlateAccessibleWidgetData.md#accessibletextdelegate)
- [\_\_tid\_Object\_\_](ue_ue.SlateAccessibleWidgetData.md#__tid_object__)
- [\_\_tid\_SlateAccessibleWidgetData\_\_](ue_ue.SlateAccessibleWidgetData.md#__tid_slateaccessiblewidgetdata__)
- [bCanChildrenBeAccessible](ue_ue.SlateAccessibleWidgetData.md#bcanchildrenbeaccessible)

### Methods

- [CreateDefaultSubobject](ue_ue.SlateAccessibleWidgetData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SlateAccessibleWidgetData.md#executeubergraph)
- [GetClass](ue_ue.SlateAccessibleWidgetData.md#getclass)
- [GetName](ue_ue.SlateAccessibleWidgetData.md#getname)
- [GetOuter](ue_ue.SlateAccessibleWidgetData.md#getouter)
- [GetText\_\_DelegateSignature](ue_ue.SlateAccessibleWidgetData.md#gettext__delegatesignature)
- [GetWorld](ue_ue.SlateAccessibleWidgetData.md#getworld)
- [Find](ue_ue.SlateAccessibleWidgetData.md#find)
- [Load](ue_ue.SlateAccessibleWidgetData.md#load)
- [StaticClass](ue_ue.SlateAccessibleWidgetData.md#staticclass)

## Constructors

### constructor

• **new SlateAccessibleWidgetData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:10725](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10725)

## Properties

### AccessibleBehavior

• **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Defined in

[ue/ue.d.ts:10727](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10727)

___

### AccessibleSummaryBehavior

• **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Defined in

[ue/ue.d.ts:10728](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10728)

___

### AccessibleSummaryText

• **AccessibleSummaryText**: `string`

#### Defined in

[ue/ue.d.ts:10731](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10731)

___

### AccessibleSummaryTextDelegate

• **AccessibleSummaryTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Defined in

[ue/ue.d.ts:10732](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10732)

___

### AccessibleText

• **AccessibleText**: `string`

#### Defined in

[ue/ue.d.ts:10729](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10729)

___

### AccessibleTextDelegate

• **AccessibleTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Defined in

[ue/ue.d.ts:10730](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10730)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SlateAccessibleWidgetData\_\_

• **\_\_tid\_SlateAccessibleWidgetData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:10738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10738)

___

### bCanChildrenBeAccessible

• **bCanChildrenBeAccessible**: `boolean`

#### Defined in

[ue/ue.d.ts:10726](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10726)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetText\_\_DelegateSignature

▸ **GetText__DelegateSignature**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:10733](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10733)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:10735](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10735)

___

### Load

▸ `Static` **Load**(`InName`): [`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:10736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10736)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:10734](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10734)
