[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintSetLibrary

# Class: BlueprintSetLibrary

[ue/ue](../modules/ue_ue.md).BlueprintSetLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`BlueprintSetLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintSetLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.BlueprintSetLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_BlueprintSetLibrary\_\_](ue_ue.BlueprintSetLibrary.md#__tid_blueprintsetlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.BlueprintSetLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BlueprintSetLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlueprintSetLibrary.md#executeubergraph)
- [GetClass](ue_ue.BlueprintSetLibrary.md#getclass)
- [GetName](ue_ue.BlueprintSetLibrary.md#getname)
- [GetOuter](ue_ue.BlueprintSetLibrary.md#getouter)
- [GetWorld](ue_ue.BlueprintSetLibrary.md#getworld)
- [Find](ue_ue.BlueprintSetLibrary.md#find)
- [Load](ue_ue.BlueprintSetLibrary.md#load)
- [SetSetPropertyByName](ue_ue.BlueprintSetLibrary.md#setsetpropertybyname)
- [Set\_Add](ue_ue.BlueprintSetLibrary.md#set_add)
- [Set\_AddItems](ue_ue.BlueprintSetLibrary.md#set_additems)
- [Set\_Clear](ue_ue.BlueprintSetLibrary.md#set_clear)
- [Set\_Contains](ue_ue.BlueprintSetLibrary.md#set_contains)
- [Set\_Difference](ue_ue.BlueprintSetLibrary.md#set_difference)
- [Set\_Intersection](ue_ue.BlueprintSetLibrary.md#set_intersection)
- [Set\_Length](ue_ue.BlueprintSetLibrary.md#set_length)
- [Set\_Remove](ue_ue.BlueprintSetLibrary.md#set_remove)
- [Set\_RemoveItems](ue_ue.BlueprintSetLibrary.md#set_removeitems)
- [Set\_ToArray](ue_ue.BlueprintSetLibrary.md#set_toarray)
- [Set\_Union](ue_ue.BlueprintSetLibrary.md#set_union)
- [StaticClass](ue_ue.BlueprintSetLibrary.md#staticclass)

## Constructors

### constructor

• **new BlueprintSetLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_BlueprintSetLibrary\_\_

• **\_\_tid\_BlueprintSetLibrary\_\_**: `boolean`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlueprintSetLibrary`](ue_ue.BlueprintSetLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlueprintSetLibrary`](ue_ue.BlueprintSetLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BlueprintSetLibrary`](ue_ue.BlueprintSetLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlueprintSetLibrary`](ue_ue.BlueprintSetLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### SetSetPropertyByName

▸ `Static` **SetSetPropertyByName**(`Object`, `PropertyName`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PropertyName` | `string` |
| `Value` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |

#### Returns

`void`

___

### Set\_Add

▸ `Static` **Set_Add**(`TargetSet`, `NewItem`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetSet` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |
| `NewItem` | `number` |

#### Returns

`void`

___

### Set\_AddItems

▸ `Static` **Set_AddItems**(`TargetSet`, `NewItems`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetSet` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |
| `NewItems` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

___

### Set\_Clear

▸ `Static` **Set_Clear**(`TargetSet`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetSet` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |

#### Returns

`void`

___

### Set\_Contains

▸ `Static` **Set_Contains**(`TargetSet`, `ItemToFind`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetSet` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |
| `ItemToFind` | `number` |

#### Returns

`boolean`

___

### Set\_Difference

▸ `Static` **Set_Difference**(`A`, `B`, `Result`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |
| `B` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |
| `Result` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\>\> |

#### Returns

`void`

___

### Set\_Intersection

▸ `Static` **Set_Intersection**(`A`, `B`, `Result`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |
| `B` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |
| `Result` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\>\> |

#### Returns

`void`

___

### Set\_Length

▸ `Static` **Set_Length**(`TargetSet`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetSet` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |

#### Returns

`number`

___

### Set\_Remove

▸ `Static` **Set_Remove**(`TargetSet`, `Item`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetSet` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |
| `Item` | `number` |

#### Returns

`boolean`

___

### Set\_RemoveItems

▸ `Static` **Set_RemoveItems**(`TargetSet`, `Items`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetSet` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |
| `Items` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

___

### Set\_ToArray

▸ `Static` **Set_ToArray**(`A`, `Result`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |
| `Result` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |

#### Returns

`void`

___

### Set\_Union

▸ `Static` **Set_Union**(`A`, `B`, `Result`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |
| `B` | [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\> |
| `Result` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\>\> |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
