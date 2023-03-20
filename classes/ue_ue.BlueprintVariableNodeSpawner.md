[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintVariableNodeSpawner

# Class: BlueprintVariableNodeSpawner

[ue/ue](../modules/ue_ue.md).BlueprintVariableNodeSpawner

## Hierarchy

- [`BlueprintFieldNodeSpawner`](ue_ue.BlueprintFieldNodeSpawner.md)

  ↳ **`BlueprintVariableNodeSpawner`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintVariableNodeSpawner.md#constructor)

### Properties

- [Field](ue_ue.BlueprintVariableNodeSpawner.md#field)
- [LocalVarDesc](ue_ue.BlueprintVariableNodeSpawner.md#localvardesc)
- [LocalVarOuter](ue_ue.BlueprintVariableNodeSpawner.md#localvarouter)
- [NodeClass](ue_ue.BlueprintVariableNodeSpawner.md#nodeclass)
- [OwnerClass](ue_ue.BlueprintVariableNodeSpawner.md#ownerclass)
- [\_\_tid\_BlueprintFieldNodeSpawner\_\_](ue_ue.BlueprintVariableNodeSpawner.md#__tid_blueprintfieldnodespawner__)
- [\_\_tid\_BlueprintNodeSpawner\_\_](ue_ue.BlueprintVariableNodeSpawner.md#__tid_blueprintnodespawner__)
- [\_\_tid\_BlueprintVariableNodeSpawner\_\_](ue_ue.BlueprintVariableNodeSpawner.md#__tid_blueprintvariablenodespawner__)
- [\_\_tid\_Object\_\_](ue_ue.BlueprintVariableNodeSpawner.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BlueprintVariableNodeSpawner.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlueprintVariableNodeSpawner.md#executeubergraph)
- [GetClass](ue_ue.BlueprintVariableNodeSpawner.md#getclass)
- [GetName](ue_ue.BlueprintVariableNodeSpawner.md#getname)
- [GetOuter](ue_ue.BlueprintVariableNodeSpawner.md#getouter)
- [GetWorld](ue_ue.BlueprintVariableNodeSpawner.md#getworld)
- [Find](ue_ue.BlueprintVariableNodeSpawner.md#find)
- [Load](ue_ue.BlueprintVariableNodeSpawner.md#load)
- [StaticClass](ue_ue.BlueprintVariableNodeSpawner.md#staticclass)

## Constructors

### constructor

• **new BlueprintVariableNodeSpawner**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[constructor](ue_ue.BlueprintFieldNodeSpawner.md#constructor)

## Properties

### Field

• **Field**: [`Field`](ue_ue.Field.md)

#### Inherited from

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[Field](ue_ue.BlueprintFieldNodeSpawner.md#field)

___

### LocalVarDesc

• **LocalVarDesc**: [`BPVariableDescription`](ue_ue.BPVariableDescription.md)

___

### LocalVarOuter

• **LocalVarOuter**: [`EdGraph`](ue_ue.EdGraph.md)

___

### NodeClass

• **NodeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[NodeClass](ue_ue.BlueprintFieldNodeSpawner.md#nodeclass)

___

### OwnerClass

• **OwnerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[OwnerClass](ue_ue.BlueprintFieldNodeSpawner.md#ownerclass)

___

### \_\_tid\_BlueprintFieldNodeSpawner\_\_

• **\_\_tid\_BlueprintFieldNodeSpawner\_\_**: `boolean`

#### Inherited from

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[__tid_BlueprintFieldNodeSpawner__](ue_ue.BlueprintFieldNodeSpawner.md#__tid_blueprintfieldnodespawner__)

___

### \_\_tid\_BlueprintNodeSpawner\_\_

• **\_\_tid\_BlueprintNodeSpawner\_\_**: `boolean`

#### Inherited from

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[__tid_BlueprintNodeSpawner__](ue_ue.BlueprintFieldNodeSpawner.md#__tid_blueprintnodespawner__)

___

### \_\_tid\_BlueprintVariableNodeSpawner\_\_

• **\_\_tid\_BlueprintVariableNodeSpawner\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[__tid_Object__](ue_ue.BlueprintFieldNodeSpawner.md#__tid_object__)

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

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[CreateDefaultSubobject](ue_ue.BlueprintFieldNodeSpawner.md#createdefaultsubobject)

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

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[ExecuteUbergraph](ue_ue.BlueprintFieldNodeSpawner.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[GetClass](ue_ue.BlueprintFieldNodeSpawner.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[GetName](ue_ue.BlueprintFieldNodeSpawner.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[GetOuter](ue_ue.BlueprintFieldNodeSpawner.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[GetWorld](ue_ue.BlueprintFieldNodeSpawner.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlueprintVariableNodeSpawner`](ue_ue.BlueprintVariableNodeSpawner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlueprintVariableNodeSpawner`](ue_ue.BlueprintVariableNodeSpawner.md)

#### Overrides

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[Find](ue_ue.BlueprintFieldNodeSpawner.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BlueprintVariableNodeSpawner`](ue_ue.BlueprintVariableNodeSpawner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlueprintVariableNodeSpawner`](ue_ue.BlueprintVariableNodeSpawner.md)

#### Overrides

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[Load](ue_ue.BlueprintFieldNodeSpawner.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFieldNodeSpawner](ue_ue.BlueprintFieldNodeSpawner.md).[StaticClass](ue_ue.BlueprintFieldNodeSpawner.md#staticclass)
