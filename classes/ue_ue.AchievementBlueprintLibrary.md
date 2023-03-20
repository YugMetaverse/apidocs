[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AchievementBlueprintLibrary

# Class: AchievementBlueprintLibrary

[ue/ue](../modules/ue_ue.md).AchievementBlueprintLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`AchievementBlueprintLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.AchievementBlueprintLibrary.md#constructor)

### Properties

- [\_\_tid\_AchievementBlueprintLibrary\_\_](ue_ue.AchievementBlueprintLibrary.md#__tid_achievementblueprintlibrary__)
- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.AchievementBlueprintLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.AchievementBlueprintLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AchievementBlueprintLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AchievementBlueprintLibrary.md#executeubergraph)
- [GetClass](ue_ue.AchievementBlueprintLibrary.md#getclass)
- [GetName](ue_ue.AchievementBlueprintLibrary.md#getname)
- [GetOuter](ue_ue.AchievementBlueprintLibrary.md#getouter)
- [GetWorld](ue_ue.AchievementBlueprintLibrary.md#getworld)
- [Find](ue_ue.AchievementBlueprintLibrary.md#find)
- [GetCachedAchievementDescription](ue_ue.AchievementBlueprintLibrary.md#getcachedachievementdescription)
- [GetCachedAchievementProgress](ue_ue.AchievementBlueprintLibrary.md#getcachedachievementprogress)
- [Load](ue_ue.AchievementBlueprintLibrary.md#load)
- [StaticClass](ue_ue.AchievementBlueprintLibrary.md#staticclass)

## Constructors

### constructor

• **new AchievementBlueprintLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_AchievementBlueprintLibrary\_\_

• **\_\_tid\_AchievementBlueprintLibrary\_\_**: `boolean`

___

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AchievementBlueprintLibrary`](ue_ue.AchievementBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AchievementBlueprintLibrary`](ue_ue.AchievementBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetCachedAchievementDescription

▸ `Static` **GetCachedAchievementDescription**(`WorldContextObject`, `PlayerController`, `AchievementID`, `bFoundID`, `Title`, `LockedDescription`, `UnlockedDescription`, `bHidden`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `AchievementID` | `string` |
| `bFoundID` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `Title` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `LockedDescription` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `UnlockedDescription` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `bHidden` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

___

### GetCachedAchievementProgress

▸ `Static` **GetCachedAchievementProgress**(`WorldContextObject`, `PlayerController`, `AchievementID`, `bFoundID`, `Progress`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `AchievementID` | `string` |
| `bFoundID` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `Progress` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### Load

▸ `Static` **Load**(`InName`): [`AchievementBlueprintLibrary`](ue_ue.AchievementBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AchievementBlueprintLibrary`](ue_ue.AchievementBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
