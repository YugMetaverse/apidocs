[yug_typings](../README.md) / [Modules](../modules.md) / [ue/puerts\_decorators](ue_puerts_decorators.md) / uproperty

# Namespace: uproperty

[ue/puerts_decorators](ue_puerts_decorators.md).uproperty

**`Brief`**

the functionality for add meta data to property

## Table of contents

### Type Aliases

- [MetaKey](ue_puerts_decorators.uproperty.md#metakey)
- [PropertyKey](ue_puerts_decorators.uproperty.md#propertykey)

### Variables

- [AdvancedDisplay](ue_puerts_decorators.uproperty.md#advanceddisplay)
- [AllowAbstract](ue_puerts_decorators.uproperty.md#allowabstract)
- [AllowAnyActor](ue_puerts_decorators.uproperty.md#allowanyactor)
- [AllowPreserveRatio](ue_puerts_decorators.uproperty.md#allowpreserveratio)
- [AllowPrivateAccess](ue_puerts_decorators.uproperty.md#allowprivateaccess)
- [AllowedClasses](ue_puerts_decorators.uproperty.md#allowedclasses)
- [ArrayClamp](ue_puerts_decorators.uproperty.md#arrayclamp)
- [AssetBundles](ue_puerts_decorators.uproperty.md#assetbundles)
- [AssetRegistrySearchable](ue_puerts_decorators.uproperty.md#assetregistrysearchable)
- [Bitmask](ue_puerts_decorators.uproperty.md#bitmask)
- [BitmaskEnum](ue_puerts_decorators.uproperty.md#bitmaskenum)
- [BlueprintAssignable](ue_puerts_decorators.uproperty.md#blueprintassignable)
- [BlueprintAuthorityOnly](ue_puerts_decorators.uproperty.md#blueprintauthorityonly)
- [BlueprintBaseOnly](ue_puerts_decorators.uproperty.md#blueprintbaseonly)
- [BlueprintCallable](ue_puerts_decorators.uproperty.md#blueprintcallable)
- [BlueprintCompilerGeneratedDefaults](ue_puerts_decorators.uproperty.md#blueprintcompilergenerateddefaults)
- [BlueprintGetter](ue_puerts_decorators.uproperty.md#blueprintgetter)
- [BlueprintReadOnly](ue_puerts_decorators.uproperty.md#blueprintreadonly)
- [BlueprintReadWrite](ue_puerts_decorators.uproperty.md#blueprintreadwrite)
- [BlueprintSetter](ue_puerts_decorators.uproperty.md#blueprintsetter)
- [Category](ue_puerts_decorators.uproperty.md#category)
- [ClampMax](ue_puerts_decorators.uproperty.md#clampmax)
- [ClampMin](ue_puerts_decorators.uproperty.md#clampmin)
- [Config](ue_puerts_decorators.uproperty.md#config)
- [ConfigHierarchyEditable](ue_puerts_decorators.uproperty.md#confighierarchyeditable)
- [Const](ue_puerts_decorators.uproperty.md#const)
- [ContentDir](ue_puerts_decorators.uproperty.md#contentdir)
- [DeprecatedProperty](ue_puerts_decorators.uproperty.md#deprecatedproperty)
- [DeprecationMessage](ue_puerts_decorators.uproperty.md#deprecationmessage)
- [DevelopmentOnly](ue_puerts_decorators.uproperty.md#developmentonly)
- [DisallowedClasses](ue_puerts_decorators.uproperty.md#disallowedclasses)
- [DisplayAfter](ue_puerts_decorators.uproperty.md#displayafter)
- [DisplayName](ue_puerts_decorators.uproperty.md#displayname)
- [DisplayPriority](ue_puerts_decorators.uproperty.md#displaypriority)
- [DisplayThumbnail](ue_puerts_decorators.uproperty.md#displaythumbnail)
- [DocumentationPolicy](ue_puerts_decorators.uproperty.md#documentationpolicy)
- [DuplicateTransient](ue_puerts_decorators.uproperty.md#duplicatetransient)
- [EditAnywhere](ue_puerts_decorators.uproperty.md#editanywhere)
- [EditCondition](ue_puerts_decorators.uproperty.md#editcondition)
- [EditDefaultsOnly](ue_puerts_decorators.uproperty.md#editdefaultsonly)
- [EditFixedOrder](ue_puerts_decorators.uproperty.md#editfixedorder)
- [EditFixedSize](ue_puerts_decorators.uproperty.md#editfixedsize)
- [EditInstanceOnly](ue_puerts_decorators.uproperty.md#editinstanceonly)
- [ExactClass](ue_puerts_decorators.uproperty.md#exactclass)
- [Export](ue_puerts_decorators.uproperty.md#export)
- [ExposeFunctionCategories](ue_puerts_decorators.uproperty.md#exposefunctioncategories)
- [ExposeOnSpawn](ue_puerts_decorators.uproperty.md#exposeonspawn)
- [FilePathFilter](ue_puerts_decorators.uproperty.md#filepathfilter)
- [ForceShowEngineContent](ue_puerts_decorators.uproperty.md#forceshowenginecontent)
- [ForceShowPluginContent](ue_puerts_decorators.uproperty.md#forceshowplugincontent)
- [GetOptions](ue_puerts_decorators.uproperty.md#getoptions)
- [GlobalConfig](ue_puerts_decorators.uproperty.md#globalconfig)
- [HideAlphaChannel](ue_puerts_decorators.uproperty.md#hidealphachannel)
- [HideInDetailPanel](ue_puerts_decorators.uproperty.md#hideindetailpanel)
- [HideSelfPin](ue_puerts_decorators.uproperty.md#hideselfpin)
- [HideViewOptions](ue_puerts_decorators.uproperty.md#hideviewoptions)
- [IgnoreForMemberInitializationTest](ue_puerts_decorators.uproperty.md#ignoreformemberinitializationtest)
- [InlineEditConditionToggle](ue_puerts_decorators.uproperty.md#inlineeditconditiontoggle)
- [Instanced](ue_puerts_decorators.uproperty.md#instanced)
- [Interp](ue_puerts_decorators.uproperty.md#interp)
- [LatentCallbackTarget](ue_puerts_decorators.uproperty.md#latentcallbacktarget)
- [Localized](ue_puerts_decorators.uproperty.md#localized)
- [LongPackageName](ue_puerts_decorators.uproperty.md#longpackagename)
- [MakeEditWidget](ue_puerts_decorators.uproperty.md#makeeditwidget)
- [MakeStructureDefaultValue](ue_puerts_decorators.uproperty.md#makestructuredefaultvalue)
- [MetaClass](ue_puerts_decorators.uproperty.md#metaclass)
- [MultiLine](ue_puerts_decorators.uproperty.md#multiline)
- [Multiple](ue_puerts_decorators.uproperty.md#multiple)
- [MustImplement](ue_puerts_decorators.uproperty.md#mustimplement)
- [NeedsLatentFixup](ue_puerts_decorators.uproperty.md#needslatentfixup)
- [NoClear](ue_puerts_decorators.uproperty.md#noclear)
- [NoElementDuplicate](ue_puerts_decorators.uproperty.md#noelementduplicate)
- [NoResetToDefault](ue_puerts_decorators.uproperty.md#noresettodefault)
- [NoSpinbox](ue_puerts_decorators.uproperty.md#nospinbox)
- [NonPIEDuplicateTransient](ue_puerts_decorators.uproperty.md#nonpieduplicatetransient)
- [NonPIETransient](ue_puerts_decorators.uproperty.md#nonpietransient)
- [NonTransactional](ue_puerts_decorators.uproperty.md#nontransactional)
- [NotReplicated](ue_puerts_decorators.uproperty.md#notreplicated)
- [OnlyPlaceable](ue_puerts_decorators.uproperty.md#onlyplaceable)
- [PasswordField](ue_puerts_decorators.uproperty.md#passwordfield)
- [RelativePath](ue_puerts_decorators.uproperty.md#relativepath)
- [RelativeToGameContentDir](ue_puerts_decorators.uproperty.md#relativetogamecontentdir)
- [RelativeToGameDir](ue_puerts_decorators.uproperty.md#relativetogamedir)
- [Replicated](ue_puerts_decorators.uproperty.md#replicated)
- [ReplicatedUsing](ue_puerts_decorators.uproperty.md#replicatedusing)
- [SaveGame](ue_puerts_decorators.uproperty.md#savegame)
- [ScriptName](ue_puerts_decorators.uproperty.md#scriptname)
- [ScriptNoExport](ue_puerts_decorators.uproperty.md#scriptnoexport)
- [ShortTooltip](ue_puerts_decorators.uproperty.md#shorttooltip)
- [ShowOnlyInnerProperties](ue_puerts_decorators.uproperty.md#showonlyinnerproperties)
- [ShowTreeView](ue_puerts_decorators.uproperty.md#showtreeview)
- [SimpleDisplay](ue_puerts_decorators.uproperty.md#simpledisplay)
- [SkipSerialization](ue_puerts_decorators.uproperty.md#skipserialization)
- [SliderExponent](ue_puerts_decorators.uproperty.md#sliderexponent)
- [TextExportTransient](ue_puerts_decorators.uproperty.md#textexporttransient)
- [TitleProperty](ue_puerts_decorators.uproperty.md#titleproperty)
- [ToolTip](ue_puerts_decorators.uproperty.md#tooltip)
- [Transient](ue_puerts_decorators.uproperty.md#transient)
- [UIMax](ue_puerts_decorators.uproperty.md#uimax)
- [UIMin](ue_puerts_decorators.uproperty.md#uimin)
- [Untracked](ue_puerts_decorators.uproperty.md#untracked)
- [VisibleAnywhere](ue_puerts_decorators.uproperty.md#visibleanywhere)
- [VisibleDefaultsOnly](ue_puerts_decorators.uproperty.md#visibledefaultsonly)
- [VisibleInstanceOnly](ue_puerts_decorators.uproperty.md#visibleinstanceonly)

### Functions

- [umeta](ue_puerts_decorators.uproperty.md#umeta)
- [uproperty](ue_puerts_decorators.uproperty.md#uproperty)

## Type Aliases

### MetaKey

Ƭ **MetaKey**: `string` \| `string`[]

**`Brief`**

the meta data with one key for  property meta

___

### PropertyKey

Ƭ **PropertyKey**: `string` \| `string`[]

**`Brief`**

the meta data

## Variables

### AdvancedDisplay

• **AdvancedDisplay**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Properties are in the advanced dropdown in a details panel

___

### AllowAbstract

• **AllowAbstract**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for Subclass and SoftClass properties.  Indicates whether abstract class types should be shown in the class picker.

___

### AllowAnyActor

• **AllowAnyActor**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for ComponentReference properties.  Indicates whether other actor that are not in the property outer hierarchy should be shown in the component picker.

___

### AllowPreserveRatio

• **AllowPreserveRatio**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for FVector properties.  It causes a ratio lock to be added when displaying this property in details panels.

___

### AllowPrivateAccess

• **AllowPrivateAccess**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Indicates that a private member marked as BluperintReadOnly or BlueprintReadWrite should be accessible from blueprints

___

### AllowedClasses

• **AllowedClasses**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for FSoftObjectPath, ComponentReference and UClass properties.  Comma delimited list that indicates the class type(s) of assets to be displayed in the asset picker(FSoftObjectPath) or component picker or class viewer (UClass).

___

### ArrayClamp

• **ArrayClamp**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for integer properties.  Clamps the valid values that can be entered in the UI to be between 0 and the length of the array specified.

___

### AssetBundles

• **AssetBundles**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for SoftObjectPtr/SoftObjectPath properties. Comma separated list of Bundle names used inside PrimaryDataAssets to specify which bundles this reference is part of

___

### AssetRegistrySearchable

• **AssetRegistrySearchable**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

The AssetRegistrySearchable keyword indicates that this property and it's value will be automatically added
     to the asset registry for any asset class instances containing this as a member variable.  It is not legal
     to use on struct properties or parameters.

___

### Bitmask

• **Bitmask**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[FunctionMetadata] [InterfaceMetadata] Metadata that identifies an integral property as a bitmask.

___

### BitmaskEnum

• **BitmaskEnum**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[FunctionMetadata] [InterfaceMetadata] Metadata that associates a bitmask property with a bitflag enum.

___

### BlueprintAssignable

• **BlueprintAssignable**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

MC Delegates only.  Property should be exposed for assigning in blueprints.

___

### BlueprintAuthorityOnly

• **BlueprintAuthorityOnly**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

MC Delegates only. This delegate accepts (only in blueprint) only events with BlueprintAuthorityOnly.

___

### BlueprintBaseOnly

• **BlueprintBaseOnly**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for Subclass and SoftClass properties.  Indicates whether only blueprint classes should be shown in the class picker.

___

### BlueprintCallable

• **BlueprintCallable**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

MC Delegates only.  Property should be exposed for calling in blueprint code

___

### BlueprintCompilerGeneratedDefaults

• **BlueprintCompilerGeneratedDefaults**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Property defaults are generated by the Blueprint compiler and will not be copied when CopyPropertiesForUnrelatedObjects is called post-compile.

___

### BlueprintGetter

• **BlueprintGetter**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

This property has an accessor to return the value. Implies BlueprintReadOnly if BlueprintSetter or BlueprintReadWrite is not specified. (usage: BlueprintGetter=FunctionName).

___

### BlueprintReadOnly

• **BlueprintReadOnly**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

This property can be read by blueprints, but not modified.

___

### BlueprintReadWrite

• **BlueprintReadWrite**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

This property can be read or written from a blueprint.

___

### BlueprintSetter

• **BlueprintSetter**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

This property has an accessor to set the value. Implies BlueprintReadWrite. (usage: BlueprintSetter=FunctionName).

___

### Category

• **Category**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Specifies the category of the property. Usage: Category=CategoryName.

___

### ClampMax

• **ClampMax**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for float and integer properties.  Specifies the maximum value that may be entered for the property.

___

### ClampMin

• **ClampMin**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for float and integer properties.  Specifies the minimum value that may be entered for the property.

___

### Config

• **Config**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Property should be loaded/saved to ini file as permanent profile.

___

### ConfigHierarchyEditable

• **ConfigHierarchyEditable**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Property is serialized to config and we should be able to set it anywhere along the config hierarchy.

___

### Const

• **Const**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

This property is const and should be exported as const.

___

### ContentDir

• **ContentDir**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used by FDirectoryPath properties. Indicates that the path will be picked using the Slate-style directory picker inside the game Content dir.

___

### DeprecatedProperty

• **DeprecatedProperty**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] This property is deprecated, any blueprint references to it cause a compilation warning.

___

### DeprecationMessage

• **DeprecationMessage**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[ClassMetadata] [PropertyMetadata] [FunctionMetadata] Used in conjunction with DeprecatedNode, DeprecatedProperty, or DeprecatedFunction to customize the warning message displayed to the user.

___

### DevelopmentOnly

• **DevelopmentOnly**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] For functions that should be compiled in development mode only.

___

### DisallowedClasses

• **DisallowedClasses**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for FSoftObjectPath, ActorComponentReference and UClass properties.  Comma delimited list that indicates the class type(s) of assets that will NOT be displayed in the asset picker (FSoftObjectPath) or component picker or class viewer (UClass).

___

### DisplayAfter

• **DisplayAfter**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Indicates that the property should be displayed immediately after the property named in the metadata.

___

### DisplayName

• **DisplayName**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[ClassMetadata] [PropertyMetadata] [FunctionMetadata] The name to display for this class, property, or function instead of auto-generating it from the name.

___

### DisplayPriority

• **DisplayPriority**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] The relative order within its category that the property should be displayed in where lower values are sorted first..
     If used in conjunction with DisplayAfter, specifies the priority relative to other properties with same DisplayAfter specifier.

___

### DisplayThumbnail

• **DisplayThumbnail**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Indicates that the property is an asset type and it should display the thumbnail of the selected asset.

___

### DocumentationPolicy

• **DocumentationPolicy**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

A setting to determine validation of tooltips and comments. Needs to be set to "Strict"

___

### DuplicateTransient

• **DuplicateTransient**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Property should always be reset to the default value during any type of duplication (copy/paste, binary duplication, etc.)

___

### EditAnywhere

• **EditAnywhere**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Indicates that this property can be edited by property windows in the editor

___

### EditCondition

• **EditCondition**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Specifies a boolean property that is used to indicate whether editing of this property is disabled.

___

### EditDefaultsOnly

• **EditDefaultsOnly**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Indicates that this property can be edited by property windows, but only on archetypes

___

### EditFixedOrder

• **EditFixedOrder**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Keeps the elements of an array from being reordered by dragging

___

### EditFixedSize

• **EditFixedSize**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Indicates that elements of an array can be modified, but its size cannot be changed.

___

### EditInstanceOnly

• **EditInstanceOnly**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Indicates that this property can be edited by property windows, but only on instances, not on archetypes

___

### ExactClass

• **ExactClass**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for FSoftObjectPath properties in conjunction with AllowedClasses. Indicates whether only the exact classes specified in AllowedClasses can be used or whether subclasses are valid.

___

### Export

• **Export**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Object property can be exported with it's owner.

___

### ExposeFunctionCategories

• **ExposeFunctionCategories**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Specifies a list of categories whose functions should be exposed when building a function list in the Blueprint Editor.

___

### ExposeOnSpawn

• **ExposeOnSpawn**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Specifies whether the property should be exposed on a Spawn Actor for the class type.

___

### FilePathFilter

• **FilePathFilter**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used by FFilePath properties. Indicates the path filter to display in the file picker.

___

### ForceShowEngineContent

• **ForceShowEngineContent**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used by asset properties. Indicates that the asset pickers should always show engine content

___

### ForceShowPluginContent

• **ForceShowPluginContent**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used by asset properties. Indicates that the asset pickers should always show plugin content

___

### GetOptions

• **GetOptions**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Causes FString and FName properties to have a limited set of options generated dynamically, e.g. meta=(GetOptions="FuncName")

     UFUNCTION()
     TArray<FString> FuncName() const; // Always return string array even if FName property.

___

### GlobalConfig

• **GlobalConfig**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Same as above but load config from base class, not subclass.

___

### HideAlphaChannel

• **HideAlphaChannel**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for FColor and FLinearColor properties. Indicates that the Alpha property should be hidden when displaying the property widget in the details.

___

### HideInDetailPanel

• **HideInDetailPanel**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Indicates that the property should be hidden in the details panel. Currently only used by events.

___

### HideSelfPin

• **HideSelfPin**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

If true, the self pin should not be shown or connectable regardless of purity, const, etc. similar to InternalUseParam

___

### HideViewOptions

• **HideViewOptions**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for Subclass and SoftClass properties. Specifies to hide the ability to change view options in the class picker

___

### IgnoreForMemberInitializationTest

• **IgnoreForMemberInitializationTest**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for bypassing property initialization tests when the property cannot be safely tested in a deterministic fashion. Example: random numbers, guids, etc.

___

### InlineEditConditionToggle

• **InlineEditConditionToggle**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Signifies that the bool property is only displayed inline as an edit condition toggle in other properties, and should not be shown on its own row.

___

### Instanced

• **Instanced**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Property is a component reference. Implies EditInline and Export.

___

### Interp

• **Interp**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Interpolatable property for use with matinee. Always user-settable in the editor.

___

### LatentCallbackTarget

• **LatentCallbackTarget**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] (Internal use only) Used for the latent action manager to track where it's re-entry should be

___

### Localized

• **Localized**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Property should be loaded as localizable text. Implies ReadOnly.

___

### LongPackageName

• **LongPackageName**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used by FDirectoryPath properties.  Converts the path to a long package name

___

### MakeEditWidget

• **MakeEditWidget**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for Transform/Rotator properties (also works on arrays of them). Indicates that the property should be exposed in the viewport as a movable widget.

___

### MakeStructureDefaultValue

• **MakeStructureDefaultValue**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] For properties in a structure indicates the default value of the property in a blueprint make structure node.

___

### MetaClass

• **MetaClass**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used FSoftClassPath properties. Indicates the parent class that the class picker will use when filtering which classes to display.

___

### MultiLine

• **MultiLine**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for FString and FText properties.  Indicates that the edit field should be multi-line, allowing entry of newlines.

___

### Multiple

• **Multiple**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for numeric properties. Stipulates that the value must be a multiple of the metadata value.

___

### MustImplement

• **MustImplement**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for Subclass and SoftClass properties. Indicates the selected class must implement a specific interface

___

### NeedsLatentFixup

• **NeedsLatentFixup**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] (Internal use only) Used for the latent action manager to fix up a latent action with the VM

___

### NoClear

• **NoClear**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Hide clear (and browse) button in the editor.

___

### NoElementDuplicate

• **NoElementDuplicate**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for array properties. Indicates that the duplicate icon should not be shown for entries of this array in the property panel.

___

### NoResetToDefault

• **NoResetToDefault**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Property wont have a 'reset to default' button when displayed in property windows

___

### NoSpinbox

• **NoSpinbox**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for integer and float properties. Indicates that the spin box element of the number editing widget should not be displayed.

___

### NonPIEDuplicateTransient

• **NonPIEDuplicateTransient**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Property should always be reset to the default value unless it's being duplicated for a PIE session

___

### NonPIETransient

• **NonPIETransient**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Property should always be reset to the default value unless it's being duplicated for a PIE session - deprecated, use NonPIEDuplicateTransient instead

___

### NonTransactional

• **NonTransactional**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Property isn't transacted.

___

### NotReplicated

• **NotReplicated**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Skip replication (only for struct members and parameters in service request functions).

___

### OnlyPlaceable

• **OnlyPlaceable**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for Subclass properties. Indicates whether only placeable classes should be shown in the class picker.

___

### PasswordField

• **PasswordField**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for FString and FText properties.  Indicates that the edit field is a secret field (e.g a password) and entered text will be replaced with dots. Do not use this as your only security measure.  The property data is still stored as plain text.

___

### RelativePath

• **RelativePath**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used by FDirectoryPath properties. Indicates that the directory dialog will output a relative path when setting the property.

___

### RelativeToGameContentDir

• **RelativeToGameContentDir**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used by FDirectoryPath properties. Indicates that the directory dialog will output a path relative to the game content directory when setting the property.

___

### RelativeToGameDir

• **RelativeToGameDir**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used by FFilePath properties. Indicates that the FilePicker dialog will output a path relative to the game directory when setting the property. An absolute path will be used when outside the game directory.

___

### Replicated

• **Replicated**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Property is relevant to network replication.

___

### ReplicatedUsing

• **ReplicatedUsing**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Property is relevant to network replication. Notify actors when a property is replicated (usage: ReplicatedUsing=FunctionName).

___

### SaveGame

• **SaveGame**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Property should be serialized for save games.
     This is only checked for game-specific archives with ArIsSaveGame set

___

### ScriptName

• **ScriptName**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[ClassMetadata] [PropertyMetadata] [FunctionMetadata] The name to use for this class, property, or function when exporting it to a scripting language. May include deprecated names as additional semi-colon separated entries.

___

### ScriptNoExport

• **ScriptNoExport**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] [FunctionMetadata] Flag set on a property or function to prevent it being exported to a scripting language.

___

### ShortTooltip

• **ShortTooltip**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

A short tooltip that is used in some contexts where the full tooltip might be overwhelming (such as the parent class picker dialog)

___

### ShowOnlyInnerProperties

• **ShowOnlyInnerProperties**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used by struct properties. Indicates that the inner properties will not be shown inside an expandable struct, but promoted up a level.

___

### ShowTreeView

• **ShowTreeView**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for Subclass and SoftClass properties. Shows the picker as a tree view instead of as a list

___

### SimpleDisplay

• **SimpleDisplay**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Properties appear visible by default in a details panel

___

### SkipSerialization

• **SkipSerialization**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Property shouldn't be serialized, can still be exported to text

___

### SliderExponent

• **SliderExponent**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used by numeric properties. Indicates how rapidly the value will grow when moving an unbounded slider.

___

### TextExportTransient

• **TextExportTransient**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Property shouldn't be exported to text format (e.g. copy/paste)

___

### TitleProperty

• **TitleProperty**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used by arrays of structs. Indicates a single property inside of the struct that should be used as a title summary when the array entry is collapsed.

___

### ToolTip

• **ToolTip**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

Overrides the automatically generated tooltip from the class comment

___

### Transient

• **Transient**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Property is transient: shouldn't be saved, zero-filled at load time.

___

### UIMax

• **UIMax**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for float and integer properties.  Specifies the highest that the value slider should represent.

___

### UIMin

• **UIMin**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for float and integer properties.  Specifies the lowest that the value slider should represent.

___

### Untracked

• **Untracked**: [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)

**`Brief`**

[PropertyMetadata] Used for SoftObjectPtr/SoftObjectPath properties to specify a reference should not be tracked. This reference will not be automatically cooked or saved into the asset registry for redirector/delete fixup.

___

### VisibleAnywhere

• **VisibleAnywhere**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Indicates that this property is visible in property windows, but cannot be edited at all

___

### VisibleDefaultsOnly

• **VisibleDefaultsOnly**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Indicates that this property is only visible in property windows for archetypes, and cannot be edited

___

### VisibleInstanceOnly

• **VisibleInstanceOnly**: [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)

**`Brief`**

Indicates that this property is only visible in property windows for instances, not for archetypes, and cannot be edited

## Functions

### umeta

▸ **umeta**(`...InValues`): `any`

the decorator used to add meta data to property

#### Parameters

| Name | Type |
| :------ | :------ |
| `...InValues` | [`MetaKey`](ue_puerts_decorators.uproperty.md#metakey)[] |

#### Returns

`any`

___

### uproperty

▸ **uproperty**(`...InValues`): `any`

decorator used to add property specifier

#### Parameters

| Name | Type |
| :------ | :------ |
| `...InValues` | [`PropertyKey`](ue_puerts_decorators.uproperty.md#propertykey)[] |

#### Returns

`any`
