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

#### Defined in

[ue/ue.d.ts:37201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37201)

## Properties

### CategoryRemapping

• **CategoryRemapping**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTagCategoryRemap`](ue_ue.GameplayTagCategoryRemap.md)\>

#### Defined in

[ue/ue.d.ts:37206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37206)

___

### CommonlyReplicatedTags

• **CommonlyReplicatedTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:37209](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37209)

___

### ConfigFileName

• **ConfigFileName**: `string`

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[ConfigFileName](ue_ue.GameplayTagsList.md#configfilename)

#### Defined in

[ue/ue.d.ts:37103](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37103)

___

### FastReplication

• **FastReplication**: `boolean`

#### Defined in

[ue/ue.d.ts:37204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37204)

___

### GameplayTagList

• **GameplayTagList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTagTableRow`](ue_ue.GameplayTagTableRow.md)\>

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[GameplayTagList](ue_ue.GameplayTagsList.md#gameplaytaglist)

#### Defined in

[ue/ue.d.ts:37104](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37104)

___

### GameplayTagRedirects

• **GameplayTagRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameplayTagRedirect`](ue_ue.GameplayTagRedirect.md)\>

#### Defined in

[ue/ue.d.ts:37208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37208)

___

### GameplayTagTableList

• **GameplayTagTableList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\>

#### Defined in

[ue/ue.d.ts:37207](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37207)

___

### ImportTagsFromConfig

• **ImportTagsFromConfig**: `boolean`

#### Defined in

[ue/ue.d.ts:37202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37202)

___

### InvalidTagCharacters

• **InvalidTagCharacters**: `string`

#### Defined in

[ue/ue.d.ts:37205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37205)

___

### NetIndexFirstBitSegment

• **NetIndexFirstBitSegment**: `number`

#### Defined in

[ue/ue.d.ts:37211](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37211)

___

### NumBitsForContainerSize

• **NumBitsForContainerSize**: `number`

#### Defined in

[ue/ue.d.ts:37210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37210)

___

### RestrictedConfigFiles

• **RestrictedConfigFiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RestrictedConfigInfo`](ue_ue.RestrictedConfigInfo.md)\>

#### Defined in

[ue/ue.d.ts:37212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37212)

___

### RestrictedTagList

• **RestrictedTagList**: `string`

#### Defined in

[ue/ue.d.ts:37213](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37213)

___

### WarnOnInvalidTags

• **WarnOnInvalidTags**: `boolean`

#### Defined in

[ue/ue.d.ts:37203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37203)

___

### \_\_tid\_GameplayTagsList\_\_

• **\_\_tid\_GameplayTagsList\_\_**: `boolean`

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[__tid_GameplayTagsList__](ue_ue.GameplayTagsList.md#__tid_gameplaytagslist__)

#### Defined in

[ue/ue.d.ts:37109](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37109)

___

### \_\_tid\_GameplayTagsSettings\_\_

• **\_\_tid\_GameplayTagsSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:37218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37218)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[__tid_Object__](ue_ue.GameplayTagsList.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[GameplayTagsList](ue_ue.GameplayTagsList.md).[ExecuteUbergraph](ue_ue.GameplayTagsList.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[GetClass](ue_ue.GameplayTagsList.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[GetName](ue_ue.GameplayTagsList.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[GetOuter](ue_ue.GameplayTagsList.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameplayTagsList](ue_ue.GameplayTagsList.md).[GetWorld](ue_ue.GameplayTagsList.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:37215](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37215)

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

#### Defined in

[ue/ue.d.ts:37216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37216)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameplayTagsList](ue_ue.GameplayTagsList.md).[StaticClass](ue_ue.GameplayTagsList.md#staticclass)

#### Defined in

[ue/ue.d.ts:37214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37214)
