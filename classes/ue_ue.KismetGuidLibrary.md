[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KismetGuidLibrary

# Class: KismetGuidLibrary

[ue/ue](../modules/ue_ue.md).KismetGuidLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`KismetGuidLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.KismetGuidLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.KismetGuidLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_KismetGuidLibrary\_\_](ue_ue.KismetGuidLibrary.md#__tid_kismetguidlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.KismetGuidLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.KismetGuidLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.KismetGuidLibrary.md#executeubergraph)
- [GetClass](ue_ue.KismetGuidLibrary.md#getclass)
- [GetName](ue_ue.KismetGuidLibrary.md#getname)
- [GetOuter](ue_ue.KismetGuidLibrary.md#getouter)
- [GetWorld](ue_ue.KismetGuidLibrary.md#getworld)
- [Conv\_GuidToString](ue_ue.KismetGuidLibrary.md#conv_guidtostring)
- [EqualEqual\_GuidGuid](ue_ue.KismetGuidLibrary.md#equalequal_guidguid)
- [Find](ue_ue.KismetGuidLibrary.md#find)
- [Invalidate\_Guid](ue_ue.KismetGuidLibrary.md#invalidate_guid)
- [IsValid\_Guid](ue_ue.KismetGuidLibrary.md#isvalid_guid)
- [Load](ue_ue.KismetGuidLibrary.md#load)
- [NewGuid](ue_ue.KismetGuidLibrary.md#newguid)
- [NotEqual\_GuidGuid](ue_ue.KismetGuidLibrary.md#notequal_guidguid)
- [Parse\_StringToGuid](ue_ue.KismetGuidLibrary.md#parse_stringtoguid)
- [StaticClass](ue_ue.KismetGuidLibrary.md#staticclass)

## Constructors

### constructor

• **new KismetGuidLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_KismetGuidLibrary\_\_

• **\_\_tid\_KismetGuidLibrary\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### Conv\_GuidToString

▸ `Static` **Conv_GuidToString**(`InGuid`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InGuid` | [`Guid`](ue_ue_s.Guid.md) |

#### Returns

`string`

___

### EqualEqual\_GuidGuid

▸ `Static` **EqualEqual_GuidGuid**(`A`, `B`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Guid`](ue_ue_s.Guid.md) |
| `B` | [`Guid`](ue_ue_s.Guid.md) |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`KismetGuidLibrary`](ue_ue.KismetGuidLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`KismetGuidLibrary`](ue_ue.KismetGuidLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### Invalidate\_Guid

▸ `Static` **Invalidate_Guid**(`InGuid`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InGuid` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Guid`](ue_ue_s.Guid.md)\> |

#### Returns

`void`

___

### IsValid\_Guid

▸ `Static` **IsValid_Guid**(`InGuid`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InGuid` | [`Guid`](ue_ue_s.Guid.md) |

#### Returns

`boolean`

___

### Load

▸ `Static` **Load**(`InName`): [`KismetGuidLibrary`](ue_ue.KismetGuidLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`KismetGuidLibrary`](ue_ue.KismetGuidLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### NewGuid

▸ `Static` **NewGuid**(): [`Guid`](ue_ue_s.Guid.md)

#### Returns

[`Guid`](ue_ue_s.Guid.md)

___

### NotEqual\_GuidGuid

▸ `Static` **NotEqual_GuidGuid**(`A`, `B`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Guid`](ue_ue_s.Guid.md) |
| `B` | [`Guid`](ue_ue_s.Guid.md) |

#### Returns

`boolean`

___

### Parse\_StringToGuid

▸ `Static` **Parse_StringToGuid**(`GuidString`, `OutGuid`, `Success`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GuidString` | `string` |
| `OutGuid` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Guid`](ue_ue_s.Guid.md)\> |
| `Success` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
