[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KismetMaterialLibrary

# Class: KismetMaterialLibrary

[ue/ue](../modules/ue_ue.md).KismetMaterialLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`KismetMaterialLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.KismetMaterialLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.KismetMaterialLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_KismetMaterialLibrary\_\_](ue_ue.KismetMaterialLibrary.md#__tid_kismetmateriallibrary__)
- [\_\_tid\_Object\_\_](ue_ue.KismetMaterialLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.KismetMaterialLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.KismetMaterialLibrary.md#executeubergraph)
- [GetClass](ue_ue.KismetMaterialLibrary.md#getclass)
- [GetName](ue_ue.KismetMaterialLibrary.md#getname)
- [GetOuter](ue_ue.KismetMaterialLibrary.md#getouter)
- [GetWorld](ue_ue.KismetMaterialLibrary.md#getworld)
- [CreateDynamicMaterialInstance](ue_ue.KismetMaterialLibrary.md#createdynamicmaterialinstance)
- [Find](ue_ue.KismetMaterialLibrary.md#find)
- [GetScalarParameterValue](ue_ue.KismetMaterialLibrary.md#getscalarparametervalue)
- [GetVectorParameterValue](ue_ue.KismetMaterialLibrary.md#getvectorparametervalue)
- [Load](ue_ue.KismetMaterialLibrary.md#load)
- [SetScalarParameterValue](ue_ue.KismetMaterialLibrary.md#setscalarparametervalue)
- [SetVectorParameterValue](ue_ue.KismetMaterialLibrary.md#setvectorparametervalue)
- [StaticClass](ue_ue.KismetMaterialLibrary.md#staticclass)

## Constructors

### constructor

• **new KismetMaterialLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:42261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42261)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13418)

___

### \_\_tid\_KismetMaterialLibrary\_\_

• **\_\_tid\_KismetMaterialLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:42271](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42271)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### CreateDynamicMaterialInstance

▸ `Static` **CreateDynamicMaterialInstance**(`WorldContextObject`, `Parent`, `OptionalName?`): [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Parent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `OptionalName?` | `string` |

#### Returns

[`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:42262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42262)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`KismetMaterialLibrary`](ue_ue.KismetMaterialLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`KismetMaterialLibrary`](ue_ue.KismetMaterialLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:42268](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42268)

___

### GetScalarParameterValue

▸ `Static` **GetScalarParameterValue**(`WorldContextObject`, `Collection`, `ParameterName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Collection` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialParameterCollection`](ue_ue.MaterialParameterCollection.md)\> |
| `ParameterName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42263](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42263)

___

### GetVectorParameterValue

▸ `Static` **GetVectorParameterValue**(`WorldContextObject`, `Collection`, `ParameterName`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Collection` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialParameterCollection`](ue_ue.MaterialParameterCollection.md)\> |
| `ParameterName` | `string` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:42264](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42264)

___

### Load

▸ `Static` **Load**(`InName`): [`KismetMaterialLibrary`](ue_ue.KismetMaterialLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`KismetMaterialLibrary`](ue_ue.KismetMaterialLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:42269](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42269)

___

### SetScalarParameterValue

▸ `Static` **SetScalarParameterValue**(`WorldContextObject`, `Collection`, `ParameterName`, `ParameterValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Collection` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialParameterCollection`](ue_ue.MaterialParameterCollection.md)\> |
| `ParameterName` | `string` |
| `ParameterValue` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42265](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42265)

___

### SetVectorParameterValue

▸ `Static` **SetVectorParameterValue**(`WorldContextObject`, `Collection`, `ParameterName`, `ParameterValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Collection` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialParameterCollection`](ue_ue.MaterialParameterCollection.md)\> |
| `ParameterName` | `string` |
| `ParameterValue` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42266](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42266)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:42267](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42267)
