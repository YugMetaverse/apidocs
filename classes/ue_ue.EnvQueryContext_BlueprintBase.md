[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EnvQueryContext\_BlueprintBase

# Class: EnvQueryContext\_BlueprintBase

[ue/ue](../modules/ue_ue.md).EnvQueryContext_BlueprintBase

## Hierarchy

- [`EnvQueryContext`](ue_ue.EnvQueryContext.md)

  ↳ **`EnvQueryContext_BlueprintBase`**

## Table of contents

### Constructors

- [constructor](ue_ue.EnvQueryContext_BlueprintBase.md#constructor)

### Properties

- [\_\_tid\_EnvQueryContext\_BlueprintBase\_\_](ue_ue.EnvQueryContext_BlueprintBase.md#__tid_envquerycontext_blueprintbase__)
- [\_\_tid\_EnvQueryContext\_\_](ue_ue.EnvQueryContext_BlueprintBase.md#__tid_envquerycontext__)
- [\_\_tid\_Object\_\_](ue_ue.EnvQueryContext_BlueprintBase.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EnvQueryContext_BlueprintBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EnvQueryContext_BlueprintBase.md#executeubergraph)
- [GetClass](ue_ue.EnvQueryContext_BlueprintBase.md#getclass)
- [GetName](ue_ue.EnvQueryContext_BlueprintBase.md#getname)
- [GetOuter](ue_ue.EnvQueryContext_BlueprintBase.md#getouter)
- [GetWorld](ue_ue.EnvQueryContext_BlueprintBase.md#getworld)
- [ProvideActorsSet](ue_ue.EnvQueryContext_BlueprintBase.md#provideactorsset)
- [ProvideLocationsSet](ue_ue.EnvQueryContext_BlueprintBase.md#providelocationsset)
- [ProvideSingleActor](ue_ue.EnvQueryContext_BlueprintBase.md#providesingleactor)
- [ProvideSingleLocation](ue_ue.EnvQueryContext_BlueprintBase.md#providesinglelocation)
- [Find](ue_ue.EnvQueryContext_BlueprintBase.md#find)
- [Load](ue_ue.EnvQueryContext_BlueprintBase.md#load)
- [StaticClass](ue_ue.EnvQueryContext_BlueprintBase.md#staticclass)

## Constructors

### constructor

• **new EnvQueryContext_BlueprintBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EnvQueryContext](ue_ue.EnvQueryContext.md).[constructor](ue_ue.EnvQueryContext.md#constructor)

## Properties

### \_\_tid\_EnvQueryContext\_BlueprintBase\_\_

• **\_\_tid\_EnvQueryContext\_BlueprintBase\_\_**: `boolean`

___

### \_\_tid\_EnvQueryContext\_\_

• **\_\_tid\_EnvQueryContext\_\_**: `boolean`

#### Inherited from

[EnvQueryContext](ue_ue.EnvQueryContext.md).[__tid_EnvQueryContext__](ue_ue.EnvQueryContext.md#__tid_envquerycontext__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EnvQueryContext](ue_ue.EnvQueryContext.md).[__tid_Object__](ue_ue.EnvQueryContext.md#__tid_object__)

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

[EnvQueryContext](ue_ue.EnvQueryContext.md).[CreateDefaultSubobject](ue_ue.EnvQueryContext.md#createdefaultsubobject)

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

[EnvQueryContext](ue_ue.EnvQueryContext.md).[ExecuteUbergraph](ue_ue.EnvQueryContext.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EnvQueryContext](ue_ue.EnvQueryContext.md).[GetClass](ue_ue.EnvQueryContext.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EnvQueryContext](ue_ue.EnvQueryContext.md).[GetName](ue_ue.EnvQueryContext.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EnvQueryContext](ue_ue.EnvQueryContext.md).[GetOuter](ue_ue.EnvQueryContext.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EnvQueryContext](ue_ue.EnvQueryContext.md).[GetWorld](ue_ue.EnvQueryContext.md#getworld)

___

### ProvideActorsSet

▸ **ProvideActorsSet**(`QuerierObject`, `QuerierActor`, `ResultingActorsSet`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `QuerierObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `QuerierActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `ResultingActorsSet` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

#### Returns

`void`

___

### ProvideLocationsSet

▸ **ProvideLocationsSet**(`QuerierObject`, `QuerierActor`, `ResultingLocationSet`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `QuerierObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `QuerierActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `ResultingLocationSet` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |

#### Returns

`void`

___

### ProvideSingleActor

▸ **ProvideSingleActor**(`QuerierObject`, `QuerierActor`, `ResultingActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `QuerierObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `QuerierActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `ResultingActor` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### ProvideSingleLocation

▸ **ProvideSingleLocation**(`QuerierObject`, `QuerierActor`, `ResultingLocation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `QuerierObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `QuerierActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `ResultingLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EnvQueryContext_BlueprintBase`](ue_ue.EnvQueryContext_BlueprintBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EnvQueryContext_BlueprintBase`](ue_ue.EnvQueryContext_BlueprintBase.md)

#### Overrides

[EnvQueryContext](ue_ue.EnvQueryContext.md).[Find](ue_ue.EnvQueryContext.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EnvQueryContext_BlueprintBase`](ue_ue.EnvQueryContext_BlueprintBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EnvQueryContext_BlueprintBase`](ue_ue.EnvQueryContext_BlueprintBase.md)

#### Overrides

[EnvQueryContext](ue_ue.EnvQueryContext.md).[Load](ue_ue.EnvQueryContext.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EnvQueryContext](ue_ue.EnvQueryContext.md).[StaticClass](ue_ue.EnvQueryContext.md#staticclass)
