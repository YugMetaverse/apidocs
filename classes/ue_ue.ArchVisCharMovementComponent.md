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

#### Defined in

[ue/ue.d.ts:21161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21161)

## Properties

### Acceleration

• **Acceleration**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[Acceleration](ue_ue.CharacterMovementComponent.md#acceleration)

#### Defined in

[ue/ue.d.ts:5702](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5702)

___

### AirControl

• **AirControl**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AirControl](ue_ue.CharacterMovementComponent.md#aircontrol)

#### Defined in

[ue/ue.d.ts:5656](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5656)

___

### AirControlBoostMultiplier

• **AirControlBoostMultiplier**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AirControlBoostMultiplier](ue_ue.CharacterMovementComponent.md#aircontrolboostmultiplier)

#### Defined in

[ue/ue.d.ts:5657](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5657)

___

### AirControlBoostVelocityThreshold

• **AirControlBoostVelocityThreshold**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AirControlBoostVelocityThreshold](ue_ue.CharacterMovementComponent.md#aircontrolboostvelocitythreshold)

#### Defined in

[ue/ue.d.ts:5658](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5658)

___

### AnalogInputModifier

• **AnalogInputModifier**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AnalogInputModifier](ue_ue.CharacterMovementComponent.md#analoginputmodifier)

#### Defined in

[ue/ue.d.ts:5711](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5711)

___

### AnimRootMotionVelocity

• **AnimRootMotionVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AnimRootMotionVelocity](ue_ue.CharacterMovementComponent.md#animrootmotionvelocity)

#### Defined in

[ue/ue.d.ts:5784](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5784)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AssetUserData](ue_ue.CharacterMovementComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### AvoidanceConsiderationRadius

• **AvoidanceConsiderationRadius**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AvoidanceConsiderationRadius](ue_ue.CharacterMovementComponent.md#avoidanceconsiderationradius)

#### Defined in

[ue/ue.d.ts:5766](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5766)

___

### AvoidanceGroup

• **AvoidanceGroup**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AvoidanceGroup](ue_ue.CharacterMovementComponent.md#avoidancegroup)

#### Defined in

[ue/ue.d.ts:5769](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5769)

___

### AvoidanceUID

• **AvoidanceUID**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AvoidanceUID](ue_ue.CharacterMovementComponent.md#avoidanceuid)

#### Defined in

[ue/ue.d.ts:5768](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5768)

___

### AvoidanceWeight

• **AvoidanceWeight**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AvoidanceWeight](ue_ue.CharacterMovementComponent.md#avoidanceweight)

#### Defined in

[ue/ue.d.ts:5772](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5772)

___

### BrakingDecelerationFalling

• **BrakingDecelerationFalling**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingDecelerationFalling](ue_ue.CharacterMovementComponent.md#brakingdecelerationfalling)

#### Defined in

[ue/ue.d.ts:5653](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5653)

___

### BrakingDecelerationFlying

• **BrakingDecelerationFlying**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingDecelerationFlying](ue_ue.CharacterMovementComponent.md#brakingdecelerationflying)

#### Defined in

[ue/ue.d.ts:5655](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5655)

___

### BrakingDecelerationSwimming

• **BrakingDecelerationSwimming**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingDecelerationSwimming](ue_ue.CharacterMovementComponent.md#brakingdecelerationswimming)

#### Defined in

[ue/ue.d.ts:5654](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5654)

___

### BrakingDecelerationWalking

• **BrakingDecelerationWalking**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingDecelerationWalking](ue_ue.CharacterMovementComponent.md#brakingdecelerationwalking)

#### Defined in

[ue/ue.d.ts:5652](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5652)

___

### BrakingFriction

• **BrakingFriction**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingFriction](ue_ue.CharacterMovementComponent.md#brakingfriction)

#### Defined in

[ue/ue.d.ts:5650](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5650)

___

### BrakingFrictionFactor

• **BrakingFrictionFactor**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingFrictionFactor](ue_ue.CharacterMovementComponent.md#brakingfrictionfactor)

#### Defined in

[ue/ue.d.ts:5649](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5649)

___

### BrakingSubStepTime

• **BrakingSubStepTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[BrakingSubStepTime](ue_ue.CharacterMovementComponent.md#brakingsubsteptime)

#### Defined in

[ue/ue.d.ts:5651](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5651)

___

### Buoyancy

• **Buoyancy**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[Buoyancy](ue_ue.CharacterMovementComponent.md#buoyancy)

#### Defined in

[ue/ue.d.ts:5661](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5661)

___

### CharacterOwner

• **CharacterOwner**: [`Character`](ue_ue.Character.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CharacterOwner](ue_ue.CharacterMovementComponent.md#characterowner)

#### Defined in

[ue/ue.d.ts:5631](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5631)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ComponentTags](ue_ue.CharacterMovementComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CreationMethod](ue_ue.CharacterMovementComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### CrouchedHalfHeight

• **CrouchedHalfHeight**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CrouchedHalfHeight](ue_ue.CharacterMovementComponent.md#crouchedhalfheight)

#### Defined in

[ue/ue.d.ts:5660](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5660)

___

### CrouchedSpeedMultiplier

• **CrouchedSpeedMultiplier**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CrouchedSpeedMultiplier](ue_ue.CharacterMovementComponent.md#crouchedspeedmultiplier)

#### Defined in

[ue/ue.d.ts:5700](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5700)

___

### CurrentFloor

• **CurrentFloor**: [`FindFloorResult`](ue_ue.FindFloorResult.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CurrentFloor](ue_ue.CharacterMovementComponent.md#currentfloor)

#### Defined in

[ue/ue.d.ts:5733](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5733)

___

### CurrentRootMotion

• **CurrentRootMotion**: [`RootMotionSourceGroup`](ue_ue.RootMotionSourceGroup.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CurrentRootMotion](ue_ue.CharacterMovementComponent.md#currentrootmotion)

#### Defined in

[ue/ue.d.ts:5782](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5782)

___

### CustomMovementMode

• **CustomMovementMode**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[CustomMovementMode](ue_ue.CharacterMovementComponent.md#custommovementmode)

#### Defined in

[ue/ue.d.ts:5639](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5639)

___

### DefaultLandMovementMode

• **DefaultLandMovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[DefaultLandMovementMode](ue_ue.CharacterMovementComponent.md#defaultlandmovementmode)

#### Defined in

[ue/ue.d.ts:5734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5734)

___

### DefaultWaterMovementMode

• **DefaultWaterMovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[DefaultWaterMovementMode](ue_ue.CharacterMovementComponent.md#defaultwatermovementmode)

#### Defined in

[ue/ue.d.ts:5735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5735)

___

### DeferredUpdatedMoveComponent

• **DeferredUpdatedMoveComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[DeferredUpdatedMoveComponent](ue_ue.CharacterMovementComponent.md#deferredupdatedmovecomponent)

#### Defined in

[ue/ue.d.ts:5687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5687)

___

### FallingLateralFriction

• **FallingLateralFriction**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[FallingLateralFriction](ue_ue.CharacterMovementComponent.md#fallinglateralfriction)

#### Defined in

[ue/ue.d.ts:5659](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5659)

___

### FixedPathBrakingDistance

• **FixedPathBrakingDistance**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[FixedPathBrakingDistance](ue_ue.CharacterMovementComponent.md#fixedpathbrakingdistance)

#### Defined in

[ue/ue.d.ts:5468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5468)

___

### GravityScale

• **GravityScale**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GravityScale](ue_ue.CharacterMovementComponent.md#gravityscale)

#### Defined in

[ue/ue.d.ts:5632](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5632)

___

### GroundFriction

• **GroundFriction**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GroundFriction](ue_ue.CharacterMovementComponent.md#groundfriction)

#### Defined in

[ue/ue.d.ts:5641](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5641)

___

### GroundMovementMode

• **GroundMovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GroundMovementMode](ue_ue.CharacterMovementComponent.md#groundmovementmode)

#### Defined in

[ue/ue.d.ts:5736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5736)

___

### GroupsToAvoid

• **GroupsToAvoid**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GroupsToAvoid](ue_ue.CharacterMovementComponent.md#groupstoavoid)

#### Defined in

[ue/ue.d.ts:5770](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5770)

___

### GroupsToIgnore

• **GroupsToIgnore**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GroupsToIgnore](ue_ue.CharacterMovementComponent.md#groupstoignore)

#### Defined in

[ue/ue.d.ts:5771](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5771)

___

### InitialPushForceFactor

• **InitialPushForceFactor**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[InitialPushForceFactor](ue_ue.CharacterMovementComponent.md#initialpushforcefactor)

#### Defined in

[ue/ue.d.ts:5692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5692)

___

### JumpOffJumpZFactor

• **JumpOffJumpZFactor**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[JumpOffJumpZFactor](ue_ue.CharacterMovementComponent.md#jumpoffjumpzfactor)

#### Defined in

[ue/ue.d.ts:5635](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5635)

___

### JumpOutOfWaterPitch

• **JumpOutOfWaterPitch**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[JumpOutOfWaterPitch](ue_ue.CharacterMovementComponent.md#jumpoutofwaterpitch)

#### Defined in

[ue/ue.d.ts:5732](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5732)

___

### JumpZVelocity

• **JumpZVelocity**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[JumpZVelocity](ue_ue.CharacterMovementComponent.md#jumpzvelocity)

#### Defined in

[ue/ue.d.ts:5634](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5634)

___

### LastUpdateLocation

• **LastUpdateLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[LastUpdateLocation](ue_ue.CharacterMovementComponent.md#lastupdatelocation)

#### Defined in

[ue/ue.d.ts:5704](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5704)

___

### LastUpdateRotation

• **LastUpdateRotation**: [`Quat`](ue_ue_s.Quat.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[LastUpdateRotation](ue_ue.CharacterMovementComponent.md#lastupdaterotation)

#### Defined in

[ue/ue.d.ts:5703](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5703)

___

### LastUpdateVelocity

• **LastUpdateVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[LastUpdateVelocity](ue_ue.CharacterMovementComponent.md#lastupdatevelocity)

#### Defined in

[ue/ue.d.ts:5705](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5705)

___

### LedgeCheckThreshold

• **LedgeCheckThreshold**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[LedgeCheckThreshold](ue_ue.CharacterMovementComponent.md#ledgecheckthreshold)

#### Defined in

[ue/ue.d.ts:5731](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5731)

___

### ListenServerNetworkSimulatedSmoothLocationTime

• **ListenServerNetworkSimulatedSmoothLocationTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ListenServerNetworkSimulatedSmoothLocationTime](ue_ue.CharacterMovementComponent.md#listenservernetworksimulatedsmoothlocationtime)

#### Defined in

[ue/ue.d.ts:5721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5721)

___

### ListenServerNetworkSimulatedSmoothRotationTime

• **ListenServerNetworkSimulatedSmoothRotationTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ListenServerNetworkSimulatedSmoothRotationTime](ue_ue.CharacterMovementComponent.md#listenservernetworksimulatedsmoothrotationtime)

#### Defined in

[ue/ue.d.ts:5722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5722)

___

### Mass

• **Mass**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[Mass](ue_ue.CharacterMovementComponent.md#mass)

#### Defined in

[ue/ue.d.ts:5690](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5690)

___

### MaxAcceleration

• **MaxAcceleration**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxAcceleration](ue_ue.CharacterMovementComponent.md#maxacceleration)

#### Defined in

[ue/ue.d.ts:5647](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5647)

___

### MaxCustomMovementSpeed

• **MaxCustomMovementSpeed**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxCustomMovementSpeed](ue_ue.CharacterMovementComponent.md#maxcustommovementspeed)

#### Defined in

[ue/ue.d.ts:5646](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5646)

___

### MaxDepenetrationWithGeometry

• **MaxDepenetrationWithGeometry**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxDepenetrationWithGeometry](ue_ue.CharacterMovementComponent.md#maxdepenetrationwithgeometry)

#### Defined in

[ue/ue.d.ts:5715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5715)

___

### MaxDepenetrationWithGeometryAsProxy

• **MaxDepenetrationWithGeometryAsProxy**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxDepenetrationWithGeometryAsProxy](ue_ue.CharacterMovementComponent.md#maxdepenetrationwithgeometryasproxy)

#### Defined in

[ue/ue.d.ts:5716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5716)

___

### MaxDepenetrationWithPawn

• **MaxDepenetrationWithPawn**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxDepenetrationWithPawn](ue_ue.CharacterMovementComponent.md#maxdepenetrationwithpawn)

#### Defined in

[ue/ue.d.ts:5717](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5717)

___

### MaxDepenetrationWithPawnAsProxy

• **MaxDepenetrationWithPawnAsProxy**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxDepenetrationWithPawnAsProxy](ue_ue.CharacterMovementComponent.md#maxdepenetrationwithpawnasproxy)

#### Defined in

[ue/ue.d.ts:5718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5718)

___

### MaxFlySpeed

• **MaxFlySpeed**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxFlySpeed](ue_ue.CharacterMovementComponent.md#maxflyspeed)

#### Defined in

[ue/ue.d.ts:5645](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5645)

___

### MaxJumpApexAttemptsPerSimulation

• **MaxJumpApexAttemptsPerSimulation**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxJumpApexAttemptsPerSimulation](ue_ue.CharacterMovementComponent.md#maxjumpapexattemptspersimulation)

#### Defined in

[ue/ue.d.ts:5714](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5714)

___

### MaxOutOfWaterStepHeight

• **MaxOutOfWaterStepHeight**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxOutOfWaterStepHeight](ue_ue.CharacterMovementComponent.md#maxoutofwaterstepheight)

#### Defined in

[ue/ue.d.ts:5688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5688)

___

### MaxPitch

• **MaxPitch**: `number`

#### Defined in

[ue/ue.d.ts:21166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21166)

___

### MaxRotationalVelocity

• **MaxRotationalVelocity**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:21164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21164)

___

### MaxSimulationIterations

• **MaxSimulationIterations**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxSimulationIterations](ue_ue.CharacterMovementComponent.md#maxsimulationiterations)

#### Defined in

[ue/ue.d.ts:5713](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5713)

___

### MaxSimulationTimeStep

• **MaxSimulationTimeStep**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxSimulationTimeStep](ue_ue.CharacterMovementComponent.md#maxsimulationtimestep)

#### Defined in

[ue/ue.d.ts:5712](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5712)

___

### MaxStepHeight

• **MaxStepHeight**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxStepHeight](ue_ue.CharacterMovementComponent.md#maxstepheight)

#### Defined in

[ue/ue.d.ts:5633](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5633)

___

### MaxSwimSpeed

• **MaxSwimSpeed**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxSwimSpeed](ue_ue.CharacterMovementComponent.md#maxswimspeed)

#### Defined in

[ue/ue.d.ts:5644](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5644)

___

### MaxTouchForce

• **MaxTouchForce**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxTouchForce](ue_ue.CharacterMovementComponent.md#maxtouchforce)

#### Defined in

[ue/ue.d.ts:5697](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5697)

___

### MaxWalkSpeed

• **MaxWalkSpeed**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxWalkSpeed](ue_ue.CharacterMovementComponent.md#maxwalkspeed)

#### Defined in

[ue/ue.d.ts:5642](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5642)

___

### MaxWalkSpeedCrouched

• **MaxWalkSpeedCrouched**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MaxWalkSpeedCrouched](ue_ue.CharacterMovementComponent.md#maxwalkspeedcrouched)

#### Defined in

[ue/ue.d.ts:5643](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5643)

___

### MinAnalogWalkSpeed

• **MinAnalogWalkSpeed**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MinAnalogWalkSpeed](ue_ue.CharacterMovementComponent.md#minanalogwalkspeed)

#### Defined in

[ue/ue.d.ts:5648](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5648)

___

### MinPitch

• **MinPitch**: `number`

#### Defined in

[ue/ue.d.ts:21165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21165)

___

### MinTimeBetweenTimeStampResets

• **MinTimeBetweenTimeStampResets**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MinTimeBetweenTimeStampResets](ue_ue.CharacterMovementComponent.md#mintimebetweentimestampresets)

#### Defined in

[ue/ue.d.ts:5781](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5781)

___

### MinTouchForce

• **MinTouchForce**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MinTouchForce](ue_ue.CharacterMovementComponent.md#mintouchforce)

#### Defined in

[ue/ue.d.ts:5696](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5696)

___

### MovementMode

• **MovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MovementMode](ue_ue.CharacterMovementComponent.md#movementmode)

#### Defined in

[ue/ue.d.ts:5638](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5638)

___

### MovementState

• **MovementState**: [`MovementProperties`](ue_ue.MovementProperties.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[MovementState](ue_ue.CharacterMovementComponent.md#movementstate)

#### Defined in

[ue/ue.d.ts:5472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5472)

___

### NavAgentProps

• **NavAgentProps**: [`NavAgentProperties`](ue_ue.NavAgentProperties.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavAgentProps](ue_ue.CharacterMovementComponent.md#navagentprops)

#### Defined in

[ue/ue.d.ts:5467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5467)

___

### NavMeshProjectionHeightScaleDown

• **NavMeshProjectionHeightScaleDown**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavMeshProjectionHeightScaleDown](ue_ue.CharacterMovementComponent.md#navmeshprojectionheightscaledown)

#### Defined in

[ue/ue.d.ts:5778](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5778)

___

### NavMeshProjectionHeightScaleUp

• **NavMeshProjectionHeightScaleUp**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavMeshProjectionHeightScaleUp](ue_ue.CharacterMovementComponent.md#navmeshprojectionheightscaleup)

#### Defined in

[ue/ue.d.ts:5777](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5777)

___

### NavMeshProjectionInterpSpeed

• **NavMeshProjectionInterpSpeed**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavMeshProjectionInterpSpeed](ue_ue.CharacterMovementComponent.md#navmeshprojectioninterpspeed)

#### Defined in

[ue/ue.d.ts:5776](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5776)

___

### NavMeshProjectionInterval

• **NavMeshProjectionInterval**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavMeshProjectionInterval](ue_ue.CharacterMovementComponent.md#navmeshprojectioninterval)

#### Defined in

[ue/ue.d.ts:5774](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5774)

___

### NavMeshProjectionTimer

• **NavMeshProjectionTimer**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavMeshProjectionTimer](ue_ue.CharacterMovementComponent.md#navmeshprojectiontimer)

#### Defined in

[ue/ue.d.ts:5775](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5775)

___

### NavWalkingFloorDistTolerance

• **NavWalkingFloorDistTolerance**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NavWalkingFloorDistTolerance](ue_ue.CharacterMovementComponent.md#navwalkingfloordisttolerance)

#### Defined in

[ue/ue.d.ts:5779](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5779)

___

### NetProxyShrinkHalfHeight

• **NetProxyShrinkHalfHeight**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetProxyShrinkHalfHeight](ue_ue.CharacterMovementComponent.md#netproxyshrinkhalfheight)

#### Defined in

[ue/ue.d.ts:5724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5724)

___

### NetProxyShrinkRadius

• **NetProxyShrinkRadius**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetProxyShrinkRadius](ue_ue.CharacterMovementComponent.md#netproxyshrinkradius)

#### Defined in

[ue/ue.d.ts:5723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5723)

___

### NetworkLargeClientCorrectionDistance

• **NetworkLargeClientCorrectionDistance**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkLargeClientCorrectionDistance](ue_ue.CharacterMovementComponent.md#networklargeclientcorrectiondistance)

#### Defined in

[ue/ue.d.ts:5730](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5730)

___

### NetworkMaxSmoothUpdateDistance

• **NetworkMaxSmoothUpdateDistance**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkMaxSmoothUpdateDistance](ue_ue.CharacterMovementComponent.md#networkmaxsmoothupdatedistance)

#### Defined in

[ue/ue.d.ts:5725](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5725)

___

### NetworkMinTimeBetweenClientAckGoodMoves

• **NetworkMinTimeBetweenClientAckGoodMoves**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkMinTimeBetweenClientAckGoodMoves](ue_ue.CharacterMovementComponent.md#networkmintimebetweenclientackgoodmoves)

#### Defined in

[ue/ue.d.ts:5727](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5727)

___

### NetworkMinTimeBetweenClientAdjustments

• **NetworkMinTimeBetweenClientAdjustments**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkMinTimeBetweenClientAdjustments](ue_ue.CharacterMovementComponent.md#networkmintimebetweenclientadjustments)

#### Defined in

[ue/ue.d.ts:5728](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5728)

___

### NetworkMinTimeBetweenClientAdjustmentsLargeCorrection

• **NetworkMinTimeBetweenClientAdjustmentsLargeCorrection**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkMinTimeBetweenClientAdjustmentsLargeCorrection](ue_ue.CharacterMovementComponent.md#networkmintimebetweenclientadjustmentslargecorrection)

#### Defined in

[ue/ue.d.ts:5729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5729)

___

### NetworkNoSmoothUpdateDistance

• **NetworkNoSmoothUpdateDistance**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkNoSmoothUpdateDistance](ue_ue.CharacterMovementComponent.md#networknosmoothupdatedistance)

#### Defined in

[ue/ue.d.ts:5726](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5726)

___

### NetworkSimulatedSmoothLocationTime

• **NetworkSimulatedSmoothLocationTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkSimulatedSmoothLocationTime](ue_ue.CharacterMovementComponent.md#networksimulatedsmoothlocationtime)

#### Defined in

[ue/ue.d.ts:5719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5719)

___

### NetworkSimulatedSmoothRotationTime

• **NetworkSimulatedSmoothRotationTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkSimulatedSmoothRotationTime](ue_ue.CharacterMovementComponent.md#networksimulatedsmoothrotationtime)

#### Defined in

[ue/ue.d.ts:5720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5720)

___

### NetworkSmoothingMode

• **NetworkSmoothingMode**: [`ENetworkSmoothingMode`](../enums/ue_ue.ENetworkSmoothingMode.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[NetworkSmoothingMode](ue_ue.CharacterMovementComponent.md#networksmoothingmode)

#### Defined in

[ue/ue.d.ts:5640](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5640)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[OnComponentActivated](ue_ue.CharacterMovementComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[OnComponentDeactivated](ue_ue.CharacterMovementComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### OutofWaterZ

• **OutofWaterZ**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[OutofWaterZ](ue_ue.CharacterMovementComponent.md#outofwaterz)

#### Defined in

[ue/ue.d.ts:5689](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5689)

___

### PathFollowingComp

• **PathFollowingComp**: [`Object`](ue_ue.Object.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PathFollowingComp](ue_ue.CharacterMovementComponent.md#pathfollowingcomp)

#### Defined in

[ue/ue.d.ts:5473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5473)

___

### PawnOwner

• **PawnOwner**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PawnOwner](ue_ue.CharacterMovementComponent.md#pawnowner)

#### Defined in

[ue/ue.d.ts:5490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5490)

___

### PendingForceToApply

• **PendingForceToApply**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PendingForceToApply](ue_ue.CharacterMovementComponent.md#pendingforcetoapply)

#### Defined in

[ue/ue.d.ts:5710](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5710)

___

### PendingImpulseToApply

• **PendingImpulseToApply**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PendingImpulseToApply](ue_ue.CharacterMovementComponent.md#pendingimpulsetoapply)

#### Defined in

[ue/ue.d.ts:5709](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5709)

___

### PendingLaunchVelocity

• **PendingLaunchVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PendingLaunchVelocity](ue_ue.CharacterMovementComponent.md#pendinglaunchvelocity)

#### Defined in

[ue/ue.d.ts:5773](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5773)

___

### PerchAdditionalHeight

• **PerchAdditionalHeight**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PerchAdditionalHeight](ue_ue.CharacterMovementComponent.md#perchadditionalheight)

#### Defined in

[ue/ue.d.ts:5663](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5663)

___

### PerchRadiusThreshold

• **PerchRadiusThreshold**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PerchRadiusThreshold](ue_ue.CharacterMovementComponent.md#perchradiusthreshold)

#### Defined in

[ue/ue.d.ts:5662](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5662)

___

### PlaneConstraintAxisSetting

• **PlaneConstraintAxisSetting**: [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PlaneConstraintAxisSetting](ue_ue.CharacterMovementComponent.md#planeconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5403](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5403)

___

### PlaneConstraintNormal

• **PlaneConstraintNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PlaneConstraintNormal](ue_ue.CharacterMovementComponent.md#planeconstraintnormal)

#### Defined in

[ue/ue.d.ts:5393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5393)

___

### PlaneConstraintOrigin

• **PlaneConstraintOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PlaneConstraintOrigin](ue_ue.CharacterMovementComponent.md#planeconstraintorigin)

#### Defined in

[ue/ue.d.ts:5394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5394)

___

### PostPhysicsTickFunction

• **PostPhysicsTickFunction**: [`CharacterMovementComponentPostPhysicsTickFunction`](ue_ue.CharacterMovementComponentPostPhysicsTickFunction.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PostPhysicsTickFunction](ue_ue.CharacterMovementComponent.md#postphysicstickfunction)

#### Defined in

[ue/ue.d.ts:5780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5780)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PrimaryComponentTick](ue_ue.CharacterMovementComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### PushForceFactor

• **PushForceFactor**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PushForceFactor](ue_ue.CharacterMovementComponent.md#pushforcefactor)

#### Defined in

[ue/ue.d.ts:5693](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5693)

___

### PushForcePointZOffsetFactor

• **PushForcePointZOffsetFactor**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[PushForcePointZOffsetFactor](ue_ue.CharacterMovementComponent.md#pushforcepointzoffsetfactor)

#### Defined in

[ue/ue.d.ts:5694](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5694)

___

### RepulsionForce

• **RepulsionForce**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RepulsionForce](ue_ue.CharacterMovementComponent.md#repulsionforce)

#### Defined in

[ue/ue.d.ts:5698](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5698)

___

### RequestedVelocity

• **RequestedVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RequestedVelocity](ue_ue.CharacterMovementComponent.md#requestedvelocity)

#### Defined in

[ue/ue.d.ts:5767](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5767)

___

### RootMotionParams

• **RootMotionParams**: [`RootMotionMovementParams`](ue_ue.RootMotionMovementParams.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RootMotionParams](ue_ue.CharacterMovementComponent.md#rootmotionparams)

#### Defined in

[ue/ue.d.ts:5783](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5783)

___

### RotationRate

• **RotationRate**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RotationRate](ue_ue.CharacterMovementComponent.md#rotationrate)

#### Defined in

[ue/ue.d.ts:5664](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5664)

___

### RotationalAcceleration

• **RotationalAcceleration**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:21162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21162)

___

### RotationalDeceleration

• **RotationalDeceleration**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:21163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21163)

___

### ServerLastClientAdjustmentTime

• **ServerLastClientAdjustmentTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ServerLastClientAdjustmentTime](ue_ue.CharacterMovementComponent.md#serverlastclientadjustmenttime)

#### Defined in

[ue/ue.d.ts:5708](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5708)

___

### ServerLastClientGoodMoveAckTime

• **ServerLastClientGoodMoveAckTime**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ServerLastClientGoodMoveAckTime](ue_ue.CharacterMovementComponent.md#serverlastclientgoodmoveacktime)

#### Defined in

[ue/ue.d.ts:5707](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5707)

___

### ServerLastTransformUpdateTimeStamp

• **ServerLastTransformUpdateTimeStamp**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ServerLastTransformUpdateTimeStamp](ue_ue.CharacterMovementComponent.md#serverlasttransformupdatetimestamp)

#### Defined in

[ue/ue.d.ts:5706](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5706)

___

### StandingDownwardForceScale

• **StandingDownwardForceScale**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[StandingDownwardForceScale](ue_ue.CharacterMovementComponent.md#standingdownwardforcescale)

#### Defined in

[ue/ue.d.ts:5691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5691)

___

### TouchForceFactor

• **TouchForceFactor**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[TouchForceFactor](ue_ue.CharacterMovementComponent.md#touchforcefactor)

#### Defined in

[ue/ue.d.ts:5695](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5695)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[UCSModifiedProperties](ue_ue.CharacterMovementComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### UpdatedComponent

• **UpdatedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[UpdatedComponent](ue_ue.CharacterMovementComponent.md#updatedcomponent)

#### Defined in

[ue/ue.d.ts:5390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5390)

___

### UpdatedPrimitive

• **UpdatedPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[UpdatedPrimitive](ue_ue.CharacterMovementComponent.md#updatedprimitive)

#### Defined in

[ue/ue.d.ts:5391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5391)

___

### UpperImpactNormalScale

• **UpperImpactNormalScale**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[UpperImpactNormalScale](ue_ue.CharacterMovementComponent.md#upperimpactnormalscale)

#### Defined in

[ue/ue.d.ts:5701](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5701)

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[Velocity](ue_ue.CharacterMovementComponent.md#velocity)

#### Defined in

[ue/ue.d.ts:5392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5392)

___

### WalkableFloorAngle

• **WalkableFloorAngle**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[WalkableFloorAngle](ue_ue.CharacterMovementComponent.md#walkablefloorangle)

#### Defined in

[ue/ue.d.ts:5636](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5636)

___

### WalkableFloorZ

• **WalkableFloorZ**: `number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[WalkableFloorZ](ue_ue.CharacterMovementComponent.md#walkablefloorz)

#### Defined in

[ue/ue.d.ts:5637](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5637)

___

### WalkingAcceleration

• **WalkingAcceleration**: `number`

#### Defined in

[ue/ue.d.ts:21169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21169)

___

### WalkingFriction

• **WalkingFriction**: `number`

#### Defined in

[ue/ue.d.ts:21167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21167)

___

### WalkingSpeed

• **WalkingSpeed**: `number`

#### Defined in

[ue/ue.d.ts:21168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21168)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[__tid_ActorComponent__](ue_ue.CharacterMovementComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_ArchVisCharMovementComponent\_\_

• **\_\_tid\_ArchVisCharMovementComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21174)

___

### \_\_tid\_CharacterMovementComponent\_\_

• **\_\_tid\_CharacterMovementComponent\_\_**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[__tid_CharacterMovementComponent__](ue_ue.CharacterMovementComponent.md#__tid_charactermovementcomponent__)

#### Defined in

[ue/ue.d.ts:5827](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5827)

___

### \_\_tid\_MovementComponent\_\_

• **\_\_tid\_MovementComponent\_\_**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[__tid_MovementComponent__](ue_ue.CharacterMovementComponent.md#__tid_movementcomponent__)

#### Defined in

[ue/ue.d.ts:5430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5430)

___

### \_\_tid\_NavMovementComponent\_\_

• **\_\_tid\_NavMovementComponent\_\_**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[__tid_NavMovementComponent__](ue_ue.CharacterMovementComponent.md#__tid_navmovementcomponent__)

#### Defined in

[ue/ue.d.ts:5485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5485)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[__tid_Object__](ue_ue.CharacterMovementComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PawnMovementComponent\_\_

• **\_\_tid\_PawnMovementComponent\_\_**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[__tid_PawnMovementComponent__](ue_ue.CharacterMovementComponent.md#__tid_pawnmovementcomponent__)

#### Defined in

[ue/ue.d.ts:5502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5502)

___

### bAllowPhysicsRotationDuringAnimRootMotion

• **bAllowPhysicsRotationDuringAnimRootMotion**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bAllowPhysicsRotationDuringAnimRootMotion](ue_ue.CharacterMovementComponent.md#ballowphysicsrotationduringanimrootmotion)

#### Defined in

[ue/ue.d.ts:5760](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5760)

___

### bAlwaysCheckFloor

• **bAlwaysCheckFloor**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bAlwaysCheckFloor](ue_ue.CharacterMovementComponent.md#balwayscheckfloor)

#### Defined in

[ue/ue.d.ts:5753](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5753)

___

### bApplyGravityWhileJumping

• **bApplyGravityWhileJumping**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bApplyGravityWhileJumping](ue_ue.CharacterMovementComponent.md#bapplygravitywhilejumping)

#### Defined in

[ue/ue.d.ts:5666](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5666)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bAutoActivate](ue_ue.CharacterMovementComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bAutoRegisterPhysicsVolumeUpdates

• **bAutoRegisterPhysicsVolumeUpdates**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bAutoRegisterPhysicsVolumeUpdates](ue_ue.CharacterMovementComponent.md#bautoregisterphysicsvolumeupdates)

#### Defined in

[ue/ue.d.ts:5401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5401)

___

### bAutoRegisterUpdatedComponent

• **bAutoRegisterUpdatedComponent**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bAutoRegisterUpdatedComponent](ue_ue.CharacterMovementComponent.md#bautoregisterupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5398)

___

### bAutoUpdateTickRegistration

• **bAutoUpdateTickRegistration**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bAutoUpdateTickRegistration](ue_ue.CharacterMovementComponent.md#bautoupdatetickregistration)

#### Defined in

[ue/ue.d.ts:5396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5396)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bCanEverAffectNavigation](ue_ue.CharacterMovementComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bCanWalkOffLedges

• **bCanWalkOffLedges**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bCanWalkOffLedges](ue_ue.CharacterMovementComponent.md#bcanwalkoffledges)

#### Defined in

[ue/ue.d.ts:5677](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5677)

___

### bCanWalkOffLedgesWhenCrouching

• **bCanWalkOffLedgesWhenCrouching**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bCanWalkOffLedgesWhenCrouching](ue_ue.CharacterMovementComponent.md#bcanwalkoffledgeswhencrouching)

#### Defined in

[ue/ue.d.ts:5678](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5678)

___

### bCheatFlying

• **bCheatFlying**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bCheatFlying](ue_ue.CharacterMovementComponent.md#bcheatflying)

#### Defined in

[ue/ue.d.ts:5748](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5748)

___

### bComponentShouldUpdatePhysicsVolume

• **bComponentShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bComponentShouldUpdatePhysicsVolume](ue_ue.CharacterMovementComponent.md#bcomponentshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:5402](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5402)

___

### bConstrainToPlane

• **bConstrainToPlane**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bConstrainToPlane](ue_ue.CharacterMovementComponent.md#bconstraintoplane)

#### Defined in

[ue/ue.d.ts:5399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5399)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bCreatedByConstructionScript](ue_ue.CharacterMovementComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bCrouchMaintainsBaseLocation

• **bCrouchMaintainsBaseLocation**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bCrouchMaintainsBaseLocation](ue_ue.CharacterMovementComponent.md#bcrouchmaintainsbaselocation)

#### Defined in

[ue/ue.d.ts:5750](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5750)

___

### bDeferUpdateMoveComponent

• **bDeferUpdateMoveComponent**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bDeferUpdateMoveComponent](ue_ue.CharacterMovementComponent.md#bdeferupdatemovecomponent)

#### Defined in

[ue/ue.d.ts:5681](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5681)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bEditableWhenInherited](ue_ue.CharacterMovementComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bEnablePhysicsInteraction

• **bEnablePhysicsInteraction**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bEnablePhysicsInteraction](ue_ue.CharacterMovementComponent.md#benablephysicsinteraction)

#### Defined in

[ue/ue.d.ts:5682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5682)

___

### bEnableScopedMovementUpdates

• **bEnableScopedMovementUpdates**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bEnableScopedMovementUpdates](ue_ue.CharacterMovementComponent.md#benablescopedmovementupdates)

#### Defined in

[ue/ue.d.ts:5671](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5671)

___

### bEnableServerDualMoveScopedMovementUpdates

• **bEnableServerDualMoveScopedMovementUpdates**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bEnableServerDualMoveScopedMovementUpdates](ue_ue.CharacterMovementComponent.md#benableserverdualmovescopedmovementupdates)

#### Defined in

[ue/ue.d.ts:5672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5672)

___

### bFastAttachedMove

• **bFastAttachedMove**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bFastAttachedMove](ue_ue.CharacterMovementComponent.md#bfastattachedmove)

#### Defined in

[ue/ue.d.ts:5752](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5752)

___

### bForceBraking

• **bForceBraking**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bForceBraking](ue_ue.CharacterMovementComponent.md#bforcebraking)

#### Defined in

[ue/ue.d.ts:5699](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5699)

___

### bForceMaxAccel

• **bForceMaxAccel**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bForceMaxAccel](ue_ue.CharacterMovementComponent.md#bforcemaxaccel)

#### Defined in

[ue/ue.d.ts:5673](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5673)

___

### bForceNextFloorCheck

• **bForceNextFloorCheck**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bForceNextFloorCheck](ue_ue.CharacterMovementComponent.md#bforcenextfloorcheck)

#### Defined in

[ue/ue.d.ts:5675](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5675)

___

### bHasRequestedVelocity

• **bHasRequestedVelocity**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bHasRequestedVelocity](ue_ue.CharacterMovementComponent.md#bhasrequestedvelocity)

#### Defined in

[ue/ue.d.ts:5761](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5761)

___

### bIgnoreBaseRotation

• **bIgnoreBaseRotation**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bIgnoreBaseRotation](ue_ue.CharacterMovementComponent.md#bignorebaserotation)

#### Defined in

[ue/ue.d.ts:5751](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5751)

___

### bIgnoreClientMovementErrorChecksAndCorrection

• **bIgnoreClientMovementErrorChecksAndCorrection**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bIgnoreClientMovementErrorChecksAndCorrection](ue_ue.CharacterMovementComponent.md#bignoreclientmovementerrorchecksandcorrection)

#### Defined in

[ue/ue.d.ts:5745](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5745)

___

### bImpartBaseAngularVelocity

• **bImpartBaseAngularVelocity**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bImpartBaseAngularVelocity](ue_ue.CharacterMovementComponent.md#bimpartbaseangularvelocity)

#### Defined in

[ue/ue.d.ts:5741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5741)

___

### bImpartBaseVelocityX

• **bImpartBaseVelocityX**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bImpartBaseVelocityX](ue_ue.CharacterMovementComponent.md#bimpartbasevelocityx)

#### Defined in

[ue/ue.d.ts:5738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5738)

___

### bImpartBaseVelocityY

• **bImpartBaseVelocityY**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bImpartBaseVelocityY](ue_ue.CharacterMovementComponent.md#bimpartbasevelocityy)

#### Defined in

[ue/ue.d.ts:5739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5739)

___

### bImpartBaseVelocityZ

• **bImpartBaseVelocityZ**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bImpartBaseVelocityZ](ue_ue.CharacterMovementComponent.md#bimpartbasevelocityz)

#### Defined in

[ue/ue.d.ts:5740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5740)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bInstanceComponent](ue_ue.CharacterMovementComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bIsActive](ue_ue.CharacterMovementComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bIsEditorOnly](ue_ue.CharacterMovementComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bIsVisualizationComponent](ue_ue.CharacterMovementComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bJustTeleported

• **bJustTeleported**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bJustTeleported](ue_ue.CharacterMovementComponent.md#bjustteleported)

#### Defined in

[ue/ue.d.ts:5742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5742)

___

### bMaintainHorizontalGroundVelocity

• **bMaintainHorizontalGroundVelocity**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bMaintainHorizontalGroundVelocity](ue_ue.CharacterMovementComponent.md#bmaintainhorizontalgroundvelocity)

#### Defined in

[ue/ue.d.ts:5737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5737)

___

### bMovementInProgress

• **bMovementInProgress**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bMovementInProgress](ue_ue.CharacterMovementComponent.md#bmovementinprogress)

#### Defined in

[ue/ue.d.ts:5670](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5670)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bNetAddressable](ue_ue.CharacterMovementComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bNetworkAlwaysReplicateTransformUpdateTimestamp

• **bNetworkAlwaysReplicateTransformUpdateTimestamp**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bNetworkAlwaysReplicateTransformUpdateTimestamp](ue_ue.CharacterMovementComponent.md#bnetworkalwaysreplicatetransformupdatetimestamp)

#### Defined in

[ue/ue.d.ts:5680](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5680)

___

### bNetworkMovementModeChanged

• **bNetworkMovementModeChanged**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bNetworkMovementModeChanged](ue_ue.CharacterMovementComponent.md#bnetworkmovementmodechanged)

#### Defined in

[ue/ue.d.ts:5744](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5744)

___

### bNetworkSkipProxyPredictionOnNetUpdate

• **bNetworkSkipProxyPredictionOnNetUpdate**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bNetworkSkipProxyPredictionOnNetUpdate](ue_ue.CharacterMovementComponent.md#bnetworkskipproxypredictiononnetupdate)

#### Defined in

[ue/ue.d.ts:5679](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5679)

___

### bNetworkUpdateReceived

• **bNetworkUpdateReceived**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bNetworkUpdateReceived](ue_ue.CharacterMovementComponent.md#bnetworkupdatereceived)

#### Defined in

[ue/ue.d.ts:5743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5743)

___

### bNotifyApex

• **bNotifyApex**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bNotifyApex](ue_ue.CharacterMovementComponent.md#bnotifyapex)

#### Defined in

[ue/ue.d.ts:5747](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5747)

___

### bOrientRotationToMovement

• **bOrientRotationToMovement**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bOrientRotationToMovement](ue_ue.CharacterMovementComponent.md#borientrotationtomovement)

#### Defined in

[ue/ue.d.ts:5668](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5668)

___

### bPerformingJumpOff

• **bPerformingJumpOff**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bPerformingJumpOff](ue_ue.CharacterMovementComponent.md#bperformingjumpoff)

#### Defined in

[ue/ue.d.ts:5755](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5755)

___

### bProjectNavMeshOnBothWorldChannels

• **bProjectNavMeshOnBothWorldChannels**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bProjectNavMeshOnBothWorldChannels](ue_ue.CharacterMovementComponent.md#bprojectnavmeshonbothworldchannels)

#### Defined in

[ue/ue.d.ts:5765](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5765)

___

### bProjectNavMeshWalking

• **bProjectNavMeshWalking**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bProjectNavMeshWalking](ue_ue.CharacterMovementComponent.md#bprojectnavmeshwalking)

#### Defined in

[ue/ue.d.ts:5764](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5764)

___

### bPushForceScaledToMass

• **bPushForceScaledToMass**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bPushForceScaledToMass](ue_ue.CharacterMovementComponent.md#bpushforcescaledtomass)

#### Defined in

[ue/ue.d.ts:5684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5684)

___

### bPushForceUsingZOffset

• **bPushForceUsingZOffset**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bPushForceUsingZOffset](ue_ue.CharacterMovementComponent.md#bpushforceusingzoffset)

#### Defined in

[ue/ue.d.ts:5685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5685)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bReplicates](ue_ue.CharacterMovementComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L292)

___

### bRequestedMoveUseAcceleration

• **bRequestedMoveUseAcceleration**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bRequestedMoveUseAcceleration](ue_ue.CharacterMovementComponent.md#brequestedmoveuseacceleration)

#### Defined in

[ue/ue.d.ts:5758](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5758)

___

### bRequestedMoveWithMaxSpeed

• **bRequestedMoveWithMaxSpeed**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bRequestedMoveWithMaxSpeed](ue_ue.CharacterMovementComponent.md#brequestedmovewithmaxspeed)

#### Defined in

[ue/ue.d.ts:5762](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5762)

___

### bRunPhysicsWithNoController

• **bRunPhysicsWithNoController**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bRunPhysicsWithNoController](ue_ue.CharacterMovementComponent.md#brunphysicswithnocontroller)

#### Defined in

[ue/ue.d.ts:5674](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5674)

___

### bScalePushForceToVelocity

• **bScalePushForceToVelocity**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bScalePushForceToVelocity](ue_ue.CharacterMovementComponent.md#bscalepushforcetovelocity)

#### Defined in

[ue/ue.d.ts:5686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5686)

___

### bServerAcceptClientAuthoritativePosition

• **bServerAcceptClientAuthoritativePosition**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bServerAcceptClientAuthoritativePosition](ue_ue.CharacterMovementComponent.md#bserveracceptclientauthoritativeposition)

#### Defined in

[ue/ue.d.ts:5746](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5746)

___

### bShrinkProxyCapsule

• **bShrinkProxyCapsule**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bShrinkProxyCapsule](ue_ue.CharacterMovementComponent.md#bshrinkproxycapsule)

#### Defined in

[ue/ue.d.ts:5676](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5676)

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bSnapToPlaneAtStart](ue_ue.CharacterMovementComponent.md#bsnaptoplaneatstart)

#### Defined in

[ue/ue.d.ts:5400](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5400)

___

### bSweepWhileNavWalking

• **bSweepWhileNavWalking**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bSweepWhileNavWalking](ue_ue.CharacterMovementComponent.md#bsweepwhilenavwalking)

#### Defined in

[ue/ue.d.ts:5669](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5669)

___

### bTickBeforeOwner

• **bTickBeforeOwner**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bTickBeforeOwner](ue_ue.CharacterMovementComponent.md#btickbeforeowner)

#### Defined in

[ue/ue.d.ts:5397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5397)

___

### bTouchForceScaledToMass

• **bTouchForceScaledToMass**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bTouchForceScaledToMass](ue_ue.CharacterMovementComponent.md#btouchforcescaledtomass)

#### Defined in

[ue/ue.d.ts:5683](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5683)

___

### bUpdateNavAgentWithOwnersCollision

• **bUpdateNavAgentWithOwnersCollision**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUpdateNavAgentWithOwnersCollision](ue_ue.CharacterMovementComponent.md#bupdatenavagentwithownerscollision)

#### Defined in

[ue/ue.d.ts:5469](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5469)

___

### bUpdateOnlyIfRendered

• **bUpdateOnlyIfRendered**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUpdateOnlyIfRendered](ue_ue.CharacterMovementComponent.md#bupdateonlyifrendered)

#### Defined in

[ue/ue.d.ts:5395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5395)

___

### bUseAccelerationForPaths

• **bUseAccelerationForPaths**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUseAccelerationForPaths](ue_ue.CharacterMovementComponent.md#buseaccelerationforpaths)

#### Defined in

[ue/ue.d.ts:5470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5470)

___

### bUseControllerDesiredRotation

• **bUseControllerDesiredRotation**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUseControllerDesiredRotation](ue_ue.CharacterMovementComponent.md#busecontrollerdesiredrotation)

#### Defined in

[ue/ue.d.ts:5667](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5667)

___

### bUseFixedBrakingDistanceForPaths

• **bUseFixedBrakingDistanceForPaths**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUseFixedBrakingDistanceForPaths](ue_ue.CharacterMovementComponent.md#busefixedbrakingdistanceforpaths)

#### Defined in

[ue/ue.d.ts:5471](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5471)

___

### bUseFlatBaseForFloorChecks

• **bUseFlatBaseForFloorChecks**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUseFlatBaseForFloorChecks](ue_ue.CharacterMovementComponent.md#buseflatbaseforfloorchecks)

#### Defined in

[ue/ue.d.ts:5754](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5754)

___

### bUseRVOAvoidance

• **bUseRVOAvoidance**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUseRVOAvoidance](ue_ue.CharacterMovementComponent.md#buservoavoidance)

#### Defined in

[ue/ue.d.ts:5757](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5757)

___

### bUseSeparateBrakingFriction

• **bUseSeparateBrakingFriction**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bUseSeparateBrakingFriction](ue_ue.CharacterMovementComponent.md#buseseparatebrakingfriction)

#### Defined in

[ue/ue.d.ts:5665](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5665)

___

### bWantsToCrouch

• **bWantsToCrouch**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bWantsToCrouch](ue_ue.CharacterMovementComponent.md#bwantstocrouch)

#### Defined in

[ue/ue.d.ts:5749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5749)

___

### bWantsToLeaveNavWalking

• **bWantsToLeaveNavWalking**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bWantsToLeaveNavWalking](ue_ue.CharacterMovementComponent.md#bwantstoleavenavwalking)

#### Defined in

[ue/ue.d.ts:5756](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5756)

___

### bWasAvoidanceUpdated

• **bWasAvoidanceUpdated**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bWasAvoidanceUpdated](ue_ue.CharacterMovementComponent.md#bwasavoidanceupdated)

#### Defined in

[ue/ue.d.ts:5763](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5763)

___

### bWasSimulatingRootMotion

• **bWasSimulatingRootMotion**: `boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[bWasSimulatingRootMotion](ue_ue.CharacterMovementComponent.md#bwassimulatingrootmotion)

#### Defined in

[ue/ue.d.ts:5759](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5759)

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

#### Defined in

[ue/ue.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L306)

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

#### Defined in

[ue/ue.d.ts:5785](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5785)

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

#### Defined in

[ue/ue.d.ts:5786](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5786)

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

#### Defined in

[ue/ue.d.ts:5491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5491)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[AddTickPrerequisiteComponent](ue_ue.CharacterMovementComponent.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:308](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L308)

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

#### Defined in

[ue/ue.d.ts:5787](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5787)

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

#### Defined in

[ue/ue.d.ts:5788](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5788)

___

### ClearAccumulatedForces

▸ **ClearAccumulatedForces**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ClearAccumulatedForces](ue_ue.CharacterMovementComponent.md#clearaccumulatedforces)

#### Defined in

[ue/ue.d.ts:5789](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5789)

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

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L309)

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

#### Defined in

[ue/ue.d.ts:5404](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5404)

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

#### Defined in

[ue/ue.d.ts:5405](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5405)

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

#### Defined in

[ue/ue.d.ts:5406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5406)

___

### ConsumeInputVector

▸ **ConsumeInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ConsumeInputVector](ue_ue.CharacterMovementComponent.md#consumeinputvector)

#### Defined in

[ue/ue.d.ts:5492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5492)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[Deactivate](ue_ue.CharacterMovementComponent.md#deactivate)

#### Defined in

[ue/ue.d.ts:310](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L310)

___

### DisableMovement

▸ **DisableMovement**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[DisableMovement](ue_ue.CharacterMovementComponent.md#disablemovement)

#### Defined in

[ue/ue.d.ts:5790](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5790)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetAnalogInputModifier

▸ **GetAnalogInputModifier**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetAnalogInputModifier](ue_ue.CharacterMovementComponent.md#getanaloginputmodifier)

#### Defined in

[ue/ue.d.ts:5791](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5791)

___

### GetCharacterOwner

▸ **GetCharacterOwner**(): [`Character`](ue_ue.Character.md)

#### Returns

[`Character`](ue_ue.Character.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetCharacterOwner](ue_ue.CharacterMovementComponent.md#getcharacterowner)

#### Defined in

[ue/ue.d.ts:5792](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5792)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetClass](ue_ue.CharacterMovementComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetComponentTickInterval](ue_ue.CharacterMovementComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetCurrentAcceleration

▸ **GetCurrentAcceleration**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetCurrentAcceleration](ue_ue.CharacterMovementComponent.md#getcurrentacceleration)

#### Defined in

[ue/ue.d.ts:5793](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5793)

___

### GetGravityZ

▸ **GetGravityZ**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetGravityZ](ue_ue.CharacterMovementComponent.md#getgravityz)

#### Defined in

[ue/ue.d.ts:5407](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5407)

___

### GetImpartedMovementBaseVelocity

▸ **GetImpartedMovementBaseVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetImpartedMovementBaseVelocity](ue_ue.CharacterMovementComponent.md#getimpartedmovementbasevelocity)

#### Defined in

[ue/ue.d.ts:5794](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5794)

___

### GetLastInputVector

▸ **GetLastInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetLastInputVector](ue_ue.CharacterMovementComponent.md#getlastinputvector)

#### Defined in

[ue/ue.d.ts:5493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5493)

___

### GetLastUpdateLocation

▸ **GetLastUpdateLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetLastUpdateLocation](ue_ue.CharacterMovementComponent.md#getlastupdatelocation)

#### Defined in

[ue/ue.d.ts:5795](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5795)

___

### GetLastUpdateRotation

▸ **GetLastUpdateRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetLastUpdateRotation](ue_ue.CharacterMovementComponent.md#getlastupdaterotation)

#### Defined in

[ue/ue.d.ts:5796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5796)

___

### GetLastUpdateVelocity

▸ **GetLastUpdateVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetLastUpdateVelocity](ue_ue.CharacterMovementComponent.md#getlastupdatevelocity)

#### Defined in

[ue/ue.d.ts:5797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5797)

___

### GetMaxAcceleration

▸ **GetMaxAcceleration**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMaxAcceleration](ue_ue.CharacterMovementComponent.md#getmaxacceleration)

#### Defined in

[ue/ue.d.ts:5798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5798)

___

### GetMaxBrakingDeceleration

▸ **GetMaxBrakingDeceleration**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMaxBrakingDeceleration](ue_ue.CharacterMovementComponent.md#getmaxbrakingdeceleration)

#### Defined in

[ue/ue.d.ts:5799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5799)

___

### GetMaxJumpHeight

▸ **GetMaxJumpHeight**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMaxJumpHeight](ue_ue.CharacterMovementComponent.md#getmaxjumpheight)

#### Defined in

[ue/ue.d.ts:5800](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5800)

___

### GetMaxJumpHeightWithJumpTime

▸ **GetMaxJumpHeightWithJumpTime**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMaxJumpHeightWithJumpTime](ue_ue.CharacterMovementComponent.md#getmaxjumpheightwithjumptime)

#### Defined in

[ue/ue.d.ts:5801](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5801)

___

### GetMaxSpeed

▸ **GetMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMaxSpeed](ue_ue.CharacterMovementComponent.md#getmaxspeed)

#### Defined in

[ue/ue.d.ts:5408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5408)

___

### GetMinAnalogSpeed

▸ **GetMinAnalogSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMinAnalogSpeed](ue_ue.CharacterMovementComponent.md#getminanalogspeed)

#### Defined in

[ue/ue.d.ts:5802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5802)

___

### GetMovementBase

▸ **GetMovementBase**(): [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Returns

[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetMovementBase](ue_ue.CharacterMovementComponent.md#getmovementbase)

#### Defined in

[ue/ue.d.ts:5803](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5803)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetName](ue_ue.CharacterMovementComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetOuter](ue_ue.CharacterMovementComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetOwner](ue_ue.CharacterMovementComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L312)

___

### GetPawnOwner

▸ **GetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPawnOwner](ue_ue.CharacterMovementComponent.md#getpawnowner)

#### Defined in

[ue/ue.d.ts:5494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5494)

___

### GetPendingInputVector

▸ **GetPendingInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPendingInputVector](ue_ue.CharacterMovementComponent.md#getpendinginputvector)

#### Defined in

[ue/ue.d.ts:5495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5495)

___

### GetPerchRadiusThreshold

▸ **GetPerchRadiusThreshold**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPerchRadiusThreshold](ue_ue.CharacterMovementComponent.md#getperchradiusthreshold)

#### Defined in

[ue/ue.d.ts:5804](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5804)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPhysicsVolume](ue_ue.CharacterMovementComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:5409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5409)

___

### GetPlaneConstraintAxisSetting

▸ **GetPlaneConstraintAxisSetting**(): [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Returns

[`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPlaneConstraintAxisSetting](ue_ue.CharacterMovementComponent.md#getplaneconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5410)

___

### GetPlaneConstraintNormal

▸ **GetPlaneConstraintNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPlaneConstraintNormal](ue_ue.CharacterMovementComponent.md#getplaneconstraintnormal)

#### Defined in

[ue/ue.d.ts:5411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5411)

___

### GetPlaneConstraintOrigin

▸ **GetPlaneConstraintOrigin**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetPlaneConstraintOrigin](ue_ue.CharacterMovementComponent.md#getplaneconstraintorigin)

#### Defined in

[ue/ue.d.ts:5412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5412)

___

### GetValidPerchRadius

▸ **GetValidPerchRadius**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetValidPerchRadius](ue_ue.CharacterMovementComponent.md#getvalidperchradius)

#### Defined in

[ue/ue.d.ts:5805](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5805)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[GetWorld](ue_ue.CharacterMovementComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsActive](ue_ue.CharacterMovementComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsBeingDestroyed](ue_ue.CharacterMovementComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsComponentTickEnabled](ue_ue.CharacterMovementComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L315)

___

### IsCrouching

▸ **IsCrouching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsCrouching](ue_ue.CharacterMovementComponent.md#iscrouching)

#### Defined in

[ue/ue.d.ts:5474](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5474)

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

#### Defined in

[ue/ue.d.ts:5413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5413)

___

### IsFalling

▸ **IsFalling**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsFalling](ue_ue.CharacterMovementComponent.md#isfalling)

#### Defined in

[ue/ue.d.ts:5475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5475)

___

### IsFlying

▸ **IsFlying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsFlying](ue_ue.CharacterMovementComponent.md#isflying)

#### Defined in

[ue/ue.d.ts:5476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5476)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsMoveInputIgnored](ue_ue.CharacterMovementComponent.md#ismoveinputignored)

#### Defined in

[ue/ue.d.ts:5496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5496)

___

### IsMovingOnGround

▸ **IsMovingOnGround**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsMovingOnGround](ue_ue.CharacterMovementComponent.md#ismovingonground)

#### Defined in

[ue/ue.d.ts:5477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5477)

___

### IsSwimming

▸ **IsSwimming**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsSwimming](ue_ue.CharacterMovementComponent.md#isswimming)

#### Defined in

[ue/ue.d.ts:5478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5478)

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

#### Defined in

[ue/ue.d.ts:5806](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5806)

___

### IsWalking

▸ **IsWalking**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[IsWalking](ue_ue.CharacterMovementComponent.md#iswalking)

#### Defined in

[ue/ue.d.ts:5807](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5807)

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

#### Defined in

[ue/ue.d.ts:5808](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5808)

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

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L316)

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

#### Defined in

[ue/ue.d.ts:5809](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5809)

___

### K2\_GetInputVector

▸ **K2_GetInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_GetInputVector](ue_ue.CharacterMovementComponent.md#k2_getinputvector)

#### Defined in

[ue/ue.d.ts:5497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5497)

___

### K2\_GetMaxSpeedModifier

▸ **K2_GetMaxSpeedModifier**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_GetMaxSpeedModifier](ue_ue.CharacterMovementComponent.md#k2_getmaxspeedmodifier)

#### Defined in

[ue/ue.d.ts:5414](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5414)

___

### K2\_GetModifiedMaxAcceleration

▸ **K2_GetModifiedMaxAcceleration**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_GetModifiedMaxAcceleration](ue_ue.CharacterMovementComponent.md#k2_getmodifiedmaxacceleration)

#### Defined in

[ue/ue.d.ts:5810](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5810)

___

### K2\_GetModifiedMaxSpeed

▸ **K2_GetModifiedMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_GetModifiedMaxSpeed](ue_ue.CharacterMovementComponent.md#k2_getmodifiedmaxspeed)

#### Defined in

[ue/ue.d.ts:5415](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5415)

___

### K2\_GetWalkableFloorAngle

▸ **K2_GetWalkableFloorAngle**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_GetWalkableFloorAngle](ue_ue.CharacterMovementComponent.md#k2_getwalkablefloorangle)

#### Defined in

[ue/ue.d.ts:5811](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5811)

___

### K2\_GetWalkableFloorZ

▸ **K2_GetWalkableFloorZ**(): `number`

#### Returns

`number`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[K2_GetWalkableFloorZ](ue_ue.CharacterMovementComponent.md#k2_getwalkablefloorz)

#### Defined in

[ue/ue.d.ts:5812](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5812)

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

#### Defined in

[ue/ue.d.ts:5416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5416)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[OnRep_IsActive](ue_ue.CharacterMovementComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L317)

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

#### Defined in

[ue/ue.d.ts:5417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5417)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ReceiveBeginPlay](ue_ue.CharacterMovementComponent.md#receivebeginplay)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ReceiveEndPlay](ue_ue.CharacterMovementComponent.md#receiveendplay)

#### Defined in

[ue/ue.d.ts:319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L319)

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

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RegisterComponent](ue_ue.CharacterMovementComponent.md#registercomponent)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RemoveTickPrerequisiteActor](ue_ue.CharacterMovementComponent.md#removetickprerequisiteactor)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.CharacterMovementComponent.md#removetickprerequisitecomponent)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetActive](ue_ue.CharacterMovementComponent.md#setactive)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetAutoActivate](ue_ue.CharacterMovementComponent.md#setautoactivate)

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L325)

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

#### Defined in

[ue/ue.d.ts:5813](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5813)

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

#### Defined in

[ue/ue.d.ts:5814](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5814)

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

#### Defined in

[ue/ue.d.ts:5815](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5815)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetComponentTickInterval](ue_ue.CharacterMovementComponent.md#setcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L327)

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

#### Defined in

[ue/ue.d.ts:5816](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5816)

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

#### Defined in

[ue/ue.d.ts:5817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5817)

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

#### Defined in

[ue/ue.d.ts:5818](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5818)

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

#### Defined in

[ue/ue.d.ts:5819](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5819)

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

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L328)

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

#### Defined in

[ue/ue.d.ts:5820](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5820)

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

#### Defined in

[ue/ue.d.ts:5418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5418)

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

#### Defined in

[ue/ue.d.ts:5419](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5419)

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

#### Defined in

[ue/ue.d.ts:5420](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5420)

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

#### Defined in

[ue/ue.d.ts:5421](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5421)

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

#### Defined in

[ue/ue.d.ts:5422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5422)

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

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SetTickableWhenPaused](ue_ue.CharacterMovementComponent.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L329)

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

#### Defined in

[ue/ue.d.ts:5423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5423)

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

#### Defined in

[ue/ue.d.ts:5821](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5821)

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

#### Defined in

[ue/ue.d.ts:5822](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5822)

___

### SnapUpdatedComponentToPlane

▸ **SnapUpdatedComponentToPlane**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[SnapUpdatedComponentToPlane](ue_ue.CharacterMovementComponent.md#snapupdatedcomponenttoplane)

#### Defined in

[ue/ue.d.ts:5424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5424)

___

### StopActiveMovement

▸ **StopActiveMovement**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[StopActiveMovement](ue_ue.CharacterMovementComponent.md#stopactivemovement)

#### Defined in

[ue/ue.d.ts:5479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5479)

___

### StopMovementImmediately

▸ **StopMovementImmediately**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[StopMovementImmediately](ue_ue.CharacterMovementComponent.md#stopmovementimmediately)

#### Defined in

[ue/ue.d.ts:5425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5425)

___

### StopMovementKeepPathing

▸ **StopMovementKeepPathing**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[StopMovementKeepPathing](ue_ue.CharacterMovementComponent.md#stopmovementkeeppathing)

#### Defined in

[ue/ue.d.ts:5480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5480)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[ToggleActive](ue_ue.CharacterMovementComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L331)

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

#### Defined in

[ue/ue.d.ts:21171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21171)

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

#### Defined in

[ue/ue.d.ts:21172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21172)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[CharacterMovementComponent](ue_ue.CharacterMovementComponent.md).[StaticClass](ue_ue.CharacterMovementComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:21170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21170)
