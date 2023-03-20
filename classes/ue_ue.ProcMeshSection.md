[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ProcMeshSection

# Class: ProcMeshSection

[ue/ue](../modules/ue_ue.md).ProcMeshSection

## Table of contents

### Constructors

- [constructor](ue_ue.ProcMeshSection.md#constructor)

### Properties

- [ProcIndexBuffer](ue_ue.ProcMeshSection.md#procindexbuffer)
- [ProcVertexBuffer](ue_ue.ProcMeshSection.md#procvertexbuffer)
- [SectionLocalBox](ue_ue.ProcMeshSection.md#sectionlocalbox)
- [\_\_tid\_ProcMeshSection\_\_](ue_ue.ProcMeshSection.md#__tid_procmeshsection__)
- [bEnableCollision](ue_ue.ProcMeshSection.md#benablecollision)
- [bSectionVisible](ue_ue.ProcMeshSection.md#bsectionvisible)

### Methods

- [StaticClass](ue_ue.ProcMeshSection.md#staticclass)
- [StaticStruct](ue_ue.ProcMeshSection.md#staticstruct)

## Constructors

### constructor

• **new ProcMeshSection**()

#### Defined in

[ue/ue.d.ts:43008](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43008)

• **new ProcMeshSection**(`ProcVertexBuffer`, `ProcIndexBuffer`, `SectionLocalBox`, `bEnableCollision`, `bSectionVisible`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ProcVertexBuffer` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ProcMeshVertex`](ue_ue.ProcMeshVertex.md)\> |
| `ProcIndexBuffer` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `SectionLocalBox` | [`Box`](ue_ue.Box.md) |
| `bEnableCollision` | `boolean` |
| `bSectionVisible` | `boolean` |

#### Defined in

[ue/ue.d.ts:43009](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43009)

## Properties

### ProcIndexBuffer

• **ProcIndexBuffer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:43011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43011)

___

### ProcVertexBuffer

• **ProcVertexBuffer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ProcMeshVertex`](ue_ue.ProcMeshVertex.md)\>

#### Defined in

[ue/ue.d.ts:43010](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43010)

___

### SectionLocalBox

• **SectionLocalBox**: [`Box`](ue_ue.Box.md)

#### Defined in

[ue/ue.d.ts:43012](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43012)

___

### \_\_tid\_ProcMeshSection\_\_

• `Private` **\_\_tid\_ProcMeshSection\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:43020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43020)

___

### bEnableCollision

• **bEnableCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:43013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43013)

___

### bSectionVisible

• **bSectionVisible**: `boolean`

#### Defined in

[ue/ue.d.ts:43014](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43014)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:43018](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43018)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:43019](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43019)
