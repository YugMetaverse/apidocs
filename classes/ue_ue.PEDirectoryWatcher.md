[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PEDirectoryWatcher

# Class: PEDirectoryWatcher

[ue/ue](../modules/ue_ue.md).PEDirectoryWatcher

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PEDirectoryWatcher`**

## Table of contents

### Constructors

- [constructor](ue_ue.PEDirectoryWatcher.md#constructor)

### Properties

- [OnChanged](ue_ue.PEDirectoryWatcher.md#onchanged)
- [\_\_tid\_Object\_\_](ue_ue.PEDirectoryWatcher.md#__tid_object__)
- [\_\_tid\_PEDirectoryWatcher\_\_](ue_ue.PEDirectoryWatcher.md#__tid_pedirectorywatcher__)

### Methods

- [CreateDefaultSubobject](ue_ue.PEDirectoryWatcher.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PEDirectoryWatcher.md#executeubergraph)
- [GetClass](ue_ue.PEDirectoryWatcher.md#getclass)
- [GetName](ue_ue.PEDirectoryWatcher.md#getname)
- [GetOuter](ue_ue.PEDirectoryWatcher.md#getouter)
- [GetWorld](ue_ue.PEDirectoryWatcher.md#getworld)
- [UnWatch](ue_ue.PEDirectoryWatcher.md#unwatch)
- [Watch](ue_ue.PEDirectoryWatcher.md#watch)
- [Find](ue_ue.PEDirectoryWatcher.md#find)
- [Load](ue_ue.PEDirectoryWatcher.md#load)
- [StaticClass](ue_ue.PEDirectoryWatcher.md#staticclass)

## Constructors

### constructor

• **new PEDirectoryWatcher**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### OnChanged

• **OnChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Added`: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>, `Modified`: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>, `Removed`: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>) => `void`\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PEDirectoryWatcher\_\_

• **\_\_tid\_PEDirectoryWatcher\_\_**: `boolean`

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

### UnWatch

▸ **UnWatch**(): `void`

#### Returns

`void`

___

### Watch

▸ **Watch**(`InDirectory`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InDirectory` | `string` |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PEDirectoryWatcher`](ue_ue.PEDirectoryWatcher.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PEDirectoryWatcher`](ue_ue.PEDirectoryWatcher.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PEDirectoryWatcher`](ue_ue.PEDirectoryWatcher.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PEDirectoryWatcher`](ue_ue.PEDirectoryWatcher.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
