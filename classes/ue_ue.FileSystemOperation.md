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

#### Defined in

[ue/ue.d.ts:35547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35547)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_FileSystemOperation\_\_

• **\_\_tid\_FileSystemOperation\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:35563](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35563)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### CreateDirectory

▸ `Static` **CreateDirectory**(`Path`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:35548](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35548)

___

### DirectoryExists

▸ `Static` **DirectoryExists**(`Path`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:35549](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35549)

___

### FileExists

▸ `Static` **FileExists**(`Path`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:35550](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35550)

___

### FileMD5Hash

▸ `Static` **FileMD5Hash**(`Path`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:35551](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35551)

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

#### Defined in

[ue/ue.d.ts:35560](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35560)

___

### GetCurrentDirectory

▸ `Static` **GetCurrentDirectory**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:35552](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35552)

___

### GetDirectories

▸ `Static` **GetDirectories**(`Path`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:35553](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35553)

___

### GetFiles

▸ `Static` **GetFiles**(`Path`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:35554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35554)

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

#### Defined in

[ue/ue.d.ts:35561](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35561)

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

#### Defined in

[ue/ue.d.ts:35555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35555)

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

#### Defined in

[ue/ue.d.ts:35556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35556)

___

### ResolvePath

▸ `Static` **ResolvePath**(`Path`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:35557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35557)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:35559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35559)

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

#### Defined in

[ue/ue.d.ts:35558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35558)
