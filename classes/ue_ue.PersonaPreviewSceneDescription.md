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

#### Defined in

[ue/ue.d.ts:57284](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57284)

## Properties

### AdditionalMeshes

• **AdditionalMeshes**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`DataAsset`](ue_ue.DataAsset.md)\>

#### Defined in

[ue/ue.d.ts:57292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57292)

___

### ApplicationMethod

• **ApplicationMethod**: [`EPreviewAnimationBlueprintApplicationMethod`](../enums/ue_ue.EPreviewAnimationBlueprintApplicationMethod.md)

#### Defined in

[ue/ue.d.ts:57290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57290)

___

### DefaultAdditionalMeshes

• **DefaultAdditionalMeshes**: [`PreviewMeshCollection`](ue_ue.PreviewMeshCollection.md)

#### Defined in

[ue/ue.d.ts:57293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57293)

___

### LinkedAnimGraphTag

• **LinkedAnimGraphTag**: `string`

#### Defined in

[ue/ue.d.ts:57291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57291)

___

### PreviewAnimationBlueprint

• **PreviewAnimationBlueprint**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`AnimBlueprint`](ue_ue.AnimBlueprint.md)\>

#### Defined in

[ue/ue.d.ts:57289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57289)

___

### PreviewController

• **PreviewController**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:57285](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57285)

___

### PreviewControllerInstance

• **PreviewControllerInstance**: [`PersonaPreviewSceneController`](ue_ue.PersonaPreviewSceneController.md)

#### Defined in

[ue/ue.d.ts:57286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57286)

___

### PreviewControllerInstances

• **PreviewControllerInstances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PersonaPreviewSceneController`](ue_ue.PersonaPreviewSceneController.md)\>

#### Defined in

[ue/ue.d.ts:57287](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57287)

___

### PreviewMesh

• **PreviewMesh**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SkeletalMesh`](ue_ue.SkeletalMesh.md)\>

#### Defined in

[ue/ue.d.ts:57288](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57288)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PersonaPreviewSceneDescription\_\_

• **\_\_tid\_PersonaPreviewSceneDescription\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:57298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57298)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:57295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57295)

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

#### Defined in

[ue/ue.d.ts:57296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57296)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:57294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L57294)
