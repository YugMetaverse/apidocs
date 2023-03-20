[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UserWidget

# Class: UserWidget

[ue/ue](../modules/ue_ue.md).UserWidget

## Hierarchy

- [`Widget`](ue_ue.Widget.md)

  ↳ **`UserWidget`**

  ↳↳ [`LevelSequenceBurnIn`](ue_ue.LevelSequenceBurnIn.md)

  ↳↳ [`EditorUtilityWidget`](ue_ue.EditorUtilityWidget.md)

  ↳↳ [`ReactWidget`](ue_ue.ReactWidget.md)

  ↳↳ [`VREditorBaseUserWidget`](ue_ue.VREditorBaseUserWidget.md)

  ↳↳ [`TestWidgetBlueprint_C`](ue_ue_bp.Game.StarterContent.TestWidgetBlueprint.TestWidgetBlueprint_C.md)

## Table of contents

### Constructors

- [constructor](ue_ue.UserWidget.md#constructor)

### Properties

- [AccessibleBehavior](ue_ue.UserWidget.md#accessiblebehavior)
- [AccessibleSummaryBehavior](ue_ue.UserWidget.md#accessiblesummarybehavior)
- [AccessibleSummaryText](ue_ue.UserWidget.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](ue_ue.UserWidget.md#accessiblesummarytextdelegate)
- [AccessibleText](ue_ue.UserWidget.md#accessibletext)
- [AccessibleTextDelegate](ue_ue.UserWidget.md#accessibletextdelegate)
- [AccessibleWidgetData](ue_ue.UserWidget.md#accessiblewidgetdata)
- [ActiveSequencePlayers](ue_ue.UserWidget.md#activesequenceplayers)
- [AnimationCallbacks](ue_ue.UserWidget.md#animationcallbacks)
- [CategoryName](ue_ue.UserWidget.md#categoryname)
- [Clipping](ue_ue.UserWidget.md#clipping)
- [ColorAndOpacity](ue_ue.UserWidget.md#colorandopacity)
- [ColorAndOpacityDelegate](ue_ue.UserWidget.md#colorandopacitydelegate)
- [Cursor](ue_ue.UserWidget.md#cursor)
- [DesignSizeMode](ue_ue.UserWidget.md#designsizemode)
- [DesignTimeSize](ue_ue.UserWidget.md#designtimesize)
- [DesignerFlags](ue_ue.UserWidget.md#designerflags)
- [DisplayLabel](ue_ue.UserWidget.md#displaylabel)
- [FlowDirectionPreference](ue_ue.UserWidget.md#flowdirectionpreference)
- [ForegroundColor](ue_ue.UserWidget.md#foregroundcolor)
- [ForegroundColorDelegate](ue_ue.UserWidget.md#foregroundcolordelegate)
- [InputComponent](ue_ue.UserWidget.md#inputcomponent)
- [NamedSlotBindings](ue_ue.UserWidget.md#namedslotbindings)
- [NativeBindings](ue_ue.UserWidget.md#nativebindings)
- [Navigation](ue_ue.UserWidget.md#navigation)
- [Padding](ue_ue.UserWidget.md#padding)
- [PaletteCategory](ue_ue.UserWidget.md#palettecategory)
- [PreviewBackground](ue_ue.UserWidget.md#previewbackground)
- [Priority](ue_ue.UserWidget.md#priority)
- [RenderOpacity](ue_ue.UserWidget.md#renderopacity)
- [RenderTransform](ue_ue.UserWidget.md#rendertransform)
- [RenderTransformPivot](ue_ue.UserWidget.md#rendertransformpivot)
- [Slot](ue_ue.UserWidget.md#slot)
- [StoppedSequencePlayers](ue_ue.UserWidget.md#stoppedsequenceplayers)
- [TickFrequency](ue_ue.UserWidget.md#tickfrequency)
- [ToolTipText](ue_ue.UserWidget.md#tooltiptext)
- [ToolTipTextDelegate](ue_ue.UserWidget.md#tooltiptextdelegate)
- [ToolTipWidget](ue_ue.UserWidget.md#tooltipwidget)
- [ToolTipWidgetDelegate](ue_ue.UserWidget.md#tooltipwidgetdelegate)
- [Visibility](ue_ue.UserWidget.md#visibility)
- [VisibilityDelegate](ue_ue.UserWidget.md#visibilitydelegate)
- [WidgetTree](ue_ue.UserWidget.md#widgettree)
- [\_\_tid\_Object\_\_](ue_ue.UserWidget.md#__tid_object__)
- [\_\_tid\_UserWidget\_\_](ue_ue.UserWidget.md#__tid_userwidget__)
- [\_\_tid\_Visual\_\_](ue_ue.UserWidget.md#__tid_visual__)
- [\_\_tid\_Widget\_\_](ue_ue.UserWidget.md#__tid_widget__)
- [bCanChildrenBeAccessible](ue_ue.UserWidget.md#bcanchildrenbeaccessible)
- [bCookedWidgetTree](ue_ue.UserWidget.md#bcookedwidgettree)
- [bCreatedByConstructionScript](ue_ue.UserWidget.md#bcreatedbyconstructionscript)
- [bExpandedInDesigner](ue_ue.UserWidget.md#bexpandedindesigner)
- [bHasScriptImplementedPaint](ue_ue.UserWidget.md#bhasscriptimplementedpaint)
- [bHasScriptImplementedTick](ue_ue.UserWidget.md#bhasscriptimplementedtick)
- [bHiddenInDesigner](ue_ue.UserWidget.md#bhiddenindesigner)
- [bIsEnabled](ue_ue.UserWidget.md#bisenabled)
- [bIsEnabledDelegate](ue_ue.UserWidget.md#bisenableddelegate)
- [bIsFocusable](ue_ue.UserWidget.md#bisfocusable)
- [bIsVariable](ue_ue.UserWidget.md#bisvariable)
- [bIsVolatile](ue_ue.UserWidget.md#bisvolatile)
- [bLockedInDesigner](ue_ue.UserWidget.md#blockedindesigner)
- [bOverrideAccessibleDefaults](ue_ue.UserWidget.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](ue_ue.UserWidget.md#boverride_cursor)
- [bStopAction](ue_ue.UserWidget.md#bstopaction)
- [bSupportsKeyboardFocus](ue_ue.UserWidget.md#bsupportskeyboardfocus)

### Methods

- [AddToPlayerScreen](ue_ue.UserWidget.md#addtoplayerscreen)
- [AddToViewport](ue_ue.UserWidget.md#addtoviewport)
- [BindToAnimationEvent](ue_ue.UserWidget.md#bindtoanimationevent)
- [BindToAnimationFinished](ue_ue.UserWidget.md#bindtoanimationfinished)
- [BindToAnimationStarted](ue_ue.UserWidget.md#bindtoanimationstarted)
- [CancelLatentActions](ue_ue.UserWidget.md#cancellatentactions)
- [Construct](ue_ue.UserWidget.md#construct)
- [CreateDefaultSubobject](ue_ue.UserWidget.md#createdefaultsubobject)
- [Destruct](ue_ue.UserWidget.md#destruct)
- [ExecuteUbergraph](ue_ue.UserWidget.md#executeubergraph)
- [ForceLayoutPrepass](ue_ue.UserWidget.md#forcelayoutprepass)
- [ForceVolatile](ue_ue.UserWidget.md#forcevolatile)
- [GenerateWidgetForObject\_\_DelegateSignature](ue_ue.UserWidget.md#generatewidgetforobject__delegatesignature)
- [GenerateWidgetForString\_\_DelegateSignature](ue_ue.UserWidget.md#generatewidgetforstring__delegatesignature)
- [GetAlignmentInViewport](ue_ue.UserWidget.md#getalignmentinviewport)
- [GetAnchorsInViewport](ue_ue.UserWidget.md#getanchorsinviewport)
- [GetAnimationCurrentTime](ue_ue.UserWidget.md#getanimationcurrenttime)
- [GetBool\_\_DelegateSignature](ue_ue.UserWidget.md#getbool__delegatesignature)
- [GetCachedGeometry](ue_ue.UserWidget.md#getcachedgeometry)
- [GetCheckBoxState\_\_DelegateSignature](ue_ue.UserWidget.md#getcheckboxstate__delegatesignature)
- [GetClass](ue_ue.UserWidget.md#getclass)
- [GetClipping](ue_ue.UserWidget.md#getclipping)
- [GetDesiredSize](ue_ue.UserWidget.md#getdesiredsize)
- [GetFloat\_\_DelegateSignature](ue_ue.UserWidget.md#getfloat__delegatesignature)
- [GetGameInstance](ue_ue.UserWidget.md#getgameinstance)
- [GetInt32\_\_DelegateSignature](ue_ue.UserWidget.md#getint32__delegatesignature)
- [GetIsEnabled](ue_ue.UserWidget.md#getisenabled)
- [GetIsVisible](ue_ue.UserWidget.md#getisvisible)
- [GetLinearColor\_\_DelegateSignature](ue_ue.UserWidget.md#getlinearcolor__delegatesignature)
- [GetMouseCursor\_\_DelegateSignature](ue_ue.UserWidget.md#getmousecursor__delegatesignature)
- [GetName](ue_ue.UserWidget.md#getname)
- [GetOuter](ue_ue.UserWidget.md#getouter)
- [GetOwningLocalPlayer](ue_ue.UserWidget.md#getowninglocalplayer)
- [GetOwningPlayer](ue_ue.UserWidget.md#getowningplayer)
- [GetOwningPlayerPawn](ue_ue.UserWidget.md#getowningplayerpawn)
- [GetPaintSpaceGeometry](ue_ue.UserWidget.md#getpaintspacegeometry)
- [GetParent](ue_ue.UserWidget.md#getparent)
- [GetRenderOpacity](ue_ue.UserWidget.md#getrenderopacity)
- [GetRenderTransformAngle](ue_ue.UserWidget.md#getrendertransformangle)
- [GetSlateBrush\_\_DelegateSignature](ue_ue.UserWidget.md#getslatebrush__delegatesignature)
- [GetSlateColor\_\_DelegateSignature](ue_ue.UserWidget.md#getslatecolor__delegatesignature)
- [GetSlateVisibility\_\_DelegateSignature](ue_ue.UserWidget.md#getslatevisibility__delegatesignature)
- [GetText\_\_DelegateSignature](ue_ue.UserWidget.md#gettext__delegatesignature)
- [GetTickSpaceGeometry](ue_ue.UserWidget.md#gettickspacegeometry)
- [GetVisibility](ue_ue.UserWidget.md#getvisibility)
- [GetWidget\_\_DelegateSignature](ue_ue.UserWidget.md#getwidget__delegatesignature)
- [GetWorld](ue_ue.UserWidget.md#getworld)
- [HasAnyUserFocus](ue_ue.UserWidget.md#hasanyuserfocus)
- [HasFocusedDescendants](ue_ue.UserWidget.md#hasfocuseddescendants)
- [HasKeyboardFocus](ue_ue.UserWidget.md#haskeyboardfocus)
- [HasMouseCapture](ue_ue.UserWidget.md#hasmousecapture)
- [HasMouseCaptureByUser](ue_ue.UserWidget.md#hasmousecapturebyuser)
- [HasUserFocus](ue_ue.UserWidget.md#hasuserfocus)
- [HasUserFocusedDescendants](ue_ue.UserWidget.md#hasuserfocuseddescendants)
- [InvalidateLayoutAndVolatility](ue_ue.UserWidget.md#invalidatelayoutandvolatility)
- [IsAnimationPlaying](ue_ue.UserWidget.md#isanimationplaying)
- [IsAnimationPlayingForward](ue_ue.UserWidget.md#isanimationplayingforward)
- [IsAnyAnimationPlaying](ue_ue.UserWidget.md#isanyanimationplaying)
- [IsHovered](ue_ue.UserWidget.md#ishovered)
- [IsInViewport](ue_ue.UserWidget.md#isinviewport)
- [IsInteractable](ue_ue.UserWidget.md#isinteractable)
- [IsListeningForInputAction](ue_ue.UserWidget.md#islisteningforinputaction)
- [IsPlayingAnimation](ue_ue.UserWidget.md#isplayinganimation)
- [IsVisible](ue_ue.UserWidget.md#isvisible)
- [ListenForInputAction](ue_ue.UserWidget.md#listenforinputaction)
- [OnAddedToFocusPath](ue_ue.UserWidget.md#onaddedtofocuspath)
- [OnAnalogValueChanged](ue_ue.UserWidget.md#onanalogvaluechanged)
- [OnAnimationFinished](ue_ue.UserWidget.md#onanimationfinished)
- [OnAnimationStarted](ue_ue.UserWidget.md#onanimationstarted)
- [OnDragCancelled](ue_ue.UserWidget.md#ondragcancelled)
- [OnDragDetected](ue_ue.UserWidget.md#ondragdetected)
- [OnDragEnter](ue_ue.UserWidget.md#ondragenter)
- [OnDragLeave](ue_ue.UserWidget.md#ondragleave)
- [OnDragOver](ue_ue.UserWidget.md#ondragover)
- [OnDrop](ue_ue.UserWidget.md#ondrop)
- [OnFocusLost](ue_ue.UserWidget.md#onfocuslost)
- [OnFocusReceived](ue_ue.UserWidget.md#onfocusreceived)
- [OnInitialized](ue_ue.UserWidget.md#oninitialized)
- [OnKeyChar](ue_ue.UserWidget.md#onkeychar)
- [OnKeyDown](ue_ue.UserWidget.md#onkeydown)
- [OnKeyUp](ue_ue.UserWidget.md#onkeyup)
- [OnMotionDetected](ue_ue.UserWidget.md#onmotiondetected)
- [OnMouseButtonDoubleClick](ue_ue.UserWidget.md#onmousebuttondoubleclick)
- [OnMouseButtonDown](ue_ue.UserWidget.md#onmousebuttondown)
- [OnMouseButtonUp](ue_ue.UserWidget.md#onmousebuttonup)
- [OnMouseCaptureLost](ue_ue.UserWidget.md#onmousecapturelost)
- [OnMouseEnter](ue_ue.UserWidget.md#onmouseenter)
- [OnMouseLeave](ue_ue.UserWidget.md#onmouseleave)
- [OnMouseMove](ue_ue.UserWidget.md#onmousemove)
- [OnMouseWheel](ue_ue.UserWidget.md#onmousewheel)
- [OnPaint](ue_ue.UserWidget.md#onpaint)
- [OnPointerEvent\_\_DelegateSignature](ue_ue.UserWidget.md#onpointerevent__delegatesignature)
- [OnPreviewKeyDown](ue_ue.UserWidget.md#onpreviewkeydown)
- [OnPreviewMouseButtonDown](ue_ue.UserWidget.md#onpreviewmousebuttondown)
- [OnRemovedFromFocusPath](ue_ue.UserWidget.md#onremovedfromfocuspath)
- [OnReply\_\_DelegateSignature](ue_ue.UserWidget.md#onreply__delegatesignature)
- [OnTouchEnded](ue_ue.UserWidget.md#ontouchended)
- [OnTouchForceChanged](ue_ue.UserWidget.md#ontouchforcechanged)
- [OnTouchGesture](ue_ue.UserWidget.md#ontouchgesture)
- [OnTouchMoved](ue_ue.UserWidget.md#ontouchmoved)
- [OnTouchStarted](ue_ue.UserWidget.md#ontouchstarted)
- [PauseAnimation](ue_ue.UserWidget.md#pauseanimation)
- [PlayAnimation](ue_ue.UserWidget.md#playanimation)
- [PlayAnimationForward](ue_ue.UserWidget.md#playanimationforward)
- [PlayAnimationReverse](ue_ue.UserWidget.md#playanimationreverse)
- [PlayAnimationTimeRange](ue_ue.UserWidget.md#playanimationtimerange)
- [PlaySound](ue_ue.UserWidget.md#playsound)
- [PreConstruct](ue_ue.UserWidget.md#preconstruct)
- [RegisterInputComponent](ue_ue.UserWidget.md#registerinputcomponent)
- [RemoveFromParent](ue_ue.UserWidget.md#removefromparent)
- [RemoveFromViewport](ue_ue.UserWidget.md#removefromviewport)
- [ResetCursor](ue_ue.UserWidget.md#resetcursor)
- [ReverseAnimation](ue_ue.UserWidget.md#reverseanimation)
- [SetAlignmentInViewport](ue_ue.UserWidget.md#setalignmentinviewport)
- [SetAllNavigationRules](ue_ue.UserWidget.md#setallnavigationrules)
- [SetAnchorsInViewport](ue_ue.UserWidget.md#setanchorsinviewport)
- [SetClipping](ue_ue.UserWidget.md#setclipping)
- [SetColorAndOpacity](ue_ue.UserWidget.md#setcolorandopacity)
- [SetCursor](ue_ue.UserWidget.md#setcursor)
- [SetDesiredSizeInViewport](ue_ue.UserWidget.md#setdesiredsizeinviewport)
- [SetFocus](ue_ue.UserWidget.md#setfocus)
- [SetForegroundColor](ue_ue.UserWidget.md#setforegroundcolor)
- [SetInputActionBlocking](ue_ue.UserWidget.md#setinputactionblocking)
- [SetInputActionPriority](ue_ue.UserWidget.md#setinputactionpriority)
- [SetIsEnabled](ue_ue.UserWidget.md#setisenabled)
- [SetKeyboardFocus](ue_ue.UserWidget.md#setkeyboardfocus)
- [SetNavigationRule](ue_ue.UserWidget.md#setnavigationrule)
- [SetNavigationRuleBase](ue_ue.UserWidget.md#setnavigationrulebase)
- [SetNavigationRuleCustom](ue_ue.UserWidget.md#setnavigationrulecustom)
- [SetNavigationRuleCustomBoundary](ue_ue.UserWidget.md#setnavigationrulecustomboundary)
- [SetNavigationRuleExplicit](ue_ue.UserWidget.md#setnavigationruleexplicit)
- [SetNumLoopsToPlay](ue_ue.UserWidget.md#setnumloopstoplay)
- [SetOwningPlayer](ue_ue.UserWidget.md#setowningplayer)
- [SetPadding](ue_ue.UserWidget.md#setpadding)
- [SetPlaybackSpeed](ue_ue.UserWidget.md#setplaybackspeed)
- [SetPositionInViewport](ue_ue.UserWidget.md#setpositioninviewport)
- [SetRenderOpacity](ue_ue.UserWidget.md#setrenderopacity)
- [SetRenderScale](ue_ue.UserWidget.md#setrenderscale)
- [SetRenderShear](ue_ue.UserWidget.md#setrendershear)
- [SetRenderTransform](ue_ue.UserWidget.md#setrendertransform)
- [SetRenderTransformAngle](ue_ue.UserWidget.md#setrendertransformangle)
- [SetRenderTransformPivot](ue_ue.UserWidget.md#setrendertransformpivot)
- [SetRenderTranslation](ue_ue.UserWidget.md#setrendertranslation)
- [SetToolTip](ue_ue.UserWidget.md#settooltip)
- [SetToolTipText](ue_ue.UserWidget.md#settooltiptext)
- [SetUserFocus](ue_ue.UserWidget.md#setuserfocus)
- [SetVisibility](ue_ue.UserWidget.md#setvisibility)
- [StopAllAnimations](ue_ue.UserWidget.md#stopallanimations)
- [StopAnimation](ue_ue.UserWidget.md#stopanimation)
- [StopAnimationsAndLatentActions](ue_ue.UserWidget.md#stopanimationsandlatentactions)
- [StopListeningForAllInputActions](ue_ue.UserWidget.md#stoplisteningforallinputactions)
- [StopListeningForInputAction](ue_ue.UserWidget.md#stoplisteningforinputaction)
- [Tick](ue_ue.UserWidget.md#tick)
- [UnbindAllFromAnimationFinished](ue_ue.UserWidget.md#unbindallfromanimationfinished)
- [UnbindAllFromAnimationStarted](ue_ue.UserWidget.md#unbindallfromanimationstarted)
- [UnbindFromAnimationFinished](ue_ue.UserWidget.md#unbindfromanimationfinished)
- [UnbindFromAnimationStarted](ue_ue.UserWidget.md#unbindfromanimationstarted)
- [UnregisterInputComponent](ue_ue.UserWidget.md#unregisterinputcomponent)
- [Find](ue_ue.UserWidget.md#find)
- [Load](ue_ue.UserWidget.md#load)
- [StaticClass](ue_ue.UserWidget.md#staticclass)

## Constructors

### constructor

• **new UserWidget**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Widget](ue_ue.Widget.md).[constructor](ue_ue.Widget.md#constructor)

## Properties

### AccessibleBehavior

• **AccessibleBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleBehavior](ue_ue.Widget.md#accessiblebehavior)

___

### AccessibleSummaryBehavior

• **AccessibleSummaryBehavior**: [`ESlateAccessibleBehavior`](../enums/ue_ue.ESlateAccessibleBehavior.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleSummaryBehavior](ue_ue.Widget.md#accessiblesummarybehavior)

___

### AccessibleSummaryText

• **AccessibleSummaryText**: `string`

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleSummaryText](ue_ue.Widget.md#accessiblesummarytext)

___

### AccessibleSummaryTextDelegate

• **AccessibleSummaryTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleSummaryTextDelegate](ue_ue.Widget.md#accessiblesummarytextdelegate)

___

### AccessibleText

• **AccessibleText**: `string`

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleText](ue_ue.Widget.md#accessibletext)

___

### AccessibleTextDelegate

• **AccessibleTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleTextDelegate](ue_ue.Widget.md#accessibletextdelegate)

___

### AccessibleWidgetData

• **AccessibleWidgetData**: [`SlateAccessibleWidgetData`](ue_ue.SlateAccessibleWidgetData.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[AccessibleWidgetData](ue_ue.Widget.md#accessiblewidgetdata)

___

### ActiveSequencePlayers

• **ActiveSequencePlayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)\>

___

### AnimationCallbacks

• **AnimationCallbacks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationEventBinding`](ue_ue.AnimationEventBinding.md)\>

___

### CategoryName

• **CategoryName**: `string`

#### Inherited from

[Widget](ue_ue.Widget.md).[CategoryName](ue_ue.Widget.md#categoryname)

___

### Clipping

• **Clipping**: [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[Clipping](ue_ue.Widget.md#clipping)

___

### ColorAndOpacity

• **ColorAndOpacity**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### ColorAndOpacityDelegate

• **ColorAndOpacityDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`LinearColor`](ue_ue_s.LinearColor.md)\>

___

### Cursor

• **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[Cursor](ue_ue.Widget.md#cursor)

___

### DesignSizeMode

• **DesignSizeMode**: [`EDesignPreviewSizeMode`](../enums/ue_ue.EDesignPreviewSizeMode.md)

___

### DesignTimeSize

• **DesignTimeSize**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### DesignerFlags

• **DesignerFlags**: `number`

#### Inherited from

[Widget](ue_ue.Widget.md).[DesignerFlags](ue_ue.Widget.md#designerflags)

___

### DisplayLabel

• **DisplayLabel**: `string`

#### Inherited from

[Widget](ue_ue.Widget.md).[DisplayLabel](ue_ue.Widget.md#displaylabel)

___

### FlowDirectionPreference

• **FlowDirectionPreference**: [`EFlowDirectionPreference`](../enums/ue_ue.EFlowDirectionPreference.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[FlowDirectionPreference](ue_ue.Widget.md#flowdirectionpreference)

___

### ForegroundColor

• **ForegroundColor**: [`SlateColor`](ue_ue.SlateColor.md)

___

### ForegroundColorDelegate

• **ForegroundColorDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`SlateColor`](ue_ue.SlateColor.md)\>

___

### InputComponent

• **InputComponent**: [`InputComponent`](ue_ue.InputComponent.md)

___

### NamedSlotBindings

• **NamedSlotBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedSlotBinding`](ue_ue.NamedSlotBinding.md)\>

___

### NativeBindings

• **NativeBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyBinding`](ue_ue.PropertyBinding.md)\>

#### Inherited from

[Widget](ue_ue.Widget.md).[NativeBindings](ue_ue.Widget.md#nativebindings)

___

### Navigation

• **Navigation**: [`WidgetNavigation`](ue_ue.WidgetNavigation.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[Navigation](ue_ue.Widget.md#navigation)

___

### Padding

• **Padding**: [`Margin`](ue_ue.Margin.md)

___

### PaletteCategory

• **PaletteCategory**: `string`

___

### PreviewBackground

• **PreviewBackground**: [`Texture2D`](ue_ue.Texture2D.md)

___

### Priority

• **Priority**: `number`

___

### RenderOpacity

• **RenderOpacity**: `number`

#### Inherited from

[Widget](ue_ue.Widget.md).[RenderOpacity](ue_ue.Widget.md#renderopacity)

___

### RenderTransform

• **RenderTransform**: [`WidgetTransform`](ue_ue.WidgetTransform.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[RenderTransform](ue_ue.Widget.md#rendertransform)

___

### RenderTransformPivot

• **RenderTransformPivot**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[RenderTransformPivot](ue_ue.Widget.md#rendertransformpivot)

___

### Slot

• **Slot**: [`PanelSlot`](ue_ue.PanelSlot.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[Slot](ue_ue.Widget.md#slot)

___

### StoppedSequencePlayers

• **StoppedSequencePlayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)\>

___

### TickFrequency

• **TickFrequency**: [`EWidgetTickFrequency`](../enums/ue_ue.EWidgetTickFrequency.md)

___

### ToolTipText

• **ToolTipText**: `string`

#### Inherited from

[Widget](ue_ue.Widget.md).[ToolTipText](ue_ue.Widget.md#tooltiptext)

___

### ToolTipTextDelegate

• **ToolTipTextDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `string`\>

#### Inherited from

[Widget](ue_ue.Widget.md).[ToolTipTextDelegate](ue_ue.Widget.md#tooltiptextdelegate)

___

### ToolTipWidget

• **ToolTipWidget**: [`Widget`](ue_ue.Widget.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[ToolTipWidget](ue_ue.Widget.md#tooltipwidget)

___

### ToolTipWidgetDelegate

• **ToolTipWidgetDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`Widget`](ue_ue.Widget.md)\>

#### Inherited from

[Widget](ue_ue.Widget.md).[ToolTipWidgetDelegate](ue_ue.Widget.md#tooltipwidgetdelegate)

___

### Visibility

• **Visibility**: [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[Visibility](ue_ue.Widget.md#visibility)

___

### VisibilityDelegate

• **VisibilityDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)\>

#### Inherited from

[Widget](ue_ue.Widget.md).[VisibilityDelegate](ue_ue.Widget.md#visibilitydelegate)

___

### WidgetTree

• **WidgetTree**: [`WidgetTree`](ue_ue.WidgetTree.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[__tid_Object__](ue_ue.Widget.md#__tid_object__)

___

### \_\_tid\_UserWidget\_\_

• **\_\_tid\_UserWidget\_\_**: `boolean`

___

### \_\_tid\_Visual\_\_

• **\_\_tid\_Visual\_\_**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[__tid_Visual__](ue_ue.Widget.md#__tid_visual__)

___

### \_\_tid\_Widget\_\_

• **\_\_tid\_Widget\_\_**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[__tid_Widget__](ue_ue.Widget.md#__tid_widget__)

___

### bCanChildrenBeAccessible

• **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bCanChildrenBeAccessible](ue_ue.Widget.md#bcanchildrenbeaccessible)

___

### bCookedWidgetTree

• **bCookedWidgetTree**: `boolean`

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bCreatedByConstructionScript](ue_ue.Widget.md#bcreatedbyconstructionscript)

___

### bExpandedInDesigner

• **bExpandedInDesigner**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bExpandedInDesigner](ue_ue.Widget.md#bexpandedindesigner)

___

### bHasScriptImplementedPaint

• **bHasScriptImplementedPaint**: `boolean`

___

### bHasScriptImplementedTick

• **bHasScriptImplementedTick**: `boolean`

___

### bHiddenInDesigner

• **bHiddenInDesigner**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bHiddenInDesigner](ue_ue.Widget.md#bhiddenindesigner)

___

### bIsEnabled

• **bIsEnabled**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bIsEnabled](ue_ue.Widget.md#bisenabled)

___

### bIsEnabledDelegate

• **bIsEnabledDelegate**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `boolean`\>

#### Inherited from

[Widget](ue_ue.Widget.md).[bIsEnabledDelegate](ue_ue.Widget.md#bisenableddelegate)

___

### bIsFocusable

• **bIsFocusable**: `boolean`

___

### bIsVariable

• **bIsVariable**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bIsVariable](ue_ue.Widget.md#bisvariable)

___

### bIsVolatile

• **bIsVolatile**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bIsVolatile](ue_ue.Widget.md#bisvolatile)

___

### bLockedInDesigner

• **bLockedInDesigner**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bLockedInDesigner](ue_ue.Widget.md#blockedindesigner)

___

### bOverrideAccessibleDefaults

• **bOverrideAccessibleDefaults**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bOverrideAccessibleDefaults](ue_ue.Widget.md#boverrideaccessibledefaults)

___

### bOverride\_Cursor

• **bOverride\_Cursor**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bOverride_Cursor](ue_ue.Widget.md#boverride_cursor)

___

### bStopAction

• **bStopAction**: `boolean`

___

### bSupportsKeyboardFocus

• **bSupportsKeyboardFocus**: `boolean`

## Methods

### AddToPlayerScreen

▸ **AddToPlayerScreen**(`ZOrder?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ZOrder?` | `number` |

#### Returns

`boolean`

___

### AddToViewport

▸ **AddToViewport**(`ZOrder?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ZOrder?` | `number` |

#### Returns

`void`

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

___

### CancelLatentActions

▸ **CancelLatentActions**(): `void`

#### Returns

`void`

___

### Construct

▸ **Construct**(): `void`

#### Returns

`void`

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

[Widget](ue_ue.Widget.md).[CreateDefaultSubobject](ue_ue.Widget.md#createdefaultsubobject)

___

### Destruct

▸ **Destruct**(): `void`

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

[Widget](ue_ue.Widget.md).[ExecuteUbergraph](ue_ue.Widget.md#executeubergraph)

___

### ForceLayoutPrepass

▸ **ForceLayoutPrepass**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[ForceLayoutPrepass](ue_ue.Widget.md#forcelayoutprepass)

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

[Widget](ue_ue.Widget.md).[ForceVolatile](ue_ue.Widget.md#forcevolatile)

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

[Widget](ue_ue.Widget.md).[GenerateWidgetForObject__DelegateSignature](ue_ue.Widget.md#generatewidgetforobject__delegatesignature)

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

[Widget](ue_ue.Widget.md).[GenerateWidgetForString__DelegateSignature](ue_ue.Widget.md#generatewidgetforstring__delegatesignature)

___

### GetAlignmentInViewport

▸ **GetAlignmentInViewport**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### GetAnchorsInViewport

▸ **GetAnchorsInViewport**(): [`Anchors`](ue_ue.Anchors.md)

#### Returns

[`Anchors`](ue_ue.Anchors.md)

___

### GetAnimationCurrentTime

▸ **GetAnimationCurrentTime**(`InAnimation`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`number`

___

### GetBool\_\_DelegateSignature

▸ **GetBool__DelegateSignature**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetBool__DelegateSignature](ue_ue.Widget.md#getbool__delegatesignature)

___

### GetCachedGeometry

▸ **GetCachedGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetCachedGeometry](ue_ue.Widget.md#getcachedgeometry)

___

### GetCheckBoxState\_\_DelegateSignature

▸ **GetCheckBoxState__DelegateSignature**(): [`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Returns

[`ECheckBoxState`](../enums/ue_ue.ECheckBoxState.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetCheckBoxState__DelegateSignature](ue_ue.Widget.md#getcheckboxstate__delegatesignature)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetClass](ue_ue.Widget.md#getclass)

___

### GetClipping

▸ **GetClipping**(): [`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Returns

[`EWidgetClipping`](../enums/ue_ue.EWidgetClipping.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetClipping](ue_ue.Widget.md#getclipping)

___

### GetDesiredSize

▸ **GetDesiredSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetDesiredSize](ue_ue.Widget.md#getdesiredsize)

___

### GetFloat\_\_DelegateSignature

▸ **GetFloat__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetFloat__DelegateSignature](ue_ue.Widget.md#getfloat__delegatesignature)

___

### GetGameInstance

▸ **GetGameInstance**(): [`GameInstance`](ue_ue.GameInstance.md)

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetGameInstance](ue_ue.Widget.md#getgameinstance)

___

### GetInt32\_\_DelegateSignature

▸ **GetInt32__DelegateSignature**(): `number`

#### Returns

`number`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetInt32__DelegateSignature](ue_ue.Widget.md#getint32__delegatesignature)

___

### GetIsEnabled

▸ **GetIsEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetIsEnabled](ue_ue.Widget.md#getisenabled)

___

### GetIsVisible

▸ **GetIsVisible**(): `boolean`

#### Returns

`boolean`

___

### GetLinearColor\_\_DelegateSignature

▸ **GetLinearColor__DelegateSignature**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetLinearColor__DelegateSignature](ue_ue.Widget.md#getlinearcolor__delegatesignature)

___

### GetMouseCursor\_\_DelegateSignature

▸ **GetMouseCursor__DelegateSignature**(): [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Returns

[`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetMouseCursor__DelegateSignature](ue_ue.Widget.md#getmousecursor__delegatesignature)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetName](ue_ue.Widget.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetOuter](ue_ue.Widget.md#getouter)

___

### GetOwningLocalPlayer

▸ **GetOwningLocalPlayer**(): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetOwningLocalPlayer](ue_ue.Widget.md#getowninglocalplayer)

___

### GetOwningPlayer

▸ **GetOwningPlayer**(): [`PlayerController`](ue_ue.PlayerController.md)

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetOwningPlayer](ue_ue.Widget.md#getowningplayer)

___

### GetOwningPlayerPawn

▸ **GetOwningPlayerPawn**(): [`Pawn`](ue_ue.Pawn.md)

#### Returns

[`Pawn`](ue_ue.Pawn.md)

___

### GetPaintSpaceGeometry

▸ **GetPaintSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetPaintSpaceGeometry](ue_ue.Widget.md#getpaintspacegeometry)

___

### GetParent

▸ **GetParent**(): [`PanelWidget`](ue_ue.PanelWidget.md)

#### Returns

[`PanelWidget`](ue_ue.PanelWidget.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetParent](ue_ue.Widget.md#getparent)

___

### GetRenderOpacity

▸ **GetRenderOpacity**(): `number`

#### Returns

`number`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetRenderOpacity](ue_ue.Widget.md#getrenderopacity)

___

### GetRenderTransformAngle

▸ **GetRenderTransformAngle**(): `number`

#### Returns

`number`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetRenderTransformAngle](ue_ue.Widget.md#getrendertransformangle)

___

### GetSlateBrush\_\_DelegateSignature

▸ **GetSlateBrush__DelegateSignature**(): [`SlateBrush`](ue_ue.SlateBrush.md)

#### Returns

[`SlateBrush`](ue_ue.SlateBrush.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetSlateBrush__DelegateSignature](ue_ue.Widget.md#getslatebrush__delegatesignature)

___

### GetSlateColor\_\_DelegateSignature

▸ **GetSlateColor__DelegateSignature**(): [`SlateColor`](ue_ue.SlateColor.md)

#### Returns

[`SlateColor`](ue_ue.SlateColor.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetSlateColor__DelegateSignature](ue_ue.Widget.md#getslatecolor__delegatesignature)

___

### GetSlateVisibility\_\_DelegateSignature

▸ **GetSlateVisibility__DelegateSignature**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetSlateVisibility__DelegateSignature](ue_ue.Widget.md#getslatevisibility__delegatesignature)

___

### GetText\_\_DelegateSignature

▸ **GetText__DelegateSignature**(): `string`

#### Returns

`string`

#### Inherited from

[Widget](ue_ue.Widget.md).[GetText__DelegateSignature](ue_ue.Widget.md#gettext__delegatesignature)

___

### GetTickSpaceGeometry

▸ **GetTickSpaceGeometry**(): [`Geometry`](ue_ue.Geometry.md)

#### Returns

[`Geometry`](ue_ue.Geometry.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetTickSpaceGeometry](ue_ue.Widget.md#gettickspacegeometry)

___

### GetVisibility

▸ **GetVisibility**(): [`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Returns

[`ESlateVisibility`](../enums/ue_ue.ESlateVisibility.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetVisibility](ue_ue.Widget.md#getvisibility)

___

### GetWidget\_\_DelegateSignature

▸ **GetWidget__DelegateSignature**(): [`Widget`](ue_ue.Widget.md)

#### Returns

[`Widget`](ue_ue.Widget.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetWidget__DelegateSignature](ue_ue.Widget.md#getwidget__delegatesignature)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[GetWorld](ue_ue.Widget.md#getworld)

___

### HasAnyUserFocus

▸ **HasAnyUserFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[HasAnyUserFocus](ue_ue.Widget.md#hasanyuserfocus)

___

### HasFocusedDescendants

▸ **HasFocusedDescendants**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[HasFocusedDescendants](ue_ue.Widget.md#hasfocuseddescendants)

___

### HasKeyboardFocus

▸ **HasKeyboardFocus**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[HasKeyboardFocus](ue_ue.Widget.md#haskeyboardfocus)

___

### HasMouseCapture

▸ **HasMouseCapture**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[HasMouseCapture](ue_ue.Widget.md#hasmousecapture)

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

[Widget](ue_ue.Widget.md).[HasMouseCaptureByUser](ue_ue.Widget.md#hasmousecapturebyuser)

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

[Widget](ue_ue.Widget.md).[HasUserFocus](ue_ue.Widget.md#hasuserfocus)

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

[Widget](ue_ue.Widget.md).[HasUserFocusedDescendants](ue_ue.Widget.md#hasuserfocuseddescendants)

___

### InvalidateLayoutAndVolatility

▸ **InvalidateLayoutAndVolatility**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[InvalidateLayoutAndVolatility](ue_ue.Widget.md#invalidatelayoutandvolatility)

___

### IsAnimationPlaying

▸ **IsAnimationPlaying**(`InAnimation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`boolean`

___

### IsAnimationPlayingForward

▸ **IsAnimationPlayingForward**(`InAnimation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`boolean`

___

### IsAnyAnimationPlaying

▸ **IsAnyAnimationPlaying**(): `boolean`

#### Returns

`boolean`

___

### IsHovered

▸ **IsHovered**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[IsHovered](ue_ue.Widget.md#ishovered)

___

### IsInViewport

▸ **IsInViewport**(): `boolean`

#### Returns

`boolean`

___

### IsInteractable

▸ **IsInteractable**(): `boolean`

#### Returns

`boolean`

___

### IsListeningForInputAction

▸ **IsListeningForInputAction**(`ActionName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActionName` | `string` |

#### Returns

`boolean`

___

### IsPlayingAnimation

▸ **IsPlayingAnimation**(): `boolean`

#### Returns

`boolean`

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[IsVisible](ue_ue.Widget.md#isvisible)

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

___

### OnAddedToFocusPath

▸ **OnAddedToFocusPath**(`InFocusEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFocusEvent` | [`FocusEvent`](ue_ue.FocusEvent.md) |

#### Returns

`void`

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

___

### OnAnimationFinished

▸ **OnAnimationFinished**(`Animation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`void`

___

### OnAnimationStarted

▸ **OnAnimationStarted**(`Animation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`void`

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

___

### OnFocusLost

▸ **OnFocusLost**(`InFocusEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFocusEvent` | [`FocusEvent`](ue_ue.FocusEvent.md) |

#### Returns

`void`

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

___

### OnInitialized

▸ **OnInitialized**(): `void`

#### Returns

`void`

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

___

### OnMouseCaptureLost

▸ **OnMouseCaptureLost**(): `void`

#### Returns

`void`

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

___

### OnMouseLeave

▸ **OnMouseLeave**(`MouseEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MouseEvent` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`void`

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

___

### OnPaint

▸ **OnPaint**(`Context`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Context` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PaintContext`](ue_ue.PaintContext.md)\> |

#### Returns

`void`

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

[Widget](ue_ue.Widget.md).[OnPointerEvent__DelegateSignature](ue_ue.Widget.md#onpointerevent__delegatesignature)

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

___

### OnRemovedFromFocusPath

▸ **OnRemovedFromFocusPath**(`InFocusEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFocusEvent` | [`FocusEvent`](ue_ue.FocusEvent.md) |

#### Returns

`void`

___

### OnReply\_\_DelegateSignature

▸ **OnReply__DelegateSignature**(): [`EventReply`](ue_ue.EventReply.md)

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[OnReply__DelegateSignature](ue_ue.Widget.md#onreply__delegatesignature)

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

___

### PauseAnimation

▸ **PauseAnimation**(`InAnimation`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`number`

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

___

### PlaySound

▸ **PlaySound**(`SoundToPlay`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SoundToPlay` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundBase`](ue_ue.SoundBase.md)\> |

#### Returns

`void`

___

### PreConstruct

▸ **PreConstruct**(`IsDesignTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `IsDesignTime` | `boolean` |

#### Returns

`void`

___

### RegisterInputComponent

▸ **RegisterInputComponent**(): `void`

#### Returns

`void`

___

### RemoveFromParent

▸ **RemoveFromParent**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[RemoveFromParent](ue_ue.Widget.md#removefromparent)

___

### RemoveFromViewport

▸ **RemoveFromViewport**(): `void`

#### Returns

`void`

___

### ResetCursor

▸ **ResetCursor**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[ResetCursor](ue_ue.Widget.md#resetcursor)

___

### ReverseAnimation

▸ **ReverseAnimation**(`InAnimation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

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

[Widget](ue_ue.Widget.md).[SetAllNavigationRules](ue_ue.Widget.md#setallnavigationrules)

___

### SetAnchorsInViewport

▸ **SetAnchorsInViewport**(`Anchors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Anchors` | [`Anchors`](ue_ue.Anchors.md) |

#### Returns

`void`

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

[Widget](ue_ue.Widget.md).[SetClipping](ue_ue.Widget.md#setclipping)

___

### SetColorAndOpacity

▸ **SetColorAndOpacity**(`InColorAndOpacity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColorAndOpacity` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

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

[Widget](ue_ue.Widget.md).[SetCursor](ue_ue.Widget.md#setcursor)

___

### SetDesiredSizeInViewport

▸ **SetDesiredSizeInViewport**(`Size`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Size` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

___

### SetFocus

▸ **SetFocus**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[SetFocus](ue_ue.Widget.md#setfocus)

___

### SetForegroundColor

▸ **SetForegroundColor**(`InForegroundColor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InForegroundColor` | [`SlateColor`](ue_ue.SlateColor.md) |

#### Returns

`void`

___

### SetInputActionBlocking

▸ **SetInputActionBlocking**(`bShouldBlock`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bShouldBlock` | `boolean` |

#### Returns

`void`

___

### SetInputActionPriority

▸ **SetInputActionPriority**(`NewPriority`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPriority` | `number` |

#### Returns

`void`

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

[Widget](ue_ue.Widget.md).[SetIsEnabled](ue_ue.Widget.md#setisenabled)

___

### SetKeyboardFocus

▸ **SetKeyboardFocus**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[SetKeyboardFocus](ue_ue.Widget.md#setkeyboardfocus)

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

[Widget](ue_ue.Widget.md).[SetNavigationRule](ue_ue.Widget.md#setnavigationrule)

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

[Widget](ue_ue.Widget.md).[SetNavigationRuleBase](ue_ue.Widget.md#setnavigationrulebase)

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

[Widget](ue_ue.Widget.md).[SetNavigationRuleCustom](ue_ue.Widget.md#setnavigationrulecustom)

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

[Widget](ue_ue.Widget.md).[SetNavigationRuleCustomBoundary](ue_ue.Widget.md#setnavigationrulecustomboundary)

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

[Widget](ue_ue.Widget.md).[SetNavigationRuleExplicit](ue_ue.Widget.md#setnavigationruleexplicit)

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

___

### SetOwningPlayer

▸ **SetOwningPlayer**(`LocalPlayerController`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LocalPlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`void`

___

### SetPadding

▸ **SetPadding**(`InPadding`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPadding` | [`Margin`](ue_ue.Margin.md) |

#### Returns

`void`

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

[Widget](ue_ue.Widget.md).[SetRenderOpacity](ue_ue.Widget.md#setrenderopacity)

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

[Widget](ue_ue.Widget.md).[SetRenderScale](ue_ue.Widget.md#setrenderscale)

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

[Widget](ue_ue.Widget.md).[SetRenderShear](ue_ue.Widget.md#setrendershear)

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

[Widget](ue_ue.Widget.md).[SetRenderTransform](ue_ue.Widget.md#setrendertransform)

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

[Widget](ue_ue.Widget.md).[SetRenderTransformAngle](ue_ue.Widget.md#setrendertransformangle)

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

[Widget](ue_ue.Widget.md).[SetRenderTransformPivot](ue_ue.Widget.md#setrendertransformpivot)

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

[Widget](ue_ue.Widget.md).[SetRenderTranslation](ue_ue.Widget.md#setrendertranslation)

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

[Widget](ue_ue.Widget.md).[SetToolTip](ue_ue.Widget.md#settooltip)

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

[Widget](ue_ue.Widget.md).[SetToolTipText](ue_ue.Widget.md#settooltiptext)

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

[Widget](ue_ue.Widget.md).[SetUserFocus](ue_ue.Widget.md#setuserfocus)

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

[Widget](ue_ue.Widget.md).[SetVisibility](ue_ue.Widget.md#setvisibility)

___

### StopAllAnimations

▸ **StopAllAnimations**(): `void`

#### Returns

`void`

___

### StopAnimation

▸ **StopAnimation**(`InAnimation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`void`

___

### StopAnimationsAndLatentActions

▸ **StopAnimationsAndLatentActions**(): `void`

#### Returns

`void`

___

### StopListeningForAllInputActions

▸ **StopListeningForAllInputActions**(): `void`

#### Returns

`void`

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

___

### UnbindAllFromAnimationFinished

▸ **UnbindAllFromAnimationFinished**(`Animation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`void`

___

### UnbindAllFromAnimationStarted

▸ **UnbindAllFromAnimationStarted**(`Animation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |

#### Returns

`void`

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

___

### UnregisterInputComponent

▸ **UnregisterInputComponent**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UserWidget`](ue_ue.UserWidget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UserWidget`](ue_ue.UserWidget.md)

#### Overrides

[Widget](ue_ue.Widget.md).[Find](ue_ue.Widget.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`UserWidget`](ue_ue.UserWidget.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UserWidget`](ue_ue.UserWidget.md)

#### Overrides

[Widget](ue_ue.Widget.md).[Load](ue_ue.Widget.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Widget](ue_ue.Widget.md).[StaticClass](ue_ue.Widget.md#staticclass)
