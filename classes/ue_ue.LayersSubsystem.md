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

#### Defined in

[ue/ue.d.ts:44640](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44640)

## Properties

### \_\_tid\_DynamicSubsystem\_\_

• **\_\_tid\_DynamicSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_DynamicSubsystem__](ue_ue.EditorSubsystem.md#__tid_dynamicsubsystem__)

#### Defined in

[ue/ue.d.ts:21573](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21573)

___

### \_\_tid\_EditorSubsystem\_\_

• **\_\_tid\_EditorSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_EditorSubsystem__](ue_ue.EditorSubsystem.md#__tid_editorsubsystem__)

#### Defined in

[ue/ue.d.ts:21582](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21582)

___

### \_\_tid\_LayersSubsystem\_\_

• **\_\_tid\_LayersSubsystem\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:44694](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44694)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Object__](ue_ue.EditorSubsystem.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_Subsystem\_\_

• **\_\_tid\_Subsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Subsystem__](ue_ue.EditorSubsystem.md#__tid_subsystem__)

#### Defined in

[ue/ue.d.ts:21564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21564)

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

#### Defined in

[ue/ue.d.ts:44643](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44643)

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

#### Defined in

[ue/ue.d.ts:44644](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44644)

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

#### Defined in

[ue/ue.d.ts:44641](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44641)

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

#### Defined in

[ue/ue.d.ts:44642](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44642)

___

### AddAllLayerNamesTo

▸ **AddAllLayerNamesTo**(`OutLayerNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutLayerNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:44645](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44645)

___

### AddAllLayersTo

▸ **AddAllLayersTo**(`OutLayers`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutLayers` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Layer`](ue_ue.Layer.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:44646](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44646)

___

### AddLevelLayerInformation

▸ **AddLevelLayerInformation**(`Level`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Level` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Level`](ue_ue.Level.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:44647](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44647)

___

### AddSelectedActorsToLayer

▸ **AddSelectedActorsToLayer**(`LayerName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:44648](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44648)

___

### AddSelectedActorsToLayers

▸ **AddSelectedActorsToLayers**(`LayerNames`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:44649](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44649)

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

#### Defined in

[ue/ue.d.ts:44650](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44650)

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

#### Defined in

[ue/ue.d.ts:44651](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44651)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### CreateLayer

▸ **CreateLayer**(`LayerName`): [`Layer`](ue_ue.Layer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

[`Layer`](ue_ue.Layer.md)

#### Defined in

[ue/ue.d.ts:44652](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44652)

___

### DeleteLayer

▸ **DeleteLayer**(`LayerToDelete`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerToDelete` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:44653](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44653)

___

### DeleteLayers

▸ **DeleteLayers**(`LayersToDelete`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayersToDelete` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:44654](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44654)

___

### DisassociateActorFromLayers

▸ **DisassociateActorFromLayers**(`Actor`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:44655](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44655)

___

### EditorMapChange

▸ **EditorMapChange**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:44656](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44656)

___

### EditorRefreshLayerBrowser

▸ **EditorRefreshLayerBrowser**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:44657](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44657)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetActorsFromLayer

▸ **GetActorsFromLayer**(`LayerName`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:44658](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44658)

___

### GetActorsFromLayers

▸ **GetActorsFromLayers**(`LayerNames`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:44659](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44659)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetClass](ue_ue.EditorSubsystem.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetLayer

▸ **GetLayer**(`LayerName`): [`Layer`](ue_ue.Layer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

[`Layer`](ue_ue.Layer.md)

#### Defined in

[ue/ue.d.ts:44660](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44660)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetName](ue_ue.EditorSubsystem.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetOuter](ue_ue.EditorSubsystem.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetSelectedActors

▸ **GetSelectedActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:44661](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44661)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetWorld](ue_ue.EditorSubsystem.md#getworld)

#### Defined in

[ue/ue.d.ts:44662](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44662)

▸ **GetWorld**(): [`World`](ue_ue.World.md)

**`Deprecated`**

Unsupported super overloads.

#### Returns

[`World`](ue_ue.World.md)

#### Overrides

UE.EditorSubsystem.GetWorld

#### Defined in

[ue/ue.d.ts:44666](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44666)

___

### InitializeNewActorLayers

▸ **InitializeNewActorLayers**(`Actor`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:44667](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44667)

___

### IsActorValidForLayer

▸ **IsActorValidForLayer**(`Actor`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:44668](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44668)

___

### IsLayer

▸ **IsLayer**(`LayerName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:44669](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44669)

___

### MakeAllLayersVisible

▸ **MakeAllLayersVisible**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:44670](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44670)

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

#### Defined in

[ue/ue.d.ts:44671](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44671)

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

#### Defined in

[ue/ue.d.ts:44672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44672)

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

#### Defined in

[ue/ue.d.ts:44673](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44673)

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

#### Defined in

[ue/ue.d.ts:44674](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44674)

___

### RemoveLevelLayerInformation

▸ **RemoveLevelLayerInformation**(`Level`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Level` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Level`](ue_ue.Level.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:44675](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44675)

___

### RemoveSelectedActorsFromLayer

▸ **RemoveSelectedActorsFromLayer**(`LayerName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:44676](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44676)

___

### RemoveSelectedActorsFromLayers

▸ **RemoveSelectedActorsFromLayers**(`LayerNames`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:44677](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44677)

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

#### Defined in

[ue/ue.d.ts:44678](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44678)

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

#### Defined in

[ue/ue.d.ts:44679](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44679)

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

#### Defined in

[ue/ue.d.ts:44680](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44680)

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

#### Defined in

[ue/ue.d.ts:44682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44682)

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

#### Defined in

[ue/ue.d.ts:44681](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44681)

___

### ToggleLayerVisibility

▸ **ToggleLayerVisibility**(`LayerName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:44684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44684)

___

### ToggleLayersVisibility

▸ **ToggleLayersVisibility**(`LayerNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:44683](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44683)

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

#### Defined in

[ue/ue.d.ts:44685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44685)

___

### UpdateActorAllViewsVisibility

▸ **UpdateActorAllViewsVisibility**(`Actor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:44686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44686)

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

#### Defined in

[ue/ue.d.ts:44687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44687)

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

#### Defined in

[ue/ue.d.ts:44688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44688)

___

### UpdateAllViewVisibility

▸ **UpdateAllViewVisibility**(`LayerThatChanged`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LayerThatChanged` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:44689](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44689)

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

#### Defined in

[ue/ue.d.ts:44691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44691)

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

#### Defined in

[ue/ue.d.ts:44692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44692)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[StaticClass](ue_ue.EditorSubsystem.md#staticclass)

#### Defined in

[ue/ue.d.ts:44690](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44690)
