[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / StaticMeshSimulationComponent

# Class: StaticMeshSimulationComponent

[ue/ue](../modules/ue_ue.md).StaticMeshSimulationComponent

## Hierarchy

- [`ActorComponent`](ue_ue.ActorComponent.md)

  ↳ **`StaticMeshSimulationComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.StaticMeshSimulationComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.StaticMeshSimulationComponent.md#assetuserdata)
- [ChaosSolverActor](ue_ue.StaticMeshSimulationComponent.md#chaossolveractor)
- [CollisionType](ue_ue.StaticMeshSimulationComponent.md#collisiontype)
- [ComponentTags](ue_ue.StaticMeshSimulationComponent.md#componenttags)
- [CreationMethod](ue_ue.StaticMeshSimulationComponent.md#creationmethod)
- [DamageThreshold](ue_ue.StaticMeshSimulationComponent.md#damagethreshold)
- [ImplicitType](ue_ue.StaticMeshSimulationComponent.md#implicittype)
- [InitialAngularVelocity](ue_ue.StaticMeshSimulationComponent.md#initialangularvelocity)
- [InitialLinearVelocity](ue_ue.StaticMeshSimulationComponent.md#initiallinearvelocity)
- [InitialVelocityType](ue_ue.StaticMeshSimulationComponent.md#initialvelocitytype)
- [Mass](ue_ue.StaticMeshSimulationComponent.md#mass)
- [MaxLevelSetResolution](ue_ue.StaticMeshSimulationComponent.md#maxlevelsetresolution)
- [MinLevelSetResolution](ue_ue.StaticMeshSimulationComponent.md#minlevelsetresolution)
- [ObjectType](ue_ue.StaticMeshSimulationComponent.md#objecttype)
- [OnChaosPhysicsCollision](ue_ue.StaticMeshSimulationComponent.md#onchaosphysicscollision)
- [OnComponentActivated](ue_ue.StaticMeshSimulationComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.StaticMeshSimulationComponent.md#oncomponentdeactivated)
- [PhysicalMaterial](ue_ue.StaticMeshSimulationComponent.md#physicalmaterial)
- [PrimaryComponentTick](ue_ue.StaticMeshSimulationComponent.md#primarycomponenttick)
- [SimulatedComponents](ue_ue.StaticMeshSimulationComponent.md#simulatedcomponents)
- [Simulating](ue_ue.StaticMeshSimulationComponent.md#simulating)
- [UCSModifiedProperties](ue_ue.StaticMeshSimulationComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.StaticMeshSimulationComponent.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.StaticMeshSimulationComponent.md#__tid_object__)
- [\_\_tid\_StaticMeshSimulationComponent\_\_](ue_ue.StaticMeshSimulationComponent.md#__tid_staticmeshsimulationcomponent__)
- [bAutoActivate](ue_ue.StaticMeshSimulationComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.StaticMeshSimulationComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.StaticMeshSimulationComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.StaticMeshSimulationComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.StaticMeshSimulationComponent.md#binstancecomponent)
- [bIsActive](ue_ue.StaticMeshSimulationComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.StaticMeshSimulationComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.StaticMeshSimulationComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.StaticMeshSimulationComponent.md#bnetaddressable)
- [bNotifyCollisions](ue_ue.StaticMeshSimulationComponent.md#bnotifycollisions)
- [bReplicates](ue_ue.StaticMeshSimulationComponent.md#breplicates)

### Methods

- [Activate](ue_ue.StaticMeshSimulationComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.StaticMeshSimulationComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.StaticMeshSimulationComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.StaticMeshSimulationComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.StaticMeshSimulationComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.StaticMeshSimulationComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.StaticMeshSimulationComponent.md#executeubergraph)
- [ForceRecreatePhysicsState](ue_ue.StaticMeshSimulationComponent.md#forcerecreatephysicsstate)
- [GetClass](ue_ue.StaticMeshSimulationComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.StaticMeshSimulationComponent.md#getcomponenttickinterval)
- [GetName](ue_ue.StaticMeshSimulationComponent.md#getname)
- [GetOuter](ue_ue.StaticMeshSimulationComponent.md#getouter)
- [GetOwner](ue_ue.StaticMeshSimulationComponent.md#getowner)
- [GetWorld](ue_ue.StaticMeshSimulationComponent.md#getworld)
- [IsActive](ue_ue.StaticMeshSimulationComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.StaticMeshSimulationComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.StaticMeshSimulationComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.StaticMeshSimulationComponent.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.StaticMeshSimulationComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.StaticMeshSimulationComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.StaticMeshSimulationComponent.md#receiveendplay)
- [ReceivePhysicsCollision](ue_ue.StaticMeshSimulationComponent.md#receivephysicscollision)
- [ReceiveTick](ue_ue.StaticMeshSimulationComponent.md#receivetick)
- [RegisterComponent](ue_ue.StaticMeshSimulationComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.StaticMeshSimulationComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.StaticMeshSimulationComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.StaticMeshSimulationComponent.md#setactive)
- [SetAutoActivate](ue_ue.StaticMeshSimulationComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.StaticMeshSimulationComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.StaticMeshSimulationComponent.md#setcomponenttickinterval)
- [SetIsReplicated](ue_ue.StaticMeshSimulationComponent.md#setisreplicated)
- [SetTickGroup](ue_ue.StaticMeshSimulationComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.StaticMeshSimulationComponent.md#settickablewhenpaused)
- [ToggleActive](ue_ue.StaticMeshSimulationComponent.md#toggleactive)
- [Find](ue_ue.StaticMeshSimulationComponent.md#find)
- [Load](ue_ue.StaticMeshSimulationComponent.md#load)
- [StaticClass](ue_ue.StaticMeshSimulationComponent.md#staticclass)

## Constructors

### constructor

• **new StaticMeshSimulationComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[constructor](ue_ue.ActorComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:62136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62136)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[AssetUserData](ue_ue.ActorComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### ChaosSolverActor

• **ChaosSolverActor**: [`ChaosSolverActor`](ue_ue.ChaosSolverActor.md)

#### Defined in

[ue/ue.d.ts:62150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62150)

___

### CollisionType

• **CollisionType**: [`ECollisionTypeEnum`](../enums/ue_ue.ECollisionTypeEnum.md)

#### Defined in

[ue/ue.d.ts:62141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62141)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ComponentTags](ue_ue.ActorComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[CreationMethod](ue_ue.ActorComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### DamageThreshold

• **DamageThreshold**: `number`

#### Defined in

[ue/ue.d.ts:62148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62148)

___

### ImplicitType

• **ImplicitType**: [`EImplicitTypeEnum`](../enums/ue_ue.EImplicitTypeEnum.md)

#### Defined in

[ue/ue.d.ts:62142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62142)

___

### InitialAngularVelocity

• **InitialAngularVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:62147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62147)

___

### InitialLinearVelocity

• **InitialLinearVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:62146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62146)

___

### InitialVelocityType

• **InitialVelocityType**: [`EInitialVelocityTypeEnum`](../enums/ue_ue.EInitialVelocityTypeEnum.md)

#### Defined in

[ue/ue.d.ts:62145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62145)

___

### Mass

• **Mass**: `number`

#### Defined in

[ue/ue.d.ts:62140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62140)

___

### MaxLevelSetResolution

• **MaxLevelSetResolution**: `number`

#### Defined in

[ue/ue.d.ts:62144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62144)

___

### MinLevelSetResolution

• **MinLevelSetResolution**: `number`

#### Defined in

[ue/ue.d.ts:62143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62143)

___

### ObjectType

• **ObjectType**: [`EObjectStateTypeEnum`](../enums/ue_ue.EObjectStateTypeEnum.md)

#### Defined in

[ue/ue.d.ts:62139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62139)

___

### OnChaosPhysicsCollision

• **OnChaosPhysicsCollision**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`CollisionInfo`: [`ChaosPhysicsCollisionInfo`](ue_ue.ChaosPhysicsCollisionInfo.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:62151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62151)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[OnComponentActivated](ue_ue.ActorComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[OnComponentDeactivated](ue_ue.ActorComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### PhysicalMaterial

• **PhysicalMaterial**: [`ChaosPhysicalMaterial`](ue_ue.ChaosPhysicalMaterial.md)

#### Defined in

[ue/ue.d.ts:62149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62149)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[PrimaryComponentTick](ue_ue.ActorComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### SimulatedComponents

• **SimulatedComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Defined in

[ue/ue.d.ts:62152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62152)

___

### Simulating

• **Simulating**: `boolean`

#### Defined in

[ue/ue.d.ts:62137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62137)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[UCSModifiedProperties](ue_ue.ActorComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[__tid_ActorComponent__](ue_ue.ActorComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[__tid_Object__](ue_ue.ActorComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_StaticMeshSimulationComponent\_\_

• **\_\_tid\_StaticMeshSimulationComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:62159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62159)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bAutoActivate](ue_ue.ActorComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bCanEverAffectNavigation](ue_ue.ActorComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bCreatedByConstructionScript](ue_ue.ActorComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bEditableWhenInherited](ue_ue.ActorComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bInstanceComponent](ue_ue.ActorComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bIsActive](ue_ue.ActorComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bIsEditorOnly](ue_ue.ActorComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bIsVisualizationComponent](ue_ue.ActorComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bNetAddressable](ue_ue.ActorComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bNotifyCollisions

• **bNotifyCollisions**: `boolean`

#### Defined in

[ue/ue.d.ts:62138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62138)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bReplicates](ue_ue.ActorComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L292)

## Methods

### Activate

▸ **Activate**(`bReset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bReset?` | `boolean` |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[Activate](ue_ue.ActorComponent.md#activate)

#### Defined in

[ue/ue.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L306)

___

### AddTickPrerequisiteActor

▸ **AddTickPrerequisiteActor**(`PrerequisiteActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[AddTickPrerequisiteActor](ue_ue.ActorComponent.md#addtickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:307](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L307)

___

### AddTickPrerequisiteComponent

▸ **AddTickPrerequisiteComponent**(`PrerequisiteComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[AddTickPrerequisiteComponent](ue_ue.ActorComponent.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:308](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L308)

___

### ComponentHasTag

▸ **ComponentHasTag**(`Tag`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tag` | `string` |

#### Returns

`boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ComponentHasTag](ue_ue.ActorComponent.md#componenthastag)

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L309)

___

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

[ActorComponent](ue_ue.ActorComponent.md).[CreateDefaultSubobject](ue_ue.ActorComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[Deactivate](ue_ue.ActorComponent.md#deactivate)

#### Defined in

[ue/ue.d.ts:310](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L310)

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

[ActorComponent](ue_ue.ActorComponent.md).[ExecuteUbergraph](ue_ue.ActorComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### ForceRecreatePhysicsState

▸ **ForceRecreatePhysicsState**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:62153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62153)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetClass](ue_ue.ActorComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetComponentTickInterval](ue_ue.ActorComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetName](ue_ue.ActorComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetOuter](ue_ue.ActorComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetOwner](ue_ue.ActorComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L312)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetWorld](ue_ue.ActorComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[IsActive](ue_ue.ActorComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[IsBeingDestroyed](ue_ue.ActorComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[IsComponentTickEnabled](ue_ue.ActorComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L315)

___

### K2\_DestroyComponent

▸ **K2_DestroyComponent**(`Object`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[K2_DestroyComponent](ue_ue.ActorComponent.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L316)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[OnRep_IsActive](ue_ue.ActorComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L317)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ReceiveBeginPlay](ue_ue.ActorComponent.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:318](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L318)

___

### ReceiveEndPlay

▸ **ReceiveEndPlay**(`EndPlayReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EndPlayReason` | [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md) |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ReceiveEndPlay](ue_ue.ActorComponent.md#receiveendplay)

#### Defined in

[ue/ue.d.ts:319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L319)

___

### ReceivePhysicsCollision

▸ **ReceivePhysicsCollision**(`CollisionInfo`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CollisionInfo` | [`ChaosPhysicsCollisionInfo`](ue_ue.ChaosPhysicsCollisionInfo.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:62154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62154)

___

### ReceiveTick

▸ **ReceiveTick**(`DeltaSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaSeconds` | `number` |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ReceiveTick](ue_ue.ActorComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[RegisterComponent](ue_ue.ActorComponent.md#registercomponent)

#### Defined in

[ue/ue.d.ts:321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L321)

___

### RemoveTickPrerequisiteActor

▸ **RemoveTickPrerequisiteActor**(`PrerequisiteActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[RemoveTickPrerequisiteActor](ue_ue.ActorComponent.md#removetickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:322](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L322)

___

### RemoveTickPrerequisiteComponent

▸ **RemoveTickPrerequisiteComponent**(`PrerequisiteComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.ActorComponent.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L323)

___

### SetActive

▸ **SetActive**(`bNewActive`, `bReset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewActive` | `boolean` |
| `bReset?` | `boolean` |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[SetActive](ue_ue.ActorComponent.md#setactive)

#### Defined in

[ue/ue.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L324)

___

### SetAutoActivate

▸ **SetAutoActivate**(`bNewAutoActivate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewAutoActivate` | `boolean` |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[SetAutoActivate](ue_ue.ActorComponent.md#setautoactivate)

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L325)

___

### SetComponentTickEnabled

▸ **SetComponentTickEnabled**(`bEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnabled` | `boolean` |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[SetComponentTickEnabled](ue_ue.ActorComponent.md#setcomponenttickenabled)

#### Defined in

[ue/ue.d.ts:326](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L326)

___

### SetComponentTickInterval

▸ **SetComponentTickInterval**(`TickInterval`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TickInterval` | `number` |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[SetComponentTickInterval](ue_ue.ActorComponent.md#setcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L327)

___

### SetIsReplicated

▸ **SetIsReplicated**(`ShouldReplicate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ShouldReplicate` | `boolean` |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[SetIsReplicated](ue_ue.ActorComponent.md#setisreplicated)

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L328)

___

### SetTickGroup

▸ **SetTickGroup**(`NewTickGroup`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTickGroup` | [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md) |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[SetTickGroup](ue_ue.ActorComponent.md#settickgroup)

#### Defined in

[ue/ue.d.ts:330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L330)

___

### SetTickableWhenPaused

▸ **SetTickableWhenPaused**(`bTickableWhenPaused`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bTickableWhenPaused` | `boolean` |

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[SetTickableWhenPaused](ue_ue.ActorComponent.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L329)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ToggleActive](ue_ue.ActorComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`StaticMeshSimulationComponent`](ue_ue.StaticMeshSimulationComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`StaticMeshSimulationComponent`](ue_ue.StaticMeshSimulationComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Find](ue_ue.ActorComponent.md#find)

#### Defined in

[ue/ue.d.ts:62156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62156)

___

### Load

▸ `Static` **Load**(`InName`): [`StaticMeshSimulationComponent`](ue_ue.StaticMeshSimulationComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`StaticMeshSimulationComponent`](ue_ue.StaticMeshSimulationComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Load](ue_ue.ActorComponent.md#load)

#### Defined in

[ue/ue.d.ts:62157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62157)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[StaticClass](ue_ue.ActorComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:62155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62155)
