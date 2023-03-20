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

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_KismetNodeHelperLibrary\_\_

• **\_\_tid\_KismetNodeHelperLibrary\_\_**: `boolean`

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

### BitIsMarked

▸ `Static` **BitIsMarked**(`Data`, `Index`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Data` | `number` |
| `Index` | `number` |

#### Returns

`boolean`

___

### ClearAllBits

▸ `Static` **ClearAllBits**(`Data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Data` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
