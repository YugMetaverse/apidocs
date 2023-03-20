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

#### Defined in

[ue/ue.d.ts:38234](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38234)

## Properties

### HelpText

• **HelpText**: `string`

#### Defined in

[ue/ue.d.ts:38235](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38235)

___

### OnEachSelectedActor

• **OnEachSelectedActor**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Actor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>, `Index`: `number`) => `void`\>

#### Defined in

[ue/ue.d.ts:38238](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38238)

___

### OnEachSelectedAsset

• **OnEachSelectedAsset**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Asset`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\>, `Index`: `number`) => `void`\>

#### Defined in

[ue/ue.d.ts:38239](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38239)

___

### \_\_tid\_GlobalEditorUtilityBase\_\_

• **\_\_tid\_GlobalEditorUtilityBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:38256](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38256)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAutoRunDefaultAction

• **bAutoRunDefaultAction**: `boolean`

#### Defined in

[ue/ue.d.ts:38237](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38237)

___

### bDirtiedSelectionSet

• **bDirtiedSelectionSet**: `boolean`

#### Defined in

[ue/ue.d.ts:38236](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38236)

## Methods

### ClearActorSelectionSet

▸ **ClearActorSelectionSet**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38240](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38240)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### ForEachSelectedActor

▸ **ForEachSelectedActor**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38241](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38241)

___

### ForEachSelectedAsset

▸ **ForEachSelectedAsset**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38242](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38242)

___

### GetActorReference

▸ **GetActorReference**(`PathToActor`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PathToActor` | `string` |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:38243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38243)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetEditorUserSettings

▸ **GetEditorUserSettings**(): [`EditorPerProjectUserSettings`](ue_ue.EditorPerProjectUserSettings.md)

#### Returns

[`EditorPerProjectUserSettings`](ue_ue.EditorPerProjectUserSettings.md)

#### Defined in

[ue/ue.d.ts:38244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38244)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetSelectedAssets

▸ **GetSelectedAssets**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:38245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38245)

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

#### Defined in

[ue/ue.d.ts:38246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38246)

___

### GetSelectionSet

▸ **GetSelectionSet**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:38247](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38247)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### OnDefaultActionClicked

▸ **OnDefaultActionClicked**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38248)

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

#### Defined in

[ue/ue.d.ts:38249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38249)

___

### SelectNothing

▸ **SelectNothing**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:38250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38250)

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

#### Defined in

[ue/ue.d.ts:38251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38251)

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

#### Defined in

[ue/ue.d.ts:38253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38253)

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

#### Defined in

[ue/ue.d.ts:38254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38254)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:38252](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L38252)
