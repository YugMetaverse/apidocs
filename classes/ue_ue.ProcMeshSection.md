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

• **new ProcMeshSection**(`ProcVertexBuffer`, `ProcIndexBuffer`, `SectionLocalBox`, `bEnableCollision`, `bSectionVisible`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ProcVertexBuffer` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ProcMeshVertex`](ue_ue.ProcMeshVertex.md)\> |
| `ProcIndexBuffer` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `SectionLocalBox` | [`Box`](ue_ue.Box.md) |
| `bEnableCollision` | `boolean` |
| `bSectionVisible` | `boolean` |

## Properties

### ProcIndexBuffer

• **ProcIndexBuffer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### ProcVertexBuffer

• **ProcVertexBuffer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ProcMeshVertex`](ue_ue.ProcMeshVertex.md)\>

___

### SectionLocalBox

• **SectionLocalBox**: [`Box`](ue_ue.Box.md)

___

### \_\_tid\_ProcMeshSection\_\_

• `Private` **\_\_tid\_ProcMeshSection\_\_**: `boolean`

___

### bEnableCollision

• **bEnableCollision**: `boolean`

___

### bSectionVisible

• **bSectionVisible**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
