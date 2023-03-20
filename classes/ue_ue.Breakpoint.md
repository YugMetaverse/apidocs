[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Breakpoint

# Class: Breakpoint

[ue/ue](../modules/ue_ue.md).Breakpoint

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Breakpoint`**

## Table of contents

### Constructors

- [constructor](ue_ue.Breakpoint.md#constructor)

### Properties

- [Node](ue_ue.Breakpoint.md#node)
- [\_\_tid\_Breakpoint\_\_](ue_ue.Breakpoint.md#__tid_breakpoint__)
- [\_\_tid\_Object\_\_](ue_ue.Breakpoint.md#__tid_object__)
- [bEnabled](ue_ue.Breakpoint.md#benabled)
- [bStepOnce](ue_ue.Breakpoint.md#bsteponce)
- [bStepOnce\_RemoveAfterHit](ue_ue.Breakpoint.md#bsteponce_removeafterhit)
- [bStepOnce\_WasPreviouslyDisabled](ue_ue.Breakpoint.md#bsteponce_waspreviouslydisabled)

### Methods

- [CreateDefaultSubobject](ue_ue.Breakpoint.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Breakpoint.md#executeubergraph)
- [GetClass](ue_ue.Breakpoint.md#getclass)
- [GetName](ue_ue.Breakpoint.md#getname)
- [GetOuter](ue_ue.Breakpoint.md#getouter)
- [GetWorld](ue_ue.Breakpoint.md#getworld)
- [Find](ue_ue.Breakpoint.md#find)
- [Load](ue_ue.Breakpoint.md#load)
- [StaticClass](ue_ue.Breakpoint.md#staticclass)

## Constructors

### constructor

• **new Breakpoint**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Node

• **Node**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

___

### \_\_tid\_Breakpoint\_\_

• **\_\_tid\_Breakpoint\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bEnabled

• **bEnabled**: `boolean`

___

### bStepOnce

• **bStepOnce**: `boolean`

___

### bStepOnce\_RemoveAfterHit

• **bStepOnce\_RemoveAfterHit**: `boolean`

___

### bStepOnce\_WasPreviouslyDisabled

• **bStepOnce\_WasPreviouslyDisabled**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Breakpoint`](ue_ue.Breakpoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Breakpoint`](ue_ue.Breakpoint.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Breakpoint`](ue_ue.Breakpoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Breakpoint`](ue_ue.Breakpoint.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
