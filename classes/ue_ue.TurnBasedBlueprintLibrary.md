[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TurnBasedBlueprintLibrary

# Class: TurnBasedBlueprintLibrary

[ue/ue](../modules/ue_ue.md).TurnBasedBlueprintLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`TurnBasedBlueprintLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.TurnBasedBlueprintLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.TurnBasedBlueprintLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.TurnBasedBlueprintLibrary.md#__tid_object__)
- [\_\_tid\_TurnBasedBlueprintLibrary\_\_](ue_ue.TurnBasedBlueprintLibrary.md#__tid_turnbasedblueprintlibrary__)

### Methods

- [CreateDefaultSubobject](ue_ue.TurnBasedBlueprintLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TurnBasedBlueprintLibrary.md#executeubergraph)
- [GetClass](ue_ue.TurnBasedBlueprintLibrary.md#getclass)
- [GetName](ue_ue.TurnBasedBlueprintLibrary.md#getname)
- [GetOuter](ue_ue.TurnBasedBlueprintLibrary.md#getouter)
- [GetWorld](ue_ue.TurnBasedBlueprintLibrary.md#getworld)
- [Find](ue_ue.TurnBasedBlueprintLibrary.md#find)
- [GetIsMyTurn](ue_ue.TurnBasedBlueprintLibrary.md#getismyturn)
- [GetMyPlayerIndex](ue_ue.TurnBasedBlueprintLibrary.md#getmyplayerindex)
- [GetPlayerDisplayName](ue_ue.TurnBasedBlueprintLibrary.md#getplayerdisplayname)
- [Load](ue_ue.TurnBasedBlueprintLibrary.md#load)
- [RegisterTurnBasedMatchInterfaceObject](ue_ue.TurnBasedBlueprintLibrary.md#registerturnbasedmatchinterfaceobject)
- [StaticClass](ue_ue.TurnBasedBlueprintLibrary.md#staticclass)

## Constructors

### constructor

• **new TurnBasedBlueprintLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

___

### \_\_tid\_TurnBasedBlueprintLibrary\_\_

• **\_\_tid\_TurnBasedBlueprintLibrary\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TurnBasedBlueprintLibrary`](ue_ue.TurnBasedBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TurnBasedBlueprintLibrary`](ue_ue.TurnBasedBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetIsMyTurn

▸ `Static` **GetIsMyTurn**(`WorldContextObject`, `PlayerController`, `MatchID`, `bIsMyTurn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `MatchID` | `string` |
| `bIsMyTurn` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

___

### GetMyPlayerIndex

▸ `Static` **GetMyPlayerIndex**(`WorldContextObject`, `PlayerController`, `MatchID`, `PlayerIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `MatchID` | `string` |
| `PlayerIndex` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### GetPlayerDisplayName

▸ `Static` **GetPlayerDisplayName**(`WorldContextObject`, `PlayerController`, `MatchID`, `PlayerIndex`, `PlayerDisplayName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `MatchID` | `string` |
| `PlayerIndex` | `number` |
| `PlayerDisplayName` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

___

### Load

▸ `Static` **Load**(`InName`): [`TurnBasedBlueprintLibrary`](ue_ue.TurnBasedBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TurnBasedBlueprintLibrary`](ue_ue.TurnBasedBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### RegisterTurnBasedMatchInterfaceObject

▸ `Static` **RegisterTurnBasedMatchInterfaceObject**(`WorldContextObject`, `PlayerController`, `Object`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
