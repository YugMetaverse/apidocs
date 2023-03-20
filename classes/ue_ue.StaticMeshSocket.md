[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / StaticMeshSocket

# Class: StaticMeshSocket

[ue/ue](../modules/ue_ue.md).StaticMeshSocket

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`StaticMeshSocket`**

## Table of contents

### Constructors

- [constructor](ue_ue.StaticMeshSocket.md#constructor)

### Properties

- [PreviewStaticMesh](ue_ue.StaticMeshSocket.md#previewstaticmesh)
- [RelativeLocation](ue_ue.StaticMeshSocket.md#relativelocation)
- [RelativeRotation](ue_ue.StaticMeshSocket.md#relativerotation)
- [RelativeScale](ue_ue.StaticMeshSocket.md#relativescale)
- [SocketName](ue_ue.StaticMeshSocket.md#socketname)
- [Tag](ue_ue.StaticMeshSocket.md#tag)
- [\_\_tid\_Object\_\_](ue_ue.StaticMeshSocket.md#__tid_object__)
- [\_\_tid\_StaticMeshSocket\_\_](ue_ue.StaticMeshSocket.md#__tid_staticmeshsocket__)
- [bSocketCreatedAtImport](ue_ue.StaticMeshSocket.md#bsocketcreatedatimport)

### Methods

- [CreateDefaultSubobject](ue_ue.StaticMeshSocket.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.StaticMeshSocket.md#executeubergraph)
- [GetClass](ue_ue.StaticMeshSocket.md#getclass)
- [GetName](ue_ue.StaticMeshSocket.md#getname)
- [GetOuter](ue_ue.StaticMeshSocket.md#getouter)
- [GetWorld](ue_ue.StaticMeshSocket.md#getworld)
- [Find](ue_ue.StaticMeshSocket.md#find)
- [Load](ue_ue.StaticMeshSocket.md#load)
- [StaticClass](ue_ue.StaticMeshSocket.md#staticclass)

## Constructors

### constructor

• **new StaticMeshSocket**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### PreviewStaticMesh

• **PreviewStaticMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

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

### Tag

• **Tag**: `string`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_StaticMeshSocket\_\_

• **\_\_tid\_StaticMeshSocket\_\_**: `boolean`

___

### bSocketCreatedAtImport

• **bSocketCreatedAtImport**: `boolean`

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

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
