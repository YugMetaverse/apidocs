[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PropertyViewBase

# Class: PropertyViewBase

[ue/ue](../modules/ue_ue.md).PropertyViewBase

## Hierarchy

- [`Widget`](ue_ue.Widget.md)

  ↳ **`PropertyViewBase`**

  ↳↳ [`DetailsView`](ue_ue.DetailsView.md)

  ↳↳ [`SinglePropertyView`](ue_ue.SinglePropertyView.md)

## Table of contents

### Constructors

- [constructor](ue_ue.PropertyViewBase.md#constructor)

### Properties

- [AccessibleBehavior](ue_ue.PropertyViewBase.md#accessiblebehavior)
- [AccessibleSummaryBehavior](ue_ue.PropertyViewBase.md#accessiblesummarybehavior)
- [AccessibleSummaryText](ue_ue.PropertyViewBase.md#accessiblesummarytext)
- [AccessibleSummaryTextDelegate](ue_ue.PropertyViewBase.md#accessiblesummarytextdelegate)
- [AccessibleText](ue_ue.PropertyViewBase.md#accessibletext)
- [AccessibleTextDelegate](ue_ue.PropertyViewBase.md#accessibletextdelegate)
- [AccessibleWidgetData](ue_ue.PropertyViewBase.md#accessiblewidgetdata)
- [CategoryName](ue_ue.PropertyViewBase.md#categoryname)
- [Clipping](ue_ue.PropertyViewBase.md#clipping)
- [Cursor](ue_ue.PropertyViewBase.md#cursor)
- [DesignerFlags](ue_ue.PropertyViewBase.md#designerflags)
- [DisplayLabel](ue_ue.PropertyViewBase.md#displaylabel)
- [FlowDirectionPreference](ue_ue.PropertyViewBase.md#flowdirectionpreference)
- [LazyObject](ue_ue.PropertyViewBase.md#lazyobject)
- [NativeBindings](ue_ue.PropertyViewBase.md#nativebindings)
- [Navigation](ue_ue.PropertyViewBase.md#navigation)
- [OnPropertyChanged](ue_ue.PropertyViewBase.md#onpropertychanged)
- [RenderOpacity](ue_ue.PropertyViewBase.md#renderopacity)
- [RenderTransform](ue_ue.PropertyViewBase.md#rendertransform)
- [RenderTransformPivot](ue_ue.PropertyViewBase.md#rendertransformpivot)
- [Slot](ue_ue.PropertyViewBase.md#slot)
- [SoftObjectPath](ue_ue.PropertyViewBase.md#softobjectpath)
- [ToolTipText](ue_ue.PropertyViewBase.md#tooltiptext)
- [ToolTipTextDelegate](ue_ue.PropertyViewBase.md#tooltiptextdelegate)
- [ToolTipWidget](ue_ue.PropertyViewBase.md#tooltipwidget)
- [ToolTipWidgetDelegate](ue_ue.PropertyViewBase.md#tooltipwidgetdelegate)
- [Visibility](ue_ue.PropertyViewBase.md#visibility)
- [VisibilityDelegate](ue_ue.PropertyViewBase.md#visibilitydelegate)
- [\_\_tid\_Object\_\_](ue_ue.PropertyViewBase.md#__tid_object__)
- [\_\_tid\_PropertyViewBase\_\_](ue_ue.PropertyViewBase.md#__tid_propertyviewbase__)
- [\_\_tid\_Visual\_\_](ue_ue.PropertyViewBase.md#__tid_visual__)
- [\_\_tid\_Widget\_\_](ue_ue.PropertyViewBase.md#__tid_widget__)
- [bAutoLoadAsset](ue_ue.PropertyViewBase.md#bautoloadasset)
- [bCanChildrenBeAccessible](ue_ue.PropertyViewBase.md#bcanchildrenbeaccessible)
- [bCreatedByConstructionScript](ue_ue.PropertyViewBase.md#bcreatedbyconstructionscript)
- [bExpandedInDesigner](ue_ue.PropertyViewBase.md#bexpandedindesigner)
- [bHiddenInDesigner](ue_ue.PropertyViewBase.md#bhiddenindesigner)
- [bIsEnabled](ue_ue.PropertyViewBase.md#bisenabled)
- [bIsEnabledDelegate](ue_ue.PropertyViewBase.md#bisenableddelegate)
- [bIsVariable](ue_ue.PropertyViewBase.md#bisvariable)
- [bIsVolatile](ue_ue.PropertyViewBase.md#bisvolatile)
- [bLockedInDesigner](ue_ue.PropertyViewBase.md#blockedindesigner)
- [bOverrideAccessibleDefaults](ue_ue.PropertyViewBase.md#boverrideaccessibledefaults)
- [bOverride\_Cursor](ue_ue.PropertyViewBase.md#boverride_cursor)

### Methods

- [CreateDefaultSubobject](ue_ue.PropertyViewBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PropertyViewBase.md#executeubergraph)
- [ForceLayoutPrepass](ue_ue.PropertyViewBase.md#forcelayoutprepass)
- [ForceVolatile](ue_ue.PropertyViewBase.md#forcevolatile)
- [GenerateWidgetForObject\_\_DelegateSignature](ue_ue.PropertyViewBase.md#generatewidgetforobject__delegatesignature)
- [GenerateWidgetForString\_\_DelegateSignature](ue_ue.PropertyViewBase.md#generatewidgetforstring__delegatesignature)
- [GetBool\_\_DelegateSignature](ue_ue.PropertyViewBase.md#getbool__delegatesignature)
- [GetCachedGeometry](ue_ue.PropertyViewBase.md#getcachedgeometry)
- [GetCheckBoxState\_\_DelegateSignature](ue_ue.PropertyViewBase.md#getcheckboxstate__delegatesignature)
- [GetClass](ue_ue.PropertyViewBase.md#getclass)
- [GetClipping](ue_ue.PropertyViewBase.md#getclipping)
- [GetDesiredSize](ue_ue.PropertyViewBase.md#getdesiredsize)
- [GetFloat\_\_DelegateSignature](ue_ue.PropertyViewBase.md#getfloat__delegatesignature)
- [GetGameInstance](ue_ue.PropertyViewBase.md#getgameinstance)
- [GetInt32\_\_DelegateSignature](ue_ue.PropertyViewBase.md#getint32__delegatesignature)
- [GetIsEnabled](ue_ue.PropertyViewBase.md#getisenabled)
- [GetLinearColor\_\_DelegateSignature](ue_ue.PropertyViewBase.md#getlinearcolor__delegatesignature)
- [GetMouseCursor\_\_DelegateSignature](ue_ue.PropertyViewBase.md#getmousecursor__delegatesignature)
- [GetName](ue_ue.PropertyViewBase.md#getname)
- [GetObject](ue_ue.PropertyViewBase.md#getobject)
- [GetOuter](ue_ue.PropertyViewBase.md#getouter)
- [GetOwningLocalPlayer](ue_ue.PropertyViewBase.md#getowninglocalplayer)
- [GetOwningPlayer](ue_ue.PropertyViewBase.md#getowningplayer)
- [GetPaintSpaceGeometry](ue_ue.PropertyViewBase.md#getpaintspacegeometry)
- [GetParent](ue_ue.PropertyViewBase.md#getparent)
- [GetRenderOpacity](ue_ue.PropertyViewBase.md#getrenderopacity)
- [GetRenderTransformAngle](ue_ue.PropertyViewBase.md#getrendertransformangle)
- [GetSlateBrush\_\_DelegateSignature](ue_ue.PropertyViewBase.md#getslatebrush__delegatesignature)
- [GetSlateColor\_\_DelegateSignature](ue_ue.PropertyViewBase.md#getslatecolor__delegatesignature)
- [GetSlateVisibility\_\_DelegateSignature](ue_ue.PropertyViewBase.md#getslatevisibility__delegatesignature)
- [GetText\_\_DelegateSignature](ue_ue.PropertyViewBase.md#gettext__delegatesignature)
- [GetTickSpaceGeometry](ue_ue.PropertyViewBase.md#gettickspacegeometry)
- [GetVisibility](ue_ue.PropertyViewBase.md#getvisibility)
- [GetWidget\_\_DelegateSignature](ue_ue.PropertyViewBase.md#getwidget__delegatesignature)
- [GetWorld](ue_ue.PropertyViewBase.md#getworld)
- [HasAnyUserFocus](ue_ue.PropertyViewBase.md#hasanyuserfocus)
- [HasFocusedDescendants](ue_ue.PropertyViewBase.md#hasfocuseddescendants)
- [HasKeyboardFocus](ue_ue.PropertyViewBase.md#haskeyboardfocus)
- [HasMouseCapture](ue_ue.PropertyViewBase.md#hasmousecapture)
- [HasMouseCaptureByUser](ue_ue.PropertyViewBase.md#hasmousecapturebyuser)
- [HasUserFocus](ue_ue.PropertyViewBase.md#hasuserfocus)
- [HasUserFocusedDescendants](ue_ue.PropertyViewBase.md#hasuserfocuseddescendants)
- [InvalidateLayoutAndVolatility](ue_ue.PropertyViewBase.md#invalidatelayoutandvolatility)
- [IsHovered](ue_ue.PropertyViewBase.md#ishovered)
- [IsVisible](ue_ue.PropertyViewBase.md#isvisible)
- [OnPointerEvent\_\_DelegateSignature](ue_ue.PropertyViewBase.md#onpointerevent__delegatesignature)
- [OnReply\_\_DelegateSignature](ue_ue.PropertyViewBase.md#onreply__delegatesignature)
- [RemoveFromParent](ue_ue.PropertyViewBase.md#removefromparent)
- [ResetCursor](ue_ue.PropertyViewBase.md#resetcursor)
- [SetAllNavigationRules](ue_ue.PropertyViewBase.md#setallnavigationrules)
- [SetClipping](ue_ue.PropertyViewBase.md#setclipping)
- [SetCursor](ue_ue.PropertyViewBase.md#setcursor)
- [SetFocus](ue_ue.PropertyViewBase.md#setfocus)
- [SetIsEnabled](ue_ue.PropertyViewBase.md#setisenabled)
- [SetKeyboardFocus](ue_ue.PropertyViewBase.md#setkeyboardfocus)
- [SetNavigationRule](ue_ue.PropertyViewBase.md#setnavigationrule)
- [SetNavigationRuleBase](ue_ue.PropertyViewBase.md#setnavigationrulebase)
- [SetNavigationRuleCustom](ue_ue.PropertyViewBase.md#setnavigationrulecustom)
- [SetNavigationRuleCustomBoundary](ue_ue.PropertyViewBase.md#setnavigationrulecustomboundary)
- [SetNavigationRuleExplicit](ue_ue.PropertyViewBase.md#setnavigationruleexplicit)
- [SetObject](ue_ue.PropertyViewBase.md#setobject)
- [SetRenderOpacity](ue_ue.PropertyViewBase.md#setrenderopacity)
- [SetRenderScale](ue_ue.PropertyViewBase.md#setrenderscale)
- [SetRenderShear](ue_ue.PropertyViewBase.md#setrendershear)
- [SetRenderTransform](ue_ue.PropertyViewBase.md#setrendertransform)
- [SetRenderTransformAngle](ue_ue.PropertyViewBase.md#setrendertransformangle)
- [SetRenderTransformPivot](ue_ue.PropertyViewBase.md#setrendertransformpivot)
- [SetRenderTranslation](ue_ue.PropertyViewBase.md#setrendertranslation)
- [SetToolTip](ue_ue.PropertyViewBase.md#settooltip)
- [SetToolTipText](ue_ue.PropertyViewBase.md#settooltiptext)
- [SetUserFocus](ue_ue.PropertyViewBase.md#setuserfocus)
- [SetVisibility](ue_ue.PropertyViewBase.md#setvisibility)
- [Find](ue_ue.PropertyViewBase.md#find)
- [Load](ue_ue.PropertyViewBase.md#load)
- [StaticClass](ue_ue.PropertyViewBase.md#staticclass)

## Constructors

### constructor

• **new PropertyViewBase**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### Cursor

• **Cursor**: [`EMouseCursor`](../enums/ue_ue.EMouseCursor.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[Cursor](ue_ue.Widget.md#cursor)

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

### LazyObject

• **LazyObject**: [`TLazyObjectPtr`](../modules/ue_puerts.md#tlazyobjectptr)<[`Object`](ue_ue.Object.md)\>

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

### OnPropertyChanged

• **OnPropertyChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`PropertyName`: `string`) => `void`\>

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

### SoftObjectPath

• **SoftObjectPath**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

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

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[__tid_Object__](ue_ue.Widget.md#__tid_object__)

___

### \_\_tid\_PropertyViewBase\_\_

• **\_\_tid\_PropertyViewBase\_\_**: `boolean`

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

### bAutoLoadAsset

• **bAutoLoadAsset**: `boolean`

___

### bCanChildrenBeAccessible

• **bCanChildrenBeAccessible**: `boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[bCanChildrenBeAccessible](ue_ue.Widget.md#bcanchildrenbeaccessible)

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

[Widget](ue_ue.Widget.md).[CreateDefaultSubobject](ue_ue.Widget.md#createdefaultsubobject)

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

### GetObject

▸ **GetObject**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

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

### IsHovered

▸ **IsHovered**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[IsHovered](ue_ue.Widget.md#ishovered)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Widget](ue_ue.Widget.md).[IsVisible](ue_ue.Widget.md#isvisible)

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

### OnReply\_\_DelegateSignature

▸ **OnReply__DelegateSignature**(): [`EventReply`](ue_ue.EventReply.md)

#### Returns

[`EventReply`](ue_ue.EventReply.md)

#### Inherited from

[Widget](ue_ue.Widget.md).[OnReply__DelegateSignature](ue_ue.Widget.md#onreply__delegatesignature)

___

### RemoveFromParent

▸ **RemoveFromParent**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[RemoveFromParent](ue_ue.Widget.md#removefromparent)

___

### ResetCursor

▸ **ResetCursor**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[ResetCursor](ue_ue.Widget.md#resetcursor)

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

### SetFocus

▸ **SetFocus**(): `void`

#### Returns

`void`

#### Inherited from

[Widget](ue_ue.Widget.md).[SetFocus](ue_ue.Widget.md#setfocus)

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

### SetObject

▸ **SetObject**(`NewObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PropertyViewBase`](ue_ue.PropertyViewBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PropertyViewBase`](ue_ue.PropertyViewBase.md)

#### Overrides

[Widget](ue_ue.Widget.md).[Find](ue_ue.Widget.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PropertyViewBase`](ue_ue.PropertyViewBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PropertyViewBase`](ue_ue.PropertyViewBase.md)

#### Overrides

[Widget](ue_ue.Widget.md).[Load](ue_ue.Widget.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Widget](ue_ue.Widget.md).[StaticClass](ue_ue.Widget.md#staticclass)
