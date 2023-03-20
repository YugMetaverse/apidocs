[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PhysAssetCreateParams

# Class: PhysAssetCreateParams

[ue/ue](../modules/ue_ue.md).PhysAssetCreateParams

## Table of contents

### Constructors

- [constructor](ue_ue.PhysAssetCreateParams.md#constructor)

### Properties

- [AngularConstraintMode](ue_ue.PhysAssetCreateParams.md#angularconstraintmode)
- [GeomType](ue_ue.PhysAssetCreateParams.md#geomtype)
- [HullCount](ue_ue.PhysAssetCreateParams.md#hullcount)
- [MaxHullVerts](ue_ue.PhysAssetCreateParams.md#maxhullverts)
- [MinBoneSize](ue_ue.PhysAssetCreateParams.md#minbonesize)
- [MinWeldSize](ue_ue.PhysAssetCreateParams.md#minweldsize)
- [VertWeight](ue_ue.PhysAssetCreateParams.md#vertweight)
- [\_\_tid\_PhysAssetCreateParams\_\_](ue_ue.PhysAssetCreateParams.md#__tid_physassetcreateparams__)
- [bAutoOrientToBone](ue_ue.PhysAssetCreateParams.md#bautoorienttobone)
- [bBodyForAll](ue_ue.PhysAssetCreateParams.md#bbodyforall)
- [bCreateConstraints](ue_ue.PhysAssetCreateParams.md#bcreateconstraints)
- [bDisableCollisionsByDefault](ue_ue.PhysAssetCreateParams.md#bdisablecollisionsbydefault)
- [bWalkPastSmall](ue_ue.PhysAssetCreateParams.md#bwalkpastsmall)

### Methods

- [StaticClass](ue_ue.PhysAssetCreateParams.md#staticclass)
- [StaticStruct](ue_ue.PhysAssetCreateParams.md#staticstruct)

## Constructors

### constructor

• **new PhysAssetCreateParams**()

• **new PhysAssetCreateParams**(`MinBoneSize`, `MinWeldSize`, `GeomType`, `VertWeight`, `bAutoOrientToBone`, `bCreateConstraints`, `bWalkPastSmall`, `bBodyForAll`, `bDisableCollisionsByDefault`, `AngularConstraintMode`, `HullCount`, `MaxHullVerts`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MinBoneSize` | `number` |
| `MinWeldSize` | `number` |
| `GeomType` | [`EPhysAssetFitGeomType`](../enums/ue_ue.EPhysAssetFitGeomType.md) |
| `VertWeight` | [`EPhysAssetFitVertWeight`](../enums/ue_ue.EPhysAssetFitVertWeight.md) |
| `bAutoOrientToBone` | `boolean` |
| `bCreateConstraints` | `boolean` |
| `bWalkPastSmall` | `boolean` |
| `bBodyForAll` | `boolean` |
| `bDisableCollisionsByDefault` | `boolean` |
| `AngularConstraintMode` | [`EAngularConstraintMotion`](../enums/ue_ue.EAngularConstraintMotion.md) |
| `HullCount` | `number` |
| `MaxHullVerts` | `number` |

## Properties

### AngularConstraintMode

• **AngularConstraintMode**: [`EAngularConstraintMotion`](../enums/ue_ue.EAngularConstraintMotion.md)

___

### GeomType

• **GeomType**: [`EPhysAssetFitGeomType`](../enums/ue_ue.EPhysAssetFitGeomType.md)

___

### HullCount

• **HullCount**: `number`

___

### MaxHullVerts

• **MaxHullVerts**: `number`

___

### MinBoneSize

• **MinBoneSize**: `number`

___

### MinWeldSize

• **MinWeldSize**: `number`

___

### VertWeight

• **VertWeight**: [`EPhysAssetFitVertWeight`](../enums/ue_ue.EPhysAssetFitVertWeight.md)

___

### \_\_tid\_PhysAssetCreateParams\_\_

• `Private` **\_\_tid\_PhysAssetCreateParams\_\_**: `boolean`

___

### bAutoOrientToBone

• **bAutoOrientToBone**: `boolean`

___

### bBodyForAll

• **bBodyForAll**: `boolean`

___

### bCreateConstraints

• **bCreateConstraints**: `boolean`

___

### bDisableCollisionsByDefault

• **bDisableCollisionsByDefault**: `boolean`

___

### bWalkPastSmall

• **bWalkPastSmall**: `boolean`

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
