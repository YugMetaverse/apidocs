[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LocalPlayer

# Class: LocalPlayer

[ue/ue](../modules/ue_ue.md).LocalPlayer

## Hierarchy

- [`Player`](ue_ue.Player.md)

  ↳ **`LocalPlayer`**

## Table of contents

### Constructors

- [constructor](ue_ue.LocalPlayer.md#constructor)

### Properties

- [AspectRatioAxisConstraint](ue_ue.LocalPlayer.md#aspectratioaxisconstraint)
- [ConfiguredInternetSpeed](ue_ue.LocalPlayer.md#configuredinternetspeed)
- [ConfiguredLanSpeed](ue_ue.LocalPlayer.md#configuredlanspeed)
- [ControllerId](ue_ue.LocalPlayer.md#controllerid)
- [CurrentNetSpeed](ue_ue.LocalPlayer.md#currentnetspeed)
- [PendingLevelPlayerControllerClass](ue_ue.LocalPlayer.md#pendinglevelplayercontrollerclass)
- [PlayerController](ue_ue.LocalPlayer.md#playercontroller)
- [ViewportClient](ue_ue.LocalPlayer.md#viewportclient)
- [\_\_tid\_LocalPlayer\_\_](ue_ue.LocalPlayer.md#__tid_localplayer__)
- [\_\_tid\_Object\_\_](ue_ue.LocalPlayer.md#__tid_object__)
- [\_\_tid\_Player\_\_](ue_ue.LocalPlayer.md#__tid_player__)
- [bSentSplitJoin](ue_ue.LocalPlayer.md#bsentsplitjoin)

### Methods

- [CreateDefaultSubobject](ue_ue.LocalPlayer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LocalPlayer.md#executeubergraph)
- [GetClass](ue_ue.LocalPlayer.md#getclass)
- [GetName](ue_ue.LocalPlayer.md#getname)
- [GetOuter](ue_ue.LocalPlayer.md#getouter)
- [GetWorld](ue_ue.LocalPlayer.md#getworld)
- [Find](ue_ue.LocalPlayer.md#find)
- [Load](ue_ue.LocalPlayer.md#load)
- [StaticClass](ue_ue.LocalPlayer.md#staticclass)

## Constructors

### constructor

• **new LocalPlayer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Player](ue_ue.Player.md).[constructor](ue_ue.Player.md#constructor)

## Properties

### AspectRatioAxisConstraint

• **AspectRatioAxisConstraint**: [`EAspectRatioAxisConstraint`](../enums/ue_ue.EAspectRatioAxisConstraint.md)

___

### ConfiguredInternetSpeed

• **ConfiguredInternetSpeed**: `number`

#### Inherited from

[Player](ue_ue.Player.md).[ConfiguredInternetSpeed](ue_ue.Player.md#configuredinternetspeed)

___

### ConfiguredLanSpeed

• **ConfiguredLanSpeed**: `number`

#### Inherited from

[Player](ue_ue.Player.md).[ConfiguredLanSpeed](ue_ue.Player.md#configuredlanspeed)

___

### ControllerId

• **ControllerId**: `number`

___

### CurrentNetSpeed

• **CurrentNetSpeed**: `number`

#### Inherited from

[Player](ue_ue.Player.md).[CurrentNetSpeed](ue_ue.Player.md#currentnetspeed)

___

### PendingLevelPlayerControllerClass

• **PendingLevelPlayerControllerClass**: [`Class`](ue_ue.Class.md)

___

### PlayerController

• **PlayerController**: [`PlayerController`](ue_ue.PlayerController.md)

#### Inherited from

[Player](ue_ue.Player.md).[PlayerController](ue_ue.Player.md#playercontroller)

___

### ViewportClient

• **ViewportClient**: [`GameViewportClient`](ue_ue.GameViewportClient.md)

___

### \_\_tid\_LocalPlayer\_\_

• **\_\_tid\_LocalPlayer\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Player](ue_ue.Player.md).[__tid_Object__](ue_ue.Player.md#__tid_object__)

___

### \_\_tid\_Player\_\_

• **\_\_tid\_Player\_\_**: `boolean`

#### Inherited from

[Player](ue_ue.Player.md).[__tid_Player__](ue_ue.Player.md#__tid_player__)

___

### bSentSplitJoin

• **bSentSplitJoin**: `boolean`

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

[Player](ue_ue.Player.md).[CreateDefaultSubobject](ue_ue.Player.md#createdefaultsubobject)

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

[Player](ue_ue.Player.md).[ExecuteUbergraph](ue_ue.Player.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Player](ue_ue.Player.md).[GetClass](ue_ue.Player.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Player](ue_ue.Player.md).[GetName](ue_ue.Player.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Player](ue_ue.Player.md).[GetOuter](ue_ue.Player.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Player](ue_ue.Player.md).[GetWorld](ue_ue.Player.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Overrides

[Player](ue_ue.Player.md).[Find](ue_ue.Player.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LocalPlayer`](ue_ue.LocalPlayer.md)

#### Overrides

[Player](ue_ue.Player.md).[Load](ue_ue.Player.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Player](ue_ue.Player.md).[StaticClass](ue_ue.Player.md#staticclass)
