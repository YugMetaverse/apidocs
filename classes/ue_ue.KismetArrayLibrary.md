[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KismetArrayLibrary

# Class: KismetArrayLibrary

[ue/ue](../modules/ue_ue.md).KismetArrayLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`KismetArrayLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.KismetArrayLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.KismetArrayLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_KismetArrayLibrary\_\_](ue_ue.KismetArrayLibrary.md#__tid_kismetarraylibrary__)
- [\_\_tid\_Object\_\_](ue_ue.KismetArrayLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.KismetArrayLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.KismetArrayLibrary.md#executeubergraph)
- [GetClass](ue_ue.KismetArrayLibrary.md#getclass)
- [GetName](ue_ue.KismetArrayLibrary.md#getname)
- [GetOuter](ue_ue.KismetArrayLibrary.md#getouter)
- [GetWorld](ue_ue.KismetArrayLibrary.md#getworld)
- [Array\_Add](ue_ue.KismetArrayLibrary.md#array_add)
- [Array\_AddUnique](ue_ue.KismetArrayLibrary.md#array_addunique)
- [Array\_Append](ue_ue.KismetArrayLibrary.md#array_append)
- [Array\_Clear](ue_ue.KismetArrayLibrary.md#array_clear)
- [Array\_Contains](ue_ue.KismetArrayLibrary.md#array_contains)
- [Array\_Find](ue_ue.KismetArrayLibrary.md#array_find)
- [Array\_Get](ue_ue.KismetArrayLibrary.md#array_get)
- [Array\_Identical](ue_ue.KismetArrayLibrary.md#array_identical)
- [Array\_Insert](ue_ue.KismetArrayLibrary.md#array_insert)
- [Array\_IsValidIndex](ue_ue.KismetArrayLibrary.md#array_isvalidindex)
- [Array\_LastIndex](ue_ue.KismetArrayLibrary.md#array_lastindex)
- [Array\_Length](ue_ue.KismetArrayLibrary.md#array_length)
- [Array\_Remove](ue_ue.KismetArrayLibrary.md#array_remove)
- [Array\_RemoveItem](ue_ue.KismetArrayLibrary.md#array_removeitem)
- [Array\_Resize](ue_ue.KismetArrayLibrary.md#array_resize)
- [Array\_Set](ue_ue.KismetArrayLibrary.md#array_set)
- [Array\_Shuffle](ue_ue.KismetArrayLibrary.md#array_shuffle)
- [Array\_Swap](ue_ue.KismetArrayLibrary.md#array_swap)
- [FilterArray](ue_ue.KismetArrayLibrary.md#filterarray)
- [Find](ue_ue.KismetArrayLibrary.md#find)
- [Load](ue_ue.KismetArrayLibrary.md#load)
- [SetArrayPropertyByName](ue_ue.KismetArrayLibrary.md#setarraypropertybyname)
- [StaticClass](ue_ue.KismetArrayLibrary.md#staticclass)

## Constructors

### constructor

• **new KismetArrayLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:42140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42140)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_KismetArrayLibrary\_\_

• **\_\_tid\_KismetArrayLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:42165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42165)

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

### Array\_Add

▸ `Static` **Array_Add**(`TargetArray`, `NewItem`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `NewItem` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42141)

___

### Array\_AddUnique

▸ `Static` **Array_AddUnique**(`TargetArray`, `NewItem`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `NewItem` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42142)

___

### Array\_Append

▸ `Static` **Array_Append**(`TargetArray`, `SourceArray`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `SourceArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42143)

___

### Array\_Clear

▸ `Static` **Array_Clear**(`TargetArray`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42144)

___

### Array\_Contains

▸ `Static` **Array_Contains**(`TargetArray`, `ItemToFind`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `ItemToFind` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42145)

___

### Array\_Find

▸ `Static` **Array_Find**(`TargetArray`, `ItemToFind`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `ItemToFind` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42146)

___

### Array\_Get

▸ `Static` **Array_Get**(`TargetArray`, `Index`, `Item`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `Index` | `number` |
| `Item` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42147)

___

### Array\_Identical

▸ `Static` **Array_Identical**(`ArrayA`, `ArrayB`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ArrayA` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `ArrayB` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42148)

___

### Array\_Insert

▸ `Static` **Array_Insert**(`TargetArray`, `NewItem`, `Index`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `NewItem` | `number` |
| `Index` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42149)

___

### Array\_IsValidIndex

▸ `Static` **Array_IsValidIndex**(`TargetArray`, `IndexToTest`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `IndexToTest` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42150)

___

### Array\_LastIndex

▸ `Static` **Array_LastIndex**(`TargetArray`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42151)

___

### Array\_Length

▸ `Static` **Array_Length**(`TargetArray`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42152)

___

### Array\_Remove

▸ `Static` **Array_Remove**(`TargetArray`, `IndexToRemove`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `IndexToRemove` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42153)

___

### Array\_RemoveItem

▸ `Static` **Array_RemoveItem**(`TargetArray`, `Item`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `Item` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42154)

___

### Array\_Resize

▸ `Static` **Array_Resize**(`TargetArray`, `Size`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `Size` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42155)

___

### Array\_Set

▸ `Static` **Array_Set**(`TargetArray`, `Index`, `Item`, `bSizeToFit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `Index` | `number` |
| `Item` | `number` |
| `bSizeToFit` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42156)

___

### Array\_Shuffle

▸ `Static` **Array_Shuffle**(`TargetArray`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42157)

___

### Array\_Swap

▸ `Static` **Array_Swap**(`TargetArray`, `FirstIndex`, `SecondIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `FirstIndex` | `number` |
| `SecondIndex` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42158)

___

### FilterArray

▸ `Static` **FilterArray**(`TargetArray`, `FilterClass`, `FilteredArray`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |
| `FilterClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `FilteredArray` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42159)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`KismetArrayLibrary`](ue_ue.KismetArrayLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`KismetArrayLibrary`](ue_ue.KismetArrayLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:42162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42162)

___

### Load

▸ `Static` **Load**(`InName`): [`KismetArrayLibrary`](ue_ue.KismetArrayLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`KismetArrayLibrary`](ue_ue.KismetArrayLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:42163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42163)

___

### SetArrayPropertyByName

▸ `Static` **SetArrayPropertyByName**(`Object`, `PropertyName`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PropertyName` | `string` |
| `Value` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42160)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:42161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L42161)
