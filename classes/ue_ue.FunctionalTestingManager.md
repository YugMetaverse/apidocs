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

#### Defined in

[ue/ue.d.ts:36483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36483)

## Properties

### AllTests

• **AllTests**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FunctionalTest`](ue_ue.FunctionalTest.md)\>

#### Defined in

[ue/ue.d.ts:36485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36485)

___

### OnSetupTests

• **OnSetupTests**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:36486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36486)

___

### OnTestsBegin

• **OnTestsBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:36488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36488)

___

### OnTestsComplete

• **OnTestsComplete**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:36487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36487)

___

### TestsLeft

• **TestsLeft**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FunctionalTest`](ue_ue.FunctionalTest.md)\>

#### Defined in

[ue/ue.d.ts:36484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36484)

___

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_FunctionalTestingManager\_\_

• **\_\_tid\_FunctionalTestingManager\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:36494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36494)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

#### Defined in

[ue/ue.d.ts:36491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36491)

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

#### Defined in

[ue/ue.d.ts:36492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36492)

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

#### Defined in

[ue/ue.d.ts:36489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36489)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:36490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36490)
