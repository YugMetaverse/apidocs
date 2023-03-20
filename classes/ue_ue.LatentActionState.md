[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LatentActionState

# Class: LatentActionState

[ue/ue](../modules/ue_ue.md).LatentActionState

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LatentActionState`**

## Table of contents

### Constructors

- [constructor](ue_ue.LatentActionState.md#constructor)

### Properties

- [LatentActionCallback](ue_ue.LatentActionState.md#latentactioncallback)
- [\_\_tid\_LatentActionState\_\_](ue_ue.LatentActionState.md#__tid_latentactionstate__)
- [\_\_tid\_Object\_\_](ue_ue.LatentActionState.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LatentActionState.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LatentActionState.md#executeubergraph)
- [GetClass](ue_ue.LatentActionState.md#getclass)
- [GetLatentActionInfo](ue_ue.LatentActionState.md#getlatentactioninfo)
- [GetName](ue_ue.LatentActionState.md#getname)
- [GetOuter](ue_ue.LatentActionState.md#getouter)
- [GetWorld](ue_ue.LatentActionState.md#getworld)
- [OnLatentActionCompleted](ue_ue.LatentActionState.md#onlatentactioncompleted)
- [Find](ue_ue.LatentActionState.md#find)
- [Load](ue_ue.LatentActionState.md#load)
- [StaticClass](ue_ue.LatentActionState.md#staticclass)

## Constructors

### constructor

• **new LatentActionState**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### LatentActionCallback

• **LatentActionCallback**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\>

___

### \_\_tid\_LatentActionState\_\_

• **\_\_tid\_LatentActionState\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

### GetLatentActionInfo

▸ **GetLatentActionInfo**(): [`LatentActionInfo`](ue_ue.LatentActionInfo.md)

#### Returns

[`LatentActionInfo`](ue_ue.LatentActionInfo.md)

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

### OnLatentActionCompleted

▸ **OnLatentActionCompleted**(`LinkID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LinkID` | `number` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LatentActionState`](ue_ue.LatentActionState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LatentActionState`](ue_ue.LatentActionState.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LatentActionState`](ue_ue.LatentActionState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LatentActionState`](ue_ue.LatentActionState.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
