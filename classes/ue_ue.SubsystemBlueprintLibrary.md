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

#### Defined in

[ue/ue.d.ts:62691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62691)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SubsystemBlueprintLibrary\_\_

• **\_\_tid\_SubsystemBlueprintLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:62701](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62701)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:62698](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62698)

___

### GetEngineSubsystem

▸ `Static` **GetEngineSubsystem**(`Class`): [`EngineSubsystem`](ue_ue.EngineSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Class` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`EngineSubsystem`](ue_ue.EngineSubsystem.md)

#### Defined in

[ue/ue.d.ts:62692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62692)

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

#### Defined in

[ue/ue.d.ts:62693](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62693)

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

#### Defined in

[ue/ue.d.ts:62695](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62695)

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

#### Defined in

[ue/ue.d.ts:62694](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62694)

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

#### Defined in

[ue/ue.d.ts:62696](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62696)

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

#### Defined in

[ue/ue.d.ts:62699](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62699)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:62697](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L62697)
