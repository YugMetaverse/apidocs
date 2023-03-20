[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KismetInternationalizationLibrary

# Class: KismetInternationalizationLibrary

[ue/ue](../modules/ue_ue.md).KismetInternationalizationLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`KismetInternationalizationLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.KismetInternationalizationLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.KismetInternationalizationLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_KismetInternationalizationLibrary\_\_](ue_ue.KismetInternationalizationLibrary.md#__tid_kismetinternationalizationlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.KismetInternationalizationLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.KismetInternationalizationLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.KismetInternationalizationLibrary.md#executeubergraph)
- [GetClass](ue_ue.KismetInternationalizationLibrary.md#getclass)
- [GetName](ue_ue.KismetInternationalizationLibrary.md#getname)
- [GetOuter](ue_ue.KismetInternationalizationLibrary.md#getouter)
- [GetWorld](ue_ue.KismetInternationalizationLibrary.md#getworld)
- [ClearCurrentAssetGroupCulture](ue_ue.KismetInternationalizationLibrary.md#clearcurrentassetgroupculture)
- [Find](ue_ue.KismetInternationalizationLibrary.md#find)
- [GetCultureDisplayName](ue_ue.KismetInternationalizationLibrary.md#getculturedisplayname)
- [GetCurrentAssetGroupCulture](ue_ue.KismetInternationalizationLibrary.md#getcurrentassetgroupculture)
- [GetCurrentCulture](ue_ue.KismetInternationalizationLibrary.md#getcurrentculture)
- [GetCurrentLanguage](ue_ue.KismetInternationalizationLibrary.md#getcurrentlanguage)
- [GetCurrentLocale](ue_ue.KismetInternationalizationLibrary.md#getcurrentlocale)
- [GetLocalizedCultures](ue_ue.KismetInternationalizationLibrary.md#getlocalizedcultures)
- [GetNativeCulture](ue_ue.KismetInternationalizationLibrary.md#getnativeculture)
- [GetSuitableCulture](ue_ue.KismetInternationalizationLibrary.md#getsuitableculture)
- [Load](ue_ue.KismetInternationalizationLibrary.md#load)
- [SetCurrentAssetGroupCulture](ue_ue.KismetInternationalizationLibrary.md#setcurrentassetgroupculture)
- [SetCurrentCulture](ue_ue.KismetInternationalizationLibrary.md#setcurrentculture)
- [SetCurrentLanguage](ue_ue.KismetInternationalizationLibrary.md#setcurrentlanguage)
- [SetCurrentLanguageAndLocale](ue_ue.KismetInternationalizationLibrary.md#setcurrentlanguageandlocale)
- [SetCurrentLocale](ue_ue.KismetInternationalizationLibrary.md#setcurrentlocale)
- [StaticClass](ue_ue.KismetInternationalizationLibrary.md#staticclass)

## Constructors

### constructor

• **new KismetInternationalizationLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:42238](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42238)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_KismetInternationalizationLibrary\_\_

• **\_\_tid\_KismetInternationalizationLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:42257](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42257)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### ClearCurrentAssetGroupCulture

▸ `Static` **ClearCurrentAssetGroupCulture**(`AssetGroup`, `SaveToConfig?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetGroup` | `string` |
| `SaveToConfig?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42239](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42239)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`KismetInternationalizationLibrary`](ue_ue.KismetInternationalizationLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`KismetInternationalizationLibrary`](ue_ue.KismetInternationalizationLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:42254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42254)

___

### GetCultureDisplayName

▸ `Static` **GetCultureDisplayName**(`Culture`, `Localized?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Culture` | `string` |
| `Localized?` | `boolean` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:42240](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42240)

___

### GetCurrentAssetGroupCulture

▸ `Static` **GetCurrentAssetGroupCulture**(`AssetGroup`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetGroup` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:42241](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42241)

___

### GetCurrentCulture

▸ `Static` **GetCurrentCulture**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:42242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42242)

___

### GetCurrentLanguage

▸ `Static` **GetCurrentLanguage**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:42243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42243)

___

### GetCurrentLocale

▸ `Static` **GetCurrentLocale**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:42244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42244)

___

### GetLocalizedCultures

▸ `Static` **GetLocalizedCultures**(`IncludeGame?`, `IncludeEngine?`, `IncludeEditor?`, `IncludeAdditional?`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `IncludeGame?` | `boolean` |
| `IncludeEngine?` | `boolean` |
| `IncludeEditor?` | `boolean` |
| `IncludeAdditional?` | `boolean` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:42245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42245)

___

### GetNativeCulture

▸ `Static` **GetNativeCulture**(`TextCategory`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TextCategory` | [`ELocalizedTextSourceCategory`](../enums/ue_ue.ELocalizedTextSourceCategory.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:42246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42246)

___

### GetSuitableCulture

▸ `Static` **GetSuitableCulture**(`AvailableCultures`, `CultureToMatch`, `FallbackCulture?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AvailableCultures` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `CultureToMatch` | `string` |
| `FallbackCulture?` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:42247](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42247)

___

### Load

▸ `Static` **Load**(`InName`): [`KismetInternationalizationLibrary`](ue_ue.KismetInternationalizationLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`KismetInternationalizationLibrary`](ue_ue.KismetInternationalizationLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:42255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42255)

___

### SetCurrentAssetGroupCulture

▸ `Static` **SetCurrentAssetGroupCulture**(`AssetGroup`, `Culture`, `SaveToConfig?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetGroup` | `string` |
| `Culture` | `string` |
| `SaveToConfig?` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42248)

___

### SetCurrentCulture

▸ `Static` **SetCurrentCulture**(`Culture`, `SaveToConfig?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Culture` | `string` |
| `SaveToConfig?` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42249)

___

### SetCurrentLanguage

▸ `Static` **SetCurrentLanguage**(`Culture`, `SaveToConfig?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Culture` | `string` |
| `SaveToConfig?` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42250)

___

### SetCurrentLanguageAndLocale

▸ `Static` **SetCurrentLanguageAndLocale**(`Culture`, `SaveToConfig?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Culture` | `string` |
| `SaveToConfig?` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42251)

___

### SetCurrentLocale

▸ `Static` **SetCurrentLocale**(`Culture`, `SaveToConfig?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Culture` | `string` |
| `SaveToConfig?` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42252](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42252)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:42253](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42253)
