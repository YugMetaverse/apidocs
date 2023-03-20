[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapPrivilegesFunctionLibrary

# Class: MagicLeapPrivilegesFunctionLibrary

[ue/ue](../modules/ue_ue.md).MagicLeapPrivilegesFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`MagicLeapPrivilegesFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_MagicLeapPrivilegesFunctionLibrary\_\_](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#__tid_magicleapprivilegesfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#getclass)
- [GetName](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#getname)
- [GetOuter](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#getworld)
- [CheckPrivilege](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#checkprivilege)
- [Find](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#find)
- [Load](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#load)
- [RequestPrivilege](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#requestprivilege)
- [RequestPrivilegeAsync](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#requestprivilegeasync)
- [StaticClass](ue_ue.MagicLeapPrivilegesFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new MagicLeapPrivilegesFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_MagicLeapPrivilegesFunctionLibrary\_\_

• **\_\_tid\_MagicLeapPrivilegesFunctionLibrary\_\_**: `boolean`

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

### CheckPrivilege

▸ `Static` **CheckPrivilege**(`Privilege`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Privilege` | [`EMagicLeapPrivilege`](../enums/ue_ue.EMagicLeapPrivilege.md) |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MagicLeapPrivilegesFunctionLibrary`](ue_ue.MagicLeapPrivilegesFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MagicLeapPrivilegesFunctionLibrary`](ue_ue.MagicLeapPrivilegesFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MagicLeapPrivilegesFunctionLibrary`](ue_ue.MagicLeapPrivilegesFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MagicLeapPrivilegesFunctionLibrary`](ue_ue.MagicLeapPrivilegesFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### RequestPrivilege

▸ `Static` **RequestPrivilege**(`Privilege`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Privilege` | [`EMagicLeapPrivilege`](../enums/ue_ue.EMagicLeapPrivilege.md) |

#### Returns

`boolean`

___

### RequestPrivilegeAsync

▸ `Static` **RequestPrivilegeAsync**(`Privilege`, `ResultDelegate`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Privilege` | [`EMagicLeapPrivilege`](../enums/ue_ue.EMagicLeapPrivilege.md) |
| `ResultDelegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`RequestedPrivilege`: [`EMagicLeapPrivilege`](../enums/ue_ue.EMagicLeapPrivilege.md), `WasGranted`: `boolean`) => `void`\> |

#### Returns

`boolean`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
