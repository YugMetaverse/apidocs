[yug_typings](../README.md) / [Modules](../modules.md) / puerts

# Module: puerts

## Table of contents

### Namespaces

- [blueprint](puerts.blueprint.md)

### Interfaces

- [$InRef](../interfaces/puerts._InRef.md)
- [$Ref](../interfaces/puerts._Ref.md)

### Type Aliases

- [$Nullable](puerts.md#$nullable)
- [cstring](puerts.md#cstring)

### Variables

- [argv](puerts.md#argv)

### Functions

- [$ref](puerts.md#$ref)
- [$set](puerts.md#$set)
- [$unref](puerts.md#$unref)
- [blueprint](puerts.md#blueprint)
- [emit](puerts.md#emit)
- [makeUClass](puerts.md#makeuclass)
- [merge](puerts.md#merge)
- [off](puerts.md#off)
- [on](puerts.md#on)
- [releaseManualReleaseDelegate](puerts.md#releasemanualreleasedelegate)
- [toCPtrArray](puerts.md#tocptrarray)
- [toCString](puerts.md#tocstring)
- [toDelegate](puerts.md#todelegate)
- [toManualReleaseDelegate](puerts.md#tomanualreleasedelegate)

## Type Aliases

### $Nullable

Ƭ **$Nullable**<`T`\>: `T` \| ``null``

#### Type parameters

| Name |
| :------ |
| `T` |

___

### cstring

Ƭ **cstring**: `string` \| `ArrayBuffer`

## Variables

### argv

• `Const` **argv**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `getByIndex` | (`index`: `number`) => [`Object`](../classes/ue_ue.Object.md) |
| `getByName` | (`name`: `string`) => [`Object`](../classes/ue_ue.Object.md) |

## Functions

### $ref

▸ **$ref**<`T`\>(`x?`): [`$Ref`](../interfaces/puerts._Ref.md)<`T`\>

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `x?` | `T` |

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<`T`\>

___

### $set

▸ **$set**<`T`\>(`x`, `val`): `void`

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`$Ref`](../interfaces/puerts._Ref.md)<`T`\> \| [`$InRef`](../interfaces/puerts._InRef.md)<`T`\> |
| `val` | `T` |

#### Returns

`void`

___

### $unref

▸ **$unref**<`T`\>(`x`): `T`

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`$Ref`](../interfaces/puerts._Ref.md)<`T`\> \| [`$InRef`](../interfaces/puerts._InRef.md)<`T`\> |

#### Returns

`T`

___

### blueprint

▸ **blueprint**<`T`\>(`path`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends (...`args`: `any`[]) => [`Object`](../classes/ue_ue.Object.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |

#### Returns

`T`

___

### emit

▸ **emit**(`eventType`, `...args`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventType` | `string` |
| `...args` | `any`[] |

#### Returns

`boolean`

___

### makeUClass

▸ **makeUClass**(`ctor`): [`Class`](../classes/ue_ue.Class.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ctor` | () => [`Object`](../classes/ue_ue.Object.md) |

#### Returns

[`Class`](../classes/ue_ue.Class.md)

___

### merge

▸ **merge**(`des`, `src`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `des` | `Object` |
| `src` | `Object` |

#### Returns

`void`

___

### off

▸ **off**(`eventType`, `listener`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventType` | `string` |
| `listener` | `Function` |

#### Returns

`void`

___

### on

▸ **on**(`eventType`, `listener`, `prepend?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventType` | `string` |
| `listener` | `Function` |
| `prepend?` | `boolean` |

#### Returns

`void`

___

### releaseManualReleaseDelegate

▸ **releaseManualReleaseDelegate**<`T`\>(`func`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends (...`args`: `any`) => `any` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `func` | `T` |

#### Returns

`void`

___

### toCPtrArray

▸ **toCPtrArray**(`...ab`): `ArrayBuffer`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...ab` | `ArrayBuffer`[] |

#### Returns

`ArrayBuffer`

___

### toCString

▸ **toCString**(`str`): `ArrayBuffer`

#### Parameters

| Name | Type |
| :------ | :------ |
| `str` | `string` |

#### Returns

`ArrayBuffer`

___

### toDelegate

▸ **toDelegate**<`T`, `K`\>(`obj`, `key`): [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<`T`[`K`] extends (...`args`: `any`) => `any` ? `T`[`K`] : `never`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends [`Object`](../classes/ue_ue.Object.md)<`T`\> |
| `K` | extends `string` \| `number` \| `symbol` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `T` |
| `key` | `T`[`K`] extends (...`args`: `any`) => `any` ? `K` : `never` |

#### Returns

[`$Delegate`](../interfaces/ue_puerts._Delegate.md)<`T`[`K`] extends (...`args`: `any`) => `any` ? `T`[`K`] : `never`\>

___

### toManualReleaseDelegate

▸ **toManualReleaseDelegate**<`T`\>(`func`): [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends (...`args`: `any`) => `any` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `func` | `T` |

#### Returns

[`$Delegate`](../interfaces/ue_puerts._Delegate.md)<`T`\>
