[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorSettings

# Class: EditorSettings

[ue/ue](../modules/ue_ue.md).EditorSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EditorSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorSettings.md#constructor)

### Properties

- [AutoScalabilityWorkScaleAmount](ue_ue.EditorSettings.md#autoscalabilityworkscaleamount)
- [CompletedSurveys](ue_ue.EditorSettings.md#completedsurveys)
- [CreatedProjectPaths](ue_ue.EditorSettings.md#createdprojectpaths)
- [InProgressSurveys](ue_ue.EditorSettings.md#inprogresssurveys)
- [LocalDerivedDataCache](ue_ue.EditorSettings.md#localderiveddatacache)
- [RecentlyOpenedProjectFiles](ue_ue.EditorSettings.md#recentlyopenedprojectfiles)
- [SharedDerivedDataCache](ue_ue.EditorSettings.md#sharedderiveddatacache)
- [\_\_tid\_EditorSettings\_\_](ue_ue.EditorSettings.md#__tid_editorsettings__)
- [\_\_tid\_Object\_\_](ue_ue.EditorSettings.md#__tid_object__)
- [bCopyStarterContentPreference](ue_ue.EditorSettings.md#bcopystartercontentpreference)
- [bEditorAnalyticsEnabled](ue_ue.EditorSettings.md#beditoranalyticsenabled)
- [bLoadTheMostRecentlyLoadedProjectAtStartup](ue_ue.EditorSettings.md#bloadthemostrecentlyloadedprojectatstartup)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorSettings.md#executeubergraph)
- [GetClass](ue_ue.EditorSettings.md#getclass)
- [GetName](ue_ue.EditorSettings.md#getname)
- [GetOuter](ue_ue.EditorSettings.md#getouter)
- [GetWorld](ue_ue.EditorSettings.md#getworld)
- [Find](ue_ue.EditorSettings.md#find)
- [Load](ue_ue.EditorSettings.md#load)
- [StaticClass](ue_ue.EditorSettings.md#staticclass)

## Constructors

### constructor

• **new EditorSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:33259](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33259)

## Properties

### AutoScalabilityWorkScaleAmount

• **AutoScalabilityWorkScaleAmount**: `number`

#### Defined in

[ue/ue.d.ts:33269](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33269)

___

### CompletedSurveys

• **CompletedSurveys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Defined in

[ue/ue.d.ts:33267](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33267)

___

### CreatedProjectPaths

• **CreatedProjectPaths**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:33265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33265)

___

### InProgressSurveys

• **InProgressSurveys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Defined in

[ue/ue.d.ts:33268](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33268)

___

### LocalDerivedDataCache

• **LocalDerivedDataCache**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

#### Defined in

[ue/ue.d.ts:33262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33262)

___

### RecentlyOpenedProjectFiles

• **RecentlyOpenedProjectFiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:33264](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33264)

___

### SharedDerivedDataCache

• **SharedDerivedDataCache**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

#### Defined in

[ue/ue.d.ts:33263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33263)

___

### \_\_tid\_EditorSettings\_\_

• **\_\_tid\_EditorSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:33274](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33274)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bCopyStarterContentPreference

• **bCopyStarterContentPreference**: `boolean`

#### Defined in

[ue/ue.d.ts:33266](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33266)

___

### bEditorAnalyticsEnabled

• **bEditorAnalyticsEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:33261](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33261)

___

### bLoadTheMostRecentlyLoadedProjectAtStartup

• **bLoadTheMostRecentlyLoadedProjectAtStartup**: `boolean`

#### Defined in

[ue/ue.d.ts:33260](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33260)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorSettings`](ue_ue.EditorSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorSettings`](ue_ue.EditorSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:33271](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33271)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorSettings`](ue_ue.EditorSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorSettings`](ue_ue.EditorSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:33272](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33272)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:33270](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33270)
