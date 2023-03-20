[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WorldExtensionMethods

# Class: WorldExtensionMethods

[ue/ue](../modules/ue_ue.md).WorldExtensionMethods

## Hierarchy

- [`ExtensionMethods`](ue_ue.ExtensionMethods.md)

  ↳ **`WorldExtensionMethods`**

## Table of contents

### Constructors

- [constructor](ue_ue.WorldExtensionMethods.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.WorldExtensionMethods.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_ExtensionMethods\_\_](ue_ue.WorldExtensionMethods.md#__tid_extensionmethods__)
- [\_\_tid\_Object\_\_](ue_ue.WorldExtensionMethods.md#__tid_object__)
- [\_\_tid\_WorldExtensionMethods\_\_](ue_ue.WorldExtensionMethods.md#__tid_worldextensionmethods__)

### Methods

- [CreateDefaultSubobject](ue_ue.WorldExtensionMethods.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.WorldExtensionMethods.md#executeubergraph)
- [GetClass](ue_ue.WorldExtensionMethods.md#getclass)
- [GetName](ue_ue.WorldExtensionMethods.md#getname)
- [GetOuter](ue_ue.WorldExtensionMethods.md#getouter)
- [GetWorld](ue_ue.WorldExtensionMethods.md#getworld)
- [Find](ue_ue.WorldExtensionMethods.md#find)
- [Load](ue_ue.WorldExtensionMethods.md#load)
- [SpawnActor](ue_ue.WorldExtensionMethods.md#spawnactor)
- [StaticClass](ue_ue.WorldExtensionMethods.md#staticclass)

## Constructors

### constructor

• **new WorldExtensionMethods**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ExtensionMethods](ue_ue.ExtensionMethods.md).[constructor](ue_ue.ExtensionMethods.md#constructor)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[ExtensionMethods](ue_ue.ExtensionMethods.md).[__tid_BlueprintFunctionLibrary__](ue_ue.ExtensionMethods.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_ExtensionMethods\_\_

• **\_\_tid\_ExtensionMethods\_\_**: `boolean`

#### Inherited from

[ExtensionMethods](ue_ue.ExtensionMethods.md).[__tid_ExtensionMethods__](ue_ue.ExtensionMethods.md#__tid_extensionmethods__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ExtensionMethods](ue_ue.ExtensionMethods.md).[__tid_Object__](ue_ue.ExtensionMethods.md#__tid_object__)

___

### \_\_tid\_WorldExtensionMethods\_\_

• **\_\_tid\_WorldExtensionMethods\_\_**: `boolean`

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

[ExtensionMethods](ue_ue.ExtensionMethods.md).[CreateDefaultSubobject](ue_ue.ExtensionMethods.md#createdefaultsubobject)

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

[ExtensionMethods](ue_ue.ExtensionMethods.md).[ExecuteUbergraph](ue_ue.ExtensionMethods.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ExtensionMethods](ue_ue.ExtensionMethods.md).[GetClass](ue_ue.ExtensionMethods.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ExtensionMethods](ue_ue.ExtensionMethods.md).[GetName](ue_ue.ExtensionMethods.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ExtensionMethods](ue_ue.ExtensionMethods.md).[GetOuter](ue_ue.ExtensionMethods.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ExtensionMethods](ue_ue.ExtensionMethods.md).[GetWorld](ue_ue.ExtensionMethods.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`WorldExtensionMethods`](ue_ue.WorldExtensionMethods.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`WorldExtensionMethods`](ue_ue.WorldExtensionMethods.md)

#### Overrides

[ExtensionMethods](ue_ue.ExtensionMethods.md).[Find](ue_ue.ExtensionMethods.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`WorldExtensionMethods`](ue_ue.WorldExtensionMethods.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`WorldExtensionMethods`](ue_ue.WorldExtensionMethods.md)

#### Overrides

[ExtensionMethods](ue_ue.ExtensionMethods.md).[Load](ue_ue.ExtensionMethods.md#load)

___

### SpawnActor

▸ `Static` **SpawnActor**(`World`, `Class`, `Transform`, `SpawnCollisionHandlingOverride`, `Owner`, `Instigator`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `World` | [`$Nullable`](../modules/puerts.md#$nullable)<[`World`](ue_ue.World.md)\> |
| `Class` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `Transform` | [`Transform`](ue_ue_s.Transform.md) |
| `SpawnCollisionHandlingOverride` | [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md) |
| `Owner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `Instigator` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ExtensionMethods](ue_ue.ExtensionMethods.md).[StaticClass](ue_ue.ExtensionMethods.md#staticclass)
