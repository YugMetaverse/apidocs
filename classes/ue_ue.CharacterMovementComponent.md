[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CharacterMovementComponent

# Class: CharacterMovementComponent

[ue/ue](../modules/ue_ue.md).CharacterMovementComponent

## Hierarchy

- [`PawnMovementComponent`](ue_ue.PawnMovementComponent.md)

  ↳ **`CharacterMovementComponent`**

  ↳↳ [`ArchVisCharMovementComponent`](ue_ue.ArchVisCharMovementComponent.md)

## Table of contents

### Constructors

- [constructor](ue_ue.CharacterMovementComponent.md#constructor)

### Properties

- [Acceleration](ue_ue.CharacterMovementComponent.md#acceleration)
- [AirControl](ue_ue.CharacterMovementComponent.md#aircontrol)
- [AirControlBoostMultiplier](ue_ue.CharacterMovementComponent.md#aircontrolboostmultiplier)
- [AirControlBoostVelocityThreshold](ue_ue.CharacterMovementComponent.md#aircontrolboostvelocitythreshold)
- [AnalogInputModifier](ue_ue.CharacterMovementComponent.md#analoginputmodifier)
- [AnimRootMotionVelocity](ue_ue.CharacterMovementComponent.md#animrootmotionvelocity)
- [AssetUserData](ue_ue.CharacterMovementComponent.md#assetuserdata)
- [AvoidanceConsiderationRadius](ue_ue.CharacterMovementComponent.md#avoidanceconsiderationradius)
- [AvoidanceGroup](ue_ue.CharacterMovementComponent.md#avoidancegroup)
- [AvoidanceUID](ue_ue.CharacterMovementComponent.md#avoidanceuid)
- [AvoidanceWeight](ue_ue.CharacterMovementComponent.md#avoidanceweight)
- [BrakingDecelerationFalling](ue_ue.CharacterMovementComponent.md#brakingdecelerationfalling)
- [BrakingDecelerationFlying](ue_ue.CharacterMovementComponent.md#brakingdecelerationflying)
- [BrakingDecelerationSwimming](ue_ue.CharacterMovementComponent.md#brakingdecelerationswimming)
- [BrakingDecelerationWalking](ue_ue.CharacterMovementComponent.md#brakingdecelerationwalking)
- [BrakingFriction](ue_ue.CharacterMovementComponent.md#brakingfriction)
- [BrakingFrictionFactor](ue_ue.CharacterMovementComponent.md#brakingfrictionfactor)
- [BrakingSubStepTime](ue_ue.CharacterMovementComponent.md#brakingsubsteptime)
- [Buoyancy](ue_ue.CharacterMovementComponent.md#buoyancy)
- [CharacterOwner](ue_ue.CharacterMovementComponent.md#characterowner)
- [ComponentTags](ue_ue.CharacterMovementComponent.md#componenttags)
- [CreationMethod](ue_ue.CharacterMovementComponent.md#creationmethod)
- [CrouchedHalfHeight](ue_ue.CharacterMovementComponent.md#crouchedhalfheight)
- [CrouchedSpeedMultiplier](ue_ue.CharacterMovementComponent.md#crouchedspeedmultiplier)
- [CurrentFloor](ue_ue.CharacterMovementComponent.md#currentfloor)
- [CurrentRootMotion](ue_ue.CharacterMovementComponent.md#currentrootmotion)
- [CustomMovementMode](ue_ue.CharacterMovementComponent.md#custommovementmode)
- [DefaultLandMovementMode](ue_ue.CharacterMovementComponent.md#defaultlandmovementmode)
- [DefaultWaterMovementMode](ue_ue.CharacterMovementComponent.md#defaultwatermovementmode)
- [DeferredUpdatedMoveComponent](ue_ue.CharacterMovementComponent.md#deferredupdatedmovecomponent)
- [FallingLateralFriction](ue_ue.CharacterMovementComponent.md#fallinglateralfriction)
- [FixedPathBrakingDistance](ue_ue.CharacterMovementComponent.md#fixedpathbrakingdistance)
- [GravityScale](ue_ue.CharacterMovementComponent.md#gravityscale)
- [GroundFriction](ue_ue.CharacterMovementComponent.md#groundfriction)
- [GroundMovementMode](ue_ue.CharacterMovementComponent.md#groundmovementmode)
- [GroupsToAvoid](ue_ue.CharacterMovementComponent.md#groupstoavoid)
- [GroupsToIgnore](ue_ue.CharacterMovementComponent.md#groupstoignore)
- [InitialPushForceFactor](ue_ue.CharacterMovementComponent.md#initialpushforcefactor)
- [JumpOffJumpZFactor](ue_ue.CharacterMovementComponent.md#jumpoffjumpzfactor)
- [JumpOutOfWaterPitch](ue_ue.CharacterMovementComponent.md#jumpoutofwaterpitch)
- [JumpZVelocity](ue_ue.CharacterMovementComponent.md#jumpzvelocity)
- [LastUpdateLocation](ue_ue.CharacterMovementComponent.md#lastupdatelocation)
- [LastUpdateRotation](ue_ue.CharacterMovementComponent.md#lastupdaterotation)
- [LastUpdateVelocity](ue_ue.CharacterMovementComponent.md#lastupdatevelocity)
- [LedgeCheckThreshold](ue_ue.CharacterMovementComponent.md#ledgecheckthreshold)
- [ListenServerNetworkSimulatedSmoothLocationTime](ue_ue.CharacterMovementComponent.md#listenservernetworksimulatedsmoothlocationtime)
- [ListenServerNetworkSimulatedSmoothRotationTime](ue_ue.CharacterMovementComponent.md#listenservernetworksimulatedsmoothrotationtime)
- [Mass](ue_ue.CharacterMovementComponent.md#mass)
- [MaxAcceleration](ue_ue.CharacterMovementComponent.md#maxacceleration)
- [MaxCustomMovementSpeed](ue_ue.CharacterMovementComponent.md#maxcustommovementspeed)
- [MaxDepenetrationWithGeometry](ue_ue.CharacterMovementComponent.md#maxdepenetrationwithgeometry)
- [MaxDepenetrationWithGeometryAsProxy](ue_ue.CharacterMovementComponent.md#maxdepenetrationwithgeometryasproxy)
- [MaxDepenetrationWithPawn](ue_ue.CharacterMovementComponent.md#maxdepenetrationwithpawn)
- [MaxDepenetrationWithPawnAsProxy](ue_ue.CharacterMovementComponent.md#maxdepenetrationwithpawnasproxy)
- [MaxFlySpeed](ue_ue.CharacterMovementComponent.md#maxflyspeed)
- [MaxJumpApexAttemptsPerSimulation](ue_ue.CharacterMovementComponent.md#maxjumpapexattemptspersimulation)
- [MaxOutOfWaterStepHeight](ue_ue.CharacterMovementComponent.md#maxoutofwaterstepheight)
- [MaxSimulationIterations](ue_ue.CharacterMovementComponent.md#maxsimulationiterations)
- [MaxSimulationTimeStep](ue_ue.CharacterMovementComponent.md#maxsimulationtimestep)
- [MaxStepHeight](ue_ue.CharacterMovementComponent.md#maxstepheight)
- [MaxSwimSpeed](ue_ue.CharacterMovementComponent.md#maxswimspeed)
- [MaxTouchForce](ue_ue.CharacterMovementComponent.md#maxtouchforce)
- [MaxWalkSpeed](ue_ue.CharacterMovementComponent.md#maxwalkspeed)
- [MaxWalkSpeedCrouched](ue_ue.CharacterMovementComponent.md#maxwalkspeedcrouched)
- [MinAnalogWalkSpeed](ue_ue.CharacterMovementComponent.md#minanalogwalkspeed)
- [MinTimeBetweenTimeStampResets](ue_ue.CharacterMovementComponent.md#mintimebetweentimestampresets)
- [MinTouchForce](ue_ue.CharacterMovementComponent.md#mintouchforce)
- [MovementMode](ue_ue.CharacterMovementComponent.md#movementmode)
- [MovementState](ue_ue.CharacterMovementComponent.md#movementstate)
- [NavAgentProps](ue_ue.CharacterMovementComponent.md#navagentprops)
- [NavMeshProjectionHeightScaleDown](ue_ue.CharacterMovementComponent.md#navmeshprojectionheightscaledown)
- [NavMeshProjectionHeightScaleUp](ue_ue.CharacterMovementComponent.md#navmeshprojectionheightscaleup)
- [NavMeshProjectionInterpSpeed](ue_ue.CharacterMovementComponent.md#navmeshprojectioninterpspeed)
- [NavMeshProjectionInterval](ue_ue.CharacterMovementComponent.md#navmeshprojectioninterval)
- [NavMeshProjectionTimer](ue_ue.CharacterMovementComponent.md#navmeshprojectiontimer)
- [NavWalkingFloorDistTolerance](ue_ue.CharacterMovementComponent.md#navwalkingfloordisttolerance)
- [NetProxyShrinkHalfHeight](ue_ue.CharacterMovementComponent.md#netproxyshrinkhalfheight)
- [NetProxyShrinkRadius](ue_ue.CharacterMovementComponent.md#netproxyshrinkradius)
- [NetworkLargeClientCorrectionDistance](ue_ue.CharacterMovementComponent.md#networklargeclientcorrectiondistance)
- [NetworkMaxSmoothUpdateDistance](ue_ue.CharacterMovementComponent.md#networkmaxsmoothupdatedistance)
- [NetworkMinTimeBetweenClientAckGoodMoves](ue_ue.CharacterMovementComponent.md#networkmintimebetweenclientackgoodmoves)
- [NetworkMinTimeBetweenClientAdjustments](ue_ue.CharacterMovementComponent.md#networkmintimebetweenclientadjustments)
- [NetworkMinTimeBetweenClientAdjustmentsLargeCorrection](ue_ue.CharacterMovementComponent.md#networkmintimebetweenclientadjustmentslargecorrection)
- [NetworkNoSmoothUpdateDistance](ue_ue.CharacterMovementComponent.md#networknosmoothupdatedistance)
- [NetworkSimulatedSmoothLocationTime](ue_ue.CharacterMovementComponent.md#networksimulatedsmoothlocationtime)
- [NetworkSimulatedSmoothRotationTime](ue_ue.CharacterMovementComponent.md#networksimulatedsmoothrotationtime)
- [NetworkSmoothingMode](ue_ue.CharacterMovementComponent.md#networksmoothingmode)
- [OnComponentActivated](ue_ue.CharacterMovementComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.CharacterMovementComponent.md#oncomponentdeactivated)
- [OutofWaterZ](ue_ue.CharacterMovementComponent.md#outofwaterz)
- [PathFollowingComp](ue_ue.CharacterMovementComponent.md#pathfollowingcomp)
- [PawnOwner](ue_ue.CharacterMovementComponent.md#pawnowner)
- [PendingForceToApply](ue_ue.CharacterMovementComponent.md#pendingforcetoapply)
- [PendingImpulseToApply](ue_ue.CharacterMovementComponent.md#pendingimpulsetoapply)
- [PendingLaunchVelocity](ue_ue.CharacterMovementComponent.md#pendinglaunchvelocity)
- [PerchAdditionalHeight](ue_ue.CharacterMovementComponent.md#perchadditionalheight)
- [PerchRadiusThreshold](ue_ue.CharacterMovementComponent.md#perchradiusthreshold)
- [PlaneConstraintAxisSetting](ue_ue.CharacterMovementComponent.md#planeconstraintaxissetting)
- [PlaneConstraintNormal](ue_ue.CharacterMovementComponent.md#planeconstraintnormal)
- [PlaneConstraintOrigin](ue_ue.CharacterMovementComponent.md#planeconstraintorigin)
- [PostPhysicsTickFunction](ue_ue.CharacterMovementComponent.md#postphysicstickfunction)
- [PrimaryComponentTick](ue_ue.CharacterMovementComponent.md#primarycomponenttick)
- [PushForceFactor](ue_ue.CharacterMovementComponent.md#pushforcefactor)
- [PushForcePointZOffsetFactor](ue_ue.CharacterMovementComponent.md#pushforcepointzoffsetfactor)
- [RepulsionForce](ue_ue.CharacterMovementComponent.md#repulsionforce)
- [RequestedVelocity](ue_ue.CharacterMovementComponent.md#requestedvelocity)
- [RootMotionParams](ue_ue.CharacterMovementComponent.md#rootmotionparams)
- [RotationRate](ue_ue.CharacterMovementComponent.md#rotationrate)
- [ServerLastClientAdjustmentTime](ue_ue.CharacterMovementComponent.md#serverlastclientadjustmenttime)
- [ServerLastClientGoodMoveAckTime](ue_ue.CharacterMovementComponent.md#serverlastclientgoodmoveacktime)
- [ServerLastTransformUpdateTimeStamp](ue_ue.CharacterMovementComponent.md#serverlasttransformupdatetimestamp)
- [StandingDownwardForceScale](ue_ue.CharacterMovementComponent.md#standingdownwardforcescale)
- [TouchForceFactor](ue_ue.CharacterMovementComponent.md#touchforcefactor)
- [UCSModifiedProperties](ue_ue.CharacterMovementComponent.md#ucsmodifiedproperties)
- [UpdatedComponent](ue_ue.CharacterMovementComponent.md#updatedcomponent)
- [UpdatedPrimitive](ue_ue.CharacterMovementComponent.md#updatedprimitive)
- [UpperImpactNormalScale](ue_ue.CharacterMovementComponent.md#upperimpactnormalscale)
- [Velocity](ue_ue.CharacterMovementComponent.md#velocity)
- [WalkableFloorAngle](ue_ue.CharacterMovementComponent.md#walkablefloorangle)
- [WalkableFloorZ](ue_ue.CharacterMovementComponent.md#walkablefloorz)
- [\_\_tid\_ActorComponent\_\_](ue_ue.CharacterMovementComponent.md#__tid_actorcomponent__)
- [\_\_tid\_CharacterMovementComponent\_\_](ue_ue.CharacterMovementComponent.md#__tid_charactermovementcomponent__)
- [\_\_tid\_MovementComponent\_\_](ue_ue.CharacterMovementComponent.md#__tid_movementcomponent__)
- [\_\_tid\_NavMovementComponent\_\_](ue_ue.CharacterMovementComponent.md#__tid_navmovementcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.CharacterMovementComponent.md#__tid_object__)
- [\_\_tid\_PawnMovementComponent\_\_](ue_ue.CharacterMovementComponent.md#__tid_pawnmovementcomponent__)
- [bAllowPhysicsRotationDuringAnimRootMotion](ue_ue.CharacterMovementComponent.md#ballowphysicsrotationduringanimrootmotion)
- [bAlwaysCheckFloor](ue_ue.CharacterMovementComponent.md#balwayscheckfloor)
- [bApplyGravityWhileJumping](ue_ue.CharacterMovementComponent.md#bapplygravitywhilejumping)
- [bAutoActivate](ue_ue.CharacterMovementComponent.md#bautoactivate)
- [bAutoRegisterPhysicsVolumeUpdates](ue_ue.CharacterMovementComponent.md#bautoregisterphysicsvolumeupdates)
- [bAutoRegisterUpdatedComponent](ue_ue.CharacterMovementComponent.md#bautoregisterupdatedcomponent)
- [bAutoUpdateTickRegistration](ue_ue.CharacterMovementComponent.md#bautoupdatetickregistration)
- [bCanEverAffectNavigation](ue_ue.CharacterMovementComponent.md#bcaneveraffectnavigation)
- [bCanWalkOffLedges](ue_ue.CharacterMovementComponent.md#bcanwalkoffledges)
- [bCanWalkOffLedgesWhenCrouching](ue_ue.CharacterMovementComponent.md#bcanwalkoffledgeswhencrouching)
- [bCheatFlying](ue_ue.CharacterMovementComponent.md#bcheatflying)
- [bComponentShouldUpdatePhysicsVolume](ue_ue.CharacterMovementComponent.md#bcomponentshouldupdatephysicsvolume)
- [bConstrainToPlane](ue_ue.CharacterMovementComponent.md#bconstraintoplane)
- [bCreatedByConstructionScript](ue_ue.CharacterMovementComponent.md#bcreatedbyconstructionscript)
- [bCrouchMaintainsBaseLocation](ue_ue.CharacterMovementComponent.md#bcrouchmaintainsbaselocation)
- [bDeferUpdateMoveComponent](ue_ue.CharacterMovementComponent.md#bdeferupdatemovecomponent)
- [bEditableWhenInherited](ue_ue.CharacterMovementComponent.md#beditablewheninherited)
- [bEnablePhysicsInteraction](ue_ue.CharacterMovementComponent.md#benablephysicsinteraction)
- [bEnableScopedMovementUpdates](ue_ue.CharacterMovementComponent.md#benablescopedmovementupdates)
- [bEnableServerDualMoveScopedMovementUpdates](ue_ue.CharacterMovementComponent.md#benableserverdualmovescopedmovementupdates)
- [bFastAttachedMove](ue_ue.CharacterMovementComponent.md#bfastattachedmove)
- [bForceBraking](ue_ue.CharacterMovementComponent.md#bforcebraking)
- [bForceMaxAccel](ue_ue.CharacterMovementComponent.md#bforcemaxaccel)
- [bForceNextFloorCheck](ue_ue.CharacterMovementComponent.md#bforcenextfloorcheck)
- [bHasRequestedVelocity](ue_ue.CharacterMovementComponent.md#bhasrequestedvelocity)
- [bIgnoreBaseRotation](ue_ue.CharacterMovementComponent.md#bignorebaserotation)
- [bIgnoreClientMovementErrorChecksAndCorrection](ue_ue.CharacterMovementComponent.md#bignoreclientmovementerrorchecksandcorrection)
- [bImpartBaseAngularVelocity](ue_ue.CharacterMovementComponent.md#bimpartbaseangularvelocity)
- [bImpartBaseVelocityX](ue_ue.CharacterMovementComponent.md#bimpartbasevelocityx)
- [bImpartBaseVelocityY](ue_ue.CharacterMovementComponent.md#bimpartbasevelocityy)
- [bImpartBaseVelocityZ](ue_ue.CharacterMovementComponent.md#bimpartbasevelocityz)
- [bInstanceComponent](ue_ue.CharacterMovementComponent.md#binstancecomponent)
- [bIsActive](ue_ue.CharacterMovementComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.CharacterMovementComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.CharacterMovementComponent.md#bisvisualizationcomponent)
- [bJustTeleported](ue_ue.CharacterMovementComponent.md#bjustteleported)
- [bMaintainHorizontalGroundVelocity](ue_ue.CharacterMovementComponent.md#bmaintainhorizontalgroundvelocity)
- [bMovementInProgress](ue_ue.CharacterMovementComponent.md#bmovementinprogress)
- [bNetAddressable](ue_ue.CharacterMovementComponent.md#bnetaddressable)
- [bNetworkAlwaysReplicateTransformUpdateTimestamp](ue_ue.CharacterMovementComponent.md#bnetworkalwaysreplicatetransformupdatetimestamp)
- [bNetworkMovementModeChanged](ue_ue.CharacterMovementComponent.md#bnetworkmovementmodechanged)
- [bNetworkSkipProxyPredictionOnNetUpdate](ue_ue.CharacterMovementComponent.md#bnetworkskipproxypredictiononnetupdate)
- [bNetworkUpdateReceived](ue_ue.CharacterMovementComponent.md#bnetworkupdatereceived)
- [bNotifyApex](ue_ue.CharacterMovementComponent.md#bnotifyapex)
- [bOrientRotationToMovement](ue_ue.CharacterMovementComponent.md#borientrotationtomovement)
- [bPerformingJumpOff](ue_ue.CharacterMovementComponent.md#bperformingjumpoff)
- [bProjectNavMeshOnBothWorldChannels](ue_ue.CharacterMovementComponent.md#bprojectnavmeshonbothworldchannels)
- [bProjectNavMeshWalking](ue_ue.CharacterMovementComponent.md#bprojectnavmeshwalking)
- [bPushForceScaledToMass](ue_ue.CharacterMovementComponent.md#bpushforcescaledtomass)
- [bPushForceUsingZOffset](ue_ue.CharacterMovementComponent.md#bpushforceusingzoffset)
- [bReplicates](ue_ue.CharacterMovementComponent.md#breplicates)
- [bRequestedMoveUseAcceleration](ue_ue.CharacterMovementComponent.md#brequestedmoveuseacceleration)
- [bRequestedMoveWithMaxSpeed](ue_ue.CharacterMovementComponent.md#brequestedmovewithmaxspeed)
- [bRunPhysicsWithNoController](ue_ue.CharacterMovementComponent.md#brunphysicswithnocontroller)
- [bScalePushForceToVelocity](ue_ue.CharacterMovementComponent.md#bscalepushforcetovelocity)
- [bServerAcceptClientAuthoritativePosition](ue_ue.CharacterMovementComponent.md#bserveracceptclientauthoritativeposition)
- [bShrinkProxyCapsule](ue_ue.CharacterMovementComponent.md#bshrinkproxycapsule)
- [bSnapToPlaneAtStart](ue_ue.CharacterMovementComponent.md#bsnaptoplaneatstart)
- [bSweepWhileNavWalking](ue_ue.CharacterMovementComponent.md#bsweepwhilenavwalking)
- [bTickBeforeOwner](ue_ue.CharacterMovementComponent.md#btickbeforeowner)
- [bTouchForceScaledToMass](ue_ue.CharacterMovementComponent.md#btouchforcescaledtomass)
- [bUpdateNavAgentWithOwnersCollision](ue_ue.CharacterMovementComponent.md#bupdatenavagentwithownerscollision)
- [bUpdateOnlyIfRendered](ue_ue.CharacterMovementComponent.md#bupdateonlyifrendered)
- [bUseAccelerationForPaths](ue_ue.CharacterMovementComponent.md#buseaccelerationforpaths)
- [bUseControllerDesiredRotation](ue_ue.CharacterMovementComponent.md#busecontrollerdesiredrotation)
- [bUseFixedBrakingDistanceForPaths](ue_ue.CharacterMovementComponent.md#busefixedbrakingdistanceforpaths)
- [bUseFlatBaseForFloorChecks](ue_ue.CharacterMovementComponent.md#buseflatbaseforfloorchecks)
- [bUseRVOAvoidance](ue_ue.CharacterMovementComponent.md#buservoavoidance)
- [bUseSeparateBrakingFriction](ue_ue.CharacterMovementComponent.md#buseseparatebrakingfriction)
- [bWantsToCrouch](ue_ue.CharacterMovementComponent.md#bwantstocrouch)
- [bWantsToLeaveNavWalking](ue_ue.CharacterMovementComponent.md#bwantstoleavenavwalking)
- [bWasAvoidanceUpdated](ue_ue.CharacterMovementComponent.md#bwasavoidanceupdated)
- [bWasSimulatingRootMotion](ue_ue.CharacterMovementComponent.md#bwassimulatingrootmotion)

### Methods

- [Activate](ue_ue.CharacterMovementComponent.md#activate)
- [AddForce](ue_ue.CharacterMovementComponent.md#addforce)
- [AddImpulse](ue_ue.CharacterMovementComponent.md#addimpulse)
- [AddInputVector](ue_ue.CharacterMovementComponent.md#addinputvector)
- [AddTickPrerequisiteActor](ue_ue.CharacterMovementComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.CharacterMovementComponent.md#addtickprerequisitecomponent)
- [CalcVelocity](ue_ue.CharacterMovementComponent.md#calcvelocity)
- [CapsuleTouched](ue_ue.CharacterMovementComponent.md#capsuletouched)
- [ClearAccumulatedForces](ue_ue.CharacterMovementComponent.md#clearaccumulatedforces)
- [ComponentHasTag](ue_ue.CharacterMovementComponent.md#componenthastag)
- [ConstrainDirectionToPlane](ue_ue.CharacterMovementComponent.md#constraindirectiontoplane)
- [ConstrainLocationToPlane](ue_ue.CharacterMovementComponent.md#constrainlocationtoplane)
- [ConstrainNormalToPlane](ue_ue.CharacterMovementComponent.md#constrainnormaltoplane)
- [ConsumeInputVector](ue_ue.CharacterMovementComponent.md#consumeinputvector)
- [CreateDefaultSubobject](ue_ue.CharacterMovementComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.CharacterMovementComponent.md#deactivate)
- [DisableMovement](ue_ue.CharacterMovementComponent.md#disablemovement)
- [ExecuteUbergraph](ue_ue.CharacterMovementComponent.md#executeubergraph)
- [GetAnalogInputModifier](ue_ue.CharacterMovementComponent.md#getanaloginputmodifier)
- [GetCharacterOwner](ue_ue.CharacterMovementComponent.md#getcharacterowner)
- [GetClass](ue_ue.CharacterMovementComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.CharacterMovementComponent.md#getcomponenttickinterval)
- [GetCurrentAcceleration](ue_ue.CharacterMovementComponent.md#getcurrentacceleration)
- [GetGravityZ](ue_ue.CharacterMovementComponent.md#getgravityz)
- [GetImpartedMovementBaseVelocity](ue_ue.CharacterMovementComponent.md#getimpartedmovementbasevelocity)
- [GetLastInputVector](ue_ue.CharacterMovementComponent.md#getlastinputvector)
- [GetLastUpdateLocation](ue_ue.CharacterMovementComponent.md#getlastupdatelocation)
- [GetLastUpdateRotation](ue_ue.CharacterMovementComponent.md#getlastupdaterotation)
- [GetLastUpdateVelocity](ue_ue.CharacterMovementComponent.md#getlastupdatevelocity)
- [GetMaxAcceleration](ue_ue.CharacterMovementComponent.md#getmaxacceleration)
- [GetMaxBrakingDeceleration](ue_ue.CharacterMovementComponent.md#getmaxbrakingdeceleration)
- [GetMaxJumpHeight](ue_ue.CharacterMovementComponent.md#getmaxjumpheight)
- [GetMaxJumpHeightWithJumpTime](ue_ue.CharacterMovementComponent.md#getmaxjumpheightwithjumptime)
- [GetMaxSpeed](ue_ue.CharacterMovementComponent.md#getmaxspeed)
- [GetMinAnalogSpeed](ue_ue.CharacterMovementComponent.md#getminanalogspeed)
- [GetMovementBase](ue_ue.CharacterMovementComponent.md#getmovementbase)
- [GetName](ue_ue.CharacterMovementComponent.md#getname)
- [GetOuter](ue_ue.CharacterMovementComponent.md#getouter)
- [GetOwner](ue_ue.CharacterMovementComponent.md#getowner)
- [GetPawnOwner](ue_ue.CharacterMovementComponent.md#getpawnowner)
- [GetPendingInputVector](ue_ue.CharacterMovementComponent.md#getpendinginputvector)
- [GetPerchRadiusThreshold](ue_ue.CharacterMovementComponent.md#getperchradiusthreshold)
- [GetPhysicsVolume](ue_ue.CharacterMovementComponent.md#getphysicsvolume)
- [GetPlaneConstraintAxisSetting](ue_ue.CharacterMovementComponent.md#getplaneconstraintaxissetting)
- [GetPlaneConstraintNormal](ue_ue.CharacterMovementComponent.md#getplaneconstraintnormal)
- [GetPlaneConstraintOrigin](ue_ue.CharacterMovementComponent.md#getplaneconstraintorigin)
- [GetValidPerchRadius](ue_ue.CharacterMovementComponent.md#getvalidperchradius)
- [GetWorld](ue_ue.CharacterMovementComponent.md#getworld)
- [IsActive](ue_ue.CharacterMovementComponent.md#isactive)
- [IsBeingDestroyed](ue_ue.CharacterMovementComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.CharacterMovementComponent.md#iscomponenttickenabled)
- [IsCrouching](ue_ue.CharacterMovementComponent.md#iscrouching)
- [IsExceedingMaxSpeed](ue_ue.CharacterMovementComponent.md#isexceedingmaxspeed)
- [IsFalling](ue_ue.CharacterMovementComponent.md#isfalling)
- [IsFlying](ue_ue.CharacterMovementComponent.md#isflying)
- [IsMoveInputIgnored](ue_ue.CharacterMovementComponent.md#ismoveinputignored)
- [IsMovingOnGround](ue_ue.CharacterMovementComponent.md#ismovingonground)
- [IsSwimming](ue_ue.CharacterMovementComponent.md#isswimming)
- [IsWalkable](ue_ue.CharacterMovementComponent.md#iswalkable)
- [IsWalking](ue_ue.CharacterMovementComponent.md#iswalking)
- [K2\_ComputeFloorDist](ue_ue.CharacterMovementComponent.md#k2_computefloordist)
- [K2\_DestroyComponent](ue_ue.CharacterMovementComponent.md#k2_destroycomponent)
- [K2\_FindFloor](ue_ue.CharacterMovementComponent.md#k2_findfloor)
- [K2\_GetInputVector](ue_ue.CharacterMovementComponent.md#k2_getinputvector)
- [K2\_GetMaxSpeedModifier](ue_ue.CharacterMovementComponent.md#k2_getmaxspeedmodifier)
- [K2\_GetModifiedMaxAcceleration](ue_ue.CharacterMovementComponent.md#k2_getmodifiedmaxacceleration)
- [K2\_GetModifiedMaxSpeed](ue_ue.CharacterMovementComponent.md#k2_getmodifiedmaxspeed)
- [K2\_GetWalkableFloorAngle](ue_ue.CharacterMovementComponent.md#k2_getwalkablefloorangle)
- [K2\_GetWalkableFloorZ](ue_ue.CharacterMovementComponent.md#k2_getwalkablefloorz)
- [K2\_MoveUpdatedComponent](ue_ue.CharacterMovementComponent.md#k2_moveupdatedcomponent)
- [OnRep\_IsActive](ue_ue.CharacterMovementComponent.md#onrep_isactive)
- [PhysicsVolumeChanged](ue_ue.CharacterMovementComponent.md#physicsvolumechanged)
- [ReceiveBeginPlay](ue_ue.CharacterMovementComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.CharacterMovementComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.CharacterMovementComponent.md#receivetick)
- [RegisterComponent](ue_ue.CharacterMovementComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.CharacterMovementComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.CharacterMovementComponent.md#removetickprerequisitecomponent)
- [SetActive](ue_ue.CharacterMovementComponent.md#setactive)
- [SetAutoActivate](ue_ue.CharacterMovementComponent.md#setautoactivate)
- [SetAvoidanceEnabled](ue_ue.CharacterMovementComponent.md#setavoidanceenabled)
- [SetAvoidanceGroup](ue_ue.CharacterMovementComponent.md#setavoidancegroup)
- [SetAvoidanceGroupMask](ue_ue.CharacterMovementComponent.md#setavoidancegroupmask)
- [SetComponentTickEnabled](ue_ue.CharacterMovementComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.CharacterMovementComponent.md#setcomponenttickinterval)
- [SetGroupsToAvoid](ue_ue.CharacterMovementComponent.md#setgroupstoavoid)
- [SetGroupsToAvoidMask](ue_ue.CharacterMovementComponent.md#setgroupstoavoidmask)
- [SetGroupsToIgnore](ue_ue.CharacterMovementComponent.md#setgroupstoignore)
- [SetGroupsToIgnoreMask](ue_ue.CharacterMovementComponent.md#setgroupstoignoremask)
- [SetIsReplicated](ue_ue.CharacterMovementComponent.md#setisreplicated)
- [SetMovementMode](ue_ue.CharacterMovementComponent.md#setmovementmode)
- [SetPlaneConstraintAxisSetting](ue_ue.CharacterMovementComponent.md#setplaneconstraintaxissetting)
- [SetPlaneConstraintEnabled](ue_ue.CharacterMovementComponent.md#setplaneconstraintenabled)
- [SetPlaneConstraintFromVectors](ue_ue.CharacterMovementComponent.md#setplaneconstraintfromvectors)
- [SetPlaneConstraintNormal](ue_ue.CharacterMovementComponent.md#setplaneconstraintnormal)
- [SetPlaneConstraintOrigin](ue_ue.CharacterMovementComponent.md#setplaneconstraintorigin)
- [SetTickGroup](ue_ue.CharacterMovementComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.CharacterMovementComponent.md#settickablewhenpaused)
- [SetUpdatedComponent](ue_ue.CharacterMovementComponent.md#setupdatedcomponent)
- [SetWalkableFloorAngle](ue_ue.CharacterMovementComponent.md#setwalkablefloorangle)
- [SetWalkableFloorZ](ue_ue.CharacterMovementComponent.md#setwalkablefloorz)
- [SnapUpdatedComponentToPlane](ue_ue.CharacterMovementComponent.md#snapupdatedcomponenttoplane)
- [StopActiveMovement](ue_ue.CharacterMovementComponent.md#stopactivemovement)
- [StopMovementImmediately](ue_ue.CharacterMovementComponent.md#stopmovementimmediately)
- [StopMovementKeepPathing](ue_ue.CharacterMovementComponent.md#stopmovementkeeppathing)
- [ToggleActive](ue_ue.CharacterMovementComponent.md#toggleactive)
- [Find](ue_ue.CharacterMovementComponent.md#find)
- [Load](ue_ue.CharacterMovementComponent.md#load)
- [StaticClass](ue_ue.CharacterMovementComponent.md#staticclass)

## Constructors

### constructor

• **new CharacterMovementComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[constructor](ue_ue.PawnMovementComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:5630](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5630)

## Properties

### Acceleration

• **Acceleration**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5702](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5702)

___

### AirControl

• **AirControl**: `number`

#### Defined in

[ue/ue.d.ts:5656](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5656)

___

### AirControlBoostMultiplier

• **AirControlBoostMultiplier**: `number`

#### Defined in

[ue/ue.d.ts:5657](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5657)

___

### AirControlBoostVelocityThreshold

• **AirControlBoostVelocityThreshold**: `number`

#### Defined in

[ue/ue.d.ts:5658](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5658)

___

### AnalogInputModifier

• **AnalogInputModifier**: `number`

#### Defined in

[ue/ue.d.ts:5711](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5711)

___

### AnimRootMotionVelocity

• **AnimRootMotionVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5784](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5784)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[AssetUserData](ue_ue.PawnMovementComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### AvoidanceConsiderationRadius

• **AvoidanceConsiderationRadius**: `number`

#### Defined in

[ue/ue.d.ts:5766](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5766)

___

### AvoidanceGroup

• **AvoidanceGroup**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Defined in

[ue/ue.d.ts:5769](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5769)

___

### AvoidanceUID

• **AvoidanceUID**: `number`

#### Defined in

[ue/ue.d.ts:5768](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5768)

___

### AvoidanceWeight

• **AvoidanceWeight**: `number`

#### Defined in

[ue/ue.d.ts:5772](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5772)

___

### BrakingDecelerationFalling

• **BrakingDecelerationFalling**: `number`

#### Defined in

[ue/ue.d.ts:5653](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5653)

___

### BrakingDecelerationFlying

• **BrakingDecelerationFlying**: `number`

#### Defined in

[ue/ue.d.ts:5655](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5655)

___

### BrakingDecelerationSwimming

• **BrakingDecelerationSwimming**: `number`

#### Defined in

[ue/ue.d.ts:5654](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5654)

___

### BrakingDecelerationWalking

• **BrakingDecelerationWalking**: `number`

#### Defined in

[ue/ue.d.ts:5652](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5652)

___

### BrakingFriction

• **BrakingFriction**: `number`

#### Defined in

[ue/ue.d.ts:5650](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5650)

___

### BrakingFrictionFactor

• **BrakingFrictionFactor**: `number`

#### Defined in

[ue/ue.d.ts:5649](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5649)

___

### BrakingSubStepTime

• **BrakingSubStepTime**: `number`

#### Defined in

[ue/ue.d.ts:5651](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5651)

___

### Buoyancy

• **Buoyancy**: `number`

#### Defined in

[ue/ue.d.ts:5661](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5661)

___

### CharacterOwner

• **CharacterOwner**: [`Character`](ue_ue.Character.md)

#### Defined in

[ue/ue.d.ts:5631](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5631)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ComponentTags](ue_ue.PawnMovementComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[CreationMethod](ue_ue.PawnMovementComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### CrouchedHalfHeight

• **CrouchedHalfHeight**: `number`

#### Defined in

[ue/ue.d.ts:5660](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5660)

___

### CrouchedSpeedMultiplier

• **CrouchedSpeedMultiplier**: `number`

#### Defined in

[ue/ue.d.ts:5700](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5700)

___

### CurrentFloor

• **CurrentFloor**: [`FindFloorResult`](ue_ue.FindFloorResult.md)

#### Defined in

[ue/ue.d.ts:5733](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5733)

___

### CurrentRootMotion

• **CurrentRootMotion**: [`RootMotionSourceGroup`](ue_ue.RootMotionSourceGroup.md)

#### Defined in

[ue/ue.d.ts:5782](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5782)

___

### CustomMovementMode

• **CustomMovementMode**: `number`

#### Defined in

[ue/ue.d.ts:5639](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5639)

___

### DefaultLandMovementMode

• **DefaultLandMovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

#### Defined in

[ue/ue.d.ts:5734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5734)

___

### DefaultWaterMovementMode

• **DefaultWaterMovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

#### Defined in

[ue/ue.d.ts:5735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5735)

___

### DeferredUpdatedMoveComponent

• **DeferredUpdatedMoveComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Defined in

[ue/ue.d.ts:5687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5687)

___

### FallingLateralFriction

• **FallingLateralFriction**: `number`

#### Defined in

[ue/ue.d.ts:5659](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5659)

___

### FixedPathBrakingDistance

• **FixedPathBrakingDistance**: `number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[FixedPathBrakingDistance](ue_ue.PawnMovementComponent.md#fixedpathbrakingdistance)

#### Defined in

[ue/ue.d.ts:5468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5468)

___

### GravityScale

• **GravityScale**: `number`

#### Defined in

[ue/ue.d.ts:5632](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5632)

___

### GroundFriction

• **GroundFriction**: `number`

#### Defined in

[ue/ue.d.ts:5641](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5641)

___

### GroundMovementMode

• **GroundMovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

#### Defined in

[ue/ue.d.ts:5736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5736)

___

### GroupsToAvoid

• **GroupsToAvoid**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Defined in

[ue/ue.d.ts:5770](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5770)

___

### GroupsToIgnore

• **GroupsToIgnore**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

#### Defined in

[ue/ue.d.ts:5771](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5771)

___

### InitialPushForceFactor

• **InitialPushForceFactor**: `number`

#### Defined in

[ue/ue.d.ts:5692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5692)

___

### JumpOffJumpZFactor

• **JumpOffJumpZFactor**: `number`

#### Defined in

[ue/ue.d.ts:5635](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5635)

___

### JumpOutOfWaterPitch

• **JumpOutOfWaterPitch**: `number`

#### Defined in

[ue/ue.d.ts:5732](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5732)

___

### JumpZVelocity

• **JumpZVelocity**: `number`

#### Defined in

[ue/ue.d.ts:5634](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5634)

___

### LastUpdateLocation

• **LastUpdateLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5704](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5704)

___

### LastUpdateRotation

• **LastUpdateRotation**: [`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue.d.ts:5703](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5703)

___

### LastUpdateVelocity

• **LastUpdateVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5705](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5705)

___

### LedgeCheckThreshold

• **LedgeCheckThreshold**: `number`

#### Defined in

[ue/ue.d.ts:5731](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5731)

___

### ListenServerNetworkSimulatedSmoothLocationTime

• **ListenServerNetworkSimulatedSmoothLocationTime**: `number`

#### Defined in

[ue/ue.d.ts:5721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5721)

___

### ListenServerNetworkSimulatedSmoothRotationTime

• **ListenServerNetworkSimulatedSmoothRotationTime**: `number`

#### Defined in

[ue/ue.d.ts:5722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5722)

___

### Mass

• **Mass**: `number`

#### Defined in

[ue/ue.d.ts:5690](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5690)

___

### MaxAcceleration

• **MaxAcceleration**: `number`

#### Defined in

[ue/ue.d.ts:5647](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5647)

___

### MaxCustomMovementSpeed

• **MaxCustomMovementSpeed**: `number`

#### Defined in

[ue/ue.d.ts:5646](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5646)

___

### MaxDepenetrationWithGeometry

• **MaxDepenetrationWithGeometry**: `number`

#### Defined in

[ue/ue.d.ts:5715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5715)

___

### MaxDepenetrationWithGeometryAsProxy

• **MaxDepenetrationWithGeometryAsProxy**: `number`

#### Defined in

[ue/ue.d.ts:5716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5716)

___

### MaxDepenetrationWithPawn

• **MaxDepenetrationWithPawn**: `number`

#### Defined in

[ue/ue.d.ts:5717](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5717)

___

### MaxDepenetrationWithPawnAsProxy

• **MaxDepenetrationWithPawnAsProxy**: `number`

#### Defined in

[ue/ue.d.ts:5718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5718)

___

### MaxFlySpeed

• **MaxFlySpeed**: `number`

#### Defined in

[ue/ue.d.ts:5645](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5645)

___

### MaxJumpApexAttemptsPerSimulation

• **MaxJumpApexAttemptsPerSimulation**: `number`

#### Defined in

[ue/ue.d.ts:5714](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5714)

___

### MaxOutOfWaterStepHeight

• **MaxOutOfWaterStepHeight**: `number`

#### Defined in

[ue/ue.d.ts:5688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5688)

___

### MaxSimulationIterations

• **MaxSimulationIterations**: `number`

#### Defined in

[ue/ue.d.ts:5713](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5713)

___

### MaxSimulationTimeStep

• **MaxSimulationTimeStep**: `number`

#### Defined in

[ue/ue.d.ts:5712](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5712)

___

### MaxStepHeight

• **MaxStepHeight**: `number`

#### Defined in

[ue/ue.d.ts:5633](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5633)

___

### MaxSwimSpeed

• **MaxSwimSpeed**: `number`

#### Defined in

[ue/ue.d.ts:5644](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5644)

___

### MaxTouchForce

• **MaxTouchForce**: `number`

#### Defined in

[ue/ue.d.ts:5697](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5697)

___

### MaxWalkSpeed

• **MaxWalkSpeed**: `number`

#### Defined in

[ue/ue.d.ts:5642](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5642)

___

### MaxWalkSpeedCrouched

• **MaxWalkSpeedCrouched**: `number`

#### Defined in

[ue/ue.d.ts:5643](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5643)

___

### MinAnalogWalkSpeed

• **MinAnalogWalkSpeed**: `number`

#### Defined in

[ue/ue.d.ts:5648](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5648)

___

### MinTimeBetweenTimeStampResets

• **MinTimeBetweenTimeStampResets**: `number`

#### Defined in

[ue/ue.d.ts:5781](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5781)

___

### MinTouchForce

• **MinTouchForce**: `number`

#### Defined in

[ue/ue.d.ts:5696](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5696)

___

### MovementMode

• **MovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

#### Defined in

[ue/ue.d.ts:5638](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5638)

___

### MovementState

• **MovementState**: [`MovementProperties`](ue_ue.MovementProperties.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[MovementState](ue_ue.PawnMovementComponent.md#movementstate)

#### Defined in

[ue/ue.d.ts:5472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5472)

___

### NavAgentProps

• **NavAgentProps**: [`NavAgentProperties`](ue_ue.NavAgentProperties.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[NavAgentProps](ue_ue.PawnMovementComponent.md#navagentprops)

#### Defined in

[ue/ue.d.ts:5467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5467)

___

### NavMeshProjectionHeightScaleDown

• **NavMeshProjectionHeightScaleDown**: `number`

#### Defined in

[ue/ue.d.ts:5778](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5778)

___

### NavMeshProjectionHeightScaleUp

• **NavMeshProjectionHeightScaleUp**: `number`

#### Defined in

[ue/ue.d.ts:5777](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5777)

___

### NavMeshProjectionInterpSpeed

• **NavMeshProjectionInterpSpeed**: `number`

#### Defined in

[ue/ue.d.ts:5776](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5776)

___

### NavMeshProjectionInterval

• **NavMeshProjectionInterval**: `number`

#### Defined in

[ue/ue.d.ts:5774](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5774)

___

### NavMeshProjectionTimer

• **NavMeshProjectionTimer**: `number`

#### Defined in

[ue/ue.d.ts:5775](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5775)

___

### NavWalkingFloorDistTolerance

• **NavWalkingFloorDistTolerance**: `number`

#### Defined in

[ue/ue.d.ts:5779](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5779)

___

### NetProxyShrinkHalfHeight

• **NetProxyShrinkHalfHeight**: `number`

#### Defined in

[ue/ue.d.ts:5724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5724)

___

### NetProxyShrinkRadius

• **NetProxyShrinkRadius**: `number`

#### Defined in

[ue/ue.d.ts:5723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5723)

___

### NetworkLargeClientCorrectionDistance

• **NetworkLargeClientCorrectionDistance**: `number`

#### Defined in

[ue/ue.d.ts:5730](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5730)

___

### NetworkMaxSmoothUpdateDistance

• **NetworkMaxSmoothUpdateDistance**: `number`

#### Defined in

[ue/ue.d.ts:5725](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5725)

___

### NetworkMinTimeBetweenClientAckGoodMoves

• **NetworkMinTimeBetweenClientAckGoodMoves**: `number`

#### Defined in

[ue/ue.d.ts:5727](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5727)

___

### NetworkMinTimeBetweenClientAdjustments

• **NetworkMinTimeBetweenClientAdjustments**: `number`

#### Defined in

[ue/ue.d.ts:5728](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5728)

___

### NetworkMinTimeBetweenClientAdjustmentsLargeCorrection

• **NetworkMinTimeBetweenClientAdjustmentsLargeCorrection**: `number`

#### Defined in

[ue/ue.d.ts:5729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5729)

___

### NetworkNoSmoothUpdateDistance

• **NetworkNoSmoothUpdateDistance**: `number`

#### Defined in

[ue/ue.d.ts:5726](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5726)

___

### NetworkSimulatedSmoothLocationTime

• **NetworkSimulatedSmoothLocationTime**: `number`

#### Defined in

[ue/ue.d.ts:5719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5719)

___

### NetworkSimulatedSmoothRotationTime

• **NetworkSimulatedSmoothRotationTime**: `number`

#### Defined in

[ue/ue.d.ts:5720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5720)

___

### NetworkSmoothingMode

• **NetworkSmoothingMode**: [`ENetworkSmoothingMode`](../enums/ue_ue.ENetworkSmoothingMode.md)

#### Defined in

[ue/ue.d.ts:5640](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5640)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[OnComponentActivated](ue_ue.PawnMovementComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[OnComponentDeactivated](ue_ue.PawnMovementComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### OutofWaterZ

• **OutofWaterZ**: `number`

#### Defined in

[ue/ue.d.ts:5689](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5689)

___

### PathFollowingComp

• **PathFollowingComp**: [`Object`](ue_ue.Object.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PathFollowingComp](ue_ue.PawnMovementComponent.md#pathfollowingcomp)

#### Defined in

[ue/ue.d.ts:5473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5473)

___

### PawnOwner

• **PawnOwner**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PawnOwner](ue_ue.PawnMovementComponent.md#pawnowner)

#### Defined in

[ue/ue.d.ts:5490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5490)

___

### PendingForceToApply

• **PendingForceToApply**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5710](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5710)

___

### PendingImpulseToApply

• **PendingImpulseToApply**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5709](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5709)

___

### PendingLaunchVelocity

• **PendingLaunchVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5773](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5773)

___

### PerchAdditionalHeight

• **PerchAdditionalHeight**: `number`

#### Defined in

[ue/ue.d.ts:5663](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5663)

___

### PerchRadiusThreshold

• **PerchRadiusThreshold**: `number`

#### Defined in

[ue/ue.d.ts:5662](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5662)

___

### PlaneConstraintAxisSetting

• **PlaneConstraintAxisSetting**: [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PlaneConstraintAxisSetting](ue_ue.PawnMovementComponent.md#planeconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5403](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5403)

___

### PlaneConstraintNormal

• **PlaneConstraintNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PlaneConstraintNormal](ue_ue.PawnMovementComponent.md#planeconstraintnormal)

#### Defined in

[ue/ue.d.ts:5393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5393)

___

### PlaneConstraintOrigin

• **PlaneConstraintOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PlaneConstraintOrigin](ue_ue.PawnMovementComponent.md#planeconstraintorigin)

#### Defined in

[ue/ue.d.ts:5394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5394)

___

### PostPhysicsTickFunction

• **PostPhysicsTickFunction**: [`CharacterMovementComponentPostPhysicsTickFunction`](ue_ue.CharacterMovementComponentPostPhysicsTickFunction.md)

#### Defined in

[ue/ue.d.ts:5780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5780)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PrimaryComponentTick](ue_ue.PawnMovementComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### PushForceFactor

• **PushForceFactor**: `number`

#### Defined in

[ue/ue.d.ts:5693](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5693)

___

### PushForcePointZOffsetFactor

• **PushForcePointZOffsetFactor**: `number`

#### Defined in

[ue/ue.d.ts:5694](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5694)

___

### RepulsionForce

• **RepulsionForce**: `number`

#### Defined in

[ue/ue.d.ts:5698](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5698)

___

### RequestedVelocity

• **RequestedVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5767](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5767)

___

### RootMotionParams

• **RootMotionParams**: [`RootMotionMovementParams`](ue_ue.RootMotionMovementParams.md)

#### Defined in

[ue/ue.d.ts:5783](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5783)

___

### RotationRate

• **RotationRate**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:5664](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5664)

___

### ServerLastClientAdjustmentTime

• **ServerLastClientAdjustmentTime**: `number`

#### Defined in

[ue/ue.d.ts:5708](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5708)

___

### ServerLastClientGoodMoveAckTime

• **ServerLastClientGoodMoveAckTime**: `number`

#### Defined in

[ue/ue.d.ts:5707](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5707)

___

### ServerLastTransformUpdateTimeStamp

• **ServerLastTransformUpdateTimeStamp**: `number`

#### Defined in

[ue/ue.d.ts:5706](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5706)

___

### StandingDownwardForceScale

• **StandingDownwardForceScale**: `number`

#### Defined in

[ue/ue.d.ts:5691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5691)

___

### TouchForceFactor

• **TouchForceFactor**: `number`

#### Defined in

[ue/ue.d.ts:5695](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5695)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[UCSModifiedProperties](ue_ue.PawnMovementComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### UpdatedComponent

• **UpdatedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[UpdatedComponent](ue_ue.PawnMovementComponent.md#updatedcomponent)

#### Defined in

[ue/ue.d.ts:5390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5390)

___

### UpdatedPrimitive

• **UpdatedPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[UpdatedPrimitive](ue_ue.PawnMovementComponent.md#updatedprimitive)

#### Defined in

[ue/ue.d.ts:5391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5391)

___

### UpperImpactNormalScale

• **UpperImpactNormalScale**: `number`

#### Defined in

[ue/ue.d.ts:5701](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5701)

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Velocity](ue_ue.PawnMovementComponent.md#velocity)

#### Defined in

[ue/ue.d.ts:5392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5392)

___

### WalkableFloorAngle

• **WalkableFloorAngle**: `number`

#### Defined in

[ue/ue.d.ts:5636](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5636)

___

### WalkableFloorZ

• **WalkableFloorZ**: `number`

#### Defined in

[ue/ue.d.ts:5637](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5637)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_ActorComponent__](ue_ue.PawnMovementComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_CharacterMovementComponent\_\_

• **\_\_tid\_CharacterMovementComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:5827](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5827)

___

### \_\_tid\_MovementComponent\_\_

• **\_\_tid\_MovementComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_MovementComponent__](ue_ue.PawnMovementComponent.md#__tid_movementcomponent__)

#### Defined in

[ue/ue.d.ts:5430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5430)

___

### \_\_tid\_NavMovementComponent\_\_

• **\_\_tid\_NavMovementComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_NavMovementComponent__](ue_ue.PawnMovementComponent.md#__tid_navmovementcomponent__)

#### Defined in

[ue/ue.d.ts:5485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5485)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_Object__](ue_ue.PawnMovementComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PawnMovementComponent\_\_

• **\_\_tid\_PawnMovementComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_PawnMovementComponent__](ue_ue.PawnMovementComponent.md#__tid_pawnmovementcomponent__)

#### Defined in

[ue/ue.d.ts:5502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5502)

___

### bAllowPhysicsRotationDuringAnimRootMotion

• **bAllowPhysicsRotationDuringAnimRootMotion**: `boolean`

#### Defined in

[ue/ue.d.ts:5760](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5760)

___

### bAlwaysCheckFloor

• **bAlwaysCheckFloor**: `boolean`

#### Defined in

[ue/ue.d.ts:5753](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5753)

___

### bApplyGravityWhileJumping

• **bApplyGravityWhileJumping**: `boolean`

#### Defined in

[ue/ue.d.ts:5666](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5666)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoActivate](ue_ue.PawnMovementComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bAutoRegisterPhysicsVolumeUpdates

• **bAutoRegisterPhysicsVolumeUpdates**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoRegisterPhysicsVolumeUpdates](ue_ue.PawnMovementComponent.md#bautoregisterphysicsvolumeupdates)

#### Defined in

[ue/ue.d.ts:5401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5401)

___

### bAutoRegisterUpdatedComponent

• **bAutoRegisterUpdatedComponent**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoRegisterUpdatedComponent](ue_ue.PawnMovementComponent.md#bautoregisterupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5398)

___

### bAutoUpdateTickRegistration

• **bAutoUpdateTickRegistration**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoUpdateTickRegistration](ue_ue.PawnMovementComponent.md#bautoupdatetickregistration)

#### Defined in

[ue/ue.d.ts:5396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5396)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bCanEverAffectNavigation](ue_ue.PawnMovementComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bCanWalkOffLedges

• **bCanWalkOffLedges**: `boolean`

#### Defined in

[ue/ue.d.ts:5677](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5677)

___

### bCanWalkOffLedgesWhenCrouching

• **bCanWalkOffLedgesWhenCrouching**: `boolean`

#### Defined in

[ue/ue.d.ts:5678](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5678)

___

### bCheatFlying

• **bCheatFlying**: `boolean`

#### Defined in

[ue/ue.d.ts:5748](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5748)

___

### bComponentShouldUpdatePhysicsVolume

• **bComponentShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bComponentShouldUpdatePhysicsVolume](ue_ue.PawnMovementComponent.md#bcomponentshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:5402](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5402)

___

### bConstrainToPlane

• **bConstrainToPlane**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bConstrainToPlane](ue_ue.PawnMovementComponent.md#bconstraintoplane)

#### Defined in

[ue/ue.d.ts:5399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5399)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bCreatedByConstructionScript](ue_ue.PawnMovementComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bCrouchMaintainsBaseLocation

• **bCrouchMaintainsBaseLocation**: `boolean`

#### Defined in

[ue/ue.d.ts:5750](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5750)

___

### bDeferUpdateMoveComponent

• **bDeferUpdateMoveComponent**: `boolean`

#### Defined in

[ue/ue.d.ts:5681](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5681)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bEditableWhenInherited](ue_ue.PawnMovementComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bEnablePhysicsInteraction

• **bEnablePhysicsInteraction**: `boolean`

#### Defined in

[ue/ue.d.ts:5682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5682)

___

### bEnableScopedMovementUpdates

• **bEnableScopedMovementUpdates**: `boolean`

#### Defined in

[ue/ue.d.ts:5671](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5671)

___

### bEnableServerDualMoveScopedMovementUpdates

• **bEnableServerDualMoveScopedMovementUpdates**: `boolean`

#### Defined in

[ue/ue.d.ts:5672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5672)

___

### bFastAttachedMove

• **bFastAttachedMove**: `boolean`

#### Defined in

[ue/ue.d.ts:5752](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5752)

___

### bForceBraking

• **bForceBraking**: `boolean`

#### Defined in

[ue/ue.d.ts:5699](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5699)

___

### bForceMaxAccel

• **bForceMaxAccel**: `boolean`

#### Defined in

[ue/ue.d.ts:5673](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5673)

___

### bForceNextFloorCheck

• **bForceNextFloorCheck**: `boolean`

#### Defined in

[ue/ue.d.ts:5675](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5675)

___

### bHasRequestedVelocity

• **bHasRequestedVelocity**: `boolean`

#### Defined in

[ue/ue.d.ts:5761](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5761)

___

### bIgnoreBaseRotation

• **bIgnoreBaseRotation**: `boolean`

#### Defined in

[ue/ue.d.ts:5751](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5751)

___

### bIgnoreClientMovementErrorChecksAndCorrection

• **bIgnoreClientMovementErrorChecksAndCorrection**: `boolean`

#### Defined in

[ue/ue.d.ts:5745](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5745)

___

### bImpartBaseAngularVelocity

• **bImpartBaseAngularVelocity**: `boolean`

#### Defined in

[ue/ue.d.ts:5741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5741)

___

### bImpartBaseVelocityX

• **bImpartBaseVelocityX**: `boolean`

#### Defined in

[ue/ue.d.ts:5738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5738)

___

### bImpartBaseVelocityY

• **bImpartBaseVelocityY**: `boolean`

#### Defined in

[ue/ue.d.ts:5739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5739)

___

### bImpartBaseVelocityZ

• **bImpartBaseVelocityZ**: `boolean`

#### Defined in

[ue/ue.d.ts:5740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5740)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bInstanceComponent](ue_ue.PawnMovementComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bIsActive](ue_ue.PawnMovementComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bIsEditorOnly](ue_ue.PawnMovementComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bIsVisualizationComponent](ue_ue.PawnMovementComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bJustTeleported

• **bJustTeleported**: `boolean`

#### Defined in

[ue/ue.d.ts:5742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5742)

___

### bMaintainHorizontalGroundVelocity

• **bMaintainHorizontalGroundVelocity**: `boolean`

#### Defined in

[ue/ue.d.ts:5737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5737)

___

### bMovementInProgress

• **bMovementInProgress**: `boolean`

#### Defined in

[ue/ue.d.ts:5670](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5670)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bNetAddressable](ue_ue.PawnMovementComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bNetworkAlwaysReplicateTransformUpdateTimestamp

• **bNetworkAlwaysReplicateTransformUpdateTimestamp**: `boolean`

#### Defined in

[ue/ue.d.ts:5680](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5680)

___

### bNetworkMovementModeChanged

• **bNetworkMovementModeChanged**: `boolean`

#### Defined in

[ue/ue.d.ts:5744](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5744)

___

### bNetworkSkipProxyPredictionOnNetUpdate

• **bNetworkSkipProxyPredictionOnNetUpdate**: `boolean`

#### Defined in

[ue/ue.d.ts:5679](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5679)

___

### bNetworkUpdateReceived

• **bNetworkUpdateReceived**: `boolean`

#### Defined in

[ue/ue.d.ts:5743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5743)

___

### bNotifyApex

• **bNotifyApex**: `boolean`

#### Defined in

[ue/ue.d.ts:5747](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5747)

___

### bOrientRotationToMovement

• **bOrientRotationToMovement**: `boolean`

#### Defined in

[ue/ue.d.ts:5668](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5668)

___

### bPerformingJumpOff

• **bPerformingJumpOff**: `boolean`

#### Defined in

[ue/ue.d.ts:5755](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5755)

___

### bProjectNavMeshOnBothWorldChannels

• **bProjectNavMeshOnBothWorldChannels**: `boolean`

#### Defined in

[ue/ue.d.ts:5765](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5765)

___

### bProjectNavMeshWalking

• **bProjectNavMeshWalking**: `boolean`

#### Defined in

[ue/ue.d.ts:5764](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5764)

___

### bPushForceScaledToMass

• **bPushForceScaledToMass**: `boolean`

#### Defined in

[ue/ue.d.ts:5684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5684)

___

### bPushForceUsingZOffset

• **bPushForceUsingZOffset**: `boolean`

#### Defined in

[ue/ue.d.ts:5685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5685)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bReplicates](ue_ue.PawnMovementComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L292)

___

### bRequestedMoveUseAcceleration

• **bRequestedMoveUseAcceleration**: `boolean`

#### Defined in

[ue/ue.d.ts:5758](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5758)

___

### bRequestedMoveWithMaxSpeed

• **bRequestedMoveWithMaxSpeed**: `boolean`

#### Defined in

[ue/ue.d.ts:5762](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5762)

___

### bRunPhysicsWithNoController

• **bRunPhysicsWithNoController**: `boolean`

#### Defined in

[ue/ue.d.ts:5674](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5674)

___

### bScalePushForceToVelocity

• **bScalePushForceToVelocity**: `boolean`

#### Defined in

[ue/ue.d.ts:5686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5686)

___

### bServerAcceptClientAuthoritativePosition

• **bServerAcceptClientAuthoritativePosition**: `boolean`

#### Defined in

[ue/ue.d.ts:5746](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5746)

___

### bShrinkProxyCapsule

• **bShrinkProxyCapsule**: `boolean`

#### Defined in

[ue/ue.d.ts:5676](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5676)

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bSnapToPlaneAtStart](ue_ue.PawnMovementComponent.md#bsnaptoplaneatstart)

#### Defined in

[ue/ue.d.ts:5400](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5400)

___

### bSweepWhileNavWalking

• **bSweepWhileNavWalking**: `boolean`

#### Defined in

[ue/ue.d.ts:5669](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5669)

___

### bTickBeforeOwner

• **bTickBeforeOwner**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bTickBeforeOwner](ue_ue.PawnMovementComponent.md#btickbeforeowner)

#### Defined in

[ue/ue.d.ts:5397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5397)

___

### bTouchForceScaledToMass

• **bTouchForceScaledToMass**: `boolean`

#### Defined in

[ue/ue.d.ts:5683](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5683)

___

### bUpdateNavAgentWithOwnersCollision

• **bUpdateNavAgentWithOwnersCollision**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUpdateNavAgentWithOwnersCollision](ue_ue.PawnMovementComponent.md#bupdatenavagentwithownerscollision)

#### Defined in

[ue/ue.d.ts:5469](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5469)

___

### bUpdateOnlyIfRendered

• **bUpdateOnlyIfRendered**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUpdateOnlyIfRendered](ue_ue.PawnMovementComponent.md#bupdateonlyifrendered)

#### Defined in

[ue/ue.d.ts:5395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5395)

___

### bUseAccelerationForPaths

• **bUseAccelerationForPaths**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUseAccelerationForPaths](ue_ue.PawnMovementComponent.md#buseaccelerationforpaths)

#### Defined in

[ue/ue.d.ts:5470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5470)

___

### bUseControllerDesiredRotation

• **bUseControllerDesiredRotation**: `boolean`

#### Defined in

[ue/ue.d.ts:5667](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5667)

___

### bUseFixedBrakingDistanceForPaths

• **bUseFixedBrakingDistanceForPaths**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUseFixedBrakingDistanceForPaths](ue_ue.PawnMovementComponent.md#busefixedbrakingdistanceforpaths)

#### Defined in

[ue/ue.d.ts:5471](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5471)

___

### bUseFlatBaseForFloorChecks

• **bUseFlatBaseForFloorChecks**: `boolean`

#### Defined in

[ue/ue.d.ts:5754](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5754)

___

### bUseRVOAvoidance

• **bUseRVOAvoidance**: `boolean`

#### Defined in

[ue/ue.d.ts:5757](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5757)

___

### bUseSeparateBrakingFriction

• **bUseSeparateBrakingFriction**: `boolean`

#### Defined in

[ue/ue.d.ts:5665](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5665)

___

### bWantsToCrouch

• **bWantsToCrouch**: `boolean`

#### Defined in

[ue/ue.d.ts:5749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5749)

___

### bWantsToLeaveNavWalking

• **bWantsToLeaveNavWalking**: `boolean`

#### Defined in

[ue/ue.d.ts:5756](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5756)

___

### bWasAvoidanceUpdated

• **bWasAvoidanceUpdated**: `boolean`

#### Defined in

[ue/ue.d.ts:5763](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5763)

___

### bWasSimulatingRootMotion

• **bWasSimulatingRootMotion**: `boolean`

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Activate](ue_ue.PawnMovementComponent.md#activate)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[AddInputVector](ue_ue.PawnMovementComponent.md#addinputvector)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[AddTickPrerequisiteActor](ue_ue.PawnMovementComponent.md#addtickprerequisiteactor)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[AddTickPrerequisiteComponent](ue_ue.PawnMovementComponent.md#addtickprerequisitecomponent)

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

#### Defined in

[ue/ue.d.ts:5788](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5788)

___

### ClearAccumulatedForces

▸ **ClearAccumulatedForces**(): `void`

#### Returns

`void`

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ComponentHasTag](ue_ue.PawnMovementComponent.md#componenthastag)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ConstrainDirectionToPlane](ue_ue.PawnMovementComponent.md#constraindirectiontoplane)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ConstrainLocationToPlane](ue_ue.PawnMovementComponent.md#constrainlocationtoplane)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ConstrainNormalToPlane](ue_ue.PawnMovementComponent.md#constrainnormaltoplane)

#### Defined in

[ue/ue.d.ts:5406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5406)

___

### ConsumeInputVector

▸ **ConsumeInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ConsumeInputVector](ue_ue.PawnMovementComponent.md#consumeinputvector)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[CreateDefaultSubobject](ue_ue.PawnMovementComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Deactivate](ue_ue.PawnMovementComponent.md#deactivate)

#### Defined in

[ue/ue.d.ts:310](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L310)

___

### DisableMovement

▸ **DisableMovement**(): `void`

#### Returns

`void`

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ExecuteUbergraph](ue_ue.PawnMovementComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetAnalogInputModifier

▸ **GetAnalogInputModifier**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:5791](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5791)

___

### GetCharacterOwner

▸ **GetCharacterOwner**(): [`Character`](ue_ue.Character.md)

#### Returns

[`Character`](ue_ue.Character.md)

#### Defined in

[ue/ue.d.ts:5792](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5792)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetClass](ue_ue.PawnMovementComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetComponentTickInterval](ue_ue.PawnMovementComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetCurrentAcceleration

▸ **GetCurrentAcceleration**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5793](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5793)

___

### GetGravityZ

▸ **GetGravityZ**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetGravityZ](ue_ue.PawnMovementComponent.md#getgravityz)

#### Defined in

[ue/ue.d.ts:5407](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5407)

___

### GetImpartedMovementBaseVelocity

▸ **GetImpartedMovementBaseVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5794](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5794)

___

### GetLastInputVector

▸ **GetLastInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetLastInputVector](ue_ue.PawnMovementComponent.md#getlastinputvector)

#### Defined in

[ue/ue.d.ts:5493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5493)

___

### GetLastUpdateLocation

▸ **GetLastUpdateLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5795](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5795)

___

### GetLastUpdateRotation

▸ **GetLastUpdateRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:5796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5796)

___

### GetLastUpdateVelocity

▸ **GetLastUpdateVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:5797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5797)

___

### GetMaxAcceleration

▸ **GetMaxAcceleration**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:5798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5798)

___

### GetMaxBrakingDeceleration

▸ **GetMaxBrakingDeceleration**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:5799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5799)

___

### GetMaxJumpHeight

▸ **GetMaxJumpHeight**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:5800](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5800)

___

### GetMaxJumpHeightWithJumpTime

▸ **GetMaxJumpHeightWithJumpTime**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:5801](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5801)

___

### GetMaxSpeed

▸ **GetMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetMaxSpeed](ue_ue.PawnMovementComponent.md#getmaxspeed)

#### Defined in

[ue/ue.d.ts:5408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5408)

___

### GetMinAnalogSpeed

▸ **GetMinAnalogSpeed**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:5802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5802)

___

### GetMovementBase

▸ **GetMovementBase**(): [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Returns

[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:5803](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5803)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetName](ue_ue.PawnMovementComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetOuter](ue_ue.PawnMovementComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetOwner](ue_ue.PawnMovementComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L312)

___

### GetPawnOwner

▸ **GetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPawnOwner](ue_ue.PawnMovementComponent.md#getpawnowner)

#### Defined in

[ue/ue.d.ts:5494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5494)

___

### GetPendingInputVector

▸ **GetPendingInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPendingInputVector](ue_ue.PawnMovementComponent.md#getpendinginputvector)

#### Defined in

[ue/ue.d.ts:5495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5495)

___

### GetPerchRadiusThreshold

▸ **GetPerchRadiusThreshold**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:5804](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5804)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPhysicsVolume](ue_ue.PawnMovementComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:5409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5409)

___

### GetPlaneConstraintAxisSetting

▸ **GetPlaneConstraintAxisSetting**(): [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Returns

[`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPlaneConstraintAxisSetting](ue_ue.PawnMovementComponent.md#getplaneconstraintaxissetting)

#### Defined in

[ue/ue.d.ts:5410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5410)

___

### GetPlaneConstraintNormal

▸ **GetPlaneConstraintNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPlaneConstraintNormal](ue_ue.PawnMovementComponent.md#getplaneconstraintnormal)

#### Defined in

[ue/ue.d.ts:5411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5411)

___

### GetPlaneConstraintOrigin

▸ **GetPlaneConstraintOrigin**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPlaneConstraintOrigin](ue_ue.PawnMovementComponent.md#getplaneconstraintorigin)

#### Defined in

[ue/ue.d.ts:5412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5412)

___

### GetValidPerchRadius

▸ **GetValidPerchRadius**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:5805](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5805)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetWorld](ue_ue.PawnMovementComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsActive](ue_ue.PawnMovementComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsBeingDestroyed](ue_ue.PawnMovementComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsComponentTickEnabled](ue_ue.PawnMovementComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L315)

___

### IsCrouching

▸ **IsCrouching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsCrouching](ue_ue.PawnMovementComponent.md#iscrouching)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsExceedingMaxSpeed](ue_ue.PawnMovementComponent.md#isexceedingmaxspeed)

#### Defined in

[ue/ue.d.ts:5413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5413)

___

### IsFalling

▸ **IsFalling**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsFalling](ue_ue.PawnMovementComponent.md#isfalling)

#### Defined in

[ue/ue.d.ts:5475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5475)

___

### IsFlying

▸ **IsFlying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsFlying](ue_ue.PawnMovementComponent.md#isflying)

#### Defined in

[ue/ue.d.ts:5476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5476)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsMoveInputIgnored](ue_ue.PawnMovementComponent.md#ismoveinputignored)

#### Defined in

[ue/ue.d.ts:5496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5496)

___

### IsMovingOnGround

▸ **IsMovingOnGround**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsMovingOnGround](ue_ue.PawnMovementComponent.md#ismovingonground)

#### Defined in

[ue/ue.d.ts:5477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5477)

___

### IsSwimming

▸ **IsSwimming**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsSwimming](ue_ue.PawnMovementComponent.md#isswimming)

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

#### Defined in

[ue/ue.d.ts:5806](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5806)

___

### IsWalking

▸ **IsWalking**(): `boolean`

#### Returns

`boolean`

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_DestroyComponent](ue_ue.PawnMovementComponent.md#k2_destroycomponent)

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

#### Defined in

[ue/ue.d.ts:5809](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5809)

___

### K2\_GetInputVector

▸ **K2_GetInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_GetInputVector](ue_ue.PawnMovementComponent.md#k2_getinputvector)

#### Defined in

[ue/ue.d.ts:5497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5497)

___

### K2\_GetMaxSpeedModifier

▸ **K2_GetMaxSpeedModifier**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_GetMaxSpeedModifier](ue_ue.PawnMovementComponent.md#k2_getmaxspeedmodifier)

#### Defined in

[ue/ue.d.ts:5414](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5414)

___

### K2\_GetModifiedMaxAcceleration

▸ **K2_GetModifiedMaxAcceleration**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:5810](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5810)

___

### K2\_GetModifiedMaxSpeed

▸ **K2_GetModifiedMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_GetModifiedMaxSpeed](ue_ue.PawnMovementComponent.md#k2_getmodifiedmaxspeed)

#### Defined in

[ue/ue.d.ts:5415](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5415)

___

### K2\_GetWalkableFloorAngle

▸ **K2_GetWalkableFloorAngle**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:5811](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5811)

___

### K2\_GetWalkableFloorZ

▸ **K2_GetWalkableFloorZ**(): `number`

#### Returns

`number`

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_MoveUpdatedComponent](ue_ue.PawnMovementComponent.md#k2_moveupdatedcomponent)

#### Defined in

[ue/ue.d.ts:5416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5416)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[OnRep_IsActive](ue_ue.PawnMovementComponent.md#onrep_isactive)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PhysicsVolumeChanged](ue_ue.PawnMovementComponent.md#physicsvolumechanged)

#### Defined in

[ue/ue.d.ts:5417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5417)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ReceiveBeginPlay](ue_ue.PawnMovementComponent.md#receivebeginplay)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ReceiveEndPlay](ue_ue.PawnMovementComponent.md#receiveendplay)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ReceiveTick](ue_ue.PawnMovementComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[RegisterComponent](ue_ue.PawnMovementComponent.md#registercomponent)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[RemoveTickPrerequisiteActor](ue_ue.PawnMovementComponent.md#removetickprerequisiteactor)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.PawnMovementComponent.md#removetickprerequisitecomponent)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetActive](ue_ue.PawnMovementComponent.md#setactive)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetAutoActivate](ue_ue.PawnMovementComponent.md#setautoactivate)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetComponentTickEnabled](ue_ue.PawnMovementComponent.md#setcomponenttickenabled)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetComponentTickInterval](ue_ue.PawnMovementComponent.md#setcomponenttickinterval)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetIsReplicated](ue_ue.PawnMovementComponent.md#setisreplicated)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetPlaneConstraintAxisSetting](ue_ue.PawnMovementComponent.md#setplaneconstraintaxissetting)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetPlaneConstraintEnabled](ue_ue.PawnMovementComponent.md#setplaneconstraintenabled)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetPlaneConstraintFromVectors](ue_ue.PawnMovementComponent.md#setplaneconstraintfromvectors)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetPlaneConstraintNormal](ue_ue.PawnMovementComponent.md#setplaneconstraintnormal)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetPlaneConstraintOrigin](ue_ue.PawnMovementComponent.md#setplaneconstraintorigin)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetTickGroup](ue_ue.PawnMovementComponent.md#settickgroup)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetTickableWhenPaused](ue_ue.PawnMovementComponent.md#settickablewhenpaused)

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

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SetUpdatedComponent](ue_ue.PawnMovementComponent.md#setupdatedcomponent)

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

#### Defined in

[ue/ue.d.ts:5822](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5822)

___

### SnapUpdatedComponentToPlane

▸ **SnapUpdatedComponentToPlane**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SnapUpdatedComponentToPlane](ue_ue.PawnMovementComponent.md#snapupdatedcomponenttoplane)

#### Defined in

[ue/ue.d.ts:5424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5424)

___

### StopActiveMovement

▸ **StopActiveMovement**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StopActiveMovement](ue_ue.PawnMovementComponent.md#stopactivemovement)

#### Defined in

[ue/ue.d.ts:5479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5479)

___

### StopMovementImmediately

▸ **StopMovementImmediately**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StopMovementImmediately](ue_ue.PawnMovementComponent.md#stopmovementimmediately)

#### Defined in

[ue/ue.d.ts:5425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5425)

___

### StopMovementKeepPathing

▸ **StopMovementKeepPathing**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StopMovementKeepPathing](ue_ue.PawnMovementComponent.md#stopmovementkeeppathing)

#### Defined in

[ue/ue.d.ts:5480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5480)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ToggleActive](ue_ue.PawnMovementComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CharacterMovementComponent`](ue_ue.CharacterMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CharacterMovementComponent`](ue_ue.CharacterMovementComponent.md)

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Find](ue_ue.PawnMovementComponent.md#find)

#### Defined in

[ue/ue.d.ts:5824](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5824)

___

### Load

▸ `Static` **Load**(`InName`): [`CharacterMovementComponent`](ue_ue.CharacterMovementComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CharacterMovementComponent`](ue_ue.CharacterMovementComponent.md)

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Load](ue_ue.PawnMovementComponent.md#load)

#### Defined in

[ue/ue.d.ts:5825](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5825)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StaticClass](ue_ue.PawnMovementComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:5823](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5823)
