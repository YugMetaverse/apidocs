[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintComponentNodeSpawner

# Class: BlueprintComponentNodeSpawner

[ue/ue](../modules/ue_ue.md).BlueprintComponentNodeSpawner

## Hierarchy

- [`BlueprintNodeSpawner`](ue_ue.BlueprintNodeSpawner.md)

  ↳ **`BlueprintComponentNodeSpawner`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintComponentNodeSpawner.md#constructor)

### Properties

- [ComponentAssetName](ue_ue.BlueprintComponentNodeSpawner.md#componentassetname)
- [ComponentClass](ue_ue.BlueprintComponentNodeSpawner.md#componentclass)
- [ComponentName](ue_ue.BlueprintComponentNodeSpawner.md#componentname)
- [NodeClass](ue_ue.BlueprintComponentNodeSpawner.md#nodeclass)
- [\_\_tid\_BlueprintComponentNodeSpawner\_\_](ue_ue.BlueprintComponentNodeSpawner.md#__tid_blueprintcomponentnodespawner__)
- [\_\_tid\_BlueprintNodeSpawner\_\_](ue_ue.BlueprintComponentNodeSpawner.md#__tid_blueprintnodespawner__)
- [\_\_tid\_Object\_\_](ue_ue.BlueprintComponentNodeSpawner.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BlueprintComponentNodeSpawner.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlueprintComponentNodeSpawner.md#executeubergraph)
- [GetClass](ue_ue.BlueprintComponentNodeSpawner.md#getclass)
- [GetName](ue_ue.BlueprintComponentNodeSpawner.md#getname)
- [GetOuter](ue_ue.BlueprintComponentNodeSpawner.md#getouter)
- [GetWorld](ue_ue.BlueprintComponentNodeSpawner.md#getworld)
- [Find](ue_ue.BlueprintComponentNodeSpawner.md#find)
- [Load](ue_ue.BlueprintComponentNodeSpawner.md#load)
- [StaticClass](ue_ue.BlueprintComponentNodeSpawner.md#staticclass)

## Constructors

### constructor

• **new BlueprintComponentNodeSpawner**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintNodeSpawner](ue_ue.BlueprintNodeSpawner.md).[constructor](ue_ue.BlueprintNodeSpawner.md#constructor)

#### Defined in

[ue/ue.d.ts:23954](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23954)

## Properties

### ComponentAssetName

• **ComponentAssetName**: `string`

#### Defined in

[ue/ue.d.ts:23957](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23957)

___

### ComponentClass

• **ComponentClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:23955](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23955)

___

### ComponentName

• **ComponentName**: `string`

#### Defined in

[ue/ue.d.ts:23956](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23956)

___

### NodeClass

• **NodeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintNodeSpawner](ue_ue.BlueprintNodeSpawner.md).[NodeClass](ue_ue.BlueprintNodeSpawner.md#nodeclass)

#### Defined in

[ue/ue.d.ts:23897](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23897)

___

### \_\_tid\_BlueprintComponentNodeSpawner\_\_

• **\_\_tid\_BlueprintComponentNodeSpawner\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:23962](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23962)

___

### \_\_tid\_BlueprintNodeSpawner\_\_

• **\_\_tid\_BlueprintNodeSpawner\_\_**: `boolean`

#### Inherited from

[BlueprintNodeSpawner](ue_ue.BlueprintNodeSpawner.md).[__tid_BlueprintNodeSpawner__](ue_ue.BlueprintNodeSpawner.md#__tid_blueprintnodespawner__)

#### Defined in

[ue/ue.d.ts:23902](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23902)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintNodeSpawner](ue_ue.BlueprintNodeSpawner.md).[__tid_Object__](ue_ue.BlueprintNodeSpawner.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[BlueprintNodeSpawner](ue_ue.BlueprintNodeSpawner.md).[CreateDefaultSubobject](ue_ue.BlueprintNodeSpawner.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[BlueprintNodeSpawner](ue_ue.BlueprintNodeSpawner.md).[ExecuteUbergraph](ue_ue.BlueprintNodeSpawner.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintNodeSpawner](ue_ue.BlueprintNodeSpawner.md).[GetClass](ue_ue.BlueprintNodeSpawner.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintNodeSpawner](ue_ue.BlueprintNodeSpawner.md).[GetName](ue_ue.BlueprintNodeSpawner.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintNodeSpawner](ue_ue.BlueprintNodeSpawner.md).[GetOuter](ue_ue.BlueprintNodeSpawner.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintNodeSpawner](ue_ue.BlueprintNodeSpawner.md).[GetWorld](ue_ue.BlueprintNodeSpawner.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlueprintComponentNodeSpawner`](ue_ue.BlueprintComponentNodeSpawner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlueprintComponentNodeSpawner`](ue_ue.BlueprintComponentNodeSpawner.md)

#### Overrides

[BlueprintNodeSpawner](ue_ue.BlueprintNodeSpawner.md).[Find](ue_ue.BlueprintNodeSpawner.md#find)

#### Defined in

[ue/ue.d.ts:23959](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23959)

___

### Load

▸ `Static` **Load**(`InName`): [`BlueprintComponentNodeSpawner`](ue_ue.BlueprintComponentNodeSpawner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlueprintComponentNodeSpawner`](ue_ue.BlueprintComponentNodeSpawner.md)

#### Overrides

[BlueprintNodeSpawner](ue_ue.BlueprintNodeSpawner.md).[Load](ue_ue.BlueprintNodeSpawner.md#load)

#### Defined in

[ue/ue.d.ts:23960](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23960)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintNodeSpawner](ue_ue.BlueprintNodeSpawner.md).[StaticClass](ue_ue.BlueprintNodeSpawner.md#staticclass)

#### Defined in

[ue/ue.d.ts:23958](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23958)
