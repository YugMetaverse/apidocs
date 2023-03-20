[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimationSharingStateProcessor

# Class: AnimationSharingStateProcessor

[ue/ue](../modules/ue_ue.md).AnimationSharingStateProcessor

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AnimationSharingStateProcessor`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimationSharingStateProcessor.md#constructor)

### Properties

- [AnimationStateEnum](ue_ue.AnimationSharingStateProcessor.md#animationstateenum)
- [\_\_tid\_AnimationSharingStateProcessor\_\_](ue_ue.AnimationSharingStateProcessor.md#__tid_animationsharingstateprocessor__)
- [\_\_tid\_Object\_\_](ue_ue.AnimationSharingStateProcessor.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimationSharingStateProcessor.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimationSharingStateProcessor.md#executeubergraph)
- [GetAnimationStateEnum](ue_ue.AnimationSharingStateProcessor.md#getanimationstateenum)
- [GetClass](ue_ue.AnimationSharingStateProcessor.md#getclass)
- [GetName](ue_ue.AnimationSharingStateProcessor.md#getname)
- [GetOuter](ue_ue.AnimationSharingStateProcessor.md#getouter)
- [GetWorld](ue_ue.AnimationSharingStateProcessor.md#getworld)
- [ProcessActorState](ue_ue.AnimationSharingStateProcessor.md#processactorstate)
- [Find](ue_ue.AnimationSharingStateProcessor.md#find)
- [Load](ue_ue.AnimationSharingStateProcessor.md#load)
- [StaticClass](ue_ue.AnimationSharingStateProcessor.md#staticclass)

## Constructors

### constructor

• **new AnimationSharingStateProcessor**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AnimationStateEnum

• **AnimationStateEnum**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Enum`](ue_ue.Enum.md)\>

___

### \_\_tid\_AnimationSharingStateProcessor\_\_

• **\_\_tid\_AnimationSharingStateProcessor\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

### GetAnimationStateEnum

▸ **GetAnimationStateEnum**(): [`Enum`](ue_ue.Enum.md)

#### Returns

[`Enum`](ue_ue.Enum.md)

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

### ProcessActorState

▸ **ProcessActorState**(`OutState`, `InActor`, `CurrentState`, `OnDemandState`, `bShouldProcess`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutState` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `InActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `CurrentState` | `number` |
| `OnDemandState` | `number` |
| `bShouldProcess` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimationSharingStateProcessor`](ue_ue.AnimationSharingStateProcessor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimationSharingStateProcessor`](ue_ue.AnimationSharingStateProcessor.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimationSharingStateProcessor`](ue_ue.AnimationSharingStateProcessor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimationSharingStateProcessor`](ue_ue.AnimationSharingStateProcessor.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
