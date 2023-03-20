[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CryptoKeysSettings

# Class: CryptoKeysSettings

[ue/ue](../modules/ue_ue.md).CryptoKeysSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`CryptoKeysSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.CryptoKeysSettings.md#constructor)

### Properties

- [EncryptionKey](ue_ue.CryptoKeysSettings.md#encryptionkey)
- [SecondaryEncryptionKeys](ue_ue.CryptoKeysSettings.md#secondaryencryptionkeys)
- [SigningModulus](ue_ue.CryptoKeysSettings.md#signingmodulus)
- [SigningPrivateExponent](ue_ue.CryptoKeysSettings.md#signingprivateexponent)
- [SigningPublicExponent](ue_ue.CryptoKeysSettings.md#signingpublicexponent)
- [\_\_tid\_CryptoKeysSettings\_\_](ue_ue.CryptoKeysSettings.md#__tid_cryptokeyssettings__)
- [\_\_tid\_Object\_\_](ue_ue.CryptoKeysSettings.md#__tid_object__)
- [bEnablePakSigning](ue_ue.CryptoKeysSettings.md#benablepaksigning)
- [bEncryptAllAssetFiles](ue_ue.CryptoKeysSettings.md#bencryptallassetfiles)
- [bEncryptPakIndex](ue_ue.CryptoKeysSettings.md#bencryptpakindex)
- [bEncryptPakIniFiles](ue_ue.CryptoKeysSettings.md#bencryptpakinifiles)
- [bEncryptUAssetFiles](ue_ue.CryptoKeysSettings.md#bencryptuassetfiles)

### Methods

- [CreateDefaultSubobject](ue_ue.CryptoKeysSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CryptoKeysSettings.md#executeubergraph)
- [GetClass](ue_ue.CryptoKeysSettings.md#getclass)
- [GetName](ue_ue.CryptoKeysSettings.md#getname)
- [GetOuter](ue_ue.CryptoKeysSettings.md#getouter)
- [GetWorld](ue_ue.CryptoKeysSettings.md#getworld)
- [Find](ue_ue.CryptoKeysSettings.md#find)
- [Load](ue_ue.CryptoKeysSettings.md#load)
- [StaticClass](ue_ue.CryptoKeysSettings.md#staticclass)

## Constructors

### constructor

• **new CryptoKeysSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:28950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28950)

## Properties

### EncryptionKey

• **EncryptionKey**: `string`

#### Defined in

[ue/ue.d.ts:28951](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28951)

___

### SecondaryEncryptionKeys

• **SecondaryEncryptionKeys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CryptoEncryptionKey`](ue_ue.CryptoEncryptionKey.md)\>

#### Defined in

[ue/ue.d.ts:28952](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28952)

___

### SigningModulus

• **SigningModulus**: `string`

#### Defined in

[ue/ue.d.ts:28958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28958)

___

### SigningPrivateExponent

• **SigningPrivateExponent**: `string`

#### Defined in

[ue/ue.d.ts:28959](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28959)

___

### SigningPublicExponent

• **SigningPublicExponent**: `string`

#### Defined in

[ue/ue.d.ts:28957](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28957)

___

### \_\_tid\_CryptoKeysSettings\_\_

• **\_\_tid\_CryptoKeysSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28965)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bEnablePakSigning

• **bEnablePakSigning**: `boolean`

#### Defined in

[ue/ue.d.ts:28960](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28960)

___

### bEncryptAllAssetFiles

• **bEncryptAllAssetFiles**: `boolean`

#### Defined in

[ue/ue.d.ts:28956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28956)

___

### bEncryptPakIndex

• **bEncryptPakIndex**: `boolean`

#### Defined in

[ue/ue.d.ts:28954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28954)

___

### bEncryptPakIniFiles

• **bEncryptPakIniFiles**: `boolean`

#### Defined in

[ue/ue.d.ts:28953](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28953)

___

### bEncryptUAssetFiles

• **bEncryptUAssetFiles**: `boolean`

#### Defined in

[ue/ue.d.ts:28955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28955)

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CryptoKeysSettings`](ue_ue.CryptoKeysSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CryptoKeysSettings`](ue_ue.CryptoKeysSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:28962](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28962)

___

### Load

▸ `Static` **Load**(`InName`): [`CryptoKeysSettings`](ue_ue.CryptoKeysSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CryptoKeysSettings`](ue_ue.CryptoKeysSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:28963](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28963)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:28961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28961)
