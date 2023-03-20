[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SkeletalMeshSocket

# Class: SkeletalMeshSocket

[ue/ue](../modules/ue_ue.md).SkeletalMeshSocket

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SkeletalMeshSocket`**

## Table of contents

### Constructors

- [constructor](ue_ue.SkeletalMeshSocket.md#constructor)

### Properties

- [BoneName](ue_ue.SkeletalMeshSocket.md#bonename)
- [RelativeLocation](ue_ue.SkeletalMeshSocket.md#relativelocation)
- [RelativeRotation](ue_ue.SkeletalMeshSocket.md#relativerotation)
- [RelativeScale](ue_ue.SkeletalMeshSocket.md#relativescale)
- [SocketName](ue_ue.SkeletalMeshSocket.md#socketname)
- [\_\_tid\_Object\_\_](ue_ue.SkeletalMeshSocket.md#__tid_object__)
- [\_\_tid\_SkeletalMeshSocket\_\_](ue_ue.SkeletalMeshSocket.md#__tid_skeletalmeshsocket__)
- [bForceAlwaysAnimated](ue_ue.SkeletalMeshSocket.md#bforcealwaysanimated)

### Methods

- [CreateDefaultSubobject](ue_ue.SkeletalMeshSocket.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SkeletalMeshSocket.md#executeubergraph)
- [GetClass](ue_ue.SkeletalMeshSocket.md#getclass)
- [GetName](ue_ue.SkeletalMeshSocket.md#getname)
- [GetOuter](ue_ue.SkeletalMeshSocket.md#getouter)
- [GetSocketLocation](ue_ue.SkeletalMeshSocket.md#getsocketlocation)
- [GetWorld](ue_ue.SkeletalMeshSocket.md#getworld)
- [InitializeSocketFromLocation](ue_ue.SkeletalMeshSocket.md#initializesocketfromlocation)
- [Find](ue_ue.SkeletalMeshSocket.md#find)
- [Load](ue_ue.SkeletalMeshSocket.md#load)
- [StaticClass](ue_ue.SkeletalMeshSocket.md#staticclass)

## Constructors

### constructor

• **new SkeletalMeshSocket**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### BoneName

• **BoneName**: `string`

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### RelativeScale

• **RelativeScale**: [`Vector`](ue_ue_s.Vector.md)

___

### SocketName

• **SocketName**: `string`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_SkeletalMeshSocket\_\_

• **\_\_tid\_SkeletalMeshSocket\_\_**: `boolean`

___

### bForceAlwaysAnimated

• **bForceAlwaysAnimated**: `boolean`

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

### GetSocketLocation

▸ **GetSocketLocation**(`SkelComp`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SkelComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\> |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### InitializeSocketFromLocation

▸ **InitializeSocketFromLocation**(`SkelComp`, `WorldLocation`, `WorldNormal`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SkelComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\> |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `WorldNormal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
