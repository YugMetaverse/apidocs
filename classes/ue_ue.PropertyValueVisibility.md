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

#### Defined in

[ue/ue.d.ts:58935](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58935)

## Properties

### CapturedPropSegments

• **CapturedPropSegments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CapturedPropSegment`](ue_ue.CapturedPropSegment.md)\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[CapturedPropSegments](ue_ue.PropertyValue.md#capturedpropsegments)

#### Defined in

[ue/ue.d.ts:29858](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29858)

___

### FullDisplayString

• **FullDisplayString**: `string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[FullDisplayString](ue_ue.PropertyValue.md#fulldisplaystring)

#### Defined in

[ue/ue.d.ts:29859](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29859)

___

### LeafPropertyClass

• **LeafPropertyClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[LeafPropertyClass](ue_ue.PropertyValue.md#leafpropertyclass)

#### Defined in

[ue/ue.d.ts:29863](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29863)

___

### PropCategory

• **PropCategory**: [`EPropertyValueCategory`](../enums/ue_ue.EPropertyValueCategory.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[PropCategory](ue_ue.PropertyValue.md#propcategory)

#### Defined in

[ue/ue.d.ts:29865](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29865)

___

### Properties

• **Properties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Property`](ue_ue.Property.md)\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[Properties](ue_ue.PropertyValue.md#properties)

#### Defined in

[ue/ue.d.ts:29856](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29856)

___

### PropertyIndices

• **PropertyIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[PropertyIndices](ue_ue.PropertyValue.md#propertyindices)

#### Defined in

[ue/ue.d.ts:29857](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29857)

___

### PropertySetterName

• **PropertySetterName**: `string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[PropertySetterName](ue_ue.PropertyValue.md#propertysettername)

#### Defined in

[ue/ue.d.ts:29860](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29860)

___

### PropertySetterParameterDefaults

• **PropertySetterParameterDefaults**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[PropertySetterParameterDefaults](ue_ue.PropertyValue.md#propertysetterparameterdefaults)

#### Defined in

[ue/ue.d.ts:29861](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29861)

___

### ValueBytes

• **ValueBytes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[ValueBytes](ue_ue.PropertyValue.md#valuebytes)

#### Defined in

[ue/ue.d.ts:29864](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29864)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[__tid_Object__](ue_ue.PropertyValue.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PropertyValueVisibility\_\_

• **\_\_tid\_PropertyValueVisibility\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:58940](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58940)

___

### \_\_tid\_PropertyValue\_\_

• **\_\_tid\_PropertyValue\_\_**: `boolean`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[__tid_PropertyValue__](ue_ue.PropertyValue.md#__tid_propertyvalue__)

#### Defined in

[ue/ue.d.ts:29873](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29873)

___

### bHasRecordedData

• **bHasRecordedData**: `boolean`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[bHasRecordedData](ue_ue.PropertyValue.md#bhasrecordeddata)

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

[PropertyValue](ue_ue.PropertyValue.md).[CreateDefaultSubobject](ue_ue.PropertyValue.md#createdefaultsubobject)

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

[PropertyValue](ue_ue.PropertyValue.md).[ExecuteUbergraph](ue_ue.PropertyValue.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetClass](ue_ue.PropertyValue.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetFullDisplayString

▸ **GetFullDisplayString**(): `string`

#### Returns

`string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetFullDisplayString](ue_ue.PropertyValue.md#getfulldisplaystring)

#### Defined in

[ue/ue.d.ts:29866](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29866)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetName](ue_ue.PropertyValue.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetOuter](ue_ue.PropertyValue.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetPropertyTooltip

▸ **GetPropertyTooltip**(): `string`

#### Returns

`string`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetPropertyTooltip](ue_ue.PropertyValue.md#getpropertytooltip)

#### Defined in

[ue/ue.d.ts:29867](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29867)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[GetWorld](ue_ue.PropertyValue.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### HasRecordedData

▸ **HasRecordedData**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PropertyValue](ue_ue.PropertyValue.md).[HasRecordedData](ue_ue.PropertyValue.md#hasrecordeddata)

#### Defined in

[ue/ue.d.ts:29868](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29868)

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

#### Defined in

[ue/ue.d.ts:58937](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58937)

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

#### Defined in

[ue/ue.d.ts:58938](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58938)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PropertyValue](ue_ue.PropertyValue.md).[StaticClass](ue_ue.PropertyValue.md#staticclass)

#### Defined in

[ue/ue.d.ts:58936](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58936)
