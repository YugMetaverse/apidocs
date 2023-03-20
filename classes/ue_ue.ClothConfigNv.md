[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClothConfigNv

# Class: ClothConfigNv

[ue/ue](../modules/ue_ue.md).ClothConfigNv

## Hierarchy

- [`ClothConfigBase`](ue_ue.ClothConfigBase.md)

  ↳ **`ClothConfigNv`**

## Table of contents

### Constructors

- [constructor](ue_ue.ClothConfigNv.md#constructor)

### Properties

- [AngularDrag](ue_ue.ClothConfigNv.md#angulardrag)
- [AngularInertiaScale](ue_ue.ClothConfigNv.md#angularinertiascale)
- [AnimDriveDamperStiffness](ue_ue.ClothConfigNv.md#animdrivedamperstiffness)
- [AnimDriveSpringStiffness](ue_ue.ClothConfigNv.md#animdrivespringstiffness)
- [BendConstraintConfig](ue_ue.ClothConfigNv.md#bendconstraintconfig)
- [CentrifugalInertiaScale](ue_ue.ClothConfigNv.md#centrifugalinertiascale)
- [CollisionThickness](ue_ue.ClothConfigNv.md#collisionthickness)
- [Damping](ue_ue.ClothConfigNv.md#damping)
- [Friction](ue_ue.ClothConfigNv.md#friction)
- [GravityOverride](ue_ue.ClothConfigNv.md#gravityoverride)
- [GravityScale](ue_ue.ClothConfigNv.md#gravityscale)
- [HorizontalConstraintConfig](ue_ue.ClothConfigNv.md#horizontalconstraintconfig)
- [LinearDrag](ue_ue.ClothConfigNv.md#lineardrag)
- [LinearInertiaScale](ue_ue.ClothConfigNv.md#linearinertiascale)
- [SelfCollisionCullScale](ue_ue.ClothConfigNv.md#selfcollisioncullscale)
- [SelfCollisionRadius](ue_ue.ClothConfigNv.md#selfcollisionradius)
- [SelfCollisionStiffness](ue_ue.ClothConfigNv.md#selfcollisionstiffness)
- [ShearConstraintConfig](ue_ue.ClothConfigNv.md#shearconstraintconfig)
- [SolverFrequency](ue_ue.ClothConfigNv.md#solverfrequency)
- [StiffnessFrequency](ue_ue.ClothConfigNv.md#stiffnessfrequency)
- [TetherLimit](ue_ue.ClothConfigNv.md#tetherlimit)
- [TetherStiffness](ue_ue.ClothConfigNv.md#tetherstiffness)
- [VerticalConstraintConfig](ue_ue.ClothConfigNv.md#verticalconstraintconfig)
- [WindDragCoefficient](ue_ue.ClothConfigNv.md#winddragcoefficient)
- [WindLiftCoefficient](ue_ue.ClothConfigNv.md#windliftcoefficient)
- [WindMethod](ue_ue.ClothConfigNv.md#windmethod)
- [\_\_tid\_ClothConfigBase\_\_](ue_ue.ClothConfigNv.md#__tid_clothconfigbase__)
- [\_\_tid\_ClothConfigNv\_\_](ue_ue.ClothConfigNv.md#__tid_clothconfignv__)
- [\_\_tid\_Object\_\_](ue_ue.ClothConfigNv.md#__tid_object__)
- [bUseGravityOverride](ue_ue.ClothConfigNv.md#busegravityoverride)

### Methods

- [CreateDefaultSubobject](ue_ue.ClothConfigNv.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ClothConfigNv.md#executeubergraph)
- [GetClass](ue_ue.ClothConfigNv.md#getclass)
- [GetName](ue_ue.ClothConfigNv.md#getname)
- [GetOuter](ue_ue.ClothConfigNv.md#getouter)
- [GetWorld](ue_ue.ClothConfigNv.md#getworld)
- [Find](ue_ue.ClothConfigNv.md#find)
- [Load](ue_ue.ClothConfigNv.md#load)
- [StaticClass](ue_ue.ClothConfigNv.md#staticclass)

## Constructors

### constructor

• **new ClothConfigNv**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ClothConfigBase](ue_ue.ClothConfigBase.md).[constructor](ue_ue.ClothConfigBase.md#constructor)

## Properties

### AngularDrag

• **AngularDrag**: [`Vector`](ue_ue_s.Vector.md)

___

### AngularInertiaScale

• **AngularInertiaScale**: [`Vector`](ue_ue_s.Vector.md)

___

### AnimDriveDamperStiffness

• **AnimDriveDamperStiffness**: `number`

___

### AnimDriveSpringStiffness

• **AnimDriveSpringStiffness**: `number`

___

### BendConstraintConfig

• **BendConstraintConfig**: [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md)

___

### CentrifugalInertiaScale

• **CentrifugalInertiaScale**: [`Vector`](ue_ue_s.Vector.md)

___

### CollisionThickness

• **CollisionThickness**: `number`

___

### Damping

• **Damping**: [`Vector`](ue_ue_s.Vector.md)

___

### Friction

• **Friction**: `number`

___

### GravityOverride

• **GravityOverride**: [`Vector`](ue_ue_s.Vector.md)

___

### GravityScale

• **GravityScale**: `number`

___

### HorizontalConstraintConfig

• **HorizontalConstraintConfig**: [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md)

___

### LinearDrag

• **LinearDrag**: [`Vector`](ue_ue_s.Vector.md)

___

### LinearInertiaScale

• **LinearInertiaScale**: [`Vector`](ue_ue_s.Vector.md)

___

### SelfCollisionCullScale

• **SelfCollisionCullScale**: `number`

___

### SelfCollisionRadius

• **SelfCollisionRadius**: `number`

___

### SelfCollisionStiffness

• **SelfCollisionStiffness**: `number`

___

### ShearConstraintConfig

• **ShearConstraintConfig**: [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md)

___

### SolverFrequency

• **SolverFrequency**: `number`

___

### StiffnessFrequency

• **StiffnessFrequency**: `number`

___

### TetherLimit

• **TetherLimit**: `number`

___

### TetherStiffness

• **TetherStiffness**: `number`

___

### VerticalConstraintConfig

• **VerticalConstraintConfig**: [`ClothConstraintSetup`](ue_ue.ClothConstraintSetup.md)

___

### WindDragCoefficient

• **WindDragCoefficient**: `number`

___

### WindLiftCoefficient

• **WindLiftCoefficient**: `number`

___

### WindMethod

• **WindMethod**: [`EClothingWindMethod`](../enums/ue_ue.EClothingWindMethod.md)

___

### \_\_tid\_ClothConfigBase\_\_

• **\_\_tid\_ClothConfigBase\_\_**: `boolean`

#### Inherited from

[ClothConfigBase](ue_ue.ClothConfigBase.md).[__tid_ClothConfigBase__](ue_ue.ClothConfigBase.md#__tid_clothconfigbase__)

___

### \_\_tid\_ClothConfigNv\_\_

• **\_\_tid\_ClothConfigNv\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ClothConfigBase](ue_ue.ClothConfigBase.md).[__tid_Object__](ue_ue.ClothConfigBase.md#__tid_object__)

___

### bUseGravityOverride

• **bUseGravityOverride**: `boolean`

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

[ClothConfigBase](ue_ue.ClothConfigBase.md).[CreateDefaultSubobject](ue_ue.ClothConfigBase.md#createdefaultsubobject)

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

[ClothConfigBase](ue_ue.ClothConfigBase.md).[ExecuteUbergraph](ue_ue.ClothConfigBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ClothConfigBase](ue_ue.ClothConfigBase.md).[GetClass](ue_ue.ClothConfigBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ClothConfigBase](ue_ue.ClothConfigBase.md).[GetName](ue_ue.ClothConfigBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ClothConfigBase](ue_ue.ClothConfigBase.md).[GetOuter](ue_ue.ClothConfigBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ClothConfigBase](ue_ue.ClothConfigBase.md).[GetWorld](ue_ue.ClothConfigBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ClothConfigNv`](ue_ue.ClothConfigNv.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ClothConfigNv`](ue_ue.ClothConfigNv.md)

#### Overrides

[ClothConfigBase](ue_ue.ClothConfigBase.md).[Find](ue_ue.ClothConfigBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ClothConfigNv`](ue_ue.ClothConfigNv.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ClothConfigNv`](ue_ue.ClothConfigNv.md)

#### Overrides

[ClothConfigBase](ue_ue.ClothConfigBase.md).[Load](ue_ue.ClothConfigBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ClothConfigBase](ue_ue.ClothConfigBase.md).[StaticClass](ue_ue.ClothConfigBase.md#staticclass)
