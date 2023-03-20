[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MainObject

# Class: MainObject

[ue/ue](../modules/ue_ue.md).MainObject

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MainObject`**

## Table of contents

### Constructors

- [constructor](ue_ue.MainObject.md#constructor)

### Properties

- [ArrayBuffer](ue_ue.MainObject.md#arraybuffer)
- [MyArray](ue_ue.MainObject.md#myarray)
- [MyFixSizeArray](ue_ue.MainObject.md#myfixsizearray)
- [MyMap](ue_ue.MainObject.md#mymap)
- [MySet](ue_ue.MainObject.md#myset)
- [MyString](ue_ue.MainObject.md#mystring)
- [SomeData](ue_ue.MainObject.md#somedata)
- [V](ue_ue.MainObject.md#v)
- [\_\_tid\_MainObject\_\_](ue_ue.MainObject.md#__tid_mainobject__)
- [\_\_tid\_Object\_\_](ue_ue.MainObject.md#__tid_object__)

### Methods

- [Add](ue_ue.MainObject.md#add)
- [ArrayBufferTest](ue_ue.MainObject.md#arraybuffertest)
- [Bar](ue_ue.MainObject.md#bar)
- [Bar2](ue_ue.MainObject.md#bar2)
- [Bar3](ue_ue.MainObject.md#bar3)
- [Callback\_\_DelegateSignature](ue_ue.MainObject.md#callback__delegatesignature)
- [CreateDefaultSubobject](ue_ue.MainObject.md#createdefaultsubobject)
- [DefaultTest](ue_ue.MainObject.md#defaulttest)
- [Div](ue_ue.MainObject.md#div)
- [EnumTest](ue_ue.MainObject.md#enumtest)
- [ExecuteUbergraph](ue_ue.MainObject.md#executeubergraph)
- [Foo](ue_ue.MainObject.md#foo)
- [GetClass](ue_ue.MainObject.md#getclass)
- [GetData](ue_ue.MainObject.md#getdata)
- [GetInts](ue_ue.MainObject.md#getints)
- [GetName](ue_ue.MainObject.md#getname)
- [GetOuter](ue_ue.MainObject.md#getouter)
- [GetStrings](ue_ue.MainObject.md#getstrings)
- [GetWorld](ue_ue.MainObject.md#getworld)
- [Mult](ue_ue.MainObject.md#mult)
- [NameTest](ue_ue.MainObject.md#nametest)
- [PassJsFunctionAsDelegate](ue_ue.MainObject.md#passjsfunctionasdelegate)
- [PrintState](ue_ue.MainObject.md#printstate)
- [Find](ue_ue.MainObject.md#find)
- [Load](ue_ue.MainObject.md#load)
- [StaticClass](ue_ue.MainObject.md#staticclass)

## Constructors

### constructor

• **new MainObject**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ArrayBuffer

• **ArrayBuffer**: `ArrayBuffer`

___

### MyArray

• **MyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### MyFixSizeArray

• **MyFixSizeArray**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<`number`\>

___

### MyMap

• **MyMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>

___

### MySet

• **MySet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`string`\>

___

### MyString

• **MyString**: `string`

___

### SomeData

• **SomeData**: [`SomeData`](ue_ue.SomeData.md)

___

### V

• **V**: [`Vector`](ue_ue_s.Vector.md)

___

### \_\_tid\_MainObject\_\_

• **\_\_tid\_MainObject\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

## Methods

### Add

▸ **Add**(`a`, `b`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `number` |
| `b` | `number` |

#### Returns

`number`

___

### ArrayBufferTest

▸ **ArrayBufferTest**(`Ab`): `ArrayBuffer`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Ab` | `ArrayBuffer` |

#### Returns

`ArrayBuffer`

___

### Bar

▸ **Bar**(`V`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`string`

___

### Bar2

▸ **Bar2**(`V`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`string`

___

### Bar3

▸ **Bar3**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### Callback\_\_DelegateSignature

▸ **Callback__DelegateSignature**(`A`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `string` |

#### Returns

`boolean`

___

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

### DefaultTest

▸ **DefaultTest**(`Str?`, `I?`, `Vec?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Str?` | `string` |
| `I?` | `number` |
| `Vec?` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### Div

▸ **Div**(`a`, `b`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `number` |
| `b` | `number` |

#### Returns

`number`

___

### EnumTest

▸ **EnumTest**(`E`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `E` | [`EToTest`](../enums/ue_ue.EToTest.md) |

#### Returns

`void`

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

### Foo

▸ **Foo**(): `string`

#### Returns

`string`

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetData

▸ **GetData**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### GetInts

▸ **GetInts**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

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

### GetStrings

▸ **GetStrings**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Mult

▸ **Mult**(`a`, `b`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `number` |
| `b` | `number` |

#### Returns

`number`

___

### NameTest

▸ **NameTest**(`Name`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |

#### Returns

`void`

___

### PassJsFunctionAsDelegate

▸ **PassJsFunctionAsDelegate**(`Callback`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Callback` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`A`: `string`) => `boolean`\> |

#### Returns

`void`

___

### PrintState

▸ **PrintState**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MainObject`](ue_ue.MainObject.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MainObject`](ue_ue.MainObject.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MainObject`](ue_ue.MainObject.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MainObject`](ue_ue.MainObject.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
