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

___

### MetaKey

Ƭ **MetaKey**: `string` \| `string`[]

**`Brief`**

the meta data with one key for class meta

## Variables

### AdvancedDisplay

• **AdvancedDisplay**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used with a comma-separated list of parameter names that should show up as advanced pins (requiring UI expansion).
     Alternatively you can set a number, which is the number of parameters from the start that should *not* be marked as advanced (eg 'AdvancedDisplay="2"' will mark all but the first two advanced).

**`Deprecated`**

currently not supported

___

### AnimBlueprintFunction

• **AnimBlueprintFunction**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[InterfaceMetadata] Stub function used internally by animation blueprints

**`Deprecated`**

currently not supported by blueprint function

___

### ArrayParam

• **ArrayParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] [InterfaceMetadata] Metadata that flags TArray function parameters that will have their type determined at blueprint compile time

**`Deprecated`**

currently not supported by blueprint function

___

### ArrayParm

• **ArrayParm**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Indicates that a BlueprintCallable function should use a Call Array Function node and that the parameters specified in the comma delimited list should be treated as wild card array properties.

**`Deprecated`**

currently not supported by blueprint function

___

### ArrayTypeDependentParams

• **ArrayTypeDependentParams**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used when ArrayParm has been specified to indicate other function parameters that should be treated as wild card properties linked to the type of the array parameter.

**`Deprecated`**

currently not supported by blueprint function

___

### AutoCreateRefTerm

• **AutoCreateRefTerm**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For reference parameters, indicates that a value should be created to be used for the input if none is linked via BP.
     This also allows for inline editing of the default value on some types (take FRotator for instance). Only valid for inputs.

**`Deprecated`**

currently not supported by blueprint function

___

### BlueprintAuthorityOnly

• **BlueprintAuthorityOnly**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function will not execute from blueprint code if running on something without network authority

___

### BlueprintAutocast

• **BlueprintAutocast**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used only by static BlueprintPure functions from BlueprintLibrary. A cast node will be automatically added for the return type and the type of the first parameter of the function.

**`Deprecated`**

currently not supported by blueprint function

___

### BlueprintCallable

• **BlueprintCallable**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function can be called from blueprint code and should be exposed to the user of blueprint editing tools.

___

### BlueprintCosmetic

• **BlueprintCosmetic**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is cosmetic and will not run on dedicated servers

___

### BlueprintGetter

• **BlueprintGetter**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is used as the get accessor for a blueprint exposed property. Implies BlueprintPure and BlueprintCallable.

**`Deprecated`**

metadata "BlueprintGetter" will be discarded

___

### BlueprintImplementableEvent

• **BlueprintImplementableEvent**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is designed to be overridden by a blueprint.  Do not provide a body for this function;
     the autogenerated code will include a thunk that calls ProcessEvent to execute the overridden body.

___

### BlueprintInternalUseOnly

• **BlueprintInternalUseOnly**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

Indicates that a Blueprint exposed function should not be exposed to the end user

**`Deprecated`**

currently not supported

___

### BlueprintNativeEvent

• **BlueprintNativeEvent**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is designed to be overridden by a blueprint, but also has a native implementation.
     Provide a body named [FunctionName]_Implementation instead of [FunctionName]; the autogenerated
     code will include a thunk that calls the implementation method when necessary.

___

### BlueprintProtected

• **BlueprintProtected**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] This function is only accessible from within its class and derived classes.

**`Deprecated`**

currently not supported by blueprint function

___

### BlueprintPure

• **BlueprintPure**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function fulfills a contract of producing no side effects, and additionally implies BlueprintCallable.

___

### BlueprintSetter

• **BlueprintSetter**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is used as the set accessor for a blueprint exposed property. Implies BlueprintCallable.

**`Deprecated`**

metadata "BlueprintSetter" will be discarded

___

### CallInEditor

• **CallInEditor**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function can be called in the editor on selected instances via a button in the details panel.

___

### CallableWithoutWorldContext

• **CallableWithoutWorldContext**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used for BlueprintCallable functions that have a WorldContext pin to indicate that the function can be called even if the class does not implement the virtual function GetWorld().

**`Deprecated`**

currently not supported by blueprint function

___

### Category

• **Category**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

Specifies the category of the function when displayed in blueprint editing tools.
     Usage: Category=CategoryName or Category="MajorCategory,SubCategory"

___

### Client

• **Client**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is replicated, and executed on clients.  Provide a body named [FunctionName]_Implementation instead of [FunctionName];
     the autogenerated code will include a thunk that calls the implementation method when necessary.

___

### CommutativeAssociativeBinaryOperator

• **CommutativeAssociativeBinaryOperator**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Indicates that a BlueprintCallable function should use the Commutative Associative Binary node.

**`Deprecated`**

currently not supported by blueprint function

___

### CompactNodeTitle

• **CompactNodeTitle**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Indicates that a BlueprintCallable function should display in the compact display mode and the name to use in that mode.

___

### CustomStructureParam

• **CustomStructureParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used with CustomThunk to declare that a parameter is actually polymorphic

**`Deprecated`**

currently not supported by blueprint function

___

### CustomThunk

• **CustomThunk**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

The UnrealHeaderTool code generator will not produce a execFoo thunk for this function; it is up to the user to provide one.

**`Deprecated`**

currently custom thunk is meaningless for ufunction

___

### DataTablePin

• **DataTablePin**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata][InterfaceMetadata] Metadata to identify an DataTable Pin. Depending on which DataTable is selected, we display different RowName options

**`Deprecated`**

currently not supported by blueprint function

___

### DefaultToSelf

• **DefaultToSelf**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions indicates that the object property named's default value should be the self context of the node

**`Deprecated`**

currently not supported by blueprint function

___

### DeprecatedFunction

• **DeprecatedFunction**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] This function is deprecated, any blueprint references to it cause a compilation warning.

___

### DeprecationMessage

• **DeprecationMessage**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[ClassMetadata] [FunctionMetadata] Used in conjunction with DeprecatedNode or DeprecatedFunction to customize the warning message displayed to the user.

___

### DeterminesOutputType

• **DeterminesOutputType**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] [InterfaceMetadata] Metadata that flags function params that govern what type of object the function returns

**`Deprecated`**

currently not supported by blueprint function

___

### DisplayName

• **DisplayName**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[ClassMetadata] [PropertyMetadata] [FunctionMetadata] The name to display for this class, property, or function instead of auto-generating it from the name.

**`Deprecated`**

currently not supported by blueprint function

___

### DocumentationPolicy

• **DocumentationPolicy**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

A setting to determine validation of tooltips and comments. Needs to be set to "Strict"

**`Deprecated`**

currently not supported

___

### DynamicOutputParam

• **DynamicOutputParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] [InterfaceMetadata] Metadata that flags the function output param that will be controlled by the "MD_DynamicOutputType" pin

**`Deprecated`**

currently not supported by blueprint function

___

### Exec

• **Exec**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is executable from the command line.

___

### ExpandBoolAsExecs

• **ExpandBoolAsExecs**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

Synonym for ExpandEnumAsExecs

**`Deprecated`**

currently not supported by blueprint function

___

### ExpandEnumAsExecs

• **ExpandEnumAsExecs**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions indicates that an input/output (determined by whether it is an input/output enum) exec pin should be created for each entry in the enum specified.
     Use ReturnValue to refer to the return value of the function. Also works for bools.

**`Deprecated`**

currently not supported by blueprint function

___

### HidePin

• **HidePin**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions indicates that the parameter pin should be hidden from the user's view.

**`Deprecated`**

currently not supported by blueprint function

___

### HideSpawnParms

• **HideSpawnParms**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For some functions used by async task nodes, specify this parameter should be skipped when exposing pins

**`Deprecated`**

currently not supported by blueprint function

___

### InternalUseParam

• **InternalUseParam**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

[FunctionMetadata] Indicates that a particular function parameter is for internal use only, which means it will be both hidden and not connectible.

**`Deprecated`**

currently not supported

___

### Keywords

• **Keywords**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions provides additional keywords to be associated with the function for search purposes.

___

### Latent

• **Latent**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Indicates that a BlueprintCallable function is Latent

**`Deprecated`**

currently not supported by blueprint function

___

### LatentInfo

• **LatentInfo**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For Latent BlueprintCallable functions indicates which parameter is the LatentInfo parameter

**`Deprecated`**

currently not supported by blueprint function

___

### MapKeyParam

• **MapKeyParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] [InterfaceMetadata]  Metadata that flags TMap function parameters that will have their key type determined at blueprint compile time

**`Deprecated`**

currently not supported by blueprint function

___

### MapParam

• **MapParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] [InterfaceMetadata] Metadata that flags TMap function parameters that will have their type determined at blueprint compile time

**`Deprecated`**

currently not supported by blueprint function

___

### MapValueParam

• **MapValueParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata][InterfaceMetadata] Metadata that flags TMap function parameter that will have their value type determined at blueprint compile time

**`Deprecated`**

currently not supported by blueprint function

___

### MaterialParameterCollectionFunction

• **MaterialParameterCollectionFunction**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions indicates that the material override node should be used

**`Deprecated`**

currently not supported by blueprint function

___

### NativeBreakFunc

• **NativeBreakFunc**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions indicates that the function should be displayed the same as the implicit Break Struct nodes

**`Deprecated`**

currently not supported by blueprint function

___

### NativeMakeFunc

• **NativeMakeFunc**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] For BlueprintCallable functions indicates that the function should be displayed the same as the implicit Make Struct nodes

**`Deprecated`**

currently not supported by blueprint function

___

### NetMulticast

• **NetMulticast**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is both executed locally on the server and replicated to all clients, regardless of the Actor's NetOwner

___

### NotBlueprintThreadSafe

• **NotBlueprintThreadSafe**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Only valid in Blueprint Function Libraries. Mark this function as an exception to the class's general BlueprintThreadSafe metadata.

**`Deprecated`**

currently not supported by blueprint function

___

### Reliable

• **Reliable**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

Replication of calls to this function should be done on a reliable channel.
     Only valid when used in conjunction with Client or Server

___

### ReturnDisplayName

• **ReturnDisplayName**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

[FunctionMetadata] Indicates the display name of the return value pin

**`Deprecated`**

currently not supported

___

### ScriptConstant

• **ScriptConstant**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Flags a static function returning a value so that it "hoists" the function to be a constant of its host type when exporting it to a scripting language.
     The constant will be hosted on the class that owns the function, but ScriptConstantHost can be used to host it on a different type (struct or class).
     The value is optional, and may specify a name override for the constant. May include deprecated names as additional semi-colon separated entries.

**`Deprecated`**

currently not supported by blueprint function

___

### ScriptConstantHost

• **ScriptConstantHost**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used with ScriptConstant to override the host type for a constant. Should be the name of a struct or class with no prefix, eg) Vector2D or Actor

**`Deprecated`**

currently not supported by blueprint function

___

### ScriptMethod

• **ScriptMethod**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Flags a static function taking a struct or or object as its first argument so that it "hoists" the function to be a method of the struct or class when exporting it to a scripting language.
     The value is optional, and may specify a name override for the method. May include deprecated names as additional semi-colon separated entries.

**`Deprecated`**

currently not supported by blueprint function

___

### ScriptMethodSelfReturn

• **ScriptMethodSelfReturn**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used with ScriptMethod to denote that the return value of the function should overwrite the value of the instance that made the call (structs only, equivalent to using UPARAM(self) on the struct argument).

**`Deprecated`**

currently not supported by blueprint function

___

### ScriptName

• **ScriptName**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[ClassMetadata] [PropertyMetadata] [FunctionMetadata] The name to use for this class, property, or function when exporting it to a scripting language. May include deprecated names as additional semi-colon separated entries.

**`Deprecated`**

currently not supported by blueprint function

___

### ScriptNoExport

• **ScriptNoExport**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[PropertyMetadata] [FunctionMetadata] Flag set on a property or function to prevent it being exported to a scripting language.

**`Deprecated`**

currently not supported by blueprint function

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

___

### SealedEvent

• **SealedEvent**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is sealed and cannot be overridden in subclasses.
     It is only a valid keyword for events; declare other methods as static or final to indicate that they are sealed.

___

### Server

• **Server**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is replicated, and executed on servers.  Provide a body named [FunctionName]_Implementation instead of [FunctionName];
     the autogenerated code will include a thunk that calls the implementation method when necessary.

___

### ServiceRequest

• **ServiceRequest**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is RPC service request

**`Deprecated`**

no way to inject information to uht

___

### ServiceResponse

• **ServiceResponse**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function is RPC service response

**`Deprecated`**

no way to inject information to uht

___

### SetParam

• **SetParam**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata][InterfaceMetadata] Metadata that flags TSet parameters that will have their type determined at blueprint compile time

**`Deprecated`**

currently not supported by blueprint function

___

### ShortTooltip

• **ShortTooltip**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

A short tooltip that is used in some contexts where the full tooltip might be overwhelming (such as the parent class picker dialog)

**`Deprecated`**

currently not supported

___

### ToolTip

• **ToolTip**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

Overrides the automatically generated tooltip from the class comment

___

### Unreliable

• **Unreliable**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

Replication of calls to this function can be done on an unreliable channel.
     Only valid when used in conjunction with Client or Server

___

### UnsafeDuringActorConstruction

• **UnsafeDuringActorConstruction**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used by BlueprintCallable functions to indicate that this function is not to be allowed in the Construction Script.

**`Deprecated`**

currently not supported by blueprint function

___

### Variadic

• **Variadic**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

[FunctionMetadata]	Marks a UFUNCTION as accepting variadic arguments. Variadic functions may have extra terms they need to emit after the main set of function arguments
						These are all considered wildcards so no type checking will be performed on them

**`Deprecated`**

currently not supported

___

### WithValidation

• **WithValidation**: [`FunctionKey`](ue_puerts_decorators.ufunction.md#functionkey)

**`Brief`**

This function must supply a _Validate implementation

**`Deprecated`**

metadata for WithValidation is discarded

___

### WorldContext

• **WorldContext**: [`MetaKey`](ue_puerts_decorators.ufunction.md#metakey)

**`Brief`**

[FunctionMetadata] Used by BlueprintCallable functions to indicate which parameter is used to determine the World that the operation is occurring within.

**`Deprecated`**

currently not supported by blueprint function

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
