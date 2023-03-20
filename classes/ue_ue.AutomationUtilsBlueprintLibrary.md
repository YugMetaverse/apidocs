[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AutomationUtilsBlueprintLibrary

# Class: AutomationUtilsBlueprintLibrary

[ue/ue](../modules/ue_ue.md).AutomationUtilsBlueprintLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`AutomationUtilsBlueprintLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.AutomationUtilsBlueprintLibrary.md#constructor)

### Properties

- [\_\_tid\_AutomationUtilsBlueprintLibrary\_\_](ue_ue.AutomationUtilsBlueprintLibrary.md#__tid_automationutilsblueprintlibrary__)
- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.AutomationUtilsBlueprintLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.AutomationUtilsBlueprintLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AutomationUtilsBlueprintLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AutomationUtilsBlueprintLibrary.md#executeubergraph)
- [GetClass](ue_ue.AutomationUtilsBlueprintLibrary.md#getclass)
- [GetName](ue_ue.AutomationUtilsBlueprintLibrary.md#getname)
- [GetOuter](ue_ue.AutomationUtilsBlueprintLibrary.md#getouter)
- [GetWorld](ue_ue.AutomationUtilsBlueprintLibrary.md#getworld)
- [Find](ue_ue.AutomationUtilsBlueprintLibrary.md#find)
- [Load](ue_ue.AutomationUtilsBlueprintLibrary.md#load)
- [StaticClass](ue_ue.AutomationUtilsBlueprintLibrary.md#staticclass)
- [TakeGameplayAutomationScreenshot](ue_ue.AutomationUtilsBlueprintLibrary.md#takegameplayautomationscreenshot)

## Constructors

### constructor

• **new AutomationUtilsBlueprintLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_AutomationUtilsBlueprintLibrary\_\_

• **\_\_tid\_AutomationUtilsBlueprintLibrary\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AutomationUtilsBlueprintLibrary`](ue_ue.AutomationUtilsBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AutomationUtilsBlueprintLibrary`](ue_ue.AutomationUtilsBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AutomationUtilsBlueprintLibrary`](ue_ue.AutomationUtilsBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AutomationUtilsBlueprintLibrary`](ue_ue.AutomationUtilsBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

___

### TakeGameplayAutomationScreenshot

▸ `Static` **TakeGameplayAutomationScreenshot**(`ScreenshotName`, `MaxGlobalError?`, `MaxLocalError?`, `MapNameOverride?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScreenshotName` | `string` |
| `MaxGlobalError?` | `number` |
| `MaxLocalError?` | `number` |
| `MapNameOverride?` | `string` |

#### Returns

`void`
