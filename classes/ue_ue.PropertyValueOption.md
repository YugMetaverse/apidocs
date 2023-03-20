[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PropertyValueOption

# Class: PropertyValueOption

[ue/ue](../modules/ue_ue.md).PropertyValueOption

## Hierarchy

- [`PropertyValue`](ue_ue.PropertyValue.md)

  ↳ **`PropertyValueOption`**

## Table of contents

### Constructors

- [constructor](ue_ue.PropertyValueOption.md#constructor)

### Properties

- [CapturedPropSegments](ue_ue.PropertyValueOption.md#capturedpropsegments)
- [FullDisplayString](ue_ue.PropertyValueOption.md#fulldisplaystring)
- [LeafPropertyClass](ue_ue.PropertyValueOption.md#leafpropertyclass)
- [PropCategory](ue_ue.PropertyValueOption.md#propcategory)
- [Properties](ue_ue.PropertyValueOption.md#properties)
- [PropertyIndices](ue_ue.PropertyValueOption.md#propertyindices)
- [PropertySetterName](ue_ue.PropertyValueOption.md#propertysettername)
- [PropertySetterParameterDefaults](ue_ue.PropertyValueOption.md#propertysetterparameterdefaults)
- [ValueBytes](ue_ue.PropertyValueOption.md#valuebytes)
- [\_\_tid\_Object\_\_](ue_ue.PropertyValueOption.md#__tid_object__)
- [\_\_tid\_PropertyValueOption\_\_](ue_ue.PropertyValueOption.md#__tid_propertyvalueoption__)
- [\_\_tid\_PropertyValue\_\_](ue_ue.PropertyValueOption.md#__tid_propertyvalue__)
- [bHasRecordedData](ue_ue.PropertyValueOption.md#bhasrecordeddata)

### Methods

- [CreateDefaultSubobject](ue_ue.PropertyValueOption.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PropertyValueOption.md#executeubergraph)
- [GetClass](ue_ue.PropertyValueOption.md#getclass)
- [GetFullDisplayString](ue_ue.PropertyValueOption.md#getfulldisplaystring)
- [GetName](ue_ue.PropertyValueOption.md#getname)
- [GetOuter](ue_ue.PropertyValueOption.md#getouter)
- [GetPropertyTooltip](ue_ue.PropertyValueOption.md#getpropertytooltip)
- [GetWorld](ue_ue.PropertyValueOption.md#getworld)
- [HasRecordedData](ue_ue.PropertyValueOption.md#hasrecordeddata)
- [Find](ue_ue.PropertyValueOption.md#find)
- [Load](ue_ue.PropertyValueOption.md#load)
- [StaticClass](ue_ue.PropertyValueOption.md#staticclass)

## Constructors

### constructor

• **new PropertyValueOption**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PropertyValue](ue_ue.PropertyValue.md).[constructor](ue_ue.PropertyValue.md#constructor)

#### Defined in

[ue/ue.d.ts:58917](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58917)

## Properties

### CapturedPropSegments

• **CapturedPropSegments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CapturedPropSegment`](ue_ue.CapturedPropSegment.md)\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[CapturedPropSegments](ue_ue.PropertyValue.md#capturedpropsegments)

#### Defined in

[ue/ue.d.ts:29858](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29858)

___

### FullDisplayString

• **FullDisplayString**: `string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[FullDisplayString](ue_ue.PropertyValue.md#fulldisplaystring)

#### Defined in

[ue/ue.d.ts:29859](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29859)

___

### LeafPropertyClass

• **LeafPropertyClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[LeafPropertyClass](ue_ue.PropertyValue.md#leafpropertyclass)

#### Defined in

[ue/ue.d.ts:29863](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29863)

___

### PropCategory

• **PropCategory**: [`EPropertyValueCategory`](../enums/ue_ue.EPropertyValueCategory.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[PropCategory](ue_ue.PropertyValue.md#propcategory)

#### Defined in

[ue/ue.d.ts:29865](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29865)

___

### Properties

• **Properties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Property`](ue_ue.Property.md)\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[Properties](ue_ue.PropertyValue.md#properties)

#### Defined in

[ue/ue.d.ts:29856](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29856)

___

### PropertyIndices

• **PropertyIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[PropertyIndices](ue_ue.PropertyValue.md#propertyindices)

#### Defined in

[ue/ue.d.ts:29857](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29857)

___

### PropertySetterName

• **PropertySetterName**: `string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[PropertySetterName](ue_ue.PropertyValue.md#propertysettername)

#### Defined in

[ue/ue.d.ts:29860](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29860)

___

### PropertySetterParameterDefaults

• **PropertySetterParameterDefaults**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[PropertySetterParameterDefaults](ue_ue.PropertyValue.md#propertysetterparameterdefaults)

#### Defined in

[ue/ue.d.ts:29861](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29861)

___

### ValueBytes

• **ValueBytes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[ValueBytes](ue_ue.PropertyValue.md#valuebytes)

#### Defined in

[ue/ue.d.ts:29864](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29864)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[__tid_Object__](ue_ue.PropertyValue.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PropertyValueOption\_\_

• **\_\_tid\_PropertyValueOption\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:58922](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58922)

___

### \_\_tid\_PropertyValue\_\_

• **\_\_tid\_PropertyValue\_\_**: `boolean`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[__tid_PropertyValue__](ue_ue.PropertyValue.md#__tid_propertyvalue__)

#### Defined in

[ue/ue.d.ts:29873](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29873)

___

### bHasRecordedData

• **bHasRecordedData**: `boolean`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[bHasRecordedData](ue_ue.PropertyValue.md#bhasrecordeddata)

#### Defined in

[ue/ue.d.ts:29862](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29862)

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

[PropertyValue](ue_ue.PropertyValue.md).[CreateDefaultSubobject](ue_ue.PropertyValue.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[PropertyValue](ue_ue.PropertyValue.md).[ExecuteUbergraph](ue_ue.PropertyValue.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetClass](ue_ue.PropertyValue.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetFullDisplayString

▸ **GetFullDisplayString**(): `string`

#### Returns

`string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetFullDisplayString](ue_ue.PropertyValue.md#getfulldisplaystring)

#### Defined in

[ue/ue.d.ts:29866](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29866)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetName](ue_ue.PropertyValue.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetOuter](ue_ue.PropertyValue.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetPropertyTooltip

▸ **GetPropertyTooltip**(): `string`

#### Returns

`string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetPropertyTooltip](ue_ue.PropertyValue.md#getpropertytooltip)

#### Defined in

[ue/ue.d.ts:29867](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29867)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetWorld](ue_ue.PropertyValue.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HasRecordedData

▸ **HasRecordedData**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[HasRecordedData](ue_ue.PropertyValue.md#hasrecordeddata)

#### Defined in

[ue/ue.d.ts:29868](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29868)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PropertyValueOption`](ue_ue.PropertyValueOption.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PropertyValueOption`](ue_ue.PropertyValueOption.md)

#### Overrides

[PropertyValue](ue_ue.PropertyValue.md).[Find](ue_ue.PropertyValue.md#find)

#### Defined in

[ue/ue.d.ts:58919](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58919)

___

### Load

▸ `Static` **Load**(`InName`): [`PropertyValueOption`](ue_ue.PropertyValueOption.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PropertyValueOption`](ue_ue.PropertyValueOption.md)

#### Overrides

[PropertyValue](ue_ue.PropertyValue.md).[Load](ue_ue.PropertyValue.md#load)

#### Defined in

[ue/ue.d.ts:58920](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58920)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PropertyValue](ue_ue.PropertyValue.md).[StaticClass](ue_ue.PropertyValue.md#staticclass)

#### Defined in

[ue/ue.d.ts:58918](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58918)
