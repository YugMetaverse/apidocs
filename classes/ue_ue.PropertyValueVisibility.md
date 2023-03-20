[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PropertyValueVisibility

# Class: PropertyValueVisibility

[ue/ue](../modules/ue_ue.md).PropertyValueVisibility

## Hierarchy

- [`PropertyValue`](ue_ue.PropertyValue.md)

  ↳ **`PropertyValueVisibility`**

## Table of contents

### Constructors

- [constructor](ue_ue.PropertyValueVisibility.md#constructor)

### Properties

- [CapturedPropSegments](ue_ue.PropertyValueVisibility.md#capturedpropsegments)
- [FullDisplayString](ue_ue.PropertyValueVisibility.md#fulldisplaystring)
- [LeafPropertyClass](ue_ue.PropertyValueVisibility.md#leafpropertyclass)
- [PropCategory](ue_ue.PropertyValueVisibility.md#propcategory)
- [Properties](ue_ue.PropertyValueVisibility.md#properties)
- [PropertyIndices](ue_ue.PropertyValueVisibility.md#propertyindices)
- [PropertySetterName](ue_ue.PropertyValueVisibility.md#propertysettername)
- [PropertySetterParameterDefaults](ue_ue.PropertyValueVisibility.md#propertysetterparameterdefaults)
- [ValueBytes](ue_ue.PropertyValueVisibility.md#valuebytes)
- [\_\_tid\_Object\_\_](ue_ue.PropertyValueVisibility.md#__tid_object__)
- [\_\_tid\_PropertyValueVisibility\_\_](ue_ue.PropertyValueVisibility.md#__tid_propertyvaluevisibility__)
- [\_\_tid\_PropertyValue\_\_](ue_ue.PropertyValueVisibility.md#__tid_propertyvalue__)
- [bHasRecordedData](ue_ue.PropertyValueVisibility.md#bhasrecordeddata)

### Methods

- [CreateDefaultSubobject](ue_ue.PropertyValueVisibility.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PropertyValueVisibility.md#executeubergraph)
- [GetClass](ue_ue.PropertyValueVisibility.md#getclass)
- [GetFullDisplayString](ue_ue.PropertyValueVisibility.md#getfulldisplaystring)
- [GetName](ue_ue.PropertyValueVisibility.md#getname)
- [GetOuter](ue_ue.PropertyValueVisibility.md#getouter)
- [GetPropertyTooltip](ue_ue.PropertyValueVisibility.md#getpropertytooltip)
- [GetWorld](ue_ue.PropertyValueVisibility.md#getworld)
- [HasRecordedData](ue_ue.PropertyValueVisibility.md#hasrecordeddata)
- [Find](ue_ue.PropertyValueVisibility.md#find)
- [Load](ue_ue.PropertyValueVisibility.md#load)
- [StaticClass](ue_ue.PropertyValueVisibility.md#staticclass)

## Constructors

### constructor

• **new PropertyValueVisibility**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PropertyValue](ue_ue.PropertyValue.md).[constructor](ue_ue.PropertyValue.md#constructor)

## Properties

### CapturedPropSegments

• **CapturedPropSegments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CapturedPropSegment`](ue_ue.CapturedPropSegment.md)\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[CapturedPropSegments](ue_ue.PropertyValue.md#capturedpropsegments)

___

### FullDisplayString

• **FullDisplayString**: `string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[FullDisplayString](ue_ue.PropertyValue.md#fulldisplaystring)

___

### LeafPropertyClass

• **LeafPropertyClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[LeafPropertyClass](ue_ue.PropertyValue.md#leafpropertyclass)

___

### PropCategory

• **PropCategory**: [`EPropertyValueCategory`](../enums/ue_ue.EPropertyValueCategory.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[PropCategory](ue_ue.PropertyValue.md#propcategory)

___

### Properties

• **Properties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Property`](ue_ue.Property.md)\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[Properties](ue_ue.PropertyValue.md#properties)

___

### PropertyIndices

• **PropertyIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[PropertyIndices](ue_ue.PropertyValue.md#propertyindices)

___

### PropertySetterName

• **PropertySetterName**: `string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[PropertySetterName](ue_ue.PropertyValue.md#propertysettername)

___

### PropertySetterParameterDefaults

• **PropertySetterParameterDefaults**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[PropertySetterParameterDefaults](ue_ue.PropertyValue.md#propertysetterparameterdefaults)

___

### ValueBytes

• **ValueBytes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[ValueBytes](ue_ue.PropertyValue.md#valuebytes)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[__tid_Object__](ue_ue.PropertyValue.md#__tid_object__)

___

### \_\_tid\_PropertyValueVisibility\_\_

• **\_\_tid\_PropertyValueVisibility\_\_**: `boolean`

___

### \_\_tid\_PropertyValue\_\_

• **\_\_tid\_PropertyValue\_\_**: `boolean`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[__tid_PropertyValue__](ue_ue.PropertyValue.md#__tid_propertyvalue__)

___

### bHasRecordedData

• **bHasRecordedData**: `boolean`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[bHasRecordedData](ue_ue.PropertyValue.md#bhasrecordeddata)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetClass](ue_ue.PropertyValue.md#getclass)

___

### GetFullDisplayString

▸ **GetFullDisplayString**(): `string`

#### Returns

`string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetFullDisplayString](ue_ue.PropertyValue.md#getfulldisplaystring)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetName](ue_ue.PropertyValue.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetOuter](ue_ue.PropertyValue.md#getouter)

___

### GetPropertyTooltip

▸ **GetPropertyTooltip**(): `string`

#### Returns

`string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetPropertyTooltip](ue_ue.PropertyValue.md#getpropertytooltip)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetWorld](ue_ue.PropertyValue.md#getworld)

___

### HasRecordedData

▸ **HasRecordedData**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[HasRecordedData](ue_ue.PropertyValue.md#hasrecordeddata)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PropertyValueVisibility`](ue_ue.PropertyValueVisibility.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PropertyValueVisibility`](ue_ue.PropertyValueVisibility.md)

#### Overrides

[PropertyValue](ue_ue.PropertyValue.md).[Find](ue_ue.PropertyValue.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PropertyValueVisibility`](ue_ue.PropertyValueVisibility.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PropertyValueVisibility`](ue_ue.PropertyValueVisibility.md)

#### Overrides

[PropertyValue](ue_ue.PropertyValue.md).[Load](ue_ue.PropertyValue.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PropertyValue](ue_ue.PropertyValue.md).[StaticClass](ue_ue.PropertyValue.md#staticclass)
