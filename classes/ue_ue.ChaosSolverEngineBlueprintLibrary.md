[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ChaosSolverEngineBlueprintLibrary

# Class: ChaosSolverEngineBlueprintLibrary

[ue/ue](../modules/ue_ue.md).ChaosSolverEngineBlueprintLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`ChaosSolverEngineBlueprintLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.ChaosSolverEngineBlueprintLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.ChaosSolverEngineBlueprintLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_ChaosSolverEngineBlueprintLibrary\_\_](ue_ue.ChaosSolverEngineBlueprintLibrary.md#__tid_chaossolverengineblueprintlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.ChaosSolverEngineBlueprintLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ChaosSolverEngineBlueprintLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ChaosSolverEngineBlueprintLibrary.md#executeubergraph)
- [GetClass](ue_ue.ChaosSolverEngineBlueprintLibrary.md#getclass)
- [GetName](ue_ue.ChaosSolverEngineBlueprintLibrary.md#getname)
- [GetOuter](ue_ue.ChaosSolverEngineBlueprintLibrary.md#getouter)
- [GetWorld](ue_ue.ChaosSolverEngineBlueprintLibrary.md#getworld)
- [ConvertPhysicsCollisionToHitResult](ue_ue.ChaosSolverEngineBlueprintLibrary.md#convertphysicscollisiontohitresult)
- [Find](ue_ue.ChaosSolverEngineBlueprintLibrary.md#find)
- [Load](ue_ue.ChaosSolverEngineBlueprintLibrary.md#load)
- [StaticClass](ue_ue.ChaosSolverEngineBlueprintLibrary.md#staticclass)

## Constructors

### constructor

• **new ChaosSolverEngineBlueprintLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_ChaosSolverEngineBlueprintLibrary\_\_

• **\_\_tid\_ChaosSolverEngineBlueprintLibrary\_\_**: `boolean`

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

### ConvertPhysicsCollisionToHitResult

▸ `Static` **ConvertPhysicsCollisionToHitResult**(`PhysicsCollision`): [`HitResult`](ue_ue.HitResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PhysicsCollision` | [`ChaosPhysicsCollisionInfo`](ue_ue.ChaosPhysicsCollisionInfo.md) |

#### Returns

[`HitResult`](ue_ue.HitResult.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ChaosSolverEngineBlueprintLibrary`](ue_ue.ChaosSolverEngineBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ChaosSolverEngineBlueprintLibrary`](ue_ue.ChaosSolverEngineBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ChaosSolverEngineBlueprintLibrary`](ue_ue.ChaosSolverEngineBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ChaosSolverEngineBlueprintLibrary`](ue_ue.ChaosSolverEngineBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
