[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorValidatorBase

# Class: EditorValidatorBase

[ue/ue](../modules/ue_ue.md).EditorValidatorBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EditorValidatorBase`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorValidatorBase.md#constructor)

### Properties

- [\_\_tid\_EditorValidatorBase\_\_](ue_ue.EditorValidatorBase.md#__tid_editorvalidatorbase__)
- [\_\_tid\_Object\_\_](ue_ue.EditorValidatorBase.md#__tid_object__)
- [bIsEnabled](ue_ue.EditorValidatorBase.md#bisenabled)

### Methods

- [AssetFails](ue_ue.EditorValidatorBase.md#assetfails)
- [AssetPasses](ue_ue.EditorValidatorBase.md#assetpasses)
- [CanValidateAsset](ue_ue.EditorValidatorBase.md#canvalidateasset)
- [CreateDefaultSubobject](ue_ue.EditorValidatorBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorValidatorBase.md#executeubergraph)
- [GetClass](ue_ue.EditorValidatorBase.md#getclass)
- [GetName](ue_ue.EditorValidatorBase.md#getname)
- [GetOuter](ue_ue.EditorValidatorBase.md#getouter)
- [GetValidationResult](ue_ue.EditorValidatorBase.md#getvalidationresult)
- [GetWorld](ue_ue.EditorValidatorBase.md#getworld)
- [ValidateLoadedAsset](ue_ue.EditorValidatorBase.md#validateloadedasset)
- [Find](ue_ue.EditorValidatorBase.md#find)
- [Load](ue_ue.EditorValidatorBase.md#load)
- [StaticClass](ue_ue.EditorValidatorBase.md#staticclass)

## Constructors

### constructor

• **new EditorValidatorBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_EditorValidatorBase\_\_

• **\_\_tid\_EditorValidatorBase\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bIsEnabled

• **bIsEnabled**: `boolean`

## Methods

### AssetFails

▸ **AssetFails**(`InAsset`, `InMessage`, `ValidationErrors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `InMessage` | `string` |
| `ValidationErrors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

___

### AssetPasses

▸ **AssetPasses**(`InAsset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### CanValidateAsset

▸ **CanValidateAsset**(`InAsset`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

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

### GetValidationResult

▸ **GetValidationResult**(): [`EDataValidationResult`](../enums/ue_ue.EDataValidationResult.md)

#### Returns

[`EDataValidationResult`](../enums/ue_ue.EDataValidationResult.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### ValidateLoadedAsset

▸ **ValidateLoadedAsset**(`InAsset`, `ValidationErrors`): [`EDataValidationResult`](../enums/ue_ue.EDataValidationResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ValidationErrors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

[`EDataValidationResult`](../enums/ue_ue.EDataValidationResult.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorValidatorBase`](ue_ue.EditorValidatorBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorValidatorBase`](ue_ue.EditorValidatorBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorValidatorBase`](ue_ue.EditorValidatorBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorValidatorBase`](ue_ue.EditorValidatorBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
