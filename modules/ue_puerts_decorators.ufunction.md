[yug_typings](../README.md) / [Modules](../modules.md) / [ue/puerts\_decorators](ue_puerts_decorators.md) / ufunction

# Namespace: ufunction

[ue/puerts_decorators](ue_puerts_decorators.md).ufunction

**`Brief`**

the functionality for add meta data to function

## Table of contents

### Type Aliases

- [FunctionKey](ue_puerts_decorators.ufunction.md#functionkey)
- [MetaKey](ue_puerts_decorators.ufunction.md#metakey)

### Variables

- [AdvancedDisplay](ue_puerts_decorators.ufunction.md#advanceddisplay)
- [AnimBlueprintFunction](ue_puerts_decorators.ufunction.md#animblueprintfunction)
- [ArrayParam](ue_puerts_decorators.ufunction.md#arrayparam)
- [ArrayParm](ue_puerts_decorators.ufunction.md#arrayparm)
- [ArrayTypeDependentParams](ue_puerts_decorators.ufunction.md#arraytypedependentparams)
- [AutoCreateRefTerm](ue_puerts_decorators.ufunction.md#autocreaterefterm)
- [BlueprintAuthorityOnly](ue_puerts_decorators.ufunction.md#blueprintauthorityonly)
- [BlueprintAutocast](ue_puerts_decorators.ufunction.md#blueprintautocast)
- [BlueprintCallable](ue_puerts_decorators.ufunction.md#blueprintcallable)
- [BlueprintCosmetic](ue_puerts_decorators.ufunction.md#blueprintcosmetic)
- [BlueprintGetter](ue_puerts_decorators.ufunction.md#blueprintgetter)
- [BlueprintImplementableEvent](ue_puerts_decorators.ufunction.md#blueprintimplementableevent)
- [BlueprintInternalUseOnly](ue_puerts_decorators.ufunction.md#blueprintinternaluseonly)
- [BlueprintNativeEvent](ue_puerts_decorators.ufunction.md#blueprintnativeevent)
- [BlueprintProtected](ue_puerts_decorators.ufunction.md#blueprintprotected)
- [BlueprintPure](ue_puerts_decorators.ufunction.md#blueprintpure)
- [BlueprintSetter](ue_puerts_decorators.ufunction.md#blueprintsetter)
- [CallInEditor](ue_puerts_decorators.ufunction.md#callineditor)
- [CallableWithoutWorldContext](ue_puerts_decorators.ufunction.md#callablewithoutworldcontext)
- [Category](ue_puerts_decorators.ufunction.md#category)
- [Client](ue_puerts_decorators.ufunction.md#client)
- [CommutativeAssociativeBinaryOperator](ue_puerts_decorators.ufunction.md#commutativeassociativebinaryoperator)
- [CompactNodeTitle](ue_puerts_decorators.ufunction.md#compactnodetitle)
- [CustomStructureParam](ue_puerts_decorators.ufunction.md#customstructureparam)
- [CustomThunk](ue_puerts_decorators.ufunction.md#customthunk)
- [DataTablePin](ue_puerts_decorators.ufunction.md#datatablepin)
- [DefaultToSelf](ue_puerts_decorators.ufunction.md#defaulttoself)
- [DeprecatedFunction](ue_puerts_decorators.ufunction.md#deprecatedfunction)
- [DeprecationMessage](ue_puerts_decorators.ufunction.md#deprecationmessage)
- [DeterminesOutputType](ue_puerts_decorators.ufunction.md#determinesoutputtype)
- [DisplayName](ue_puerts_decorators.ufunction.md#displayname)
- [DocumentationPolicy](ue_puerts_decorators.ufunction.md#documentationpolicy)
- [DynamicOutputParam](ue_puerts_decorators.ufunction.md#dynamicoutputparam)
- [Exec](ue_puerts_decorators.ufunction.md#exec)
- [ExpandBoolAsExecs](ue_puerts_decorators.ufunction.md#expandboolasexecs)
- [ExpandEnumAsExecs](ue_puerts_decorators.ufunction.md#expandenumasexecs)
- [HidePin](ue_puerts_decorators.ufunction.md#hidepin)
- [HideSpawnParms](ue_puerts_decorators.ufunction.md#hidespawnparms)
- [InternalUseParam](ue_puerts_decorators.ufunction.md#internaluseparam)
- [Keywords](ue_puerts_decorators.ufunction.md#keywords)
- [Latent](ue_puerts_decorators.ufunction.md#latent)
- [LatentInfo](ue_puerts_decorators.ufunction.md#latentinfo)
- [MapKeyParam](ue_puerts_decorators.ufunction.md#mapkeyparam)
- [MapParam](ue_puerts_decorators.ufunction.md#mapparam)
- [MapValueParam](ue_puerts_decorators.ufunction.md#mapvalueparam)
- [MaterialParameterCollectionFunction](ue_puerts_decorators.ufunction.md#materialparametercollectionfunction)
- [NativeBreakFunc](ue_puerts_decorators.ufunction.md#nativebreakfunc)
- [NativeMakeFunc](ue_puerts_decorators.ufunction.md#nativemakefunc)
- [NetMulticast](ue_puerts_decorators.ufunction.md#netmulticast)
- [NotBlueprintThreadSafe](ue_puerts_decorators.ufunction.md#notblueprintthreadsafe)
- [Reliable](ue_puerts_decorators.ufunction.md#reliable)
- [ReturnDisplayName](ue_puerts_decorators.ufunction.md#returndisplayname)
- [ScriptConstant](ue_puerts_decorators.ufunction.md#scriptconstant)
- [ScriptConstantHost](ue_puerts_decorators.ufunction.md#scriptconstanthost)
- [ScriptMethod](ue_puerts_decorators.ufunction.md#scriptmethod)
- [ScriptMethodSelfReturn](ue_puerts_decorators.ufunction.md#scriptmethodselfreturn)
- [ScriptName](ue_puerts_decorators.ufunction.md#scriptname)
- [ScriptNoExport](ue_puerts_decorators.ufunction.md#scriptnoexport)
- [ScriptOperator](ue_puerts_decorators.ufunction.md#scriptoperator)
- [SealedEvent](ue_puerts_decorators.ufunction.md#sealedevent)
- [Server](ue_puerts_decorators.ufunction.md#server)
- [ServiceRequest](ue_puerts_decorators.ufunction.md#servicerequest)
- [ServiceResponse](ue_puerts_decorators.ufunction.md#serviceresponse)
- [SetParam](ue_puerts_decorators.ufunction.md#setparam)
- [ShortTooltip](ue_puerts_decorators.ufunction.md#shorttooltip)
- [ToolTip](ue_puerts_decorators.ufunction.md#tooltip)
- [Unreliable](ue_puerts_decorators.ufunction.md#unreliable)
- [UnsafeDuringActorConstruction](ue_puerts_decorators.ufunction.md#unsafeduringactorconstruction)
- [Variadic](ue_puerts_decorators.ufunction.md#variadic)
- [WithValidation](ue_puerts_decorators.ufunction.md#withvalidation)
- [WorldContext](ue_puerts_decorators.ufunction.md#worldcontext)

### Functions

- [ufunction](ue_puerts_decorators.ufunction.md#ufunction)
- [umeta](ue_puerts_decorators.ufunction.md#umeta)

## Type Aliases

### FunctionKey

Ƭ **FunctionKey**: `string` \| `string`[]

**`Brief`**

the meta data

#### Defined in

[ue/puerts_decorators.d.ts:735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L735)

___

### MetaKey

Ƭ **MetaKey**: `string` \| `string`[]

**`Brief`**

the meta data with one key for class meta

#### Defined in

[ue/puerts_decorators.d.ts:919](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L919)

## Variables

### AdvancedDisplay

• **AdvancedDisplay**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used with a comma-separated list of parameter names that should show up as advanced pins (requiring UI expansion).
     Alternatively you can set a number, which is the number of parameters from the start that should *not* be marked as advanced (eg 'AdvancedDisplay="2"' will mark all but the first two advanced).

**`Deprecated`**

currently not supported

#### Defined in

[ue/puerts_decorators.d.ts:958](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L958)

___

### AnimBlueprintFunction

• **AnimBlueprintFunction**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[InterfaceMetadata] Stub function used internally by animation blueprints

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1307](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1307)

___

### ArrayParam

• **ArrayParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] [InterfaceMetadata] Metadata that flags TArray function parameters that will have their type determined at blueprint compile time

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1315)

___

### ArrayParm

• **ArrayParm**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Indicates that a BlueprintCallable function should use a Call Array Function node and that the parameters specified in the comma delimited list should be treated as wild card array properties.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:966](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L966)

___

### ArrayTypeDependentParams

• **ArrayTypeDependentParams**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used when ArrayParm has been specified to indicate other function parameters that should be treated as wild card properties linked to the type of the array parameter.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:974](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L974)

___

### AutoCreateRefTerm

• **AutoCreateRefTerm**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For reference parameters, indicates that a value should be created to be used for the input if none is linked via BP.
     This also allows for inline editing of the default value on some types (take FRotator for instance). Only valid for inputs.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:983](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L983)

___

### BlueprintAuthorityOnly

• **BlueprintAuthorityOnly**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function will not execute from blueprint code if running on something without network authority

#### Defined in

[ue/puerts_decorators.d.ts:831](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L831)

___

### BlueprintAutocast

• **BlueprintAutocast**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used only by static BlueprintPure functions from BlueprintLibrary. A cast node will be automatically added for the return type and the type of the first parameter of the function.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1223)

___

### BlueprintCallable

• **BlueprintCallable**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function can be called from blueprint code and should be exposed to the user of blueprint editing tools.

#### Defined in

[ue/puerts_decorators.d.ts:809](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L809)

___

### BlueprintCosmetic

• **BlueprintCosmetic**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is cosmetic and will not run on dedicated servers

#### Defined in

[ue/puerts_decorators.d.ts:837](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L837)

___

### BlueprintGetter

• **BlueprintGetter**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is used as the get accessor for a blueprint exposed property. Implies BlueprintPure and BlueprintCallable.

**`Deprecated`**

metadata "BlueprintGetter" will be discarded

#### Defined in

[ue/puerts_decorators.d.ts:817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L817)

___

### BlueprintImplementableEvent

• **BlueprintImplementableEvent**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is designed to be overridden by a blueprint.  Do not provide a body for this function;
     the autogenerated code will include a thunk that calls ProcessEvent to execute the overridden body.

#### Defined in

[ue/puerts_decorators.d.ts:742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L742)

___

### BlueprintInternalUseOnly

• **BlueprintInternalUseOnly**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

Indicates that a Blueprint exposed function should not be exposed to the end user

**`Deprecated`**

currently not supported

#### Defined in

[ue/puerts_decorators.d.ts:927](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L927)

___

### BlueprintNativeEvent

• **BlueprintNativeEvent**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is designed to be overridden by a blueprint, but also has a native implementation.
     Provide a body named [FunctionName]_Implementation instead of [FunctionName]; the autogenerated
     code will include a thunk that calls the implementation method when necessary.

#### Defined in

[ue/puerts_decorators.d.ts:750](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L750)

___

### BlueprintProtected

• **BlueprintProtected**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] This function is only accessible from within its class and derived classes.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:991](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L991)

___

### BlueprintPure

• **BlueprintPure**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function fulfills a contract of producing no side effects, and additionally implies BlueprintCallable.

#### Defined in

[ue/puerts_decorators.d.ts:803](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L803)

___

### BlueprintSetter

• **BlueprintSetter**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is used as the set accessor for a blueprint exposed property. Implies BlueprintCallable.

**`Deprecated`**

metadata "BlueprintSetter" will be discarded

#### Defined in

[ue/puerts_decorators.d.ts:825](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L825)

___

### CallInEditor

• **CallInEditor**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function can be called in the editor on selected instances via a button in the details panel.

#### Defined in

[ue/puerts_decorators.d.ts:843](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L843)

___

### CallableWithoutWorldContext

• **CallableWithoutWorldContext**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used for BlueprintCallable functions that have a WorldContext pin to indicate that the function can be called even if the class does not implement the virtual function GetWorld().

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:999](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L999)

___

### Category

• **Category**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

Specifies the category of the function when displayed in blueprint editing tools.
     Usage: Category=CategoryName or Category="MajorCategory,SubCategory"

#### Defined in

[ue/puerts_decorators.d.ts:858](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L858)

___

### Client

• **Client**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is replicated, and executed on clients.  Provide a body named [FunctionName]_Implementation instead of [FunctionName];
     the autogenerated code will include a thunk that calls the implementation method when necessary.

#### Defined in

[ue/puerts_decorators.d.ts:777](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L777)

___

### CommutativeAssociativeBinaryOperator

• **CommutativeAssociativeBinaryOperator**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Indicates that a BlueprintCallable function should use the Commutative Associative Binary node.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1007](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1007)

___

### CompactNodeTitle

• **CompactNodeTitle**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Indicates that a BlueprintCallable function should display in the compact display mode and the name to use in that mode.

#### Defined in

[ue/puerts_decorators.d.ts:1013](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1013)

___

### CustomStructureParam

• **CustomStructureParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used with CustomThunk to declare that a parameter is actually polymorphic

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1021](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1021)

___

### CustomThunk

• **CustomThunk**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

The UnrealHeaderTool code generator will not produce a execFoo thunk for this function; it is up to the user to provide one.

**`Deprecated`**

currently custom thunk is meaningless for ufunction

#### Defined in

[ue/puerts_decorators.d.ts:851](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L851)

___

### DataTablePin

• **DataTablePin**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata][InterfaceMetadata] Metadata to identify an DataTable Pin. Depending on which DataTable is selected, we display different RowName options

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1255)

___

### DefaultToSelf

• **DefaultToSelf**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions indicates that the object property named's default value should be the self context of the node

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1029](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1029)

___

### DeprecatedFunction

• **DeprecatedFunction**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] This function is deprecated, any blueprint references to it cause a compilation warning.

#### Defined in

[ue/puerts_decorators.d.ts:1035](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1035)

___

### DeprecationMessage

• **DeprecationMessage**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[ClassMetadata] [FunctionMetadata] Used in conjunction with DeprecatedNode or DeprecatedFunction to customize the warning message displayed to the user.

#### Defined in

[ue/puerts_decorators.d.ts:1041](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1041)

___

### DeterminesOutputType

• **DeterminesOutputType**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] [InterfaceMetadata] Metadata that flags function params that govern what type of object the function returns

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1239](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1239)

___

### DisplayName

• **DisplayName**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[ClassMetadata] [PropertyMetadata] [FunctionMetadata] The name to display for this class, property, or function instead of auto-generating it from the name.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1066](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1066)

___

### DocumentationPolicy

• **DocumentationPolicy**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

A setting to determine validation of tooltips and comments. Needs to be set to "Strict"

**`Deprecated`**

currently not supported

#### Defined in

[ue/puerts_decorators.d.ts:949](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L949)

___

### DynamicOutputParam

• **DynamicOutputParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] [InterfaceMetadata] Metadata that flags the function output param that will be controlled by the "MD_DynamicOutputType" pin

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1247](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1247)

___

### Exec

• **Exec**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is executable from the command line.

#### Defined in

[ue/puerts_decorators.d.ts:763](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L763)

___

### ExpandBoolAsExecs

• **ExpandBoolAsExecs**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

Synonym for ExpandEnumAsExecs

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1058](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1058)

___

### ExpandEnumAsExecs

• **ExpandEnumAsExecs**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions indicates that an input/output (determined by whether it is an input/output enum) exec pin should be created for each entry in the enum specified.
     Use ReturnValue to refer to the return value of the function. Also works for bools.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1050](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1050)

___

### HidePin

• **HidePin**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions indicates that the parameter pin should be hidden from the user's view.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1145)

___

### HideSpawnParms

• **HideSpawnParms**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For some functions used by async task nodes, specify this parameter should be skipped when exposing pins

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1153)

___

### InternalUseParam

• **InternalUseParam**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

[FunctionMetadata] Indicates that a particular function parameter is for internal use only, which means it will be both hidden and not connectible.

**`Deprecated`**

currently not supported

#### Defined in

[ue/puerts_decorators.d.ts:907](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L907)

___

### Keywords

• **Keywords**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions provides additional keywords to be associated with the function for search purposes.

#### Defined in

[ue/puerts_decorators.d.ts:1159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1159)

___

### Latent

• **Latent**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Indicates that a BlueprintCallable function is Latent

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1167)

___

### LatentInfo

• **LatentInfo**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For Latent BlueprintCallable functions indicates which parameter is the LatentInfo parameter

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1175)

___

### MapKeyParam

• **MapKeyParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] [InterfaceMetadata]  Metadata that flags TMap function parameters that will have their key type determined at blueprint compile time

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1279](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1279)

___

### MapParam

• **MapParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] [InterfaceMetadata] Metadata that flags TMap function parameters that will have their type determined at blueprint compile time

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1271](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1271)

___

### MapValueParam

• **MapValueParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata][InterfaceMetadata] Metadata that flags TMap function parameter that will have their value type determined at blueprint compile time

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1287](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1287)

___

### MaterialParameterCollectionFunction

• **MaterialParameterCollectionFunction**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions indicates that the material override node should be used

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1183)

___

### NativeBreakFunc

• **NativeBreakFunc**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions indicates that the function should be displayed the same as the implicit Break Struct nodes

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1191)

___

### NativeMakeFunc

• **NativeMakeFunc**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions indicates that the function should be displayed the same as the implicit Make Struct nodes

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1199)

___

### NetMulticast

• **NetMulticast**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is both executed locally on the server and replicated to all clients, regardless of the Actor's NetOwner

#### Defined in

[ue/puerts_decorators.d.ts:783](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L783)

___

### NotBlueprintThreadSafe

• **NotBlueprintThreadSafe**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Only valid in Blueprint Function Libraries. Mark this function as an exception to the class's general BlueprintThreadSafe metadata.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1231](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1231)

___

### Reliable

• **Reliable**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

Replication of calls to this function should be done on a reliable channel.
     Only valid when used in conjunction with Client or Server

#### Defined in

[ue/puerts_decorators.d.ts:790](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L790)

___

### ReturnDisplayName

• **ReturnDisplayName**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

[FunctionMetadata] Indicates the display name of the return value pin

**`Deprecated`**

currently not supported

#### Defined in

[ue/puerts_decorators.d.ts:899](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L899)

___

### ScriptConstant

• **ScriptConstant**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Flags a static function returning a value so that it "hoists" the function to be a constant of its host type when exporting it to a scripting language.
     The constant will be hosted on the class that owns the function, but ScriptConstantHost can be used to host it on a different type (struct or class).
     The value is optional, and may specify a name override for the constant. May include deprecated names as additional semi-colon separated entries.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1129)

___

### ScriptConstantHost

• **ScriptConstantHost**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used with ScriptConstant to override the host type for a constant. Should be the name of a struct or class with no prefix, eg) Vector2D or Actor

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1137)

___

### ScriptMethod

• **ScriptMethod**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Flags a static function taking a struct or or object as its first argument so that it "hoists" the function to be a method of the struct or class when exporting it to a scripting language.
     The value is optional, and may specify a name override for the method. May include deprecated names as additional semi-colon separated entries.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1091](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1091)

___

### ScriptMethodSelfReturn

• **ScriptMethodSelfReturn**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used with ScriptMethod to denote that the return value of the function should overwrite the value of the instance that made the call (structs only, equivalent to using UPARAM(self) on the struct argument).

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1099](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1099)

___

### ScriptName

• **ScriptName**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[ClassMetadata] [PropertyMetadata] [FunctionMetadata] The name to use for this class, property, or function when exporting it to a scripting language. May include deprecated names as additional semi-colon separated entries.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1074)

___

### ScriptNoExport

• **ScriptNoExport**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[PropertyMetadata] [FunctionMetadata] Flag set on a property or function to prevent it being exported to a scripting language.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1082)

___

### ScriptOperator

• **ScriptOperator**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Flags a static function taking a struct as its first argument so that it "hoists" the function to be an operator of the struct when exporting it to a scripting language.
     The value describes the kind of operator using C++ operator syntax (see below), and may contain multiple semi-colon separated values.
     The signature of the function depends on the operator type, and additional parameters may be passed as long as they're defaulted and the basic signature requirements are met.
     - For the bool conversion operator (bool) the signature must be:
    		bool FuncName(const FMyStruct&); // FMyStruct may be passed by value rather than const-ref
     - For the unary conversion operators (neg(-obj)) the signature must be:
    		FMyStruct FuncName(const FMyStruct&); // FMyStruct may be passed by value rather than const-ref
     - For comparison operators (==, !=, <, <=, >, >=) the signature must be:
    		bool FuncName(const FMyStruct, OtherType); // OtherType can be any type, FMyStruct may be passed by value rather than const-ref
    	- For mathematical operators (+, -, *, /, %, &, |, ^, >>, <<) the signature must be:
    		ReturnType FuncName(const FMyStruct&, OtherType); // ReturnType and OtherType can be any type, FMyStruct may be passed by value rather than const-ref
    	- For mathematical assignment operators (+=, -=, *=, /=, %=, &=, |=, ^=, >>=, <<=) the signature must be:
    		FMyStruct FuncName(const FMyStruct&, OtherType); // OtherType can be any type, FMyStruct may be passed by value rather than const-ref

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1119)

___

### SealedEvent

• **SealedEvent**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is sealed and cannot be overridden in subclasses.
     It is only a valid keyword for events; declare other methods as static or final to indicate that they are sealed.

#### Defined in

[ue/puerts_decorators.d.ts:757](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L757)

___

### Server

• **Server**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is replicated, and executed on servers.  Provide a body named [FunctionName]_Implementation instead of [FunctionName];
     the autogenerated code will include a thunk that calls the implementation method when necessary.

#### Defined in

[ue/puerts_decorators.d.ts:770](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L770)

___

### ServiceRequest

• **ServiceRequest**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is RPC service request

**`Deprecated`**

no way to inject information to uht

#### Defined in

[ue/puerts_decorators.d.ts:874](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L874)

___

### ServiceResponse

• **ServiceResponse**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is RPC service response

**`Deprecated`**

no way to inject information to uht

#### Defined in

[ue/puerts_decorators.d.ts:882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L882)

___

### SetParam

• **SetParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata][InterfaceMetadata] Metadata that flags TSet parameters that will have their type determined at blueprint compile time

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1263)

___

### ShortTooltip

• **ShortTooltip**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

A short tooltip that is used in some contexts where the full tooltip might be overwhelming (such as the parent class picker dialog)

**`Deprecated`**

currently not supported

#### Defined in

[ue/puerts_decorators.d.ts:941](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L941)

___

### ToolTip

• **ToolTip**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

Overrides the automatically generated tooltip from the class comment

#### Defined in

[ue/puerts_decorators.d.ts:933](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L933)

___

### Unreliable

• **Unreliable**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

Replication of calls to this function can be done on an unreliable channel.
     Only valid when used in conjunction with Client or Server

#### Defined in

[ue/puerts_decorators.d.ts:797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L797)

___

### UnsafeDuringActorConstruction

• **UnsafeDuringActorConstruction**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used by BlueprintCallable functions to indicate that this function is not to be allowed in the Construction Script.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1207](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1207)

___

### Variadic

• **Variadic**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

[FunctionMetadata]	Marks a UFUNCTION as accepting variadic arguments. Variadic functions may have extra terms they need to emit after the main set of function arguments
						These are all considered wildcards so no type checking will be performed on them

**`Deprecated`**

currently not supported

#### Defined in

[ue/puerts_decorators.d.ts:891](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L891)

___

### WithValidation

• **WithValidation**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function must supply a _Validate implementation

**`Deprecated`**

metadata for WithValidation is discarded

#### Defined in

[ue/puerts_decorators.d.ts:866](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L866)

___

### WorldContext

• **WorldContext**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used by BlueprintCallable functions to indicate which parameter is used to determine the World that the operation is occurring within.

**`Deprecated`**

currently not supported by blueprint function

#### Defined in

[ue/puerts_decorators.d.ts:1215](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1215)

## Functions

### ufunction

▸ **ufunction**(`...InValues`): `any`

decorator used to add function specifier

#### Parameters

| Name | Type |
| :------ | :------ |
| `...InValues` | [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)[] |

#### Returns

`any`

#### Defined in

[ue/puerts_decorators.d.ts:913](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L913)

___

### umeta

▸ **umeta**(`...InValues`): `any`

the decorator used to add meta data to function

#### Parameters

| Name | Type |
| :------ | :------ |
| `...InValues` | [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)[] |

#### Returns

`any`

#### Defined in

[ue/puerts_decorators.d.ts:1321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/puerts_decorators.d.ts#L1321)
