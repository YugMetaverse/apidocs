[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorUtilityWidget

# Class: EditorUtilityWidget

[ue/ue](../modules/ue_ue.md).EditorUtilityWidget

## Hierarchy

- [`UserWidget`](ue_ue.UserWidget.md)

  ↳ **`EditorUtilityWidget`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorUtilityWidget.md#constructor)

### Properties

- [AccessibleBehavior](ue_ue.EditorUtilityWidget.md#accessiblebehavior)
- [AccessibleSummaryBehavior](ue_ue.EditorUtilityWidget.md#accessiblesummarybehavior)
- [AccessibleSummaryText](ue_ue.EditorUtilityWidget.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](ue_ue.EditorUtilityWidget.md#accessiblesummarytextdelegate)
- [AccessibleText](ue_ue.EditorUtilityWidget.md#accessibletext)
- [AccessibleTextDelegate](ue_ue.EditorUtilityWidget.md#accessibletextdelegate)
- [AccessibleWidgetData](ue_ue.EditorUtilityWidget.md#accessiblewidgetdata)
- [ActiveSequencePlayers](ue_ue.EditorUtilityWidget.md#activesequenceplayers)
- [AnimationCallbacks](ue_ue.EditorUtilityWidget.md#animationcallbacks)
- [CategoryName](ue_ue.EditorUtilityWidget.md#categoryname)
- [Clipping](ue_ue.EditorUtilityWidget.md#clipping)
- [ColorAndOpacity](ue_ue.EditorUtilityWidget.md#colorandopacity)
- [ColorAndOpacityDelegate](ue_ue.EditorUtilityWidget.md#colorandopacitydelegate)
- [Cursor](ue_ue.EditorUtilityWidget.md#cursor)
- [DesignSizeMode](ue_ue.EditorUtilityWidget.md#designsizemode)
- [DesignTimeSize](ue_ue.EditorUtilityWidget.md#designtimesize)
- [DesignerFlags](ue_ue.EditorUtilityWidget.md#designerflags)
- [DisplayLabel](ue_ue.EditorUtilityWidget.md#displaylabel)
- [FlowDirectionPreference](ue_ue.EditorUtilityWidget.md#flowdirectionpreference)
- [ForegroundColor](ue_ue.EditorUtilityWidget.md#foregroundcolor)
- [ForegroundColorDelegate](ue_ue.EditorUtilityWidget.md#foregroundcolordelegate)
- [HelpText](ue_ue.EditorUtilityWidget.md#helptext)
- [InputComponent](ue_ue.EditorUtilityWidget.md#inputcomponent)
- [NamedSlotBindings](ue_ue.EditorUtilityWidget.md#namedslotbindings)
- [NativeBindings](ue_ue.EditorUtilityWidget.md#nativebindings)
- [Navigation](ue_ue.EditorUtilityWidget.md#navigation)
- [Padding](ue_ue.EditorUtilityWidget.md#padding)
- [PaletteCategory](ue_ue.EditorUtilityWidget.md#palettecategory)
- [PreviewBackground](ue_ue.EditorUtilityWidget.md#previewbackground)
- [Priority](ue_ue.EditorUtilityWidget.md#priority)
- [RenderOpacity](ue_ue.EditorUtilityWidget.md#renderopacity)
- [RenderTransform](ue_ue.EditorUtilityWidget.md#rendertransform)
- [RenderTransformPivot](ue_ue.EditorUtilityWidget.md#rendertransformpivot)
- [Slot](ue_ue.EditorUtilityWidget.md#slot)
- [StoppedSequencePlayers](ue_ue.EditorUtilityWidget.md#stoppedsequenceplayers)
- [TickFrequency](ue_ue.EditorUtilityWidget.md#tickfrequency)
- [ToolTipText](ue_ue.EditorUtilityWidget.md#tooltiptext)
- [ToolTipTextDelegate](ue_ue.EditorUtilityWidget.md#tooltiptextdelegate)
- [ToolTipWidget](ue_ue.EditorUtilityWidget.md#tooltipwidget)
- [ToolTipWidgetDelegate](ue_ue.EditorUtilityWidget.md#tooltipwidgetdelegate)
- [Visibility](ue_ue.EditorUtilityWidget.md#visibility)
- [VisibilityDelegate](ue_ue.EditorUtilityWidget.md#visibilitydelegate)
- [WidgetTree](ue_ue.EditorUtilityWidget.md#widgettree)
- [\_\_tid\_EditorUtilityWidget\_\_](ue_ue.EditorUtilityWidget.md#__tid_editorutilitywidget__)
- [\_\_tid\_Object\_\_](ue_ue.EditorUtilityWidget.md#__tid_object__)
- [\_\_tid\_UserWidget\_\_](ue_ue.EditorUtilityWidget.md#__tid_userwidget__)
- [\_\_tid\_Visual\_\_](ue_ue.EditorUtilityWidget.md#__tid_visual__)
- [\_\_tid\_Widget\_\_](ue_ue.EditorUtilityWidget.md#__tid_widget__)
- [bAlwaysReregisterWithWindowsMenu](ue_ue.EditorUtilityWidget.md#balwaysreregisterwithwindowsmenu)
- [bAutoRunDefaultAction](ue_ue.EditorUtilityWidget.md#bautorundefaultaction)
- [bCanChildrenBeAccessible](ue_ue.EditorUtilityWidget.md#bcanchildrenbeaccessible)
- [bCookedWidgetTree](ue_ue.EditorUtilityWidget.md#bcookedwidgettree)
- [bCreatedByConstructionScript](ue_ue.EditorUtilityWidget.md#bcreatedbyconstructionscript)
- [bExpandedInDesigner](ue_ue.EditorUtilityWidget.md#bexpandedindesigner)
- [bHasScriptImplementedPaint](ue_ue.EditorUtilityWidget.md#bhasscriptimplementedpaint)
- [bHasScriptImplementedTick](ue_ue.EditorUtilityWidget.md#bhasscriptimplementedtick)
- [bHiddenInDesigner](ue_ue.EditorUtilityWidget.md#bhiddenindesigner)
- [bIsEnabled](ue_ue.EditorUtilityWidget.md#bisenabled)
- [bIsEnabledDelegate](ue_ue.EditorUtilityWidget.md#bisenableddelegate)
- [bIsFocusable](ue_ue.EditorUtilityWidget.md#bisfocusable)
- [bIsVariable](ue_ue.EditorUtilityWidget.md#bisvariable)
- [bIsVolatile](ue_ue.EditorUtilityWidget.md#bisvolatile)
- [bLockedInDesigner](ue_ue.EditorUtilityWidget.md#blockedindesigner)
- [bOverrideAccessibleDefaults](ue_ue.EditorUtilityWidget.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](ue_ue.EditorUtilityWidget.md#boverride_cursor)
- [bStopAction](ue_ue.EditorUtilityWidget.md#bstopaction)
- [bSupportsKeyboardFocus](ue_ue.EditorUtilityWidget.md#bsupportskeyboardfocus)

### Methods

- [AddToPlayerScreen](ue_ue.EditorUtilityWidget.md#addtoplayerscreen)
- [AddToViewport](ue_ue.EditorUtilityWidget.md#addtoviewport)
- [BindToAnimationEvent](ue_ue.EditorUtilityWidget.md#bindtoanimationevent)
- [BindToAnimationFinished](ue_ue.EditorUtilityWidget.md#bindtoanimationfinished)
- [BindToAnimationStarted](ue_ue.EditorUtilityWidget.md#bindtoanimationstarted)
- [CancelLatentActions](ue_ue.EditorUtilityWidget.md#cancellatentactions)
- [Construct](ue_ue.EditorUtilityWidget.md#construct)
- [CreateDefaultSubobject](ue_ue.EditorUtilityWidget.md#createdefaultsubobject)
- [Destruct](ue_ue.EditorUtilityWidget.md#destruct)
- [ExecuteUbergraph](ue_ue.EditorUtilityWidget.md#executeubergraph)
- [ForceLayoutPrepass](ue_ue.EditorUtilityWidget.md#forcelayoutprepass)
- [ForceVolatile](ue_ue.EditorUtilityWidget.md#forcevolatile)
- [GenerateWidgetForObject\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#generatewidgetforobject__delegatesignature)
- [GenerateWidgetForString\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#generatewidgetforstring__delegatesignature)
- [GetAlignmentInViewport](ue_ue.EditorUtilityWidget.md#getalignmentinviewport)
- [GetAnchorsInViewport](ue_ue.EditorUtilityWidget.md#getanchorsinviewport)
- [GetAnimationCurrentTime](ue_ue.EditorUtilityWidget.md#getanimationcurrenttime)
- [GetBool\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#getbool__delegatesignature)
- [GetCachedGeometry](ue_ue.EditorUtilityWidget.md#getcachedgeometry)
- [GetCheckBoxState\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#getcheckboxstate__delegatesignature)
- [GetClass](ue_ue.EditorUtilityWidget.md#getclass)
- [GetClipping](ue_ue.EditorUtilityWidget.md#getclipping)
- [GetDesiredSize](ue_ue.EditorUtilityWidget.md#getdesiredsize)
- [GetFloat\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#getfloat__delegatesignature)
- [GetGameInstance](ue_ue.EditorUtilityWidget.md#getgameinstance)
- [GetInt32\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#getint32__delegatesignature)
- [GetIsEnabled](ue_ue.EditorUtilityWidget.md#getisenabled)
- [GetIsVisible](ue_ue.EditorUtilityWidget.md#getisvisible)
- [GetLinearColor\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#getlinearcolor__delegatesignature)
- [GetMouseCursor\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#getmousecursor__delegatesignature)
- [GetName](ue_ue.EditorUtilityWidget.md#getname)
- [GetOuter](ue_ue.EditorUtilityWidget.md#getouter)
- [GetOwningLocalPlayer](ue_ue.EditorUtilityWidget.md#getowninglocalplayer)
- [GetOwningPlayer](ue_ue.EditorUtilityWidget.md#getowningplayer)
- [GetOwningPlayerPawn](ue_ue.EditorUtilityWidget.md#getowningplayerpawn)
- [GetPaintSpaceGeometry](ue_ue.EditorUtilityWidget.md#getpaintspacegeometry)
- [GetParent](ue_ue.EditorUtilityWidget.md#getparent)
- [GetRenderOpacity](ue_ue.EditorUtilityWidget.md#getrenderopacity)
- [GetRenderTransformAngle](ue_ue.EditorUtilityWidget.md#getrendertransformangle)
- [GetSlateBrush\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#getslatebrush__delegatesignature)
- [GetSlateColor\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#getslatecolor__delegatesignature)
- [GetSlateVisibility\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#getslatevisibility__delegatesignature)
- [GetText\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#gettext__delegatesignature)
- [GetTickSpaceGeometry](ue_ue.EditorUtilityWidget.md#gettickspacegeometry)
- [GetVisibility](ue_ue.EditorUtilityWidget.md#getvisibility)
- [GetWidget\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#getwidget__delegatesignature)
- [GetWorld](ue_ue.EditorUtilityWidget.md#getworld)
- [HasAnyUserFocus](ue_ue.EditorUtilityWidget.md#hasanyuserfocus)
- [HasFocusedDescendants](ue_ue.EditorUtilityWidget.md#hasfocuseddescendants)
- [HasKeyboardFocus](ue_ue.EditorUtilityWidget.md#haskeyboardfocus)
- [HasMouseCapture](ue_ue.EditorUtilityWidget.md#hasmousecapture)
- [HasMouseCaptureByUser](ue_ue.EditorUtilityWidget.md#hasmousecapturebyuser)
- [HasUserFocus](ue_ue.EditorUtilityWidget.md#hasuserfocus)
- [HasUserFocusedDescendants](ue_ue.EditorUtilityWidget.md#hasuserfocuseddescendants)
- [InvalidateLayoutAndVolatility](ue_ue.EditorUtilityWidget.md#invalidatelayoutandvolatility)
- [IsAnimationPlaying](ue_ue.EditorUtilityWidget.md#isanimationplaying)
- [IsAnimationPlayingForward](ue_ue.EditorUtilityWidget.md#isanimationplayingforward)
- [IsAnyAnimationPlaying](ue_ue.EditorUtilityWidget.md#isanyanimationplaying)
- [IsHovered](ue_ue.EditorUtilityWidget.md#ishovered)
- [IsInViewport](ue_ue.EditorUtilityWidget.md#isinviewport)
- [IsInteractable](ue_ue.EditorUtilityWidget.md#isinteractable)
- [IsListeningForInputAction](ue_ue.EditorUtilityWidget.md#islisteningforinputaction)
- [IsPlayingAnimation](ue_ue.EditorUtilityWidget.md#isplayinganimation)
- [IsVisible](ue_ue.EditorUtilityWidget.md#isvisible)
- [ListenForInputAction](ue_ue.EditorUtilityWidget.md#listenforinputaction)
- [OnAddedToFocusPath](ue_ue.EditorUtilityWidget.md#onaddedtofocuspath)
- [OnAnalogValueChanged](ue_ue.EditorUtilityWidget.md#onanalogvaluechanged)
- [OnAnimationFinished](ue_ue.EditorUtilityWidget.md#onanimationfinished)
- [OnAnimationStarted](ue_ue.EditorUtilityWidget.md#onanimationstarted)
- [OnDragCancelled](ue_ue.EditorUtilityWidget.md#ondragcancelled)
- [OnDragDetected](ue_ue.EditorUtilityWidget.md#ondragdetected)
- [OnDragEnter](ue_ue.EditorUtilityWidget.md#ondragenter)
- [OnDragLeave](ue_ue.EditorUtilityWidget.md#ondragleave)
- [OnDragOver](ue_ue.EditorUtilityWidget.md#ondragover)
- [OnDrop](ue_ue.EditorUtilityWidget.md#ondrop)
- [OnFocusLost](ue_ue.EditorUtilityWidget.md#onfocuslost)
- [OnFocusReceived](ue_ue.EditorUtilityWidget.md#onfocusreceived)
- [OnInitialized](ue_ue.EditorUtilityWidget.md#oninitialized)
- [OnKeyChar](ue_ue.EditorUtilityWidget.md#onkeychar)
- [OnKeyDown](ue_ue.EditorUtilityWidget.md#onkeydown)
- [OnKeyUp](ue_ue.EditorUtilityWidget.md#onkeyup)
- [OnMotionDetected](ue_ue.EditorUtilityWidget.md#onmotiondetected)
- [OnMouseButtonDoubleClick](ue_ue.EditorUtilityWidget.md#onmousebuttondoubleclick)
- [OnMouseButtonDown](ue_ue.EditorUtilityWidget.md#onmousebuttondown)
- [OnMouseButtonUp](ue_ue.EditorUtilityWidget.md#onmousebuttonup)
- [OnMouseCaptureLost](ue_ue.EditorUtilityWidget.md#onmousecapturelost)
- [OnMouseEnter](ue_ue.EditorUtilityWidget.md#onmouseenter)
- [OnMouseLeave](ue_ue.EditorUtilityWidget.md#onmouseleave)
- [OnMouseMove](ue_ue.EditorUtilityWidget.md#onmousemove)
- [OnMouseWheel](ue_ue.EditorUtilityWidget.md#onmousewheel)
- [OnPaint](ue_ue.EditorUtilityWidget.md#onpaint)
- [OnPointerEvent\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#onpointerevent__delegatesignature)
- [OnPreviewKeyDown](ue_ue.EditorUtilityWidget.md#onpreviewkeydown)
- [OnPreviewMouseButtonDown](ue_ue.EditorUtilityWidget.md#onpreviewmousebuttondown)
- [OnRemovedFromFocusPath](ue_ue.EditorUtilityWidget.md#onremovedfromfocuspath)
- [OnReply\_\_DelegateSignature](ue_ue.EditorUtilityWidget.md#onreply__delegatesignature)
- [OnTouchEnded](ue_ue.EditorUtilityWidget.md#ontouchended)
- [OnTouchForceChanged](ue_ue.EditorUtilityWidget.md#ontouchforcechanged)
- [OnTouchGesture](ue_ue.EditorUtilityWidget.md#ontouchgesture)
- [OnTouchMoved](ue_ue.EditorUtilityWidget.md#ontouchmoved)
- [OnTouchStarted](ue_ue.EditorUtilityWidget.md#ontouchstarted)
- [PauseAnimation](ue_ue.EditorUtilityWidget.md#pauseanimation)
- [PlayAnimation](ue_ue.EditorUtilityWidget.md#playanimation)
- [PlayAnimationForward](ue_ue.EditorUtilityWidget.md#playanimationforward)
- [PlayAnimationReverse](ue_ue.EditorUtilityWidget.md#playanimationreverse)
- [PlayAnimationTimeRange](ue_ue.EditorUtilityWidget.md#playanimationtimerange)
- [PlaySound](ue_ue.EditorUtilityWidget.md#playsound)
- [PreConstruct](ue_ue.EditorUtilityWidget.md#preconstruct)
- [RegisterInputComponent](ue_ue.EditorUtilityWidget.md#registerinputcomponent)
- [RemoveFromParent](ue_ue.EditorUtilityWidget.md#removefromparent)
- [RemoveFromViewport](ue_ue.EditorUtilityWidget.md#removefromviewport)
- [ResetCursor](ue_ue.EditorUtilityWidget.md#resetcursor)
- [ReverseAnimation](ue_ue.EditorUtilityWidget.md#reverseanimation)
- [Run](ue_ue.EditorUtilityWidget.md#run)
- [SetAlignmentInViewport](ue_ue.EditorUtilityWidget.md#setalignmentinviewport)
- [SetAllNavigationRules](ue_ue.EditorUtilityWidget.md#setallnavigationrules)
- [SetAnchorsInViewport](ue_ue.EditorUtilityWidget.md#setanchorsinviewport)
- [SetClipping](ue_ue.EditorUtilityWidget.md#setclipping)
- [SetColorAndOpacity](ue_ue.EditorUtilityWidget.md#setcolorandopacity)
- [SetCursor](ue_ue.EditorUtilityWidget.md#setcursor)
- [SetDesiredSizeInViewport](ue_ue.EditorUtilityWidget.md#setdesiredsizeinviewport)
- [SetFocus](ue_ue.EditorUtilityWidget.md#setfocus)
- [SetForegroundColor](ue_ue.EditorUtilityWidget.md#setforegroundcolor)
- [SetInputActionBlocking](ue_ue.EditorUtilityWidget.md#setinputactionblocking)
- [SetInputActionPriority](ue_ue.EditorUtilityWidget.md#setinputactionpriority)
- [SetIsEnabled](ue_ue.EditorUtilityWidget.md#setisenabled)
- [SetKeyboardFocus](ue_ue.EditorUtilityWidget.md#setkeyboardfocus)
- [SetNavigationRule](ue_ue.EditorUtilityWidget.md#setnavigationrule)
- [SetNavigationRuleBase](ue_ue.EditorUtilityWidget.md#setnavigationrulebase)
- [SetNavigationRuleCustom](ue_ue.EditorUtilityWidget.md#setnavigationrulecustom)
- [SetNavigationRuleCustomBoundary](ue_ue.EditorUtilityWidget.md#setnavigationrulecustomboundary)
- [SetNavigationRuleExplicit](ue_ue.EditorUtilityWidget.md#setnavigationruleexplicit)
- [SetNumLoopsToPlay](ue_ue.EditorUtilityWidget.md#setnumloopstoplay)
- [SetOwningPlayer](ue_ue.EditorUtilityWidget.md#setowningplayer)
- [SetPadding](ue_ue.EditorUtilityWidget.md#setpadding)
- [SetPlaybackSpeed](ue_ue.EditorUtilityWidget.md#setplaybackspeed)
- [SetPositionInViewport](ue_ue.EditorUtilityWidget.md#setpositioninviewport)
- [SetRenderOpacity](ue_ue.EditorUtilityWidget.md#setrenderopacity)
- [SetRenderScale](ue_ue.EditorUtilityWidget.md#setrenderscale)
- [SetRenderShear](ue_ue.EditorUtilityWidget.md#setrendershear)
- [SetRenderTransform](ue_ue.EditorUtilityWidget.md#setrendertransform)
- [SetRenderTransformAngle](ue_ue.EditorUtilityWidget.md#setrendertransformangle)
- [SetRenderTransformPivot](ue_ue.EditorUtilityWidget.md#setrendertransformpivot)
- [SetRenderTranslation](ue_ue.EditorUtilityWidget.md#setrendertranslation)
- [SetToolTip](ue_ue.EditorUtilityWidget.md#settooltip)
- [SetToolTipText](ue_ue.EditorUtilityWidget.md#settooltiptext)
- [SetUserFocus](ue_ue.EditorUtilityWidget.md#setuserfocus)
- [SetVisibility](ue_ue.EditorUtilityWidget.md#setvisibility)
- [StopAllAnimations](ue_ue.EditorUtilityWidget.md#stopallanimations)
- [StopAnimation](ue_ue.EditorUtilityWidget.md#stopanimation)
- [StopAnimationsAndLatentActions](ue_ue.EditorUtilityWidget.md#stopanimationsandlatentactions)
- [StopListeningForAllInputActions](ue_ue.EditorUtilityWidget.md#stoplisteningforallinputactions)
- [StopListeningForInputAction](ue_ue.EditorUtilityWidget.md#stoplisteningforinputaction)
- [Tick](ue_ue.EditorUtilityWidget.md#tick)
- [UnbindAllFromAnimationFinished](ue_ue.EditorUtilityWidget.md#unbindallfromanimationfinished)
- [UnbindAllFromAnimationStarted](ue_ue.EditorUtilityWidget.md#unbindallfromanimationstarted)
- [UnbindFromAnimationFinished](ue_ue.EditorUtilityWidget.md#unbindfromanimationfinished)
- [UnbindFromAnimationStarted](ue_ue.EditorUtilityWidget.md#unbindfromanimationstarted)
- [UnregisterInputComponent](ue_ue.EditorUtilityWidget.md#unregisterinputcomponent)
- [Find](ue_ue.EditorUtilityWidget.md#find)
- [Load](ue_ue.EditorUtilityWidget.md#load)
- [StaticClass](ue_ue.EditorUtilityWidget.md#staticclass)

## Constructors

### constructor

• **new EditorUtilityWidget**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[UserWidget](ue_ue.UserWidget.md).[constructor](ue_ue.UserWidget.md#constructor)

## Properties

### AccessibleBehavior

• **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[AccessibleBehavior](ue_ue.UserWidget.md#accessiblebehavior)

___

### AccessibleSummaryBehavior

• **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[AccessibleSummaryBehavior](ue_ue.UserWidget.md#accessiblesummarybehavior)

___

### AccessibleSummaryText

• **AccessibleSummaryText**: `string`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[AccessibleSummaryText](ue_ue.UserWidget.md#accessiblesummarytext)

___

### AccessibleSummaryTextDelegate

• **AccessibleSummaryTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[AccessibleSummaryTextDelegate](ue_ue.UserWidget.md#accessiblesummarytextdelegate)

___

### AccessibleText

• **AccessibleText**: `string`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[AccessibleText](ue_ue.UserWidget.md#accessibletext)

___

### AccessibleTextDelegate

• **AccessibleTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[AccessibleTextDelegate](ue_ue.UserWidget.md#accessibletextdelegate)

___

### AccessibleWidgetData

• **AccessibleWidgetData**: [`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[AccessibleWidgetData](ue_ue.UserWidget.md#accessiblewidgetdata)

___

### ActiveSequencePlayers

• **ActiveSequencePlayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)\>

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ActiveSequencePlayers](ue_ue.UserWidget.md#activesequenceplayers)

___

### AnimationCallbacks

• **AnimationCallbacks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationEventBinding`](ue_ue.AnimationEventBinding.md)\>

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[AnimationCallbacks](ue_ue.UserWidget.md#animationcallbacks)

___

### CategoryName

• **CategoryName**: `string`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[CategoryName](ue_ue.UserWidget.md#categoryname)

___

### Clipping

• **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[Clipping](ue_ue.UserWidget.md#clipping)

___

### ColorAndOpacity

• **ColorAndOpacity**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ColorAndOpacity](ue_ue.UserWidget.md#colorandopacity)

___

### ColorAndOpacityDelegate

• **ColorAndOpacityDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ColorAndOpacityDelegate](ue_ue.UserWidget.md#colorandopacitydelegate)

___

### Cursor

• **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[Cursor](ue_ue.UserWidget.md#cursor)

___

### DesignSizeMode

• **DesignSizeMode**: [`EDesignPreviewSizeMode`](../enums/ue_ue.EDesignPreviewSizeMode.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[DesignSizeMode](ue_ue.UserWidget.md#designsizemode)

___

### DesignTimeSize

• **DesignTimeSize**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[DesignTimeSize](ue_ue.UserWidget.md#designtimesize)

___

### DesignerFlags

• **DesignerFlags**: `number`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[DesignerFlags](ue_ue.UserWidget.md#designerflags)

___

### DisplayLabel

• **DisplayLabel**: `string`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[DisplayLabel](ue_ue.UserWidget.md#displaylabel)

___

### FlowDirectionPreference

• **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[FlowDirectionPreference](ue_ue.UserWidget.md#flowdirectionpreference)

___

### ForegroundColor

• **ForegroundColor**: [`SlateColor`](ue_ue.SlateColor.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ForegroundColor](ue_ue.UserWidget.md#foregroundcolor)

___

### ForegroundColorDelegate

• **ForegroundColorDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`SlateColor`](ue_ue.SlateColor.md)\>

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ForegroundColorDelegate](ue_ue.UserWidget.md#foregroundcolordelegate)

___

### HelpText

• **HelpText**: `string`

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[InputComponent](ue_ue.UserWidget.md#inputcomponent)

___

### NamedSlotBindings

• **NamedSlotBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedSlotBinding`](ue_ue.NamedSlotBinding.md)\>

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[NamedSlotBindings](ue_ue.UserWidget.md#namedslotbindings)

___

### NativeBindings

• **NativeBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyBinding`](ue_ue.PropertyBinding.md)\>

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[NativeBindings](ue_ue.UserWidget.md#nativebindings)

___

### Navigation

• **Navigation**: [`WidgetNavigation`](ue_ue.WidgetNavigation.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[Navigation](ue_ue.UserWidget.md#navigation)

___

### Padding

• **Padding**: [`Margin`](ue_ue.Margin.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[Padding](ue_ue.UserWidget.md#padding)

___

### PaletteCategory

• **PaletteCategory**: `string`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[PaletteCategory](ue_ue.UserWidget.md#palettecategory)

___

### PreviewBackground

• **PreviewBackground**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[PreviewBackground](ue_ue.UserWidget.md#previewbackground)

___

### Priority

• **Priority**: `number`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[Priority](ue_ue.UserWidget.md#priority)

___

### RenderOpacity

• **RenderOpacity**: `number`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[RenderOpacity](ue_ue.UserWidget.md#renderopacity)

___

### RenderTransform

• **RenderTransform**: [`WidgetTransform`](ue_ue.WidgetTransform.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[RenderTransform](ue_ue.UserWidget.md#rendertransform)

___

### RenderTransformPivot

• **RenderTransformPivot**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[RenderTransformPivot](ue_ue.UserWidget.md#rendertransformpivot)

___

### Slot

• **Slot**: [`PanelSlot`](ue_ue.PanelSlot.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[Slot](ue_ue.UserWidget.md#slot)

___

### StoppedSequencePlayers

• **StoppedSequencePlayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)\>

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[StoppedSequencePlayers](ue_ue.UserWidget.md#stoppedsequenceplayers)

___

### TickFrequency

• **TickFrequency**: [`EWidgetTickFrequency`](../enums/ue_ue.EWidgetTickFrequency.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[TickFrequency](ue_ue.UserWidget.md#tickfrequency)

___

### ToolTipText

• **ToolTipText**: `string`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ToolTipText](ue_ue.UserWidget.md#tooltiptext)

___

### ToolTipTextDelegate

• **ToolTipTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ToolTipTextDelegate](ue_ue.UserWidget.md#tooltiptextdelegate)

___

### ToolTipWidget

• **ToolTipWidget**: [`Widget`](ue_ue.Widget.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ToolTipWidget](ue_ue.UserWidget.md#tooltipwidget)

___

### ToolTipWidgetDelegate

• **ToolTipWidgetDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`Widget`](ue_ue.Widget.md)\>

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ToolTipWidgetDelegate](ue_ue.UserWidget.md#tooltipwidgetdelegate)

___

### Visibility

• **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[Visibility](ue_ue.UserWidget.md#visibility)

___

### VisibilityDelegate

• **VisibilityDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)\>

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[VisibilityDelegate](ue_ue.UserWidget.md#visibilitydelegate)

___

### WidgetTree

• **WidgetTree**: [`WidgetTree`](ue_ue.WidgetTree.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[WidgetTree](ue_ue.UserWidget.md#widgettree)

___

### \_\_tid\_EditorUtilityWidget\_\_

• **\_\_tid\_EditorUtilityWidget\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[__tid_Object__](ue_ue.UserWidget.md#__tid_object__)

___

### \_\_tid\_UserWidget\_\_

• **\_\_tid\_UserWidget\_\_**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[__tid_UserWidget__](ue_ue.UserWidget.md#__tid_userwidget__)

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[__tid_Visual__](ue_ue.UserWidget.md#__tid_visual__)

___

### \_\_tid\_Widget\_\_

• **\_\_tid\_Widget\_\_**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[__tid_Widget__](ue_ue.UserWidget.md#__tid_widget__)

___

### bAlwaysReregisterWithWindowsMenu

• **bAlwaysReregisterWithWindowsMenu**: `boolean`

___

### bAutoRunDefaultAction

• **bAutoRunDefaultAction**: `boolean`

___

### bCanChildrenBeAccessible

• **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bCanChildrenBeAccessible](ue_ue.UserWidget.md#bcanchildrenbeaccessible)

___

### bCookedWidgetTree

• **bCookedWidgetTree**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bCookedWidgetTree](ue_ue.UserWidget.md#bcookedwidgettree)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bCreatedByConstructionScript](ue_ue.UserWidget.md#bcreatedbyconstructionscript)

___

### bExpandedInDesigner

• **bExpandedInDesigner**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bExpandedInDesigner](ue_ue.UserWidget.md#bexpandedindesigner)

___

### bHasScriptImplementedPaint

• **bHasScriptImplementedPaint**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bHasScriptImplementedPaint](ue_ue.UserWidget.md#bhasscriptimplementedpaint)

___

### bHasScriptImplementedTick

• **bHasScriptImplementedTick**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bHasScriptImplementedTick](ue_ue.UserWidget.md#bhasscriptimplementedtick)

___

### bHiddenInDesigner

• **bHiddenInDesigner**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bHiddenInDesigner](ue_ue.UserWidget.md#bhiddenindesigner)

___

### bIsEnabled

• **bIsEnabled**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bIsEnabled](ue_ue.UserWidget.md#bisenabled)

___

### bIsEnabledDelegate

• **bIsEnabledDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `boolean`\>

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bIsEnabledDelegate](ue_ue.UserWidget.md#bisenableddelegate)

___

### bIsFocusable

• **bIsFocusable**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bIsFocusable](ue_ue.UserWidget.md#bisfocusable)

___

### bIsVariable

• **bIsVariable**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bIsVariable](ue_ue.UserWidget.md#bisvariable)

___

### bIsVolatile

• **bIsVolatile**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bIsVolatile](ue_ue.UserWidget.md#bisvolatile)

___

### bLockedInDesigner

• **bLockedInDesigner**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bLockedInDesigner](ue_ue.UserWidget.md#blockedindesigner)

___

### bOverrideAccessibleDefaults

• **bOverrideAccessibleDefaults**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bOverrideAccessibleDefaults](ue_ue.UserWidget.md#boverrideaccessibledefaults)

___

### bOverride\_Cursor

• **bOverride\_Cursor**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bOverride_Cursor](ue_ue.UserWidget.md#boverride_cursor)

___

### bStopAction

• **bStopAction**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bStopAction](ue_ue.UserWidget.md#bstopaction)

___

### bSupportsKeyboardFocus

• **bSupportsKeyboardFocus**: `boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[bSupportsKeyboardFocus](ue_ue.UserWidget.md#bsupportskeyboardfocus)

## Methods

### AddToPlayerScreen

▸ **AddToPlayerScreen**(`ZOrder?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ZOrder?` | `number` |

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[AddToPlayerScreen](ue_ue.UserWidget.md#addtoplayerscreen)

___

### AddToViewport

▸ **AddToViewport**(`ZOrder?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ZOrder?` | `number` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[AddToViewport](ue_ue.UserWidget.md#addtoviewport)

___

### BindToAnimationEvent

▸ **BindToAnimationEvent**(`Animation`, `Delegate`, `AnimationEvent`, `UserTag?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |
| `Delegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\> |
| `AnimationEvent` | [`EWidgetAnimationEvent`](../enums/ue_ue.EWidgetAnimationEvent.md) |
| `UserTag?` | `string` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[BindToAnimationEvent](ue_ue.UserWidget.md#bindtoanimationevent)

___

### BindToAnimationFinished

▸ **BindToAnimationFinished**(`Animation`, `Delegate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |
| `Delegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[BindToAnimationFinished](ue_ue.UserWidget.md#bindtoanimationfinished)

___

### BindToAnimationStarted

▸ **BindToAnimationStarted**(`Animation`, `Delegate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |
| `Delegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[BindToAnimationStarted](ue_ue.UserWidget.md#bindtoanimationstarted)

___

### CancelLatentActions

▸ **CancelLatentActions**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[CancelLatentActions](ue_ue.UserWidget.md#cancellatentactions)

___

### Construct

▸ **Construct**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[Construct](ue_ue.UserWidget.md#construct)

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

[UserWidget](ue_ue.UserWidget.md).[CreateDefaultSubobject](ue_ue.UserWidget.md#createdefaultsubobject)

___

### Destruct

▸ **Destruct**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[Destruct](ue_ue.UserWidget.md#destruct)

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

[UserWidget](ue_ue.UserWidget.md).[ExecuteUbergraph](ue_ue.UserWidget.md#executeubergraph)

___

### ForceLayoutPrepass

▸ **ForceLayoutPrepass**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ForceLayoutPrepass](ue_ue.UserWidget.md#forcelayoutprepass)

___

### ForceVolatile

▸ **ForceVolatile**(`bForce`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bForce` | `boolean` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ForceVolatile](ue_ue.UserWidget.md#forcevolatile)

___

### GenerateWidgetForObject\_\_DelegateSignature

▸ **GenerateWidgetForObject__DelegateSignature**(`Item`): [`Widget`](ue_ue.Widget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GenerateWidgetForObject__DelegateSignature](ue_ue.UserWidget.md#generatewidgetforobject__delegatesignature)

___

### GenerateWidgetForString\_\_DelegateSignature

▸ **GenerateWidgetForString__DelegateSignature**(`Item`): [`Widget`](ue_ue.Widget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Item` | `string` |

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GenerateWidgetForString__DelegateSignature](ue_ue.UserWidget.md#generatewidgetforstring__delegatesignature)

___

### GetAlignmentInViewport

▸ **GetAlignmentInViewport**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetAlignmentInViewport](ue_ue.UserWidget.md#getalignmentinviewport)

___

### GetAnchorsInViewport

▸ **GetAnchorsInViewport**(): [`Anchors`](ue_ue.Anchors.md)

#### Returns

[`Anchors`](ue_ue.Anchors.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetAnchorsInViewport](ue_ue.UserWidget.md#getanchorsinviewport)

___

### GetAnimationCurrentTime

▸ **GetAnimationCurrentTime**(`InAnimation`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`number`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetAnimationCurrentTime](ue_ue.UserWidget.md#getanimationcurrenttime)

___

### GetBool\_\_DelegateSignature

▸ **GetBool__DelegateSignature**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetBool__DelegateSignature](ue_ue.UserWidget.md#getbool__delegatesignature)

___

### GetCachedGeometry

▸ **GetCachedGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetCachedGeometry](ue_ue.UserWidget.md#getcachedgeometry)

___

### GetCheckBoxState\_\_DelegateSignature

▸ **GetCheckBoxState__DelegateSignature**(): [`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Returns

[`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetCheckBoxState__DelegateSignature](ue_ue.UserWidget.md#getcheckboxstate__delegatesignature)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetClass](ue_ue.UserWidget.md#getclass)

___

### GetClipping

▸ **GetClipping**(): [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Returns

[`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetClipping](ue_ue.UserWidget.md#getclipping)

___

### GetDesiredSize

▸ **GetDesiredSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetDesiredSize](ue_ue.UserWidget.md#getdesiredsize)

___

### GetFloat\_\_DelegateSignature

▸ **GetFloat__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetFloat__DelegateSignature](ue_ue.UserWidget.md#getfloat__delegatesignature)

___

### GetGameInstance

▸ **GetGameInstance**(): [`GameInstance`](ue_ue.GameInstance.md)

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetGameInstance](ue_ue.UserWidget.md#getgameinstance)

___

### GetInt32\_\_DelegateSignature

▸ **GetInt32__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetInt32__DelegateSignature](ue_ue.UserWidget.md#getint32__delegatesignature)

___

### GetIsEnabled

▸ **GetIsEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetIsEnabled](ue_ue.UserWidget.md#getisenabled)

___

### GetIsVisible

▸ **GetIsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetIsVisible](ue_ue.UserWidget.md#getisvisible)

___

### GetLinearColor\_\_DelegateSignature

▸ **GetLinearColor__DelegateSignature**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetLinearColor__DelegateSignature](ue_ue.UserWidget.md#getlinearcolor__delegatesignature)

___

### GetMouseCursor\_\_DelegateSignature

▸ **GetMouseCursor__DelegateSignature**(): [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Returns

[`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetMouseCursor__DelegateSignature](ue_ue.UserWidget.md#getmousecursor__delegatesignature)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetName](ue_ue.UserWidget.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetOuter](ue_ue.UserWidget.md#getouter)

___

### GetOwningLocalPlayer

▸ **GetOwningLocalPlayer**(): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetOwningLocalPlayer](ue_ue.UserWidget.md#getowninglocalplayer)

___

### GetOwningPlayer

▸ **GetOwningPlayer**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetOwningPlayer](ue_ue.UserWidget.md#getowningplayer)

___

### GetOwningPlayerPawn

▸ **GetOwningPlayerPawn**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetOwningPlayerPawn](ue_ue.UserWidget.md#getowningplayerpawn)

___

### GetPaintSpaceGeometry

▸ **GetPaintSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetPaintSpaceGeometry](ue_ue.UserWidget.md#getpaintspacegeometry)

___

### GetParent

▸ **GetParent**(): [`PanelWidget`](ue_ue.PanelWidget.md)

#### Returns

[`PanelWidget`](ue_ue.PanelWidget.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetParent](ue_ue.UserWidget.md#getparent)

___

### GetRenderOpacity

▸ **GetRenderOpacity**(): `number`

#### Returns

`number`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetRenderOpacity](ue_ue.UserWidget.md#getrenderopacity)

___

### GetRenderTransformAngle

▸ **GetRenderTransformAngle**(): `number`

#### Returns

`number`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetRenderTransformAngle](ue_ue.UserWidget.md#getrendertransformangle)

___

### GetSlateBrush\_\_DelegateSignature

▸ **GetSlateBrush__DelegateSignature**(): [`SlateBrush`](ue_ue.SlateBrush.md)

#### Returns

[`SlateBrush`](ue_ue.SlateBrush.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetSlateBrush__DelegateSignature](ue_ue.UserWidget.md#getslatebrush__delegatesignature)

___

### GetSlateColor\_\_DelegateSignature

▸ **GetSlateColor__DelegateSignature**(): [`SlateColor`](ue_ue.SlateColor.md)

#### Returns

[`SlateColor`](ue_ue.SlateColor.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetSlateColor__DelegateSignature](ue_ue.UserWidget.md#getslatecolor__delegatesignature)

___

### GetSlateVisibility\_\_DelegateSignature

▸ **GetSlateVisibility__DelegateSignature**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetSlateVisibility__DelegateSignature](ue_ue.UserWidget.md#getslatevisibility__delegatesignature)

___

### GetText\_\_DelegateSignature

▸ **GetText__DelegateSignature**(): `string`

#### Returns

`string`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetText__DelegateSignature](ue_ue.UserWidget.md#gettext__delegatesignature)

___

### GetTickSpaceGeometry

▸ **GetTickSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetTickSpaceGeometry](ue_ue.UserWidget.md#gettickspacegeometry)

___

### GetVisibility

▸ **GetVisibility**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetVisibility](ue_ue.UserWidget.md#getvisibility)

___

### GetWidget\_\_DelegateSignature

▸ **GetWidget__DelegateSignature**(): [`Widget`](ue_ue.Widget.md)

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetWidget__DelegateSignature](ue_ue.UserWidget.md#getwidget__delegatesignature)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[GetWorld](ue_ue.UserWidget.md#getworld)

___

### HasAnyUserFocus

▸ **HasAnyUserFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[HasAnyUserFocus](ue_ue.UserWidget.md#hasanyuserfocus)

___

### HasFocusedDescendants

▸ **HasFocusedDescendants**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[HasFocusedDescendants](ue_ue.UserWidget.md#hasfocuseddescendants)

___

### HasKeyboardFocus

▸ **HasKeyboardFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[HasKeyboardFocus](ue_ue.UserWidget.md#haskeyboardfocus)

___

### HasMouseCapture

▸ **HasMouseCapture**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[HasMouseCapture](ue_ue.UserWidget.md#hasmousecapture)

___

### HasMouseCaptureByUser

▸ **HasMouseCaptureByUser**(`UserIndex`, `PointerIndex?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `UserIndex` | `number` |
| `PointerIndex?` | `number` |

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[HasMouseCaptureByUser](ue_ue.UserWidget.md#hasmousecapturebyuser)

___

### HasUserFocus

▸ **HasUserFocus**(`PlayerController`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[HasUserFocus](ue_ue.UserWidget.md#hasuserfocus)

___

### HasUserFocusedDescendants

▸ **HasUserFocusedDescendants**(`PlayerController`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[HasUserFocusedDescendants](ue_ue.UserWidget.md#hasuserfocuseddescendants)

___

### InvalidateLayoutAndVolatility

▸ **InvalidateLayoutAndVolatility**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[InvalidateLayoutAndVolatility](ue_ue.UserWidget.md#invalidatelayoutandvolatility)

___

### IsAnimationPlaying

▸ **IsAnimationPlaying**(`InAnimation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[IsAnimationPlaying](ue_ue.UserWidget.md#isanimationplaying)

___

### IsAnimationPlayingForward

▸ **IsAnimationPlayingForward**(`InAnimation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[IsAnimationPlayingForward](ue_ue.UserWidget.md#isanimationplayingforward)

___

### IsAnyAnimationPlaying

▸ **IsAnyAnimationPlaying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[IsAnyAnimationPlaying](ue_ue.UserWidget.md#isanyanimationplaying)

___

### IsHovered

▸ **IsHovered**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[IsHovered](ue_ue.UserWidget.md#ishovered)

___

### IsInViewport

▸ **IsInViewport**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[IsInViewport](ue_ue.UserWidget.md#isinviewport)

___

### IsInteractable

▸ **IsInteractable**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[IsInteractable](ue_ue.UserWidget.md#isinteractable)

___

### IsListeningForInputAction

▸ **IsListeningForInputAction**(`ActionName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActionName` | `string` |

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[IsListeningForInputAction](ue_ue.UserWidget.md#islisteningforinputaction)

___

### IsPlayingAnimation

▸ **IsPlayingAnimation**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[IsPlayingAnimation](ue_ue.UserWidget.md#isplayinganimation)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[IsVisible](ue_ue.UserWidget.md#isvisible)

___

### ListenForInputAction

▸ **ListenForInputAction**(`ActionName`, `EventType`, `bConsume`, `Callback`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActionName` | `string` |
| `EventType` | [`EInputEvent`](../enums/ue_ue.EInputEvent.md) |
| `bConsume` | `boolean` |
| `Callback` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ListenForInputAction](ue_ue.UserWidget.md#listenforinputaction)

___

### OnAddedToFocusPath

▸ **OnAddedToFocusPath**(`InFocusEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFocusEvent` | [`FocusEvent`](ue_ue.FocusEvent.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnAddedToFocusPath](ue_ue.UserWidget.md#onaddedtofocuspath)

___

### OnAnalogValueChanged

▸ **OnAnalogValueChanged**(`MyGeometry`, `InAnalogInputEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `InAnalogInputEvent` | [`AnalogInputEvent`](ue_ue.AnalogInputEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnAnalogValueChanged](ue_ue.UserWidget.md#onanalogvaluechanged)

___

### OnAnimationFinished

▸ **OnAnimationFinished**(`Animation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnAnimationFinished](ue_ue.UserWidget.md#onanimationfinished)

___

### OnAnimationStarted

▸ **OnAnimationStarted**(`Animation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnAnimationStarted](ue_ue.UserWidget.md#onanimationstarted)

___

### OnDragCancelled

▸ **OnDragCancelled**(`PointerEvent`, `Operation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointerEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |
| `Operation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DragDropOperation`](ue_ue.DragDropOperation.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnDragCancelled](ue_ue.UserWidget.md#ondragcancelled)

___

### OnDragDetected

▸ **OnDragDetected**(`MyGeometry`, `PointerEvent`, `Operation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `PointerEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |
| `Operation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`DragDropOperation`](ue_ue.DragDropOperation.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnDragDetected](ue_ue.UserWidget.md#ondragdetected)

___

### OnDragEnter

▸ **OnDragEnter**(`MyGeometry`, `PointerEvent`, `Operation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `PointerEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |
| `Operation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DragDropOperation`](ue_ue.DragDropOperation.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnDragEnter](ue_ue.UserWidget.md#ondragenter)

___

### OnDragLeave

▸ **OnDragLeave**(`PointerEvent`, `Operation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PointerEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |
| `Operation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DragDropOperation`](ue_ue.DragDropOperation.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnDragLeave](ue_ue.UserWidget.md#ondragleave)

___

### OnDragOver

▸ **OnDragOver**(`MyGeometry`, `PointerEvent`, `Operation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `PointerEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |
| `Operation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DragDropOperation`](ue_ue.DragDropOperation.md)\> |

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnDragOver](ue_ue.UserWidget.md#ondragover)

___

### OnDrop

▸ **OnDrop**(`MyGeometry`, `PointerEvent`, `Operation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `PointerEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |
| `Operation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DragDropOperation`](ue_ue.DragDropOperation.md)\> |

#### Returns

`boolean`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnDrop](ue_ue.UserWidget.md#ondrop)

___

### OnFocusLost

▸ **OnFocusLost**(`InFocusEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFocusEvent` | [`FocusEvent`](ue_ue.FocusEvent.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnFocusLost](ue_ue.UserWidget.md#onfocuslost)

___

### OnFocusReceived

▸ **OnFocusReceived**(`MyGeometry`, `InFocusEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `InFocusEvent` | [`FocusEvent`](ue_ue.FocusEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnFocusReceived](ue_ue.UserWidget.md#onfocusreceived)

___

### OnInitialized

▸ **OnInitialized**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnInitialized](ue_ue.UserWidget.md#oninitialized)

___

### OnKeyChar

▸ **OnKeyChar**(`MyGeometry`, `InCharacterEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `InCharacterEvent` | [`CharacterEvent`](ue_ue.CharacterEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnKeyChar](ue_ue.UserWidget.md#onkeychar)

___

### OnKeyDown

▸ **OnKeyDown**(`MyGeometry`, `InKeyEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `InKeyEvent` | [`KeyEvent`](ue_ue.KeyEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnKeyDown](ue_ue.UserWidget.md#onkeydown)

___

### OnKeyUp

▸ **OnKeyUp**(`MyGeometry`, `InKeyEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `InKeyEvent` | [`KeyEvent`](ue_ue.KeyEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnKeyUp](ue_ue.UserWidget.md#onkeyup)

___

### OnMotionDetected

▸ **OnMotionDetected**(`MyGeometry`, `InMotionEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `InMotionEvent` | [`MotionEvent`](ue_ue.MotionEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnMotionDetected](ue_ue.UserWidget.md#onmotiondetected)

___

### OnMouseButtonDoubleClick

▸ **OnMouseButtonDoubleClick**(`InMyGeometry`, `InMouseEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `InMouseEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnMouseButtonDoubleClick](ue_ue.UserWidget.md#onmousebuttondoubleclick)

___

### OnMouseButtonDown

▸ **OnMouseButtonDown**(`MyGeometry`, `MouseEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `MouseEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnMouseButtonDown](ue_ue.UserWidget.md#onmousebuttondown)

___

### OnMouseButtonUp

▸ **OnMouseButtonUp**(`MyGeometry`, `MouseEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `MouseEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnMouseButtonUp](ue_ue.UserWidget.md#onmousebuttonup)

___

### OnMouseCaptureLost

▸ **OnMouseCaptureLost**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnMouseCaptureLost](ue_ue.UserWidget.md#onmousecapturelost)

___

### OnMouseEnter

▸ **OnMouseEnter**(`MyGeometry`, `MouseEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `MouseEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnMouseEnter](ue_ue.UserWidget.md#onmouseenter)

___

### OnMouseLeave

▸ **OnMouseLeave**(`MouseEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MouseEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnMouseLeave](ue_ue.UserWidget.md#onmouseleave)

___

### OnMouseMove

▸ **OnMouseMove**(`MyGeometry`, `MouseEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `MouseEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnMouseMove](ue_ue.UserWidget.md#onmousemove)

___

### OnMouseWheel

▸ **OnMouseWheel**(`MyGeometry`, `MouseEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `MouseEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnMouseWheel](ue_ue.UserWidget.md#onmousewheel)

___

### OnPaint

▸ **OnPaint**(`Context`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Context` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PaintContext`](ue_ue.PaintContext.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnPaint](ue_ue.UserWidget.md#onpaint)

___

### OnPointerEvent\_\_DelegateSignature

▸ **OnPointerEvent__DelegateSignature**(`MyGeometry`, `MouseEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `MouseEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnPointerEvent__DelegateSignature](ue_ue.UserWidget.md#onpointerevent__delegatesignature)

___

### OnPreviewKeyDown

▸ **OnPreviewKeyDown**(`MyGeometry`, `InKeyEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `InKeyEvent` | [`KeyEvent`](ue_ue.KeyEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnPreviewKeyDown](ue_ue.UserWidget.md#onpreviewkeydown)

___

### OnPreviewMouseButtonDown

▸ **OnPreviewMouseButtonDown**(`MyGeometry`, `MouseEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `MouseEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnPreviewMouseButtonDown](ue_ue.UserWidget.md#onpreviewmousebuttondown)

___

### OnRemovedFromFocusPath

▸ **OnRemovedFromFocusPath**(`InFocusEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFocusEvent` | [`FocusEvent`](ue_ue.FocusEvent.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnRemovedFromFocusPath](ue_ue.UserWidget.md#onremovedfromfocuspath)

___

### OnReply\_\_DelegateSignature

▸ **OnReply__DelegateSignature**(): [`EventReply`](ue_ue.EventReply.md)

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnReply__DelegateSignature](ue_ue.UserWidget.md#onreply__delegatesignature)

___

### OnTouchEnded

▸ **OnTouchEnded**(`MyGeometry`, `InTouchEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `InTouchEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnTouchEnded](ue_ue.UserWidget.md#ontouchended)

___

### OnTouchForceChanged

▸ **OnTouchForceChanged**(`MyGeometry`, `InTouchEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `InTouchEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnTouchForceChanged](ue_ue.UserWidget.md#ontouchforcechanged)

___

### OnTouchGesture

▸ **OnTouchGesture**(`MyGeometry`, `GestureEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `GestureEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnTouchGesture](ue_ue.UserWidget.md#ontouchgesture)

___

### OnTouchMoved

▸ **OnTouchMoved**(`MyGeometry`, `InTouchEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `InTouchEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnTouchMoved](ue_ue.UserWidget.md#ontouchmoved)

___

### OnTouchStarted

▸ **OnTouchStarted**(`MyGeometry`, `InTouchEvent`): [`EventReply`](ue_ue.EventReply.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `InTouchEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[OnTouchStarted](ue_ue.UserWidget.md#ontouchstarted)

___

### PauseAnimation

▸ **PauseAnimation**(`InAnimation`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`number`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[PauseAnimation](ue_ue.UserWidget.md#pauseanimation)

___

### PlayAnimation

▸ **PlayAnimation**(`InAnimation`, `StartAtTime?`, `NumLoopsToPlay?`, `PlayMode?`, `PlaybackSpeed?`, `bRestoreState?`): [`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |
| `StartAtTime?` | `number` |
| `NumLoopsToPlay?` | `number` |
| `PlayMode?` | [`EUMGSequencePlayMode`](../enums/ue_ue.EUMGSequencePlayMode.md) |
| `PlaybackSpeed?` | `number` |
| `bRestoreState?` | `boolean` |

#### Returns

[`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[PlayAnimation](ue_ue.UserWidget.md#playanimation)

___

### PlayAnimationForward

▸ **PlayAnimationForward**(`InAnimation`, `PlaybackSpeed?`, `bRestoreState?`): [`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |
| `PlaybackSpeed?` | `number` |
| `bRestoreState?` | `boolean` |

#### Returns

[`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[PlayAnimationForward](ue_ue.UserWidget.md#playanimationforward)

___

### PlayAnimationReverse

▸ **PlayAnimationReverse**(`InAnimation`, `PlaybackSpeed?`, `bRestoreState?`): [`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |
| `PlaybackSpeed?` | `number` |
| `bRestoreState?` | `boolean` |

#### Returns

[`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[PlayAnimationReverse](ue_ue.UserWidget.md#playanimationreverse)

___

### PlayAnimationTimeRange

▸ **PlayAnimationTimeRange**(`InAnimation`, `StartAtTime?`, `EndAtTime?`, `NumLoopsToPlay?`, `PlayMode?`, `PlaybackSpeed?`, `bRestoreState?`): [`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |
| `StartAtTime?` | `number` |
| `EndAtTime?` | `number` |
| `NumLoopsToPlay?` | `number` |
| `PlayMode?` | [`EUMGSequencePlayMode`](../enums/ue_ue.EUMGSequencePlayMode.md) |
| `PlaybackSpeed?` | `number` |
| `bRestoreState?` | `boolean` |

#### Returns

[`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[PlayAnimationTimeRange](ue_ue.UserWidget.md#playanimationtimerange)

___

### PlaySound

▸ **PlaySound**(`SoundToPlay`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SoundToPlay` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundBase`](ue_ue.SoundBase.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[PlaySound](ue_ue.UserWidget.md#playsound)

___

### PreConstruct

▸ **PreConstruct**(`IsDesignTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `IsDesignTime` | `boolean` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[PreConstruct](ue_ue.UserWidget.md#preconstruct)

___

### RegisterInputComponent

▸ **RegisterInputComponent**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[RegisterInputComponent](ue_ue.UserWidget.md#registerinputcomponent)

___

### RemoveFromParent

▸ **RemoveFromParent**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[RemoveFromParent](ue_ue.UserWidget.md#removefromparent)

___

### RemoveFromViewport

▸ **RemoveFromViewport**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[RemoveFromViewport](ue_ue.UserWidget.md#removefromviewport)

___

### ResetCursor

▸ **ResetCursor**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ResetCursor](ue_ue.UserWidget.md#resetcursor)

___

### ReverseAnimation

▸ **ReverseAnimation**(`InAnimation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[ReverseAnimation](ue_ue.UserWidget.md#reverseanimation)

___

### Run

▸ **Run**(): `void`

#### Returns

`void`

___

### SetAlignmentInViewport

▸ **SetAlignmentInViewport**(`Alignment`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Alignment` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetAlignmentInViewport](ue_ue.UserWidget.md#setalignmentinviewport)

___

### SetAllNavigationRules

▸ **SetAllNavigationRules**(`Rule`, `WidgetToFocus`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rule` | [`EUINavigationRule`](../enums/ue_ue.EUINavigationRule.md) |
| `WidgetToFocus` | `string` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetAllNavigationRules](ue_ue.UserWidget.md#setallnavigationrules)

___

### SetAnchorsInViewport

▸ **SetAnchorsInViewport**(`Anchors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Anchors` | [`Anchors`](ue_ue.Anchors.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetAnchorsInViewport](ue_ue.UserWidget.md#setanchorsinviewport)

___

### SetClipping

▸ **SetClipping**(`InClipping`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InClipping` | [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetClipping](ue_ue.UserWidget.md#setclipping)

___

### SetColorAndOpacity

▸ **SetColorAndOpacity**(`InColorAndOpacity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColorAndOpacity` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetColorAndOpacity](ue_ue.UserWidget.md#setcolorandopacity)

___

### SetCursor

▸ **SetCursor**(`InCursor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCursor` | [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetCursor](ue_ue.UserWidget.md#setcursor)

___

### SetDesiredSizeInViewport

▸ **SetDesiredSizeInViewport**(`Size`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Size` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetDesiredSizeInViewport](ue_ue.UserWidget.md#setdesiredsizeinviewport)

___

### SetFocus

▸ **SetFocus**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetFocus](ue_ue.UserWidget.md#setfocus)

___

### SetForegroundColor

▸ **SetForegroundColor**(`InForegroundColor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InForegroundColor` | [`SlateColor`](ue_ue.SlateColor.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetForegroundColor](ue_ue.UserWidget.md#setforegroundcolor)

___

### SetInputActionBlocking

▸ **SetInputActionBlocking**(`bShouldBlock`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bShouldBlock` | `boolean` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetInputActionBlocking](ue_ue.UserWidget.md#setinputactionblocking)

___

### SetInputActionPriority

▸ **SetInputActionPriority**(`NewPriority`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPriority` | `number` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetInputActionPriority](ue_ue.UserWidget.md#setinputactionpriority)

___

### SetIsEnabled

▸ **SetIsEnabled**(`bInIsEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInIsEnabled` | `boolean` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetIsEnabled](ue_ue.UserWidget.md#setisenabled)

___

### SetKeyboardFocus

▸ **SetKeyboardFocus**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetKeyboardFocus](ue_ue.UserWidget.md#setkeyboardfocus)

___

### SetNavigationRule

▸ **SetNavigationRule**(`Direction`, `Rule`, `WidgetToFocus`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Direction` | [`EUINavigation`](../enums/ue_ue.EUINavigation.md) |
| `Rule` | [`EUINavigationRule`](../enums/ue_ue.EUINavigationRule.md) |
| `WidgetToFocus` | `string` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetNavigationRule](ue_ue.UserWidget.md#setnavigationrule)

___

### SetNavigationRuleBase

▸ **SetNavigationRuleBase**(`Direction`, `Rule`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Direction` | [`EUINavigation`](../enums/ue_ue.EUINavigation.md) |
| `Rule` | [`EUINavigationRule`](../enums/ue_ue.EUINavigationRule.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetNavigationRuleBase](ue_ue.UserWidget.md#setnavigationrulebase)

___

### SetNavigationRuleCustom

▸ **SetNavigationRuleCustom**(`Direction`, `InCustomDelegate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Direction` | [`EUINavigation`](../enums/ue_ue.EUINavigation.md) |
| `InCustomDelegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Navigation`: [`EUINavigation`](../enums/ue_ue.EUINavigation.md)) => [`Widget`](ue_ue.Widget.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetNavigationRuleCustom](ue_ue.UserWidget.md#setnavigationrulecustom)

___

### SetNavigationRuleCustomBoundary

▸ **SetNavigationRuleCustomBoundary**(`Direction`, `InCustomDelegate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Direction` | [`EUINavigation`](../enums/ue_ue.EUINavigation.md) |
| `InCustomDelegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Navigation`: [`EUINavigation`](../enums/ue_ue.EUINavigation.md)) => [`Widget`](ue_ue.Widget.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetNavigationRuleCustomBoundary](ue_ue.UserWidget.md#setnavigationrulecustomboundary)

___

### SetNavigationRuleExplicit

▸ **SetNavigationRuleExplicit**(`Direction`, `InWidget`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Direction` | [`EUINavigation`](../enums/ue_ue.EUINavigation.md) |
| `InWidget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetNavigationRuleExplicit](ue_ue.UserWidget.md#setnavigationruleexplicit)

___

### SetNumLoopsToPlay

▸ **SetNumLoopsToPlay**(`InAnimation`, `NumLoopsToPlay`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |
| `NumLoopsToPlay` | `number` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetNumLoopsToPlay](ue_ue.UserWidget.md#setnumloopstoplay)

___

### SetOwningPlayer

▸ **SetOwningPlayer**(`LocalPlayerController`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LocalPlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetOwningPlayer](ue_ue.UserWidget.md#setowningplayer)

___

### SetPadding

▸ **SetPadding**(`InPadding`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPadding` | [`Margin`](ue_ue.Margin.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetPadding](ue_ue.UserWidget.md#setpadding)

___

### SetPlaybackSpeed

▸ **SetPlaybackSpeed**(`InAnimation`, `PlaybackSpeed?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |
| `PlaybackSpeed?` | `number` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetPlaybackSpeed](ue_ue.UserWidget.md#setplaybackspeed)

___

### SetPositionInViewport

▸ **SetPositionInViewport**(`Position`, `bRemoveDPIScale?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Position` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `bRemoveDPIScale?` | `boolean` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetPositionInViewport](ue_ue.UserWidget.md#setpositioninviewport)

___

### SetRenderOpacity

▸ **SetRenderOpacity**(`InOpacity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOpacity` | `number` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetRenderOpacity](ue_ue.UserWidget.md#setrenderopacity)

___

### SetRenderScale

▸ **SetRenderScale**(`Scale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetRenderScale](ue_ue.UserWidget.md#setrenderscale)

___

### SetRenderShear

▸ **SetRenderShear**(`Shear`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Shear` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetRenderShear](ue_ue.UserWidget.md#setrendershear)

___

### SetRenderTransform

▸ **SetRenderTransform**(`InTransform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTransform` | [`WidgetTransform`](ue_ue.WidgetTransform.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetRenderTransform](ue_ue.UserWidget.md#setrendertransform)

___

### SetRenderTransformAngle

▸ **SetRenderTransformAngle**(`Angle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetRenderTransformAngle](ue_ue.UserWidget.md#setrendertransformangle)

___

### SetRenderTransformPivot

▸ **SetRenderTransformPivot**(`Pivot`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Pivot` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetRenderTransformPivot](ue_ue.UserWidget.md#setrendertransformpivot)

___

### SetRenderTranslation

▸ **SetRenderTranslation**(`Translation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Translation` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetRenderTranslation](ue_ue.UserWidget.md#setrendertranslation)

___

### SetToolTip

▸ **SetToolTip**(`Widget`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Widget`](ue_ue.Widget.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetToolTip](ue_ue.UserWidget.md#settooltip)

___

### SetToolTipText

▸ **SetToolTipText**(`InToolTipText`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InToolTipText` | `string` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetToolTipText](ue_ue.UserWidget.md#settooltiptext)

___

### SetUserFocus

▸ **SetUserFocus**(`PlayerController`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetUserFocus](ue_ue.UserWidget.md#setuserfocus)

___

### SetVisibility

▸ **SetVisibility**(`InVisibility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVisibility` | [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[SetVisibility](ue_ue.UserWidget.md#setvisibility)

___

### StopAllAnimations

▸ **StopAllAnimations**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[StopAllAnimations](ue_ue.UserWidget.md#stopallanimations)

___

### StopAnimation

▸ **StopAnimation**(`InAnimation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[StopAnimation](ue_ue.UserWidget.md#stopanimation)

___

### StopAnimationsAndLatentActions

▸ **StopAnimationsAndLatentActions**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[StopAnimationsAndLatentActions](ue_ue.UserWidget.md#stopanimationsandlatentactions)

___

### StopListeningForAllInputActions

▸ **StopListeningForAllInputActions**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[StopListeningForAllInputActions](ue_ue.UserWidget.md#stoplisteningforallinputactions)

___

### StopListeningForInputAction

▸ **StopListeningForInputAction**(`ActionName`, `EventType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActionName` | `string` |
| `EventType` | [`EInputEvent`](../enums/ue_ue.EInputEvent.md) |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[StopListeningForInputAction](ue_ue.UserWidget.md#stoplisteningforinputaction)

___

### Tick

▸ **Tick**(`MyGeometry`, `InDeltaTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MyGeometry` | [`Geometry`](ue_ue.Geometry.md) |
| `InDeltaTime` | `number` |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[Tick](ue_ue.UserWidget.md#tick)

___

### UnbindAllFromAnimationFinished

▸ **UnbindAllFromAnimationFinished**(`Animation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[UnbindAllFromAnimationFinished](ue_ue.UserWidget.md#unbindallfromanimationfinished)

___

### UnbindAllFromAnimationStarted

▸ **UnbindAllFromAnimationStarted**(`Animation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[UnbindAllFromAnimationStarted](ue_ue.UserWidget.md#unbindallfromanimationstarted)

___

### UnbindFromAnimationFinished

▸ **UnbindFromAnimationFinished**(`Animation`, `Delegate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |
| `Delegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[UnbindFromAnimationFinished](ue_ue.UserWidget.md#unbindfromanimationfinished)

___

### UnbindFromAnimationStarted

▸ **UnbindFromAnimationStarted**(`Animation`, `Delegate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |
| `Delegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\> |

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[UnbindFromAnimationStarted](ue_ue.UserWidget.md#unbindfromanimationstarted)

___

### UnregisterInputComponent

▸ **UnregisterInputComponent**(): `void`

#### Returns

`void`

#### Inherited from

[UserWidget](ue_ue.UserWidget.md).[UnregisterInputComponent](ue_ue.UserWidget.md#unregisterinputcomponent)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorUtilityWidget`](ue_ue.EditorUtilityWidget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorUtilityWidget`](ue_ue.EditorUtilityWidget.md)

#### Overrides

[UserWidget](ue_ue.UserWidget.md).[Find](ue_ue.UserWidget.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorUtilityWidget`](ue_ue.EditorUtilityWidget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorUtilityWidget`](ue_ue.EditorUtilityWidget.md)

#### Overrides

[UserWidget](ue_ue.UserWidget.md).[Load](ue_ue.UserWidget.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[UserWidget](ue_ue.UserWidget.md).[StaticClass](ue_ue.UserWidget.md#staticclass)
