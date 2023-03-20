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

## Properties

### AIControllerClassName

• **AIControllerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### ActiveClassRedirects

• **ActiveClassRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClassRedirect`](ue_ue.ClassRedirect.md)\>

___

### ActiveGameNameRedirects

• **ActiveGameNameRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameNameRedirect`](ue_ue.GameNameRedirect.md)\>

___

### ActivePluginRedirects

• **ActivePluginRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PluginRedirect`](ue_ue.PluginRedirect.md)\>

___

### ActiveStructRedirects

• **ActiveStructRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StructRedirect`](ue_ue.StructRedirect.md)\>

___

### AdditionalFontNames

• **AdditionalFontNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### AdditionalFonts

• **AdditionalFonts**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Font`](ue_ue.Font.md)\>

___

### ArrowMaterial

• **ArrowMaterial**: [`Material`](ue_ue.Material.md)

___

### ArrowMaterialName

• **ArrowMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### ArrowMaterialYellow

• **ArrowMaterialYellow**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

___

### AssetManager

• **AssetManager**: [`AssetManager`](ue_ue.AssetManager.md)

___

### AssetManagerClassName

• **AssetManagerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### AvoidanceManagerClass

• **AvoidanceManagerClass**: [`Class`](ue_ue.Class.md)

___

### AvoidanceManagerClassName

• **AvoidanceManagerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### BSPSelectionHighlightIntensity

• **BSPSelectionHighlightIntensity**: `number`

___

### BlueNoiseTexture

• **BlueNoiseTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### BlueNoiseTextureName

• **BlueNoiseTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### BoneWeightMaterial

• **BoneWeightMaterial**: [`Material`](ue_ue.Material.md)

___

### BoneWeightMaterialName

• **BoneWeightMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### C\_AddWire

• **C\_AddWire**: [`Color`](ue_ue_s.Color.md)

___

### C\_BSPCollision

• **C\_BSPCollision**: [`Color`](ue_ue_s.Color.md)

___

### C\_BrushShape

• **C\_BrushShape**: [`Color`](ue_ue_s.Color.md)

___

### C\_BrushWire

• **C\_BrushWire**: [`Color`](ue_ue_s.Color.md)

___

### C\_NonSolidWire

• **C\_NonSolidWire**: [`Color`](ue_ue_s.Color.md)

___

### C\_OrthoBackground

• **C\_OrthoBackground**: [`Color`](ue_ue_s.Color.md)

___

### C\_ScaleBoxHi

• **C\_ScaleBoxHi**: [`Color`](ue_ue_s.Color.md)

___

### C\_SemiSolidWire

• **C\_SemiSolidWire**: [`Color`](ue_ue_s.Color.md)

___

### C\_SubtractWire

• **C\_SubtractWire**: [`Color`](ue_ue_s.Color.md)

___

### C\_Volume

• **C\_Volume**: [`Color`](ue_ue_s.Color.md)

___

### C\_VolumeCollision

• **C\_VolumeCollision**: [`Color`](ue_ue_s.Color.md)

___

### C\_WireBackground

• **C\_WireBackground**: [`Color`](ue_ue_s.Color.md)

___

### C\_WorldBox

• **C\_WorldBox**: [`Color`](ue_ue_s.Color.md)

___

### CameraRotationThreshold

• **CameraRotationThreshold**: `number`

___

### CameraTranslationThreshold

• **CameraTranslationThreshold**: `number`

___

### ClientCycles

• **ClientCycles**: `number`

___

### ClothPaintMaterial

• **ClothPaintMaterial**: [`Material`](ue_ue.Material.md)

___

### ClothPaintMaterialInstance

• **ClothPaintMaterialInstance**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

___

### ClothPaintMaterialName

• **ClothPaintMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### ClothPaintMaterialWireframe

• **ClothPaintMaterialWireframe**: [`Material`](ue_ue.Material.md)

___

### ClothPaintMaterialWireframeInstance

• **ClothPaintMaterialWireframeInstance**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

___

### ClothPaintMaterialWireframeName

• **ClothPaintMaterialWireframeName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### ConsoleClass

• **ConsoleClass**: [`Class`](ue_ue.Class.md)

___

### ConsoleClassName

• **ConsoleClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### ConstraintLimitMaterial

• **ConstraintLimitMaterial**: [`Material`](ue_ue.Material.md)

___

### ConstraintLimitMaterialPrismatic

• **ConstraintLimitMaterialPrismatic**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

___

### ConstraintLimitMaterialX

• **ConstraintLimitMaterialX**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

___

### ConstraintLimitMaterialXAxis

• **ConstraintLimitMaterialXAxis**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

___

### ConstraintLimitMaterialY

• **ConstraintLimitMaterialY**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

___

### ConstraintLimitMaterialYAxis

• **ConstraintLimitMaterialYAxis**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

___

### ConstraintLimitMaterialZ

• **ConstraintLimitMaterialZ**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

___

### ConstraintLimitMaterialZAxis

• **ConstraintLimitMaterialZAxis**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

___

### CurrentCustomTimeStep

• **CurrentCustomTimeStep**: [`EngineCustomTimeStep`](ue_ue.EngineCustomTimeStep.md)

___

### CustomTimeStepClassName

• **CustomTimeStepClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### CustomTimecodeProvider

• **CustomTimecodeProvider**: [`TimecodeProvider`](ue_ue.TimecodeProvider.md)

___

### DebugEditorMaterial

• **DebugEditorMaterial**: [`Material`](ue_ue.Material.md)

___

### DebugEditorMaterialName

• **DebugEditorMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### DebugMeshMaterial

• **DebugMeshMaterial**: [`Material`](ue_ue.Material.md)

___

### DebugMeshMaterialName

• **DebugMeshMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### DefaultBSPVertexTexture

• **DefaultBSPVertexTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### DefaultBSPVertexTextureName

• **DefaultBSPVertexTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### DefaultBloomKernelTexture

• **DefaultBloomKernelTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### DefaultBloomKernelTextureName

• **DefaultBloomKernelTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### DefaultBlueprintBaseClassName

• **DefaultBlueprintBaseClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### DefaultBokehTexture

• **DefaultBokehTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### DefaultBokehTextureName

• **DefaultBokehTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### DefaultCustomTimeStep

• **DefaultCustomTimeStep**: [`EngineCustomTimeStep`](ue_ue.EngineCustomTimeStep.md)

___

### DefaultDiffuseTexture

• **DefaultDiffuseTexture**: [`Texture`](ue_ue.Texture.md)

___

### DefaultDiffuseTextureName

• **DefaultDiffuseTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### DefaultPhysMaterial

• **DefaultPhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

___

### DefaultPhysMaterialName

• **DefaultPhysMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### DefaultSelectedMaterialColor

• **DefaultSelectedMaterialColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### DefaultTexture

• **DefaultTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### DefaultTextureName

• **DefaultTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### DefaultTimecodeFrameRate

• **DefaultTimecodeFrameRate**: [`FrameRate`](ue_ue.FrameRate.md)

___

### DefaultTimecodeProvider

• **DefaultTimecodeProvider**: [`TimecodeProvider`](ue_ue.TimecodeProvider.md)

___

### DefaultTimecodeProviderClassName

• **DefaultTimecodeProviderClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### DeferredCommands

• **DeferredCommands**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### DisplayGamma

• **DisplayGamma**: `number`

___

### EditorBrushMaterial

• **EditorBrushMaterial**: [`Material`](ue_ue.Material.md)

___

### EditorBrushMaterialName

• **EditorBrushMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### EmissiveMeshMaterial

• **EmissiveMeshMaterial**: [`Material`](ue_ue.Material.md)

___

### EmissiveMeshMaterialName

• **EmissiveMeshMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### FixedFrameRate

• **FixedFrameRate**: `number`

___

### GameCycles

• **GameCycles**: `number`

___

### GameScreenshotSaveDirectory

• **GameScreenshotSaveDirectory**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

___

### GameSingleton

• **GameSingleton**: [`Object`](ue_ue.Object.md)

___

### GameSingletonClassName

• **GameSingletonClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### GameUserSettings

• **GameUserSettings**: [`GameUserSettings`](ue_ue.GameUserSettings.md)

___

### GameUserSettingsClass

• **GameUserSettingsClass**: [`Class`](ue_ue.Class.md)

___

### GameUserSettingsClassName

• **GameUserSettingsClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### GameViewport

• **GameViewport**: [`GameViewportClient`](ue_ue.GameViewportClient.md)

___

### GameViewportClientClass

• **GameViewportClientClass**: [`Class`](ue_ue.Class.md)

___

### GameViewportClientClassName

• **GameViewportClientClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### GeomMaterial

• **GeomMaterial**: [`Material`](ue_ue.Material.md)

___

### GeomMaterialName

• **GeomMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### HLODColorationColors

• **HLODColorationColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

___

### HairDebugMaterial

• **HairDebugMaterial**: [`Material`](ue_ue.Material.md)

___

### HairDebugMaterialName

• **HairDebugMaterialName**: `string`

___

### HairDefaultMaterial

• **HairDefaultMaterial**: [`Material`](ue_ue.Material.md)

___

### HairDefaultMaterialName

• **HairDefaultMaterialName**: `string`

___

### HighFrequencyNoiseTexture

• **HighFrequencyNoiseTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### HighFrequencyNoiseTextureName

• **HighFrequencyNoiseTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### IdealLightMapDensity

• **IdealLightMapDensity**: `number`

___

### InvalidLightmapSettingsMaterial

• **InvalidLightmapSettingsMaterial**: [`Material`](ue_ue.Material.md)

___

### InvalidLightmapSettingsMaterialName

• **InvalidLightmapSettingsMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### LODColorationColors

• **LODColorationColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

___

### LargeFont

• **LargeFont**: [`Font`](ue_ue.Font.md)

___

### LargeFontName

• **LargeFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### LevelColorationLitMaterial

• **LevelColorationLitMaterial**: [`Material`](ue_ue.Material.md)

___

### LevelColorationLitMaterialName

• **LevelColorationLitMaterialName**: `string`

___

### LevelColorationUnlitMaterial

• **LevelColorationUnlitMaterial**: [`Material`](ue_ue.Material.md)

___

### LevelColorationUnlitMaterialName

• **LevelColorationUnlitMaterialName**: `string`

___

### LevelScriptActorClass

• **LevelScriptActorClass**: [`Class`](ue_ue.Class.md)

___

### LevelScriptActorClassName

• **LevelScriptActorClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### LightComplexityColors

• **LightComplexityColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

___

### LightMapDensitySelectedColor

• **LightMapDensitySelectedColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### LightMapDensityTexture

• **LightMapDensityTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### LightMapDensityTextureName

• **LightMapDensityTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### LightMapDensityVertexMappedColor

• **LightMapDensityVertexMappedColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### LightingOnlyBrightness

• **LightingOnlyBrightness**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### LightingTexelDensityMaterial

• **LightingTexelDensityMaterial**: [`Material`](ue_ue.Material.md)

___

### LightingTexelDensityName

• **LightingTexelDensityName**: `string`

___

### LocalPlayerClass

• **LocalPlayerClass**: [`Class`](ue_ue.Class.md)

___

### LocalPlayerClassName

• **LocalPlayerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### MaxES2PixelShaderAdditiveComplexityCount

• **MaxES2PixelShaderAdditiveComplexityCount**: `number`

___

### MaxES3PixelShaderAdditiveComplexityCount

• **MaxES3PixelShaderAdditiveComplexityCount**: `number`

___

### MaxLightMapDensity

• **MaxLightMapDensity**: `number`

___

### MaxOcclusionPixelsFraction

• **MaxOcclusionPixelsFraction**: `number`

___

### MaxParticleResize

• **MaxParticleResize**: `number`

___

### MaxParticleResizeWarn

• **MaxParticleResizeWarn**: `number`

___

### MaxPixelShaderAdditiveComplexityCount

• **MaxPixelShaderAdditiveComplexityCount**: `number`

___

### MaximumLoopIterationCount

• **MaximumLoopIterationCount**: `number`

___

### MediumFont

• **MediumFont**: [`Font`](ue_ue.Font.md)

___

### MediumFontName

• **MediumFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### MeshLODRange

• **MeshLODRange**: `number`

___

### MinDesiredFrameRate

• **MinDesiredFrameRate**: `number`

___

### MinLightMapDensity

• **MinLightMapDensity**: `number`

___

### MiniFontTexture

• **MiniFontTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### MiniFontTextureName

• **MiniFontTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### NavigationSystemClass

• **NavigationSystemClass**: [`Class`](ue_ue.Class.md)

___

### NavigationSystemClassName

• **NavigationSystemClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### NavigationSystemConfigClass

• **NavigationSystemConfigClass**: [`Class`](ue_ue.Class.md)

___

### NavigationSystemConfigClassName

• **NavigationSystemConfigClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### NearClipPlane

• **NearClipPlane**: `number`

___

### NetClientTicksPerSecond

• **NetClientTicksPerSecond**: `number`

___

### NetDriverDefinitions

• **NetDriverDefinitions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NetDriverDefinition`](ue_ue.NetDriverDefinition.md)\>

___

### NetErrorLogInterval

• **NetErrorLogInterval**: `number`

___

### NextWorldContextHandle

• **NextWorldContextHandle**: `number`

___

### NumPawnsAllowedToBeSpawnedInAFrame

• **NumPawnsAllowedToBeSpawnedInAFrame**: `number`

___

### ParticleEventManagerClassPath

• **ParticleEventManagerClassPath**: `string`

___

### PendingDroppedNotes

• **PendingDroppedNotes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DropNoteInfo`](ue_ue.DropNoteInfo.md)\>

___

### PhysicsCollisionHandlerClass

• **PhysicsCollisionHandlerClass**: [`Class`](ue_ue.Class.md)

___

### PhysicsCollisionHandlerClassName

• **PhysicsCollisionHandlerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### PreIntegratedSkinBRDFTexture

• **PreIntegratedSkinBRDFTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### PreIntegratedSkinBRDFTextureName

• **PreIntegratedSkinBRDFTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### PreviewShadowsIndicatorMaterial

• **PreviewShadowsIndicatorMaterial**: [`Material`](ue_ue.Material.md)

___

### PreviewShadowsIndicatorMaterialName

• **PreviewShadowsIndicatorMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### PrimitiveProbablyVisibleTime

• **PrimitiveProbablyVisibleTime**: `number`

___

### QuadComplexityColors

• **QuadComplexityColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

___

### RemoveSurfaceMaterial

• **RemoveSurfaceMaterial**: [`Material`](ue_ue.Material.md)

___

### RemoveSurfaceMaterialName

• **RemoveSurfaceMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### RenderLightMapDensityColorScale

• **RenderLightMapDensityColorScale**: `number`

___

### RenderLightMapDensityGrayscaleScale

• **RenderLightMapDensityGrayscaleScale**: `number`

___

### RuntimeServerActors

• **RuntimeServerActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ScreenSaverInhibitorSemaphore

• **ScreenSaverInhibitorSemaphore**: `number`

___

### SelectedMaterialColor

• **SelectedMaterialColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### SelectedMaterialColorOverride

• **SelectedMaterialColorOverride**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### SelectionHighlightIntensity

• **SelectionHighlightIntensity**: `number`

___

### SelectionHighlightIntensityBillboards

• **SelectionHighlightIntensityBillboards**: `number`

___

### SelectionOutlineColor

• **SelectionOutlineColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### ServerActors

• **ServerActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ShadedLevelColorationLitMaterial

• **ShadedLevelColorationLitMaterial**: [`Material`](ue_ue.Material.md)

___

### ShadedLevelColorationLitMaterialName

• **ShadedLevelColorationLitMaterialName**: `string`

___

### ShadedLevelColorationUnlitMaterial

• **ShadedLevelColorationUnlitMaterial**: [`Material`](ue_ue.Material.md)

___

### ShadedLevelColorationUnlitMaterialName

• **ShadedLevelColorationUnlitMaterialName**: `string`

___

### ShaderComplexityColors

• **ShaderComplexityColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

___

### SmallFont

• **SmallFont**: [`Font`](ue_ue.Font.md)

___

### SmallFontName

• **SmallFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### SmoothedFrameRateRange

• **SmoothedFrameRateRange**: [`FloatRange`](ue_ue.FloatRange.md)

___

### StatColorMappings

• **StatColorMappings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StatColorMapping`](ue_ue.StatColorMapping.md)\>

___

### StationaryLightOverlapColors

• **StationaryLightOverlapColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

___

### StreamingAccuracyColors

• **StreamingAccuracyColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

___

### StreamingDistanceFactor

• **StreamingDistanceFactor**: `number`

___

### SubduedSelectionOutlineColor

• **SubduedSelectionOutlineColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### SubtitleFont

• **SubtitleFont**: [`Font`](ue_ue.Font.md)

___

### SubtitleFontName

• **SubtitleFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### TickCycles

• **TickCycles**: `number`

___

### TimecodeProviderClassName

• **TimecodeProviderClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### TinyFont

• **TinyFont**: [`Font`](ue_ue.Font.md)

___

### TinyFontName

• **TinyFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### TransitionDescription

• **TransitionDescription**: `string`

___

### TransitionGameMode

• **TransitionGameMode**: `string`

___

### TransitionType

• **TransitionType**: [`ETransitionType`](../enums/ue_ue.ETransitionType.md)

___

### VertexColorMaterial

• **VertexColorMaterial**: [`Material`](ue_ue.Material.md)

___

### VertexColorMaterialName

• **VertexColorMaterialName**: `string`

___

### VertexColorViewModeMaterialName\_AlphaAsColor

• **VertexColorViewModeMaterialName\_AlphaAsColor**: `string`

___

### VertexColorViewModeMaterialName\_BlueOnly

• **VertexColorViewModeMaterialName\_BlueOnly**: `string`

___

### VertexColorViewModeMaterialName\_ColorOnly

• **VertexColorViewModeMaterialName\_ColorOnly**: `string`

___

### VertexColorViewModeMaterialName\_GreenOnly

• **VertexColorViewModeMaterialName\_GreenOnly**: `string`

___

### VertexColorViewModeMaterialName\_RedOnly

• **VertexColorViewModeMaterialName\_RedOnly**: `string`

___

### VertexColorViewModeMaterial\_AlphaAsColor

• **VertexColorViewModeMaterial\_AlphaAsColor**: [`Material`](ue_ue.Material.md)

___

### VertexColorViewModeMaterial\_BlueOnly

• **VertexColorViewModeMaterial\_BlueOnly**: [`Material`](ue_ue.Material.md)

___

### VertexColorViewModeMaterial\_ColorOnly

• **VertexColorViewModeMaterial\_ColorOnly**: [`Material`](ue_ue.Material.md)

___

### VertexColorViewModeMaterial\_GreenOnly

• **VertexColorViewModeMaterial\_GreenOnly**: [`Material`](ue_ue.Material.md)

___

### VertexColorViewModeMaterial\_RedOnly

• **VertexColorViewModeMaterial\_RedOnly**: [`Material`](ue_ue.Material.md)

___

### WeightMapPlaceholderTexture

• **WeightMapPlaceholderTexture**: [`Texture`](ue_ue.Texture.md)

___

### WeightMapPlaceholderTextureName

• **WeightMapPlaceholderTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### WireframeMaterial

• **WireframeMaterial**: [`Material`](ue_ue.Material.md)

___

### WireframeMaterialName

• **WireframeMaterialName**: `string`

___

### WorldSettingsClass

• **WorldSettingsClass**: [`Class`](ue_ue.Class.md)

___

### WorldSettingsClassName

• **WorldSettingsClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### \_\_tid\_Engine\_\_

• **\_\_tid\_Engine\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAllowMatureLanguage

• **bAllowMatureLanguage**: `boolean`

___

### bAllowMultiThreadedAnimationUpdate

• **bAllowMultiThreadedAnimationUpdate**: `boolean`

___

### bCanBlueprintsTickByDefault

• **bCanBlueprintsTickByDefault**: `boolean`

___

### bCheckForMultiplePawnsSpawnedInAFrame

• **bCheckForMultiplePawnsSpawnedInAFrame**: `boolean`

___

### bDisableAILogging

• **bDisableAILogging**: `boolean`

___

### bEnableEditorPSysRealtimeLOD

• **bEnableEditorPSysRealtimeLOD**: `boolean`

___

### bEnableOnScreenDebugMessages

• **bEnableOnScreenDebugMessages**: `boolean`

___

### bEnableOnScreenDebugMessagesDisplay

• **bEnableOnScreenDebugMessagesDisplay**: `boolean`

___

### bEnableVisualLogRecordingOnStart

• **bEnableVisualLogRecordingOnStart**: `number`

___

### bHardwareSurveyEnabled

• **bHardwareSurveyEnabled**: `boolean`

___

### bIsOverridingSelectedColor

• **bIsOverridingSelectedColor**: `boolean`

___

### bLockReadOnlyLevels

• **bLockReadOnlyLevels**: `boolean`

___

### bOptimizeAnimBlueprintMemberVariableAccess

• **bOptimizeAnimBlueprintMemberVariableAccess**: `boolean`

___

### bPauseOnLossOfFocus

• **bPauseOnLossOfFocus**: `boolean`

___

### bRenderLightMapDensityGrayscale

• **bRenderLightMapDensityGrayscale**: `boolean`

___

### bShouldGenerateLowQualityLightmaps

• **bShouldGenerateLowQualityLightmaps**: `boolean`

___

### bSmoothFrameRate

• **bSmoothFrameRate**: `boolean`

___

### bStartedLoadMapMovie

• **bStartedLoadMapMovie**: `boolean`

___

### bSubtitlesEnabled

• **bSubtitlesEnabled**: `boolean`

___

### bSubtitlesForcedOff

• **bSubtitlesForcedOff**: `boolean`

___

### bSuppressMapWarnings

• **bSuppressMapWarnings**: `boolean`

___

### bUseFixedFrameRate

• **bUseFixedFrameRate**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
