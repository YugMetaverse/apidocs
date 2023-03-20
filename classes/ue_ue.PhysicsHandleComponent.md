[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PhysicsHandleComponent

# Class: PhysicsHandleComponent

[ue/ue](../modules/ue_ue.md).PhysicsHandleComponent

## Hierarchy

- [`ActorComponent`](ue_ue.ActorComponent.md)

  ↳ **`PhysicsHandleComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.PhysicsHandleComponent.md#constructor)

### Properties

- [AngularDamping](ue_ue.PhysicsHandleComponent.md#angulardamping)
- [AngularStiffness](ue_ue.PhysicsHandleComponent.md#angularstiffness)
- [AssetUserData](ue_ue.PhysicsHandleComponent.md#assetuserdata)
- [ComponentTags](ue_ue.PhysicsHandleComponent.md#componenttags)
- [CreationMethod](ue_ue.PhysicsHandleComponent.md#creationmethod)
- [GrabbedComponent](ue_ue.PhysicsHandleComponent.md#grabbedcomponent)
- [InterpolationSpeed](ue_ue.PhysicsHandleComponent.md#interpolationspeed)
- [LinearDamping](ue_ue.PhysicsHandleComponent.md#lineardamping)
- [LinearStiffness](ue_ue.PhysicsHandleComponent.md#linearstiffness)
- [OnComponentActivated](ue_ue.PhysicsHandleComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.PhysicsHandleComponent.md#oncomponentdeactivated)
- [PrimaryComponentTick](ue_ue.PhysicsHandleComponent.md#primarycomponenttick)
- [UCSModifiedProperties](ue_ue.PhysicsHandleComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.PhysicsHandleComponent.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.PhysicsHandleComponent.md#__tid_object__)
- [\_\_tid\_PhysicsHandleComponent\_\_](ue_ue.PhysicsHandleComponent.md#__tid_physicshandlecomponent__)
- [bAutoActivate](ue_ue.PhysicsHandleComponent.md#bautoactivate)
- [bCanEverAffectNavigation](ue_ue.PhysicsHandleComponent.md#bcaneveraffectnavigation)
- [bCreatedByConstructionScript](ue_ue.PhysicsHandleComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.PhysicsHandleComponent.md#beditablewheninherited)
- [bInstanceComponent](ue_ue.PhysicsHandleComponent.md#binstancecomponent)
- [bInterpolateTarget](ue_ue.PhysicsHandleComponent.md#binterpolatetarget)
- [bIsActive](ue_ue.PhysicsHandleComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.PhysicsHandleComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.PhysicsHandleComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.PhysicsHandleComponent.md#bnetaddressable)
- [bReplicates](ue_ue.PhysicsHandleComponent.md#breplicates)
- [bSoftAngularConstraint](ue_ue.PhysicsHandleComponent.md#bsoftangularconstraint)
- [bSoftLinearConstraint](ue_ue.PhysicsHandleComponent.md#bsoftlinearconstraint)

### Methods

- [Activate](ue_ue.PhysicsHandleComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.PhysicsHandleComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PhysicsHandleComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.PhysicsHandleComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.PhysicsHandleComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.PhysicsHandleComponent.md#deactivate)
- [ExecuteUbergraph](ue_ue.PhysicsHandleComponent.md#executeubergraph)
- [GetClass](ue_ue.PhysicsHandleComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.PhysicsHandleComponent.md#getcomponenttickinterval)
- [GetGrabbedComponent](ue_ue.PhysicsHandleComponent.md#getgrabbedcomponent)
- [GetName](ue_ue.PhysicsHandleComponent.md#getname)
- [GetOuter](ue_ue.PhysicsHandleComponent.md#getouter)
- [GetOwner](ue_ue.PhysicsHandleComponent.md#getowner)
- [GetTargetLocationAndRotation](ue_ue.PhysicsHandleComponent.md#gettargetlocationandrotation)
- [GetWorld](ue_ue.PhysicsHandleComponent.md#getworld)
- [GrabComponent](ue_ue.PhysicsHandleComponent.md#grabcomponent)
- [GrabComponentAtLocation](ue_ue.PhysicsHandleComponent.md#grabcomponentatlocation)
- [GrabComponentAtLocationWithRotation](ue_ue.PhysicsHandleComponent.md#grabcomponentatlocationwithrotation)
- [IsActive](ue_ue.PhysicsHandleComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.PhysicsHandleComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.PhysicsHandleComponent.md#iscomponenttickenabled)
- [K2\_DestroyComponent](ue_ue.PhysicsHandleComponent.md#k2_destroycomponent)
- [OnRep\_IsActive](ue_ue.PhysicsHandleComponent.md#onrep_isactive)
- [ReceiveBeginPlay](ue_ue.PhysicsHandleComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.PhysicsHandleComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.PhysicsHandleComponent.md#receivetick)
- [RegisterComponent](ue_ue.PhysicsHandleComponent.md#registercomponent)
- [ReleaseComponent](ue_ue.PhysicsHandleComponent.md#releasecomponent)
- [RemoveTickPrerequisiteActor](ue_ue.PhysicsHandleComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PhysicsHandleComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.PhysicsHandleComponent.md#setactive)
- [SetAngularDamping](ue_ue.PhysicsHandleComponent.md#setangulardamping)
- [SetAngularStiffness](ue_ue.PhysicsHandleComponent.md#setangularstiffness)
- [SetAutoActivate](ue_ue.PhysicsHandleComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.PhysicsHandleComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.PhysicsHandleComponent.md#setcomponenttickinterval)
- [SetInterpolationSpeed](ue_ue.PhysicsHandleComponent.md#setinterpolationspeed)
- [SetIsReplicated](ue_ue.PhysicsHandleComponent.md#setisreplicated)
- [SetLinearDamping](ue_ue.PhysicsHandleComponent.md#setlineardamping)
- [SetLinearStiffness](ue_ue.PhysicsHandleComponent.md#setlinearstiffness)
- [SetTargetLocation](ue_ue.PhysicsHandleComponent.md#settargetlocation)
- [SetTargetLocationAndRotation](ue_ue.PhysicsHandleComponent.md#settargetlocationandrotation)
- [SetTargetRotation](ue_ue.PhysicsHandleComponent.md#settargetrotation)
- [SetTickGroup](ue_ue.PhysicsHandleComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PhysicsHandleComponent.md#settickablewhenpaused)
- [ToggleActive](ue_ue.PhysicsHandleComponent.md#toggleactive)
- [Find](ue_ue.PhysicsHandleComponent.md#find)
- [Load](ue_ue.PhysicsHandleComponent.md#load)
- [StaticClass](ue_ue.PhysicsHandleComponent.md#staticclass)

## Constructors

### constructor

• **new PhysicsHandleComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[constructor](ue_ue.ActorComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:57522](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57522)

## Properties

### AngularDamping

• **AngularDamping**: `number`

#### Defined in

[ue/ue.d.ts:57529](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57529)

___

### AngularStiffness

• **AngularStiffness**: `number`

#### Defined in

[ue/ue.d.ts:57530](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57530)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[AssetUserData](ue_ue.ActorComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ComponentTags](ue_ue.ActorComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[CreationMethod](ue_ue.ActorComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L302)

___

### GrabbedComponent

• **GrabbedComponent**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:57523](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57523)

___

### InterpolationSpeed

• **InterpolationSpeed**: `number`

#### Defined in

[ue/ue.d.ts:57531](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57531)

___

### LinearDamping

• **LinearDamping**: `number`

#### Defined in

[ue/ue.d.ts:57527](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57527)

___

### LinearStiffness

• **LinearStiffness**: `number`

#### Defined in

[ue/ue.d.ts:57528](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57528)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[OnComponentActivated](ue_ue.ActorComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[OnComponentDeactivated](ue_ue.ActorComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L304)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[PrimaryComponentTick](ue_ue.ActorComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[UCSModifiedProperties](ue_ue.ActorComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[__tid_ActorComponent__](ue_ue.ActorComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L336)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[__tid_Object__](ue_ue.ActorComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PhysicsHandleComponent\_\_

• **\_\_tid\_PhysicsHandleComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:57550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57550)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bAutoActivate](ue_ue.ActorComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L296)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bCanEverAffectNavigation](ue_ue.ActorComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L299)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bCreatedByConstructionScript](ue_ue.ActorComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bEditableWhenInherited](ue_ue.ActorComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L298)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bInstanceComponent](ue_ue.ActorComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

___

### bInterpolateTarget

• **bInterpolateTarget**: `boolean`

#### Defined in

[ue/ue.d.ts:57526](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57526)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bIsActive](ue_ue.ActorComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bIsEditorOnly](ue_ue.ActorComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bIsVisualizationComponent](ue_ue.ActorComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bNetAddressable](ue_ue.ActorComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[bReplicates](ue_ue.ActorComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L292)

___

### bSoftAngularConstraint

• **bSoftAngularConstraint**: `boolean`

#### Defined in

[ue/ue.d.ts:57524](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57524)

___

### bSoftLinearConstraint

• **bSoftLinearConstraint**: `boolean`

#### Defined in

[ue/ue.d.ts:57525](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57525)

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

[ue/ue.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L306)

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

[ue/ue.d.ts:307](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L307)

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

[ue/ue.d.ts:308](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L308)

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

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L309)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[Deactivate](ue_ue.ActorComponent.md#deactivate)

#### Defined in

[ue/ue.d.ts:310](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L310)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetClass](ue_ue.ActorComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetComponentTickInterval](ue_ue.ActorComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L311)

___

### GetGrabbedComponent

▸ **GetGrabbedComponent**(): [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Returns

[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:57532](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57532)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetName](ue_ue.ActorComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetOuter](ue_ue.ActorComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetOwner](ue_ue.ActorComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L312)

___

### GetTargetLocationAndRotation

▸ **GetTargetLocationAndRotation**(`TargetLocation`, `TargetRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `TargetRotation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57533](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57533)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[GetWorld](ue_ue.ActorComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### GrabComponent

▸ **GrabComponent**(`Component`, `InBoneName`, `GrabLocation`, `bConstrainRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `InBoneName` | `string` |
| `GrabLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bConstrainRotation` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57534](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57534)

___

### GrabComponentAtLocation

▸ **GrabComponentAtLocation**(`Component`, `InBoneName`, `GrabLocation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `InBoneName` | `string` |
| `GrabLocation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57535](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57535)

___

### GrabComponentAtLocationWithRotation

▸ **GrabComponentAtLocationWithRotation**(`Component`, `InBoneName`, `Location`, `Rotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Component` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `InBoneName` | `string` |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57536](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57536)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[IsActive](ue_ue.ActorComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[IsBeingDestroyed](ue_ue.ActorComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[IsComponentTickEnabled](ue_ue.ActorComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L315)

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

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L316)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[OnRep_IsActive](ue_ue.ActorComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L317)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ReceiveBeginPlay](ue_ue.ActorComponent.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:318](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L318)

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

[ue/ue.d.ts:319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L319)

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

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[RegisterComponent](ue_ue.ActorComponent.md#registercomponent)

#### Defined in

[ue/ue.d.ts:321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L321)

___

### ReleaseComponent

▸ **ReleaseComponent**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57537](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57537)

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

[ue/ue.d.ts:322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L322)

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

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L323)

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

[ue/ue.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L324)

___

### SetAngularDamping

▸ **SetAngularDamping**(`NewAngularDamping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAngularDamping` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57538](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57538)

___

### SetAngularStiffness

▸ **SetAngularStiffness**(`NewAngularStiffness`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAngularStiffness` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57539](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57539)

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

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L325)

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

[ue/ue.d.ts:326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L326)

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

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L327)

___

### SetInterpolationSpeed

▸ **SetInterpolationSpeed**(`NewInterpolationSpeed`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewInterpolationSpeed` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57540](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57540)

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

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L328)

___

### SetLinearDamping

▸ **SetLinearDamping**(`NewLinearDamping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLinearDamping` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57541](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57541)

___

### SetLinearStiffness

▸ **SetLinearStiffness**(`NewLinearStiffness`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLinearStiffness` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57542](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57542)

___

### SetTargetLocation

▸ **SetTargetLocation**(`NewLocation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57543](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57543)

___

### SetTargetLocationAndRotation

▸ **SetTargetLocationAndRotation**(`NewLocation`, `NewRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57544](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57544)

___

### SetTargetRotation

▸ **SetTargetRotation**(`NewRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:57545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57545)

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

[ue/ue.d.ts:330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L330)

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

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L329)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[ActorComponent](ue_ue.ActorComponent.md).[ToggleActive](ue_ue.ActorComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PhysicsHandleComponent`](ue_ue.PhysicsHandleComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PhysicsHandleComponent`](ue_ue.PhysicsHandleComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Find](ue_ue.ActorComponent.md#find)

#### Defined in

[ue/ue.d.ts:57547](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57547)

___

### Load

▸ `Static` **Load**(`InName`): [`PhysicsHandleComponent`](ue_ue.PhysicsHandleComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PhysicsHandleComponent`](ue_ue.PhysicsHandleComponent.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[Load](ue_ue.ActorComponent.md#load)

#### Defined in

[ue/ue.d.ts:57548](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57548)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ActorComponent](ue_ue.ActorComponent.md).[StaticClass](ue_ue.ActorComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:57546](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L57546)
