[yug_typings](../README.md) / [Modules](../modules.md) / [ue/puerts\_decorators](../modules/ue_puerts_decorators.md) / ClassFlags

# Enumeration: ClassFlags

[ue/puerts_decorators](../modules/ue_puerts_decorators.md).ClassFlags

the class flags, current internal 32 bit int is ok

## Table of contents

### Enumeration Members

- [CLASS\_Abstract](ue_puerts_decorators.ClassFlags.md#class_abstract)
- [CLASS\_CollapseCategories](ue_puerts_decorators.ClassFlags.md#class_collapsecategories)
- [CLASS\_CompiledFromBlueprint](ue_puerts_decorators.ClassFlags.md#class_compiledfromblueprint)
- [CLASS\_Config](ue_puerts_decorators.ClassFlags.md#class_config)
- [CLASS\_ConfigDoNotCheckDefaults](ue_puerts_decorators.ClassFlags.md#class_configdonotcheckdefaults)
- [CLASS\_Const](ue_puerts_decorators.ClassFlags.md#class_const)
- [CLASS\_Constructed](ue_puerts_decorators.ClassFlags.md#class_constructed)
- [CLASS\_CustomConstructor](ue_puerts_decorators.ClassFlags.md#class_customconstructor)
- [CLASS\_DefaultConfig](ue_puerts_decorators.ClassFlags.md#class_defaultconfig)
- [CLASS\_DefaultToInstanced](ue_puerts_decorators.ClassFlags.md#class_defaulttoinstanced)
- [CLASS\_Deprecated](ue_puerts_decorators.ClassFlags.md#class_deprecated)
- [CLASS\_EditInlineNew](ue_puerts_decorators.ClassFlags.md#class_editinlinenew)
- [CLASS\_GlobalUserConfig](ue_puerts_decorators.ClassFlags.md#class_globaluserconfig)
- [CLASS\_HasInstancedReference](ue_puerts_decorators.ClassFlags.md#class_hasinstancedreference)
- [CLASS\_Hidden](ue_puerts_decorators.ClassFlags.md#class_hidden)
- [CLASS\_HideDropDown](ue_puerts_decorators.ClassFlags.md#class_hidedropdown)
- [CLASS\_Interface](ue_puerts_decorators.ClassFlags.md#class_interface)
- [CLASS\_Intrinsic](ue_puerts_decorators.ClassFlags.md#class_intrinsic)
- [CLASS\_LayoutChanging](ue_puerts_decorators.ClassFlags.md#class_layoutchanging)
- [CLASS\_MatchedSerializers](ue_puerts_decorators.ClassFlags.md#class_matchedserializers)
- [CLASS\_MinimalAPI](ue_puerts_decorators.ClassFlags.md#class_minimalapi)
- [CLASS\_Native](ue_puerts_decorators.ClassFlags.md#class_native)
- [CLASS\_NewerVersionExists](ue_puerts_decorators.ClassFlags.md#class_newerversionexists)
- [CLASS\_NoExport](ue_puerts_decorators.ClassFlags.md#class_noexport)
- [CLASS\_None](ue_puerts_decorators.ClassFlags.md#class_none)
- [CLASS\_NotPlaceable](ue_puerts_decorators.ClassFlags.md#class_notplaceable)
- [CLASS\_Parsed](ue_puerts_decorators.ClassFlags.md#class_parsed)
- [CLASS\_PerObjectConfig](ue_puerts_decorators.ClassFlags.md#class_perobjectconfig)
- [CLASS\_ProjectUserConfig](ue_puerts_decorators.ClassFlags.md#class_projectuserconfig)
- [CLASS\_ReplicationDataIsSetUp](ue_puerts_decorators.ClassFlags.md#class_replicationdataissetup)
- [CLASS\_RequiredAPI](ue_puerts_decorators.ClassFlags.md#class_requiredapi)
- [CLASS\_TokenStreamAssembled](ue_puerts_decorators.ClassFlags.md#class_tokenstreamassembled)
- [CLASS\_Transient](ue_puerts_decorators.ClassFlags.md#class_transient)

## Enumeration Members

### CLASS\_Abstract

• **CLASS\_Abstract** = ``1``

Class is abstract and can't be instantiated directly.

___

### CLASS\_CollapseCategories

• **CLASS\_CollapseCategories** = ``8192``

Display properties in the editor without using categories.

___

### CLASS\_CompiledFromBlueprint

• **CLASS\_CompiledFromBlueprint** = ``262144``

Indicates that the class was created from blueprint source material

___

### CLASS\_Config

• **CLASS\_Config** = ``4``

Load object configuration at construction time.

___

### CLASS\_ConfigDoNotCheckDefaults

• **CLASS\_ConfigDoNotCheckDefaults** = ``1073741824``

Indicates that object configuration will not check against ini base/defaults when serialized

___

### CLASS\_Const

• **CLASS\_Const** = ``65536``

all properties and functions in this class are const and should be exported as const

___

### CLASS\_Constructed

• **CLASS\_Constructed** = ``536870912``

Class has already been constructed (maybe in a previous DLL version before hot-reload).

___

### CLASS\_CustomConstructor

• **CLASS\_CustomConstructor** = ``32768``

Do not export a constructor for this class, assuming it is in the cpptext *

___

### CLASS\_DefaultConfig

• **CLASS\_DefaultConfig** = ``2``

Save object configuration only to Default INIs, never to local INIs. Must be combined with CLASS_Config

___

### CLASS\_DefaultToInstanced

• **CLASS\_DefaultToInstanced** = ``2097152``

Indicates that references to this class default to instanced. Used to be subclasses of UComponent, but now can be any UObject

___

### CLASS\_Deprecated

• **CLASS\_Deprecated** = ``33554432``

Don't save objects of this class when serializing

___

### CLASS\_EditInlineNew

• **CLASS\_EditInlineNew** = ``4096``

Class can be constructed from editinline New button.

___

### CLASS\_GlobalUserConfig

• **CLASS\_GlobalUserConfig** = ``134217728``

Class settings are saved to <AppData>/..../Blah.ini (as opposed to CLASS_DefaultConfig)

___

### CLASS\_HasInstancedReference

• **CLASS\_HasInstancedReference** = ``8388608``

Class has component properties.

___

### CLASS\_Hidden

• **CLASS\_Hidden** = ``16777216``

Don't show this class in the editor class browser or edit inline new menus.

___

### CLASS\_HideDropDown

• **CLASS\_HideDropDown** = ``67108864``

Class not shown in editor drop down for class selection

___

### CLASS\_Interface

• **CLASS\_Interface** = ``16384``

Class is an interface *

___

### CLASS\_Intrinsic

• **CLASS\_Intrinsic** = ``268435456``

Class was declared directly in C++ and has no boilerplate generated by UnrealHeaderTool

___

### CLASS\_LayoutChanging

• **CLASS\_LayoutChanging** = ``131072``

Class flag indicating the class is having its layout changed, and therefore is not ready for a CDO to be created

___

### CLASS\_MatchedSerializers

• **CLASS\_MatchedSerializers** = ``32``

___

### CLASS\_MinimalAPI

• **CLASS\_MinimalAPI** = ``524288``

Indicates that only the bare minimum bits of this class should be DLL exported/imported

___

### CLASS\_Native

• **CLASS\_Native** = ``128``

Class is a native class - native interfaces will have CLASS_Native set, but not RF_MarkAsNative

___

### CLASS\_NewerVersionExists

• **CLASS\_NewerVersionExists** = ``2147483648``

Class has been consigned to oblivion as part of a blueprint recompile, and a newer version currently exists.

___

### CLASS\_NoExport

• **CLASS\_NoExport** = ``256``

Don't export to C++ header.

___

### CLASS\_None

• **CLASS\_None** = ``0``

___

### CLASS\_NotPlaceable

• **CLASS\_NotPlaceable** = ``512``

Do not allow users to create in the editor.

___

### CLASS\_Parsed

• **CLASS\_Parsed** = ``16``

Successfully parsed.

___

### CLASS\_PerObjectConfig

• **CLASS\_PerObjectConfig** = ``1024``

Handle object configuration on a per-object basis, rather than per-class.

___

### CLASS\_ProjectUserConfig

• **CLASS\_ProjectUserConfig** = ``64``

Indicates that the config settings for this class will be saved to Project/User*.ini (similar to CLASS_GlobalUserConfig)

___

### CLASS\_ReplicationDataIsSetUp

• **CLASS\_ReplicationDataIsSetUp** = ``2048``

Whether SetUpRuntimeReplicationData still needs to be called for this class

___

### CLASS\_RequiredAPI

• **CLASS\_RequiredAPI** = ``1048576``

Indicates this class must be DLL exported/imported (along with all of it's members)

___

### CLASS\_TokenStreamAssembled

• **CLASS\_TokenStreamAssembled** = ``4194304``

Indicates that the parent token stream has been merged with ours.

___

### CLASS\_Transient

• **CLASS\_Transient** = ``8``

This object type can't be saved; null it out at save time.
