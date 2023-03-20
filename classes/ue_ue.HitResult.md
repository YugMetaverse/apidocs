[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / HitResult

# Class: HitResult

[ue/ue](../modules/ue_ue.md).HitResult

## Table of contents

### Constructors

- [constructor](ue_ue.HitResult.md#constructor)

### Properties

- [Actor](ue_ue.HitResult.md#actor)
- [BoneName](ue_ue.HitResult.md#bonename)
- [Component](ue_ue.HitResult.md#component)
- [Distance](ue_ue.HitResult.md#distance)
- [FaceIndex](ue_ue.HitResult.md#faceindex)
- [ImpactNormal](ue_ue.HitResult.md#impactnormal)
- [ImpactPoint](ue_ue.HitResult.md#impactpoint)
- [Item](ue_ue.HitResult.md#item)
- [Location](ue_ue.HitResult.md#location)
- [MyBoneName](ue_ue.HitResult.md#mybonename)
- [Normal](ue_ue.HitResult.md#normal)
- [PenetrationDepth](ue_ue.HitResult.md#penetrationdepth)
- [PhysMaterial](ue_ue.HitResult.md#physmaterial)
- [Time](ue_ue.HitResult.md#time)
- [TraceEnd](ue_ue.HitResult.md#traceend)
- [TraceStart](ue_ue.HitResult.md#tracestart)
- [\_\_tid\_HitResult\_\_](ue_ue.HitResult.md#__tid_hitresult__)
- [bBlockingHit](ue_ue.HitResult.md#bblockinghit)
- [bStartPenetrating](ue_ue.HitResult.md#bstartpenetrating)

### Methods

- [StaticClass](ue_ue.HitResult.md#staticclass)
- [StaticStruct](ue_ue.HitResult.md#staticstruct)

## Constructors

### constructor

• **new HitResult**()

• **new HitResult**(`bBlockingHit`, `bStartPenetrating`, `FaceIndex`, `Time`, `Distance`, `Location`, `ImpactPoint`, `Normal`, `ImpactNormal`, `TraceStart`, `TraceEnd`, `PenetrationDepth`, `Item`, `PhysMaterial`, `Actor`, `Component`, `BoneName`, `MyBoneName`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `bBlockingHit` | `boolean` |
| `bStartPenetrating` | `boolean` |
| `FaceIndex` | `number` |
| `Time` | `number` |
| `Distance` | `number` |
| `Location` | [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md) |
| `ImpactPoint` | [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md) |
| `Normal` | [`Vector_NetQuantizeNormal`](ue_ue.Vector_NetQuantizeNormal.md) |
| `ImpactNormal` | [`Vector_NetQuantizeNormal`](ue_ue.Vector_NetQuantizeNormal.md) |
| `TraceStart` | [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md) |
| `TraceEnd` | [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md) |
| `PenetrationDepth` | `number` |
| `Item` | `number` |
| `PhysMaterial` | [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)\> |
| `Actor` | [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\> |
| `Component` | [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `BoneName` | `string` |
| `MyBoneName` | `string` |

## Properties

### Actor

• **Actor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

___

### BoneName

• **BoneName**: `string`

___

### Component

• **Component**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

___

### Distance

• **Distance**: `number`

___

### FaceIndex

• **FaceIndex**: `number`

___

### ImpactNormal

• **ImpactNormal**: [`Vector_NetQuantizeNormal`](ue_ue.Vector_NetQuantizeNormal.md)

___

### ImpactPoint

• **ImpactPoint**: [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md)

___

### Item

• **Item**: `number`

___

### Location

• **Location**: [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md)

___

### MyBoneName

• **MyBoneName**: `string`

___

### Normal

• **Normal**: [`Vector_NetQuantizeNormal`](ue_ue.Vector_NetQuantizeNormal.md)

___

### PenetrationDepth

• **PenetrationDepth**: `number`

___

### PhysMaterial

• **PhysMaterial**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)\>

___

### Time

• **Time**: `number`

___

### TraceEnd

• **TraceEnd**: [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md)

___

### TraceStart

• **TraceStart**: [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md)

___

### \_\_tid\_HitResult\_\_

• `Private` **\_\_tid\_HitResult\_\_**: `boolean`

___

### bBlockingHit

• **bBlockingHit**: `boolean`

___

### bStartPenetrating

• **bStartPenetrating**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
