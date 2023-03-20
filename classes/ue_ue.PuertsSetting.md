[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PuertsSetting

# Class: PuertsSetting

[ue/ue](../modules/ue_ue.md).PuertsSetting

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PuertsSetting`**

## Table of contents

### Constructors

- [constructor](ue_ue.PuertsSetting.md#constructor)

### Properties

- [AutoModeEnable](ue_ue.PuertsSetting.md#automodeenable)
- [DebugEnable](ue_ue.PuertsSetting.md#debugenable)
- [DebugPort](ue_ue.PuertsSetting.md#debugport)
- [IgnoreClassListOnDTS](ue_ue.PuertsSetting.md#ignoreclasslistondts)
- [IgnoreStructListOnDTS](ue_ue.PuertsSetting.md#ignorestructlistondts)
- [NumberOfJsEnv](ue_ue.PuertsSetting.md#numberofjsenv)
- [WaitDebugger](ue_ue.PuertsSetting.md#waitdebugger)
- [WaitDebuggerTimeout](ue_ue.PuertsSetting.md#waitdebuggertimeout)
- [WatchDisable](ue_ue.PuertsSetting.md#watchdisable)
- [\_\_tid\_Object\_\_](ue_ue.PuertsSetting.md#__tid_object__)
- [\_\_tid\_PuertsSetting\_\_](ue_ue.PuertsSetting.md#__tid_puertssetting__)

### Methods

- [CreateDefaultSubobject](ue_ue.PuertsSetting.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PuertsSetting.md#executeubergraph)
- [GetClass](ue_ue.PuertsSetting.md#getclass)
- [GetName](ue_ue.PuertsSetting.md#getname)
- [GetOuter](ue_ue.PuertsSetting.md#getouter)
- [GetWorld](ue_ue.PuertsSetting.md#getworld)
- [Find](ue_ue.PuertsSetting.md#find)
- [Load](ue_ue.PuertsSetting.md#load)
- [StaticClass](ue_ue.PuertsSetting.md#staticclass)

## Constructors

### constructor

• **new PuertsSetting**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AutoModeEnable

• **AutoModeEnable**: `boolean`

___

### DebugEnable

• **DebugEnable**: `boolean`

___

### DebugPort

• **DebugPort**: `number`

___

### IgnoreClassListOnDTS

• **IgnoreClassListOnDTS**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### IgnoreStructListOnDTS

• **IgnoreStructListOnDTS**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### NumberOfJsEnv

• **NumberOfJsEnv**: `number`

___

### WaitDebugger

• **WaitDebugger**: `boolean`

___

### WaitDebuggerTimeout

• **WaitDebuggerTimeout**: `number`

___

### WatchDisable

• **WatchDisable**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PuertsSetting\_\_

• **\_\_tid\_PuertsSetting\_\_**: `boolean`

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

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PuertsSetting`](ue_ue.PuertsSetting.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PuertsSetting`](ue_ue.PuertsSetting.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PuertsSetting`](ue_ue.PuertsSetting.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PuertsSetting`](ue_ue.PuertsSetting.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
