[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Engine

# Class: Engine

[ue/ue](../modules/ue_ue.md).Engine

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Engine`**

  ↳↳ [`EditorEngine`](ue_ue.EditorEngine.md)

  ↳↳ [`GameEngine`](ue_ue.GameEngine.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Engine-1.md#constructor)

### Properties

- [AIControllerClassName](ue_ue.Engine-1.md#aicontrollerclassname)
- [ActiveClassRedirects](ue_ue.Engine-1.md#activeclassredirects)
- [ActiveGameNameRedirects](ue_ue.Engine-1.md#activegamenameredirects)
- [ActivePluginRedirects](ue_ue.Engine-1.md#activepluginredirects)
- [ActiveStructRedirects](ue_ue.Engine-1.md#activestructredirects)
- [AdditionalFontNames](ue_ue.Engine-1.md#additionalfontnames)
- [AdditionalFonts](ue_ue.Engine-1.md#additionalfonts)
- [ArrowMaterial](ue_ue.Engine-1.md#arrowmaterial)
- [ArrowMaterialName](ue_ue.Engine-1.md#arrowmaterialname)
- [ArrowMaterialYellow](ue_ue.Engine-1.md#arrowmaterialyellow)
- [AssetManager](ue_ue.Engine-1.md#assetmanager)
- [AssetManagerClassName](ue_ue.Engine-1.md#assetmanagerclassname)
- [AvoidanceManagerClass](ue_ue.Engine-1.md#avoidancemanagerclass)
- [AvoidanceManagerClassName](ue_ue.Engine-1.md#avoidancemanagerclassname)
- [BSPSelectionHighlightIntensity](ue_ue.Engine-1.md#bspselectionhighlightintensity)
- [BlueNoiseTexture](ue_ue.Engine-1.md#bluenoisetexture)
- [BlueNoiseTextureName](ue_ue.Engine-1.md#bluenoisetexturename)
- [BoneWeightMaterial](ue_ue.Engine-1.md#boneweightmaterial)
- [BoneWeightMaterialName](ue_ue.Engine-1.md#boneweightmaterialname)
- [C\_AddWire](ue_ue.Engine-1.md#c_addwire)
- [C\_BSPCollision](ue_ue.Engine-1.md#c_bspcollision)
- [C\_BrushShape](ue_ue.Engine-1.md#c_brushshape)
- [C\_BrushWire](ue_ue.Engine-1.md#c_brushwire)
- [C\_NonSolidWire](ue_ue.Engine-1.md#c_nonsolidwire)
- [C\_OrthoBackground](ue_ue.Engine-1.md#c_orthobackground)
- [C\_ScaleBoxHi](ue_ue.Engine-1.md#c_scaleboxhi)
- [C\_SemiSolidWire](ue_ue.Engine-1.md#c_semisolidwire)
- [C\_SubtractWire](ue_ue.Engine-1.md#c_subtractwire)
- [C\_Volume](ue_ue.Engine-1.md#c_volume)
- [C\_VolumeCollision](ue_ue.Engine-1.md#c_volumecollision)
- [C\_WireBackground](ue_ue.Engine-1.md#c_wirebackground)
- [C\_WorldBox](ue_ue.Engine-1.md#c_worldbox)
- [CameraRotationThreshold](ue_ue.Engine-1.md#camerarotationthreshold)
- [CameraTranslationThreshold](ue_ue.Engine-1.md#cameratranslationthreshold)
- [ClientCycles](ue_ue.Engine-1.md#clientcycles)
- [ClothPaintMaterial](ue_ue.Engine-1.md#clothpaintmaterial)
- [ClothPaintMaterialInstance](ue_ue.Engine-1.md#clothpaintmaterialinstance)
- [ClothPaintMaterialName](ue_ue.Engine-1.md#clothpaintmaterialname)
- [ClothPaintMaterialWireframe](ue_ue.Engine-1.md#clothpaintmaterialwireframe)
- [ClothPaintMaterialWireframeInstance](ue_ue.Engine-1.md#clothpaintmaterialwireframeinstance)
- [ClothPaintMaterialWireframeName](ue_ue.Engine-1.md#clothpaintmaterialwireframename)
- [ConsoleClass](ue_ue.Engine-1.md#consoleclass)
- [ConsoleClassName](ue_ue.Engine-1.md#consoleclassname)
- [ConstraintLimitMaterial](ue_ue.Engine-1.md#constraintlimitmaterial)
- [ConstraintLimitMaterialPrismatic](ue_ue.Engine-1.md#constraintlimitmaterialprismatic)
- [ConstraintLimitMaterialX](ue_ue.Engine-1.md#constraintlimitmaterialx)
- [ConstraintLimitMaterialXAxis](ue_ue.Engine-1.md#constraintlimitmaterialxaxis)
- [ConstraintLimitMaterialY](ue_ue.Engine-1.md#constraintlimitmaterialy)
- [ConstraintLimitMaterialYAxis](ue_ue.Engine-1.md#constraintlimitmaterialyaxis)
- [ConstraintLimitMaterialZ](ue_ue.Engine-1.md#constraintlimitmaterialz)
- [ConstraintLimitMaterialZAxis](ue_ue.Engine-1.md#constraintlimitmaterialzaxis)
- [CurrentCustomTimeStep](ue_ue.Engine-1.md#currentcustomtimestep)
- [CustomTimeStepClassName](ue_ue.Engine-1.md#customtimestepclassname)
- [CustomTimecodeProvider](ue_ue.Engine-1.md#customtimecodeprovider)
- [DebugEditorMaterial](ue_ue.Engine-1.md#debugeditormaterial)
- [DebugEditorMaterialName](ue_ue.Engine-1.md#debugeditormaterialname)
- [DebugMeshMaterial](ue_ue.Engine-1.md#debugmeshmaterial)
- [DebugMeshMaterialName](ue_ue.Engine-1.md#debugmeshmaterialname)
- [DefaultBSPVertexTexture](ue_ue.Engine-1.md#defaultbspvertextexture)
- [DefaultBSPVertexTextureName](ue_ue.Engine-1.md#defaultbspvertextexturename)
- [DefaultBloomKernelTexture](ue_ue.Engine-1.md#defaultbloomkerneltexture)
- [DefaultBloomKernelTextureName](ue_ue.Engine-1.md#defaultbloomkerneltexturename)
- [DefaultBlueprintBaseClassName](ue_ue.Engine-1.md#defaultblueprintbaseclassname)
- [DefaultBokehTexture](ue_ue.Engine-1.md#defaultbokehtexture)
- [DefaultBokehTextureName](ue_ue.Engine-1.md#defaultbokehtexturename)
- [DefaultCustomTimeStep](ue_ue.Engine-1.md#defaultcustomtimestep)
- [DefaultDiffuseTexture](ue_ue.Engine-1.md#defaultdiffusetexture)
- [DefaultDiffuseTextureName](ue_ue.Engine-1.md#defaultdiffusetexturename)
- [DefaultPhysMaterial](ue_ue.Engine-1.md#defaultphysmaterial)
- [DefaultPhysMaterialName](ue_ue.Engine-1.md#defaultphysmaterialname)
- [DefaultSelectedMaterialColor](ue_ue.Engine-1.md#defaultselectedmaterialcolor)
- [DefaultTexture](ue_ue.Engine-1.md#defaulttexture)
- [DefaultTextureName](ue_ue.Engine-1.md#defaulttexturename)
- [DefaultTimecodeFrameRate](ue_ue.Engine-1.md#defaulttimecodeframerate)
- [DefaultTimecodeProvider](ue_ue.Engine-1.md#defaulttimecodeprovider)
- [DefaultTimecodeProviderClassName](ue_ue.Engine-1.md#defaulttimecodeproviderclassname)
- [DeferredCommands](ue_ue.Engine-1.md#deferredcommands)
- [DisplayGamma](ue_ue.Engine-1.md#displaygamma)
- [EditorBrushMaterial](ue_ue.Engine-1.md#editorbrushmaterial)
- [EditorBrushMaterialName](ue_ue.Engine-1.md#editorbrushmaterialname)
- [EmissiveMeshMaterial](ue_ue.Engine-1.md#emissivemeshmaterial)
- [EmissiveMeshMaterialName](ue_ue.Engine-1.md#emissivemeshmaterialname)
- [FixedFrameRate](ue_ue.Engine-1.md#fixedframerate)
- [GameCycles](ue_ue.Engine-1.md#gamecycles)
- [GameScreenshotSaveDirectory](ue_ue.Engine-1.md#gamescreenshotsavedirectory)
- [GameSingleton](ue_ue.Engine-1.md#gamesingleton)
- [GameSingletonClassName](ue_ue.Engine-1.md#gamesingletonclassname)
- [GameUserSettings](ue_ue.Engine-1.md#gameusersettings)
- [GameUserSettingsClass](ue_ue.Engine-1.md#gameusersettingsclass)
- [GameUserSettingsClassName](ue_ue.Engine-1.md#gameusersettingsclassname)
- [GameViewport](ue_ue.Engine-1.md#gameviewport)
- [GameViewportClientClass](ue_ue.Engine-1.md#gameviewportclientclass)
- [GameViewportClientClassName](ue_ue.Engine-1.md#gameviewportclientclassname)
- [GeomMaterial](ue_ue.Engine-1.md#geommaterial)
- [GeomMaterialName](ue_ue.Engine-1.md#geommaterialname)
- [HLODColorationColors](ue_ue.Engine-1.md#hlodcolorationcolors)
- [HairDebugMaterial](ue_ue.Engine-1.md#hairdebugmaterial)
- [HairDebugMaterialName](ue_ue.Engine-1.md#hairdebugmaterialname)
- [HairDefaultMaterial](ue_ue.Engine-1.md#hairdefaultmaterial)
- [HairDefaultMaterialName](ue_ue.Engine-1.md#hairdefaultmaterialname)
- [HighFrequencyNoiseTexture](ue_ue.Engine-1.md#highfrequencynoisetexture)
- [HighFrequencyNoiseTextureName](ue_ue.Engine-1.md#highfrequencynoisetexturename)
- [IdealLightMapDensity](ue_ue.Engine-1.md#ideallightmapdensity)
- [InvalidLightmapSettingsMaterial](ue_ue.Engine-1.md#invalidlightmapsettingsmaterial)
- [InvalidLightmapSettingsMaterialName](ue_ue.Engine-1.md#invalidlightmapsettingsmaterialname)
- [LODColorationColors](ue_ue.Engine-1.md#lodcolorationcolors)
- [LargeFont](ue_ue.Engine-1.md#largefont)
- [LargeFontName](ue_ue.Engine-1.md#largefontname)
- [LevelColorationLitMaterial](ue_ue.Engine-1.md#levelcolorationlitmaterial)
- [LevelColorationLitMaterialName](ue_ue.Engine-1.md#levelcolorationlitmaterialname)
- [LevelColorationUnlitMaterial](ue_ue.Engine-1.md#levelcolorationunlitmaterial)
- [LevelColorationUnlitMaterialName](ue_ue.Engine-1.md#levelcolorationunlitmaterialname)
- [LevelScriptActorClass](ue_ue.Engine-1.md#levelscriptactorclass)
- [LevelScriptActorClassName](ue_ue.Engine-1.md#levelscriptactorclassname)
- [LightComplexityColors](ue_ue.Engine-1.md#lightcomplexitycolors)
- [LightMapDensitySelectedColor](ue_ue.Engine-1.md#lightmapdensityselectedcolor)
- [LightMapDensityTexture](ue_ue.Engine-1.md#lightmapdensitytexture)
- [LightMapDensityTextureName](ue_ue.Engine-1.md#lightmapdensitytexturename)
- [LightMapDensityVertexMappedColor](ue_ue.Engine-1.md#lightmapdensityvertexmappedcolor)
- [LightingOnlyBrightness](ue_ue.Engine-1.md#lightingonlybrightness)
- [LightingTexelDensityMaterial](ue_ue.Engine-1.md#lightingtexeldensitymaterial)
- [LightingTexelDensityName](ue_ue.Engine-1.md#lightingtexeldensityname)
- [LocalPlayerClass](ue_ue.Engine-1.md#localplayerclass)
- [LocalPlayerClassName](ue_ue.Engine-1.md#localplayerclassname)
- [MaxES2PixelShaderAdditiveComplexityCount](ue_ue.Engine-1.md#maxes2pixelshaderadditivecomplexitycount)
- [MaxES3PixelShaderAdditiveComplexityCount](ue_ue.Engine-1.md#maxes3pixelshaderadditivecomplexitycount)
- [MaxLightMapDensity](ue_ue.Engine-1.md#maxlightmapdensity)
- [MaxOcclusionPixelsFraction](ue_ue.Engine-1.md#maxocclusionpixelsfraction)
- [MaxParticleResize](ue_ue.Engine-1.md#maxparticleresize)
- [MaxParticleResizeWarn](ue_ue.Engine-1.md#maxparticleresizewarn)
- [MaxPixelShaderAdditiveComplexityCount](ue_ue.Engine-1.md#maxpixelshaderadditivecomplexitycount)
- [MaximumLoopIterationCount](ue_ue.Engine-1.md#maximumloopiterationcount)
- [MediumFont](ue_ue.Engine-1.md#mediumfont)
- [MediumFontName](ue_ue.Engine-1.md#mediumfontname)
- [MeshLODRange](ue_ue.Engine-1.md#meshlodrange)
- [MinDesiredFrameRate](ue_ue.Engine-1.md#mindesiredframerate)
- [MinLightMapDensity](ue_ue.Engine-1.md#minlightmapdensity)
- [MiniFontTexture](ue_ue.Engine-1.md#minifonttexture)
- [MiniFontTextureName](ue_ue.Engine-1.md#minifonttexturename)
- [NavigationSystemClass](ue_ue.Engine-1.md#navigationsystemclass)
- [NavigationSystemClassName](ue_ue.Engine-1.md#navigationsystemclassname)
- [NavigationSystemConfigClass](ue_ue.Engine-1.md#navigationsystemconfigclass)
- [NavigationSystemConfigClassName](ue_ue.Engine-1.md#navigationsystemconfigclassname)
- [NearClipPlane](ue_ue.Engine-1.md#nearclipplane)
- [NetClientTicksPerSecond](ue_ue.Engine-1.md#netclienttickspersecond)
- [NetDriverDefinitions](ue_ue.Engine-1.md#netdriverdefinitions)
- [NetErrorLogInterval](ue_ue.Engine-1.md#neterrorloginterval)
- [NextWorldContextHandle](ue_ue.Engine-1.md#nextworldcontexthandle)
- [NumPawnsAllowedToBeSpawnedInAFrame](ue_ue.Engine-1.md#numpawnsallowedtobespawnedinaframe)
- [ParticleEventManagerClassPath](ue_ue.Engine-1.md#particleeventmanagerclasspath)
- [PendingDroppedNotes](ue_ue.Engine-1.md#pendingdroppednotes)
- [PhysicsCollisionHandlerClass](ue_ue.Engine-1.md#physicscollisionhandlerclass)
- [PhysicsCollisionHandlerClassName](ue_ue.Engine-1.md#physicscollisionhandlerclassname)
- [PreIntegratedSkinBRDFTexture](ue_ue.Engine-1.md#preintegratedskinbrdftexture)
- [PreIntegratedSkinBRDFTextureName](ue_ue.Engine-1.md#preintegratedskinbrdftexturename)
- [PreviewShadowsIndicatorMaterial](ue_ue.Engine-1.md#previewshadowsindicatormaterial)
- [PreviewShadowsIndicatorMaterialName](ue_ue.Engine-1.md#previewshadowsindicatormaterialname)
- [PrimitiveProbablyVisibleTime](ue_ue.Engine-1.md#primitiveprobablyvisibletime)
- [QuadComplexityColors](ue_ue.Engine-1.md#quadcomplexitycolors)
- [RemoveSurfaceMaterial](ue_ue.Engine-1.md#removesurfacematerial)
- [RemoveSurfaceMaterialName](ue_ue.Engine-1.md#removesurfacematerialname)
- [RenderLightMapDensityColorScale](ue_ue.Engine-1.md#renderlightmapdensitycolorscale)
- [RenderLightMapDensityGrayscaleScale](ue_ue.Engine-1.md#renderlightmapdensitygrayscalescale)
- [RuntimeServerActors](ue_ue.Engine-1.md#runtimeserveractors)
- [ScreenSaverInhibitorSemaphore](ue_ue.Engine-1.md#screensaverinhibitorsemaphore)
- [SelectedMaterialColor](ue_ue.Engine-1.md#selectedmaterialcolor)
- [SelectedMaterialColorOverride](ue_ue.Engine-1.md#selectedmaterialcoloroverride)
- [SelectionHighlightIntensity](ue_ue.Engine-1.md#selectionhighlightintensity)
- [SelectionHighlightIntensityBillboards](ue_ue.Engine-1.md#selectionhighlightintensitybillboards)
- [SelectionOutlineColor](ue_ue.Engine-1.md#selectionoutlinecolor)
- [ServerActors](ue_ue.Engine-1.md#serveractors)
- [ShadedLevelColorationLitMaterial](ue_ue.Engine-1.md#shadedlevelcolorationlitmaterial)
- [ShadedLevelColorationLitMaterialName](ue_ue.Engine-1.md#shadedlevelcolorationlitmaterialname)
- [ShadedLevelColorationUnlitMaterial](ue_ue.Engine-1.md#shadedlevelcolorationunlitmaterial)
- [ShadedLevelColorationUnlitMaterialName](ue_ue.Engine-1.md#shadedlevelcolorationunlitmaterialname)
- [ShaderComplexityColors](ue_ue.Engine-1.md#shadercomplexitycolors)
- [SmallFont](ue_ue.Engine-1.md#smallfont)
- [SmallFontName](ue_ue.Engine-1.md#smallfontname)
- [SmoothedFrameRateRange](ue_ue.Engine-1.md#smoothedframeraterange)
- [StatColorMappings](ue_ue.Engine-1.md#statcolormappings)
- [StationaryLightOverlapColors](ue_ue.Engine-1.md#stationarylightoverlapcolors)
- [StreamingAccuracyColors](ue_ue.Engine-1.md#streamingaccuracycolors)
- [StreamingDistanceFactor](ue_ue.Engine-1.md#streamingdistancefactor)
- [SubduedSelectionOutlineColor](ue_ue.Engine-1.md#subduedselectionoutlinecolor)
- [SubtitleFont](ue_ue.Engine-1.md#subtitlefont)
- [SubtitleFontName](ue_ue.Engine-1.md#subtitlefontname)
- [TickCycles](ue_ue.Engine-1.md#tickcycles)
- [TimecodeProviderClassName](ue_ue.Engine-1.md#timecodeproviderclassname)
- [TinyFont](ue_ue.Engine-1.md#tinyfont)
- [TinyFontName](ue_ue.Engine-1.md#tinyfontname)
- [TransitionDescription](ue_ue.Engine-1.md#transitiondescription)
- [TransitionGameMode](ue_ue.Engine-1.md#transitiongamemode)
- [TransitionType](ue_ue.Engine-1.md#transitiontype)
- [VertexColorMaterial](ue_ue.Engine-1.md#vertexcolormaterial)
- [VertexColorMaterialName](ue_ue.Engine-1.md#vertexcolormaterialname)
- [VertexColorViewModeMaterialName\_AlphaAsColor](ue_ue.Engine-1.md#vertexcolorviewmodematerialname_alphaascolor)
- [VertexColorViewModeMaterialName\_BlueOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerialname_blueonly)
- [VertexColorViewModeMaterialName\_ColorOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerialname_coloronly)
- [VertexColorViewModeMaterialName\_GreenOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerialname_greenonly)
- [VertexColorViewModeMaterialName\_RedOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerialname_redonly)
- [VertexColorViewModeMaterial\_AlphaAsColor](ue_ue.Engine-1.md#vertexcolorviewmodematerial_alphaascolor)
- [VertexColorViewModeMaterial\_BlueOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerial_blueonly)
- [VertexColorViewModeMaterial\_ColorOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerial_coloronly)
- [VertexColorViewModeMaterial\_GreenOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerial_greenonly)
- [VertexColorViewModeMaterial\_RedOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerial_redonly)
- [WeightMapPlaceholderTexture](ue_ue.Engine-1.md#weightmapplaceholdertexture)
- [WeightMapPlaceholderTextureName](ue_ue.Engine-1.md#weightmapplaceholdertexturename)
- [WireframeMaterial](ue_ue.Engine-1.md#wireframematerial)
- [WireframeMaterialName](ue_ue.Engine-1.md#wireframematerialname)
- [WorldSettingsClass](ue_ue.Engine-1.md#worldsettingsclass)
- [WorldSettingsClassName](ue_ue.Engine-1.md#worldsettingsclassname)
- [\_\_tid\_Engine\_\_](ue_ue.Engine-1.md#__tid_engine__)
- [\_\_tid\_Object\_\_](ue_ue.Engine-1.md#__tid_object__)
- [bAllowMatureLanguage](ue_ue.Engine-1.md#ballowmaturelanguage)
- [bAllowMultiThreadedAnimationUpdate](ue_ue.Engine-1.md#ballowmultithreadedanimationupdate)
- [bCanBlueprintsTickByDefault](ue_ue.Engine-1.md#bcanblueprintstickbydefault)
- [bCheckForMultiplePawnsSpawnedInAFrame](ue_ue.Engine-1.md#bcheckformultiplepawnsspawnedinaframe)
- [bDisableAILogging](ue_ue.Engine-1.md#bdisableailogging)
- [bEnableEditorPSysRealtimeLOD](ue_ue.Engine-1.md#benableeditorpsysrealtimelod)
- [bEnableOnScreenDebugMessages](ue_ue.Engine-1.md#benableonscreendebugmessages)
- [bEnableOnScreenDebugMessagesDisplay](ue_ue.Engine-1.md#benableonscreendebugmessagesdisplay)
- [bEnableVisualLogRecordingOnStart](ue_ue.Engine-1.md#benablevisuallogrecordingonstart)
- [bHardwareSurveyEnabled](ue_ue.Engine-1.md#bhardwaresurveyenabled)
- [bIsOverridingSelectedColor](ue_ue.Engine-1.md#bisoverridingselectedcolor)
- [bLockReadOnlyLevels](ue_ue.Engine-1.md#blockreadonlylevels)
- [bOptimizeAnimBlueprintMemberVariableAccess](ue_ue.Engine-1.md#boptimizeanimblueprintmembervariableaccess)
- [bPauseOnLossOfFocus](ue_ue.Engine-1.md#bpauseonlossoffocus)
- [bRenderLightMapDensityGrayscale](ue_ue.Engine-1.md#brenderlightmapdensitygrayscale)
- [bShouldGenerateLowQualityLightmaps](ue_ue.Engine-1.md#bshouldgeneratelowqualitylightmaps)
- [bSmoothFrameRate](ue_ue.Engine-1.md#bsmoothframerate)
- [bStartedLoadMapMovie](ue_ue.Engine-1.md#bstartedloadmapmovie)
- [bSubtitlesEnabled](ue_ue.Engine-1.md#bsubtitlesenabled)
- [bSubtitlesForcedOff](ue_ue.Engine-1.md#bsubtitlesforcedoff)
- [bSuppressMapWarnings](ue_ue.Engine-1.md#bsuppressmapwarnings)
- [bUseFixedFrameRate](ue_ue.Engine-1.md#busefixedframerate)

### Methods

- [CreateDefaultSubobject](ue_ue.Engine-1.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Engine-1.md#executeubergraph)
- [GetClass](ue_ue.Engine-1.md#getclass)
- [GetName](ue_ue.Engine-1.md#getname)
- [GetOuter](ue_ue.Engine-1.md#getouter)
- [GetWorld](ue_ue.Engine-1.md#getworld)
- [Find](ue_ue.Engine-1.md#find)
- [Load](ue_ue.Engine-1.md#load)
- [StaticClass](ue_ue.Engine-1.md#staticclass)

## Constructors

### constructor

• **new Engine**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:32650](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32650)

## Properties

### AIControllerClassName

• **AIControllerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32681](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32681)

___

### ActiveClassRedirects

• **ActiveClassRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClassRedirect`](ue_ue.ClassRedirect.md)\>

#### Defined in

[ue/ue.d.ts:32788](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32788)

___

### ActiveGameNameRedirects

• **ActiveGameNameRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameNameRedirect`](ue_ue.GameNameRedirect.md)\>

#### Defined in

[ue/ue.d.ts:32787](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32787)

___

### ActivePluginRedirects

• **ActivePluginRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PluginRedirect`](ue_ue.PluginRedirect.md)\>

#### Defined in

[ue/ue.d.ts:32789](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32789)

___

### ActiveStructRedirects

• **ActiveStructRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StructRedirect`](ue_ue.StructRedirect.md)\>

#### Defined in

[ue/ue.d.ts:32790](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32790)

___

### AdditionalFontNames

• **AdditionalFontNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:32662](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32662)

___

### AdditionalFonts

• **AdditionalFonts**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Font`](ue_ue.Font.md)\>

#### Defined in

[ue/ue.d.ts:32661](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32661)

___

### ArrowMaterial

• **ArrowMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32760](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32760)

___

### ArrowMaterialName

• **ArrowMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32762](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32762)

___

### ArrowMaterialYellow

• **ArrowMaterialYellow**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:32761](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32761)

___

### AssetManager

• **AssetManager**: [`AssetManager`](ue_ue.AssetManager.md)

#### Defined in

[ue/ue.d.ts:32689](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32689)

___

### AssetManagerClassName

• **AssetManagerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32688](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32688)

___

### AvoidanceManagerClass

• **AvoidanceManagerClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:32676](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32676)

___

### AvoidanceManagerClassName

• **AvoidanceManagerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32675](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32675)

___

### BSPSelectionHighlightIntensity

• **BSPSelectionHighlightIntensity**: `number`

#### Defined in

[ue/ue.d.ts:32876](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32876)

___

### BlueNoiseTexture

• **BlueNoiseTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:32793](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32793)

___

### BlueNoiseTextureName

• **BlueNoiseTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32794](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32794)

___

### BoneWeightMaterial

• **BoneWeightMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32738)

___

### BoneWeightMaterialName

• **BoneWeightMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32739)

___

### C\_AddWire

• **C\_AddWire**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:32832](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32832)

___

### C\_BSPCollision

• **C\_BSPCollision**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:32839](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32839)

___

### C\_BrushShape

• **C\_BrushShape**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:32842](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32842)

___

### C\_BrushWire

• **C\_BrushWire**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:32831](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32831)

___

### C\_NonSolidWire

• **C\_NonSolidWire**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:32835](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32835)

___

### C\_OrthoBackground

• **C\_OrthoBackground**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:32840](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32840)

___

### C\_ScaleBoxHi

• **C\_ScaleBoxHi**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:32837](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32837)

___

### C\_SemiSolidWire

• **C\_SemiSolidWire**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:32834](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32834)

___

### C\_SubtractWire

• **C\_SubtractWire**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:32833](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32833)

___

### C\_Volume

• **C\_Volume**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:32841](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32841)

___

### C\_VolumeCollision

• **C\_VolumeCollision**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:32838](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32838)

___

### C\_WireBackground

• **C\_WireBackground**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:32836](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32836)

___

### C\_WorldBox

• **C\_WorldBox**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:32830](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32830)

___

### CameraRotationThreshold

• **CameraRotationThreshold**: `number`

#### Defined in

[ue/ue.d.ts:32850](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32850)

___

### CameraTranslationThreshold

• **CameraTranslationThreshold**: `number`

#### Defined in

[ue/ue.d.ts:32851](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32851)

___

### ClientCycles

• **ClientCycles**: `number`

#### Defined in

[ue/ue.d.ts:32805](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32805)

___

### ClothPaintMaterial

• **ClothPaintMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32740)

___

### ClothPaintMaterialInstance

• **ClothPaintMaterialInstance**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:32742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32742)

___

### ClothPaintMaterialName

• **ClothPaintMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32744)

___

### ClothPaintMaterialWireframe

• **ClothPaintMaterialWireframe**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32741)

___

### ClothPaintMaterialWireframeInstance

• **ClothPaintMaterialWireframeInstance**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:32743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32743)

___

### ClothPaintMaterialWireframeName

• **ClothPaintMaterialWireframeName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32745)

___

### ConsoleClass

• **ConsoleClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:32663](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32663)

___

### ConsoleClassName

• **ConsoleClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32664](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32664)

___

### ConstraintLimitMaterial

• **ConstraintLimitMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32748](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32748)

___

### ConstraintLimitMaterialPrismatic

• **ConstraintLimitMaterialPrismatic**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:32755](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32755)

___

### ConstraintLimitMaterialX

• **ConstraintLimitMaterialX**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:32749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32749)

___

### ConstraintLimitMaterialXAxis

• **ConstraintLimitMaterialXAxis**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:32750](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32750)

___

### ConstraintLimitMaterialY

• **ConstraintLimitMaterialY**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:32751](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32751)

___

### ConstraintLimitMaterialYAxis

• **ConstraintLimitMaterialYAxis**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:32752](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32752)

___

### ConstraintLimitMaterialZ

• **ConstraintLimitMaterialZ**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:32753](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32753)

___

### ConstraintLimitMaterialZAxis

• **ConstraintLimitMaterialZAxis**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:32754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32754)

___

### CurrentCustomTimeStep

• **CurrentCustomTimeStep**: [`EngineCustomTimeStep`](ue_ue.EngineCustomTimeStep.md)

#### Defined in

[ue/ue.d.ts:32820](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32820)

___

### CustomTimeStepClassName

• **CustomTimeStepClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32821](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32821)

___

### CustomTimecodeProvider

• **CustomTimecodeProvider**: [`TimecodeProvider`](ue_ue.TimecodeProvider.md)

#### Defined in

[ue/ue.d.ts:32823](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32823)

___

### DebugEditorMaterial

• **DebugEditorMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32746)

___

### DebugEditorMaterialName

• **DebugEditorMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32747](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32747)

___

### DebugMeshMaterial

• **DebugMeshMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32710](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32710)

___

### DebugMeshMaterialName

• **DebugMeshMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32711](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32711)

___

### DefaultBSPVertexTexture

• **DefaultBSPVertexTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:32694](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32694)

___

### DefaultBSPVertexTextureName

• **DefaultBSPVertexTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32695](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32695)

___

### DefaultBloomKernelTexture

• **DefaultBloomKernelTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:32700](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32700)

___

### DefaultBloomKernelTextureName

• **DefaultBloomKernelTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32701](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32701)

___

### DefaultBlueprintBaseClassName

• **DefaultBlueprintBaseClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32685](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32685)

___

### DefaultBokehTexture

• **DefaultBokehTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:32698](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32698)

___

### DefaultBokehTextureName

• **DefaultBokehTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32699](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32699)

___

### DefaultCustomTimeStep

• **DefaultCustomTimeStep**: [`EngineCustomTimeStep`](ue_ue.EngineCustomTimeStep.md)

#### Defined in

[ue/ue.d.ts:32819](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32819)

___

### DefaultDiffuseTexture

• **DefaultDiffuseTexture**: [`Texture`](ue_ue.Texture.md)

#### Defined in

[ue/ue.d.ts:32692](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32692)

___

### DefaultDiffuseTextureName

• **DefaultDiffuseTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32693](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32693)

___

### DefaultPhysMaterial

• **DefaultPhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Defined in

[ue/ue.d.ts:32785](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32785)

___

### DefaultPhysMaterialName

• **DefaultPhysMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32786](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32786)

___

### DefaultSelectedMaterialColor

• **DefaultSelectedMaterialColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:32861](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32861)

___

### DefaultTexture

• **DefaultTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:32690](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32690)

___

### DefaultTextureName

• **DefaultTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32691](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32691)

___

### DefaultTimecodeFrameRate

• **DefaultTimecodeFrameRate**: [`FrameRate`](ue_ue.FrameRate.md)

#### Defined in

[ue/ue.d.ts:32826](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32826)

___

### DefaultTimecodeProvider

• **DefaultTimecodeProvider**: [`TimecodeProvider`](ue_ue.TimecodeProvider.md)

#### Defined in

[ue/ue.d.ts:32822](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32822)

___

### DefaultTimecodeProviderClassName

• **DefaultTimecodeProviderClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32824](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32824)

___

### DeferredCommands

• **DeferredCommands**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:32802](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32802)

___

### DisplayGamma

• **DisplayGamma**: `number`

#### Defined in

[ue/ue.d.ts:32859](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32859)

___

### EditorBrushMaterial

• **EditorBrushMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32783](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32783)

___

### EditorBrushMaterialName

• **EditorBrushMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32784](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32784)

___

### EmissiveMeshMaterial

• **EmissiveMeshMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32712](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32712)

___

### EmissiveMeshMaterialName

• **EmissiveMeshMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32713](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32713)

___

### FixedFrameRate

• **FixedFrameRate**: `number`

#### Defined in

[ue/ue.d.ts:32817](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32817)

___

### GameCycles

• **GameCycles**: `number`

#### Defined in

[ue/ue.d.ts:32804](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32804)

___

### GameScreenshotSaveDirectory

• **GameScreenshotSaveDirectory**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

#### Defined in

[ue/ue.d.ts:32844](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32844)

___

### GameSingleton

• **GameSingleton**: [`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:32687](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32687)

___

### GameSingletonClassName

• **GameSingletonClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32686](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32686)

___

### GameUserSettings

• **GameUserSettings**: [`GameUserSettings`](ue_ue.GameUserSettings.md)

#### Defined in

[ue/ue.d.ts:32682](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32682)

___

### GameUserSettingsClass

• **GameUserSettingsClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:32680](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32680)

___

### GameUserSettingsClassName

• **GameUserSettingsClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32679](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32679)

___

### GameViewport

• **GameViewport**: [`GameViewportClient`](ue_ue.GameViewportClient.md)

#### Defined in

[ue/ue.d.ts:32801](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32801)

___

### GameViewportClientClass

• **GameViewportClientClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:32665](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32665)

___

### GameViewportClientClassName

• **GameViewportClientClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32666](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32666)

___

### GeomMaterial

• **GeomMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32708](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32708)

___

### GeomMaterialName

• **GeomMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32709](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32709)

___

### HLODColorationColors

• **HLODColorationColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Defined in

[ue/ue.d.ts:32769](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32769)

___

### HairDebugMaterial

• **HairDebugMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32706](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32706)

___

### HairDebugMaterialName

• **HairDebugMaterialName**: `string`

#### Defined in

[ue/ue.d.ts:32707](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32707)

___

### HairDefaultMaterial

• **HairDefaultMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32704](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32704)

___

### HairDefaultMaterialName

• **HairDefaultMaterialName**: `string`

#### Defined in

[ue/ue.d.ts:32705](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32705)

___

### HighFrequencyNoiseTexture

• **HighFrequencyNoiseTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:32696](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32696)

___

### HighFrequencyNoiseTextureName

• **HighFrequencyNoiseTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32697](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32697)

___

### IdealLightMapDensity

• **IdealLightMapDensity**: `number`

#### Defined in

[ue/ue.d.ts:32775](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32775)

___

### InvalidLightmapSettingsMaterial

• **InvalidLightmapSettingsMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32756](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32756)

___

### InvalidLightmapSettingsMaterialName

• **InvalidLightmapSettingsMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32757](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32757)

___

### LODColorationColors

• **LODColorationColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Defined in

[ue/ue.d.ts:32768](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32768)

___

### LargeFont

• **LargeFont**: [`Font`](ue_ue.Font.md)

#### Defined in

[ue/ue.d.ts:32657](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32657)

___

### LargeFontName

• **LargeFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32658](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32658)

___

### LevelColorationLitMaterial

• **LevelColorationLitMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32714](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32714)

___

### LevelColorationLitMaterialName

• **LevelColorationLitMaterialName**: `string`

#### Defined in

[ue/ue.d.ts:32715](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32715)

___

### LevelColorationUnlitMaterial

• **LevelColorationUnlitMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32716)

___

### LevelColorationUnlitMaterialName

• **LevelColorationUnlitMaterialName**: `string`

#### Defined in

[ue/ue.d.ts:32717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32717)

___

### LevelScriptActorClass

• **LevelScriptActorClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:32683](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32683)

___

### LevelScriptActorClassName

• **LevelScriptActorClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32684](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32684)

___

### LightComplexityColors

• **LightComplexityColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Defined in

[ue/ue.d.ts:32766](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32766)

___

### LightMapDensitySelectedColor

• **LightMapDensitySelectedColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:32781](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32781)

___

### LightMapDensityTexture

• **LightMapDensityTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:32799](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32799)

___

### LightMapDensityTextureName

• **LightMapDensityTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32800](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32800)

___

### LightMapDensityVertexMappedColor

• **LightMapDensityVertexMappedColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:32780](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32780)

___

### LightingOnlyBrightness

• **LightingOnlyBrightness**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:32763](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32763)

___

### LightingTexelDensityMaterial

• **LightingTexelDensityMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32718)

___

### LightingTexelDensityName

• **LightingTexelDensityName**: `string`

#### Defined in

[ue/ue.d.ts:32719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32719)

___

### LocalPlayerClass

• **LocalPlayerClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:32667](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32667)

___

### LocalPlayerClassName

• **LocalPlayerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32668](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32668)

___

### MaxES2PixelShaderAdditiveComplexityCount

• **MaxES2PixelShaderAdditiveComplexityCount**: `number`

#### Defined in

[ue/ue.d.ts:32772](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32772)

___

### MaxES3PixelShaderAdditiveComplexityCount

• **MaxES3PixelShaderAdditiveComplexityCount**: `number`

#### Defined in

[ue/ue.d.ts:32773](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32773)

___

### MaxLightMapDensity

• **MaxLightMapDensity**: `number`

#### Defined in

[ue/ue.d.ts:32776](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32776)

___

### MaxOcclusionPixelsFraction

• **MaxOcclusionPixelsFraction**: `number`

#### Defined in

[ue/ue.d.ts:32853](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32853)

___

### MaxParticleResize

• **MaxParticleResize**: `number`

#### Defined in

[ue/ue.d.ts:32855](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32855)

___

### MaxParticleResizeWarn

• **MaxParticleResizeWarn**: `number`

#### Defined in

[ue/ue.d.ts:32856](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32856)

___

### MaxPixelShaderAdditiveComplexityCount

• **MaxPixelShaderAdditiveComplexityCount**: `number`

#### Defined in

[ue/ue.d.ts:32771](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32771)

___

### MaximumLoopIterationCount

• **MaximumLoopIterationCount**: `number`

#### Defined in

[ue/ue.d.ts:32810](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32810)

___

### MediumFont

• **MediumFont**: [`Font`](ue_ue.Font.md)

#### Defined in

[ue/ue.d.ts:32655](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32655)

___

### MediumFontName

• **MediumFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32656](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32656)

___

### MeshLODRange

• **MeshLODRange**: `number`

#### Defined in

[ue/ue.d.ts:32848](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32848)

___

### MinDesiredFrameRate

• **MinDesiredFrameRate**: `number`

#### Defined in

[ue/ue.d.ts:32860](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32860)

___

### MinLightMapDensity

• **MinLightMapDensity**: `number`

#### Defined in

[ue/ue.d.ts:32774](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32774)

___

### MiniFontTexture

• **MiniFontTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:32795](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32795)

___

### MiniFontTextureName

• **MiniFontTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32796](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32796)

___

### NavigationSystemClass

• **NavigationSystemClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:32672](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32672)

___

### NavigationSystemClassName

• **NavigationSystemClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32671](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32671)

___

### NavigationSystemConfigClass

• **NavigationSystemConfigClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:32674](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32674)

___

### NavigationSystemConfigClassName

• **NavigationSystemConfigClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32673](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32673)

___

### NearClipPlane

• **NearClipPlane**: `number`

#### Defined in

[ue/ue.d.ts:32806](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32806)

___

### NetClientTicksPerSecond

• **NetClientTicksPerSecond**: `number`

#### Defined in

[ue/ue.d.ts:32858](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32858)

___

### NetDriverDefinitions

• **NetDriverDefinitions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NetDriverDefinition`](ue_ue.NetDriverDefinition.md)\>

#### Defined in

[ue/ue.d.ts:32878](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32878)

___

### NetErrorLogInterval

• **NetErrorLogInterval**: `number`

#### Defined in

[ue/ue.d.ts:32881](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32881)

___

### NextWorldContextHandle

• **NextWorldContextHandle**: `number`

#### Defined in

[ue/ue.d.ts:32883](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32883)

___

### NumPawnsAllowedToBeSpawnedInAFrame

• **NumPawnsAllowedToBeSpawnedInAFrame**: `number`

#### Defined in

[ue/ue.d.ts:32828](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32828)

___

### ParticleEventManagerClassPath

• **ParticleEventManagerClassPath**: `string`

#### Defined in

[ue/ue.d.ts:32874](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32874)

___

### PendingDroppedNotes

• **PendingDroppedNotes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DropNoteInfo`](ue_ue.DropNoteInfo.md)\>

#### Defined in

[ue/ue.d.ts:32857](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32857)

___

### PhysicsCollisionHandlerClass

• **PhysicsCollisionHandlerClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:32677](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32677)

___

### PhysicsCollisionHandlerClassName

• **PhysicsCollisionHandlerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32678](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32678)

___

### PreIntegratedSkinBRDFTexture

• **PreIntegratedSkinBRDFTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:32791](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32791)

___

### PreIntegratedSkinBRDFTextureName

• **PreIntegratedSkinBRDFTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32792](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32792)

___

### PreviewShadowsIndicatorMaterial

• **PreviewShadowsIndicatorMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32758](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32758)

___

### PreviewShadowsIndicatorMaterialName

• **PreviewShadowsIndicatorMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32759](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32759)

___

### PrimitiveProbablyVisibleTime

• **PrimitiveProbablyVisibleTime**: `number`

#### Defined in

[ue/ue.d.ts:32852](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32852)

___

### QuadComplexityColors

• **QuadComplexityColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Defined in

[ue/ue.d.ts:32765](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32765)

___

### RemoveSurfaceMaterial

• **RemoveSurfaceMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32724)

___

### RemoveSurfaceMaterialName

• **RemoveSurfaceMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32725](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32725)

___

### RenderLightMapDensityColorScale

• **RenderLightMapDensityColorScale**: `number`

#### Defined in

[ue/ue.d.ts:32779](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32779)

___

### RenderLightMapDensityGrayscaleScale

• **RenderLightMapDensityGrayscaleScale**: `number`

#### Defined in

[ue/ue.d.ts:32778](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32778)

___

### RuntimeServerActors

• **RuntimeServerActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:32880](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32880)

___

### ScreenSaverInhibitorSemaphore

• **ScreenSaverInhibitorSemaphore**: `number`

#### Defined in

[ue/ue.d.ts:32872](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32872)

___

### SelectedMaterialColor

• **SelectedMaterialColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:32862](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32862)

___

### SelectedMaterialColorOverride

• **SelectedMaterialColorOverride**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:32865](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32865)

___

### SelectionHighlightIntensity

• **SelectionHighlightIntensity**: `number`

#### Defined in

[ue/ue.d.ts:32875](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32875)

___

### SelectionHighlightIntensityBillboards

• **SelectionHighlightIntensityBillboards**: `number`

#### Defined in

[ue/ue.d.ts:32877](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32877)

___

### SelectionOutlineColor

• **SelectionOutlineColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:32863](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32863)

___

### ServerActors

• **ServerActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:32879](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32879)

___

### ShadedLevelColorationLitMaterial

• **ShadedLevelColorationLitMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32720)

___

### ShadedLevelColorationLitMaterialName

• **ShadedLevelColorationLitMaterialName**: `string`

#### Defined in

[ue/ue.d.ts:32721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32721)

___

### ShadedLevelColorationUnlitMaterial

• **ShadedLevelColorationUnlitMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32722](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32722)

___

### ShadedLevelColorationUnlitMaterialName

• **ShadedLevelColorationUnlitMaterialName**: `string`

#### Defined in

[ue/ue.d.ts:32723](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32723)

___

### ShaderComplexityColors

• **ShaderComplexityColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Defined in

[ue/ue.d.ts:32764](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32764)

___

### SmallFont

• **SmallFont**: [`Font`](ue_ue.Font.md)

#### Defined in

[ue/ue.d.ts:32653](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32653)

___

### SmallFontName

• **SmallFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32654](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32654)

___

### SmoothedFrameRateRange

• **SmoothedFrameRateRange**: [`FloatRange`](ue_ue.FloatRange.md)

#### Defined in

[ue/ue.d.ts:32818](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32818)

___

### StatColorMappings

• **StatColorMappings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StatColorMapping`](ue_ue.StatColorMapping.md)\>

#### Defined in

[ue/ue.d.ts:32782](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32782)

___

### StationaryLightOverlapColors

• **StationaryLightOverlapColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Defined in

[ue/ue.d.ts:32767](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32767)

___

### StreamingAccuracyColors

• **StreamingAccuracyColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Defined in

[ue/ue.d.ts:32770](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32770)

___

### StreamingDistanceFactor

• **StreamingDistanceFactor**: `number`

#### Defined in

[ue/ue.d.ts:32843](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32843)

___

### SubduedSelectionOutlineColor

• **SubduedSelectionOutlineColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:32864](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32864)

___

### SubtitleFont

• **SubtitleFont**: [`Font`](ue_ue.Font.md)

#### Defined in

[ue/ue.d.ts:32659](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32659)

___

### SubtitleFontName

• **SubtitleFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32660](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32660)

___

### TickCycles

• **TickCycles**: `number`

#### Defined in

[ue/ue.d.ts:32803](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32803)

___

### TimecodeProviderClassName

• **TimecodeProviderClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32825](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32825)

___

### TinyFont

• **TinyFont**: [`Font`](ue_ue.Font.md)

#### Defined in

[ue/ue.d.ts:32651](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32651)

___

### TinyFontName

• **TinyFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32652](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32652)

___

### TransitionDescription

• **TransitionDescription**: `string`

#### Defined in

[ue/ue.d.ts:32846](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32846)

___

### TransitionGameMode

• **TransitionGameMode**: `string`

#### Defined in

[ue/ue.d.ts:32847](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32847)

___

### TransitionType

• **TransitionType**: [`ETransitionType`](../enums/ue_ue.ETransitionType.md)

#### Defined in

[ue/ue.d.ts:32845](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32845)

___

### VertexColorMaterial

• **VertexColorMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32726](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32726)

___

### VertexColorMaterialName

• **VertexColorMaterialName**: `string`

#### Defined in

[ue/ue.d.ts:32727](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32727)

___

### VertexColorViewModeMaterialName\_AlphaAsColor

• **VertexColorViewModeMaterialName\_AlphaAsColor**: `string`

#### Defined in

[ue/ue.d.ts:32731](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32731)

___

### VertexColorViewModeMaterialName\_BlueOnly

• **VertexColorViewModeMaterialName\_BlueOnly**: `string`

#### Defined in

[ue/ue.d.ts:32737](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32737)

___

### VertexColorViewModeMaterialName\_ColorOnly

• **VertexColorViewModeMaterialName\_ColorOnly**: `string`

#### Defined in

[ue/ue.d.ts:32729](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32729)

___

### VertexColorViewModeMaterialName\_GreenOnly

• **VertexColorViewModeMaterialName\_GreenOnly**: `string`

#### Defined in

[ue/ue.d.ts:32735](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32735)

___

### VertexColorViewModeMaterialName\_RedOnly

• **VertexColorViewModeMaterialName\_RedOnly**: `string`

#### Defined in

[ue/ue.d.ts:32733](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32733)

___

### VertexColorViewModeMaterial\_AlphaAsColor

• **VertexColorViewModeMaterial\_AlphaAsColor**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32730](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32730)

___

### VertexColorViewModeMaterial\_BlueOnly

• **VertexColorViewModeMaterial\_BlueOnly**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32736)

___

### VertexColorViewModeMaterial\_ColorOnly

• **VertexColorViewModeMaterial\_ColorOnly**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32728](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32728)

___

### VertexColorViewModeMaterial\_GreenOnly

• **VertexColorViewModeMaterial\_GreenOnly**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32734](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32734)

___

### VertexColorViewModeMaterial\_RedOnly

• **VertexColorViewModeMaterial\_RedOnly**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32732](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32732)

___

### WeightMapPlaceholderTexture

• **WeightMapPlaceholderTexture**: [`Texture`](ue_ue.Texture.md)

#### Defined in

[ue/ue.d.ts:32797](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32797)

___

### WeightMapPlaceholderTextureName

• **WeightMapPlaceholderTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:32798](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32798)

___

### WireframeMaterial

• **WireframeMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:32702](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32702)

___

### WireframeMaterialName

• **WireframeMaterialName**: `string`

#### Defined in

[ue/ue.d.ts:32703](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32703)

___

### WorldSettingsClass

• **WorldSettingsClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:32669](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32669)

___

### WorldSettingsClassName

• **WorldSettingsClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:32670](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32670)

___

### \_\_tid\_Engine\_\_

• **\_\_tid\_Engine\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:32888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32888)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAllowMatureLanguage

• **bAllowMatureLanguage**: `boolean`

#### Defined in

[ue/ue.d.ts:32849](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32849)

___

### bAllowMultiThreadedAnimationUpdate

• **bAllowMultiThreadedAnimationUpdate**: `boolean`

#### Defined in

[ue/ue.d.ts:32813](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32813)

___

### bCanBlueprintsTickByDefault

• **bCanBlueprintsTickByDefault**: `boolean`

#### Defined in

[ue/ue.d.ts:32811](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32811)

___

### bCheckForMultiplePawnsSpawnedInAFrame

• **bCheckForMultiplePawnsSpawnedInAFrame**: `boolean`

#### Defined in

[ue/ue.d.ts:32827](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32827)

___

### bDisableAILogging

• **bDisableAILogging**: `boolean`

#### Defined in

[ue/ue.d.ts:32870](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32870)

___

### bEnableEditorPSysRealtimeLOD

• **bEnableEditorPSysRealtimeLOD**: `boolean`

#### Defined in

[ue/ue.d.ts:32814](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32814)

___

### bEnableOnScreenDebugMessages

• **bEnableOnScreenDebugMessages**: `boolean`

#### Defined in

[ue/ue.d.ts:32867](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32867)

___

### bEnableOnScreenDebugMessagesDisplay

• **bEnableOnScreenDebugMessagesDisplay**: `boolean`

#### Defined in

[ue/ue.d.ts:32868](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32868)

___

### bEnableVisualLogRecordingOnStart

• **bEnableVisualLogRecordingOnStart**: `number`

#### Defined in

[ue/ue.d.ts:32871](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32871)

___

### bHardwareSurveyEnabled

• **bHardwareSurveyEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:32807](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32807)

___

### bIsOverridingSelectedColor

• **bIsOverridingSelectedColor**: `boolean`

#### Defined in

[ue/ue.d.ts:32866](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32866)

___

### bLockReadOnlyLevels

• **bLockReadOnlyLevels**: `boolean`

#### Defined in

[ue/ue.d.ts:32873](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32873)

___

### bOptimizeAnimBlueprintMemberVariableAccess

• **bOptimizeAnimBlueprintMemberVariableAccess**: `boolean`

#### Defined in

[ue/ue.d.ts:32812](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32812)

___

### bPauseOnLossOfFocus

• **bPauseOnLossOfFocus**: `boolean`

#### Defined in

[ue/ue.d.ts:32854](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32854)

___

### bRenderLightMapDensityGrayscale

• **bRenderLightMapDensityGrayscale**: `boolean`

#### Defined in

[ue/ue.d.ts:32777](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32777)

___

### bShouldGenerateLowQualityLightmaps

• **bShouldGenerateLowQualityLightmaps**: `boolean`

#### Defined in

[ue/ue.d.ts:32829](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32829)

___

### bSmoothFrameRate

• **bSmoothFrameRate**: `boolean`

#### Defined in

[ue/ue.d.ts:32815](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32815)

___

### bStartedLoadMapMovie

• **bStartedLoadMapMovie**: `boolean`

#### Defined in

[ue/ue.d.ts:32882](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32882)

___

### bSubtitlesEnabled

• **bSubtitlesEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:32808](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32808)

___

### bSubtitlesForcedOff

• **bSubtitlesForcedOff**: `boolean`

#### Defined in

[ue/ue.d.ts:32809](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32809)

___

### bSuppressMapWarnings

• **bSuppressMapWarnings**: `boolean`

#### Defined in

[ue/ue.d.ts:32869](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32869)

___

### bUseFixedFrameRate

• **bUseFixedFrameRate**: `boolean`

#### Defined in

[ue/ue.d.ts:32816](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32816)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Engine`](ue_ue.Engine-1.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Engine`](ue_ue.Engine-1.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:32885](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32885)

___

### Load

▸ `Static` **Load**(`InName`): [`Engine`](ue_ue.Engine-1.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Engine`](ue_ue.Engine-1.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:32886](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32886)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:32884](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32884)
