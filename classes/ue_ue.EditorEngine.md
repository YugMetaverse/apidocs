[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorEngine

# Class: EditorEngine

[ue/ue](../modules/ue_ue.md).EditorEngine

## Hierarchy

- [`Engine`](ue_ue.Engine-1.md)

  ↳ **`EditorEngine`**

  ↳↳ [`UnrealEdEngine`](ue_ue.UnrealEdEngine.md)

## Table of contents

### Constructors

- [constructor](ue_ue.EditorEngine.md#constructor)

### Properties

- [AIControllerClassName](ue_ue.EditorEngine.md#aicontrollerclassname)
- [ActiveClassRedirects](ue_ue.EditorEngine.md#activeclassredirects)
- [ActiveGameNameRedirects](ue_ue.EditorEngine.md#activegamenameredirects)
- [ActivePluginRedirects](ue_ue.EditorEngine.md#activepluginredirects)
- [ActiveStructRedirects](ue_ue.EditorEngine.md#activestructredirects)
- [ActorFactories](ue_ue.EditorEngine.md#actorfactories)
- [ActorGroupingUtils](ue_ue.EditorEngine.md#actorgroupingutils)
- [ActorGroupingUtilsClassName](ue_ue.EditorEngine.md#actorgroupingutilsclassname)
- [ActorsThatWereSelected](ue_ue.EditorEngine.md#actorsthatwereselected)
- [AdditionalFontNames](ue_ue.EditorEngine.md#additionalfontnames)
- [AdditionalFonts](ue_ue.EditorEngine.md#additionalfonts)
- [ArrowMaterial](ue_ue.EditorEngine.md#arrowmaterial)
- [ArrowMaterialName](ue_ue.EditorEngine.md#arrowmaterialname)
- [ArrowMaterialYellow](ue_ue.EditorEngine.md#arrowmaterialyellow)
- [AssetManager](ue_ue.EditorEngine.md#assetmanager)
- [AssetManagerClassName](ue_ue.EditorEngine.md#assetmanagerclassname)
- [AvoidanceManagerClass](ue_ue.EditorEngine.md#avoidancemanagerclass)
- [AvoidanceManagerClassName](ue_ue.EditorEngine.md#avoidancemanagerclassname)
- [BSPSelectionHighlightIntensity](ue_ue.EditorEngine.md#bspselectionhighlightintensity)
- [Bad](ue_ue.EditorEngine.md#bad)
- [BlueNoiseTexture](ue_ue.EditorEngine.md#bluenoisetexture)
- [BlueNoiseTextureName](ue_ue.EditorEngine.md#bluenoisetexturename)
- [BoneWeightMaterial](ue_ue.EditorEngine.md#boneweightmaterial)
- [BoneWeightMaterialName](ue_ue.EditorEngine.md#boneweightmaterialname)
- [BrushBuilders](ue_ue.EditorEngine.md#brushbuilders)
- [BuildPlayDevice](ue_ue.EditorEngine.md#buildplaydevice)
- [C\_AddWire](ue_ue.EditorEngine.md#c_addwire)
- [C\_BSPCollision](ue_ue.EditorEngine.md#c_bspcollision)
- [C\_BrushShape](ue_ue.EditorEngine.md#c_brushshape)
- [C\_BrushWire](ue_ue.EditorEngine.md#c_brushwire)
- [C\_NonSolidWire](ue_ue.EditorEngine.md#c_nonsolidwire)
- [C\_OrthoBackground](ue_ue.EditorEngine.md#c_orthobackground)
- [C\_ScaleBoxHi](ue_ue.EditorEngine.md#c_scaleboxhi)
- [C\_SemiSolidWire](ue_ue.EditorEngine.md#c_semisolidwire)
- [C\_SubtractWire](ue_ue.EditorEngine.md#c_subtractwire)
- [C\_Volume](ue_ue.EditorEngine.md#c_volume)
- [C\_VolumeCollision](ue_ue.EditorEngine.md#c_volumecollision)
- [C\_WireBackground](ue_ue.EditorEngine.md#c_wirebackground)
- [C\_WorldBox](ue_ue.EditorEngine.md#c_worldbox)
- [CameraRotationThreshold](ue_ue.EditorEngine.md#camerarotationthreshold)
- [CameraTranslationThreshold](ue_ue.EditorEngine.md#cameratranslationthreshold)
- [ClickFlags](ue_ue.EditorEngine.md#clickflags)
- [ClickLocation](ue_ue.EditorEngine.md#clicklocation)
- [ClickPlane](ue_ue.EditorEngine.md#clickplane)
- [ClientCycles](ue_ue.EditorEngine.md#clientcycles)
- [ClothPaintMaterial](ue_ue.EditorEngine.md#clothpaintmaterial)
- [ClothPaintMaterialInstance](ue_ue.EditorEngine.md#clothpaintmaterialinstance)
- [ClothPaintMaterialName](ue_ue.EditorEngine.md#clothpaintmaterialname)
- [ClothPaintMaterialWireframe](ue_ue.EditorEngine.md#clothpaintmaterialwireframe)
- [ClothPaintMaterialWireframeInstance](ue_ue.EditorEngine.md#clothpaintmaterialwireframeinstance)
- [ClothPaintMaterialWireframeName](ue_ue.EditorEngine.md#clothpaintmaterialwireframename)
- [ConsoleClass](ue_ue.EditorEngine.md#consoleclass)
- [ConsoleClassName](ue_ue.EditorEngine.md#consoleclassname)
- [ConstraintLimitMaterial](ue_ue.EditorEngine.md#constraintlimitmaterial)
- [ConstraintLimitMaterialPrismatic](ue_ue.EditorEngine.md#constraintlimitmaterialprismatic)
- [ConstraintLimitMaterialX](ue_ue.EditorEngine.md#constraintlimitmaterialx)
- [ConstraintLimitMaterialXAxis](ue_ue.EditorEngine.md#constraintlimitmaterialxaxis)
- [ConstraintLimitMaterialY](ue_ue.EditorEngine.md#constraintlimitmaterialy)
- [ConstraintLimitMaterialYAxis](ue_ue.EditorEngine.md#constraintlimitmaterialyaxis)
- [ConstraintLimitMaterialZ](ue_ue.EditorEngine.md#constraintlimitmaterialz)
- [ConstraintLimitMaterialZAxis](ue_ue.EditorEngine.md#constraintlimitmaterialzaxis)
- [ConversionTempModel](ue_ue.EditorEngine.md#conversiontempmodel)
- [CurrentCustomTimeStep](ue_ue.EditorEngine.md#currentcustomtimestep)
- [CurrentPlayWorldDestination](ue_ue.EditorEngine.md#currentplayworlddestination)
- [CustomCameraAlignEmitterDistance](ue_ue.EditorEngine.md#customcameraalignemitterdistance)
- [CustomTimeStepClassName](ue_ue.EditorEngine.md#customtimestepclassname)
- [CustomTimecodeProvider](ue_ue.EditorEngine.md#customtimecodeprovider)
- [DebugEditorMaterial](ue_ue.EditorEngine.md#debugeditormaterial)
- [DebugEditorMaterialName](ue_ue.EditorEngine.md#debugeditormaterialname)
- [DebugMeshMaterial](ue_ue.EditorEngine.md#debugmeshmaterial)
- [DebugMeshMaterialName](ue_ue.EditorEngine.md#debugmeshmaterialname)
- [DefaultBSPVertexTexture](ue_ue.EditorEngine.md#defaultbspvertextexture)
- [DefaultBSPVertexTextureName](ue_ue.EditorEngine.md#defaultbspvertextexturename)
- [DefaultBloomKernelTexture](ue_ue.EditorEngine.md#defaultbloomkerneltexture)
- [DefaultBloomKernelTextureName](ue_ue.EditorEngine.md#defaultbloomkerneltexturename)
- [DefaultBlueprintBaseClassName](ue_ue.EditorEngine.md#defaultblueprintbaseclassname)
- [DefaultBokehTexture](ue_ue.EditorEngine.md#defaultbokehtexture)
- [DefaultBokehTextureName](ue_ue.EditorEngine.md#defaultbokehtexturename)
- [DefaultCustomTimeStep](ue_ue.EditorEngine.md#defaultcustomtimestep)
- [DefaultDiffuseTexture](ue_ue.EditorEngine.md#defaultdiffusetexture)
- [DefaultDiffuseTextureName](ue_ue.EditorEngine.md#defaultdiffusetexturename)
- [DefaultPhysMaterial](ue_ue.EditorEngine.md#defaultphysmaterial)
- [DefaultPhysMaterialName](ue_ue.EditorEngine.md#defaultphysmaterialname)
- [DefaultSelectedMaterialColor](ue_ue.EditorEngine.md#defaultselectedmaterialcolor)
- [DefaultTexture](ue_ue.EditorEngine.md#defaulttexture)
- [DefaultTextureName](ue_ue.EditorEngine.md#defaulttexturename)
- [DefaultTimecodeFrameRate](ue_ue.EditorEngine.md#defaulttimecodeframerate)
- [DefaultTimecodeProvider](ue_ue.EditorEngine.md#defaulttimecodeprovider)
- [DefaultTimecodeProviderClassName](ue_ue.EditorEngine.md#defaulttimecodeproviderclassname)
- [DeferredCommands](ue_ue.EditorEngine.md#deferredcommands)
- [DetailMode](ue_ue.EditorEngine.md#detailmode)
- [DisplayGamma](ue_ue.EditorEngine.md#displaygamma)
- [EditorBrushMaterial](ue_ue.EditorEngine.md#editorbrushmaterial)
- [EditorBrushMaterialName](ue_ue.EditorEngine.md#editorbrushmaterialname)
- [EditorCube](ue_ue.EditorEngine.md#editorcube)
- [EditorCylinder](ue_ue.EditorEngine.md#editorcylinder)
- [EditorFont](ue_ue.EditorEngine.md#editorfont)
- [EditorPlane](ue_ue.EditorEngine.md#editorplane)
- [EditorSphere](ue_ue.EditorEngine.md#editorsphere)
- [EditorWorld](ue_ue.EditorEngine.md#editorworld)
- [EditorWorldExtensionsManager](ue_ue.EditorEngine.md#editorworldextensionsmanager)
- [EmissiveMeshMaterial](ue_ue.EditorEngine.md#emissivemeshmaterial)
- [EmissiveMeshMaterialName](ue_ue.EditorEngine.md#emissivemeshmaterialname)
- [FixedFrameRate](ue_ue.EditorEngine.md#fixedframerate)
- [GameCommandLine](ue_ue.EditorEngine.md#gamecommandline)
- [GameCycles](ue_ue.EditorEngine.md#gamecycles)
- [GameScreenshotSaveDirectory](ue_ue.EditorEngine.md#gamescreenshotsavedirectory)
- [GameSingleton](ue_ue.EditorEngine.md#gamesingleton)
- [GameSingletonClassName](ue_ue.EditorEngine.md#gamesingletonclassname)
- [GameUserSettings](ue_ue.EditorEngine.md#gameusersettings)
- [GameUserSettingsClass](ue_ue.EditorEngine.md#gameusersettingsclass)
- [GameUserSettingsClassName](ue_ue.EditorEngine.md#gameusersettingsclassname)
- [GameViewport](ue_ue.EditorEngine.md#gameviewport)
- [GameViewportClientClass](ue_ue.EditorEngine.md#gameviewportclientclass)
- [GameViewportClientClassName](ue_ue.EditorEngine.md#gameviewportclientclassname)
- [GeomMaterial](ue_ue.EditorEngine.md#geommaterial)
- [GeomMaterialName](ue_ue.EditorEngine.md#geommaterialname)
- [GodMode](ue_ue.EditorEngine.md#godmode)
- [HLODColorationColors](ue_ue.EditorEngine.md#hlodcolorationcolors)
- [HairDebugMaterial](ue_ue.EditorEngine.md#hairdebugmaterial)
- [HairDebugMaterialName](ue_ue.EditorEngine.md#hairdebugmaterialname)
- [HairDefaultMaterial](ue_ue.EditorEngine.md#hairdefaultmaterial)
- [HairDefaultMaterialName](ue_ue.EditorEngine.md#hairdefaultmaterialname)
- [HeightMapExportClassName](ue_ue.EditorEngine.md#heightmapexportclassname)
- [HighFrequencyNoiseTexture](ue_ue.EditorEngine.md#highfrequencynoisetexture)
- [HighFrequencyNoiseTextureName](ue_ue.EditorEngine.md#highfrequencynoisetexturename)
- [IdealLightMapDensity](ue_ue.EditorEngine.md#ideallightmapdensity)
- [InEditorGameURLOptions](ue_ue.EditorEngine.md#ineditorgameurloptions)
- [InvalidLightmapSettingsMaterial](ue_ue.EditorEngine.md#invalidlightmapsettingsmaterial)
- [InvalidLightmapSettingsMaterialName](ue_ue.EditorEngine.md#invalidlightmapsettingsmaterialname)
- [IsImportingT3D](ue_ue.EditorEngine.md#isimportingt3d)
- [LODColorationColors](ue_ue.EditorEngine.md#lodcolorationcolors)
- [LargeFont](ue_ue.EditorEngine.md#largefont)
- [LargeFontName](ue_ue.EditorEngine.md#largefontname)
- [LevelColorationLitMaterial](ue_ue.EditorEngine.md#levelcolorationlitmaterial)
- [LevelColorationLitMaterialName](ue_ue.EditorEngine.md#levelcolorationlitmaterialname)
- [LevelColorationUnlitMaterial](ue_ue.EditorEngine.md#levelcolorationunlitmaterial)
- [LevelColorationUnlitMaterialName](ue_ue.EditorEngine.md#levelcolorationunlitmaterialname)
- [LevelScriptActorClass](ue_ue.EditorEngine.md#levelscriptactorclass)
- [LevelScriptActorClassName](ue_ue.EditorEngine.md#levelscriptactorclassname)
- [LightComplexityColors](ue_ue.EditorEngine.md#lightcomplexitycolors)
- [LightMapDensitySelectedColor](ue_ue.EditorEngine.md#lightmapdensityselectedcolor)
- [LightMapDensityTexture](ue_ue.EditorEngine.md#lightmapdensitytexture)
- [LightMapDensityTextureName](ue_ue.EditorEngine.md#lightmapdensitytexturename)
- [LightMapDensityVertexMappedColor](ue_ue.EditorEngine.md#lightmapdensityvertexmappedcolor)
- [LightingOnlyBrightness](ue_ue.EditorEngine.md#lightingonlybrightness)
- [LightingTexelDensityMaterial](ue_ue.EditorEngine.md#lightingtexeldensitymaterial)
- [LightingTexelDensityName](ue_ue.EditorEngine.md#lightingtexeldensityname)
- [LocalPlayerClass](ue_ue.EditorEngine.md#localplayerclass)
- [LocalPlayerClassName](ue_ue.EditorEngine.md#localplayerclassname)
- [MaxES2PixelShaderAdditiveComplexityCount](ue_ue.EditorEngine.md#maxes2pixelshaderadditivecomplexitycount)
- [MaxES3PixelShaderAdditiveComplexityCount](ue_ue.EditorEngine.md#maxes3pixelshaderadditivecomplexitycount)
- [MaxLightMapDensity](ue_ue.EditorEngine.md#maxlightmapdensity)
- [MaxOcclusionPixelsFraction](ue_ue.EditorEngine.md#maxocclusionpixelsfraction)
- [MaxParticleResize](ue_ue.EditorEngine.md#maxparticleresize)
- [MaxParticleResizeWarn](ue_ue.EditorEngine.md#maxparticleresizewarn)
- [MaxPixelShaderAdditiveComplexityCount](ue_ue.EditorEngine.md#maxpixelshaderadditivecomplexitycount)
- [MaximumLoopIterationCount](ue_ue.EditorEngine.md#maximumloopiterationcount)
- [MediumFont](ue_ue.EditorEngine.md#mediumfont)
- [MediumFontName](ue_ue.EditorEngine.md#mediumfontname)
- [MeshLODRange](ue_ue.EditorEngine.md#meshlodrange)
- [MinDesiredFrameRate](ue_ue.EditorEngine.md#mindesiredframerate)
- [MinLightMapDensity](ue_ue.EditorEngine.md#minlightmapdensity)
- [MiniFontTexture](ue_ue.EditorEngine.md#minifonttexture)
- [MiniFontTextureName](ue_ue.EditorEngine.md#minifonttexturename)
- [MouseMovement](ue_ue.EditorEngine.md#mousemovement)
- [NavigationSystemClass](ue_ue.EditorEngine.md#navigationsystemclass)
- [NavigationSystemClassName](ue_ue.EditorEngine.md#navigationsystemclassname)
- [NavigationSystemConfigClass](ue_ue.EditorEngine.md#navigationsystemconfigclass)
- [NavigationSystemConfigClassName](ue_ue.EditorEngine.md#navigationsystemconfigclassname)
- [NearClipPlane](ue_ue.EditorEngine.md#nearclipplane)
- [NetClientTicksPerSecond](ue_ue.EditorEngine.md#netclienttickspersecond)
- [NetDriverDefinitions](ue_ue.EditorEngine.md#netdriverdefinitions)
- [NetErrorLogInterval](ue_ue.EditorEngine.md#neterrorloginterval)
- [NextWorldContextHandle](ue_ue.EditorEngine.md#nextworldcontexthandle)
- [NumPawnsAllowedToBeSpawnedInAFrame](ue_ue.EditorEngine.md#numpawnsallowedtobespawnedinaframe)
- [ParentContext](ue_ue.EditorEngine.md#parentcontext)
- [ParticleEventManagerClassPath](ue_ue.EditorEngine.md#particleeventmanagerclasspath)
- [PendingDroppedNotes](ue_ue.EditorEngine.md#pendingdroppednotes)
- [PhysicsCollisionHandlerClass](ue_ue.EditorEngine.md#physicscollisionhandlerclass)
- [PhysicsCollisionHandlerClassName](ue_ue.EditorEngine.md#physicscollisionhandlerclassname)
- [PlayFromHerePlayerStartClass](ue_ue.EditorEngine.md#playfromhereplayerstartclass)
- [PlayInEditorViewportIndex](ue_ue.EditorEngine.md#playineditorviewportindex)
- [PlayWorld](ue_ue.EditorEngine.md#playworld)
- [PlayWorldDestination](ue_ue.EditorEngine.md#playworlddestination)
- [PlayWorldLocation](ue_ue.EditorEngine.md#playworldlocation)
- [PlayWorldRotation](ue_ue.EditorEngine.md#playworldrotation)
- [PreIntegratedSkinBRDFTexture](ue_ue.EditorEngine.md#preintegratedskinbrdftexture)
- [PreIntegratedSkinBRDFTextureName](ue_ue.EditorEngine.md#preintegratedskinbrdftexturename)
- [PreviewAudioComponent](ue_ue.EditorEngine.md#previewaudiocomponent)
- [PreviewMeshComp](ue_ue.EditorEngine.md#previewmeshcomp)
- [PreviewMeshIndex](ue_ue.EditorEngine.md#previewmeshindex)
- [PreviewShadowsIndicatorMaterial](ue_ue.EditorEngine.md#previewshadowsindicatormaterial)
- [PreviewShadowsIndicatorMaterialName](ue_ue.EditorEngine.md#previewshadowsindicatormaterialname)
- [PreviewSoundCue](ue_ue.EditorEngine.md#previewsoundcue)
- [PrimitiveProbablyVisibleTime](ue_ue.EditorEngine.md#primitiveprobablyvisibletime)
- [QuadComplexityColors](ue_ue.EditorEngine.md#quadcomplexitycolors)
- [RemoveSurfaceMaterial](ue_ue.EditorEngine.md#removesurfacematerial)
- [RemoveSurfaceMaterialName](ue_ue.EditorEngine.md#removesurfacematerialname)
- [RenderLightMapDensityColorScale](ue_ue.EditorEngine.md#renderlightmapdensitycolorscale)
- [RenderLightMapDensityGrayscaleScale](ue_ue.EditorEngine.md#renderlightmapdensitygrayscalescale)
- [RuntimeServerActors](ue_ue.EditorEngine.md#runtimeserveractors)
- [ScratchRenderTarget1024](ue_ue.EditorEngine.md#scratchrendertarget1024)
- [ScratchRenderTarget2048](ue_ue.EditorEngine.md#scratchrendertarget2048)
- [ScratchRenderTarget256](ue_ue.EditorEngine.md#scratchrendertarget256)
- [ScratchRenderTarget512](ue_ue.EditorEngine.md#scratchrendertarget512)
- [ScreenSaverInhibitorSemaphore](ue_ue.EditorEngine.md#screensaverinhibitorsemaphore)
- [SelectedMaterialColor](ue_ue.EditorEngine.md#selectedmaterialcolor)
- [SelectedMaterialColorOverride](ue_ue.EditorEngine.md#selectedmaterialcoloroverride)
- [SelectionHighlightIntensity](ue_ue.EditorEngine.md#selectionhighlightintensity)
- [SelectionHighlightIntensityBillboards](ue_ue.EditorEngine.md#selectionhighlightintensitybillboards)
- [SelectionOutlineColor](ue_ue.EditorEngine.md#selectionoutlinecolor)
- [ServerActors](ue_ue.EditorEngine.md#serveractors)
- [ShadedLevelColorationLitMaterial](ue_ue.EditorEngine.md#shadedlevelcolorationlitmaterial)
- [ShadedLevelColorationLitMaterialName](ue_ue.EditorEngine.md#shadedlevelcolorationlitmaterialname)
- [ShadedLevelColorationUnlitMaterial](ue_ue.EditorEngine.md#shadedlevelcolorationunlitmaterial)
- [ShadedLevelColorationUnlitMaterialName](ue_ue.EditorEngine.md#shadedlevelcolorationunlitmaterialname)
- [ShaderComplexityColors](ue_ue.EditorEngine.md#shadercomplexitycolors)
- [SmallFont](ue_ue.EditorEngine.md#smallfont)
- [SmallFontName](ue_ue.EditorEngine.md#smallfontname)
- [SmoothedFrameRateRange](ue_ue.EditorEngine.md#smoothedframeraterange)
- [StatColorMappings](ue_ue.EditorEngine.md#statcolormappings)
- [StationaryLightOverlapColors](ue_ue.EditorEngine.md#stationarylightoverlapcolors)
- [StreamingAccuracyColors](ue_ue.EditorEngine.md#streamingaccuracycolors)
- [StreamingDistanceFactor](ue_ue.EditorEngine.md#streamingdistancefactor)
- [SubduedSelectionOutlineColor](ue_ue.EditorEngine.md#subduedselectionoutlinecolor)
- [SubtitleFont](ue_ue.EditorEngine.md#subtitlefont)
- [SubtitleFontName](ue_ue.EditorEngine.md#subtitlefontname)
- [TempModel](ue_ue.EditorEngine.md#tempmodel)
- [TickCycles](ue_ue.EditorEngine.md#tickcycles)
- [TimecodeProviderClassName](ue_ue.EditorEngine.md#timecodeproviderclassname)
- [TinyFont](ue_ue.EditorEngine.md#tinyfont)
- [TinyFontName](ue_ue.EditorEngine.md#tinyfontname)
- [Trans](ue_ue.EditorEngine.md#trans)
- [TransitionDescription](ue_ue.EditorEngine.md#transitiondescription)
- [TransitionGameMode](ue_ue.EditorEngine.md#transitiongamemode)
- [TransitionType](ue_ue.EditorEngine.md#transitiontype)
- [UnsnappedClickLocation](ue_ue.EditorEngine.md#unsnappedclicklocation)
- [UseAxisIndicator](ue_ue.EditorEngine.md#useaxisindicator)
- [UseSizingBox](ue_ue.EditorEngine.md#usesizingbox)
- [UserEditedPlayWorldURL](ue_ue.EditorEngine.md#usereditedplayworldurl)
- [UserOpenedFile](ue_ue.EditorEngine.md#useropenedfile)
- [VertexColorMaterial](ue_ue.EditorEngine.md#vertexcolormaterial)
- [VertexColorMaterialName](ue_ue.EditorEngine.md#vertexcolormaterialname)
- [VertexColorViewModeMaterialName\_AlphaAsColor](ue_ue.EditorEngine.md#vertexcolorviewmodematerialname_alphaascolor)
- [VertexColorViewModeMaterialName\_BlueOnly](ue_ue.EditorEngine.md#vertexcolorviewmodematerialname_blueonly)
- [VertexColorViewModeMaterialName\_ColorOnly](ue_ue.EditorEngine.md#vertexcolorviewmodematerialname_coloronly)
- [VertexColorViewModeMaterialName\_GreenOnly](ue_ue.EditorEngine.md#vertexcolorviewmodematerialname_greenonly)
- [VertexColorViewModeMaterialName\_RedOnly](ue_ue.EditorEngine.md#vertexcolorviewmodematerialname_redonly)
- [VertexColorViewModeMaterial\_AlphaAsColor](ue_ue.EditorEngine.md#vertexcolorviewmodematerial_alphaascolor)
- [VertexColorViewModeMaterial\_BlueOnly](ue_ue.EditorEngine.md#vertexcolorviewmodematerial_blueonly)
- [VertexColorViewModeMaterial\_ColorOnly](ue_ue.EditorEngine.md#vertexcolorviewmodematerial_coloronly)
- [VertexColorViewModeMaterial\_GreenOnly](ue_ue.EditorEngine.md#vertexcolorviewmodematerial_greenonly)
- [VertexColorViewModeMaterial\_RedOnly](ue_ue.EditorEngine.md#vertexcolorviewmodematerial_redonly)
- [WeightMapPlaceholderTexture](ue_ue.EditorEngine.md#weightmapplaceholdertexture)
- [WeightMapPlaceholderTextureName](ue_ue.EditorEngine.md#weightmapplaceholdertexturename)
- [WireframeMaterial](ue_ue.EditorEngine.md#wireframematerial)
- [WireframeMaterialName](ue_ue.EditorEngine.md#wireframematerialname)
- [WorldSettingsClass](ue_ue.EditorEngine.md#worldsettingsclass)
- [WorldSettingsClassName](ue_ue.EditorEngine.md#worldsettingsclassname)
- [\_\_tid\_EditorEngine\_\_](ue_ue.EditorEngine.md#__tid_editorengine__)
- [\_\_tid\_Engine\_\_](ue_ue.EditorEngine.md#__tid_engine__)
- [\_\_tid\_Object\_\_](ue_ue.EditorEngine.md#__tid_object__)
- [bAllowMatureLanguage](ue_ue.EditorEngine.md#ballowmaturelanguage)
- [bAllowMultiThreadedAnimationUpdate](ue_ue.EditorEngine.md#ballowmultithreadedanimationupdate)
- [bAllowMultiplePIEWorlds](ue_ue.EditorEngine.md#ballowmultiplepieworlds)
- [bCanBlueprintsTickByDefault](ue_ue.EditorEngine.md#bcanblueprintstickbydefault)
- [bCheckForMultiplePawnsSpawnedInAFrame](ue_ue.EditorEngine.md#bcheckformultiplepawnsspawnedinaframe)
- [bCustomCameraAlignEmitter](ue_ue.EditorEngine.md#bcustomcameraalignemitter)
- [bDisableAILogging](ue_ue.EditorEngine.md#bdisableailogging)
- [bDrawParticleHelpers](ue_ue.EditorEngine.md#bdrawparticlehelpers)
- [bDrawSocketsInGMode](ue_ue.EditorEngine.md#bdrawsocketsingmode)
- [bEnableEditorPSysRealtimeLOD](ue_ue.EditorEngine.md#benableeditorpsysrealtimelod)
- [bEnableLODLocking](ue_ue.EditorEngine.md#benablelodlocking)
- [bEnableOnScreenDebugMessages](ue_ue.EditorEngine.md#benableonscreendebugmessages)
- [bEnableOnScreenDebugMessagesDisplay](ue_ue.EditorEngine.md#benableonscreendebugmessagesdisplay)
- [bEnableSocketSnapping](ue_ue.EditorEngine.md#benablesocketsnapping)
- [bEnableVisualLogRecordingOnStart](ue_ue.EditorEngine.md#benablevisuallogrecordingonstart)
- [bFastRebuild](ue_ue.EditorEngine.md#bfastrebuild)
- [bHardwareSurveyEnabled](ue_ue.EditorEngine.md#bhardwaresurveyenabled)
- [bHasPlayWorldPlacement](ue_ue.EditorEngine.md#bhasplayworldplacement)
- [bIsOverridingSelectedColor](ue_ue.EditorEngine.md#bisoverridingselectedcolor)
- [bIsPlayWorldQueued](ue_ue.EditorEngine.md#bisplayworldqueued)
- [bIsSimulateInEditorQueued](ue_ue.EditorEngine.md#bissimulateineditorqueued)
- [bIsSimulatingInEditor](ue_ue.EditorEngine.md#bissimulatingineditor)
- [bIsToggleBetweenPIEandSIEQueued](ue_ue.EditorEngine.md#bistogglebetweenpieandsiequeued)
- [bLockReadOnlyLevels](ue_ue.EditorEngine.md#blockreadonlylevels)
- [bMobilePreviewPortrait](ue_ue.EditorEngine.md#bmobilepreviewportrait)
- [bNotifyUndoRedoSelectionChange](ue_ue.EditorEngine.md#bnotifyundoredoselectionchange)
- [bOptimizeAnimBlueprintMemberVariableAccess](ue_ue.EditorEngine.md#boptimizeanimblueprintmembervariableaccess)
- [bPauseOnLossOfFocus](ue_ue.EditorEngine.md#bpauseonlossoffocus)
- [bRenderLightMapDensityGrayscale](ue_ue.EditorEngine.md#brenderlightmapdensitygrayscale)
- [bRequestEndPlayMapQueued](ue_ue.EditorEngine.md#brequestendplaymapqueued)
- [bShouldGenerateLowQualityLightmaps](ue_ue.EditorEngine.md#bshouldgeneratelowqualitylightmaps)
- [bShowBrushMarkerPolys](ue_ue.EditorEngine.md#bshowbrushmarkerpolys)
- [bShowPreviewMesh](ue_ue.EditorEngine.md#bshowpreviewmesh)
- [bSmoothFrameRate](ue_ue.EditorEngine.md#bsmoothframerate)
- [bSquelchTransactionNotification](ue_ue.EditorEngine.md#bsquelchtransactionnotification)
- [bStartedLoadMapMovie](ue_ue.EditorEngine.md#bstartedloadmapmovie)
- [bSubtitlesEnabled](ue_ue.EditorEngine.md#bsubtitlesenabled)
- [bSubtitlesForcedOff](ue_ue.EditorEngine.md#bsubtitlesforcedoff)
- [bSuppressMapWarnings](ue_ue.EditorEngine.md#bsuppressmapwarnings)
- [bUseFixedFrameRate](ue_ue.EditorEngine.md#busefixedframerate)
- [bUseMobilePreviewForPlayWorld](ue_ue.EditorEngine.md#busemobilepreviewforplayworld)
- [bUseVRPreviewForPlayWorld](ue_ue.EditorEngine.md#busevrpreviewforplayworld)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorEngine.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorEngine.md#executeubergraph)
- [GetClass](ue_ue.EditorEngine.md#getclass)
- [GetName](ue_ue.EditorEngine.md#getname)
- [GetOuter](ue_ue.EditorEngine.md#getouter)
- [GetWorld](ue_ue.EditorEngine.md#getworld)
- [Find](ue_ue.EditorEngine.md#find)
- [Load](ue_ue.EditorEngine.md#load)
- [StaticClass](ue_ue.EditorEngine.md#staticclass)

## Constructors

### constructor

• **new EditorEngine**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Engine](ue_ue.Engine-1.md).[constructor](ue_ue.Engine-1.md#constructor)

## Properties

### AIControllerClassName

• **AIControllerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[AIControllerClassName](ue_ue.Engine-1.md#aicontrollerclassname)

___

### ActiveClassRedirects

• **ActiveClassRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClassRedirect`](ue_ue.ClassRedirect.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ActiveClassRedirects](ue_ue.Engine-1.md#activeclassredirects)

___

### ActiveGameNameRedirects

• **ActiveGameNameRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameNameRedirect`](ue_ue.GameNameRedirect.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ActiveGameNameRedirects](ue_ue.Engine-1.md#activegamenameredirects)

___

### ActivePluginRedirects

• **ActivePluginRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PluginRedirect`](ue_ue.PluginRedirect.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ActivePluginRedirects](ue_ue.Engine-1.md#activepluginredirects)

___

### ActiveStructRedirects

• **ActiveStructRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StructRedirect`](ue_ue.StructRedirect.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ActiveStructRedirects](ue_ue.Engine-1.md#activestructredirects)

___

### ActorFactories

• **ActorFactories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorFactory`](ue_ue.ActorFactory.md)\>

___

### ActorGroupingUtils

• **ActorGroupingUtils**: [`ActorGroupingUtils`](ue_ue.ActorGroupingUtils.md)

___

### ActorGroupingUtilsClassName

• **ActorGroupingUtilsClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### ActorsThatWereSelected

• **ActorsThatWereSelected**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>\>

___

### AdditionalFontNames

• **AdditionalFontNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[AdditionalFontNames](ue_ue.Engine-1.md#additionalfontnames)

___

### AdditionalFonts

• **AdditionalFonts**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Font`](ue_ue.Font.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[AdditionalFonts](ue_ue.Engine-1.md#additionalfonts)

___

### ArrowMaterial

• **ArrowMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ArrowMaterial](ue_ue.Engine-1.md#arrowmaterial)

___

### ArrowMaterialName

• **ArrowMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ArrowMaterialName](ue_ue.Engine-1.md#arrowmaterialname)

___

### ArrowMaterialYellow

• **ArrowMaterialYellow**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ArrowMaterialYellow](ue_ue.Engine-1.md#arrowmaterialyellow)

___

### AssetManager

• **AssetManager**: [`AssetManager`](ue_ue.AssetManager.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[AssetManager](ue_ue.Engine-1.md#assetmanager)

___

### AssetManagerClassName

• **AssetManagerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[AssetManagerClassName](ue_ue.Engine-1.md#assetmanagerclassname)

___

### AvoidanceManagerClass

• **AvoidanceManagerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[AvoidanceManagerClass](ue_ue.Engine-1.md#avoidancemanagerclass)

___

### AvoidanceManagerClassName

• **AvoidanceManagerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[AvoidanceManagerClassName](ue_ue.Engine-1.md#avoidancemanagerclassname)

___

### BSPSelectionHighlightIntensity

• **BSPSelectionHighlightIntensity**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[BSPSelectionHighlightIntensity](ue_ue.Engine-1.md#bspselectionhighlightintensity)

___

### Bad

• **Bad**: [`Texture2D`](ue_ue.Texture2D.md)

___

### BlueNoiseTexture

• **BlueNoiseTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[BlueNoiseTexture](ue_ue.Engine-1.md#bluenoisetexture)

___

### BlueNoiseTextureName

• **BlueNoiseTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[BlueNoiseTextureName](ue_ue.Engine-1.md#bluenoisetexturename)

___

### BoneWeightMaterial

• **BoneWeightMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[BoneWeightMaterial](ue_ue.Engine-1.md#boneweightmaterial)

___

### BoneWeightMaterialName

• **BoneWeightMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[BoneWeightMaterialName](ue_ue.Engine-1.md#boneweightmaterialname)

___

### BrushBuilders

• **BrushBuilders**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BrushBuilder`](ue_ue.BrushBuilder.md)\>

___

### BuildPlayDevice

• **BuildPlayDevice**: `number`

___

### C\_AddWire

• **C\_AddWire**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[C_AddWire](ue_ue.Engine-1.md#c_addwire)

___

### C\_BSPCollision

• **C\_BSPCollision**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[C_BSPCollision](ue_ue.Engine-1.md#c_bspcollision)

___

### C\_BrushShape

• **C\_BrushShape**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[C_BrushShape](ue_ue.Engine-1.md#c_brushshape)

___

### C\_BrushWire

• **C\_BrushWire**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[C_BrushWire](ue_ue.Engine-1.md#c_brushwire)

___

### C\_NonSolidWire

• **C\_NonSolidWire**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[C_NonSolidWire](ue_ue.Engine-1.md#c_nonsolidwire)

___

### C\_OrthoBackground

• **C\_OrthoBackground**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[C_OrthoBackground](ue_ue.Engine-1.md#c_orthobackground)

___

### C\_ScaleBoxHi

• **C\_ScaleBoxHi**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[C_ScaleBoxHi](ue_ue.Engine-1.md#c_scaleboxhi)

___

### C\_SemiSolidWire

• **C\_SemiSolidWire**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[C_SemiSolidWire](ue_ue.Engine-1.md#c_semisolidwire)

___

### C\_SubtractWire

• **C\_SubtractWire**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[C_SubtractWire](ue_ue.Engine-1.md#c_subtractwire)

___

### C\_Volume

• **C\_Volume**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[C_Volume](ue_ue.Engine-1.md#c_volume)

___

### C\_VolumeCollision

• **C\_VolumeCollision**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[C_VolumeCollision](ue_ue.Engine-1.md#c_volumecollision)

___

### C\_WireBackground

• **C\_WireBackground**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[C_WireBackground](ue_ue.Engine-1.md#c_wirebackground)

___

### C\_WorldBox

• **C\_WorldBox**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[C_WorldBox](ue_ue.Engine-1.md#c_worldbox)

___

### CameraRotationThreshold

• **CameraRotationThreshold**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[CameraRotationThreshold](ue_ue.Engine-1.md#camerarotationthreshold)

___

### CameraTranslationThreshold

• **CameraTranslationThreshold**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[CameraTranslationThreshold](ue_ue.Engine-1.md#cameratranslationthreshold)

___

### ClickFlags

• **ClickFlags**: `number`

___

### ClickLocation

• **ClickLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### ClickPlane

• **ClickPlane**: [`Plane`](ue_ue.Plane.md)

___

### ClientCycles

• **ClientCycles**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ClientCycles](ue_ue.Engine-1.md#clientcycles)

___

### ClothPaintMaterial

• **ClothPaintMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ClothPaintMaterial](ue_ue.Engine-1.md#clothpaintmaterial)

___

### ClothPaintMaterialInstance

• **ClothPaintMaterialInstance**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ClothPaintMaterialInstance](ue_ue.Engine-1.md#clothpaintmaterialinstance)

___

### ClothPaintMaterialName

• **ClothPaintMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ClothPaintMaterialName](ue_ue.Engine-1.md#clothpaintmaterialname)

___

### ClothPaintMaterialWireframe

• **ClothPaintMaterialWireframe**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ClothPaintMaterialWireframe](ue_ue.Engine-1.md#clothpaintmaterialwireframe)

___

### ClothPaintMaterialWireframeInstance

• **ClothPaintMaterialWireframeInstance**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ClothPaintMaterialWireframeInstance](ue_ue.Engine-1.md#clothpaintmaterialwireframeinstance)

___

### ClothPaintMaterialWireframeName

• **ClothPaintMaterialWireframeName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ClothPaintMaterialWireframeName](ue_ue.Engine-1.md#clothpaintmaterialwireframename)

___

### ConsoleClass

• **ConsoleClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ConsoleClass](ue_ue.Engine-1.md#consoleclass)

___

### ConsoleClassName

• **ConsoleClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ConsoleClassName](ue_ue.Engine-1.md#consoleclassname)

___

### ConstraintLimitMaterial

• **ConstraintLimitMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ConstraintLimitMaterial](ue_ue.Engine-1.md#constraintlimitmaterial)

___

### ConstraintLimitMaterialPrismatic

• **ConstraintLimitMaterialPrismatic**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ConstraintLimitMaterialPrismatic](ue_ue.Engine-1.md#constraintlimitmaterialprismatic)

___

### ConstraintLimitMaterialX

• **ConstraintLimitMaterialX**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ConstraintLimitMaterialX](ue_ue.Engine-1.md#constraintlimitmaterialx)

___

### ConstraintLimitMaterialXAxis

• **ConstraintLimitMaterialXAxis**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ConstraintLimitMaterialXAxis](ue_ue.Engine-1.md#constraintlimitmaterialxaxis)

___

### ConstraintLimitMaterialY

• **ConstraintLimitMaterialY**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ConstraintLimitMaterialY](ue_ue.Engine-1.md#constraintlimitmaterialy)

___

### ConstraintLimitMaterialYAxis

• **ConstraintLimitMaterialYAxis**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ConstraintLimitMaterialYAxis](ue_ue.Engine-1.md#constraintlimitmaterialyaxis)

___

### ConstraintLimitMaterialZ

• **ConstraintLimitMaterialZ**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ConstraintLimitMaterialZ](ue_ue.Engine-1.md#constraintlimitmaterialz)

___

### ConstraintLimitMaterialZAxis

• **ConstraintLimitMaterialZAxis**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ConstraintLimitMaterialZAxis](ue_ue.Engine-1.md#constraintlimitmaterialzaxis)

___

### ConversionTempModel

• **ConversionTempModel**: [`Model`](ue_ue.Model.md)

___

### CurrentCustomTimeStep

• **CurrentCustomTimeStep**: [`EngineCustomTimeStep`](ue_ue.EngineCustomTimeStep.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[CurrentCustomTimeStep](ue_ue.Engine-1.md#currentcustomtimestep)

___

### CurrentPlayWorldDestination

• **CurrentPlayWorldDestination**: `number`

___

### CustomCameraAlignEmitterDistance

• **CustomCameraAlignEmitterDistance**: `number`

___

### CustomTimeStepClassName

• **CustomTimeStepClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[CustomTimeStepClassName](ue_ue.Engine-1.md#customtimestepclassname)

___

### CustomTimecodeProvider

• **CustomTimecodeProvider**: [`TimecodeProvider`](ue_ue.TimecodeProvider.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[CustomTimecodeProvider](ue_ue.Engine-1.md#customtimecodeprovider)

___

### DebugEditorMaterial

• **DebugEditorMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DebugEditorMaterial](ue_ue.Engine-1.md#debugeditormaterial)

___

### DebugEditorMaterialName

• **DebugEditorMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DebugEditorMaterialName](ue_ue.Engine-1.md#debugeditormaterialname)

___

### DebugMeshMaterial

• **DebugMeshMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DebugMeshMaterial](ue_ue.Engine-1.md#debugmeshmaterial)

___

### DebugMeshMaterialName

• **DebugMeshMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DebugMeshMaterialName](ue_ue.Engine-1.md#debugmeshmaterialname)

___

### DefaultBSPVertexTexture

• **DefaultBSPVertexTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultBSPVertexTexture](ue_ue.Engine-1.md#defaultbspvertextexture)

___

### DefaultBSPVertexTextureName

• **DefaultBSPVertexTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultBSPVertexTextureName](ue_ue.Engine-1.md#defaultbspvertextexturename)

___

### DefaultBloomKernelTexture

• **DefaultBloomKernelTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultBloomKernelTexture](ue_ue.Engine-1.md#defaultbloomkerneltexture)

___

### DefaultBloomKernelTextureName

• **DefaultBloomKernelTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultBloomKernelTextureName](ue_ue.Engine-1.md#defaultbloomkerneltexturename)

___

### DefaultBlueprintBaseClassName

• **DefaultBlueprintBaseClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultBlueprintBaseClassName](ue_ue.Engine-1.md#defaultblueprintbaseclassname)

___

### DefaultBokehTexture

• **DefaultBokehTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultBokehTexture](ue_ue.Engine-1.md#defaultbokehtexture)

___

### DefaultBokehTextureName

• **DefaultBokehTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultBokehTextureName](ue_ue.Engine-1.md#defaultbokehtexturename)

___

### DefaultCustomTimeStep

• **DefaultCustomTimeStep**: [`EngineCustomTimeStep`](ue_ue.EngineCustomTimeStep.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultCustomTimeStep](ue_ue.Engine-1.md#defaultcustomtimestep)

___

### DefaultDiffuseTexture

• **DefaultDiffuseTexture**: [`Texture`](ue_ue.Texture.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultDiffuseTexture](ue_ue.Engine-1.md#defaultdiffusetexture)

___

### DefaultDiffuseTextureName

• **DefaultDiffuseTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultDiffuseTextureName](ue_ue.Engine-1.md#defaultdiffusetexturename)

___

### DefaultPhysMaterial

• **DefaultPhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultPhysMaterial](ue_ue.Engine-1.md#defaultphysmaterial)

___

### DefaultPhysMaterialName

• **DefaultPhysMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultPhysMaterialName](ue_ue.Engine-1.md#defaultphysmaterialname)

___

### DefaultSelectedMaterialColor

• **DefaultSelectedMaterialColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultSelectedMaterialColor](ue_ue.Engine-1.md#defaultselectedmaterialcolor)

___

### DefaultTexture

• **DefaultTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultTexture](ue_ue.Engine-1.md#defaulttexture)

___

### DefaultTextureName

• **DefaultTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultTextureName](ue_ue.Engine-1.md#defaulttexturename)

___

### DefaultTimecodeFrameRate

• **DefaultTimecodeFrameRate**: [`FrameRate`](ue_ue.FrameRate.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultTimecodeFrameRate](ue_ue.Engine-1.md#defaulttimecodeframerate)

___

### DefaultTimecodeProvider

• **DefaultTimecodeProvider**: [`TimecodeProvider`](ue_ue.TimecodeProvider.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultTimecodeProvider](ue_ue.Engine-1.md#defaulttimecodeprovider)

___

### DefaultTimecodeProviderClassName

• **DefaultTimecodeProviderClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DefaultTimecodeProviderClassName](ue_ue.Engine-1.md#defaulttimecodeproviderclassname)

___

### DeferredCommands

• **DeferredCommands**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DeferredCommands](ue_ue.Engine-1.md#deferredcommands)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

___

### DisplayGamma

• **DisplayGamma**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[DisplayGamma](ue_ue.Engine-1.md#displaygamma)

___

### EditorBrushMaterial

• **EditorBrushMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[EditorBrushMaterial](ue_ue.Engine-1.md#editorbrushmaterial)

___

### EditorBrushMaterialName

• **EditorBrushMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[EditorBrushMaterialName](ue_ue.Engine-1.md#editorbrushmaterialname)

___

### EditorCube

• **EditorCube**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### EditorCylinder

• **EditorCylinder**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### EditorFont

• **EditorFont**: [`Font`](ue_ue.Font.md)

___

### EditorPlane

• **EditorPlane**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### EditorSphere

• **EditorSphere**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### EditorWorld

• **EditorWorld**: [`World`](ue_ue.World.md)

___

### EditorWorldExtensionsManager

• **EditorWorldExtensionsManager**: [`EditorWorldExtensionManager`](ue_ue.EditorWorldExtensionManager.md)

___

### EmissiveMeshMaterial

• **EmissiveMeshMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[EmissiveMeshMaterial](ue_ue.Engine-1.md#emissivemeshmaterial)

___

### EmissiveMeshMaterialName

• **EmissiveMeshMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[EmissiveMeshMaterialName](ue_ue.Engine-1.md#emissivemeshmaterialname)

___

### FixedFrameRate

• **FixedFrameRate**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[FixedFrameRate](ue_ue.Engine-1.md#fixedframerate)

___

### GameCommandLine

• **GameCommandLine**: `string`

___

### GameCycles

• **GameCycles**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GameCycles](ue_ue.Engine-1.md#gamecycles)

___

### GameScreenshotSaveDirectory

• **GameScreenshotSaveDirectory**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GameScreenshotSaveDirectory](ue_ue.Engine-1.md#gamescreenshotsavedirectory)

___

### GameSingleton

• **GameSingleton**: [`Object`](ue_ue.Object.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GameSingleton](ue_ue.Engine-1.md#gamesingleton)

___

### GameSingletonClassName

• **GameSingletonClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GameSingletonClassName](ue_ue.Engine-1.md#gamesingletonclassname)

___

### GameUserSettings

• **GameUserSettings**: [`GameUserSettings`](ue_ue.GameUserSettings.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GameUserSettings](ue_ue.Engine-1.md#gameusersettings)

___

### GameUserSettingsClass

• **GameUserSettingsClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GameUserSettingsClass](ue_ue.Engine-1.md#gameusersettingsclass)

___

### GameUserSettingsClassName

• **GameUserSettingsClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GameUserSettingsClassName](ue_ue.Engine-1.md#gameusersettingsclassname)

___

### GameViewport

• **GameViewport**: [`GameViewportClient`](ue_ue.GameViewportClient.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GameViewport](ue_ue.Engine-1.md#gameviewport)

___

### GameViewportClientClass

• **GameViewportClientClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GameViewportClientClass](ue_ue.Engine-1.md#gameviewportclientclass)

___

### GameViewportClientClassName

• **GameViewportClientClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GameViewportClientClassName](ue_ue.Engine-1.md#gameviewportclientclassname)

___

### GeomMaterial

• **GeomMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GeomMaterial](ue_ue.Engine-1.md#geommaterial)

___

### GeomMaterialName

• **GeomMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GeomMaterialName](ue_ue.Engine-1.md#geommaterialname)

___

### GodMode

• **GodMode**: `boolean`

___

### HLODColorationColors

• **HLODColorationColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[HLODColorationColors](ue_ue.Engine-1.md#hlodcolorationcolors)

___

### HairDebugMaterial

• **HairDebugMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[HairDebugMaterial](ue_ue.Engine-1.md#hairdebugmaterial)

___

### HairDebugMaterialName

• **HairDebugMaterialName**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[HairDebugMaterialName](ue_ue.Engine-1.md#hairdebugmaterialname)

___

### HairDefaultMaterial

• **HairDefaultMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[HairDefaultMaterial](ue_ue.Engine-1.md#hairdefaultmaterial)

___

### HairDefaultMaterialName

• **HairDefaultMaterialName**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[HairDefaultMaterialName](ue_ue.Engine-1.md#hairdefaultmaterialname)

___

### HeightMapExportClassName

• **HeightMapExportClassName**: `string`

___

### HighFrequencyNoiseTexture

• **HighFrequencyNoiseTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[HighFrequencyNoiseTexture](ue_ue.Engine-1.md#highfrequencynoisetexture)

___

### HighFrequencyNoiseTextureName

• **HighFrequencyNoiseTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[HighFrequencyNoiseTextureName](ue_ue.Engine-1.md#highfrequencynoisetexturename)

___

### IdealLightMapDensity

• **IdealLightMapDensity**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[IdealLightMapDensity](ue_ue.Engine-1.md#ideallightmapdensity)

___

### InEditorGameURLOptions

• **InEditorGameURLOptions**: `string`

___

### InvalidLightmapSettingsMaterial

• **InvalidLightmapSettingsMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[InvalidLightmapSettingsMaterial](ue_ue.Engine-1.md#invalidlightmapsettingsmaterial)

___

### InvalidLightmapSettingsMaterialName

• **InvalidLightmapSettingsMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[InvalidLightmapSettingsMaterialName](ue_ue.Engine-1.md#invalidlightmapsettingsmaterialname)

___

### IsImportingT3D

• **IsImportingT3D**: `boolean`

___

### LODColorationColors

• **LODColorationColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LODColorationColors](ue_ue.Engine-1.md#lodcolorationcolors)

___

### LargeFont

• **LargeFont**: [`Font`](ue_ue.Font.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LargeFont](ue_ue.Engine-1.md#largefont)

___

### LargeFontName

• **LargeFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LargeFontName](ue_ue.Engine-1.md#largefontname)

___

### LevelColorationLitMaterial

• **LevelColorationLitMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LevelColorationLitMaterial](ue_ue.Engine-1.md#levelcolorationlitmaterial)

___

### LevelColorationLitMaterialName

• **LevelColorationLitMaterialName**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LevelColorationLitMaterialName](ue_ue.Engine-1.md#levelcolorationlitmaterialname)

___

### LevelColorationUnlitMaterial

• **LevelColorationUnlitMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LevelColorationUnlitMaterial](ue_ue.Engine-1.md#levelcolorationunlitmaterial)

___

### LevelColorationUnlitMaterialName

• **LevelColorationUnlitMaterialName**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LevelColorationUnlitMaterialName](ue_ue.Engine-1.md#levelcolorationunlitmaterialname)

___

### LevelScriptActorClass

• **LevelScriptActorClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LevelScriptActorClass](ue_ue.Engine-1.md#levelscriptactorclass)

___

### LevelScriptActorClassName

• **LevelScriptActorClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LevelScriptActorClassName](ue_ue.Engine-1.md#levelscriptactorclassname)

___

### LightComplexityColors

• **LightComplexityColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LightComplexityColors](ue_ue.Engine-1.md#lightcomplexitycolors)

___

### LightMapDensitySelectedColor

• **LightMapDensitySelectedColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LightMapDensitySelectedColor](ue_ue.Engine-1.md#lightmapdensityselectedcolor)

___

### LightMapDensityTexture

• **LightMapDensityTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LightMapDensityTexture](ue_ue.Engine-1.md#lightmapdensitytexture)

___

### LightMapDensityTextureName

• **LightMapDensityTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LightMapDensityTextureName](ue_ue.Engine-1.md#lightmapdensitytexturename)

___

### LightMapDensityVertexMappedColor

• **LightMapDensityVertexMappedColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LightMapDensityVertexMappedColor](ue_ue.Engine-1.md#lightmapdensityvertexmappedcolor)

___

### LightingOnlyBrightness

• **LightingOnlyBrightness**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LightingOnlyBrightness](ue_ue.Engine-1.md#lightingonlybrightness)

___

### LightingTexelDensityMaterial

• **LightingTexelDensityMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LightingTexelDensityMaterial](ue_ue.Engine-1.md#lightingtexeldensitymaterial)

___

### LightingTexelDensityName

• **LightingTexelDensityName**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LightingTexelDensityName](ue_ue.Engine-1.md#lightingtexeldensityname)

___

### LocalPlayerClass

• **LocalPlayerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LocalPlayerClass](ue_ue.Engine-1.md#localplayerclass)

___

### LocalPlayerClassName

• **LocalPlayerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[LocalPlayerClassName](ue_ue.Engine-1.md#localplayerclassname)

___

### MaxES2PixelShaderAdditiveComplexityCount

• **MaxES2PixelShaderAdditiveComplexityCount**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MaxES2PixelShaderAdditiveComplexityCount](ue_ue.Engine-1.md#maxes2pixelshaderadditivecomplexitycount)

___

### MaxES3PixelShaderAdditiveComplexityCount

• **MaxES3PixelShaderAdditiveComplexityCount**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MaxES3PixelShaderAdditiveComplexityCount](ue_ue.Engine-1.md#maxes3pixelshaderadditivecomplexitycount)

___

### MaxLightMapDensity

• **MaxLightMapDensity**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MaxLightMapDensity](ue_ue.Engine-1.md#maxlightmapdensity)

___

### MaxOcclusionPixelsFraction

• **MaxOcclusionPixelsFraction**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MaxOcclusionPixelsFraction](ue_ue.Engine-1.md#maxocclusionpixelsfraction)

___

### MaxParticleResize

• **MaxParticleResize**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MaxParticleResize](ue_ue.Engine-1.md#maxparticleresize)

___

### MaxParticleResizeWarn

• **MaxParticleResizeWarn**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MaxParticleResizeWarn](ue_ue.Engine-1.md#maxparticleresizewarn)

___

### MaxPixelShaderAdditiveComplexityCount

• **MaxPixelShaderAdditiveComplexityCount**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MaxPixelShaderAdditiveComplexityCount](ue_ue.Engine-1.md#maxpixelshaderadditivecomplexitycount)

___

### MaximumLoopIterationCount

• **MaximumLoopIterationCount**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MaximumLoopIterationCount](ue_ue.Engine-1.md#maximumloopiterationcount)

___

### MediumFont

• **MediumFont**: [`Font`](ue_ue.Font.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MediumFont](ue_ue.Engine-1.md#mediumfont)

___

### MediumFontName

• **MediumFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MediumFontName](ue_ue.Engine-1.md#mediumfontname)

___

### MeshLODRange

• **MeshLODRange**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MeshLODRange](ue_ue.Engine-1.md#meshlodrange)

___

### MinDesiredFrameRate

• **MinDesiredFrameRate**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MinDesiredFrameRate](ue_ue.Engine-1.md#mindesiredframerate)

___

### MinLightMapDensity

• **MinLightMapDensity**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MinLightMapDensity](ue_ue.Engine-1.md#minlightmapdensity)

___

### MiniFontTexture

• **MiniFontTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MiniFontTexture](ue_ue.Engine-1.md#minifonttexture)

___

### MiniFontTextureName

• **MiniFontTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[MiniFontTextureName](ue_ue.Engine-1.md#minifonttexturename)

___

### MouseMovement

• **MouseMovement**: [`Vector`](ue_ue_s.Vector.md)

___

### NavigationSystemClass

• **NavigationSystemClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[NavigationSystemClass](ue_ue.Engine-1.md#navigationsystemclass)

___

### NavigationSystemClassName

• **NavigationSystemClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[NavigationSystemClassName](ue_ue.Engine-1.md#navigationsystemclassname)

___

### NavigationSystemConfigClass

• **NavigationSystemConfigClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[NavigationSystemConfigClass](ue_ue.Engine-1.md#navigationsystemconfigclass)

___

### NavigationSystemConfigClassName

• **NavigationSystemConfigClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[NavigationSystemConfigClassName](ue_ue.Engine-1.md#navigationsystemconfigclassname)

___

### NearClipPlane

• **NearClipPlane**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[NearClipPlane](ue_ue.Engine-1.md#nearclipplane)

___

### NetClientTicksPerSecond

• **NetClientTicksPerSecond**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[NetClientTicksPerSecond](ue_ue.Engine-1.md#netclienttickspersecond)

___

### NetDriverDefinitions

• **NetDriverDefinitions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NetDriverDefinition`](ue_ue.NetDriverDefinition.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[NetDriverDefinitions](ue_ue.Engine-1.md#netdriverdefinitions)

___

### NetErrorLogInterval

• **NetErrorLogInterval**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[NetErrorLogInterval](ue_ue.Engine-1.md#neterrorloginterval)

___

### NextWorldContextHandle

• **NextWorldContextHandle**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[NextWorldContextHandle](ue_ue.Engine-1.md#nextworldcontexthandle)

___

### NumPawnsAllowedToBeSpawnedInAFrame

• **NumPawnsAllowedToBeSpawnedInAFrame**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[NumPawnsAllowedToBeSpawnedInAFrame](ue_ue.Engine-1.md#numpawnsallowedtobespawnedinaframe)

___

### ParentContext

• **ParentContext**: [`Package`](ue_ue.Package.md)

___

### ParticleEventManagerClassPath

• **ParticleEventManagerClassPath**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ParticleEventManagerClassPath](ue_ue.Engine-1.md#particleeventmanagerclasspath)

___

### PendingDroppedNotes

• **PendingDroppedNotes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DropNoteInfo`](ue_ue.DropNoteInfo.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[PendingDroppedNotes](ue_ue.Engine-1.md#pendingdroppednotes)

___

### PhysicsCollisionHandlerClass

• **PhysicsCollisionHandlerClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[PhysicsCollisionHandlerClass](ue_ue.Engine-1.md#physicscollisionhandlerclass)

___

### PhysicsCollisionHandlerClassName

• **PhysicsCollisionHandlerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[PhysicsCollisionHandlerClassName](ue_ue.Engine-1.md#physicscollisionhandlerclassname)

___

### PlayFromHerePlayerStartClass

• **PlayFromHerePlayerStartClass**: [`Class`](ue_ue.Class.md)

___

### PlayInEditorViewportIndex

• **PlayInEditorViewportIndex**: `number`

___

### PlayWorld

• **PlayWorld**: [`World`](ue_ue.World.md)

___

### PlayWorldDestination

• **PlayWorldDestination**: `number`

___

### PlayWorldLocation

• **PlayWorldLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### PlayWorldRotation

• **PlayWorldRotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### PreIntegratedSkinBRDFTexture

• **PreIntegratedSkinBRDFTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[PreIntegratedSkinBRDFTexture](ue_ue.Engine-1.md#preintegratedskinbrdftexture)

___

### PreIntegratedSkinBRDFTextureName

• **PreIntegratedSkinBRDFTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[PreIntegratedSkinBRDFTextureName](ue_ue.Engine-1.md#preintegratedskinbrdftexturename)

___

### PreviewAudioComponent

• **PreviewAudioComponent**: [`AudioComponent`](ue_ue.AudioComponent.md)

___

### PreviewMeshComp

• **PreviewMeshComp**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

___

### PreviewMeshIndex

• **PreviewMeshIndex**: `number`

___

### PreviewShadowsIndicatorMaterial

• **PreviewShadowsIndicatorMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[PreviewShadowsIndicatorMaterial](ue_ue.Engine-1.md#previewshadowsindicatormaterial)

___

### PreviewShadowsIndicatorMaterialName

• **PreviewShadowsIndicatorMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[PreviewShadowsIndicatorMaterialName](ue_ue.Engine-1.md#previewshadowsindicatormaterialname)

___

### PreviewSoundCue

• **PreviewSoundCue**: [`SoundCue`](ue_ue.SoundCue.md)

___

### PrimitiveProbablyVisibleTime

• **PrimitiveProbablyVisibleTime**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[PrimitiveProbablyVisibleTime](ue_ue.Engine-1.md#primitiveprobablyvisibletime)

___

### QuadComplexityColors

• **QuadComplexityColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[QuadComplexityColors](ue_ue.Engine-1.md#quadcomplexitycolors)

___

### RemoveSurfaceMaterial

• **RemoveSurfaceMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[RemoveSurfaceMaterial](ue_ue.Engine-1.md#removesurfacematerial)

___

### RemoveSurfaceMaterialName

• **RemoveSurfaceMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[RemoveSurfaceMaterialName](ue_ue.Engine-1.md#removesurfacematerialname)

___

### RenderLightMapDensityColorScale

• **RenderLightMapDensityColorScale**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[RenderLightMapDensityColorScale](ue_ue.Engine-1.md#renderlightmapdensitycolorscale)

___

### RenderLightMapDensityGrayscaleScale

• **RenderLightMapDensityGrayscaleScale**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[RenderLightMapDensityGrayscaleScale](ue_ue.Engine-1.md#renderlightmapdensitygrayscalescale)

___

### RuntimeServerActors

• **RuntimeServerActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[RuntimeServerActors](ue_ue.Engine-1.md#runtimeserveractors)

___

### ScratchRenderTarget1024

• **ScratchRenderTarget1024**: [`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

___

### ScratchRenderTarget2048

• **ScratchRenderTarget2048**: [`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

___

### ScratchRenderTarget256

• **ScratchRenderTarget256**: [`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

___

### ScratchRenderTarget512

• **ScratchRenderTarget512**: [`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

___

### ScreenSaverInhibitorSemaphore

• **ScreenSaverInhibitorSemaphore**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ScreenSaverInhibitorSemaphore](ue_ue.Engine-1.md#screensaverinhibitorsemaphore)

___

### SelectedMaterialColor

• **SelectedMaterialColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[SelectedMaterialColor](ue_ue.Engine-1.md#selectedmaterialcolor)

___

### SelectedMaterialColorOverride

• **SelectedMaterialColorOverride**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[SelectedMaterialColorOverride](ue_ue.Engine-1.md#selectedmaterialcoloroverride)

___

### SelectionHighlightIntensity

• **SelectionHighlightIntensity**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[SelectionHighlightIntensity](ue_ue.Engine-1.md#selectionhighlightintensity)

___

### SelectionHighlightIntensityBillboards

• **SelectionHighlightIntensityBillboards**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[SelectionHighlightIntensityBillboards](ue_ue.Engine-1.md#selectionhighlightintensitybillboards)

___

### SelectionOutlineColor

• **SelectionOutlineColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[SelectionOutlineColor](ue_ue.Engine-1.md#selectionoutlinecolor)

___

### ServerActors

• **ServerActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ServerActors](ue_ue.Engine-1.md#serveractors)

___

### ShadedLevelColorationLitMaterial

• **ShadedLevelColorationLitMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ShadedLevelColorationLitMaterial](ue_ue.Engine-1.md#shadedlevelcolorationlitmaterial)

___

### ShadedLevelColorationLitMaterialName

• **ShadedLevelColorationLitMaterialName**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ShadedLevelColorationLitMaterialName](ue_ue.Engine-1.md#shadedlevelcolorationlitmaterialname)

___

### ShadedLevelColorationUnlitMaterial

• **ShadedLevelColorationUnlitMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ShadedLevelColorationUnlitMaterial](ue_ue.Engine-1.md#shadedlevelcolorationunlitmaterial)

___

### ShadedLevelColorationUnlitMaterialName

• **ShadedLevelColorationUnlitMaterialName**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ShadedLevelColorationUnlitMaterialName](ue_ue.Engine-1.md#shadedlevelcolorationunlitmaterialname)

___

### ShaderComplexityColors

• **ShaderComplexityColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[ShaderComplexityColors](ue_ue.Engine-1.md#shadercomplexitycolors)

___

### SmallFont

• **SmallFont**: [`Font`](ue_ue.Font.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[SmallFont](ue_ue.Engine-1.md#smallfont)

___

### SmallFontName

• **SmallFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[SmallFontName](ue_ue.Engine-1.md#smallfontname)

___

### SmoothedFrameRateRange

• **SmoothedFrameRateRange**: [`FloatRange`](ue_ue.FloatRange.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[SmoothedFrameRateRange](ue_ue.Engine-1.md#smoothedframeraterange)

___

### StatColorMappings

• **StatColorMappings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StatColorMapping`](ue_ue.StatColorMapping.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[StatColorMappings](ue_ue.Engine-1.md#statcolormappings)

___

### StationaryLightOverlapColors

• **StationaryLightOverlapColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[StationaryLightOverlapColors](ue_ue.Engine-1.md#stationarylightoverlapcolors)

___

### StreamingAccuracyColors

• **StreamingAccuracyColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Inherited from

[Engine](ue_ue.Engine-1.md).[StreamingAccuracyColors](ue_ue.Engine-1.md#streamingaccuracycolors)

___

### StreamingDistanceFactor

• **StreamingDistanceFactor**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[StreamingDistanceFactor](ue_ue.Engine-1.md#streamingdistancefactor)

___

### SubduedSelectionOutlineColor

• **SubduedSelectionOutlineColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[SubduedSelectionOutlineColor](ue_ue.Engine-1.md#subduedselectionoutlinecolor)

___

### SubtitleFont

• **SubtitleFont**: [`Font`](ue_ue.Font.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[SubtitleFont](ue_ue.Engine-1.md#subtitlefont)

___

### SubtitleFontName

• **SubtitleFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[SubtitleFontName](ue_ue.Engine-1.md#subtitlefontname)

___

### TempModel

• **TempModel**: [`Model`](ue_ue.Model.md)

___

### TickCycles

• **TickCycles**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[TickCycles](ue_ue.Engine-1.md#tickcycles)

___

### TimecodeProviderClassName

• **TimecodeProviderClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[TimecodeProviderClassName](ue_ue.Engine-1.md#timecodeproviderclassname)

___

### TinyFont

• **TinyFont**: [`Font`](ue_ue.Font.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[TinyFont](ue_ue.Engine-1.md#tinyfont)

___

### TinyFontName

• **TinyFontName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[TinyFontName](ue_ue.Engine-1.md#tinyfontname)

___

### Trans

• **Trans**: [`Transactor`](ue_ue.Transactor.md)

___

### TransitionDescription

• **TransitionDescription**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[TransitionDescription](ue_ue.Engine-1.md#transitiondescription)

___

### TransitionGameMode

• **TransitionGameMode**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[TransitionGameMode](ue_ue.Engine-1.md#transitiongamemode)

___

### TransitionType

• **TransitionType**: [`ETransitionType`](../enums/ue_ue.ETransitionType.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[TransitionType](ue_ue.Engine-1.md#transitiontype)

___

### UnsnappedClickLocation

• **UnsnappedClickLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### UseAxisIndicator

• **UseAxisIndicator**: `boolean`

___

### UseSizingBox

• **UseSizingBox**: `boolean`

___

### UserEditedPlayWorldURL

• **UserEditedPlayWorldURL**: `string`

___

### UserOpenedFile

• **UserOpenedFile**: `string`

___

### VertexColorMaterial

• **VertexColorMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[VertexColorMaterial](ue_ue.Engine-1.md#vertexcolormaterial)

___

### VertexColorMaterialName

• **VertexColorMaterialName**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[VertexColorMaterialName](ue_ue.Engine-1.md#vertexcolormaterialname)

___

### VertexColorViewModeMaterialName\_AlphaAsColor

• **VertexColorViewModeMaterialName\_AlphaAsColor**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[VertexColorViewModeMaterialName_AlphaAsColor](ue_ue.Engine-1.md#vertexcolorviewmodematerialname_alphaascolor)

___

### VertexColorViewModeMaterialName\_BlueOnly

• **VertexColorViewModeMaterialName\_BlueOnly**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[VertexColorViewModeMaterialName_BlueOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerialname_blueonly)

___

### VertexColorViewModeMaterialName\_ColorOnly

• **VertexColorViewModeMaterialName\_ColorOnly**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[VertexColorViewModeMaterialName_ColorOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerialname_coloronly)

___

### VertexColorViewModeMaterialName\_GreenOnly

• **VertexColorViewModeMaterialName\_GreenOnly**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[VertexColorViewModeMaterialName_GreenOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerialname_greenonly)

___

### VertexColorViewModeMaterialName\_RedOnly

• **VertexColorViewModeMaterialName\_RedOnly**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[VertexColorViewModeMaterialName_RedOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerialname_redonly)

___

### VertexColorViewModeMaterial\_AlphaAsColor

• **VertexColorViewModeMaterial\_AlphaAsColor**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[VertexColorViewModeMaterial_AlphaAsColor](ue_ue.Engine-1.md#vertexcolorviewmodematerial_alphaascolor)

___

### VertexColorViewModeMaterial\_BlueOnly

• **VertexColorViewModeMaterial\_BlueOnly**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[VertexColorViewModeMaterial_BlueOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerial_blueonly)

___

### VertexColorViewModeMaterial\_ColorOnly

• **VertexColorViewModeMaterial\_ColorOnly**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[VertexColorViewModeMaterial_ColorOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerial_coloronly)

___

### VertexColorViewModeMaterial\_GreenOnly

• **VertexColorViewModeMaterial\_GreenOnly**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[VertexColorViewModeMaterial_GreenOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerial_greenonly)

___

### VertexColorViewModeMaterial\_RedOnly

• **VertexColorViewModeMaterial\_RedOnly**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[VertexColorViewModeMaterial_RedOnly](ue_ue.Engine-1.md#vertexcolorviewmodematerial_redonly)

___

### WeightMapPlaceholderTexture

• **WeightMapPlaceholderTexture**: [`Texture`](ue_ue.Texture.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[WeightMapPlaceholderTexture](ue_ue.Engine-1.md#weightmapplaceholdertexture)

___

### WeightMapPlaceholderTextureName

• **WeightMapPlaceholderTextureName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[WeightMapPlaceholderTextureName](ue_ue.Engine-1.md#weightmapplaceholdertexturename)

___

### WireframeMaterial

• **WireframeMaterial**: [`Material`](ue_ue.Material.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[WireframeMaterial](ue_ue.Engine-1.md#wireframematerial)

___

### WireframeMaterialName

• **WireframeMaterialName**: `string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[WireframeMaterialName](ue_ue.Engine-1.md#wireframematerialname)

___

### WorldSettingsClass

• **WorldSettingsClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[WorldSettingsClass](ue_ue.Engine-1.md#worldsettingsclass)

___

### WorldSettingsClassName

• **WorldSettingsClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[WorldSettingsClassName](ue_ue.Engine-1.md#worldsettingsclassname)

___

### \_\_tid\_EditorEngine\_\_

• **\_\_tid\_EditorEngine\_\_**: `boolean`

___

### \_\_tid\_Engine\_\_

• **\_\_tid\_Engine\_\_**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[__tid_Engine__](ue_ue.Engine-1.md#__tid_engine__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[__tid_Object__](ue_ue.Engine-1.md#__tid_object__)

___

### bAllowMatureLanguage

• **bAllowMatureLanguage**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bAllowMatureLanguage](ue_ue.Engine-1.md#ballowmaturelanguage)

___

### bAllowMultiThreadedAnimationUpdate

• **bAllowMultiThreadedAnimationUpdate**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bAllowMultiThreadedAnimationUpdate](ue_ue.Engine-1.md#ballowmultithreadedanimationupdate)

___

### bAllowMultiplePIEWorlds

• **bAllowMultiplePIEWorlds**: `boolean`

___

### bCanBlueprintsTickByDefault

• **bCanBlueprintsTickByDefault**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bCanBlueprintsTickByDefault](ue_ue.Engine-1.md#bcanblueprintstickbydefault)

___

### bCheckForMultiplePawnsSpawnedInAFrame

• **bCheckForMultiplePawnsSpawnedInAFrame**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bCheckForMultiplePawnsSpawnedInAFrame](ue_ue.Engine-1.md#bcheckformultiplepawnsspawnedinaframe)

___

### bCustomCameraAlignEmitter

• **bCustomCameraAlignEmitter**: `boolean`

___

### bDisableAILogging

• **bDisableAILogging**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bDisableAILogging](ue_ue.Engine-1.md#bdisableailogging)

___

### bDrawParticleHelpers

• **bDrawParticleHelpers**: `boolean`

___

### bDrawSocketsInGMode

• **bDrawSocketsInGMode**: `boolean`

___

### bEnableEditorPSysRealtimeLOD

• **bEnableEditorPSysRealtimeLOD**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bEnableEditorPSysRealtimeLOD](ue_ue.Engine-1.md#benableeditorpsysrealtimelod)

___

### bEnableLODLocking

• **bEnableLODLocking**: `boolean`

___

### bEnableOnScreenDebugMessages

• **bEnableOnScreenDebugMessages**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bEnableOnScreenDebugMessages](ue_ue.Engine-1.md#benableonscreendebugmessages)

___

### bEnableOnScreenDebugMessagesDisplay

• **bEnableOnScreenDebugMessagesDisplay**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bEnableOnScreenDebugMessagesDisplay](ue_ue.Engine-1.md#benableonscreendebugmessagesdisplay)

___

### bEnableSocketSnapping

• **bEnableSocketSnapping**: `boolean`

___

### bEnableVisualLogRecordingOnStart

• **bEnableVisualLogRecordingOnStart**: `number`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bEnableVisualLogRecordingOnStart](ue_ue.Engine-1.md#benablevisuallogrecordingonstart)

___

### bFastRebuild

• **bFastRebuild**: `boolean`

___

### bHardwareSurveyEnabled

• **bHardwareSurveyEnabled**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bHardwareSurveyEnabled](ue_ue.Engine-1.md#bhardwaresurveyenabled)

___

### bHasPlayWorldPlacement

• **bHasPlayWorldPlacement**: `boolean`

___

### bIsOverridingSelectedColor

• **bIsOverridingSelectedColor**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bIsOverridingSelectedColor](ue_ue.Engine-1.md#bisoverridingselectedcolor)

___

### bIsPlayWorldQueued

• **bIsPlayWorldQueued**: `boolean`

___

### bIsSimulateInEditorQueued

• **bIsSimulateInEditorQueued**: `boolean`

___

### bIsSimulatingInEditor

• **bIsSimulatingInEditor**: `boolean`

___

### bIsToggleBetweenPIEandSIEQueued

• **bIsToggleBetweenPIEandSIEQueued**: `boolean`

___

### bLockReadOnlyLevels

• **bLockReadOnlyLevels**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bLockReadOnlyLevels](ue_ue.Engine-1.md#blockreadonlylevels)

___

### bMobilePreviewPortrait

• **bMobilePreviewPortrait**: `boolean`

___

### bNotifyUndoRedoSelectionChange

• **bNotifyUndoRedoSelectionChange**: `boolean`

___

### bOptimizeAnimBlueprintMemberVariableAccess

• **bOptimizeAnimBlueprintMemberVariableAccess**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bOptimizeAnimBlueprintMemberVariableAccess](ue_ue.Engine-1.md#boptimizeanimblueprintmembervariableaccess)

___

### bPauseOnLossOfFocus

• **bPauseOnLossOfFocus**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bPauseOnLossOfFocus](ue_ue.Engine-1.md#bpauseonlossoffocus)

___

### bRenderLightMapDensityGrayscale

• **bRenderLightMapDensityGrayscale**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bRenderLightMapDensityGrayscale](ue_ue.Engine-1.md#brenderlightmapdensitygrayscale)

___

### bRequestEndPlayMapQueued

• **bRequestEndPlayMapQueued**: `boolean`

___

### bShouldGenerateLowQualityLightmaps

• **bShouldGenerateLowQualityLightmaps**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bShouldGenerateLowQualityLightmaps](ue_ue.Engine-1.md#bshouldgeneratelowqualitylightmaps)

___

### bShowBrushMarkerPolys

• **bShowBrushMarkerPolys**: `boolean`

___

### bShowPreviewMesh

• **bShowPreviewMesh**: `boolean`

___

### bSmoothFrameRate

• **bSmoothFrameRate**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bSmoothFrameRate](ue_ue.Engine-1.md#bsmoothframerate)

___

### bSquelchTransactionNotification

• **bSquelchTransactionNotification**: `boolean`

___

### bStartedLoadMapMovie

• **bStartedLoadMapMovie**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bStartedLoadMapMovie](ue_ue.Engine-1.md#bstartedloadmapmovie)

___

### bSubtitlesEnabled

• **bSubtitlesEnabled**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bSubtitlesEnabled](ue_ue.Engine-1.md#bsubtitlesenabled)

___

### bSubtitlesForcedOff

• **bSubtitlesForcedOff**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bSubtitlesForcedOff](ue_ue.Engine-1.md#bsubtitlesforcedoff)

___

### bSuppressMapWarnings

• **bSuppressMapWarnings**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bSuppressMapWarnings](ue_ue.Engine-1.md#bsuppressmapwarnings)

___

### bUseFixedFrameRate

• **bUseFixedFrameRate**: `boolean`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[bUseFixedFrameRate](ue_ue.Engine-1.md#busefixedframerate)

___

### bUseMobilePreviewForPlayWorld

• **bUseMobilePreviewForPlayWorld**: `boolean`

___

### bUseVRPreviewForPlayWorld

• **bUseVRPreviewForPlayWorld**: `boolean`

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

[Engine](ue_ue.Engine-1.md).[CreateDefaultSubobject](ue_ue.Engine-1.md#createdefaultsubobject)

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

[Engine](ue_ue.Engine-1.md).[ExecuteUbergraph](ue_ue.Engine-1.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GetClass](ue_ue.Engine-1.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GetName](ue_ue.Engine-1.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GetOuter](ue_ue.Engine-1.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Engine](ue_ue.Engine-1.md).[GetWorld](ue_ue.Engine-1.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorEngine`](ue_ue.EditorEngine.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorEngine`](ue_ue.EditorEngine.md)

#### Overrides

[Engine](ue_ue.Engine-1.md).[Find](ue_ue.Engine-1.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorEngine`](ue_ue.EditorEngine.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorEngine`](ue_ue.EditorEngine.md)

#### Overrides

[Engine](ue_ue.Engine-1.md).[Load](ue_ue.Engine-1.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Engine](ue_ue.Engine-1.md).[StaticClass](ue_ue.Engine-1.md#staticclass)
