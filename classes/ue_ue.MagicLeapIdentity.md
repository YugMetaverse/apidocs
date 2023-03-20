[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapIdentity

# Class: MagicLeapIdentity

[ue/ue](../modules/ue_ue.md).MagicLeapIdentity

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MagicLeapIdentity`**

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapIdentity.md#constructor)

### Properties

- [\_\_tid\_MagicLeapIdentity\_\_](ue_ue.MagicLeapIdentity.md#__tid_magicleapidentity__)
- [\_\_tid\_Object\_\_](ue_ue.MagicLeapIdentity.md#__tid_object__)

### Methods

- [AvailableIdentityAttributesDelegate\_\_DelegateSignature](ue_ue.MagicLeapIdentity.md#availableidentityattributesdelegate__delegatesignature)
- [CreateDefaultSubobject](ue_ue.MagicLeapIdentity.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MagicLeapIdentity.md#executeubergraph)
- [GetAllAvailableAttributes](ue_ue.MagicLeapIdentity.md#getallavailableattributes)
- [GetAllAvailableAttributesAsync](ue_ue.MagicLeapIdentity.md#getallavailableattributesasync)
- [GetClass](ue_ue.MagicLeapIdentity.md#getclass)
- [GetName](ue_ue.MagicLeapIdentity.md#getname)
- [GetOuter](ue_ue.MagicLeapIdentity.md#getouter)
- [GetWorld](ue_ue.MagicLeapIdentity.md#getworld)
- [ModifyIdentityAttributeValueDelegate\_\_DelegateSignature](ue_ue.MagicLeapIdentity.md#modifyidentityattributevaluedelegate__delegatesignature)
- [RequestAttributeValue](ue_ue.MagicLeapIdentity.md#requestattributevalue)
- [RequestAttributeValueAsync](ue_ue.MagicLeapIdentity.md#requestattributevalueasync)
- [RequestIdentityAttributeValueDelegate\_\_DelegateSignature](ue_ue.MagicLeapIdentity.md#requestidentityattributevaluedelegate__delegatesignature)
- [Find](ue_ue.MagicLeapIdentity.md#find)
- [Load](ue_ue.MagicLeapIdentity.md#load)
- [StaticClass](ue_ue.MagicLeapIdentity.md#staticclass)

## Constructors

### constructor

• **new MagicLeapIdentity**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_MagicLeapIdentity\_\_

• **\_\_tid\_MagicLeapIdentity\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

## Methods

### AvailableIdentityAttributesDelegate\_\_DelegateSignature

▸ **AvailableIdentityAttributesDelegate__DelegateSignature**(`ResultCode`, `AvailableAttributes`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ResultCode` | [`EMagicLeapIdentityError`](../enums/ue_ue.EMagicLeapIdentityError.md) |
| `AvailableAttributes` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EMagicLeapIdentityKey`](../enums/ue_ue.EMagicLeapIdentityKey.md)\> |

#### Returns

`void`

___

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

### GetAllAvailableAttributes

▸ **GetAllAvailableAttributes**(`AvailableAttributes`): [`EMagicLeapIdentityError`](../enums/ue_ue.EMagicLeapIdentityError.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AvailableAttributes` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EMagicLeapIdentityKey`](../enums/ue_ue.EMagicLeapIdentityKey.md)\>\> |

#### Returns

[`EMagicLeapIdentityError`](../enums/ue_ue.EMagicLeapIdentityError.md)

___

### GetAllAvailableAttributesAsync

▸ **GetAllAvailableAttributesAsync**(`ResultDelegate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ResultDelegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`ResultCode`: [`EMagicLeapIdentityError`](../enums/ue_ue.EMagicLeapIdentityError.md), `AvailableAttributes`: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EMagicLeapIdentityKey`](../enums/ue_ue.EMagicLeapIdentityKey.md)\>) => `void`\> |

#### Returns

`void`

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

### ModifyIdentityAttributeValueDelegate\_\_DelegateSignature

▸ **ModifyIdentityAttributeValueDelegate__DelegateSignature**(`ResultCode`, `AttributesUpdatedSuccessfully`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ResultCode` | [`EMagicLeapIdentityError`](../enums/ue_ue.EMagicLeapIdentityError.md) |
| `AttributesUpdatedSuccessfully` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EMagicLeapIdentityKey`](../enums/ue_ue.EMagicLeapIdentityKey.md)\> |

#### Returns

`void`

___

### RequestAttributeValue

▸ **RequestAttributeValue**(`RequestedAttributeList`, `RequestedAttributeValues`): [`EMagicLeapIdentityError`](../enums/ue_ue.EMagicLeapIdentityError.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `RequestedAttributeList` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EMagicLeapIdentityKey`](../enums/ue_ue.EMagicLeapIdentityKey.md)\> |
| `RequestedAttributeValues` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MagicLeapIdentityAttribute`](ue_ue.MagicLeapIdentityAttribute.md)\>\> |

#### Returns

[`EMagicLeapIdentityError`](../enums/ue_ue.EMagicLeapIdentityError.md)

___

### RequestAttributeValueAsync

▸ **RequestAttributeValueAsync**(`RequestedAttributeList`, `ResultDelegate`): [`EMagicLeapIdentityError`](../enums/ue_ue.EMagicLeapIdentityError.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `RequestedAttributeList` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EMagicLeapIdentityKey`](../enums/ue_ue.EMagicLeapIdentityKey.md)\> |
| `ResultDelegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`ResultCode`: [`EMagicLeapIdentityError`](../enums/ue_ue.EMagicLeapIdentityError.md), `AttributeValue`: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MagicLeapIdentityAttribute`](ue_ue.MagicLeapIdentityAttribute.md)\>) => `void`\> |

#### Returns

[`EMagicLeapIdentityError`](../enums/ue_ue.EMagicLeapIdentityError.md)

___

### RequestIdentityAttributeValueDelegate\_\_DelegateSignature

▸ **RequestIdentityAttributeValueDelegate__DelegateSignature**(`ResultCode`, `AttributeValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ResultCode` | [`EMagicLeapIdentityError`](../enums/ue_ue.EMagicLeapIdentityError.md) |
| `AttributeValue` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MagicLeapIdentityAttribute`](ue_ue.MagicLeapIdentityAttribute.md)\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MagicLeapIdentity`](ue_ue.MagicLeapIdentity.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MagicLeapIdentity`](ue_ue.MagicLeapIdentity.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MagicLeapIdentity`](ue_ue.MagicLeapIdentity.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MagicLeapIdentity`](ue_ue.MagicLeapIdentity.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
