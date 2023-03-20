[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PropertyValue

# Class: PropertyValue

[ue/ue](../modules/ue_ue.md).PropertyValue

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PropertyValue`**

  ↳↳ [`PropertyValueColor`](ue_ue.PropertyValueColor.md)

  ↳↳ [`PropertyValueMaterial`](ue_ue.PropertyValueMaterial.md)

  ↳↳ [`PropertyValueOption`](ue_ue.PropertyValueOption.md)

  ↳↳ [`PropertyValueTransform`](ue_ue.PropertyValueTransform.md)

  ↳↳ [`PropertyValueVisibility`](ue_ue.PropertyValueVisibility.md)

## Table of contents

### Constructors

- [constructor](ue_ue.PropertyValue.md#constructor)

### Properties

- [CapturedPropSegments](ue_ue.PropertyValue.md#capturedpropsegments)
- [FullDisplayString](ue_ue.PropertyValue.md#fulldisplaystring)
- [LeafPropertyClass](ue_ue.PropertyValue.md#leafpropertyclass)
- [PropCategory](ue_ue.PropertyValue.md#propcategory)
- [Properties](ue_ue.PropertyValue.md#properties)
- [PropertyIndices](ue_ue.PropertyValue.md#propertyindices)
- [PropertySetterName](ue_ue.PropertyValue.md#propertysettername)
- [PropertySetterParameterDefaults](ue_ue.PropertyValue.md#propertysetterparameterdefaults)
- [ValueBytes](ue_ue.PropertyValue.md#valuebytes)
- [\_\_tid\_Object\_\_](ue_ue.PropertyValue.md#__tid_object__)
- [\_\_tid\_PropertyValue\_\_](ue_ue.PropertyValue.md#__tid_propertyvalue__)
- [bHasRecordedData](ue_ue.PropertyValue.md#bhasrecordeddata)

### Methods

- [CreateDefaultSubobject](ue_ue.PropertyValue.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PropertyValue.md#executeubergraph)
- [GetClass](ue_ue.PropertyValue.md#getclass)
- [GetFullDisplayString](ue_ue.PropertyValue.md#getfulldisplaystring)
- [GetName](ue_ue.PropertyValue.md#getname)
- [GetOuter](ue_ue.PropertyValue.md#getouter)
- [GetPropertyTooltip](ue_ue.PropertyValue.md#getpropertytooltip)
- [GetWorld](ue_ue.PropertyValue.md#getworld)
- [HasRecordedData](ue_ue.PropertyValue.md#hasrecordeddata)
- [Find](ue_ue.PropertyValue.md#find)
- [Load](ue_ue.PropertyValue.md#load)
- [StaticClass](ue_ue.PropertyValue.md#staticclass)

## Constructors

### constructor

• **new PropertyValue**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:29855](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29855)

## Properties

### CapturedPropSegments

• **CapturedPropSegments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CapturedPropSegment`](ue_ue.CapturedPropSegment.md)\>

#### Defined in

[ue/ue.d.ts:29858](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29858)

___

### FullDisplayString

• **FullDisplayString**: `string`

#### Defined in

[ue/ue.d.ts:29859](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29859)

___

### LeafPropertyClass

• **LeafPropertyClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:29863](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29863)

___

### PropCategory

• **PropCategory**: [`EPropertyValueCategory`](../enums/ue_ue.EPropertyValueCategory.md)

#### Defined in

[ue/ue.d.ts:29865](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29865)

___

### Properties

• **Properties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Property`](ue_ue.Property.md)\>

#### Defined in

[ue/ue.d.ts:29856](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29856)

___

### PropertyIndices

• **PropertyIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:29857](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29857)

___

### PropertySetterName

• **PropertySetterName**: `string`

#### Defined in

[ue/ue.d.ts:29860](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29860)

___

### PropertySetterParameterDefaults

• **PropertySetterParameterDefaults**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Defined in

[ue/ue.d.ts:29861](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29861)

___

### ValueBytes

• **ValueBytes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:29864](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29864)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PropertyValue\_\_

• **\_\_tid\_PropertyValue\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:29873](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29873)

___

### bHasRecordedData

• **bHasRecordedData**: `boolean`

#### Defined in

[ue/ue.d.ts:29862](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29862)

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

### GetFullDisplayString

▸ **GetFullDisplayString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:29866](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29866)

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

### GetPropertyTooltip

▸ **GetPropertyTooltip**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:29867](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29867)

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

### HasRecordedData

▸ **HasRecordedData**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:29868](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29868)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PropertyValue`](ue_ue.PropertyValue.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PropertyValue`](ue_ue.PropertyValue.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:29870](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29870)

___

### Load

▸ `Static` **Load**(`InName`): [`PropertyValue`](ue_ue.PropertyValue.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PropertyValue`](ue_ue.PropertyValue.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:29871](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29871)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:29869](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29869)
