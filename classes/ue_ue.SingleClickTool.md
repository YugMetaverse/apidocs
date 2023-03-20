[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SingleClickTool

# Class: SingleClickTool

[ue/ue](../modules/ue_ue.md).SingleClickTool

## Hierarchy

- [`InteractiveTool`](ue_ue.InteractiveTool.md)

  ↳ **`SingleClickTool`**

## Table of contents

### Constructors

- [constructor](ue_ue.SingleClickTool.md#constructor)

### Properties

- [InputBehaviors](ue_ue.SingleClickTool.md#inputbehaviors)
- [ToolPropertyObjects](ue_ue.SingleClickTool.md#toolpropertyobjects)
- [\_\_tid\_InteractiveTool\_\_](ue_ue.SingleClickTool.md#__tid_interactivetool__)
- [\_\_tid\_Object\_\_](ue_ue.SingleClickTool.md#__tid_object__)
- [\_\_tid\_SingleClickTool\_\_](ue_ue.SingleClickTool.md#__tid_singleclicktool__)

### Methods

- [CreateDefaultSubobject](ue_ue.SingleClickTool.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SingleClickTool.md#executeubergraph)
- [GetClass](ue_ue.SingleClickTool.md#getclass)
- [GetName](ue_ue.SingleClickTool.md#getname)
- [GetOuter](ue_ue.SingleClickTool.md#getouter)
- [GetWorld](ue_ue.SingleClickTool.md#getworld)
- [Find](ue_ue.SingleClickTool.md#find)
- [Load](ue_ue.SingleClickTool.md#load)
- [StaticClass](ue_ue.SingleClickTool.md#staticclass)

## Constructors

### constructor

• **new SingleClickTool**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InteractiveTool](ue_ue.InteractiveTool.md).[constructor](ue_ue.InteractiveTool.md#constructor)

## Properties

### InputBehaviors

• **InputBehaviors**: [`InputBehaviorSet`](ue_ue.InputBehaviorSet.md)

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[InputBehaviors](ue_ue.InteractiveTool.md#inputbehaviors)

___

### ToolPropertyObjects

• **ToolPropertyObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[ToolPropertyObjects](ue_ue.InteractiveTool.md#toolpropertyobjects)

___

### \_\_tid\_InteractiveTool\_\_

• **\_\_tid\_InteractiveTool\_\_**: `boolean`

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[__tid_InteractiveTool__](ue_ue.InteractiveTool.md#__tid_interactivetool__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[__tid_Object__](ue_ue.InteractiveTool.md#__tid_object__)

___

### \_\_tid\_SingleClickTool\_\_

• **\_\_tid\_SingleClickTool\_\_**: `boolean`

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

[InteractiveTool](ue_ue.InteractiveTool.md).[CreateDefaultSubobject](ue_ue.InteractiveTool.md#createdefaultsubobject)

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

[InteractiveTool](ue_ue.InteractiveTool.md).[ExecuteUbergraph](ue_ue.InteractiveTool.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[GetClass](ue_ue.InteractiveTool.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[GetName](ue_ue.InteractiveTool.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[GetOuter](ue_ue.InteractiveTool.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[GetWorld](ue_ue.InteractiveTool.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SingleClickTool`](ue_ue.SingleClickTool.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SingleClickTool`](ue_ue.SingleClickTool.md)

#### Overrides

[InteractiveTool](ue_ue.InteractiveTool.md).[Find](ue_ue.InteractiveTool.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SingleClickTool`](ue_ue.SingleClickTool.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SingleClickTool`](ue_ue.SingleClickTool.md)

#### Overrides

[InteractiveTool](ue_ue.InteractiveTool.md).[Load](ue_ue.InteractiveTool.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InteractiveTool](ue_ue.InteractiveTool.md).[StaticClass](ue_ue.InteractiveTool.md#staticclass)
