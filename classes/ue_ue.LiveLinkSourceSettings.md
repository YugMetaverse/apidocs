[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LiveLinkSourceSettings

# Class: LiveLinkSourceSettings

[ue/ue](../modules/ue_ue.md).LiveLinkSourceSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LiveLinkSourceSettings`**

  ↳↳ [`LiveLinkCurveRemapSettings`](ue_ue.LiveLinkCurveRemapSettings.md)

## Table of contents

### Constructors

- [constructor](ue_ue.LiveLinkSourceSettings.md#constructor)

### Properties

- [BufferSettings](ue_ue.LiveLinkSourceSettings.md#buffersettings)
- [ConnectionString](ue_ue.LiveLinkSourceSettings.md#connectionstring)
- [Factory](ue_ue.LiveLinkSourceSettings.md#factory)
- [Mode](ue_ue.LiveLinkSourceSettings.md#mode)
- [SourceDebugInfos](ue_ue.LiveLinkSourceSettings.md#sourcedebuginfos)
- [\_\_tid\_LiveLinkSourceSettings\_\_](ue_ue.LiveLinkSourceSettings.md#__tid_livelinksourcesettings__)
- [\_\_tid\_Object\_\_](ue_ue.LiveLinkSourceSettings.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LiveLinkSourceSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LiveLinkSourceSettings.md#executeubergraph)
- [GetClass](ue_ue.LiveLinkSourceSettings.md#getclass)
- [GetName](ue_ue.LiveLinkSourceSettings.md#getname)
- [GetOuter](ue_ue.LiveLinkSourceSettings.md#getouter)
- [GetWorld](ue_ue.LiveLinkSourceSettings.md#getworld)
- [Find](ue_ue.LiveLinkSourceSettings.md#find)
- [Load](ue_ue.LiveLinkSourceSettings.md#load)
- [StaticClass](ue_ue.LiveLinkSourceSettings.md#staticclass)

## Constructors

### constructor

• **new LiveLinkSourceSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### BufferSettings

• **BufferSettings**: [`LiveLinkSourceBufferManagementSettings`](ue_ue.LiveLinkSourceBufferManagementSettings.md)

___

### ConnectionString

• **ConnectionString**: `string`

___

### Factory

• **Factory**: [`Class`](ue_ue.Class.md)

___

### Mode

• **Mode**: [`ELiveLinkSourceMode`](../enums/ue_ue.ELiveLinkSourceMode.md)

___

### SourceDebugInfos

• **SourceDebugInfos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LiveLinkSourceDebugInfo`](ue_ue.LiveLinkSourceDebugInfo.md)\>

___

### \_\_tid\_LiveLinkSourceSettings\_\_

• **\_\_tid\_LiveLinkSourceSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LiveLinkSourceSettings`](ue_ue.LiveLinkSourceSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LiveLinkSourceSettings`](ue_ue.LiveLinkSourceSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LiveLinkSourceSettings`](ue_ue.LiveLinkSourceSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LiveLinkSourceSettings`](ue_ue.LiveLinkSourceSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
