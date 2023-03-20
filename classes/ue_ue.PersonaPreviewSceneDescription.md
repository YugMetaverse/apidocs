[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PersonaPreviewSceneDescription

# Class: PersonaPreviewSceneDescription

[ue/ue](../modules/ue_ue.md).PersonaPreviewSceneDescription

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PersonaPreviewSceneDescription`**

## Table of contents

### Constructors

- [constructor](ue_ue.PersonaPreviewSceneDescription.md#constructor)

### Properties

- [AdditionalMeshes](ue_ue.PersonaPreviewSceneDescription.md#additionalmeshes)
- [ApplicationMethod](ue_ue.PersonaPreviewSceneDescription.md#applicationmethod)
- [DefaultAdditionalMeshes](ue_ue.PersonaPreviewSceneDescription.md#defaultadditionalmeshes)
- [LinkedAnimGraphTag](ue_ue.PersonaPreviewSceneDescription.md#linkedanimgraphtag)
- [PreviewAnimationBlueprint](ue_ue.PersonaPreviewSceneDescription.md#previewanimationblueprint)
- [PreviewController](ue_ue.PersonaPreviewSceneDescription.md#previewcontroller)
- [PreviewControllerInstance](ue_ue.PersonaPreviewSceneDescription.md#previewcontrollerinstance)
- [PreviewControllerInstances](ue_ue.PersonaPreviewSceneDescription.md#previewcontrollerinstances)
- [PreviewMesh](ue_ue.PersonaPreviewSceneDescription.md#previewmesh)
- [\_\_tid\_Object\_\_](ue_ue.PersonaPreviewSceneDescription.md#__tid_object__)
- [\_\_tid\_PersonaPreviewSceneDescription\_\_](ue_ue.PersonaPreviewSceneDescription.md#__tid_personapreviewscenedescription__)

### Methods

- [CreateDefaultSubobject](ue_ue.PersonaPreviewSceneDescription.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PersonaPreviewSceneDescription.md#executeubergraph)
- [GetClass](ue_ue.PersonaPreviewSceneDescription.md#getclass)
- [GetName](ue_ue.PersonaPreviewSceneDescription.md#getname)
- [GetOuter](ue_ue.PersonaPreviewSceneDescription.md#getouter)
- [GetWorld](ue_ue.PersonaPreviewSceneDescription.md#getworld)
- [Find](ue_ue.PersonaPreviewSceneDescription.md#find)
- [Load](ue_ue.PersonaPreviewSceneDescription.md#load)
- [StaticClass](ue_ue.PersonaPreviewSceneDescription.md#staticclass)

## Constructors

### constructor

• **new PersonaPreviewSceneDescription**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AdditionalMeshes

• **AdditionalMeshes**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`DataAsset`](ue_ue.DataAsset.md)\>

___

### ApplicationMethod

• **ApplicationMethod**: [`EPreviewAnimationBlueprintApplicationMethod`](../enums/ue_ue.EPreviewAnimationBlueprintApplicationMethod.md)

___

### DefaultAdditionalMeshes

• **DefaultAdditionalMeshes**: [`PreviewMeshCollection`](ue_ue.PreviewMeshCollection.md)

___

### LinkedAnimGraphTag

• **LinkedAnimGraphTag**: `string`

___

### PreviewAnimationBlueprint

• **PreviewAnimationBlueprint**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`AnimBlueprint`](ue_ue.AnimBlueprint.md)\>

___

### PreviewController

• **PreviewController**: [`Class`](ue_ue.Class.md)

___

### PreviewControllerInstance

• **PreviewControllerInstance**: [`PersonaPreviewSceneController`](ue_ue.PersonaPreviewSceneController.md)

___

### PreviewControllerInstances

• **PreviewControllerInstances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PersonaPreviewSceneController`](ue_ue.PersonaPreviewSceneController.md)\>

___

### PreviewMesh

• **PreviewMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PersonaPreviewSceneDescription\_\_

• **\_\_tid\_PersonaPreviewSceneDescription\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PersonaPreviewSceneDescription`](ue_ue.PersonaPreviewSceneDescription.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PersonaPreviewSceneDescription`](ue_ue.PersonaPreviewSceneDescription.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PersonaPreviewSceneDescription`](ue_ue.PersonaPreviewSceneDescription.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PersonaPreviewSceneDescription`](ue_ue.PersonaPreviewSceneDescription.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
