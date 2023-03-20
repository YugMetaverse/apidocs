[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameMapsSettings

# Class: GameMapsSettings

[ue/ue](../modules/ue_ue.md).GameMapsSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`GameMapsSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.GameMapsSettings.md#constructor)

### Properties

- [EditorStartupMap](ue_ue.GameMapsSettings.md#editorstartupmap)
- [FourPlayerSplitscreenLayout](ue_ue.GameMapsSettings.md#fourplayersplitscreenlayout)
- [GameDefaultMap](ue_ue.GameMapsSettings.md#gamedefaultmap)
- [GameInstanceClass](ue_ue.GameMapsSettings.md#gameinstanceclass)
- [GameModeClassAliases](ue_ue.GameMapsSettings.md#gamemodeclassaliases)
- [GameModeMapPrefixes](ue_ue.GameMapsSettings.md#gamemodemapprefixes)
- [GlobalDefaultGameMode](ue_ue.GameMapsSettings.md#globaldefaultgamemode)
- [GlobalDefaultServerGameMode](ue_ue.GameMapsSettings.md#globaldefaultservergamemode)
- [LocalMapOptions](ue_ue.GameMapsSettings.md#localmapoptions)
- [ServerDefaultMap](ue_ue.GameMapsSettings.md#serverdefaultmap)
- [ThreePlayerSplitscreenLayout](ue_ue.GameMapsSettings.md#threeplayersplitscreenlayout)
- [TransitionMap](ue_ue.GameMapsSettings.md#transitionmap)
- [TwoPlayerSplitscreenLayout](ue_ue.GameMapsSettings.md#twoplayersplitscreenlayout)
- [\_\_tid\_GameMapsSettings\_\_](ue_ue.GameMapsSettings.md#__tid_gamemapssettings__)
- [\_\_tid\_Object\_\_](ue_ue.GameMapsSettings.md#__tid_object__)
- [bOffsetPlayerGamepadIds](ue_ue.GameMapsSettings.md#boffsetplayergamepadids)
- [bUseSplitscreen](ue_ue.GameMapsSettings.md#busesplitscreen)

### Methods

- [CreateDefaultSubobject](ue_ue.GameMapsSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GameMapsSettings.md#executeubergraph)
- [GetClass](ue_ue.GameMapsSettings.md#getclass)
- [GetName](ue_ue.GameMapsSettings.md#getname)
- [GetOuter](ue_ue.GameMapsSettings.md#getouter)
- [GetSkipAssigningGamepadToPlayer1](ue_ue.GameMapsSettings.md#getskipassigninggamepadtoplayer1)
- [GetWorld](ue_ue.GameMapsSettings.md#getworld)
- [SetSkipAssigningGamepadToPlayer1](ue_ue.GameMapsSettings.md#setskipassigninggamepadtoplayer1)
- [Find](ue_ue.GameMapsSettings.md#find)
- [GetGameMapsSettings](ue_ue.GameMapsSettings.md#getgamemapssettings)
- [Load](ue_ue.GameMapsSettings.md#load)
- [StaticClass](ue_ue.GameMapsSettings.md#staticclass)

## Constructors

### constructor

• **new GameMapsSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### EditorStartupMap

• **EditorStartupMap**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### FourPlayerSplitscreenLayout

• **FourPlayerSplitscreenLayout**: [`EFourPlayerSplitScreenType`](../enums/ue_ue.EFourPlayerSplitScreenType.md)

___

### GameDefaultMap

• **GameDefaultMap**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### GameInstanceClass

• **GameInstanceClass**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### GameModeClassAliases

• **GameModeClassAliases**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameModeName`](ue_ue.GameModeName.md)\>

___

### GameModeMapPrefixes

• **GameModeMapPrefixes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GameModeName`](ue_ue.GameModeName.md)\>

___

### GlobalDefaultGameMode

• **GlobalDefaultGameMode**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### GlobalDefaultServerGameMode

• **GlobalDefaultServerGameMode**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### LocalMapOptions

• **LocalMapOptions**: `string`

___

### ServerDefaultMap

• **ServerDefaultMap**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### ThreePlayerSplitscreenLayout

• **ThreePlayerSplitscreenLayout**: [`EThreePlayerSplitScreenType`](../enums/ue_ue.EThreePlayerSplitScreenType.md)

___

### TransitionMap

• **TransitionMap**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### TwoPlayerSplitscreenLayout

• **TwoPlayerSplitscreenLayout**: [`ETwoPlayerSplitScreenType`](../enums/ue_ue.ETwoPlayerSplitScreenType.md)

___

### \_\_tid\_GameMapsSettings\_\_

• **\_\_tid\_GameMapsSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bOffsetPlayerGamepadIds

• **bOffsetPlayerGamepadIds**: `boolean`

___

### bUseSplitscreen

• **bUseSplitscreen**: `boolean`

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

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

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

### GetSkipAssigningGamepadToPlayer1

▸ **GetSkipAssigningGamepadToPlayer1**(): `boolean`

#### Returns

`boolean`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### SetSkipAssigningGamepadToPlayer1

▸ **SetSkipAssigningGamepadToPlayer1**(`bSkipFirstPlayer?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bSkipFirstPlayer?` | `boolean` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameMapsSettings`](ue_ue.GameMapsSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameMapsSettings`](ue_ue.GameMapsSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### GetGameMapsSettings

▸ `Static` **GetGameMapsSettings**(): [`GameMapsSettings`](ue_ue.GameMapsSettings.md)

#### Returns

[`GameMapsSettings`](ue_ue.GameMapsSettings.md)

___

### Load

▸ `Static` **Load**(`InName`): [`GameMapsSettings`](ue_ue.GameMapsSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameMapsSettings`](ue_ue.GameMapsSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
