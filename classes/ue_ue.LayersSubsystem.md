[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LayersSubsystem

# Class: LayersSubsystem

[ue/ue](../modules/ue_ue.md).LayersSubsystem

## Hierarchy

- [`EditorSubsystem`](ue_ue.EditorSubsystem.md)

  ↳ **`LayersSubsystem`**

## Table of contents

### Constructors

- [constructor](ue_ue.LayersSubsystem.md#constructor)

### Properties

- [\_\_tid\_DynamicSubsystem\_\_](ue_ue.LayersSubsystem.md#__tid_dynamicsubsystem__)
- [\_\_tid\_EditorSubsystem\_\_](ue_ue.LayersSubsystem.md#__tid_editorsubsystem__)
- [\_\_tid\_LayersSubsystem\_\_](ue_ue.LayersSubsystem.md#__tid_layerssubsystem__)
- [\_\_tid\_Object\_\_](ue_ue.LayersSubsystem.md#__tid_object__)
- [\_\_tid\_Subsystem\_\_](ue_ue.LayersSubsystem.md#__tid_subsystem__)

### Methods

- [AddActorToLayer](ue_ue.LayersSubsystem.md#addactortolayer)
- [AddActorToLayers](ue_ue.LayersSubsystem.md#addactortolayers)
- [AddActorsToLayer](ue_ue.LayersSubsystem.md#addactorstolayer)
- [AddActorsToLayers](ue_ue.LayersSubsystem.md#addactorstolayers)
- [AddAllLayerNamesTo](ue_ue.LayersSubsystem.md#addalllayernamesto)
- [AddAllLayersTo](ue_ue.LayersSubsystem.md#addalllayersto)
- [AddLevelLayerInformation](ue_ue.LayersSubsystem.md#addlevellayerinformation)
- [AddSelectedActorsToLayer](ue_ue.LayersSubsystem.md#addselectedactorstolayer)
- [AddSelectedActorsToLayers](ue_ue.LayersSubsystem.md#addselectedactorstolayers)
- [AppendActorsFromLayer](ue_ue.LayersSubsystem.md#appendactorsfromlayer)
- [AppendActorsFromLayers](ue_ue.LayersSubsystem.md#appendactorsfromlayers)
- [CreateDefaultSubobject](ue_ue.LayersSubsystem.md#createdefaultsubobject)
- [CreateLayer](ue_ue.LayersSubsystem.md#createlayer)
- [DeleteLayer](ue_ue.LayersSubsystem.md#deletelayer)
- [DeleteLayers](ue_ue.LayersSubsystem.md#deletelayers)
- [DisassociateActorFromLayers](ue_ue.LayersSubsystem.md#disassociateactorfromlayers)
- [EditorMapChange](ue_ue.LayersSubsystem.md#editormapchange)
- [EditorRefreshLayerBrowser](ue_ue.LayersSubsystem.md#editorrefreshlayerbrowser)
- [ExecuteUbergraph](ue_ue.LayersSubsystem.md#executeubergraph)
- [GetActorsFromLayer](ue_ue.LayersSubsystem.md#getactorsfromlayer)
- [GetActorsFromLayers](ue_ue.LayersSubsystem.md#getactorsfromlayers)
- [GetClass](ue_ue.LayersSubsystem.md#getclass)
- [GetLayer](ue_ue.LayersSubsystem.md#getlayer)
- [GetName](ue_ue.LayersSubsystem.md#getname)
- [GetOuter](ue_ue.LayersSubsystem.md#getouter)
- [GetSelectedActors](ue_ue.LayersSubsystem.md#getselectedactors)
- [GetWorld](ue_ue.LayersSubsystem.md#getworld)
- [InitializeNewActorLayers](ue_ue.LayersSubsystem.md#initializenewactorlayers)
- [IsActorValidForLayer](ue_ue.LayersSubsystem.md#isactorvalidforlayer)
- [IsLayer](ue_ue.LayersSubsystem.md#islayer)
- [MakeAllLayersVisible](ue_ue.LayersSubsystem.md#makealllayersvisible)
- [RemoveActorFromLayer](ue_ue.LayersSubsystem.md#removeactorfromlayer)
- [RemoveActorFromLayers](ue_ue.LayersSubsystem.md#removeactorfromlayers)
- [RemoveActorsFromLayer](ue_ue.LayersSubsystem.md#removeactorsfromlayer)
- [RemoveActorsFromLayers](ue_ue.LayersSubsystem.md#removeactorsfromlayers)
- [RemoveLevelLayerInformation](ue_ue.LayersSubsystem.md#removelevellayerinformation)
- [RemoveSelectedActorsFromLayer](ue_ue.LayersSubsystem.md#removeselectedactorsfromlayer)
- [RemoveSelectedActorsFromLayers](ue_ue.LayersSubsystem.md#removeselectedactorsfromlayers)
- [RenameLayer](ue_ue.LayersSubsystem.md#renamelayer)
- [SelectActorsInLayer](ue_ue.LayersSubsystem.md#selectactorsinlayer)
- [SelectActorsInLayers](ue_ue.LayersSubsystem.md#selectactorsinlayers)
- [SetLayerVisibility](ue_ue.LayersSubsystem.md#setlayervisibility)
- [SetLayersVisibility](ue_ue.LayersSubsystem.md#setlayersvisibility)
- [ToggleLayerVisibility](ue_ue.LayersSubsystem.md#togglelayervisibility)
- [ToggleLayersVisibility](ue_ue.LayersSubsystem.md#togglelayersvisibility)
- [TryGetLayer](ue_ue.LayersSubsystem.md#trygetlayer)
- [UpdateActorAllViewsVisibility](ue_ue.LayersSubsystem.md#updateactorallviewsvisibility)
- [UpdateActorVisibility](ue_ue.LayersSubsystem.md#updateactorvisibility)
- [UpdateAllActorsVisibility](ue_ue.LayersSubsystem.md#updateallactorsvisibility)
- [UpdateAllViewVisibility](ue_ue.LayersSubsystem.md#updateallviewvisibility)
- [Find](ue_ue.LayersSubsystem.md#find)
- [Load](ue_ue.LayersSubsystem.md#load)
- [StaticClass](ue_ue.LayersSubsystem.md#staticclass)

## Constructors

### constructor

• **new LayersSubsystem**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[constructor](ue_ue.EditorSubsystem.md#constructor)

## Properties

### \_\_tid\_DynamicSubsystem\_\_

• **\_\_tid\_DynamicSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_DynamicSubsystem__](ue_ue.EditorSubsystem.md#__tid_dynamicsubsystem__)

___

### \_\_tid\_EditorSubsystem\_\_

• **\_\_tid\_EditorSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_EditorSubsystem__](ue_ue.EditorSubsystem.md#__tid_editorsubsystem__)

___

### \_\_tid\_LayersSubsystem\_\_

• **\_\_tid\_LayersSubsystem\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Object__](ue_ue.EditorSubsystem.md#__tid_object__)

___

### \_\_tid\_Subsystem\_\_

• **\_\_tid\_Subsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Subsystem__](ue_ue.EditorSubsystem.md#__tid_subsystem__)

## Methods

### AddActorToLayer

▸ **AddActorToLayer**(`Actor`, `LayerName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `LayerName` | `string` |

#### Returns

`boolean`

___

### AddActorToLayers

▸ **AddActorToLayers**(`Actor`, `LayerNames`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`boolean`

___

### AddActorsToLayer

▸ **AddActorsToLayer**(`Actors`, `LayerName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actors` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |
| `LayerName` | `string` |

#### Returns

`boolean`

___

### AddActorsToLayers

▸ **AddActorsToLayers**(`Actors`, `LayerNames`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actors` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`boolean`

___

### AddAllLayerNamesTo

▸ **AddAllLayerNamesTo**(`OutLayerNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutLayerNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

___

### AddAllLayersTo

▸ **AddAllLayersTo**(`OutLayers`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutLayers` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Layer`](ue_ue.Layer.md)\>\> |

#### Returns

`void`

___

### AddLevelLayerInformation

▸ **AddLevelLayerInformation**(`Level`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Level` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Level`](ue_ue.Level.md)\> |

#### Returns

`void`

___

### AddSelectedActorsToLayer

▸ **AddSelectedActorsToLayer**(`LayerName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

`boolean`

___

### AddSelectedActorsToLayers

▸ **AddSelectedActorsToLayers**(`LayerNames`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`boolean`

___

### AppendActorsFromLayer

▸ **AppendActorsFromLayer**(`LayerName`, `InOutActors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |
| `InOutActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

#### Returns

`void`

___

### AppendActorsFromLayers

▸ **AppendActorsFromLayers**(`LayerNames`, `InOutActors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `InOutActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

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

[EditorSubsystem](ue_ue.EditorSubsystem.md).[CreateDefaultSubobject](ue_ue.EditorSubsystem.md#createdefaultsubobject)

___

### CreateLayer

▸ **CreateLayer**(`LayerName`): [`Layer`](ue_ue.Layer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

[`Layer`](ue_ue.Layer.md)

___

### DeleteLayer

▸ **DeleteLayer**(`LayerToDelete`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerToDelete` | `string` |

#### Returns

`void`

___

### DeleteLayers

▸ **DeleteLayers**(`LayersToDelete`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayersToDelete` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`void`

___

### DisassociateActorFromLayers

▸ **DisassociateActorFromLayers**(`Actor`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

___

### EditorMapChange

▸ **EditorMapChange**(): `void`

#### Returns

`void`

___

### EditorRefreshLayerBrowser

▸ **EditorRefreshLayerBrowser**(): `void`

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

[EditorSubsystem](ue_ue.EditorSubsystem.md).[ExecuteUbergraph](ue_ue.EditorSubsystem.md#executeubergraph)

___

### GetActorsFromLayer

▸ **GetActorsFromLayer**(`LayerName`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### GetActorsFromLayers

▸ **GetActorsFromLayers**(`LayerNames`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetClass](ue_ue.EditorSubsystem.md#getclass)

___

### GetLayer

▸ **GetLayer**(`LayerName`): [`Layer`](ue_ue.Layer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

[`Layer`](ue_ue.Layer.md)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetName](ue_ue.EditorSubsystem.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetOuter](ue_ue.EditorSubsystem.md#getouter)

___

### GetSelectedActors

▸ **GetSelectedActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetWorld](ue_ue.EditorSubsystem.md#getworld)

▸ **GetWorld**(): [`World`](ue_ue.World.md)

**`Deprecated`**

Unsupported super overloads.

#### Returns

[`World`](ue_ue.World.md)

#### Overrides

UE.EditorSubsystem.GetWorld

___

### InitializeNewActorLayers

▸ **InitializeNewActorLayers**(`Actor`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

___

### IsActorValidForLayer

▸ **IsActorValidForLayer**(`Actor`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

___

### IsLayer

▸ **IsLayer**(`LayerName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

`boolean`

___

### MakeAllLayersVisible

▸ **MakeAllLayersVisible**(): `void`

#### Returns

`void`

___

### RemoveActorFromLayer

▸ **RemoveActorFromLayer**(`Actor`, `LayerToRemove`, `bUpdateStats?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `LayerToRemove` | `string` |
| `bUpdateStats?` | `boolean` |

#### Returns

`boolean`

___

### RemoveActorFromLayers

▸ **RemoveActorFromLayers**(`Actor`, `LayerNames`, `bUpdateStats?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bUpdateStats?` | `boolean` |

#### Returns

`boolean`

___

### RemoveActorsFromLayer

▸ **RemoveActorsFromLayer**(`Actors`, `LayerName`, `bUpdateStats?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actors` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |
| `LayerName` | `string` |
| `bUpdateStats?` | `boolean` |

#### Returns

`boolean`

___

### RemoveActorsFromLayers

▸ **RemoveActorsFromLayers**(`Actors`, `LayerNames`, `bUpdateStats?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actors` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bUpdateStats?` | `boolean` |

#### Returns

`boolean`

___

### RemoveLevelLayerInformation

▸ **RemoveLevelLayerInformation**(`Level`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Level` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Level`](ue_ue.Level.md)\> |

#### Returns

`void`

___

### RemoveSelectedActorsFromLayer

▸ **RemoveSelectedActorsFromLayer**(`LayerName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

`boolean`

___

### RemoveSelectedActorsFromLayers

▸ **RemoveSelectedActorsFromLayers**(`LayerNames`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`boolean`

___

### RenameLayer

▸ **RenameLayer**(`OriginalLayerName`, `NewLayerName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OriginalLayerName` | `string` |
| `NewLayerName` | `string` |

#### Returns

`boolean`

___

### SelectActorsInLayer

▸ **SelectActorsInLayer**(`LayerName`, `bSelect`, `bNotify`, `bSelectEvenIfHidden?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |
| `bSelect` | `boolean` |
| `bNotify` | `boolean` |
| `bSelectEvenIfHidden?` | `boolean` |

#### Returns

`boolean`

___

### SelectActorsInLayers

▸ **SelectActorsInLayers**(`LayerNames`, `bSelect`, `bNotify`, `bSelectEvenIfHidden?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bSelect` | `boolean` |
| `bNotify` | `boolean` |
| `bSelectEvenIfHidden?` | `boolean` |

#### Returns

`boolean`

___

### SetLayerVisibility

▸ **SetLayerVisibility**(`LayerName`, `bIsVisible`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |
| `bIsVisible` | `boolean` |

#### Returns

`void`

___

### SetLayersVisibility

▸ **SetLayersVisibility**(`LayerNames`, `bIsVisible`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bIsVisible` | `boolean` |

#### Returns

`void`

___

### ToggleLayerVisibility

▸ **ToggleLayerVisibility**(`LayerName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

`void`

___

### ToggleLayersVisibility

▸ **ToggleLayersVisibility**(`LayerNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`void`

___

### TryGetLayer

▸ **TryGetLayer**(`LayerName`, `OutLayer`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |
| `OutLayer` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Layer`](ue_ue.Layer.md)\> |

#### Returns

`boolean`

___

### UpdateActorAllViewsVisibility

▸ **UpdateActorAllViewsVisibility**(`Actor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### UpdateActorVisibility

▸ **UpdateActorVisibility**(`Actor`, `bOutSelectionChanged`, `bOutActorModified`, `bNotifySelectionChange`, `bRedrawViewports`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `bOutSelectionChanged` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `bOutActorModified` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `bNotifySelectionChange` | `boolean` |
| `bRedrawViewports` | `boolean` |

#### Returns

`boolean`

___

### UpdateAllActorsVisibility

▸ **UpdateAllActorsVisibility**(`bNotifySelectionChange`, `bRedrawViewports`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNotifySelectionChange` | `boolean` |
| `bRedrawViewports` | `boolean` |

#### Returns

`boolean`

___

### UpdateAllViewVisibility

▸ **UpdateAllViewVisibility**(`LayerThatChanged`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerThatChanged` | `string` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LayersSubsystem`](ue_ue.LayersSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LayersSubsystem`](ue_ue.LayersSubsystem.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[Find](ue_ue.EditorSubsystem.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LayersSubsystem`](ue_ue.LayersSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LayersSubsystem`](ue_ue.LayersSubsystem.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[Load](ue_ue.EditorSubsystem.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[StaticClass](ue_ue.EditorSubsystem.md#staticclass)
