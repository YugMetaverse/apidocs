[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ArchVisCharMovementComponent

# Class: ArchVisCharMovementComponent

[ue/ue](../modules/ue_ue.md).ArchVisCharMovementComponent

## Hierarchy

- [`CharacterMovementComponent`](ue_ue.CharacterMovementComponent.md)

  ↳ **`ArchVisCharMovementComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.ArchVisCharMovementComponent.md#constructor)

### Properties

- [Acceleration](ue_ue.ArchVisCharMovementComponent.md#acceleration)
- [AirControl](ue_ue.ArchVisCharMovementComponent.md#aircontrol)
- [AirControlBoostMultiplier](ue_ue.ArchVisCharMovementComponent.md#aircontrolboostmultiplier)
- [AirControlBoostVelocityThreshold](ue_ue.ArchVisCharMovementComponent.md#aircontrolboostvelocitythreshold)
- [AnalogInputModifier](ue_ue.ArchVisCharMovementComponent.md#analoginputmodifier)
- [AnimRootMotionVelocity](ue_ue.ArchVisCharMovementComponent.md#animrootmotionvelocity)
- [AssetUserData](ue_ue.ArchVisCharMovementComponent.md#assetuserdata)
- [AvoidanceConsiderationRadius](ue_ue.ArchVisCharMovementComponent.md#avoidanceconsiderationradius)
- [AvoidanceGroup](ue_ue.ArchVisCharMovementComponent.md#avoidancegroup)
- [AvoidanceUID](ue_ue.ArchVisCharMovementComponent.md#avoidanceuid)
- [AvoidanceWeight](ue_ue.ArchVisCharMovementComponent.md#avoidanceweight)
- [BrakingDecelerationFalling](ue_ue.ArchVisCharMovementComponent.md#brakingdecelerationfalling)
- [BrakingDecelerationFlying](ue_ue.ArchVisCharMovementComponent.md#brakingdecelerationflying)
- [BrakingDecelerationSwimming](ue_ue.ArchVisCharMovementComponent.md#brakingdecelerationswimming)
- [BrakingDecelerationWalking](ue_ue.ArchVisCharMovementComponent.md#brakingdecelerationwalking)
- [BrakingFriction](ue_ue.ArchVisCharMovementComponent.md#brakingfriction)
- [BrakingFrictionFactor](ue_ue.ArchVisCharMovementComponent.md#brakingfrictionfactor)
- [BrakingSubStepTime](ue_ue.ArchVisCharMovementComponent.md#brakingsubsteptime)
- [Buoyancy](ue_ue.ArchVisCharMovementComponent.md#buoyancy)
- [CharacterOwner](ue_ue.ArchVisCharMovementComponent.md#characterowner)
- [ComponentTags](ue_ue.ArchVisCharMovementComponent.md#componenttags)
- [CreationMethod](ue_ue.ArchVisCharMovementComponent.md#creationmethod)
- [CrouchedHalfHeight](ue_ue.ArchVisCharMovementComponent.md#crouchedhalfheight)
- [CrouchedSpeedMultiplier](ue_ue.ArchVisCharMovementComponent.md#crouchedspeedmultiplier)
- [CurrentFloor](ue_ue.ArchVisCharMovementComponent.md#currentfloor)
- [CurrentRootMotion](ue_ue.ArchVisCharMovementComponent.md#currentrootmotion)
- [CustomMovementMode](ue_ue.ArchVisCharMovementComponent.md#custommovementmode)
- [DefaultLandMovementMode](ue_ue.ArchVisCharMovementComponent.md#defaultlandmovementmode)
- [DefaultWaterMovementMode](ue_ue.ArchVisCharMovementComponent.md#defaultwatermovementmode)
- [DeferredUpdatedMoveComponent](ue_ue.ArchVisCharMovementComponent.md#deferredupdatedmovecomponent)
- [FallingLateralFriction](ue_ue.ArchVisCharMovementComponent.md#fallinglateralfriction)
- [FixedPathBrakingDistance](ue_ue.ArchVisCharMovementComponent.md#fixedpathbrakingdistance)
- [GravityScale](ue_ue.ArchVisCharMovementComponent.md#gravityscale)
- [GroundFriction](ue_ue.ArchVisCharMovementComponent.md#groundfriction)
- [GroundMovementMode](ue_ue.ArchVisCharMovementComponent.md#groundmovementmode)
- [GroupsToAvoid](ue_ue.ArchVisCharMovementComponent.md#groupstoavoid)
- [GroupsToIgnore](ue_ue.ArchVisCharMovementComponent.md#groupstoignore)
- [InitialPushForceFactor](ue_ue.ArchVisCharMovementComponent.md#initialpushforcefactor)
- [JumpOffJumpZFactor](ue_ue.ArchVisCharMovementComponent.md#jumpoffjumpzfactor)
- [JumpOutOfWaterPitch](ue_ue.ArchVisCharMovementComponent.md#jumpoutofwaterpitch)
- [JumpZVelocity](ue_ue.ArchVisCharMovementComponent.md#jumpzvelocity)
- [LastUpdateLocation](ue_ue.ArchVisCharMovementComponent.md#lastupdatelocation)
- [LastUpdateRotation](ue_ue.ArchVisCharMovementComponent.md#lastupdaterotation)
- [LastUpdateVelocity](ue_ue.ArchVisCharMovementComponent.md#lastupdatevelocity)
- [LedgeCheckThreshold](ue_ue.ArchVisCharMovementComponent.md#ledgecheckthreshold)
- [ListenServerNetworkSimulatedSmoothLocationTime](ue_ue.ArchVisCharMovementComponent.md#listenservernetworksimulatedsmoothlocationtime)
- [ListenServerNetworkSimulatedSmoothRotationTime](ue_ue.ArchVisCharMovementComponent.md#listenservernetworksimulatedsmoothrotationtime)
- [Mass](ue_ue.ArchVisCharMovementComponent.md#mass)
- [MaxAcceleration](ue_ue.ArchVisCharMovementComponent.md#maxacceleration)
- [MaxCustomMovementSpeed](ue_ue.ArchVisCharMovementComponent.md#maxcustommovementspeed)
- [MaxDepenetrationWithGeometry](ue_ue.ArchVisCharMovementComponent.md#maxdepenetrationwithgeometry)
- [MaxDepenetrationWithGeometryAsProxy](ue_ue.ArchVisCharMovementComponent.md#maxdepenetrationwithgeometryasproxy)
- [MaxDepenetrationWithPawn](ue_ue.ArchVisCharMovementComponent.md#maxdepenetrationwithpawn)
- [MaxDepenetrationWithPawnAsProxy](ue_ue.ArchVisCharMovementComponent.md#maxdepenetrationwithpawnasproxy)
- [MaxFlySpeed](ue_ue.ArchVisCharMovementComponent.md#maxflyspeed)
- [MaxJumpApexAttemptsPerSimulation](ue_ue.ArchVisCharMovementComponent.md#maxjumpapexattemptspersimulation)
- [MaxOutOfWaterStepHeight](ue_ue.ArchVisCharMovementComponent.md#maxoutofwaterstepheight)
- [MaxPitch](ue_ue.ArchVisCharMovementComponent.md#maxpitch)
- [MaxRotationalVelocity](ue_ue.ArchVisCharMovementComponent.md#maxrotationalvelocity)
- [MaxSimulationIterations](ue_ue.ArchVisCharMovementComponent.md#maxsimulationiterations)
- [MaxSimulationTimeStep](ue_ue.ArchVisCharMovementComponent.md#maxsimulationtimestep)
- [MaxStepHeight](ue_ue.ArchVisCharMovementComponent.md#maxstepheight)
- [MaxSwimSpeed](ue_ue.ArchVisCharMovementComponent.md#maxswimspeed)
- [MaxTouchForce](ue_ue.ArchVisCharMovementComponent.md#maxtouchforce)
- [MaxWalkSpeed](ue_ue.ArchVisCharMovementComponent.md#maxwalkspeed)
- [MaxWalkSpeedCrouched](ue_ue.ArchVisCharMovementComponent.md#maxwalkspeedcrouched)
- [MinAnalogWalkSpeed](ue_ue.ArchVisCharMovementComponent.md#minanalogwalkspeed)
- [MinPitch](ue_ue.ArchVisCharMovementComponent.md#minpitch)
- [MinTimeBetweenTimeStampResets](ue_ue.ArchVisCharMovementComponent.md#mintimebetweentimestampresets)
- [MinTouchForce](ue_ue.ArchVisCharMovementComponent.md#mintouchforce)
- [MovementMode](ue_ue.ArchVisCharMovementComponent.md#movementmode)
- [MovementState](ue_ue.ArchVisCharMovementComponent.md#movementstate)
- [NavAgentProps](ue_ue.ArchVisCharMovementComponent.md#navagentprops)
- [NavMeshProjectionHeightScaleDown](ue_ue.ArchVisCharMovementComponent.md#navmeshprojectionheightscaledown)
- [NavMeshProjectionHeightScaleUp](ue_ue.ArchVisCharMovementComponent.md#navmeshprojectionheightscaleup)
- [NavMeshProjectionInterpSpeed](ue_ue.ArchVisCharMovementComponent.md#navmeshprojectioninterpspeed)
- [NavMeshProjectionInterval](ue_ue.ArchVisCharMovementComponent.md#navmeshprojectioninterval)
- [NavMeshProjectionTimer](ue_ue.ArchVisCharMovementComponent.md#navmeshprojectiontimer)
- [NavWalkingFloorDistTolerance](ue_ue.ArchVisCharMovementComponent.md#navwalkingfloordisttolerance)
- [NetProxyShrinkHalfHeight](ue_ue.ArchVisCharMovementComponent.md#netproxyshrinkhalfheight)
- [NetProxyShrinkRadius](ue_ue.ArchVisCharMovementComponent.md#netproxyshrinkradius)
- [NetworkLargeClientCorrectionDistance](ue_ue.ArchVisCharMovementComponent.md#networklargeclientcorrectiondistance)
- [NetworkMaxSmoothUpdateDistance](ue_ue.ArchVisCharMovementComponent.md#networkmaxsmoothupdatedistance)
- [NetworkMinTimeBetweenClientAckGoodMoves](ue_ue.ArchVisCharMovementComponent.md#networkmintimebetweenclientackgoodmoves)
- [NetworkMinTimeBetweenClientAdjustments](ue_ue.ArchVisCharMovementComponent.md#networkmintimebetweenclientadjustments)
- [NetworkMinTimeBetweenClientAdjustmentsLargeCorrection](ue_ue.ArchVisCharMovementComponent.md#networkmintimebetweenclientadjustmentslargecorrection)
- [NetworkNoSmoothUpdateDistance](ue_ue.ArchVisCharMovementComponent.md#networknosmoothupdatedistance)
- [NetworkSimulatedSmoothLocationTime](ue_ue.ArchVisCharMovementComponent.md#networksimulatedsmoothlocationtime)
- [NetworkSimulatedSmoothRotationTime](ue_ue.ArchVisCharMovementComponent.md#networksimulatedsmoothrotationtime)
- [NetworkSmoothingMode](ue_ue.ArchVisCharMovementComponent.md#networksmoothingmode)
- [OnComponentActivated](ue_ue.ArchVisCharMovementComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.ArchVisCharMovementComponent.md#oncomponentdeactivated)
- [OutofWaterZ](ue_ue.ArchVisCharMovementComponent.md#outofwaterz)
- [PathFollowingComp](ue_ue.ArchVisCharMovementComponent.md#pathfollowingcomp)
- [PawnOwner](ue_ue.ArchVisCharMovementComponent.md#pawnowner)
- [PendingForceToApply](ue_ue.ArchVisCharMovementComponent.md#pendingforcetoapply)
- [PendingImpulseToApply](ue_ue.ArchVisCharMovementComponent.md#pendingimpulsetoapply)
- [PendingLaunchVelocity](ue_ue.ArchVisCharMovementComponent.md#pendinglaunchvelocity)
- [PerchAdditionalHeight](ue_ue.ArchVisCharMovementComponent.md#perchadditionalheight)
- [PerchRadiusThreshold](ue_ue.ArchVisCharMovementComponent.md#perchradiusthreshold)
- [PlaneConstraintAxisSetting](ue_ue.ArchVisCharMovementComponent.md#planeconstraintaxissetting)
- [PlaneConstraintNormal](ue_ue.ArchVisCharMovementComponent.md#planeconstraintnormal)
- [PlaneConstraintOrigin](ue_ue.ArchVisCharMovementComponent.md#planeconstraintorigin)
- [PostPhysicsTickFunction](ue_ue.ArchVisCharMovementComponent.md#postphysicstickfunction)
- [PrimaryComponentTick](ue_ue.ArchVisCharMovementComponent.md#primarycomponenttick)
- [PushForceFactor](ue_ue.ArchVisCharMovementComponent.md#pushforcefactor)
- [PushForcePointZOffsetFactor](ue_ue.ArchVisCharMovementComponent.md#pushforcepointzoffsetfactor)
- [RepulsionForce](ue_ue.ArchVisCharMovementComponent.md#repulsionforce)
- [RequestedVelocity](ue_ue.ArchVisCharMovementComponent.md#requestedvelocity)
- [RootMotionParams](ue_ue.ArchVisCharMovementComponent.md#rootmotionparams)
- [RotationRate](ue_ue.ArchVisCharMovementComponent.md#rotationrate)
- [RotationalAcceleration](ue_ue.ArchVisCharMovementComponent.md#rotationalacceleration)
- [RotationalDeceleration](ue_ue.ArchVisCharMovementComponent.md#rotationaldeceleration)
- [ServerLastClientAdjustmentTime](ue_ue.ArchVisCharMovementComponent.md#serverlastclientadjustmenttime)
- [ServerLastClientGoodMoveAckTime](ue_ue.ArchVisCharMovementComponent.md#serverlastclientgoodmoveacktime)
- [ServerLastTransformUpdateTimeStamp](ue_ue.ArchVisCharMovementComponent.md#serverlasttransformupdatetimestamp)
- [StandingDownwardForceScale](ue_ue.ArchVisCharMovementComponent.md#standingdownwardforcescale)
- [TouchForceFactor](ue_ue.ArchVisCharMovementComponent.md#touchforcefactor)
- [UCSModifiedProperties](ue_ue.ArchVisCharMovementComponent.md#ucsmodifiedproperties)
- [UpdatedComponent](ue_ue.ArchVisCharMovementComponent.md#updatedcomponent)
- [UpdatedPrimitive](ue_ue.ArchVisCharMovementComponent.md#updatedprimitive)
- [UpperImpactNormalScale](ue_ue.ArchVisCharMovementComponent.md#upperimpactnormalscale)
- [Velocity](ue_ue.ArchVisCharMovementComponent.md#velocity)
- [WalkableFloorAngle](ue_ue.ArchVisCharMovementComponent.md#walkablefloorangle)
- [WalkableFloorZ](ue_ue.ArchVisCharMovementComponent.md#walkablefloorz)
- [WalkingAcceleration](ue_ue.ArchVisCharMovementComponent.md#walkingacceleration)
- [WalkingFriction](ue_ue.ArchVisCharMovementComponent.md#walkingfriction)
- [WalkingSpeed](ue_ue.ArchVisCharMovementComponent.md#walkingspeed)
- [\_\_tid\_ActorComponent\_\_](ue_ue.ArchVisCharMovementComponent.md#__tid_actorcomponent__)
- [\_\_tid\_ArchVisCharMovementComponent\_\_](ue_ue.ArchVisCharMovementComponent.md#__tid_archvischarmovementcomponent__)
- [\_\_tid\_CharacterMovementComponent\_\_](ue_ue.ArchVisCharMovementComponent.md#__tid_charactermovementcomponent__)
- [\_\_tid\_MovementComponent\_\_](ue_ue.ArchVisCharMovementComponent.md#__tid_movementcomponent__)
- [\_\_tid\_NavMovementComponent\_\_](ue_ue.ArchVisCharMovementComponent.md#__tid_navmovementcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.ArchVisCharMovementComponent.md#__tid_object__)
- [\_\_tid\_PawnMovementComponent\_\_](ue_ue.ArchVisCharMovementComponent.md#__tid_pawnmovementcomponent__)
- [bAllowPhysicsRotationDuringAnimRootMotion](ue_ue.ArchVisCharMovementComponent.md#ballowphysicsrotationduringanimrootmotion)
- [bAlwaysCheckFloor](ue_ue.ArchVisCharMovementComponent.md#balwayscheckfloor)
- [bApplyGravityWhileJumping](ue_ue.ArchVisCharMovementComponent.md#bapplygravitywhilejumping)
- [bAutoActivate](ue_ue.ArchVisCharMovementComponent.md#bautoactivate)
- [bAutoRegisterPhysicsVolumeUpdates](ue_ue.ArchVisCharMovementComponent.md#bautoregisterphysicsvolumeupdates)
- [bAutoRegisterUpdatedComponent](ue_ue.ArchVisCharMovementComponent.md#bautoregisterupdatedcomponent)
- [bAutoUpdateTickRegistration](ue_ue.ArchVisCharMovementComponent.md#bautoupdatetickregistration)
- [bCanEverAffectNavigation](ue_ue.ArchVisCharMovementComponent.md#bcaneveraffectnavigation)
- [bCanWalkOffLedges](ue_ue.ArchVisCharMovementComponent.md#bcanwalkoffledges)
- [bCanWalkOffLedgesWhenCrouching](ue_ue.ArchVisCharMovementComponent.md#bcanwalkoffledgeswhencrouching)
- [bCheatFlying](ue_ue.ArchVisCharMovementComponent.md#bcheatflying)
- [bComponentShouldUpdatePhysicsVolume](ue_ue.ArchVisCharMovementComponent.md#bcomponentshouldupdatephysicsvolume)
- [bConstrainToPlane](ue_ue.ArchVisCharMovementComponent.md#bconstraintoplane)
- [bCreatedByConstructionScript](ue_ue.ArchVisCharMovementComponent.md#bcreatedbyconstructionscript)
- [bCrouchMaintainsBaseLocation](ue_ue.ArchVisCharMovementComponent.md#bcrouchmaintainsbaselocation)
- [bDeferUpdateMoveComponent](ue_ue.ArchVisCharMovementComponent.md#bdeferupdatemovecomponent)
- [bEditableWhenInherited](ue_ue.ArchVisCharMovementComponent.md#beditablewheninherited)
- [bEnablePhysicsInteraction](ue_ue.ArchVisCharMovementComponent.md#benablephysicsinteraction)
- [bEnableScopedMovementUpdates](ue_ue.ArchVisCharMovementComponent.md#benablescopedmovementupdates)
- [bEnableServerDualMoveScopedMovementUpdates](ue_ue.ArchVisCharMovementComponent.md#benableserverdualmovescopedmovementupdates)
- [bFastAttachedMove](ue_ue.ArchVisCharMovementComponent.md#bfastattachedmove)
- [bForceBraking](ue_ue.ArchVisCharMovementComponent.md#bforcebraking)
- [bForceMaxAccel](ue_ue.ArchVisCharMovementComponent.md#bforcemaxaccel)
- [bForceNextFloorCheck](ue_ue.ArchVisCharMovementComponent.md#bforcenextfloorcheck)
- [bHasRequestedVelocity](ue_ue.ArchVisCharMovementComponent.md#bhasrequestedvelocity)
- [bIgnoreBaseRotation](ue_ue.ArchVisCharMovementComponent.md#bignorebaserotation)
- [bIgnoreClientMovementErrorChecksAndCorrection](ue_ue.ArchVisCharMovementComponent.md#bignoreclientmovementerrorchecksandcorrection)
- [bImpartBaseAngularVelocity](ue_ue.ArchVisCharMovementComponent.md#bimpartbaseangularvelocity)
- [bImpartBaseVelocityX](ue_ue.ArchVisCharMovementComponent.md#bimpartbasevelocityx)
- [bImpartBaseVelocityY](ue_ue.ArchVisCharMovementComponent.md#bimpartbasevelocityy)
- [bImpartBaseVelocityZ](ue_ue.ArchVisCharMovementComponent.md#bimpartbasevelocityz)
- [bInstanceComponent](ue_ue.ArchVisCharMovementComponent.md#binstancecomponent)
- [bIsActive](ue_ue.ArchVisCharMovementComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.ArchVisCharMovementComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.ArchVisCharMovementComponent.md#bisvisualizationcomponent)
- [bJustTeleported](ue_ue.ArchVisCharMovementComponent.md#bjustteleported)
- [bMaintainHorizontalGroundVelocity](ue_ue.ArchVisCharMovementComponent.md#bmaintainhorizontalgroundvelocity)
- [bMovementInProgress](ue_ue.ArchVisCharMovementComponent.md#bmovementinprogress)
- [bNetAddressable](ue_ue.ArchVisCharMovementComponent.md#bnetaddressable)
- [bNetworkAlwaysReplicateTransformUpdateTimestamp](ue_ue.ArchVisCharMovementComponent.md#bnetworkalwaysreplicatetransformupdatetimestamp)
- [bNetworkMovementModeChanged](ue_ue.ArchVisCharMovementComponent.md#bnetworkmovementmodechanged)
- [bNetworkSkipProxyPredictionOnNetUpdate](ue_ue.ArchVisCharMovementComponent.md#bnetworkskipproxypredictiononnetupdate)
- [bNetworkUpdateReceived](ue_ue.ArchVisCharMovementComponent.md#bnetworkupdatereceived)
- [bNotifyApex](ue_ue.ArchVisCharMovementComponent.md#bnotifyapex)
- [bOrientRotationToMovement](ue_ue.ArchVisCharMovementComponent.md#borientrotationtomovement)
- [bPerformingJumpOff](ue_ue.ArchVisCharMovementComponent.md#bperformingjumpoff)
- [bProjectNavMeshOnBothWorldChannels](ue_ue.ArchVisCharMovementComponent.md#bprojectnavmeshonbothworldchannels)
- [bProjectNavMeshWalking](ue_ue.ArchVisCharMovementComponent.md#bprojectnavmeshwalking)
- [bPushForceScaledToMass](ue_ue.ArchVisCharMovementComponent.md#bpushforcescaledtomass)
- [bPushForceUsingZOffset](ue_ue.ArchVisCharMovementComponent.md#bpushforceusingzoffset)
- [bReplicates](ue_ue.ArchVisCharMovementComponent.md#breplicates)
- [bRequestedMoveUseAcceleration](ue_ue.ArchVisCharMovementComponent.md#brequestedmoveuseacceleration)
- [bRequestedMoveWithMaxSpeed](ue_ue.ArchVisCharMovementComponent.md#brequestedmovewithmaxspeed)
- [bRunPhysicsWithNoController](ue_ue.ArchVisCharMovementComponent.md#brunphysicswithnocontroller)
- [bScalePushForceToVelocity](ue_ue.ArchVisCharMovementComponent.md#bscalepushforcetovelocity)
- [bServerAcceptClientAuthoritativePosition](ue_ue.ArchVisCharMovementComponent.md#bserveracceptclientauthoritativeposition)
- [bShrinkProxyCapsule](ue_ue.ArchVisCharMovementComponent.md#bshrinkproxycapsule)
- [bSnapToPlaneAtStart](ue_ue.ArchVisCharMovementComponent.md#bsnaptoplaneatstart)
- [bSweepWhileNavWalking](ue_ue.ArchVisCharMovementComponent.md#bsweepwhilenavwalking)
- [bTickBeforeOwner](ue_ue.ArchVisCharMovementComponent.md#btickbeforeowner)
- [bTouchForceScaledToMass](ue_ue.ArchVisCharMovementComponent.md#btouchforcescaledtomass)
- [bUpdateNavAgentWithOwnersCollision](ue_ue.ArchVisCharMovementComponent.md#bupdatenavagentwithownerscollision)
- [bUpdateOnlyIfRendered](ue_ue.ArchVisCharMovementComponent.md#bupdateonlyifrendered)
- [bUseAccelerationForPaths](ue_ue.ArchVisCharMovementComponent.md#buseaccelerationforpaths)
- [bUseControllerDesiredRotation](ue_ue.ArchVisCharMovementComponent.md#busecontrollerdesiredrotation)
- [bUseFixedBrakingDistanceForPaths](ue_ue.ArchVisCharMovementComponent.md#busefixedbrakingdistanceforpaths)
- [bUseFlatBaseForFloorChecks](ue_ue.ArchVisCharMovementComponent.md#buseflatbaseforfloorchecks)
- [bUseRVOAvoidance](ue_ue.ArchVisCharMovementComponent.md#buservoavoidance)
- [bUseSeparateBrakingFriction](ue_ue.ArchVisCharMovementComponent.md#buseseparatebrakingfriction)
- [bWantsToCrouch](ue_ue.ArchVisCharMovementComponent.md#bwantstocrouch)
- [bWantsToLeaveNavWalking](ue_ue.ArchVisCharMovementComponent.md#bwantstoleavenavwalking)
- [bWasAvoidanceUpdated](ue_ue.ArchVisCharMovementComponent.md#bwasavoidanceupdated)
- [bWasSimulatingRootMotion](ue_ue.ArchVisCharMovementComponent.md#bwassimulatingrootmotion)

### Methods

- [Activate](ue_ue.ArchVisCharMovementComponent.md#activate)
- [AddForce](ue_ue.ArchVisCharMovementComponent.md#addforce)
- [AddImpulse](ue_ue.ArchVisCharMovementComponent.md#addimpulse)
- [AddInputVector](ue_ue.ArchVisCharMovementComponent.md#addinputvector)
- [AddTickPrerequisiteActor](ue_ue.ArchVisCharMovementComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.ArchVisCharMovementComponent.md#addtickprerequisitecomponent)
- [CalcVelocity](ue_ue.ArchVisCharMovementComponent.md#calcvelocity)
- [CapsuleTouched](ue_ue.ArchVisCharMovementComponent.md#capsuletouched)
- [ClearAccumulatedForces](ue_ue.ArchVisCharMovementComponent.md#clearaccumulatedforces)
- [ComponentHasTag](ue_ue.ArchVisCharMovementComponent.md#componenthastag)
- [ConstrainDirectionToPlane](ue_ue.ArchVisCharMovementComponent.md#constraindirectiontoplane)
- [ConstrainLocationToPlane](ue_ue.ArchVisCharMovementComponent.md#constrainlocationtoplane)
- [ConstrainNormalToPlane](ue_ue.ArchVisCharMovementComponent.md#constrainnormaltoplane)
- [ConsumeInputVector](ue_ue.ArchVisCharMovementComponent.md#consumeinputvector)
- [CreateDefaultSubobject](ue_ue.ArchVisCharMovementComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.ArchVisCharMovementComponent.md#deactivate)
- [DisableMovement](ue_ue.ArchVisCharMovementComponent.md#disablemovement)
- [ExecuteUbergraph](ue_ue.ArchVisCharMovementComponent.md#executeubergraph)
- [GetAnalogInputModifier](ue_ue.ArchVisCharMovementComponent.md#getanaloginputmodifier)
- [GetCharacterOwner](ue_ue.ArchVisCharMovementComponent.md#getcharacterowner)
- [GetClass](ue_ue.ArchVisCharMovementComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.ArchVisCharMovementComponent.md#getcomponenttickinterval)
- [GetCurrentAcceleration](ue_ue.ArchVisCharMovementComponent.md#getcurrentacceleration)
- [GetGravityZ](ue_ue.ArchVisCharMovementComponent.md#getgravityz)
- [GetImpartedMovementBaseVelocity](ue_ue.ArchVisCharMovementComponent.md#getimpartedmovementbasevelocity)
- [GetLastInputVector](ue_ue.ArchVisCharMovementComponent.md#getlastinputvector)
- [GetLastUpdateLocation](ue_ue.ArchVisCharMovementComponent.md#getlastupdatelocation)
- [GetLastUpdateRotation](ue_ue.ArchVisCharMovementComponent.md#getlastupdaterotation)
- [GetLastUpdateVelocity](ue_ue.ArchVisCharMovementComponent.md#getlastupdatevelocity)
- [GetMaxAcceleration](ue_ue.ArchVisCharMovementComponent.md#getmaxacceleration)
- [GetMaxBrakingDeceleration](ue_ue.ArchVisCharMovementComponent.md#getmaxbrakingdeceleration)
- [GetMaxJumpHeight](ue_ue.ArchVisCharMovementComponent.md#getmaxjumpheight)
- [GetMaxJumpHeightWithJumpTime](ue_ue.ArchVisCharMovementComponent.md#getmaxjumpheightwithjumptime)
- [GetMaxSpeed](ue_ue.ArchVisCharMovementComponent.md#getmaxspeed)
- [GetMinAnalogSpeed](ue_ue.ArchVisCharMovementComponent.md#getminanalogspeed)
- [GetMovementBase](ue_ue.ArchVisCharMovementComponent.md#getmovementbase)
- [GetName](ue_ue.ArchVisCharMovementComponent.md#getname)
- [GetOuter](ue_ue.ArchVisCharMovementComponent.md#getouter)
- [GetOwner](ue_ue.ArchVisCharMovementComponent.md#getowner)
- [GetPawnOwner](ue_ue.ArchVisCharMovementComponent.md#getpawnowner)
- [GetPendingInputVector](ue_ue.ArchVisCharMovementComponent.md#getpendinginputvector)
- [GetPerchRadiusThreshold](ue_ue.ArchVisCharMovementComponent.md#getperchradiusthreshold)
- [GetPhysicsVolume](ue_ue.ArchVisCharMovementComponent.md#getphysicsvolume)
- [GetPlaneConstraintAxisSetting](ue_ue.ArchVisCharMovementComponent.md#getplaneconstraintaxissetting)
- [GetPlaneConstraintNormal](ue_ue.ArchVisCharMovementComponent.md#getplaneconstraintnormal)
- [GetPlaneConstraintOrigin](ue_ue.ArchVisCharMovementComponent.md#getplaneconstraintorigin)
- [GetValidPerchRadius](ue_ue.ArchVisCharMovementComponent.md#getvalidperchradius)
- [GetWorld](ue_ue.ArchVisCharMovementComponent.md#getworld)
- [IsActive](ue_ue.ArchVisCharMovementComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.ArchVisCharMovementComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.ArchVisCharMovementComponent.md#iscomponenttickenabled)
- [IsCrouching](ue_ue.ArchVisCharMovementComponent.md#iscrouching)
- [IsExceedingMaxSpeed](ue_ue.ArchVisCharMovementComponent.md#isexceedingmaxspeed)
- [IsFalling](ue_ue.ArchVisCharMovementComponent.md#isfalling)
- [IsFlying](ue_ue.ArchVisCharMovementComponent.md#isflying)
- [IsMoveInputIgnored](ue_ue.ArchVisCharMovementComponent.md#ismoveinputignored)
- [IsMovingOnGround](ue_ue.ArchVisCharMovementComponent.md#ismovingonground)
- [IsSwimming](ue_ue.ArchVisCharMovementComponent.md#isswimming)
- [IsWalkable](ue_ue.ArchVisCharMovementComponent.md#iswalkable)
- [IsWalking](ue_ue.ArchVisCharMovementComponent.md#iswalking)
- [K2\_ComputeFloorDist](ue_ue.ArchVisCharMovementComponent.md#k2_computefloordist)
- [K2\_DestroyComponent](ue_ue.ArchVisCharMovementComponent.md#k2_destroycomponent)
- [K2\_FindFloor](ue_ue.ArchVisCharMovementComponent.md#k2_findfloor)
- [K2\_GetInputVector](ue_ue.ArchVisCharMovementComponent.md#k2_getinputvector)
- [K2\_GetMaxSpeedModifier](ue_ue.ArchVisCharMovementComponent.md#k2_getmaxspeedmodifier)
- [K2\_GetModifiedMaxAcceleration](ue_ue.ArchVisCharMovementComponent.md#k2_getmodifiedmaxacceleration)
- [K2\_GetModifiedMaxSpeed](ue_ue.ArchVisCharMovementComponent.md#k2_getmodifiedmaxspeed)
- [K2\_GetWalkableFloorAngle](ue_ue.ArchVisCharMovementComponent.md#k2_getwalkablefloorangle)
- [K2\_GetWalkableFloorZ](ue_ue.ArchVisCharMovementComponent.md#k2_getwalkablefloorz)
- [K2\_MoveUpdatedComponent](ue_ue.ArchVisCharMovementComponent.md#k2_moveupdatedcomponent)
- [OnRep\_IsActive](ue_ue.ArchVisCharMovementComponent.md#onrep_isactive)
- [PhysicsVolumeChanged](ue_ue.ArchVisCharMovementComponent.md#physicsvolumechanged)
- [ReceiveBeginPlay](ue_ue.ArchVisCharMovementComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.ArchVisCharMovementComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.ArchVisCharMovementComponent.md#receivetick)
- [RegisterComponent](ue_ue.ArchVisCharMovementComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.ArchVisCharMovementComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.ArchVisCharMovementComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.ArchVisCharMovementComponent.md#setactive)
- [SetAutoActivate](ue_ue.ArchVisCharMovementComponent.md#setautoactivate)
- [SetAvoidanceEnabled](ue_ue.ArchVisCharMovementComponent.md#setavoidanceenabled)
- [SetAvoidanceGroup](ue_ue.ArchVisCharMovementComponent.md#setavoidancegroup)
- [SetAvoidanceGroupMask](ue_ue.ArchVisCharMovementComponent.md#setavoidancegroupmask)
- [SetComponentTickEnabled](ue_ue.ArchVisCharMovementComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.ArchVisCharMovementComponent.md#setcomponenttickinterval)
- [SetGroupsToAvoid](ue_ue.ArchVisCharMovementComponent.md#setgroupstoavoid)
- [SetGroupsToAvoidMask](ue_ue.ArchVisCharMovementComponent.md#setgroupstoavoidmask)
- [SetGroupsToIgnore](ue_ue.ArchVisCharMovementComponent.md#setgroupstoignore)
- [SetGroupsToIgnoreMask](ue_ue.ArchVisCharMovementComponent.md#setgroupstoignoremask)
- [SetIsReplicated](ue_ue.ArchVisCharMovementComponent.md#setisreplicated)
- [SetMovementMode](ue_ue.ArchVisCharMovementComponent.md#setmovementmode)
- [SetPlaneConstraintAxisSetting](ue_ue.ArchVisCharMovementComponent.md#setplaneconstraintaxissetting)
- [SetPlaneConstraintEnabled](ue_ue.ArchVisCharMovementComponent.md#setplaneconstraintenabled)
- [SetPlaneConstraintFromVectors](ue_ue.ArchVisCharMovementComponent.md#setplaneconstraintfromvectors)
- [SetPlaneConstraintNormal](ue_ue.ArchVisCharMovementComponent.md#setplaneconstraintnormal)
- [SetPlaneConstraintOrigin](ue_ue.ArchVisCharMovementComponent.md#setplaneconstraintorigin)
- [SetTickGroup](ue_ue.ArchVisCharMovementComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.ArchVisCharMovementComponent.md#settickablewhenpaused)
- [SetUpdatedComponent](ue_ue.ArchVisCharMovementComponent.md#setupdatedcomponent)
- [SetWalkableFloorAngle](ue_ue.ArchVisCharMovementComponent.md#setwalkablefloorangle)
- [SetWalkableFloorZ](ue_ue.ArchVisCharMovementComponent.md#setwalkablefloorz)
- [SnapUpdatedComponentToPlane](ue_ue.ArchVisCharMovementComponent.md#snapupdatedcomponenttoplane)
- [StopActiveMovement](ue_ue.ArchVisCharMovementComponent.md#stopactivemovement)
- [StopMovementImmediately](ue_ue.ArchVisCharMovementComponent.md#stopmovementimmediately)
- [StopMovementKeepPathing](ue_ue.ArchVisCharMovementComponent.md#stopmovementkeeppathing)
- [ToggleActive](ue_ue.ArchVisCharMovementComponent.md#toggleactive)
- [Find](ue_ue.ArchVisCharMovementComponent.md#find)
- [Load](ue_ue.ArchVisCharMovementComponent.md#load)
- [StaticClass](ue_ue.ArchVisCharMovementComponent.md#staticclass)

## Constructors

### constructor

• **new ArchVisCharMovementComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[constructor](ue_ue.CharacterMovementComponent.md#constructor)

## Properties

### Acceleration

• **Acceleration**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[Acceleration](ue_ue.CharacterMovementComponent.md#acceleration)

___

### AirControl

• **AirControl**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AirControl](ue_ue.CharacterMovementComponent.md#aircontrol)

___

### AirControlBoostMultiplier

• **AirControlBoostMultiplier**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AirControlBoostMultiplier](ue_ue.CharacterMovementComponent.md#aircontrolboostmultiplier)

___

### AirControlBoostVelocityThreshold

• **AirControlBoostVelocityThreshold**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AirControlBoostVelocityThreshold](ue_ue.CharacterMovementComponent.md#aircontrolboostvelocitythreshold)

___

### AnalogInputModifier

• **AnalogInputModifier**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AnalogInputModifier](ue_ue.CharacterMovementComponent.md#analoginputmodifier)

___

### AnimRootMotionVelocity

• **AnimRootMotionVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AnimRootMotionVelocity](ue_ue.CharacterMovementComponent.md#animrootmotionvelocity)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AssetUserData](ue_ue.CharacterMovementComponent.md#assetuserdata)

___

### AvoidanceConsiderationRadius

• **AvoidanceConsiderationRadius**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AvoidanceConsiderationRadius](ue_ue.CharacterMovementComponent.md#avoidanceconsiderationradius)

___

### AvoidanceGroup

• **AvoidanceGroup**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AvoidanceGroup](ue_ue.CharacterMovementComponent.md#avoidancegroup)

___

### AvoidanceUID

• **AvoidanceUID**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AvoidanceUID](ue_ue.CharacterMovementComponent.md#avoidanceuid)

___

### AvoidanceWeight

• **AvoidanceWeight**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AvoidanceWeight](ue_ue.CharacterMovementComponent.md#avoidanceweight)

___

### BrakingDecelerationFalling

• **BrakingDecelerationFalling**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingDecelerationFalling](ue_ue.CharacterMovementComponent.md#brakingdecelerationfalling)

___

### BrakingDecelerationFlying

• **BrakingDecelerationFlying**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingDecelerationFlying](ue_ue.CharacterMovementComponent.md#brakingdecelerationflying)

___

### BrakingDecelerationSwimming

• **BrakingDecelerationSwimming**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingDecelerationSwimming](ue_ue.CharacterMovementComponent.md#brakingdecelerationswimming)

___

### BrakingDecelerationWalking

• **BrakingDecelerationWalking**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingDecelerationWalking](ue_ue.CharacterMovementComponent.md#brakingdecelerationwalking)

___

### BrakingFriction

• **BrakingFriction**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingFriction](ue_ue.CharacterMovementComponent.md#brakingfriction)

___

### BrakingFrictionFactor

• **BrakingFrictionFactor**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingFrictionFactor](ue_ue.CharacterMovementComponent.md#brakingfrictionfactor)

___

### BrakingSubStepTime

• **BrakingSubStepTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingSubStepTime](ue_ue.CharacterMovementComponent.md#brakingsubsteptime)

___

### Buoyancy

• **Buoyancy**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[Buoyancy](ue_ue.CharacterMovementComponent.md#buoyancy)

___

### CharacterOwner

• **CharacterOwner**: [`Character`](ue_ue.Character.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CharacterOwner](ue_ue.CharacterMovementComponent.md#characterowner)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ComponentTags](ue_ue.CharacterMovementComponent.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CreationMethod](ue_ue.CharacterMovementComponent.md#creationmethod)

___

### CrouchedHalfHeight

• **CrouchedHalfHeight**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CrouchedHalfHeight](ue_ue.CharacterMovementComponent.md#crouchedhalfheight)

___

### CrouchedSpeedMultiplier

• **CrouchedSpeedMultiplier**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CrouchedSpeedMultiplier](ue_ue.CharacterMovementComponent.md#crouchedspeedmultiplier)

___

### CurrentFloor

• **CurrentFloor**: [`FindFloorResult`](ue_ue.FindFloorResult.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CurrentFloor](ue_ue.CharacterMovementComponent.md#currentfloor)

___

### CurrentRootMotion

• **CurrentRootMotion**: [`RootMotionSourceGroup`](ue_ue.RootMotionSourceGroup.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CurrentRootMotion](ue_ue.CharacterMovementComponent.md#currentrootmotion)

___

### CustomMovementMode

• **CustomMovementMode**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CustomMovementMode](ue_ue.CharacterMovementComponent.md#custommovementmode)

___

### DefaultLandMovementMode

• **DefaultLandMovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[DefaultLandMovementMode](ue_ue.CharacterMovementComponent.md#defaultlandmovementmode)

___

### DefaultWaterMovementMode

• **DefaultWaterMovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[DefaultWaterMovementMode](ue_ue.CharacterMovementComponent.md#defaultwatermovementmode)

___

### DeferredUpdatedMoveComponent

• **DeferredUpdatedMoveComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[DeferredUpdatedMoveComponent](ue_ue.CharacterMovementComponent.md#deferredupdatedmovecomponent)

___

### FallingLateralFriction

• **FallingLateralFriction**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[FallingLateralFriction](ue_ue.CharacterMovementComponent.md#fallinglateralfriction)

___

### FixedPathBrakingDistance

• **FixedPathBrakingDistance**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[FixedPathBrakingDistance](ue_ue.CharacterMovementComponent.md#fixedpathbrakingdistance)

___

### GravityScale

• **GravityScale**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GravityScale](ue_ue.CharacterMovementComponent.md#gravityscale)

___

### GroundFriction

• **GroundFriction**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GroundFriction](ue_ue.CharacterMovementComponent.md#groundfriction)

___

### GroundMovementMode

• **GroundMovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GroundMovementMode](ue_ue.CharacterMovementComponent.md#groundmovementmode)

___

### GroupsToAvoid

• **GroupsToAvoid**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GroupsToAvoid](ue_ue.CharacterMovementComponent.md#groupstoavoid)

___

### GroupsToIgnore

• **GroupsToIgnore**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GroupsToIgnore](ue_ue.CharacterMovementComponent.md#groupstoignore)

___

### InitialPushForceFactor

• **InitialPushForceFactor**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[InitialPushForceFactor](ue_ue.CharacterMovementComponent.md#initialpushforcefactor)

___

### JumpOffJumpZFactor

• **JumpOffJumpZFactor**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[JumpOffJumpZFactor](ue_ue.CharacterMovementComponent.md#jumpoffjumpzfactor)

___

### JumpOutOfWaterPitch

• **JumpOutOfWaterPitch**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[JumpOutOfWaterPitch](ue_ue.CharacterMovementComponent.md#jumpoutofwaterpitch)

___

### JumpZVelocity

• **JumpZVelocity**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[JumpZVelocity](ue_ue.CharacterMovementComponent.md#jumpzvelocity)

___

### LastUpdateLocation

• **LastUpdateLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[LastUpdateLocation](ue_ue.CharacterMovementComponent.md#lastupdatelocation)

___

### LastUpdateRotation

• **LastUpdateRotation**: [`Quat`](ue_ue_s.Quat.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[LastUpdateRotation](ue_ue.CharacterMovementComponent.md#lastupdaterotation)

___

### LastUpdateVelocity

• **LastUpdateVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[LastUpdateVelocity](ue_ue.CharacterMovementComponent.md#lastupdatevelocity)

___

### LedgeCheckThreshold

• **LedgeCheckThreshold**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[LedgeCheckThreshold](ue_ue.CharacterMovementComponent.md#ledgecheckthreshold)

___

### ListenServerNetworkSimulatedSmoothLocationTime

• **ListenServerNetworkSimulatedSmoothLocationTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ListenServerNetworkSimulatedSmoothLocationTime](ue_ue.CharacterMovementComponent.md#listenservernetworksimulatedsmoothlocationtime)

___

### ListenServerNetworkSimulatedSmoothRotationTime

• **ListenServerNetworkSimulatedSmoothRotationTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ListenServerNetworkSimulatedSmoothRotationTime](ue_ue.CharacterMovementComponent.md#listenservernetworksimulatedsmoothrotationtime)

___

### Mass

• **Mass**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[Mass](ue_ue.CharacterMovementComponent.md#mass)

___

### MaxAcceleration

• **MaxAcceleration**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxAcceleration](ue_ue.CharacterMovementComponent.md#maxacceleration)

___

### MaxCustomMovementSpeed

• **MaxCustomMovementSpeed**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxCustomMovementSpeed](ue_ue.CharacterMovementComponent.md#maxcustommovementspeed)

___

### MaxDepenetrationWithGeometry

• **MaxDepenetrationWithGeometry**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxDepenetrationWithGeometry](ue_ue.CharacterMovementComponent.md#maxdepenetrationwithgeometry)

___

### MaxDepenetrationWithGeometryAsProxy

• **MaxDepenetrationWithGeometryAsProxy**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxDepenetrationWithGeometryAsProxy](ue_ue.CharacterMovementComponent.md#maxdepenetrationwithgeometryasproxy)

___

### MaxDepenetrationWithPawn

• **MaxDepenetrationWithPawn**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxDepenetrationWithPawn](ue_ue.CharacterMovementComponent.md#maxdepenetrationwithpawn)

___

### MaxDepenetrationWithPawnAsProxy

• **MaxDepenetrationWithPawnAsProxy**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxDepenetrationWithPawnAsProxy](ue_ue.CharacterMovementComponent.md#maxdepenetrationwithpawnasproxy)

___

### MaxFlySpeed

• **MaxFlySpeed**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxFlySpeed](ue_ue.CharacterMovementComponent.md#maxflyspeed)

___

### MaxJumpApexAttemptsPerSimulation

• **MaxJumpApexAttemptsPerSimulation**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxJumpApexAttemptsPerSimulation](ue_ue.CharacterMovementComponent.md#maxjumpapexattemptspersimulation)

___

### MaxOutOfWaterStepHeight

• **MaxOutOfWaterStepHeight**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxOutOfWaterStepHeight](ue_ue.CharacterMovementComponent.md#maxoutofwaterstepheight)

___

### MaxPitch

• **MaxPitch**: `number`

___

### MaxRotationalVelocity

• **MaxRotationalVelocity**: [`Rotator`](ue_ue_s.Rotator.md)

___

### MaxSimulationIterations

• **MaxSimulationIterations**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxSimulationIterations](ue_ue.CharacterMovementComponent.md#maxsimulationiterations)

___

### MaxSimulationTimeStep

• **MaxSimulationTimeStep**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxSimulationTimeStep](ue_ue.CharacterMovementComponent.md#maxsimulationtimestep)

___

### MaxStepHeight

• **MaxStepHeight**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxStepHeight](ue_ue.CharacterMovementComponent.md#maxstepheight)

___

### MaxSwimSpeed

• **MaxSwimSpeed**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxSwimSpeed](ue_ue.CharacterMovementComponent.md#maxswimspeed)

___

### MaxTouchForce

• **MaxTouchForce**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxTouchForce](ue_ue.CharacterMovementComponent.md#maxtouchforce)

___

### MaxWalkSpeed

• **MaxWalkSpeed**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxWalkSpeed](ue_ue.CharacterMovementComponent.md#maxwalkspeed)

___

### MaxWalkSpeedCrouched

• **MaxWalkSpeedCrouched**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxWalkSpeedCrouched](ue_ue.CharacterMovementComponent.md#maxwalkspeedcrouched)

___

### MinAnalogWalkSpeed

• **MinAnalogWalkSpeed**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MinAnalogWalkSpeed](ue_ue.CharacterMovementComponent.md#minanalogwalkspeed)

___

### MinPitch

• **MinPitch**: `number`

___

### MinTimeBetweenTimeStampResets

• **MinTimeBetweenTimeStampResets**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MinTimeBetweenTimeStampResets](ue_ue.CharacterMovementComponent.md#mintimebetweentimestampresets)

___

### MinTouchForce

• **MinTouchForce**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MinTouchForce](ue_ue.CharacterMovementComponent.md#mintouchforce)

___

### MovementMode

• **MovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MovementMode](ue_ue.CharacterMovementComponent.md#movementmode)

___

### MovementState

• **MovementState**: [`MovementProperties`](ue_ue.MovementProperties.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MovementState](ue_ue.CharacterMovementComponent.md#movementstate)

___

### NavAgentProps

• **NavAgentProps**: [`NavAgentProperties`](ue_ue.NavAgentProperties.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavAgentProps](ue_ue.CharacterMovementComponent.md#navagentprops)

___

### NavMeshProjectionHeightScaleDown

• **NavMeshProjectionHeightScaleDown**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavMeshProjectionHeightScaleDown](ue_ue.CharacterMovementComponent.md#navmeshprojectionheightscaledown)

___

### NavMeshProjectionHeightScaleUp

• **NavMeshProjectionHeightScaleUp**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavMeshProjectionHeightScaleUp](ue_ue.CharacterMovementComponent.md#navmeshprojectionheightscaleup)

___

### NavMeshProjectionInterpSpeed

• **NavMeshProjectionInterpSpeed**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavMeshProjectionInterpSpeed](ue_ue.CharacterMovementComponent.md#navmeshprojectioninterpspeed)

___

### NavMeshProjectionInterval

• **NavMeshProjectionInterval**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavMeshProjectionInterval](ue_ue.CharacterMovementComponent.md#navmeshprojectioninterval)

___

### NavMeshProjectionTimer

• **NavMeshProjectionTimer**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavMeshProjectionTimer](ue_ue.CharacterMovementComponent.md#navmeshprojectiontimer)

___

### NavWalkingFloorDistTolerance

• **NavWalkingFloorDistTolerance**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavWalkingFloorDistTolerance](ue_ue.CharacterMovementComponent.md#navwalkingfloordisttolerance)

___

### NetProxyShrinkHalfHeight

• **NetProxyShrinkHalfHeight**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetProxyShrinkHalfHeight](ue_ue.CharacterMovementComponent.md#netproxyshrinkhalfheight)

___

### NetProxyShrinkRadius

• **NetProxyShrinkRadius**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetProxyShrinkRadius](ue_ue.CharacterMovementComponent.md#netproxyshrinkradius)

___

### NetworkLargeClientCorrectionDistance

• **NetworkLargeClientCorrectionDistance**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkLargeClientCorrectionDistance](ue_ue.CharacterMovementComponent.md#networklargeclientcorrectiondistance)

___

### NetworkMaxSmoothUpdateDistance

• **NetworkMaxSmoothUpdateDistance**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkMaxSmoothUpdateDistance](ue_ue.CharacterMovementComponent.md#networkmaxsmoothupdatedistance)

___

### NetworkMinTimeBetweenClientAckGoodMoves

• **NetworkMinTimeBetweenClientAckGoodMoves**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkMinTimeBetweenClientAckGoodMoves](ue_ue.CharacterMovementComponent.md#networkmintimebetweenclientackgoodmoves)

___

### NetworkMinTimeBetweenClientAdjustments

• **NetworkMinTimeBetweenClientAdjustments**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkMinTimeBetweenClientAdjustments](ue_ue.CharacterMovementComponent.md#networkmintimebetweenclientadjustments)

___

### NetworkMinTimeBetweenClientAdjustmentsLargeCorrection

• **NetworkMinTimeBetweenClientAdjustmentsLargeCorrection**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkMinTimeBetweenClientAdjustmentsLargeCorrection](ue_ue.CharacterMovementComponent.md#networkmintimebetweenclientadjustmentslargecorrection)

___

### NetworkNoSmoothUpdateDistance

• **NetworkNoSmoothUpdateDistance**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkNoSmoothUpdateDistance](ue_ue.CharacterMovementComponent.md#networknosmoothupdatedistance)

___

### NetworkSimulatedSmoothLocationTime

• **NetworkSimulatedSmoothLocationTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkSimulatedSmoothLocationTime](ue_ue.CharacterMovementComponent.md#networksimulatedsmoothlocationtime)

___

### NetworkSimulatedSmoothRotationTime

• **NetworkSimulatedSmoothRotationTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkSimulatedSmoothRotationTime](ue_ue.CharacterMovementComponent.md#networksimulatedsmoothrotationtime)

___

### NetworkSmoothingMode

• **NetworkSmoothingMode**: [`ENetworkSmoothingMode`](../enums/ue_ue.ENetworkSmoothingMode.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkSmoothingMode](ue_ue.CharacterMovementComponent.md#networksmoothingmode)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[OnComponentActivated](ue_ue.CharacterMovementComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[OnComponentDeactivated](ue_ue.CharacterMovementComponent.md#oncomponentdeactivated)

___

### OutofWaterZ

• **OutofWaterZ**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[OutofWaterZ](ue_ue.CharacterMovementComponent.md#outofwaterz)

___

### PathFollowingComp

• **PathFollowingComp**: [`Object`](ue_ue.Object.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PathFollowingComp](ue_ue.CharacterMovementComponent.md#pathfollowingcomp)

___

### PawnOwner

• **PawnOwner**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PawnOwner](ue_ue.CharacterMovementComponent.md#pawnowner)

___

### PendingForceToApply

• **PendingForceToApply**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PendingForceToApply](ue_ue.CharacterMovementComponent.md#pendingforcetoapply)

___

### PendingImpulseToApply

• **PendingImpulseToApply**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PendingImpulseToApply](ue_ue.CharacterMovementComponent.md#pendingimpulsetoapply)

___

### PendingLaunchVelocity

• **PendingLaunchVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PendingLaunchVelocity](ue_ue.CharacterMovementComponent.md#pendinglaunchvelocity)

___

### PerchAdditionalHeight

• **PerchAdditionalHeight**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PerchAdditionalHeight](ue_ue.CharacterMovementComponent.md#perchadditionalheight)

___

### PerchRadiusThreshold

• **PerchRadiusThreshold**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PerchRadiusThreshold](ue_ue.CharacterMovementComponent.md#perchradiusthreshold)

___

### PlaneConstraintAxisSetting

• **PlaneConstraintAxisSetting**: [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PlaneConstraintAxisSetting](ue_ue.CharacterMovementComponent.md#planeconstraintaxissetting)

___

### PlaneConstraintNormal

• **PlaneConstraintNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PlaneConstraintNormal](ue_ue.CharacterMovementComponent.md#planeconstraintnormal)

___

### PlaneConstraintOrigin

• **PlaneConstraintOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PlaneConstraintOrigin](ue_ue.CharacterMovementComponent.md#planeconstraintorigin)

___

### PostPhysicsTickFunction

• **PostPhysicsTickFunction**: [`CharacterMovementComponentPostPhysicsTickFunction`](ue_ue.CharacterMovementComponentPostPhysicsTickFunction.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PostPhysicsTickFunction](ue_ue.CharacterMovementComponent.md#postphysicstickfunction)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PrimaryComponentTick](ue_ue.CharacterMovementComponent.md#primarycomponenttick)

___

### PushForceFactor

• **PushForceFactor**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PushForceFactor](ue_ue.CharacterMovementComponent.md#pushforcefactor)

___

### PushForcePointZOffsetFactor

• **PushForcePointZOffsetFactor**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PushForcePointZOffsetFactor](ue_ue.CharacterMovementComponent.md#pushforcepointzoffsetfactor)

___

### RepulsionForce

• **RepulsionForce**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RepulsionForce](ue_ue.CharacterMovementComponent.md#repulsionforce)

___

### RequestedVelocity

• **RequestedVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RequestedVelocity](ue_ue.CharacterMovementComponent.md#requestedvelocity)

___

### RootMotionParams

• **RootMotionParams**: [`RootMotionMovementParams`](ue_ue.RootMotionMovementParams.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RootMotionParams](ue_ue.CharacterMovementComponent.md#rootmotionparams)

___

### RotationRate

• **RotationRate**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RotationRate](ue_ue.CharacterMovementComponent.md#rotationrate)

___

### RotationalAcceleration

• **RotationalAcceleration**: [`Rotator`](ue_ue_s.Rotator.md)

___

### RotationalDeceleration

• **RotationalDeceleration**: [`Rotator`](ue_ue_s.Rotator.md)

___

### ServerLastClientAdjustmentTime

• **ServerLastClientAdjustmentTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ServerLastClientAdjustmentTime](ue_ue.CharacterMovementComponent.md#serverlastclientadjustmenttime)

___

### ServerLastClientGoodMoveAckTime

• **ServerLastClientGoodMoveAckTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ServerLastClientGoodMoveAckTime](ue_ue.CharacterMovementComponent.md#serverlastclientgoodmoveacktime)

___

### ServerLastTransformUpdateTimeStamp

• **ServerLastTransformUpdateTimeStamp**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ServerLastTransformUpdateTimeStamp](ue_ue.CharacterMovementComponent.md#serverlasttransformupdatetimestamp)

___

### StandingDownwardForceScale

• **StandingDownwardForceScale**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[StandingDownwardForceScale](ue_ue.CharacterMovementComponent.md#standingdownwardforcescale)

___

### TouchForceFactor

• **TouchForceFactor**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[TouchForceFactor](ue_ue.CharacterMovementComponent.md#touchforcefactor)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[UCSModifiedProperties](ue_ue.CharacterMovementComponent.md#ucsmodifiedproperties)

___

### UpdatedComponent

• **UpdatedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[UpdatedComponent](ue_ue.CharacterMovementComponent.md#updatedcomponent)

___

### UpdatedPrimitive

• **UpdatedPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[UpdatedPrimitive](ue_ue.CharacterMovementComponent.md#updatedprimitive)

___

### UpperImpactNormalScale

• **UpperImpactNormalScale**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[UpperImpactNormalScale](ue_ue.CharacterMovementComponent.md#upperimpactnormalscale)

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[Velocity](ue_ue.CharacterMovementComponent.md#velocity)

___

### WalkableFloorAngle

• **WalkableFloorAngle**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[WalkableFloorAngle](ue_ue.CharacterMovementComponent.md#walkablefloorangle)

___

### WalkableFloorZ

• **WalkableFloorZ**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[WalkableFloorZ](ue_ue.CharacterMovementComponent.md#walkablefloorz)

___

### WalkingAcceleration

• **WalkingAcceleration**: `number`

___

### WalkingFriction

• **WalkingFriction**: `number`

___

### WalkingSpeed

• **WalkingSpeed**: `number`

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[__tid_ActorComponent__](ue_ue.CharacterMovementComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_ArchVisCharMovementComponent\_\_

• **\_\_tid\_ArchVisCharMovementComponent\_\_**: `boolean`

___

### \_\_tid\_CharacterMovementComponent\_\_

• **\_\_tid\_CharacterMovementComponent\_\_**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[__tid_CharacterMovementComponent__](ue_ue.CharacterMovementComponent.md#__tid_charactermovementcomponent__)

___

### \_\_tid\_MovementComponent\_\_

• **\_\_tid\_MovementComponent\_\_**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[__tid_MovementComponent__](ue_ue.CharacterMovementComponent.md#__tid_movementcomponent__)

___

### \_\_tid\_NavMovementComponent\_\_

• **\_\_tid\_NavMovementComponent\_\_**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[__tid_NavMovementComponent__](ue_ue.CharacterMovementComponent.md#__tid_navmovementcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[__tid_Object__](ue_ue.CharacterMovementComponent.md#__tid_object__)

___

### \_\_tid\_PawnMovementComponent\_\_

• **\_\_tid\_PawnMovementComponent\_\_**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[__tid_PawnMovementComponent__](ue_ue.CharacterMovementComponent.md#__tid_pawnmovementcomponent__)

___

### bAllowPhysicsRotationDuringAnimRootMotion

• **bAllowPhysicsRotationDuringAnimRootMotion**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bAllowPhysicsRotationDuringAnimRootMotion](ue_ue.CharacterMovementComponent.md#ballowphysicsrotationduringanimrootmotion)

___

### bAlwaysCheckFloor

• **bAlwaysCheckFloor**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bAlwaysCheckFloor](ue_ue.CharacterMovementComponent.md#balwayscheckfloor)

___

### bApplyGravityWhileJumping

• **bApplyGravityWhileJumping**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bApplyGravityWhileJumping](ue_ue.CharacterMovementComponent.md#bapplygravitywhilejumping)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bAutoActivate](ue_ue.CharacterMovementComponent.md#bautoactivate)

___

### bAutoRegisterPhysicsVolumeUpdates

• **bAutoRegisterPhysicsVolumeUpdates**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bAutoRegisterPhysicsVolumeUpdates](ue_ue.CharacterMovementComponent.md#bautoregisterphysicsvolumeupdates)

___

### bAutoRegisterUpdatedComponent

• **bAutoRegisterUpdatedComponent**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bAutoRegisterUpdatedComponent](ue_ue.CharacterMovementComponent.md#bautoregisterupdatedcomponent)

___

### bAutoUpdateTickRegistration

• **bAutoUpdateTickRegistration**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bAutoUpdateTickRegistration](ue_ue.CharacterMovementComponent.md#bautoupdatetickregistration)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bCanEverAffectNavigation](ue_ue.CharacterMovementComponent.md#bcaneveraffectnavigation)

___

### bCanWalkOffLedges

• **bCanWalkOffLedges**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bCanWalkOffLedges](ue_ue.CharacterMovementComponent.md#bcanwalkoffledges)

___

### bCanWalkOffLedgesWhenCrouching

• **bCanWalkOffLedgesWhenCrouching**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bCanWalkOffLedgesWhenCrouching](ue_ue.CharacterMovementComponent.md#bcanwalkoffledgeswhencrouching)

___

### bCheatFlying

• **bCheatFlying**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bCheatFlying](ue_ue.CharacterMovementComponent.md#bcheatflying)

___

### bComponentShouldUpdatePhysicsVolume

• **bComponentShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bComponentShouldUpdatePhysicsVolume](ue_ue.CharacterMovementComponent.md#bcomponentshouldupdatephysicsvolume)

___

### bConstrainToPlane

• **bConstrainToPlane**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bConstrainToPlane](ue_ue.CharacterMovementComponent.md#bconstraintoplane)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bCreatedByConstructionScript](ue_ue.CharacterMovementComponent.md#bcreatedbyconstructionscript)

___

### bCrouchMaintainsBaseLocation

• **bCrouchMaintainsBaseLocation**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bCrouchMaintainsBaseLocation](ue_ue.CharacterMovementComponent.md#bcrouchmaintainsbaselocation)

___

### bDeferUpdateMoveComponent

• **bDeferUpdateMoveComponent**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bDeferUpdateMoveComponent](ue_ue.CharacterMovementComponent.md#bdeferupdatemovecomponent)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bEditableWhenInherited](ue_ue.CharacterMovementComponent.md#beditablewheninherited)

___

### bEnablePhysicsInteraction

• **bEnablePhysicsInteraction**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bEnablePhysicsInteraction](ue_ue.CharacterMovementComponent.md#benablephysicsinteraction)

___

### bEnableScopedMovementUpdates

• **bEnableScopedMovementUpdates**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bEnableScopedMovementUpdates](ue_ue.CharacterMovementComponent.md#benablescopedmovementupdates)

___

### bEnableServerDualMoveScopedMovementUpdates

• **bEnableServerDualMoveScopedMovementUpdates**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bEnableServerDualMoveScopedMovementUpdates](ue_ue.CharacterMovementComponent.md#benableserverdualmovescopedmovementupdates)

___

### bFastAttachedMove

• **bFastAttachedMove**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bFastAttachedMove](ue_ue.CharacterMovementComponent.md#bfastattachedmove)

___

### bForceBraking

• **bForceBraking**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bForceBraking](ue_ue.CharacterMovementComponent.md#bforcebraking)

___

### bForceMaxAccel

• **bForceMaxAccel**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bForceMaxAccel](ue_ue.CharacterMovementComponent.md#bforcemaxaccel)

___

### bForceNextFloorCheck

• **bForceNextFloorCheck**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bForceNextFloorCheck](ue_ue.CharacterMovementComponent.md#bforcenextfloorcheck)

___

### bHasRequestedVelocity

• **bHasRequestedVelocity**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bHasRequestedVelocity](ue_ue.CharacterMovementComponent.md#bhasrequestedvelocity)

___

### bIgnoreBaseRotation

• **bIgnoreBaseRotation**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bIgnoreBaseRotation](ue_ue.CharacterMovementComponent.md#bignorebaserotation)

___

### bIgnoreClientMovementErrorChecksAndCorrection

• **bIgnoreClientMovementErrorChecksAndCorrection**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bIgnoreClientMovementErrorChecksAndCorrection](ue_ue.CharacterMovementComponent.md#bignoreclientmovementerrorchecksandcorrection)

___

### bImpartBaseAngularVelocity

• **bImpartBaseAngularVelocity**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bImpartBaseAngularVelocity](ue_ue.CharacterMovementComponent.md#bimpartbaseangularvelocity)

___

### bImpartBaseVelocityX

• **bImpartBaseVelocityX**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bImpartBaseVelocityX](ue_ue.CharacterMovementComponent.md#bimpartbasevelocityx)

___

### bImpartBaseVelocityY

• **bImpartBaseVelocityY**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bImpartBaseVelocityY](ue_ue.CharacterMovementComponent.md#bimpartbasevelocityy)

___

### bImpartBaseVelocityZ

• **bImpartBaseVelocityZ**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bImpartBaseVelocityZ](ue_ue.CharacterMovementComponent.md#bimpartbasevelocityz)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bInstanceComponent](ue_ue.CharacterMovementComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bIsActive](ue_ue.CharacterMovementComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bIsEditorOnly](ue_ue.CharacterMovementComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bIsVisualizationComponent](ue_ue.CharacterMovementComponent.md#bisvisualizationcomponent)

___

### bJustTeleported

• **bJustTeleported**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bJustTeleported](ue_ue.CharacterMovementComponent.md#bjustteleported)

___

### bMaintainHorizontalGroundVelocity

• **bMaintainHorizontalGroundVelocity**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bMaintainHorizontalGroundVelocity](ue_ue.CharacterMovementComponent.md#bmaintainhorizontalgroundvelocity)

___

### bMovementInProgress

• **bMovementInProgress**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bMovementInProgress](ue_ue.CharacterMovementComponent.md#bmovementinprogress)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bNetAddressable](ue_ue.CharacterMovementComponent.md#bnetaddressable)

___

### bNetworkAlwaysReplicateTransformUpdateTimestamp

• **bNetworkAlwaysReplicateTransformUpdateTimestamp**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bNetworkAlwaysReplicateTransformUpdateTimestamp](ue_ue.CharacterMovementComponent.md#bnetworkalwaysreplicatetransformupdatetimestamp)

___

### bNetworkMovementModeChanged

• **bNetworkMovementModeChanged**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bNetworkMovementModeChanged](ue_ue.CharacterMovementComponent.md#bnetworkmovementmodechanged)

___

### bNetworkSkipProxyPredictionOnNetUpdate

• **bNetworkSkipProxyPredictionOnNetUpdate**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bNetworkSkipProxyPredictionOnNetUpdate](ue_ue.CharacterMovementComponent.md#bnetworkskipproxypredictiononnetupdate)

___

### bNetworkUpdateReceived

• **bNetworkUpdateReceived**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bNetworkUpdateReceived](ue_ue.CharacterMovementComponent.md#bnetworkupdatereceived)

___

### bNotifyApex

• **bNotifyApex**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bNotifyApex](ue_ue.CharacterMovementComponent.md#bnotifyapex)

___

### bOrientRotationToMovement

• **bOrientRotationToMovement**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bOrientRotationToMovement](ue_ue.CharacterMovementComponent.md#borientrotationtomovement)

___

### bPerformingJumpOff

• **bPerformingJumpOff**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bPerformingJumpOff](ue_ue.CharacterMovementComponent.md#bperformingjumpoff)

___

### bProjectNavMeshOnBothWorldChannels

• **bProjectNavMeshOnBothWorldChannels**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bProjectNavMeshOnBothWorldChannels](ue_ue.CharacterMovementComponent.md#bprojectnavmeshonbothworldchannels)

___

### bProjectNavMeshWalking

• **bProjectNavMeshWalking**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bProjectNavMeshWalking](ue_ue.CharacterMovementComponent.md#bprojectnavmeshwalking)

___

### bPushForceScaledToMass

• **bPushForceScaledToMass**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bPushForceScaledToMass](ue_ue.CharacterMovementComponent.md#bpushforcescaledtomass)

___

### bPushForceUsingZOffset

• **bPushForceUsingZOffset**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bPushForceUsingZOffset](ue_ue.CharacterMovementComponent.md#bpushforceusingzoffset)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bReplicates](ue_ue.CharacterMovementComponent.md#breplicates)

___

### bRequestedMoveUseAcceleration

• **bRequestedMoveUseAcceleration**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bRequestedMoveUseAcceleration](ue_ue.CharacterMovementComponent.md#brequestedmoveuseacceleration)

___

### bRequestedMoveWithMaxSpeed

• **bRequestedMoveWithMaxSpeed**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bRequestedMoveWithMaxSpeed](ue_ue.CharacterMovementComponent.md#brequestedmovewithmaxspeed)

___

### bRunPhysicsWithNoController

• **bRunPhysicsWithNoController**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bRunPhysicsWithNoController](ue_ue.CharacterMovementComponent.md#brunphysicswithnocontroller)

___

### bScalePushForceToVelocity

• **bScalePushForceToVelocity**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bScalePushForceToVelocity](ue_ue.CharacterMovementComponent.md#bscalepushforcetovelocity)

___

### bServerAcceptClientAuthoritativePosition

• **bServerAcceptClientAuthoritativePosition**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bServerAcceptClientAuthoritativePosition](ue_ue.CharacterMovementComponent.md#bserveracceptclientauthoritativeposition)

___

### bShrinkProxyCapsule

• **bShrinkProxyCapsule**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bShrinkProxyCapsule](ue_ue.CharacterMovementComponent.md#bshrinkproxycapsule)

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bSnapToPlaneAtStart](ue_ue.CharacterMovementComponent.md#bsnaptoplaneatstart)

___

### bSweepWhileNavWalking

• **bSweepWhileNavWalking**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bSweepWhileNavWalking](ue_ue.CharacterMovementComponent.md#bsweepwhilenavwalking)

___

### bTickBeforeOwner

• **bTickBeforeOwner**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bTickBeforeOwner](ue_ue.CharacterMovementComponent.md#btickbeforeowner)

___

### bTouchForceScaledToMass

• **bTouchForceScaledToMass**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bTouchForceScaledToMass](ue_ue.CharacterMovementComponent.md#btouchforcescaledtomass)

___

### bUpdateNavAgentWithOwnersCollision

• **bUpdateNavAgentWithOwnersCollision**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUpdateNavAgentWithOwnersCollision](ue_ue.CharacterMovementComponent.md#bupdatenavagentwithownerscollision)

___

### bUpdateOnlyIfRendered

• **bUpdateOnlyIfRendered**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUpdateOnlyIfRendered](ue_ue.CharacterMovementComponent.md#bupdateonlyifrendered)

___

### bUseAccelerationForPaths

• **bUseAccelerationForPaths**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUseAccelerationForPaths](ue_ue.CharacterMovementComponent.md#buseaccelerationforpaths)

___

### bUseControllerDesiredRotation

• **bUseControllerDesiredRotation**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUseControllerDesiredRotation](ue_ue.CharacterMovementComponent.md#busecontrollerdesiredrotation)

___

### bUseFixedBrakingDistanceForPaths

• **bUseFixedBrakingDistanceForPaths**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUseFixedBrakingDistanceForPaths](ue_ue.CharacterMovementComponent.md#busefixedbrakingdistanceforpaths)

___

### bUseFlatBaseForFloorChecks

• **bUseFlatBaseForFloorChecks**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUseFlatBaseForFloorChecks](ue_ue.CharacterMovementComponent.md#buseflatbaseforfloorchecks)

___

### bUseRVOAvoidance

• **bUseRVOAvoidance**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUseRVOAvoidance](ue_ue.CharacterMovementComponent.md#buservoavoidance)

___

### bUseSeparateBrakingFriction

• **bUseSeparateBrakingFriction**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUseSeparateBrakingFriction](ue_ue.CharacterMovementComponent.md#buseseparatebrakingfriction)

___

### bWantsToCrouch

• **bWantsToCrouch**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bWantsToCrouch](ue_ue.CharacterMovementComponent.md#bwantstocrouch)

___

### bWantsToLeaveNavWalking

• **bWantsToLeaveNavWalking**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bWantsToLeaveNavWalking](ue_ue.CharacterMovementComponent.md#bwantstoleavenavwalking)

___

### bWasAvoidanceUpdated

• **bWasAvoidanceUpdated**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bWasAvoidanceUpdated](ue_ue.CharacterMovementComponent.md#bwasavoidanceupdated)

___

### bWasSimulatingRootMotion

• **bWasSimulatingRootMotion**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bWasSimulatingRootMotion](ue_ue.CharacterMovementComponent.md#bwassimulatingrootmotion)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[Activate](ue_ue.CharacterMovementComponent.md#activate)

___

### AddForce

▸ **AddForce**(`Force`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Force` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AddForce](ue_ue.CharacterMovementComponent.md#addforce)

___

### AddImpulse

▸ **AddImpulse**(`Impulse`, `bVelocityChange?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Impulse` | [`Vector`](ue_ue_s.Vector.md) |
| `bVelocityChange?` | `boolean` |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AddImpulse](ue_ue.CharacterMovementComponent.md#addimpulse)

___

### AddInputVector

▸ **AddInputVector**(`WorldVector`, `bForce?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldVector` | [`Vector`](ue_ue_s.Vector.md) |
| `bForce?` | `boolean` |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AddInputVector](ue_ue.CharacterMovementComponent.md#addinputvector)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AddTickPrerequisiteActor](ue_ue.CharacterMovementComponent.md#addtickprerequisiteactor)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AddTickPrerequisiteComponent](ue_ue.CharacterMovementComponent.md#addtickprerequisitecomponent)

___

### CalcVelocity

▸ **CalcVelocity**(`DeltaTime`, `Friction`, `bFluid`, `BrakingDeceleration`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTime` | `number` |
| `Friction` | `number` |
| `bFluid` | `boolean` |
| `BrakingDeceleration` | `number` |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CalcVelocity](ue_ue.CharacterMovementComponent.md#calcvelocity)

___

### CapsuleTouched

▸ **CapsuleTouched**(`OverlappedComp`, `Other`, `OtherComp`, `OtherBodyIndex`, `bFromSweep`, `SweepResult`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OverlappedComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `Other` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `OtherComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `OtherBodyIndex` | `number` |
| `bFromSweep` | `boolean` |
| `SweepResult` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CapsuleTouched](ue_ue.CharacterMovementComponent.md#capsuletouched)

___

### ClearAccumulatedForces

▸ **ClearAccumulatedForces**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ClearAccumulatedForces](ue_ue.CharacterMovementComponent.md#clearaccumulatedforces)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ComponentHasTag](ue_ue.CharacterMovementComponent.md#componenthastag)

___

### ConstrainDirectionToPlane

▸ **ConstrainDirectionToPlane**(`Direction`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Direction` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ConstrainDirectionToPlane](ue_ue.CharacterMovementComponent.md#constraindirectiontoplane)

___

### ConstrainLocationToPlane

▸ **ConstrainLocationToPlane**(`Location`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ConstrainLocationToPlane](ue_ue.CharacterMovementComponent.md#constrainlocationtoplane)

___

### ConstrainNormalToPlane

▸ **ConstrainNormalToPlane**(`Normal`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Normal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ConstrainNormalToPlane](ue_ue.CharacterMovementComponent.md#constrainnormaltoplane)

___

### ConsumeInputVector

▸ **ConsumeInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ConsumeInputVector](ue_ue.CharacterMovementComponent.md#consumeinputvector)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CreateDefaultSubobject](ue_ue.CharacterMovementComponent.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[Deactivate](ue_ue.CharacterMovementComponent.md#deactivate)

___

### DisableMovement

▸ **DisableMovement**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[DisableMovement](ue_ue.CharacterMovementComponent.md#disablemovement)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ExecuteUbergraph](ue_ue.CharacterMovementComponent.md#executeubergraph)

___

### GetAnalogInputModifier

▸ **GetAnalogInputModifier**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetAnalogInputModifier](ue_ue.CharacterMovementComponent.md#getanaloginputmodifier)

___

### GetCharacterOwner

▸ **GetCharacterOwner**(): [`Character`](ue_ue.Character.md)

#### Returns

[`Character`](ue_ue.Character.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetCharacterOwner](ue_ue.CharacterMovementComponent.md#getcharacterowner)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetClass](ue_ue.CharacterMovementComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetComponentTickInterval](ue_ue.CharacterMovementComponent.md#getcomponenttickinterval)

___

### GetCurrentAcceleration

▸ **GetCurrentAcceleration**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetCurrentAcceleration](ue_ue.CharacterMovementComponent.md#getcurrentacceleration)

___

### GetGravityZ

▸ **GetGravityZ**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetGravityZ](ue_ue.CharacterMovementComponent.md#getgravityz)

___

### GetImpartedMovementBaseVelocity

▸ **GetImpartedMovementBaseVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetImpartedMovementBaseVelocity](ue_ue.CharacterMovementComponent.md#getimpartedmovementbasevelocity)

___

### GetLastInputVector

▸ **GetLastInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetLastInputVector](ue_ue.CharacterMovementComponent.md#getlastinputvector)

___

### GetLastUpdateLocation

▸ **GetLastUpdateLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetLastUpdateLocation](ue_ue.CharacterMovementComponent.md#getlastupdatelocation)

___

### GetLastUpdateRotation

▸ **GetLastUpdateRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetLastUpdateRotation](ue_ue.CharacterMovementComponent.md#getlastupdaterotation)

___

### GetLastUpdateVelocity

▸ **GetLastUpdateVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetLastUpdateVelocity](ue_ue.CharacterMovementComponent.md#getlastupdatevelocity)

___

### GetMaxAcceleration

▸ **GetMaxAcceleration**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMaxAcceleration](ue_ue.CharacterMovementComponent.md#getmaxacceleration)

___

### GetMaxBrakingDeceleration

▸ **GetMaxBrakingDeceleration**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMaxBrakingDeceleration](ue_ue.CharacterMovementComponent.md#getmaxbrakingdeceleration)

___

### GetMaxJumpHeight

▸ **GetMaxJumpHeight**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMaxJumpHeight](ue_ue.CharacterMovementComponent.md#getmaxjumpheight)

___

### GetMaxJumpHeightWithJumpTime

▸ **GetMaxJumpHeightWithJumpTime**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMaxJumpHeightWithJumpTime](ue_ue.CharacterMovementComponent.md#getmaxjumpheightwithjumptime)

___

### GetMaxSpeed

▸ **GetMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMaxSpeed](ue_ue.CharacterMovementComponent.md#getmaxspeed)

___

### GetMinAnalogSpeed

▸ **GetMinAnalogSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMinAnalogSpeed](ue_ue.CharacterMovementComponent.md#getminanalogspeed)

___

### GetMovementBase

▸ **GetMovementBase**(): [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Returns

[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMovementBase](ue_ue.CharacterMovementComponent.md#getmovementbase)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetName](ue_ue.CharacterMovementComponent.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetOuter](ue_ue.CharacterMovementComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetOwner](ue_ue.CharacterMovementComponent.md#getowner)

___

### GetPawnOwner

▸ **GetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPawnOwner](ue_ue.CharacterMovementComponent.md#getpawnowner)

___

### GetPendingInputVector

▸ **GetPendingInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPendingInputVector](ue_ue.CharacterMovementComponent.md#getpendinginputvector)

___

### GetPerchRadiusThreshold

▸ **GetPerchRadiusThreshold**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPerchRadiusThreshold](ue_ue.CharacterMovementComponent.md#getperchradiusthreshold)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPhysicsVolume](ue_ue.CharacterMovementComponent.md#getphysicsvolume)

___

### GetPlaneConstraintAxisSetting

▸ **GetPlaneConstraintAxisSetting**(): [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Returns

[`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPlaneConstraintAxisSetting](ue_ue.CharacterMovementComponent.md#getplaneconstraintaxissetting)

___

### GetPlaneConstraintNormal

▸ **GetPlaneConstraintNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPlaneConstraintNormal](ue_ue.CharacterMovementComponent.md#getplaneconstraintnormal)

___

### GetPlaneConstraintOrigin

▸ **GetPlaneConstraintOrigin**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPlaneConstraintOrigin](ue_ue.CharacterMovementComponent.md#getplaneconstraintorigin)

___

### GetValidPerchRadius

▸ **GetValidPerchRadius**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetValidPerchRadius](ue_ue.CharacterMovementComponent.md#getvalidperchradius)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetWorld](ue_ue.CharacterMovementComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsActive](ue_ue.CharacterMovementComponent.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsBeingDestroyed](ue_ue.CharacterMovementComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsComponentTickEnabled](ue_ue.CharacterMovementComponent.md#iscomponenttickenabled)

___

### IsCrouching

▸ **IsCrouching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsCrouching](ue_ue.CharacterMovementComponent.md#iscrouching)

___

### IsExceedingMaxSpeed

▸ **IsExceedingMaxSpeed**(`MaxSpeed`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaxSpeed` | `number` |

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsExceedingMaxSpeed](ue_ue.CharacterMovementComponent.md#isexceedingmaxspeed)

___

### IsFalling

▸ **IsFalling**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsFalling](ue_ue.CharacterMovementComponent.md#isfalling)

___

### IsFlying

▸ **IsFlying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsFlying](ue_ue.CharacterMovementComponent.md#isflying)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsMoveInputIgnored](ue_ue.CharacterMovementComponent.md#ismoveinputignored)

___

### IsMovingOnGround

▸ **IsMovingOnGround**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsMovingOnGround](ue_ue.CharacterMovementComponent.md#ismovingonground)

___

### IsSwimming

▸ **IsSwimming**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsSwimming](ue_ue.CharacterMovementComponent.md#isswimming)

___

### IsWalkable

▸ **IsWalkable**(`Hit`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hit` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsWalkable](ue_ue.CharacterMovementComponent.md#iswalkable)

___

### IsWalking

▸ **IsWalking**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsWalking](ue_ue.CharacterMovementComponent.md#iswalking)

___

### K2\_ComputeFloorDist

▸ **K2_ComputeFloorDist**(`CapsuleLocation`, `LineDistance`, `SweepDistance`, `SweepRadius`, `FloorResult`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CapsuleLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `LineDistance` | `number` |
| `SweepDistance` | `number` |
| `SweepRadius` | `number` |
| `FloorResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`FindFloorResult`](ue_ue.FindFloorResult.md)\> |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_ComputeFloorDist](ue_ue.CharacterMovementComponent.md#k2_computefloordist)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_DestroyComponent](ue_ue.CharacterMovementComponent.md#k2_destroycomponent)

___

### K2\_FindFloor

▸ **K2_FindFloor**(`CapsuleLocation`, `FloorResult`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CapsuleLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `FloorResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`FindFloorResult`](ue_ue.FindFloorResult.md)\> |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_FindFloor](ue_ue.CharacterMovementComponent.md#k2_findfloor)

___

### K2\_GetInputVector

▸ **K2_GetInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_GetInputVector](ue_ue.CharacterMovementComponent.md#k2_getinputvector)

___

### K2\_GetMaxSpeedModifier

▸ **K2_GetMaxSpeedModifier**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_GetMaxSpeedModifier](ue_ue.CharacterMovementComponent.md#k2_getmaxspeedmodifier)

___

### K2\_GetModifiedMaxAcceleration

▸ **K2_GetModifiedMaxAcceleration**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_GetModifiedMaxAcceleration](ue_ue.CharacterMovementComponent.md#k2_getmodifiedmaxacceleration)

___

### K2\_GetModifiedMaxSpeed

▸ **K2_GetModifiedMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_GetModifiedMaxSpeed](ue_ue.CharacterMovementComponent.md#k2_getmodifiedmaxspeed)

___

### K2\_GetWalkableFloorAngle

▸ **K2_GetWalkableFloorAngle**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_GetWalkableFloorAngle](ue_ue.CharacterMovementComponent.md#k2_getwalkablefloorangle)

___

### K2\_GetWalkableFloorZ

▸ **K2_GetWalkableFloorZ**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_GetWalkableFloorZ](ue_ue.CharacterMovementComponent.md#k2_getwalkablefloorz)

___

### K2\_MoveUpdatedComponent

▸ **K2_MoveUpdatedComponent**(`Delta`, `NewRotation`, `OutHit`, `bSweep?`, `bTeleport?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Delta` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `OutHit` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bSweep?` | `boolean` |
| `bTeleport?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_MoveUpdatedComponent](ue_ue.CharacterMovementComponent.md#k2_moveupdatedcomponent)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[OnRep_IsActive](ue_ue.CharacterMovementComponent.md#onrep_isactive)

___

### PhysicsVolumeChanged

▸ **PhysicsVolumeChanged**(`NewVolume`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewVolume` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\> |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PhysicsVolumeChanged](ue_ue.CharacterMovementComponent.md#physicsvolumechanged)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ReceiveBeginPlay](ue_ue.CharacterMovementComponent.md#receivebeginplay)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ReceiveEndPlay](ue_ue.CharacterMovementComponent.md#receiveendplay)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ReceiveTick](ue_ue.CharacterMovementComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RegisterComponent](ue_ue.CharacterMovementComponent.md#registercomponent)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RemoveTickPrerequisiteActor](ue_ue.CharacterMovementComponent.md#removetickprerequisiteactor)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.CharacterMovementComponent.md#removetickprerequisitecomponent)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetActive](ue_ue.CharacterMovementComponent.md#setactive)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetAutoActivate](ue_ue.CharacterMovementComponent.md#setautoactivate)

___

### SetAvoidanceEnabled

▸ **SetAvoidanceEnabled**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetAvoidanceEnabled](ue_ue.CharacterMovementComponent.md#setavoidanceenabled)

___

### SetAvoidanceGroup

▸ **SetAvoidanceGroup**(`GroupFlags`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupFlags` | `number` |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetAvoidanceGroup](ue_ue.CharacterMovementComponent.md#setavoidancegroup)

___

### SetAvoidanceGroupMask

▸ **SetAvoidanceGroupMask**(`GroupMask`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupMask` | [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md) |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetAvoidanceGroupMask](ue_ue.CharacterMovementComponent.md#setavoidancegroupmask)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetComponentTickEnabled](ue_ue.CharacterMovementComponent.md#setcomponenttickenabled)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetComponentTickInterval](ue_ue.CharacterMovementComponent.md#setcomponenttickinterval)

___

### SetGroupsToAvoid

▸ **SetGroupsToAvoid**(`GroupFlags`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupFlags` | `number` |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetGroupsToAvoid](ue_ue.CharacterMovementComponent.md#setgroupstoavoid)

___

### SetGroupsToAvoidMask

▸ **SetGroupsToAvoidMask**(`GroupMask`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupMask` | [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md) |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetGroupsToAvoidMask](ue_ue.CharacterMovementComponent.md#setgroupstoavoidmask)

___

### SetGroupsToIgnore

▸ **SetGroupsToIgnore**(`GroupFlags`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupFlags` | `number` |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetGroupsToIgnore](ue_ue.CharacterMovementComponent.md#setgroupstoignore)

___

### SetGroupsToIgnoreMask

▸ **SetGroupsToIgnoreMask**(`GroupMask`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupMask` | [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md) |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetGroupsToIgnoreMask](ue_ue.CharacterMovementComponent.md#setgroupstoignoremask)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetIsReplicated](ue_ue.CharacterMovementComponent.md#setisreplicated)

___

### SetMovementMode

▸ **SetMovementMode**(`NewMovementMode`, `NewCustomMode?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMovementMode` | [`EMovementMode`](../enums/ue_ue.EMovementMode.md) |
| `NewCustomMode?` | `number` |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetMovementMode](ue_ue.CharacterMovementComponent.md#setmovementmode)

___

### SetPlaneConstraintAxisSetting

▸ **SetPlaneConstraintAxisSetting**(`NewAxisSetting`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewAxisSetting` | [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md) |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetPlaneConstraintAxisSetting](ue_ue.CharacterMovementComponent.md#setplaneconstraintaxissetting)

___

### SetPlaneConstraintEnabled

▸ **SetPlaneConstraintEnabled**(`bEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnabled` | `boolean` |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetPlaneConstraintEnabled](ue_ue.CharacterMovementComponent.md#setplaneconstraintenabled)

___

### SetPlaneConstraintFromVectors

▸ **SetPlaneConstraintFromVectors**(`Forward`, `Up`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Forward` | [`Vector`](ue_ue_s.Vector.md) |
| `Up` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetPlaneConstraintFromVectors](ue_ue.CharacterMovementComponent.md#setplaneconstraintfromvectors)

___

### SetPlaneConstraintNormal

▸ **SetPlaneConstraintNormal**(`PlaneNormal`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlaneNormal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetPlaneConstraintNormal](ue_ue.CharacterMovementComponent.md#setplaneconstraintnormal)

___

### SetPlaneConstraintOrigin

▸ **SetPlaneConstraintOrigin**(`PlaneOrigin`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlaneOrigin` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetPlaneConstraintOrigin](ue_ue.CharacterMovementComponent.md#setplaneconstraintorigin)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetTickGroup](ue_ue.CharacterMovementComponent.md#settickgroup)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetTickableWhenPaused](ue_ue.CharacterMovementComponent.md#settickablewhenpaused)

___

### SetUpdatedComponent

▸ **SetUpdatedComponent**(`NewUpdatedComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewUpdatedComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetUpdatedComponent](ue_ue.CharacterMovementComponent.md#setupdatedcomponent)

___

### SetWalkableFloorAngle

▸ **SetWalkableFloorAngle**(`InWalkableFloorAngle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InWalkableFloorAngle` | `number` |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetWalkableFloorAngle](ue_ue.CharacterMovementComponent.md#setwalkablefloorangle)

___

### SetWalkableFloorZ

▸ **SetWalkableFloorZ**(`InWalkableFloorZ`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InWalkableFloorZ` | `number` |

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetWalkableFloorZ](ue_ue.CharacterMovementComponent.md#setwalkablefloorz)

___

### SnapUpdatedComponentToPlane

▸ **SnapUpdatedComponentToPlane**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SnapUpdatedComponentToPlane](ue_ue.CharacterMovementComponent.md#snapupdatedcomponenttoplane)

___

### StopActiveMovement

▸ **StopActiveMovement**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[StopActiveMovement](ue_ue.CharacterMovementComponent.md#stopactivemovement)

___

### StopMovementImmediately

▸ **StopMovementImmediately**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[StopMovementImmediately](ue_ue.CharacterMovementComponent.md#stopmovementimmediately)

___

### StopMovementKeepPathing

▸ **StopMovementKeepPathing**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[StopMovementKeepPathing](ue_ue.CharacterMovementComponent.md#stopmovementkeeppathing)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ToggleActive](ue_ue.CharacterMovementComponent.md#toggleactive)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ArchVisCharMovementComponent`](ue_ue.ArchVisCharMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ArchVisCharMovementComponent`](ue_ue.ArchVisCharMovementComponent.md)

#### Overrides

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[Find](ue_ue.CharacterMovementComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ArchVisCharMovementComponent`](ue_ue.ArchVisCharMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ArchVisCharMovementComponent`](ue_ue.ArchVisCharMovementComponent.md)

#### Overrides

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[Load](ue_ue.CharacterMovementComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[StaticClass](ue_ue.CharacterMovementComponent.md#staticclass)
