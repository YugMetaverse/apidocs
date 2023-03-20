[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GlobalEditorUtilityBase

# Class: GlobalEditorUtilityBase

[ue/ue](../modules/ue_ue.md).GlobalEditorUtilityBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`GlobalEditorUtilityBase`**

## Table of contents

### Constructors

- [constructor](ue_ue.GlobalEditorUtilityBase.md#constructor)

### Properties

- [HelpText](ue_ue.GlobalEditorUtilityBase.md#helptext)
- [OnEachSelectedActor](ue_ue.GlobalEditorUtilityBase.md#oneachselectedactor)
- [OnEachSelectedAsset](ue_ue.GlobalEditorUtilityBase.md#oneachselectedasset)
- [\_\_tid\_GlobalEditorUtilityBase\_\_](ue_ue.GlobalEditorUtilityBase.md#__tid_globaleditorutilitybase__)
- [\_\_tid\_Object\_\_](ue_ue.GlobalEditorUtilityBase.md#__tid_object__)
- [bAutoRunDefaultAction](ue_ue.GlobalEditorUtilityBase.md#bautorundefaultaction)
- [bDirtiedSelectionSet](ue_ue.GlobalEditorUtilityBase.md#bdirtiedselectionset)

### Methods

- [ClearActorSelectionSet](ue_ue.GlobalEditorUtilityBase.md#clearactorselectionset)
- [CreateDefaultSubobject](ue_ue.GlobalEditorUtilityBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GlobalEditorUtilityBase.md#executeubergraph)
- [ForEachSelectedActor](ue_ue.GlobalEditorUtilityBase.md#foreachselectedactor)
- [ForEachSelectedAsset](ue_ue.GlobalEditorUtilityBase.md#foreachselectedasset)
- [GetActorReference](ue_ue.GlobalEditorUtilityBase.md#getactorreference)
- [GetClass](ue_ue.GlobalEditorUtilityBase.md#getclass)
- [GetEditorUserSettings](ue_ue.GlobalEditorUtilityBase.md#geteditorusersettings)
- [GetName](ue_ue.GlobalEditorUtilityBase.md#getname)
- [GetOuter](ue_ue.GlobalEditorUtilityBase.md#getouter)
- [GetSelectedAssets](ue_ue.GlobalEditorUtilityBase.md#getselectedassets)
- [GetSelectionBounds](ue_ue.GlobalEditorUtilityBase.md#getselectionbounds)
- [GetSelectionSet](ue_ue.GlobalEditorUtilityBase.md#getselectionset)
- [GetWorld](ue_ue.GlobalEditorUtilityBase.md#getworld)
- [OnDefaultActionClicked](ue_ue.GlobalEditorUtilityBase.md#ondefaultactionclicked)
- [RenameAsset](ue_ue.GlobalEditorUtilityBase.md#renameasset)
- [SelectNothing](ue_ue.GlobalEditorUtilityBase.md#selectnothing)
- [SetActorSelectionState](ue_ue.GlobalEditorUtilityBase.md#setactorselectionstate)
- [Find](ue_ue.GlobalEditorUtilityBase.md#find)
- [Load](ue_ue.GlobalEditorUtilityBase.md#load)
- [StaticClass](ue_ue.GlobalEditorUtilityBase.md#staticclass)

## Constructors

### constructor

• **new GlobalEditorUtilityBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### HelpText

• **HelpText**: `string`

___

### OnEachSelectedActor

• **OnEachSelectedActor**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Index`: `number`) => `void`\>

___

### OnEachSelectedAsset

• **OnEachSelectedAsset**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Asset`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `Index`: `number`) => `void`\>

___

### \_\_tid\_GlobalEditorUtilityBase\_\_

• **\_\_tid\_GlobalEditorUtilityBase\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAutoRunDefaultAction

• **bAutoRunDefaultAction**: `boolean`

___

### bDirtiedSelectionSet

• **bDirtiedSelectionSet**: `boolean`

## Methods

### ClearActorSelectionSet

▸ **ClearActorSelectionSet**(): `void`

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

### ForEachSelectedActor

▸ **ForEachSelectedActor**(): `void`

#### Returns

`void`

___

### ForEachSelectedAsset

▸ **ForEachSelectedAsset**(): `void`

#### Returns

`void`

___

### GetActorReference

▸ **GetActorReference**(`PathToActor`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PathToActor` | `string` |

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetEditorUserSettings

▸ **GetEditorUserSettings**(): [`EditorPerProjectUserSettings`](ue_ue.EditorPerProjectUserSettings.md)

#### Returns

[`EditorPerProjectUserSettings`](ue_ue.EditorPerProjectUserSettings.md)

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

### GetSelectedAssets

▸ **GetSelectedAssets**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### GetSelectionBounds

▸ **GetSelectionBounds**(`Origin`, `BoxExtent`, `SphereRadius`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Origin` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `BoxExtent` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `SphereRadius` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### GetSelectionSet

▸ **GetSelectionSet**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### OnDefaultActionClicked

▸ **OnDefaultActionClicked**(): `void`

#### Returns

`void`

___

### RenameAsset

▸ **RenameAsset**(`Asset`, `NewName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Asset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `NewName` | `string` |

#### Returns

`void`

___

### SelectNothing

▸ **SelectNothing**(): `void`

#### Returns

`void`

___

### SetActorSelectionState

▸ **SetActorSelectionState**(`Actor`, `bShouldBeSelected`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `bShouldBeSelected` | `boolean` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GlobalEditorUtilityBase`](ue_ue.GlobalEditorUtilityBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GlobalEditorUtilityBase`](ue_ue.GlobalEditorUtilityBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GlobalEditorUtilityBase`](ue_ue.GlobalEditorUtilityBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GlobalEditorUtilityBase`](ue_ue.GlobalEditorUtilityBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
