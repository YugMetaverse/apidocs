[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameplayTagsSettings

# Class: GameplayTagsSettings

[ue/ue](../modules/ue_ue.md).GameplayTagsSettings

## Hierarchy

- [`GameplayTagsList`](ue_ue.GameplayTagsList.md)

  ↳ **`GameplayTagsSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.GameplayTagsSettings.md#constructor)

### Properties

- [CategoryRemapping](ue_ue.GameplayTagsSettings.md#categoryremapping)
- [CommonlyReplicatedTags](ue_ue.GameplayTagsSettings.md#commonlyreplicatedtags)
- [ConfigFileName](ue_ue.GameplayTagsSettings.md#configfilename)
- [FastReplication](ue_ue.GameplayTagsSettings.md#fastreplication)
- [GameplayTagList](ue_ue.GameplayTagsSettings.md#gameplaytaglist)
- [GameplayTagRedirects](ue_ue.GameplayTagsSettings.md#gameplaytagredirects)
- [GameplayTagTableList](ue_ue.GameplayTagsSettings.md#gameplaytagtablelist)
- [ImportTagsFromConfig](ue_ue.GameplayTagsSettings.md#importtagsfromconfig)
- [InvalidTagCharacters](ue_ue.GameplayTagsSettings.md#invalidtagcharacters)
- [NetIndexFirstBitSegment](ue_ue.GameplayTagsSettings.md#netindexfirstbitsegment)
- [NumBitsForContainerSize](ue_ue.GameplayTagsSettings.md#numbitsforcontainersize)
- [RestrictedConfigFiles](ue_ue.GameplayTagsSettings.md#restrictedconfigfiles)
- [RestrictedTagList](ue_ue.GameplayTagsSettings.md#restrictedtaglist)
- [WarnOnInvalidTags](ue_ue.GameplayTagsSettings.md#warnoninvalidtags)
- [\_\_tid\_GameplayTagsList\_\_](ue_ue.GameplayTagsSettings.md#__tid_gameplaytagslist__)
- [\_\_tid\_GameplayTagsSettings\_\_](ue_ue.GameplayTagsSettings.md#__tid_gameplaytagssettings__)
- [\_\_tid\_Object\_\_](ue_ue.GameplayTagsSettings.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.GameplayTagsSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GameplayTagsSettings.md#executeubergraph)
- [GetClass](ue_ue.GameplayTagsSettings.md#getclass)
- [GetName](ue_ue.GameplayTagsSettings.md#getname)
- [GetOuter](ue_ue.GameplayTagsSettings.md#getouter)
- [GetWorld](ue_ue.GameplayTagsSettings.md#getworld)
- [Find](ue_ue.GameplayTagsSettings.md#find)
- [Load](ue_ue.GameplayTagsSettings.md#load)
- [StaticClass](ue_ue.GameplayTagsSettings.md#staticclass)

## Constructors

### constructor

• **new GameplayTagsSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GameplayTagsList](ue_ue.GameplayTagsList.md).[constructor](ue_ue.GameplayTagsList.md#constructor)

## Properties

### CategoryRemapping

• **CategoryRemapping**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTagCategoryRemap`](ue_ue.GameplayTagCategoryRemap.md)\>

___

### CommonlyReplicatedTags

• **CommonlyReplicatedTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ConfigFileName

• **ConfigFileName**: `string`

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[ConfigFileName](ue_ue.GameplayTagsList.md#configfilename)

___

### FastReplication

• **FastReplication**: `boolean`

___

### GameplayTagList

• **GameplayTagList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTagTableRow`](ue_ue.GameplayTagTableRow.md)\>

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[GameplayTagList](ue_ue.GameplayTagsList.md#gameplaytaglist)

___

### GameplayTagRedirects

• **GameplayTagRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTagRedirect`](ue_ue.GameplayTagRedirect.md)\>

___

### GameplayTagTableList

• **GameplayTagTableList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\>

___

### ImportTagsFromConfig

• **ImportTagsFromConfig**: `boolean`

___

### InvalidTagCharacters

• **InvalidTagCharacters**: `string`

___

### NetIndexFirstBitSegment

• **NetIndexFirstBitSegment**: `number`

___

### NumBitsForContainerSize

• **NumBitsForContainerSize**: `number`

___

### RestrictedConfigFiles

• **RestrictedConfigFiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RestrictedConfigInfo`](ue_ue.RestrictedConfigInfo.md)\>

___

### RestrictedTagList

• **RestrictedTagList**: `string`

___

### WarnOnInvalidTags

• **WarnOnInvalidTags**: `boolean`

___

### \_\_tid\_GameplayTagsList\_\_

• **\_\_tid\_GameplayTagsList\_\_**: `boolean`

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[__tid_GameplayTagsList__](ue_ue.GameplayTagsList.md#__tid_gameplaytagslist__)

___

### \_\_tid\_GameplayTagsSettings\_\_

• **\_\_tid\_GameplayTagsSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[__tid_Object__](ue_ue.GameplayTagsList.md#__tid_object__)

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

[GameplayTagsList](ue_ue.GameplayTagsList.md).[CreateDefaultSubobject](ue_ue.GameplayTagsList.md#createdefaultsubobject)

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

[GameplayTagsList](ue_ue.GameplayTagsList.md).[ExecuteUbergraph](ue_ue.GameplayTagsList.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[GetClass](ue_ue.GameplayTagsList.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[GetName](ue_ue.GameplayTagsList.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[GetOuter](ue_ue.GameplayTagsList.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[GetWorld](ue_ue.GameplayTagsList.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameplayTagsSettings`](ue_ue.GameplayTagsSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameplayTagsSettings`](ue_ue.GameplayTagsSettings.md)

#### Overrides

[GameplayTagsList](ue_ue.GameplayTagsList.md).[Find](ue_ue.GameplayTagsList.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GameplayTagsSettings`](ue_ue.GameplayTagsSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameplayTagsSettings`](ue_ue.GameplayTagsSettings.md)

#### Overrides

[GameplayTagsList](ue_ue.GameplayTagsList.md).[Load](ue_ue.GameplayTagsList.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameplayTagsList](ue_ue.GameplayTagsList.md).[StaticClass](ue_ue.GameplayTagsList.md#staticclass)
