[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapImageTrackerFunctionLibrary

# Class: MagicLeapImageTrackerFunctionLibrary

[ue/ue](../modules/ue_ue.md).MagicLeapImageTrackerFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`MagicLeapImageTrackerFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_MagicLeapImageTrackerFunctionLibrary\_\_](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#__tid_magicleapimagetrackerfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#getclass)
- [GetName](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#getname)
- [GetOuter](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#getworld)
- [EnableImageTracking](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#enableimagetracking)
- [Find](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#find)
- [GetMaxSimultaneousTargets](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#getmaxsimultaneoustargets)
- [IsImageTrackingEnabled](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#isimagetrackingenabled)
- [Load](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#load)
- [SetMaxSimultaneousTargets](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#setmaxsimultaneoustargets)
- [StaticClass](ue_ue.MagicLeapImageTrackerFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new MagicLeapImageTrackerFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_MagicLeapImageTrackerFunctionLibrary\_\_

• **\_\_tid\_MagicLeapImageTrackerFunctionLibrary\_\_**: `boolean`

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

### EnableImageTracking

▸ `Static` **EnableImageTracking**(`bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnable` | `boolean` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MagicLeapImageTrackerFunctionLibrary`](ue_ue.MagicLeapImageTrackerFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MagicLeapImageTrackerFunctionLibrary`](ue_ue.MagicLeapImageTrackerFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetMaxSimultaneousTargets

▸ `Static` **GetMaxSimultaneousTargets**(): `number`

#### Returns

`number`

___

### IsImageTrackingEnabled

▸ `Static` **IsImageTrackingEnabled**(): `boolean`

#### Returns

`boolean`

___

### Load

▸ `Static` **Load**(`InName`): [`MagicLeapImageTrackerFunctionLibrary`](ue_ue.MagicLeapImageTrackerFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MagicLeapImageTrackerFunctionLibrary`](ue_ue.MagicLeapImageTrackerFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### SetMaxSimultaneousTargets

▸ `Static` **SetMaxSimultaneousTargets**(`MaxSimultaneousTargets`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaxSimultaneousTargets` | `number` |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
