[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / JSBlueprintFunctionLibrary

# Class: JSBlueprintFunctionLibrary

[ue/ue](../modules/ue_ue.md).JSBlueprintFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`JSBlueprintFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.JSBlueprintFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.JSBlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_JSBlueprintFunctionLibrary\_\_](ue_ue.JSBlueprintFunctionLibrary.md#__tid_jsblueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.JSBlueprintFunctionLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.JSBlueprintFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.JSBlueprintFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.JSBlueprintFunctionLibrary.md#getclass)
- [GetName](ue_ue.JSBlueprintFunctionLibrary.md#getname)
- [GetOuter](ue_ue.JSBlueprintFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.JSBlueprintFunctionLibrary.md#getworld)
- [Concat](ue_ue.JSBlueprintFunctionLibrary.md#concat)
- [Find](ue_ue.JSBlueprintFunctionLibrary.md#find)
- [GetName](ue_ue.JSBlueprintFunctionLibrary.md#getname-1)
- [Hello](ue_ue.JSBlueprintFunctionLibrary.md#hello)
- [Info](ue_ue.JSBlueprintFunctionLibrary.md#info)
- [Load](ue_ue.JSBlueprintFunctionLibrary.md#load)
- [StaticClass](ue_ue.JSBlueprintFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new JSBlueprintFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_JSBlueprintFunctionLibrary\_\_

• **\_\_tid\_JSBlueprintFunctionLibrary\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### Concat

▸ `Static` **Concat**(`First`, `Second`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `First` | `string` |
| `Second` | `string` |

#### Returns

`string`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`JSBlueprintFunctionLibrary`](ue_ue.JSBlueprintFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`JSBlueprintFunctionLibrary`](ue_ue.JSBlueprintFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetName

▸ `Static` **GetName**(): `string`

#### Returns

`string`

___

### Hello

▸ `Static` **Hello**(`To`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `To` | `string` |

#### Returns

`string`

___

### Info

▸ `Static` **Info**(`To`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `To` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

___

### Load

▸ `Static` **Load**(`InName`): [`JSBlueprintFunctionLibrary`](ue_ue.JSBlueprintFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`JSBlueprintFunctionLibrary`](ue_ue.JSBlueprintFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
