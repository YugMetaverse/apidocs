[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FileSystemOperation

# Class: FileSystemOperation

[ue/ue](../modules/ue_ue.md).FileSystemOperation

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`FileSystemOperation`**

## Table of contents

### Constructors

- [constructor](ue_ue.FileSystemOperation.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.FileSystemOperation.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_FileSystemOperation\_\_](ue_ue.FileSystemOperation.md#__tid_filesystemoperation__)
- [\_\_tid\_Object\_\_](ue_ue.FileSystemOperation.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.FileSystemOperation.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FileSystemOperation.md#executeubergraph)
- [GetClass](ue_ue.FileSystemOperation.md#getclass)
- [GetName](ue_ue.FileSystemOperation.md#getname)
- [GetOuter](ue_ue.FileSystemOperation.md#getouter)
- [GetWorld](ue_ue.FileSystemOperation.md#getworld)
- [CreateDirectory](ue_ue.FileSystemOperation.md#createdirectory)
- [DirectoryExists](ue_ue.FileSystemOperation.md#directoryexists)
- [FileExists](ue_ue.FileSystemOperation.md#fileexists)
- [FileMD5Hash](ue_ue.FileSystemOperation.md#filemd5hash)
- [Find](ue_ue.FileSystemOperation.md#find)
- [GetCurrentDirectory](ue_ue.FileSystemOperation.md#getcurrentdirectory)
- [GetDirectories](ue_ue.FileSystemOperation.md#getdirectories)
- [GetFiles](ue_ue.FileSystemOperation.md#getfiles)
- [Load](ue_ue.FileSystemOperation.md#load)
- [PuertsNotifyChange](ue_ue.FileSystemOperation.md#puertsnotifychange)
- [ReadFile](ue_ue.FileSystemOperation.md#readfile)
- [ResolvePath](ue_ue.FileSystemOperation.md#resolvepath)
- [StaticClass](ue_ue.FileSystemOperation.md#staticclass)
- [WriteFile](ue_ue.FileSystemOperation.md#writefile)

## Constructors

### constructor

• **new FileSystemOperation**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_FileSystemOperation\_\_

• **\_\_tid\_FileSystemOperation\_\_**: `boolean`

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

### CreateDirectory

▸ `Static` **CreateDirectory**(`Path`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

`void`

___

### DirectoryExists

▸ `Static` **DirectoryExists**(`Path`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

`boolean`

___

### FileExists

▸ `Static` **FileExists**(`Path`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

`boolean`

___

### FileMD5Hash

▸ `Static` **FileMD5Hash**(`Path`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

`string`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FileSystemOperation`](ue_ue.FileSystemOperation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FileSystemOperation`](ue_ue.FileSystemOperation.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetCurrentDirectory

▸ `Static` **GetCurrentDirectory**(): `string`

#### Returns

`string`

___

### GetDirectories

▸ `Static` **GetDirectories**(`Path`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### GetFiles

▸ `Static` **GetFiles**(`Path`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### Load

▸ `Static` **Load**(`InName`): [`FileSystemOperation`](ue_ue.FileSystemOperation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FileSystemOperation`](ue_ue.FileSystemOperation.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### PuertsNotifyChange

▸ `Static` **PuertsNotifyChange**(`Path`, `Source`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |
| `Source` | `string` |

#### Returns

`void`

___

### ReadFile

▸ `Static` **ReadFile**(`Path`, `Data`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |
| `Data` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`boolean`

___

### ResolvePath

▸ `Static` **ResolvePath**(`Path`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

`string`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

___

### WriteFile

▸ `Static` **WriteFile**(`Path`, `Data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |
| `Data` | `string` |

#### Returns

`void`
