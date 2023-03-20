[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VisualLoggerKismetLibrary

# Class: VisualLoggerKismetLibrary

[ue/ue](../modules/ue_ue.md).VisualLoggerKismetLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`VisualLoggerKismetLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.VisualLoggerKismetLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.VisualLoggerKismetLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.VisualLoggerKismetLibrary.md#__tid_object__)
- [\_\_tid\_VisualLoggerKismetLibrary\_\_](ue_ue.VisualLoggerKismetLibrary.md#__tid_visualloggerkismetlibrary__)

### Methods

- [CreateDefaultSubobject](ue_ue.VisualLoggerKismetLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VisualLoggerKismetLibrary.md#executeubergraph)
- [GetClass](ue_ue.VisualLoggerKismetLibrary.md#getclass)
- [GetName](ue_ue.VisualLoggerKismetLibrary.md#getname)
- [GetOuter](ue_ue.VisualLoggerKismetLibrary.md#getouter)
- [GetWorld](ue_ue.VisualLoggerKismetLibrary.md#getworld)
- [EnableRecording](ue_ue.VisualLoggerKismetLibrary.md#enablerecording)
- [Find](ue_ue.VisualLoggerKismetLibrary.md#find)
- [Load](ue_ue.VisualLoggerKismetLibrary.md#load)
- [LogBox](ue_ue.VisualLoggerKismetLibrary.md#logbox)
- [LogLocation](ue_ue.VisualLoggerKismetLibrary.md#loglocation)
- [LogSegment](ue_ue.VisualLoggerKismetLibrary.md#logsegment)
- [LogText](ue_ue.VisualLoggerKismetLibrary.md#logtext)
- [RedirectVislog](ue_ue.VisualLoggerKismetLibrary.md#redirectvislog)
- [StaticClass](ue_ue.VisualLoggerKismetLibrary.md#staticclass)

## Constructors

### constructor

• **new VisualLoggerKismetLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_VisualLoggerKismetLibrary\_\_

• **\_\_tid\_VisualLoggerKismetLibrary\_\_**: `boolean`

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

### EnableRecording

▸ `Static` **EnableRecording**(`bEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnabled` | `boolean` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VisualLoggerKismetLibrary`](ue_ue.VisualLoggerKismetLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VisualLoggerKismetLibrary`](ue_ue.VisualLoggerKismetLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`VisualLoggerKismetLibrary`](ue_ue.VisualLoggerKismetLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VisualLoggerKismetLibrary`](ue_ue.VisualLoggerKismetLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### LogBox

▸ `Static` **LogBox**(`WorldContextObject`, `BoxShape`, `Text`, `ObjectColor?`, `LogCategory?`, `bAddToMessageLog?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `BoxShape` | [`Box`](ue_ue.Box.md) |
| `Text` | `string` |
| `ObjectColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `LogCategory?` | `string` |
| `bAddToMessageLog?` | `boolean` |

#### Returns

`void`

___

### LogLocation

▸ `Static` **LogLocation**(`WorldContextObject`, `Location`, `Text`, `ObjectColor?`, `Radius?`, `LogCategory?`, `bAddToMessageLog?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Text` | `string` |
| `ObjectColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `Radius?` | `number` |
| `LogCategory?` | `string` |
| `bAddToMessageLog?` | `boolean` |

#### Returns

`void`

___

### LogSegment

▸ `Static` **LogSegment**(`WorldContextObject`, `SegmentStart`, `SegmentEnd`, `Text`, `ObjectColor?`, `Thickness?`, `CategoryName?`, `bAddToMessageLog?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `SegmentStart` | [`Vector`](ue_ue_s.Vector.md) |
| `SegmentEnd` | [`Vector`](ue_ue_s.Vector.md) |
| `Text` | `string` |
| `ObjectColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `Thickness?` | `number` |
| `CategoryName?` | `string` |
| `bAddToMessageLog?` | `boolean` |

#### Returns

`void`

___

### LogText

▸ `Static` **LogText**(`WorldContextObject`, `Text`, `LogCategory?`, `bAddToMessageLog?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Text` | `string` |
| `LogCategory?` | `string` |
| `bAddToMessageLog?` | `boolean` |

#### Returns

`void`

___

### RedirectVislog

▸ `Static` **RedirectVislog**(`SourceOwner`, `DestinationOwner`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `DestinationOwner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
