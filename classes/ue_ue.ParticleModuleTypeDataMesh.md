[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleTypeDataMesh

# Class: ParticleModuleTypeDataMesh

[ue/ue](../modules/ue_ue.md).ParticleModuleTypeDataMesh

## Hierarchy

- [`ParticleModuleTypeDataBase`](ue_ue.ParticleModuleTypeDataBase.md)

  ↳ **`ParticleModuleTypeDataMesh`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleTypeDataMesh.md#constructor)

### Properties

- [AxisLockOption](ue_ue.ParticleModuleTypeDataMesh.md#axislockoption)
- [CameraFacingOption](ue_ue.ParticleModuleTypeDataMesh.md#camerafacingoption)
- [CameraFacingUpAxisOption](ue_ue.ParticleModuleTypeDataMesh.md#camerafacingupaxisoption)
- [CastShadows](ue_ue.ParticleModuleTypeDataMesh.md#castshadows)
- [DoCollisions](ue_ue.ParticleModuleTypeDataMesh.md#docollisions)
- [LODDuplicate](ue_ue.ParticleModuleTypeDataMesh.md#lodduplicate)
- [LODSizeScale](ue_ue.ParticleModuleTypeDataMesh.md#lodsizescale)
- [LODValidity](ue_ue.ParticleModuleTypeDataMesh.md#lodvalidity)
- [Mesh](ue_ue.ParticleModuleTypeDataMesh.md#mesh)
- [MeshAlignment](ue_ue.ParticleModuleTypeDataMesh.md#meshalignment)
- [ModuleEditorColor](ue_ue.ParticleModuleTypeDataMesh.md#moduleeditorcolor)
- [RollPitchYawRange](ue_ue.ParticleModuleTypeDataMesh.md#rollpitchyawrange)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleTypeDataMesh.md#__tid_object__)
- [\_\_tid\_ParticleModuleTypeDataBase\_\_](ue_ue.ParticleModuleTypeDataMesh.md#__tid_particlemoduletypedatabase__)
- [\_\_tid\_ParticleModuleTypeDataMesh\_\_](ue_ue.ParticleModuleTypeDataMesh.md#__tid_particlemoduletypedatamesh__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleTypeDataMesh.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleTypeDataMesh.md#b3ddrawmode)
- [bApplyParticleRotationAsSpin](ue_ue.ParticleModuleTypeDataMesh.md#bapplyparticlerotationasspin)
- [bCameraFacing](ue_ue.ParticleModuleTypeDataMesh.md#bcamerafacing)
- [bCollisionsConsiderPartilceSize](ue_ue.ParticleModuleTypeDataMesh.md#bcollisionsconsiderpartilcesize)
- [bCurvesAsColor](ue_ue.ParticleModuleTypeDataMesh.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleTypeDataMesh.md#beditable)
- [bEnableMotionBlur](ue_ue.ParticleModuleTypeDataMesh.md#benablemotionblur)
- [bEnabled](ue_ue.ParticleModuleTypeDataMesh.md#benabled)
- [bFaceCameraDirectionRatherThanPosition](ue_ue.ParticleModuleTypeDataMesh.md#bfacecameradirectionratherthanposition)
- [bFinalUpdateModule](ue_ue.ParticleModuleTypeDataMesh.md#bfinalupdatemodule)
- [bOverrideDefaultMotionBlurSettings](ue_ue.ParticleModuleTypeDataMesh.md#boverridedefaultmotionblursettings)
- [bOverrideMaterial](ue_ue.ParticleModuleTypeDataMesh.md#boverridematerial)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleTypeDataMesh.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleTypeDataMesh.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleTypeDataMesh.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleTypeDataMesh.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleTypeDataMesh.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleTypeDataMesh.md#bupdatemodule)
- [bUseStaticMeshLODs](ue_ue.ParticleModuleTypeDataMesh.md#busestaticmeshlods)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleTypeDataMesh.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleTypeDataMesh.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleTypeDataMesh.md#getclass)
- [GetName](ue_ue.ParticleModuleTypeDataMesh.md#getname)
- [GetOuter](ue_ue.ParticleModuleTypeDataMesh.md#getouter)
- [GetWorld](ue_ue.ParticleModuleTypeDataMesh.md#getworld)
- [Find](ue_ue.ParticleModuleTypeDataMesh.md#find)
- [Load](ue_ue.ParticleModuleTypeDataMesh.md#load)
- [StaticClass](ue_ue.ParticleModuleTypeDataMesh.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleTypeDataMesh**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[constructor](ue_ue.ParticleModuleTypeDataBase.md#constructor)

## Properties

### AxisLockOption

• **AxisLockOption**: [`EParticleAxisLock`](../enums/ue_ue.EParticleAxisLock.md)

___

### CameraFacingOption

• **CameraFacingOption**: [`EMeshCameraFacingOptions`](../enums/ue_ue.EMeshCameraFacingOptions.md)

___

### CameraFacingUpAxisOption

• **CameraFacingUpAxisOption**: [`EMeshCameraFacingUpAxis`](../enums/ue_ue.EMeshCameraFacingUpAxis.md)

___

### CastShadows

• **CastShadows**: `boolean`

___

### DoCollisions

• **DoCollisions**: `boolean`

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[LODDuplicate](ue_ue.ParticleModuleTypeDataBase.md#lodduplicate)

___

### LODSizeScale

• **LODSizeScale**: `number`

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[LODValidity](ue_ue.ParticleModuleTypeDataBase.md#lodvalidity)

___

### Mesh

• **Mesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### MeshAlignment

• **MeshAlignment**: [`EMeshScreenAlignment`](../enums/ue_ue.EMeshScreenAlignment.md)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[ModuleEditorColor](ue_ue.ParticleModuleTypeDataBase.md#moduleeditorcolor)

___

### RollPitchYawRange

• **RollPitchYawRange**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[__tid_Object__](ue_ue.ParticleModuleTypeDataBase.md#__tid_object__)

___

### \_\_tid\_ParticleModuleTypeDataBase\_\_

• **\_\_tid\_ParticleModuleTypeDataBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[__tid_ParticleModuleTypeDataBase__](ue_ue.ParticleModuleTypeDataBase.md#__tid_particlemoduletypedatabase__)

___

### \_\_tid\_ParticleModuleTypeDataMesh\_\_

• **\_\_tid\_ParticleModuleTypeDataMesh\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleTypeDataBase.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[b3DDrawMode](ue_ue.ParticleModuleTypeDataBase.md#b3ddrawmode)

___

### bApplyParticleRotationAsSpin

• **bApplyParticleRotationAsSpin**: `boolean`

___

### bCameraFacing

• **bCameraFacing**: `boolean`

___

### bCollisionsConsiderPartilceSize

• **bCollisionsConsiderPartilceSize**: `boolean`

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bCurvesAsColor](ue_ue.ParticleModuleTypeDataBase.md#bcurvesascolor)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bEditable](ue_ue.ParticleModuleTypeDataBase.md#beditable)

___

### bEnableMotionBlur

• **bEnableMotionBlur**: `boolean`

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bEnabled](ue_ue.ParticleModuleTypeDataBase.md#benabled)

___

### bFaceCameraDirectionRatherThanPosition

• **bFaceCameraDirectionRatherThanPosition**: `boolean`

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleTypeDataBase.md#bfinalupdatemodule)

___

### bOverrideDefaultMotionBlurSettings

• **bOverrideDefaultMotionBlurSettings**: `boolean`

___

### bOverrideMaterial

• **bOverrideMaterial**: `boolean`

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleTypeDataBase.md#brequiresloopingnotification)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bSpawnModule](ue_ue.ParticleModuleTypeDataBase.md#bspawnmodule)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleTypeDataBase.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleTypeDataBase.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleTypeDataBase.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[bUpdateModule](ue_ue.ParticleModuleTypeDataBase.md#bupdatemodule)

___

### bUseStaticMeshLODs

• **bUseStaticMeshLODs**: `boolean`

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

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleTypeDataBase.md#createdefaultsubobject)

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

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleTypeDataBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetClass](ue_ue.ParticleModuleTypeDataBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetName](ue_ue.ParticleModuleTypeDataBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetOuter](ue_ue.ParticleModuleTypeDataBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[GetWorld](ue_ue.ParticleModuleTypeDataBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleTypeDataMesh`](ue_ue.ParticleModuleTypeDataMesh.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleTypeDataMesh`](ue_ue.ParticleModuleTypeDataMesh.md)

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[Find](ue_ue.ParticleModuleTypeDataBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleTypeDataMesh`](ue_ue.ParticleModuleTypeDataMesh.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleTypeDataMesh`](ue_ue.ParticleModuleTypeDataMesh.md)

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[Load](ue_ue.ParticleModuleTypeDataBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleTypeDataBase](ue_ue.ParticleModuleTypeDataBase.md).[StaticClass](ue_ue.ParticleModuleTypeDataBase.md#staticclass)
