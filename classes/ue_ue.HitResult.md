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

#### Defined in

[ue/ue.d.ts:853](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L853)

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

#### Defined in

[ue/ue.d.ts:854](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L854)

## Properties

### Actor

• **Actor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:869](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L869)

___

### BoneName

• **BoneName**: `string`

#### Defined in

[ue/ue.d.ts:871](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L871)

___

### Component

• **Component**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Defined in

[ue/ue.d.ts:870](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L870)

___

### Distance

• **Distance**: `number`

#### Defined in

[ue/ue.d.ts:859](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L859)

___

### FaceIndex

• **FaceIndex**: `number`

#### Defined in

[ue/ue.d.ts:857](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L857)

___

### ImpactNormal

• **ImpactNormal**: [`Vector_NetQuantizeNormal`](ue_ue.Vector_NetQuantizeNormal.md)

#### Defined in

[ue/ue.d.ts:863](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L863)

___

### ImpactPoint

• **ImpactPoint**: [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md)

#### Defined in

[ue/ue.d.ts:861](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L861)

___

### Item

• **Item**: `number`

#### Defined in

[ue/ue.d.ts:867](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L867)

___

### Location

• **Location**: [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md)

#### Defined in

[ue/ue.d.ts:860](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L860)

___

### MyBoneName

• **MyBoneName**: `string`

#### Defined in

[ue/ue.d.ts:872](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L872)

___

### Normal

• **Normal**: [`Vector_NetQuantizeNormal`](ue_ue.Vector_NetQuantizeNormal.md)

#### Defined in

[ue/ue.d.ts:862](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L862)

___

### PenetrationDepth

• **PenetrationDepth**: `number`

#### Defined in

[ue/ue.d.ts:866](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L866)

___

### PhysMaterial

• **PhysMaterial**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)\>

#### Defined in

[ue/ue.d.ts:868](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L868)

___

### Time

• **Time**: `number`

#### Defined in

[ue/ue.d.ts:858](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L858)

___

### TraceEnd

• **TraceEnd**: [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md)

#### Defined in

[ue/ue.d.ts:865](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L865)

___

### TraceStart

• **TraceStart**: [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md)

#### Defined in

[ue/ue.d.ts:864](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L864)

___

### \_\_tid\_HitResult\_\_

• `Private` **\_\_tid\_HitResult\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:878](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L878)

___

### bBlockingHit

• **bBlockingHit**: `boolean`

#### Defined in

[ue/ue.d.ts:855](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L855)

___

### bStartPenetrating

• **bStartPenetrating**: `boolean`

#### Defined in

[ue/ue.d.ts:856](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L856)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L876)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:877](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L877)
