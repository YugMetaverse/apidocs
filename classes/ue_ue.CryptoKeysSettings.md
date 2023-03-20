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

## Properties

### EncryptionKey

• **EncryptionKey**: `string`

___

### SecondaryEncryptionKeys

• **SecondaryEncryptionKeys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CryptoEncryptionKey`](ue_ue.CryptoEncryptionKey.md)\>

___

### SigningModulus

• **SigningModulus**: `string`

___

### SigningPrivateExponent

• **SigningPrivateExponent**: `string`

___

### SigningPublicExponent

• **SigningPublicExponent**: `string`

___

### \_\_tid\_CryptoKeysSettings\_\_

• **\_\_tid\_CryptoKeysSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bEnablePakSigning

• **bEnablePakSigning**: `boolean`

___

### bEncryptAllAssetFiles

• **bEncryptAllAssetFiles**: `boolean`

___

### bEncryptPakIndex

• **bEncryptPakIndex**: `boolean`

___

### bEncryptPakIniFiles

• **bEncryptPakIniFiles**: `boolean`

___

### bEncryptUAssetFiles

• **bEncryptUAssetFiles**: `boolean`

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

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
