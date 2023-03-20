[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FunctionalTestingManager

# Class: FunctionalTestingManager

[ue/ue](../modules/ue_ue.md).FunctionalTestingManager

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`FunctionalTestingManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.FunctionalTestingManager.md#constructor)

### Properties

- [AllTests](ue_ue.FunctionalTestingManager.md#alltests)
- [OnSetupTests](ue_ue.FunctionalTestingManager.md#onsetuptests)
- [OnTestsBegin](ue_ue.FunctionalTestingManager.md#ontestsbegin)
- [OnTestsComplete](ue_ue.FunctionalTestingManager.md#ontestscomplete)
- [TestsLeft](ue_ue.FunctionalTestingManager.md#testsleft)
- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.FunctionalTestingManager.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_FunctionalTestingManager\_\_](ue_ue.FunctionalTestingManager.md#__tid_functionaltestingmanager__)
- [\_\_tid\_Object\_\_](ue_ue.FunctionalTestingManager.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.FunctionalTestingManager.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FunctionalTestingManager.md#executeubergraph)
- [GetClass](ue_ue.FunctionalTestingManager.md#getclass)
- [GetName](ue_ue.FunctionalTestingManager.md#getname)
- [GetOuter](ue_ue.FunctionalTestingManager.md#getouter)
- [GetWorld](ue_ue.FunctionalTestingManager.md#getworld)
- [Find](ue_ue.FunctionalTestingManager.md#find)
- [Load](ue_ue.FunctionalTestingManager.md#load)
- [RunAllFunctionalTests](ue_ue.FunctionalTestingManager.md#runallfunctionaltests)
- [StaticClass](ue_ue.FunctionalTestingManager.md#staticclass)

## Constructors

### constructor

• **new FunctionalTestingManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### AllTests

• **AllTests**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FunctionalTest`](ue_ue.FunctionalTest.md)\>

___

### OnSetupTests

• **OnSetupTests**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnTestsBegin

• **OnTestsBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnTestsComplete

• **OnTestsComplete**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### TestsLeft

• **TestsLeft**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FunctionalTest`](ue_ue.FunctionalTest.md)\>

___

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_FunctionalTestingManager\_\_

• **\_\_tid\_FunctionalTestingManager\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FunctionalTestingManager`](ue_ue.FunctionalTestingManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FunctionalTestingManager`](ue_ue.FunctionalTestingManager.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FunctionalTestingManager`](ue_ue.FunctionalTestingManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FunctionalTestingManager`](ue_ue.FunctionalTestingManager.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### RunAllFunctionalTests

▸ `Static` **RunAllFunctionalTests**(`WorldContextObject`, `bNewLog?`, `bRunLooped?`, `FailedTestsReproString?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `bNewLog?` | `boolean` |
| `bRunLooped?` | `boolean` |
| `FailedTestsReproString?` | `string` |

#### Returns

`boolean`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
