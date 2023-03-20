[yug_typings](../README.md) / [Modules](../modules.md) / [puerts](puerts.md) / blueprint

# Namespace: blueprint

[puerts](puerts.md).blueprint

## Table of contents

### Type Aliases

- [MixinConfig](puerts.blueprint.md#mixinconfig)

### Functions

- [load](puerts.blueprint.md#load)
- [mixin](puerts.blueprint.md#mixin)
- [tojs](puerts.blueprint.md#tojs)
- [unload](puerts.blueprint.md#unload)
- [unmixin](puerts.blueprint.md#unmixin)

## Type Aliases

### MixinConfig

Ƭ **MixinConfig**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `generatedClass?` | [`Class`](../classes/ue_ue.Class.md) |
| `inherit?` | `boolean` |
| `noMixinedWarning?` | `boolean` |
| `objectTakeByNative?` | `boolean` |

#### Defined in

[puerts/index.d.ts:43](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/puerts/index.d.ts#L43)

## Functions

### load

▸ **load**(`cls`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `cls` | `any` |

#### Returns

`void`

#### Defined in

[puerts/index.d.ts:50](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/puerts/index.d.ts#L50)

___

### mixin

▸ **mixin**<`T`, `R`\>(`to`, `mixinMethods`, `config?`): (`Outer?`: [`Object`](../classes/ue_ue.Object.md), `Name?`: `string`, `ObjectFlags?`: `number`) => `R`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends typeof [`Object`](../classes/ue_ue.Object.md) |
| `R` | extends [`Object`](../classes/ue_ue.Object.md)<`R`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `to` | `T` |
| `mixinMethods` | (...`args`: `any`) => `R` |
| `config?` | [`MixinConfig`](puerts.blueprint.md#mixinconfig) |

#### Returns

`fn`

• **new mixin**(`Outer?`, `Name?`, `ObjectFlags?`): `R`

##### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](../classes/ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

##### Returns

`R`

| Name | Type |
| :------ | :------ |
| `StaticClass` | () => [`Class`](../classes/ue_ue.Class.md) |

#### Defined in

[puerts/index.d.ts:45](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/puerts/index.d.ts#L45)

___

### tojs

▸ **tojs**<`T`\>(`cls`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends typeof [`Object`](../classes/ue_ue.Object.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `cls` | [`Class`](../classes/ue_ue.Class.md) |

#### Returns

`T`

#### Defined in

[puerts/index.d.ts:44](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/puerts/index.d.ts#L44)

___

### unload

▸ **unload**(`cls`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `cls` | `any` |

#### Returns

`void`

#### Defined in

[puerts/index.d.ts:51](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/puerts/index.d.ts#L51)

___

### unmixin

▸ **unmixin**<`T`\>(`to`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends typeof [`Object`](../classes/ue_ue.Object.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `to` | `T` |

#### Returns

`void`

#### Defined in

[puerts/index.d.ts:49](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/puerts/index.d.ts#L49)
