[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SourceControlHelpers

# Class: SourceControlHelpers

[ue/ue](../modules/ue_ue.md).SourceControlHelpers

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SourceControlHelpers`**

## Table of contents

### Constructors

- [constructor](ue_ue.SourceControlHelpers.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.SourceControlHelpers.md#__tid_object__)
- [\_\_tid\_SourceControlHelpers\_\_](ue_ue.SourceControlHelpers.md#__tid_sourcecontrolhelpers__)

### Methods

- [CreateDefaultSubobject](ue_ue.SourceControlHelpers.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SourceControlHelpers.md#executeubergraph)
- [GetClass](ue_ue.SourceControlHelpers.md#getclass)
- [GetName](ue_ue.SourceControlHelpers.md#getname)
- [GetOuter](ue_ue.SourceControlHelpers.md#getouter)
- [GetWorld](ue_ue.SourceControlHelpers.md#getworld)
- [CheckInFile](ue_ue.SourceControlHelpers.md#checkinfile)
- [CheckInFiles](ue_ue.SourceControlHelpers.md#checkinfiles)
- [CheckOutFile](ue_ue.SourceControlHelpers.md#checkoutfile)
- [CheckOutFiles](ue_ue.SourceControlHelpers.md#checkoutfiles)
- [CheckOutOrAddFile](ue_ue.SourceControlHelpers.md#checkoutoraddfile)
- [CopyFile](ue_ue.SourceControlHelpers.md#copyfile)
- [CurrentProvider](ue_ue.SourceControlHelpers.md#currentprovider)
- [Find](ue_ue.SourceControlHelpers.md#find)
- [IsAvailable](ue_ue.SourceControlHelpers.md#isavailable)
- [IsEnabled](ue_ue.SourceControlHelpers.md#isenabled)
- [LastErrorMsg](ue_ue.SourceControlHelpers.md#lasterrormsg)
- [Load](ue_ue.SourceControlHelpers.md#load)
- [MarkFileForAdd](ue_ue.SourceControlHelpers.md#markfileforadd)
- [MarkFileForDelete](ue_ue.SourceControlHelpers.md#markfilefordelete)
- [MarkFilesForAdd](ue_ue.SourceControlHelpers.md#markfilesforadd)
- [QueryFileState](ue_ue.SourceControlHelpers.md#queryfilestate)
- [RevertFile](ue_ue.SourceControlHelpers.md#revertfile)
- [RevertFiles](ue_ue.SourceControlHelpers.md#revertfiles)
- [RevertUnchangedFile](ue_ue.SourceControlHelpers.md#revertunchangedfile)
- [RevertUnchangedFiles](ue_ue.SourceControlHelpers.md#revertunchangedfiles)
- [StaticClass](ue_ue.SourceControlHelpers.md#staticclass)

## Constructors

### constructor

• **new SourceControlHelpers**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_SourceControlHelpers\_\_

• **\_\_tid\_SourceControlHelpers\_\_**: `boolean`

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

### CheckInFile

▸ `Static` **CheckInFile**(`InFile`, `InDescription`, `bSilent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFile` | `string` |
| `InDescription` | `string` |
| `bSilent?` | `boolean` |

#### Returns

`boolean`

___

### CheckInFiles

▸ `Static` **CheckInFiles**(`InFiles`, `InDescription`, `bSilent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFiles` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `InDescription` | `string` |
| `bSilent?` | `boolean` |

#### Returns

`boolean`

___

### CheckOutFile

▸ `Static` **CheckOutFile**(`InFile`, `bSilent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFile` | `string` |
| `bSilent?` | `boolean` |

#### Returns

`boolean`

___

### CheckOutFiles

▸ `Static` **CheckOutFiles**(`InFiles`, `bSilent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFiles` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bSilent?` | `boolean` |

#### Returns

`boolean`

___

### CheckOutOrAddFile

▸ `Static` **CheckOutOrAddFile**(`InFile`, `bSilent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFile` | `string` |
| `bSilent?` | `boolean` |

#### Returns

`boolean`

___

### CopyFile

▸ `Static` **CopyFile**(`InSourceFile`, `InDestFile`, `bSilent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSourceFile` | `string` |
| `InDestFile` | `string` |
| `bSilent?` | `boolean` |

#### Returns

`boolean`

___

### CurrentProvider

▸ `Static` **CurrentProvider**(): `string`

#### Returns

`string`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SourceControlHelpers`](ue_ue.SourceControlHelpers.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SourceControlHelpers`](ue_ue.SourceControlHelpers.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### IsAvailable

▸ `Static` **IsAvailable**(): `boolean`

#### Returns

`boolean`

___

### IsEnabled

▸ `Static` **IsEnabled**(): `boolean`

#### Returns

`boolean`

___

### LastErrorMsg

▸ `Static` **LastErrorMsg**(): `string`

#### Returns

`string`

___

### Load

▸ `Static` **Load**(`InName`): [`SourceControlHelpers`](ue_ue.SourceControlHelpers.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SourceControlHelpers`](ue_ue.SourceControlHelpers.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### MarkFileForAdd

▸ `Static` **MarkFileForAdd**(`InFile`, `bSilent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFile` | `string` |
| `bSilent?` | `boolean` |

#### Returns

`boolean`

___

### MarkFileForDelete

▸ `Static` **MarkFileForDelete**(`InFile`, `bSilent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFile` | `string` |
| `bSilent?` | `boolean` |

#### Returns

`boolean`

___

### MarkFilesForAdd

▸ `Static` **MarkFilesForAdd**(`InFiles`, `bSilent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFiles` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bSilent?` | `boolean` |

#### Returns

`boolean`

___

### QueryFileState

▸ `Static` **QueryFileState**(`InFile`, `bSilent?`): [`SourceControlState`](ue_ue.SourceControlState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFile` | `string` |
| `bSilent?` | `boolean` |

#### Returns

[`SourceControlState`](ue_ue.SourceControlState.md)

___

### RevertFile

▸ `Static` **RevertFile**(`InFile`, `bSilent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFile` | `string` |
| `bSilent?` | `boolean` |

#### Returns

`boolean`

___

### RevertFiles

▸ `Static` **RevertFiles**(`InFiles`, `bSilent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFiles` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bSilent?` | `boolean` |

#### Returns

`boolean`

___

### RevertUnchangedFile

▸ `Static` **RevertUnchangedFile**(`InFile`, `bSilent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFile` | `string` |
| `bSilent?` | `boolean` |

#### Returns

`boolean`

___

### RevertUnchangedFiles

▸ `Static` **RevertUnchangedFiles**(`InFiles`, `bSilent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFiles` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bSilent?` | `boolean` |

#### Returns

`boolean`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
