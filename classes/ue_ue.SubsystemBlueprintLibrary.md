[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SubsystemBlueprintLibrary

# Class: SubsystemBlueprintLibrary

[ue/ue](../modules/ue_ue.md).SubsystemBlueprintLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`SubsystemBlueprintLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.SubsystemBlueprintLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.SubsystemBlueprintLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.SubsystemBlueprintLibrary.md#__tid_object__)
- [\_\_tid\_SubsystemBlueprintLibrary\_\_](ue_ue.SubsystemBlueprintLibrary.md#__tid_subsystemblueprintlibrary__)

### Methods

- [CreateDefaultSubobject](ue_ue.SubsystemBlueprintLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SubsystemBlueprintLibrary.md#executeubergraph)
- [GetClass](ue_ue.SubsystemBlueprintLibrary.md#getclass)
- [GetName](ue_ue.SubsystemBlueprintLibrary.md#getname)
- [GetOuter](ue_ue.SubsystemBlueprintLibrary.md#getouter)
- [GetWorld](ue_ue.SubsystemBlueprintLibrary.md#getworld)
- [Find](ue_ue.SubsystemBlueprintLibrary.md#find)
- [GetEngineSubsystem](ue_ue.SubsystemBlueprintLibrary.md#getenginesubsystem)
- [GetGameInstanceSubsystem](ue_ue.SubsystemBlueprintLibrary.md#getgameinstancesubsystem)
- [GetLocalPlayerSubSystemFromPlayerController](ue_ue.SubsystemBlueprintLibrary.md#getlocalplayersubsystemfromplayercontroller)
- [GetLocalPlayerSubsystem](ue_ue.SubsystemBlueprintLibrary.md#getlocalplayersubsystem)
- [GetWorldSubsystem](ue_ue.SubsystemBlueprintLibrary.md#getworldsubsystem)
- [Load](ue_ue.SubsystemBlueprintLibrary.md#load)
- [StaticClass](ue_ue.SubsystemBlueprintLibrary.md#staticclass)

## Constructors

### constructor

• **new SubsystemBlueprintLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_SubsystemBlueprintLibrary\_\_

• **\_\_tid\_SubsystemBlueprintLibrary\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SubsystemBlueprintLibrary`](ue_ue.SubsystemBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SubsystemBlueprintLibrary`](ue_ue.SubsystemBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetEngineSubsystem

▸ `Static` **GetEngineSubsystem**(`Class`): [`EngineSubsystem`](ue_ue.EngineSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Class` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`EngineSubsystem`](ue_ue.EngineSubsystem.md)

___

### GetGameInstanceSubsystem

▸ `Static` **GetGameInstanceSubsystem**(`ContextObject`, `Class`): [`GameInstanceSubsystem`](ue_ue.GameInstanceSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Class` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`GameInstanceSubsystem`](ue_ue.GameInstanceSubsystem.md)

___

### GetLocalPlayerSubSystemFromPlayerController

▸ `Static` **GetLocalPlayerSubSystemFromPlayerController**(`PlayerController`, `Class`): [`LocalPlayerSubsystem`](ue_ue.LocalPlayerSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `Class` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`LocalPlayerSubsystem`](ue_ue.LocalPlayerSubsystem.md)

___

### GetLocalPlayerSubsystem

▸ `Static` **GetLocalPlayerSubsystem**(`ContextObject`, `Class`): [`LocalPlayerSubsystem`](ue_ue.LocalPlayerSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Class` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`LocalPlayerSubsystem`](ue_ue.LocalPlayerSubsystem.md)

___

### GetWorldSubsystem

▸ `Static` **GetWorldSubsystem**(`ContextObject`, `Class`): [`WorldSubsystem`](ue_ue.WorldSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Class` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`WorldSubsystem`](ue_ue.WorldSubsystem.md)

___

### Load

▸ `Static` **Load**(`InName`): [`SubsystemBlueprintLibrary`](ue_ue.SubsystemBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SubsystemBlueprintLibrary`](ue_ue.SubsystemBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
