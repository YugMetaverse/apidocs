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

#### Defined in

[ue/ue.d.ts:33717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33717)

## Properties

### \_\_tid\_EditorValidatorBase\_\_

• **\_\_tid\_EditorValidatorBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:33728](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33728)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bIsEnabled

• **bIsEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:33718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33718)

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

#### Defined in

[ue/ue.d.ts:33719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33719)

___

### AssetPasses

▸ **AssetPasses**(`InAsset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33720)

___

### CanValidateAsset

▸ **CanValidateAsset**(`InAsset`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:33721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33721)

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

### GetValidationResult

▸ **GetValidationResult**(): [`EDataValidationResult`](../enums/ue_ue.EDataValidationResult.md)

#### Returns

[`EDataValidationResult`](../enums/ue_ue.EDataValidationResult.md)

#### Defined in

[ue/ue.d.ts:33722](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33722)

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

### ValidateLoadedAsset

▸ **ValidateLoadedAsset**(`InAsset`, `ValidationErrors`): [`EDataValidationResult`](../enums/ue_ue.EDataValidationResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ValidationErrors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

[`EDataValidationResult`](../enums/ue_ue.EDataValidationResult.md)

#### Defined in

[ue/ue.d.ts:33723](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33723)

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

#### Defined in

[ue/ue.d.ts:33725](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33725)

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

#### Defined in

[ue/ue.d.ts:33726](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33726)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:33724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33724)
