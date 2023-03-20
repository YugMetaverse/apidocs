[yug_typings](../README.md) / [Modules](../modules.md) / [ue/puerts\_decorators](ue_puerts_decorators.md) / uclass

# Namespace: uclass

[ue/puerts_decorators](ue_puerts_decorators.md).uclass

**`Brief`**

the functionality for add meta data to class

## Table of contents

### Type Aliases

- [ClassKey](ue_puerts_decorators.uclass.md#classkey)
- [MetaKey](ue_puerts_decorators.uclass.md#metakey)

### Variables

- [Abstract](ue_puerts_decorators.uclass.md#abstract)
- [AdvancedClassDisplay](ue_puerts_decorators.uclass.md#advancedclassdisplay)
- [BlueprintSpawnableComponent](ue_puerts_decorators.uclass.md#blueprintspawnablecomponent)
- [BlueprintThreadSafe](ue_puerts_decorators.uclass.md#blueprintthreadsafe)
- [BlueprintType](ue_puerts_decorators.uclass.md#blueprinttype)
- [Blueprintable](ue_puerts_decorators.uclass.md#blueprintable)
- [ChildCanTick](ue_puerts_decorators.uclass.md#childcantick)
- [ChildCannotTick](ue_puerts_decorators.uclass.md#childcannottick)
- [ClassGroup](ue_puerts_decorators.uclass.md#classgroup)
- [ComponentWrapperClass](ue_puerts_decorators.uclass.md#componentwrapperclass)
- [Const](ue_puerts_decorators.uclass.md#const)
- [ConversionRoot](ue_puerts_decorators.uclass.md#conversionroot)
- [CustomThunkTemplates](ue_puerts_decorators.uclass.md#customthunktemplates)
- [DefaultToInstanced](ue_puerts_decorators.uclass.md#defaulttoinstanced)
- [DeprecatedNode](ue_puerts_decorators.uclass.md#deprecatednode)
- [DeprecationMessage](ue_puerts_decorators.uclass.md#deprecationmessage)
- [DisplayName](ue_puerts_decorators.uclass.md#displayname)
- [DocumentationPolicy](ue_puerts_decorators.uclass.md#documentationpolicy)
- [DontUseGenericSpawnObject](ue_puerts_decorators.uclass.md#dontusegenericspawnobject)
- [EarlyAccessPreview](ue_puerts_decorators.uclass.md#earlyaccesspreview)
- [Experimental](ue_puerts_decorators.uclass.md#experimental)
- [ExposedAsyncProxy](ue_puerts_decorators.uclass.md#exposedasyncproxy)
- [IgnoreCategoryKeywordsInSubclasses](ue_puerts_decorators.uclass.md#ignorecategorykeywordsinsubclasses)
- [Intrinsic](ue_puerts_decorators.uclass.md#intrinsic)
- [IsBlueprintBase](ue_puerts_decorators.uclass.md#isblueprintbase)
- [KismetHideOverrides](ue_puerts_decorators.uclass.md#kismethideoverrides)
- [MinimalAPI](ue_puerts_decorators.uclass.md#minimalapi)
- [NotBlueprintType](ue_puerts_decorators.uclass.md#notblueprinttype)
- [NotBlueprintable](ue_puerts_decorators.uclass.md#notblueprintable)
- [ProhibitedInterfaces](ue_puerts_decorators.uclass.md#prohibitedinterfaces)
- [RestrictedToClasses](ue_puerts_decorators.uclass.md#restrictedtoclasses)
- [ScriptName](ue_puerts_decorators.uclass.md#scriptname)
- [ShortTooltip](ue_puerts_decorators.uclass.md#shorttooltip)
- [ShowWorldContextPin](ue_puerts_decorators.uclass.md#showworldcontextpin)
- [SparseClassDataType](ue_puerts_decorators.uclass.md#sparseclassdatatype)
- [ToolTip](ue_puerts_decorators.uclass.md#tooltip)
- [Transient](ue_puerts_decorators.uclass.md#transient)
- [UsesHierarchy](ue_puerts_decorators.uclass.md#useshierarchy)
- [Within](ue_puerts_decorators.uclass.md#within)
- [autoCollapseCategories](ue_puerts_decorators.uclass.md#autocollapsecategories)
- [autoExpandCategories](ue_puerts_decorators.uclass.md#autoexpandcategories)
- [collapseCategories](ue_puerts_decorators.uclass.md#collapsecategories)
- [config](ue_puerts_decorators.uclass.md#config)
- [configdonotcheckdefaults](ue_puerts_decorators.uclass.md#configdonotcheckdefaults)
- [customConstructor](ue_puerts_decorators.uclass.md#customconstructor)
- [defaultconfig](ue_puerts_decorators.uclass.md#defaultconfig)
- [deprecated](ue_puerts_decorators.uclass.md#deprecated)
- [dontAutoCollapseCategories](ue_puerts_decorators.uclass.md#dontautocollapsecategories)
- [dontCollapseCategories](ue_puerts_decorators.uclass.md#dontcollapsecategories)
- [editinlinenew](ue_puerts_decorators.uclass.md#editinlinenew)
- [hideCategories](ue_puerts_decorators.uclass.md#hidecategories)
- [hideFunctions](ue_puerts_decorators.uclass.md#hidefunctions)
- [hidedropdown](ue_puerts_decorators.uclass.md#hidedropdown)
- [noexport](ue_puerts_decorators.uclass.md#noexport)
- [nonTransient](ue_puerts_decorators.uclass.md#nontransient)
- [noteditinlinenew](ue_puerts_decorators.uclass.md#noteditinlinenew)
- [notplaceable](ue_puerts_decorators.uclass.md#notplaceable)
- [perObjectConfig](ue_puerts_decorators.uclass.md#perobjectconfig)
- [placeable](ue_puerts_decorators.uclass.md#placeable)
- [showCategories](ue_puerts_decorators.uclass.md#showcategories)
- [showFunctions](ue_puerts_decorators.uclass.md#showfunctions)

### Functions

- [uclass](ue_puerts_decorators.uclass.md#uclass)
- [umeta](ue_puerts_decorators.uclass.md#umeta)

## Type Aliases

### ClassKey

Ƭ **ClassKey**: `string` \| `string`[]

**`Brief`**

the meta data

___

### MetaKey

Ƭ **MetaKey**: `string` \| `string`[]

**`Brief`**

the meta data

## Variables

### Abstract

• **Abstract**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Class is abstract and can't be instantiated directly.

___

### AdvancedClassDisplay

• **AdvancedClassDisplay**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

All the properties of the class are hidden in the main display by default, and are only shown in the advanced details section.

___

### BlueprintSpawnableComponent

• **BlueprintSpawnableComponent**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] Used for Actor Component classes. If present indicates that it can be spawned by a Blueprint.
     this is reluctant for component in blueprint

___

### BlueprintThreadSafe

• **BlueprintThreadSafe**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] Only valid on Blueprint Function Libraries. Mark the functions in this class as callable on non-game threads in an Animation Blueprint.

___

### BlueprintType

• **BlueprintType**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Exposes this class as a type that can be used for variables in blueprints
     the blueprint is always blueprint type, reluctant meta data

___

### Blueprintable

• **Blueprintable**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Exposes this class as an acceptable base class for creating blueprints. The default is NotBlueprintable, unless inherited otherwise. This is inherited by subclasses.
     default behavior blueprintable

___

### ChildCanTick

• **ChildCanTick**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] Used for Actor and Component classes. If the native class cannot tick, Blueprint generated classes based this Actor or Component can have bCanEverTick flag overridden even if bCanBlueprintsTickByDefault is false.

___

### ChildCannotTick

• **ChildCannotTick**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] Used for Actor and Component classes. If the native class cannot tick, Blueprint generated classes based this Actor or Component can never tick even if bCanBlueprintsTickByDefault is true.

___

### ClassGroup

• **ClassGroup**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

This keyword is used to set the actor group that the class is show in, in the editor.

**`Deprecated`**

the blueprint's class group is always 'Custom'

___

### ComponentWrapperClass

• **ComponentWrapperClass**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Indicates that this class is a wrapper class for a component with little intrinsic functionality (this causes things like hideCategories and showCategories to be ignored if the class is subclassed in a Blueprint)

___

### Const

• **Const**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

All properties and functions in this class are const and should be exported as const.  This flag is inherited by subclasses.

___

### ConversionRoot

• **ConversionRoot**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

A root convert limits a sub-class to only be able to convert to child classes of the first root class going up the hierarchy.

___

### CustomThunkTemplates

• **CustomThunkTemplates**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Specifies the struct that contains the CustomThunk implementations

**`Deprecated`**

the blueprint custom chunk is meaningless

___

### DefaultToInstanced

• **DefaultToInstanced**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

All instances of this class are considered "instanced". Instanced classes (components) are duplicated upon construction. This flag is inherited by subclasses.

**`Deprecated`**

the blueprint flag is reset by compile process, useless

___

### DeprecatedNode

• **DeprecatedNode**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] For BehaviorTree nodes indicates that the class is deprecated and will display a warning when compiled.

___

### DeprecationMessage

• **DeprecationMessage**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] [PropertyMetadata] [FunctionMetadata] Used in conjunction with DeprecatedNode, DeprecatedProperty, or DeprecatedFunction to customize the warning message displayed to the user.

___

### DisplayName

• **DisplayName**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] [PropertyMetadata] [FunctionMetadata] The name to display for this class, property, or function instead of auto-generating it from the name.

___

### DocumentationPolicy

• **DocumentationPolicy**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

A setting to determine validation of tooltips and comments. Needs to be set to "Strict"

___

### DontUseGenericSpawnObject

• **DontUseGenericSpawnObject**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] Do not spawn an object of the class using Generic Create Object node in Blueprint. It makes sense only for a BluprintType class, that is neither Actor, nor ActorComponent.

___

### EarlyAccessPreview

• **EarlyAccessPreview**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Marks this class as an 'early access' preview (while not considered production-ready, it's a step beyond 'experimental' and is being provided as a preview of things to come)

___

### Experimental

• **Experimental**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Marks this class as 'experimental' (a totally unsupported and undocumented prototype)

___

### ExposedAsyncProxy

• **ExposedAsyncProxy**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] Expose a proxy object of this class in Async Task node.

___

### IgnoreCategoryKeywordsInSubclasses

• **IgnoreCategoryKeywordsInSubclasses**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] Used to make the first subclass of a class ignore all inherited showCategories and hideCategories commands

___

### Intrinsic

• **Intrinsic**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Class was declared directly in C++ and has no boilerplate generated by UnrealHeaderTool.
     DO NOT USE THIS FLAG ON NEW CLASSES.

**`Deprecated`**

blueprint never could be intrinsic

___

### IsBlueprintBase

• **IsBlueprintBase**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] Specifies that this class is an acceptable base class for creating blueprints.

___

### KismetHideOverrides

• **KismetHideOverrides**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] Comma delimited list of blueprint events that are not be allowed to be overridden in classes of this type

___

### MinimalAPI

• **MinimalAPI**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

This keyword indicates that the class should be accessible outside of it's module, but does not need all methods exported.
     It exports only the autogenerated methods required for dynamic_cast<>, etc... to work.

**`Deprecated`**

the export issue is not work for blueprint, the blueprint is more or less an asset issue

___

### NotBlueprintType

• **NotBlueprintType**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Prevents this class from being used for variables in blueprints

**`Deprecated`**

___

### NotBlueprintable

• **NotBlueprintable**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Specifies that this class is *NOT* an acceptable base class for creating blueprints. The default is NotBlueprintable, unless inherited otherwise. This is inherited by subclasses.

___

### ProhibitedInterfaces

• **ProhibitedInterfaces**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] Specifies interfaces that are not compatible with the class.

___

### RestrictedToClasses

• **RestrictedToClasses**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] Used by BlueprintFunctionLibrary classes to restrict the graphs the functions in the library can be used in to the classes specified.

___

### ScriptName

• **ScriptName**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] [PropertyMetadata] [FunctionMetadata] The name to use for this class, property, or function when exporting it to a scripting language. May include deprecated names as additional semi-colon separated entries.

___

### ShortTooltip

• **ShortTooltip**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

A short tooltip that is used in some contexts where the full tooltip might be overwhelming (such as the parent class picker dialog)

___

### ShowWorldContextPin

• **ShowWorldContextPin**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] Indicates that when placing blueprint nodes in graphs owned by this class that the hidden world context pin should be visible because the self context of the class cannot
                provide the world context and it must be wired in manually

___

### SparseClassDataType

• **SparseClassDataType**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Some properties are stored once per class in a sidecar structure and not on instances of the class

___

### ToolTip

• **ToolTip**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

Overrides the automatically generated tooltip from the class comment

___

### Transient

• **Transient**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

This class can't be saved; null it out at save time.  This flag is inherited by subclasses.

**`Deprecated`**

the blueprint flag is reset by compile process, useless

___

### UsesHierarchy

• **UsesHierarchy**: [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)

**`Brief`**

[ClassMetadata] Indicates the class uses hierarchical data. Used to instantiate hierarchical editing features in details panels

___

### Within

• **Within**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Declares that instances of this class should always have an outer of the specified class.  This is inherited by subclasses unless overridden.

**`Deprecated`**

the blueprint's class with in always come from parent class, otherwise Object

___

### autoCollapseCategories

• **autoCollapseCategories**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Specifies which categories should be automatically collapsed in a property viewer.

**`Deprecated`**

the blueprint autoCollapseCategories will be clear in compilation

___

### autoExpandCategories

• **autoExpandCategories**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Specifies which categories should be automatically expanded in a property viewer.

**`Deprecated`**

the blueprint autoExpandCategories will be clear in compilation

___

### collapseCategories

• **collapseCategories**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Display properties in the editor without using categories.

**`Deprecated`**

the blueprint collapseCategories will be clear in compilation

___

### config

• **config**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Load object configuration at construction time.  These flags are inherited by subclasses.
     Class containing config properties. Usage config=ConfigName or config=inherit (inherits config name from base class).

**`Deprecated`**

the blueprint is always config from its parent

___

### configdonotcheckdefaults

• **configdonotcheckdefaults**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Determine whether on serialize to configs a check should be done on the base/defaults ini's

**`Deprecated`**

the blueprint flag is reset by compile process, useless

___

### customConstructor

• **customConstructor**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Prevents automatic generation of the constructor declaration.

**`Deprecated`**

useless

___

### defaultconfig

• **defaultconfig**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Save object config only to Default INIs, never to local INIs.

**`Deprecated`**

the blueprint flag is reset by compile process, useless

___

### deprecated

• **deprecated**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

This class is deprecated and objects of this class won't be saved when serializing.  This flag is inherited by subclasses.

___

### dontAutoCollapseCategories

• **dontAutoCollapseCategories**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Clears the list of auto collapse categories.

**`Deprecated`**

the blueprint dontAutoCollapseCategories will be clear in compilation

___

### dontCollapseCategories

• **dontCollapseCategories**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Display properties in the editor using categories (default behaviour).

**`Deprecated`**

the blueprint dontCollapseCategories will be clear in compilation

___

### editinlinenew

• **editinlinenew**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

These affect the behavior of the property editor.
     Class can be constructed from editinline New button.

**`Deprecated`**

the blueprint flag is reset by compile process, useless

___

### hideCategories

• **hideCategories**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Hides the specified categories in a property viewer. Usage: hideCategories=CategoryName or hideCategories=(category0, category1, ...)

___

### hideFunctions

• **hideFunctions**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Hides the specified function in a property viewer. Usage: hideFunctions=FunctionName or hideFunctions=(category0, category1, ...)

**`Deprecated`**

the blueprint hideFunctions will be clear in compilation

___

### hidedropdown

• **hidedropdown**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Class not shown in editor drop down for class selection.

**`Deprecated`**

the blueprint flag is reset by compile process, useless

___

### noexport

• **noexport**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

No autogenerated code will be created for this class; the header is only provided to parse metadata from.
     DO NOT USE THIS FLAG ON NEW CLASSES.

**`Deprecated`**

blueprint has no export issue

___

### nonTransient

• **nonTransient**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

This class should be saved normally (it cancels out an inherited transient flag).

**`Deprecated`**

the blueprint flag is reset by compile process, useless

___

### noteditinlinenew

• **noteditinlinenew**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Class can't be constructed from editinline New button.

**`Deprecated`**

the blueprint flag is reset by compile process, useless

___

### notplaceable

• **notplaceable**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

This class cannot be placed in the editor (it cancels out an inherited placeable flag).

**`Deprecated`**

the blueprint flag is reset by compile process, useless

___

### perObjectConfig

• **perObjectConfig**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Handle object configuration on a per-object basis, rather than per-class.

**`Deprecated`**

the blueprint flag is reset by compile process, useless

___

### placeable

• **placeable**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Allow users to create and place this class in the editor.  This flag is inherited by subclasses.

**`Deprecated`**

the blueprint flag is reset by compile process, useless

___

### showCategories

• **showCategories**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Shows the specified categories in a property viewer. Usage: showCategories=CategoryName or showCategories=(category0, category1, ...)

**`Deprecated`**

the blueprint showCategories will be clear in compilation

___

### showFunctions

• **showFunctions**: [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)

**`Brief`**

Shows the specified function in a property viewer. Usage: showFunctions=FunctionName or showFunctions=(category0, category1, ...)

**`Deprecated`**

the blueprint showFunctions will be clear in compilation

## Functions

### uclass

▸ **uclass**(`...InValues`): `any`

decorator used to add class specifier

#### Parameters

| Name | Type |
| :------ | :------ |
| `...InValues` | [`ClassKey`](ue_puerts_decorators.uclass.md#classkey)[] |

#### Returns

`any`

___

### umeta

▸ **umeta**(`...InValues`): `any`

the decorator used to add meta data to class

#### Parameters

| Name | Type |
| :------ | :------ |
| `...InValues` | [`MetaKey`](ue_puerts_decorators.uclass.md#metakey)[] |

#### Returns

`any`
