[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AndroidPermissionFunctionLibrary

# Class: AndroidPermissionFunctionLibrary

[ue/ue](../modules/ue_ue.md).AndroidPermissionFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`AndroidPermissionFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.AndroidPermissionFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_AndroidPermissionFunctionLibrary\_\_](ue_ue.AndroidPermissionFunctionLibrary.md#__tid_androidpermissionfunctionlibrary__)
- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.AndroidPermissionFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.AndroidPermissionFunctionLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AndroidPermissionFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AndroidPermissionFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.AndroidPermissionFunctionLibrary.md#getclass)
- [GetName](ue_ue.AndroidPermissionFunctionLibrary.md#getname)
- [GetOuter](ue_ue.AndroidPermissionFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.AndroidPermissionFunctionLibrary.md#getworld)
- [AcquirePermissions](ue_ue.AndroidPermissionFunctionLibrary.md#acquirepermissions)
- [CheckPermission](ue_ue.AndroidPermissionFunctionLibrary.md#checkpermission)
- [Find](ue_ue.AndroidPermissionFunctionLibrary.md#find)
- [Load](ue_ue.AndroidPermissionFunctionLibrary.md#load)
- [StaticClass](ue_ue.AndroidPermissionFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new AndroidPermissionFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_AndroidPermissionFunctionLibrary\_\_

• **\_\_tid\_AndroidPermissionFunctionLibrary\_\_**: `boolean`

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

### AcquirePermissions

▸ `Static` **AcquirePermissions**(`permissions`): [`AndroidPermissionCallbackProxy`](ue_ue.AndroidPermissionCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `permissions` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

[`AndroidPermissionCallbackProxy`](ue_ue.AndroidPermissionCallbackProxy.md)

___

### CheckPermission

▸ `Static` **CheckPermission**(`permission`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `permission` | `string` |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AndroidPermissionFunctionLibrary`](ue_ue.AndroidPermissionFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AndroidPermissionFunctionLibrary`](ue_ue.AndroidPermissionFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AndroidPermissionFunctionLibrary`](ue_ue.AndroidPermissionFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AndroidPermissionFunctionLibrary`](ue_ue.AndroidPermissionFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
