[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameplayTagAssetInterface

# Class: GameplayTagAssetInterface

[ue/ue](../modules/ue_ue.md).GameplayTagAssetInterface

## Hierarchy

- [`Interface`](ue_ue.Interface.md)

  ↳ **`GameplayTagAssetInterface`**

## Table of contents

### Constructors

- [constructor](ue_ue.GameplayTagAssetInterface.md#constructor)

### Properties

- [\_\_tid\_GameplayTagAssetInterface\_\_](ue_ue.GameplayTagAssetInterface.md#__tid_gameplaytagassetinterface__)
- [\_\_tid\_Interface\_\_](ue_ue.GameplayTagAssetInterface.md#__tid_interface__)
- [\_\_tid\_Object\_\_](ue_ue.GameplayTagAssetInterface.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.GameplayTagAssetInterface.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GameplayTagAssetInterface.md#executeubergraph)
- [GetClass](ue_ue.GameplayTagAssetInterface.md#getclass)
- [GetName](ue_ue.GameplayTagAssetInterface.md#getname)
- [GetOuter](ue_ue.GameplayTagAssetInterface.md#getouter)
- [GetOwnedGameplayTags](ue_ue.GameplayTagAssetInterface.md#getownedgameplaytags)
- [GetWorld](ue_ue.GameplayTagAssetInterface.md#getworld)
- [HasAllMatchingGameplayTags](ue_ue.GameplayTagAssetInterface.md#hasallmatchinggameplaytags)
- [HasAnyMatchingGameplayTags](ue_ue.GameplayTagAssetInterface.md#hasanymatchinggameplaytags)
- [HasMatchingGameplayTag](ue_ue.GameplayTagAssetInterface.md#hasmatchinggameplaytag)
- [Find](ue_ue.GameplayTagAssetInterface.md#find)
- [Load](ue_ue.GameplayTagAssetInterface.md#load)
- [StaticClass](ue_ue.GameplayTagAssetInterface.md#staticclass)

## Constructors

### constructor

• **new GameplayTagAssetInterface**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Interface](ue_ue.Interface.md).[constructor](ue_ue.Interface.md#constructor)

## Properties

### \_\_tid\_GameplayTagAssetInterface\_\_

• **\_\_tid\_GameplayTagAssetInterface\_\_**: `boolean`

___

### \_\_tid\_Interface\_\_

• **\_\_tid\_Interface\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Interface__](ue_ue.Interface.md#__tid_interface__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Object__](ue_ue.Interface.md#__tid_object__)

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

[Interface](ue_ue.Interface.md).[CreateDefaultSubobject](ue_ue.Interface.md#createdefaultsubobject)

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

[Interface](ue_ue.Interface.md).[ExecuteUbergraph](ue_ue.Interface.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetClass](ue_ue.Interface.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Interface](ue_ue.Interface.md).[GetName](ue_ue.Interface.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetOuter](ue_ue.Interface.md#getouter)

___

### GetOwnedGameplayTags

▸ **GetOwnedGameplayTags**(`TagContainer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TagContainer` | [`$Ref`](../interfaces/puerts._Ref.md)<[`GameplayTagContainer`](ue_ue.GameplayTagContainer.md)\> |

#### Returns

`void`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetWorld](ue_ue.Interface.md#getworld)

___

### HasAllMatchingGameplayTags

▸ **HasAllMatchingGameplayTags**(`TagContainer`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TagContainer` | [`GameplayTagContainer`](ue_ue.GameplayTagContainer.md) |

#### Returns

`boolean`

___

### HasAnyMatchingGameplayTags

▸ **HasAnyMatchingGameplayTags**(`TagContainer`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TagContainer` | [`GameplayTagContainer`](ue_ue.GameplayTagContainer.md) |

#### Returns

`boolean`

___

### HasMatchingGameplayTag

▸ **HasMatchingGameplayTag**(`TagToCheck`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TagToCheck` | [`GameplayTag`](ue_ue.GameplayTag.md) |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameplayTagAssetInterface`](ue_ue.GameplayTagAssetInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameplayTagAssetInterface`](ue_ue.GameplayTagAssetInterface.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Find](ue_ue.Interface.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GameplayTagAssetInterface`](ue_ue.GameplayTagAssetInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameplayTagAssetInterface`](ue_ue.GameplayTagAssetInterface.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Load](ue_ue.Interface.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Interface](ue_ue.Interface.md).[StaticClass](ue_ue.Interface.md#staticclass)
