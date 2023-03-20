[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AppleImageUtilsBaseAsyncTaskBlueprintProxy

# Class: AppleImageUtilsBaseAsyncTaskBlueprintProxy

[ue/ue](../modules/ue_ue.md).AppleImageUtilsBaseAsyncTaskBlueprintProxy

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AppleImageUtilsBaseAsyncTaskBlueprintProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#constructor)

### Properties

- [ConversionResult](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#conversionresult)
- [OnFailure](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#onfailure)
- [OnSuccess](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#onsuccess)
- [\_\_tid\_AppleImageUtilsBaseAsyncTaskBlueprintProxy\_\_](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#__tid_appleimageutilsbaseasynctaskblueprintproxy__)
- [\_\_tid\_Object\_\_](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#executeubergraph)
- [GetClass](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#getclass)
- [GetName](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#getname)
- [GetOuter](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#getouter)
- [GetWorld](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#getworld)
- [CreateProxyObjectForConvertToHEIF](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#createproxyobjectforconverttoheif)
- [CreateProxyObjectForConvertToJPEG](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#createproxyobjectforconverttojpeg)
- [CreateProxyObjectForConvertToPNG](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#createproxyobjectforconverttopng)
- [CreateProxyObjectForConvertToTIFF](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#createproxyobjectforconverttotiff)
- [Find](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#find)
- [Load](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#load)
- [StaticClass](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md#staticclass)

## Constructors

### constructor

• **new AppleImageUtilsBaseAsyncTaskBlueprintProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:20627](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20627)

## Properties

### ConversionResult

• **ConversionResult**: [`AppleImageUtilsImageConversionResult`](ue_ue.AppleImageUtilsImageConversionResult.md)

#### Defined in

[ue/ue.d.ts:20630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20630)

___

### OnFailure

• **OnFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ConversionResult`: [`AppleImageUtilsImageConversionResult`](ue_ue.AppleImageUtilsImageConversionResult.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:20629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20629)

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ConversionResult`: [`AppleImageUtilsImageConversionResult`](ue_ue.AppleImageUtilsImageConversionResult.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:20628](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20628)

___

### \_\_tid\_AppleImageUtilsBaseAsyncTaskBlueprintProxy\_\_

• **\_\_tid\_AppleImageUtilsBaseAsyncTaskBlueprintProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20639](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20639)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### CreateProxyObjectForConvertToHEIF

▸ `Static` **CreateProxyObjectForConvertToHEIF**(`SourceImage`, `Quality?`, `bWantColor?`, `bUseGpu?`, `Scale?`, `Rotate?`): [`AppleImageUtilsBaseAsyncTaskBlueprintProxy`](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceImage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `Quality?` | `number` |
| `bWantColor?` | `boolean` |
| `bUseGpu?` | `boolean` |
| `Scale?` | `number` |
| `Rotate?` | [`ETextureRotationDirection`](../enums/ue_ue.ETextureRotationDirection.md) |

#### Returns

[`AppleImageUtilsBaseAsyncTaskBlueprintProxy`](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md)

#### Defined in

[ue/ue.d.ts:20631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20631)

___

### CreateProxyObjectForConvertToJPEG

▸ `Static` **CreateProxyObjectForConvertToJPEG**(`SourceImage`, `Quality?`, `bWantColor?`, `bUseGpu?`, `Scale?`, `Rotate?`): [`AppleImageUtilsBaseAsyncTaskBlueprintProxy`](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceImage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `Quality?` | `number` |
| `bWantColor?` | `boolean` |
| `bUseGpu?` | `boolean` |
| `Scale?` | `number` |
| `Rotate?` | [`ETextureRotationDirection`](../enums/ue_ue.ETextureRotationDirection.md) |

#### Returns

[`AppleImageUtilsBaseAsyncTaskBlueprintProxy`](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md)

#### Defined in

[ue/ue.d.ts:20632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20632)

___

### CreateProxyObjectForConvertToPNG

▸ `Static` **CreateProxyObjectForConvertToPNG**(`SourceImage`, `bWantColor?`, `bUseGpu?`, `Scale?`, `Rotate?`): [`AppleImageUtilsBaseAsyncTaskBlueprintProxy`](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceImage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `bWantColor?` | `boolean` |
| `bUseGpu?` | `boolean` |
| `Scale?` | `number` |
| `Rotate?` | [`ETextureRotationDirection`](../enums/ue_ue.ETextureRotationDirection.md) |

#### Returns

[`AppleImageUtilsBaseAsyncTaskBlueprintProxy`](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md)

#### Defined in

[ue/ue.d.ts:20633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20633)

___

### CreateProxyObjectForConvertToTIFF

▸ `Static` **CreateProxyObjectForConvertToTIFF**(`SourceImage`, `bWantColor?`, `bUseGpu?`, `Scale?`, `Rotate?`): [`AppleImageUtilsBaseAsyncTaskBlueprintProxy`](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceImage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `bWantColor?` | `boolean` |
| `bUseGpu?` | `boolean` |
| `Scale?` | `number` |
| `Rotate?` | [`ETextureRotationDirection`](../enums/ue_ue.ETextureRotationDirection.md) |

#### Returns

[`AppleImageUtilsBaseAsyncTaskBlueprintProxy`](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md)

#### Defined in

[ue/ue.d.ts:20634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20634)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AppleImageUtilsBaseAsyncTaskBlueprintProxy`](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AppleImageUtilsBaseAsyncTaskBlueprintProxy`](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:20636](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20636)

___

### Load

▸ `Static` **Load**(`InName`): [`AppleImageUtilsBaseAsyncTaskBlueprintProxy`](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AppleImageUtilsBaseAsyncTaskBlueprintProxy`](ue_ue.AppleImageUtilsBaseAsyncTaskBlueprintProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:20637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20637)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:20635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20635)
