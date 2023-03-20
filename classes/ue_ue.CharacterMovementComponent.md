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

## Properties

### Acceleration

• **Acceleration**: [`Vector`](ue_ue_s.Vector.md)

___

### AirControl

• **AirControl**: `number`

___

### AirControlBoostMultiplier

• **AirControlBoostMultiplier**: `number`

___

### AirControlBoostVelocityThreshold

• **AirControlBoostVelocityThreshold**: `number`

___

### AnalogInputModifier

• **AnalogInputModifier**: `number`

___

### AnimRootMotionVelocity

• **AnimRootMotionVelocity**: [`Vector`](ue_ue_s.Vector.md)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[AssetUserData](ue_ue.PawnMovementComponent.md#assetuserdata)

___

### AvoidanceConsiderationRadius

• **AvoidanceConsiderationRadius**: `number`

___

### AvoidanceGroup

• **AvoidanceGroup**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

___

### AvoidanceUID

• **AvoidanceUID**: `number`

___

### AvoidanceWeight

• **AvoidanceWeight**: `number`

___

### BrakingDecelerationFalling

• **BrakingDecelerationFalling**: `number`

___

### BrakingDecelerationFlying

• **BrakingDecelerationFlying**: `number`

___

### BrakingDecelerationSwimming

• **BrakingDecelerationSwimming**: `number`

___

### BrakingDecelerationWalking

• **BrakingDecelerationWalking**: `number`

___

### BrakingFriction

• **BrakingFriction**: `number`

___

### BrakingFrictionFactor

• **BrakingFrictionFactor**: `number`

___

### BrakingSubStepTime

• **BrakingSubStepTime**: `number`

___

### Buoyancy

• **Buoyancy**: `number`

___

### CharacterOwner

• **CharacterOwner**: [`Character`](ue_ue.Character.md)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ComponentTags](ue_ue.PawnMovementComponent.md#componenttags)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[CreationMethod](ue_ue.PawnMovementComponent.md#creationmethod)

___

### CrouchedHalfHeight

• **CrouchedHalfHeight**: `number`

___

### CrouchedSpeedMultiplier

• **CrouchedSpeedMultiplier**: `number`

___

### CurrentFloor

• **CurrentFloor**: [`FindFloorResult`](ue_ue.FindFloorResult.md)

___

### CurrentRootMotion

• **CurrentRootMotion**: [`RootMotionSourceGroup`](ue_ue.RootMotionSourceGroup.md)

___

### CustomMovementMode

• **CustomMovementMode**: `number`

___

### DefaultLandMovementMode

• **DefaultLandMovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

___

### DefaultWaterMovementMode

• **DefaultWaterMovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

___

### DeferredUpdatedMoveComponent

• **DeferredUpdatedMoveComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

___

### FallingLateralFriction

• **FallingLateralFriction**: `number`

___

### FixedPathBrakingDistance

• **FixedPathBrakingDistance**: `number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[FixedPathBrakingDistance](ue_ue.PawnMovementComponent.md#fixedpathbrakingdistance)

___

### GravityScale

• **GravityScale**: `number`

___

### GroundFriction

• **GroundFriction**: `number`

___

### GroundMovementMode

• **GroundMovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

___

### GroupsToAvoid

• **GroupsToAvoid**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

___

### GroupsToIgnore

• **GroupsToIgnore**: [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md)

___

### InitialPushForceFactor

• **InitialPushForceFactor**: `number`

___

### JumpOffJumpZFactor

• **JumpOffJumpZFactor**: `number`

___

### JumpOutOfWaterPitch

• **JumpOutOfWaterPitch**: `number`

___

### JumpZVelocity

• **JumpZVelocity**: `number`

___

### LastUpdateLocation

• **LastUpdateLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### LastUpdateRotation

• **LastUpdateRotation**: [`Quat`](ue_ue_s.Quat.md)

___

### LastUpdateVelocity

• **LastUpdateVelocity**: [`Vector`](ue_ue_s.Vector.md)

___

### LedgeCheckThreshold

• **LedgeCheckThreshold**: `number`

___

### ListenServerNetworkSimulatedSmoothLocationTime

• **ListenServerNetworkSimulatedSmoothLocationTime**: `number`

___

### ListenServerNetworkSimulatedSmoothRotationTime

• **ListenServerNetworkSimulatedSmoothRotationTime**: `number`

___

### Mass

• **Mass**: `number`

___

### MaxAcceleration

• **MaxAcceleration**: `number`

___

### MaxCustomMovementSpeed

• **MaxCustomMovementSpeed**: `number`

___

### MaxDepenetrationWithGeometry

• **MaxDepenetrationWithGeometry**: `number`

___

### MaxDepenetrationWithGeometryAsProxy

• **MaxDepenetrationWithGeometryAsProxy**: `number`

___

### MaxDepenetrationWithPawn

• **MaxDepenetrationWithPawn**: `number`

___

### MaxDepenetrationWithPawnAsProxy

• **MaxDepenetrationWithPawnAsProxy**: `number`

___

### MaxFlySpeed

• **MaxFlySpeed**: `number`

___

### MaxJumpApexAttemptsPerSimulation

• **MaxJumpApexAttemptsPerSimulation**: `number`

___

### MaxOutOfWaterStepHeight

• **MaxOutOfWaterStepHeight**: `number`

___

### MaxSimulationIterations

• **MaxSimulationIterations**: `number`

___

### MaxSimulationTimeStep

• **MaxSimulationTimeStep**: `number`

___

### MaxStepHeight

• **MaxStepHeight**: `number`

___

### MaxSwimSpeed

• **MaxSwimSpeed**: `number`

___

### MaxTouchForce

• **MaxTouchForce**: `number`

___

### MaxWalkSpeed

• **MaxWalkSpeed**: `number`

___

### MaxWalkSpeedCrouched

• **MaxWalkSpeedCrouched**: `number`

___

### MinAnalogWalkSpeed

• **MinAnalogWalkSpeed**: `number`

___

### MinTimeBetweenTimeStampResets

• **MinTimeBetweenTimeStampResets**: `number`

___

### MinTouchForce

• **MinTouchForce**: `number`

___

### MovementMode

• **MovementMode**: [`EMovementMode`](../enums/ue_ue.EMovementMode.md)

___

### MovementState

• **MovementState**: [`MovementProperties`](ue_ue.MovementProperties.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[MovementState](ue_ue.PawnMovementComponent.md#movementstate)

___

### NavAgentProps

• **NavAgentProps**: [`NavAgentProperties`](ue_ue.NavAgentProperties.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[NavAgentProps](ue_ue.PawnMovementComponent.md#navagentprops)

___

### NavMeshProjectionHeightScaleDown

• **NavMeshProjectionHeightScaleDown**: `number`

___

### NavMeshProjectionHeightScaleUp

• **NavMeshProjectionHeightScaleUp**: `number`

___

### NavMeshProjectionInterpSpeed

• **NavMeshProjectionInterpSpeed**: `number`

___

### NavMeshProjectionInterval

• **NavMeshProjectionInterval**: `number`

___

### NavMeshProjectionTimer

• **NavMeshProjectionTimer**: `number`

___

### NavWalkingFloorDistTolerance

• **NavWalkingFloorDistTolerance**: `number`

___

### NetProxyShrinkHalfHeight

• **NetProxyShrinkHalfHeight**: `number`

___

### NetProxyShrinkRadius

• **NetProxyShrinkRadius**: `number`

___

### NetworkLargeClientCorrectionDistance

• **NetworkLargeClientCorrectionDistance**: `number`

___

### NetworkMaxSmoothUpdateDistance

• **NetworkMaxSmoothUpdateDistance**: `number`

___

### NetworkMinTimeBetweenClientAckGoodMoves

• **NetworkMinTimeBetweenClientAckGoodMoves**: `number`

___

### NetworkMinTimeBetweenClientAdjustments

• **NetworkMinTimeBetweenClientAdjustments**: `number`

___

### NetworkMinTimeBetweenClientAdjustmentsLargeCorrection

• **NetworkMinTimeBetweenClientAdjustmentsLargeCorrection**: `number`

___

### NetworkNoSmoothUpdateDistance

• **NetworkNoSmoothUpdateDistance**: `number`

___

### NetworkSimulatedSmoothLocationTime

• **NetworkSimulatedSmoothLocationTime**: `number`

___

### NetworkSimulatedSmoothRotationTime

• **NetworkSimulatedSmoothRotationTime**: `number`

___

### NetworkSmoothingMode

• **NetworkSmoothingMode**: [`ENetworkSmoothingMode`](../enums/ue_ue.ENetworkSmoothingMode.md)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[OnComponentActivated](ue_ue.PawnMovementComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[OnComponentDeactivated](ue_ue.PawnMovementComponent.md#oncomponentdeactivated)

___

### OutofWaterZ

• **OutofWaterZ**: `number`

___

### PathFollowingComp

• **PathFollowingComp**: [`Object`](ue_ue.Object.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PathFollowingComp](ue_ue.PawnMovementComponent.md#pathfollowingcomp)

___

### PawnOwner

• **PawnOwner**: [`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PawnOwner](ue_ue.PawnMovementComponent.md#pawnowner)

___

### PendingForceToApply

• **PendingForceToApply**: [`Vector`](ue_ue_s.Vector.md)

___

### PendingImpulseToApply

• **PendingImpulseToApply**: [`Vector`](ue_ue_s.Vector.md)

___

### PendingLaunchVelocity

• **PendingLaunchVelocity**: [`Vector`](ue_ue_s.Vector.md)

___

### PerchAdditionalHeight

• **PerchAdditionalHeight**: `number`

___

### PerchRadiusThreshold

• **PerchRadiusThreshold**: `number`

___

### PlaneConstraintAxisSetting

• **PlaneConstraintAxisSetting**: [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PlaneConstraintAxisSetting](ue_ue.PawnMovementComponent.md#planeconstraintaxissetting)

___

### PlaneConstraintNormal

• **PlaneConstraintNormal**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PlaneConstraintNormal](ue_ue.PawnMovementComponent.md#planeconstraintnormal)

___

### PlaneConstraintOrigin

• **PlaneConstraintOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PlaneConstraintOrigin](ue_ue.PawnMovementComponent.md#planeconstraintorigin)

___

### PostPhysicsTickFunction

• **PostPhysicsTickFunction**: [`CharacterMovementComponentPostPhysicsTickFunction`](ue_ue.CharacterMovementComponentPostPhysicsTickFunction.md)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[PrimaryComponentTick](ue_ue.PawnMovementComponent.md#primarycomponenttick)

___

### PushForceFactor

• **PushForceFactor**: `number`

___

### PushForcePointZOffsetFactor

• **PushForcePointZOffsetFactor**: `number`

___

### RepulsionForce

• **RepulsionForce**: `number`

___

### RequestedVelocity

• **RequestedVelocity**: [`Vector`](ue_ue_s.Vector.md)

___

### RootMotionParams

• **RootMotionParams**: [`RootMotionMovementParams`](ue_ue.RootMotionMovementParams.md)

___

### RotationRate

• **RotationRate**: [`Rotator`](ue_ue_s.Rotator.md)

___

### ServerLastClientAdjustmentTime

• **ServerLastClientAdjustmentTime**: `number`

___

### ServerLastClientGoodMoveAckTime

• **ServerLastClientGoodMoveAckTime**: `number`

___

### ServerLastTransformUpdateTimeStamp

• **ServerLastTransformUpdateTimeStamp**: `number`

___

### StandingDownwardForceScale

• **StandingDownwardForceScale**: `number`

___

### TouchForceFactor

• **TouchForceFactor**: `number`

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[UCSModifiedProperties](ue_ue.PawnMovementComponent.md#ucsmodifiedproperties)

___

### UpdatedComponent

• **UpdatedComponent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[UpdatedComponent](ue_ue.PawnMovementComponent.md#updatedcomponent)

___

### UpdatedPrimitive

• **UpdatedPrimitive**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[UpdatedPrimitive](ue_ue.PawnMovementComponent.md#updatedprimitive)

___

### UpperImpactNormalScale

• **UpperImpactNormalScale**: `number`

___

### Velocity

• **Velocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Velocity](ue_ue.PawnMovementComponent.md#velocity)

___

### WalkableFloorAngle

• **WalkableFloorAngle**: `number`

___

### WalkableFloorZ

• **WalkableFloorZ**: `number`

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_ActorComponent__](ue_ue.PawnMovementComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_CharacterMovementComponent\_\_

• **\_\_tid\_CharacterMovementComponent\_\_**: `boolean`

___

### \_\_tid\_MovementComponent\_\_

• **\_\_tid\_MovementComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_MovementComponent__](ue_ue.PawnMovementComponent.md#__tid_movementcomponent__)

___

### \_\_tid\_NavMovementComponent\_\_

• **\_\_tid\_NavMovementComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_NavMovementComponent__](ue_ue.PawnMovementComponent.md#__tid_navmovementcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_Object__](ue_ue.PawnMovementComponent.md#__tid_object__)

___

### \_\_tid\_PawnMovementComponent\_\_

• **\_\_tid\_PawnMovementComponent\_\_**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[__tid_PawnMovementComponent__](ue_ue.PawnMovementComponent.md#__tid_pawnmovementcomponent__)

___

### bAllowPhysicsRotationDuringAnimRootMotion

• **bAllowPhysicsRotationDuringAnimRootMotion**: `boolean`

___

### bAlwaysCheckFloor

• **bAlwaysCheckFloor**: `boolean`

___

### bApplyGravityWhileJumping

• **bApplyGravityWhileJumping**: `boolean`

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoActivate](ue_ue.PawnMovementComponent.md#bautoactivate)

___

### bAutoRegisterPhysicsVolumeUpdates

• **bAutoRegisterPhysicsVolumeUpdates**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoRegisterPhysicsVolumeUpdates](ue_ue.PawnMovementComponent.md#bautoregisterphysicsvolumeupdates)

___

### bAutoRegisterUpdatedComponent

• **bAutoRegisterUpdatedComponent**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoRegisterUpdatedComponent](ue_ue.PawnMovementComponent.md#bautoregisterupdatedcomponent)

___

### bAutoUpdateTickRegistration

• **bAutoUpdateTickRegistration**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bAutoUpdateTickRegistration](ue_ue.PawnMovementComponent.md#bautoupdatetickregistration)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bCanEverAffectNavigation](ue_ue.PawnMovementComponent.md#bcaneveraffectnavigation)

___

### bCanWalkOffLedges

• **bCanWalkOffLedges**: `boolean`

___

### bCanWalkOffLedgesWhenCrouching

• **bCanWalkOffLedgesWhenCrouching**: `boolean`

___

### bCheatFlying

• **bCheatFlying**: `boolean`

___

### bComponentShouldUpdatePhysicsVolume

• **bComponentShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bComponentShouldUpdatePhysicsVolume](ue_ue.PawnMovementComponent.md#bcomponentshouldupdatephysicsvolume)

___

### bConstrainToPlane

• **bConstrainToPlane**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bConstrainToPlane](ue_ue.PawnMovementComponent.md#bconstraintoplane)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bCreatedByConstructionScript](ue_ue.PawnMovementComponent.md#bcreatedbyconstructionscript)

___

### bCrouchMaintainsBaseLocation

• **bCrouchMaintainsBaseLocation**: `boolean`

___

### bDeferUpdateMoveComponent

• **bDeferUpdateMoveComponent**: `boolean`

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bEditableWhenInherited](ue_ue.PawnMovementComponent.md#beditablewheninherited)

___

### bEnablePhysicsInteraction

• **bEnablePhysicsInteraction**: `boolean`

___

### bEnableScopedMovementUpdates

• **bEnableScopedMovementUpdates**: `boolean`

___

### bEnableServerDualMoveScopedMovementUpdates

• **bEnableServerDualMoveScopedMovementUpdates**: `boolean`

___

### bFastAttachedMove

• **bFastAttachedMove**: `boolean`

___

### bForceBraking

• **bForceBraking**: `boolean`

___

### bForceMaxAccel

• **bForceMaxAccel**: `boolean`

___

### bForceNextFloorCheck

• **bForceNextFloorCheck**: `boolean`

___

### bHasRequestedVelocity

• **bHasRequestedVelocity**: `boolean`

___

### bIgnoreBaseRotation

• **bIgnoreBaseRotation**: `boolean`

___

### bIgnoreClientMovementErrorChecksAndCorrection

• **bIgnoreClientMovementErrorChecksAndCorrection**: `boolean`

___

### bImpartBaseAngularVelocity

• **bImpartBaseAngularVelocity**: `boolean`

___

### bImpartBaseVelocityX

• **bImpartBaseVelocityX**: `boolean`

___

### bImpartBaseVelocityY

• **bImpartBaseVelocityY**: `boolean`

___

### bImpartBaseVelocityZ

• **bImpartBaseVelocityZ**: `boolean`

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bInstanceComponent](ue_ue.PawnMovementComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bIsActive](ue_ue.PawnMovementComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bIsEditorOnly](ue_ue.PawnMovementComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bIsVisualizationComponent](ue_ue.PawnMovementComponent.md#bisvisualizationcomponent)

___

### bJustTeleported

• **bJustTeleported**: `boolean`

___

### bMaintainHorizontalGroundVelocity

• **bMaintainHorizontalGroundVelocity**: `boolean`

___

### bMovementInProgress

• **bMovementInProgress**: `boolean`

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bNetAddressable](ue_ue.PawnMovementComponent.md#bnetaddressable)

___

### bNetworkAlwaysReplicateTransformUpdateTimestamp

• **bNetworkAlwaysReplicateTransformUpdateTimestamp**: `boolean`

___

### bNetworkMovementModeChanged

• **bNetworkMovementModeChanged**: `boolean`

___

### bNetworkSkipProxyPredictionOnNetUpdate

• **bNetworkSkipProxyPredictionOnNetUpdate**: `boolean`

___

### bNetworkUpdateReceived

• **bNetworkUpdateReceived**: `boolean`

___

### bNotifyApex

• **bNotifyApex**: `boolean`

___

### bOrientRotationToMovement

• **bOrientRotationToMovement**: `boolean`

___

### bPerformingJumpOff

• **bPerformingJumpOff**: `boolean`

___

### bProjectNavMeshOnBothWorldChannels

• **bProjectNavMeshOnBothWorldChannels**: `boolean`

___

### bProjectNavMeshWalking

• **bProjectNavMeshWalking**: `boolean`

___

### bPushForceScaledToMass

• **bPushForceScaledToMass**: `boolean`

___

### bPushForceUsingZOffset

• **bPushForceUsingZOffset**: `boolean`

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bReplicates](ue_ue.PawnMovementComponent.md#breplicates)

___

### bRequestedMoveUseAcceleration

• **bRequestedMoveUseAcceleration**: `boolean`

___

### bRequestedMoveWithMaxSpeed

• **bRequestedMoveWithMaxSpeed**: `boolean`

___

### bRunPhysicsWithNoController

• **bRunPhysicsWithNoController**: `boolean`

___

### bScalePushForceToVelocity

• **bScalePushForceToVelocity**: `boolean`

___

### bServerAcceptClientAuthoritativePosition

• **bServerAcceptClientAuthoritativePosition**: `boolean`

___

### bShrinkProxyCapsule

• **bShrinkProxyCapsule**: `boolean`

___

### bSnapToPlaneAtStart

• **bSnapToPlaneAtStart**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bSnapToPlaneAtStart](ue_ue.PawnMovementComponent.md#bsnaptoplaneatstart)

___

### bSweepWhileNavWalking

• **bSweepWhileNavWalking**: `boolean`

___

### bTickBeforeOwner

• **bTickBeforeOwner**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bTickBeforeOwner](ue_ue.PawnMovementComponent.md#btickbeforeowner)

___

### bTouchForceScaledToMass

• **bTouchForceScaledToMass**: `boolean`

___

### bUpdateNavAgentWithOwnersCollision

• **bUpdateNavAgentWithOwnersCollision**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUpdateNavAgentWithOwnersCollision](ue_ue.PawnMovementComponent.md#bupdatenavagentwithownerscollision)

___

### bUpdateOnlyIfRendered

• **bUpdateOnlyIfRendered**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUpdateOnlyIfRendered](ue_ue.PawnMovementComponent.md#bupdateonlyifrendered)

___

### bUseAccelerationForPaths

• **bUseAccelerationForPaths**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUseAccelerationForPaths](ue_ue.PawnMovementComponent.md#buseaccelerationforpaths)

___

### bUseControllerDesiredRotation

• **bUseControllerDesiredRotation**: `boolean`

___

### bUseFixedBrakingDistanceForPaths

• **bUseFixedBrakingDistanceForPaths**: `boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[bUseFixedBrakingDistanceForPaths](ue_ue.PawnMovementComponent.md#busefixedbrakingdistanceforpaths)

___

### bUseFlatBaseForFloorChecks

• **bUseFlatBaseForFloorChecks**: `boolean`

___

### bUseRVOAvoidance

• **bUseRVOAvoidance**: `boolean`

___

### bUseSeparateBrakingFriction

• **bUseSeparateBrakingFriction**: `boolean`

___

### bWantsToCrouch

• **bWantsToCrouch**: `boolean`

___

### bWantsToLeaveNavWalking

• **bWantsToLeaveNavWalking**: `boolean`

___

### bWasAvoidanceUpdated

• **bWasAvoidanceUpdated**: `boolean`

___

### bWasSimulatingRootMotion

• **bWasSimulatingRootMotion**: `boolean`

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

___

### AddForce

▸ **AddForce**(`Force`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Force` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

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

___

### ClearAccumulatedForces

▸ **ClearAccumulatedForces**(): `void`

#### Returns

`void`

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

___

### ConsumeInputVector

▸ **ConsumeInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ConsumeInputVector](ue_ue.PawnMovementComponent.md#consumeinputvector)

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

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[Deactivate](ue_ue.PawnMovementComponent.md#deactivate)

___

### DisableMovement

▸ **DisableMovement**(): `void`

#### Returns

`void`

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

___

### GetAnalogInputModifier

▸ **GetAnalogInputModifier**(): `number`

#### Returns

`number`

___

### GetCharacterOwner

▸ **GetCharacterOwner**(): [`Character`](ue_ue.Character.md)

#### Returns

[`Character`](ue_ue.Character.md)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetClass](ue_ue.PawnMovementComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetComponentTickInterval](ue_ue.PawnMovementComponent.md#getcomponenttickinterval)

___

### GetCurrentAcceleration

▸ **GetCurrentAcceleration**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetGravityZ

▸ **GetGravityZ**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetGravityZ](ue_ue.PawnMovementComponent.md#getgravityz)

___

### GetImpartedMovementBaseVelocity

▸ **GetImpartedMovementBaseVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetLastInputVector

▸ **GetLastInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetLastInputVector](ue_ue.PawnMovementComponent.md#getlastinputvector)

___

### GetLastUpdateLocation

▸ **GetLastUpdateLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetLastUpdateRotation

▸ **GetLastUpdateRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### GetLastUpdateVelocity

▸ **GetLastUpdateVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetMaxAcceleration

▸ **GetMaxAcceleration**(): `number`

#### Returns

`number`

___

### GetMaxBrakingDeceleration

▸ **GetMaxBrakingDeceleration**(): `number`

#### Returns

`number`

___

### GetMaxJumpHeight

▸ **GetMaxJumpHeight**(): `number`

#### Returns

`number`

___

### GetMaxJumpHeightWithJumpTime

▸ **GetMaxJumpHeightWithJumpTime**(): `number`

#### Returns

`number`

___

### GetMaxSpeed

▸ **GetMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetMaxSpeed](ue_ue.PawnMovementComponent.md#getmaxspeed)

___

### GetMinAnalogSpeed

▸ **GetMinAnalogSpeed**(): `number`

#### Returns

`number`

___

### GetMovementBase

▸ **GetMovementBase**(): [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Returns

[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetName](ue_ue.PawnMovementComponent.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetOuter](ue_ue.PawnMovementComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetOwner](ue_ue.PawnMovementComponent.md#getowner)

___

### GetPawnOwner

▸ **GetPawnOwner**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPawnOwner](ue_ue.PawnMovementComponent.md#getpawnowner)

___

### GetPendingInputVector

▸ **GetPendingInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPendingInputVector](ue_ue.PawnMovementComponent.md#getpendinginputvector)

___

### GetPerchRadiusThreshold

▸ **GetPerchRadiusThreshold**(): `number`

#### Returns

`number`

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPhysicsVolume](ue_ue.PawnMovementComponent.md#getphysicsvolume)

___

### GetPlaneConstraintAxisSetting

▸ **GetPlaneConstraintAxisSetting**(): [`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Returns

[`EPlaneConstraintAxisSetting`](../enums/ue_ue.EPlaneConstraintAxisSetting.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPlaneConstraintAxisSetting](ue_ue.PawnMovementComponent.md#getplaneconstraintaxissetting)

___

### GetPlaneConstraintNormal

▸ **GetPlaneConstraintNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPlaneConstraintNormal](ue_ue.PawnMovementComponent.md#getplaneconstraintnormal)

___

### GetPlaneConstraintOrigin

▸ **GetPlaneConstraintOrigin**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetPlaneConstraintOrigin](ue_ue.PawnMovementComponent.md#getplaneconstraintorigin)

___

### GetValidPerchRadius

▸ **GetValidPerchRadius**(): `number`

#### Returns

`number`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[GetWorld](ue_ue.PawnMovementComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsActive](ue_ue.PawnMovementComponent.md#isactive)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsBeingDestroyed](ue_ue.PawnMovementComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsComponentTickEnabled](ue_ue.PawnMovementComponent.md#iscomponenttickenabled)

___

### IsCrouching

▸ **IsCrouching**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsCrouching](ue_ue.PawnMovementComponent.md#iscrouching)

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

___

### IsFalling

▸ **IsFalling**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsFalling](ue_ue.PawnMovementComponent.md#isfalling)

___

### IsFlying

▸ **IsFlying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsFlying](ue_ue.PawnMovementComponent.md#isflying)

___

### IsMoveInputIgnored

▸ **IsMoveInputIgnored**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsMoveInputIgnored](ue_ue.PawnMovementComponent.md#ismoveinputignored)

___

### IsMovingOnGround

▸ **IsMovingOnGround**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsMovingOnGround](ue_ue.PawnMovementComponent.md#ismovingonground)

___

### IsSwimming

▸ **IsSwimming**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[IsSwimming](ue_ue.PawnMovementComponent.md#isswimming)

___

### IsWalkable

▸ **IsWalkable**(`Hit`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hit` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

`boolean`

___

### IsWalking

▸ **IsWalking**(): `boolean`

#### Returns

`boolean`

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

___

### K2\_GetInputVector

▸ **K2_GetInputVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_GetInputVector](ue_ue.PawnMovementComponent.md#k2_getinputvector)

___

### K2\_GetMaxSpeedModifier

▸ **K2_GetMaxSpeedModifier**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_GetMaxSpeedModifier](ue_ue.PawnMovementComponent.md#k2_getmaxspeedmodifier)

___

### K2\_GetModifiedMaxAcceleration

▸ **K2_GetModifiedMaxAcceleration**(): `number`

#### Returns

`number`

___

### K2\_GetModifiedMaxSpeed

▸ **K2_GetModifiedMaxSpeed**(): `number`

#### Returns

`number`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[K2_GetModifiedMaxSpeed](ue_ue.PawnMovementComponent.md#k2_getmodifiedmaxspeed)

___

### K2\_GetWalkableFloorAngle

▸ **K2_GetWalkableFloorAngle**(): `number`

#### Returns

`number`

___

### K2\_GetWalkableFloorZ

▸ **K2_GetWalkableFloorZ**(): `number`

#### Returns

`number`

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

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[OnRep_IsActive](ue_ue.PawnMovementComponent.md#onrep_isactive)

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

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ReceiveBeginPlay](ue_ue.PawnMovementComponent.md#receivebeginplay)

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

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[RegisterComponent](ue_ue.PawnMovementComponent.md#registercomponent)

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

___

### SetAvoidanceEnabled

▸ **SetAvoidanceEnabled**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

___

### SetAvoidanceGroup

▸ **SetAvoidanceGroup**(`GroupFlags`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupFlags` | `number` |

#### Returns

`void`

___

### SetAvoidanceGroupMask

▸ **SetAvoidanceGroupMask**(`GroupMask`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupMask` | [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md) |

#### Returns

`void`

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

___

### SetGroupsToAvoid

▸ **SetGroupsToAvoid**(`GroupFlags`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupFlags` | `number` |

#### Returns

`void`

___

### SetGroupsToAvoidMask

▸ **SetGroupsToAvoidMask**(`GroupMask`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupMask` | [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md) |

#### Returns

`void`

___

### SetGroupsToIgnore

▸ **SetGroupsToIgnore**(`GroupFlags`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupFlags` | `number` |

#### Returns

`void`

___

### SetGroupsToIgnoreMask

▸ **SetGroupsToIgnoreMask**(`GroupMask`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GroupMask` | [`NavAvoidanceMask`](ue_ue.NavAvoidanceMask.md) |

#### Returns

`void`

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

___

### SetWalkableFloorAngle

▸ **SetWalkableFloorAngle**(`InWalkableFloorAngle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InWalkableFloorAngle` | `number` |

#### Returns

`void`

___

### SetWalkableFloorZ

▸ **SetWalkableFloorZ**(`InWalkableFloorZ`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InWalkableFloorZ` | `number` |

#### Returns

`void`

___

### SnapUpdatedComponentToPlane

▸ **SnapUpdatedComponentToPlane**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[SnapUpdatedComponentToPlane](ue_ue.PawnMovementComponent.md#snapupdatedcomponenttoplane)

___

### StopActiveMovement

▸ **StopActiveMovement**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StopActiveMovement](ue_ue.PawnMovementComponent.md#stopactivemovement)

___

### StopMovementImmediately

▸ **StopMovementImmediately**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StopMovementImmediately](ue_ue.PawnMovementComponent.md#stopmovementimmediately)

___

### StopMovementKeepPathing

▸ **StopMovementKeepPathing**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StopMovementKeepPathing](ue_ue.PawnMovementComponent.md#stopmovementkeeppathing)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[ToggleActive](ue_ue.PawnMovementComponent.md#toggleactive)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PawnMovementComponent](ue_ue.PawnMovementComponent.md).[StaticClass](ue_ue.PawnMovementComponent.md#staticclass)
