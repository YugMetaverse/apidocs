[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapHandMeshingFunctionLibrary

# Class: MagicLeapHandMeshingFunctionLibrary

[ue/ue](../modules/ue_ue.md).MagicLeapHandMeshingFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`MagicLeapHandMeshingFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_MagicLeapHandMeshingFunctionLibrary\_\_](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#__tid_magicleaphandmeshingfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#getclass)
- [GetName](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#getname)
- [GetOuter](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#getworld)
- [ConnectMRMesh](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#connectmrmesh)
- [CreateClient](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#createclient)
- [DestroyClient](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#destroyclient)
- [DisconnectMRMesh](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#disconnectmrmesh)
- [Find](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#find)
- [Load](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#load)
- [StaticClass](ue_ue.MagicLeapHandMeshingFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new MagicLeapHandMeshingFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_MagicLeapHandMeshingFunctionLibrary\_\_

• **\_\_tid\_MagicLeapHandMeshingFunctionLibrary\_\_**: `boolean`

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

### ConnectMRMesh

▸ `Static` **ConnectMRMesh**(`InMRMeshPtr`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMRMeshPtr` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MRMeshComponent`](ue_ue.MRMeshComponent.md)\> |

#### Returns

`boolean`

___

### CreateClient

▸ `Static` **CreateClient**(): `boolean`

#### Returns

`boolean`

___

### DestroyClient

▸ `Static` **DestroyClient**(): `boolean`

#### Returns

`boolean`

___

### DisconnectMRMesh

▸ `Static` **DisconnectMRMesh**(`InMRMeshPtr`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMRMeshPtr` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MRMeshComponent`](ue_ue.MRMeshComponent.md)\> |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MagicLeapHandMeshingFunctionLibrary`](ue_ue.MagicLeapHandMeshingFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MagicLeapHandMeshingFunctionLibrary`](ue_ue.MagicLeapHandMeshingFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MagicLeapHandMeshingFunctionLibrary`](ue_ue.MagicLeapHandMeshingFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MagicLeapHandMeshingFunctionLibrary`](ue_ue.MagicLeapHandMeshingFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
