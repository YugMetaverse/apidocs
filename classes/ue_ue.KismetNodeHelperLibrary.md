[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KismetNodeHelperLibrary

# Class: KismetNodeHelperLibrary

[ue/ue](../modules/ue_ue.md).KismetNodeHelperLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`KismetNodeHelperLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.KismetNodeHelperLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.KismetNodeHelperLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_KismetNodeHelperLibrary\_\_](ue_ue.KismetNodeHelperLibrary.md#__tid_kismetnodehelperlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.KismetNodeHelperLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.KismetNodeHelperLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.KismetNodeHelperLibrary.md#executeubergraph)
- [GetClass](ue_ue.KismetNodeHelperLibrary.md#getclass)
- [GetName](ue_ue.KismetNodeHelperLibrary.md#getname)
- [GetOuter](ue_ue.KismetNodeHelperLibrary.md#getouter)
- [GetWorld](ue_ue.KismetNodeHelperLibrary.md#getworld)
- [BitIsMarked](ue_ue.KismetNodeHelperLibrary.md#bitismarked)
- [ClearAllBits](ue_ue.KismetNodeHelperLibrary.md#clearallbits)
- [ClearBit](ue_ue.KismetNodeHelperLibrary.md#clearbit)
- [Find](ue_ue.KismetNodeHelperLibrary.md#find)
- [GetEnumeratorName](ue_ue.KismetNodeHelperLibrary.md#getenumeratorname)
- [GetEnumeratorUserFriendlyName](ue_ue.KismetNodeHelperLibrary.md#getenumeratoruserfriendlyname)
- [GetEnumeratorValueFromIndex](ue_ue.KismetNodeHelperLibrary.md#getenumeratorvaluefromindex)
- [GetFirstUnmarkedBit](ue_ue.KismetNodeHelperLibrary.md#getfirstunmarkedbit)
- [GetRandomUnmarkedBit](ue_ue.KismetNodeHelperLibrary.md#getrandomunmarkedbit)
- [GetUnmarkedBit](ue_ue.KismetNodeHelperLibrary.md#getunmarkedbit)
- [GetValidValue](ue_ue.KismetNodeHelperLibrary.md#getvalidvalue)
- [HasMarkedBit](ue_ue.KismetNodeHelperLibrary.md#hasmarkedbit)
- [HasUnmarkedBit](ue_ue.KismetNodeHelperLibrary.md#hasunmarkedbit)
- [Load](ue_ue.KismetNodeHelperLibrary.md#load)
- [MarkBit](ue_ue.KismetNodeHelperLibrary.md#markbit)
- [StaticClass](ue_ue.KismetNodeHelperLibrary.md#staticclass)

## Constructors

### constructor

• **new KismetNodeHelperLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:42954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42954)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13418)

___

### \_\_tid\_KismetNodeHelperLibrary\_\_

• **\_\_tid\_KismetNodeHelperLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:42972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42972)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### BitIsMarked

▸ `Static` **BitIsMarked**(`Data`, `Index`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Data` | `number` |
| `Index` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42955)

___

### ClearAllBits

▸ `Static` **ClearAllBits**(`Data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Data` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42956)

___

### ClearBit

▸ `Static` **ClearBit**(`Data`, `Index`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Data` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Index` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42957](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42957)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`KismetNodeHelperLibrary`](ue_ue.KismetNodeHelperLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`KismetNodeHelperLibrary`](ue_ue.KismetNodeHelperLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:42969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42969)

___

### GetEnumeratorName

▸ `Static` **GetEnumeratorName**(`Enum`, `EnumeratorValue`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Enum` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Enum`](ue_ue.Enum.md)\> |
| `EnumeratorValue` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:42958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42958)

___

### GetEnumeratorUserFriendlyName

▸ `Static` **GetEnumeratorUserFriendlyName**(`Enum`, `EnumeratorValue`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Enum` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Enum`](ue_ue.Enum.md)\> |
| `EnumeratorValue` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:42959](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42959)

___

### GetEnumeratorValueFromIndex

▸ `Static` **GetEnumeratorValueFromIndex**(`Enum`, `EnumeratorIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Enum` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Enum`](ue_ue.Enum.md)\> |
| `EnumeratorIndex` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42960](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42960)

___

### GetFirstUnmarkedBit

▸ `Static` **GetFirstUnmarkedBit**(`Data`, `StartIdx`, `NumBits`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Data` | `number` |
| `StartIdx` | `number` |
| `NumBits` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42961)

___

### GetRandomUnmarkedBit

▸ `Static` **GetRandomUnmarkedBit**(`Data`, `StartIdx`, `NumBits`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Data` | `number` |
| `StartIdx` | `number` |
| `NumBits` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42962](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42962)

___

### GetUnmarkedBit

▸ `Static` **GetUnmarkedBit**(`Data`, `StartIdx`, `NumBits`, `bRandom`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Data` | `number` |
| `StartIdx` | `number` |
| `NumBits` | `number` |
| `bRandom` | `boolean` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42963](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42963)

___

### GetValidValue

▸ `Static` **GetValidValue**(`Enum`, `EnumeratorValue`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Enum` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Enum`](ue_ue.Enum.md)\> |
| `EnumeratorValue` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42964)

___

### HasMarkedBit

▸ `Static` **HasMarkedBit**(`Data`, `NumBits`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Data` | `number` |
| `NumBits` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42965)

___

### HasUnmarkedBit

▸ `Static` **HasUnmarkedBit**(`Data`, `NumBits`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Data` | `number` |
| `NumBits` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42966)

___

### Load

▸ `Static` **Load**(`InName`): [`KismetNodeHelperLibrary`](ue_ue.KismetNodeHelperLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`KismetNodeHelperLibrary`](ue_ue.KismetNodeHelperLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:42970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42970)

___

### MarkBit

▸ `Static` **MarkBit**(`Data`, `Index`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Data` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Index` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42967)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:42968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42968)
