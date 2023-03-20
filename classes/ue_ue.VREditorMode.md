[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VREditorMode

# Class: VREditorMode

[ue/ue](../modules/ue_ue.md).VREditorMode

## Hierarchy

- [`EditorWorldExtension`](ue_ue.EditorWorldExtension.md)

  ↳ **`VREditorMode`**

## Table of contents

### Constructors

- [constructor](ue_ue.VREditorMode.md#constructor)

### Properties

- [AssetContainer](ue_ue.VREditorMode.md#assetcontainer)
- [AutoScalerSystem](ue_ue.VREditorMode.md#autoscalersystem)
- [AvatarActor](ue_ue.VREditorMode.md#avataractor)
- [ExtensionActors](ue_ue.VREditorMode.md#extensionactors)
- [Interactors](ue_ue.VREditorMode.md#interactors)
- [PlacementSystem](ue_ue.VREditorMode.md#placementsystem)
- [TeleportActor](ue_ue.VREditorMode.md#teleportactor)
- [UISystem](ue_ue.VREditorMode.md#uisystem)
- [WorldInteraction](ue_ue.VREditorMode.md#worldinteraction)
- [\_\_tid\_EditorWorldExtension\_\_](ue_ue.VREditorMode.md#__tid_editorworldextension__)
- [\_\_tid\_Object\_\_](ue_ue.VREditorMode.md#__tid_object__)
- [\_\_tid\_VREditorMode\_\_](ue_ue.VREditorMode.md#__tid_vreditormode__)

### Methods

- [CreateDefaultSubobject](ue_ue.VREditorMode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VREditorMode.md#executeubergraph)
- [GetClass](ue_ue.VREditorMode.md#getclass)
- [GetName](ue_ue.VREditorMode.md#getname)
- [GetOuter](ue_ue.VREditorMode.md#getouter)
- [GetWorld](ue_ue.VREditorMode.md#getworld)
- [GetWorldScaleFactor](ue_ue.VREditorMode.md#getworldscalefactor)
- [Find](ue_ue.VREditorMode.md#find)
- [Load](ue_ue.VREditorMode.md#load)
- [StaticClass](ue_ue.VREditorMode.md#staticclass)

## Constructors

### constructor

• **new VREditorMode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[constructor](ue_ue.EditorWorldExtension.md#constructor)

#### Defined in

[ue/ue.d.ts:65906](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65906)

## Properties

### AssetContainer

• **AssetContainer**: [`VREditorAssetContainer`](ue_ue.VREditorAssetContainer.md)

#### Defined in

[ue/ue.d.ts:65914](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65914)

___

### AutoScalerSystem

• **AutoScalerSystem**: [`VREditorAutoScaler`](ue_ue.VREditorAutoScaler.md)

#### Defined in

[ue/ue.d.ts:65910](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65910)

___

### AvatarActor

• **AvatarActor**: [`VREditorAvatarActor`](ue_ue.VREditorAvatarActor.md)

#### Defined in

[ue/ue.d.ts:65907](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65907)

___

### ExtensionActors

• **ExtensionActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditorWorldExtensionActorData`](ue_ue.EditorWorldExtensionActorData.md)\>

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[ExtensionActors](ue_ue.EditorWorldExtension.md#extensionactors)

#### Defined in

[ue/ue.d.ts:14324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14324)

___

### Interactors

• **Interactors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VREditorInteractor`](ue_ue.VREditorInteractor.md)\>

#### Defined in

[ue/ue.d.ts:65913](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65913)

___

### PlacementSystem

• **PlacementSystem**: [`VREditorPlacement`](ue_ue.VREditorPlacement.md)

#### Defined in

[ue/ue.d.ts:65912](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65912)

___

### TeleportActor

• **TeleportActor**: [`VREditorTeleporter`](ue_ue.VREditorTeleporter.md)

#### Defined in

[ue/ue.d.ts:65909](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65909)

___

### UISystem

• **UISystem**: [`VREditorUISystem`](ue_ue.VREditorUISystem.md)

#### Defined in

[ue/ue.d.ts:65908](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65908)

___

### WorldInteraction

• **WorldInteraction**: [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Defined in

[ue/ue.d.ts:65911](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65911)

___

### \_\_tid\_EditorWorldExtension\_\_

• **\_\_tid\_EditorWorldExtension\_\_**: `boolean`

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[__tid_EditorWorldExtension__](ue_ue.EditorWorldExtension.md#__tid_editorworldextension__)

#### Defined in

[ue/ue.d.ts:14329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14329)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[__tid_Object__](ue_ue.EditorWorldExtension.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_VREditorMode\_\_

• **\_\_tid\_VREditorMode\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:65920](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65920)

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

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[CreateDefaultSubobject](ue_ue.EditorWorldExtension.md#createdefaultsubobject)

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

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[ExecuteUbergraph](ue_ue.EditorWorldExtension.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[GetClass](ue_ue.EditorWorldExtension.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[GetName](ue_ue.EditorWorldExtension.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[GetOuter](ue_ue.EditorWorldExtension.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[GetWorld](ue_ue.EditorWorldExtension.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### GetWorldScaleFactor

▸ **GetWorldScaleFactor**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:65915](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65915)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VREditorMode`](ue_ue.VREditorMode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VREditorMode`](ue_ue.VREditorMode.md)

#### Overrides

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[Find](ue_ue.EditorWorldExtension.md#find)

#### Defined in

[ue/ue.d.ts:65917](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65917)

___

### Load

▸ `Static` **Load**(`InName`): [`VREditorMode`](ue_ue.VREditorMode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VREditorMode`](ue_ue.VREditorMode.md)

#### Overrides

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[Load](ue_ue.EditorWorldExtension.md#load)

#### Defined in

[ue/ue.d.ts:65918](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65918)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[StaticClass](ue_ue.EditorWorldExtension.md#staticclass)

#### Defined in

[ue/ue.d.ts:65916](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65916)
