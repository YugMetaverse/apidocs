[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DeviceProfile

# Class: DeviceProfile

[ue/ue](../modules/ue_ue.md).DeviceProfile

## Hierarchy

- [`TextureLODSettings`](ue_ue.TextureLODSettings.md)

  ↳ **`DeviceProfile`**

## Table of contents

### Constructors

- [constructor](ue_ue.DeviceProfile.md#constructor)

### Properties

- [BaseProfileName](ue_ue.DeviceProfile.md#baseprofilename)
- [CVars](ue_ue.DeviceProfile.md#cvars)
- [DeviceType](ue_ue.DeviceProfile.md#devicetype)
- [Parent](ue_ue.DeviceProfile.md#parent)
- [TextureLODGroups](ue_ue.DeviceProfile.md#texturelodgroups)
- [\_\_tid\_DeviceProfile\_\_](ue_ue.DeviceProfile.md#__tid_deviceprofile__)
- [\_\_tid\_Object\_\_](ue_ue.DeviceProfile.md#__tid_object__)
- [\_\_tid\_TextureLODSettings\_\_](ue_ue.DeviceProfile.md#__tid_texturelodsettings__)

### Methods

- [CreateDefaultSubobject](ue_ue.DeviceProfile.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DeviceProfile.md#executeubergraph)
- [GetClass](ue_ue.DeviceProfile.md#getclass)
- [GetName](ue_ue.DeviceProfile.md#getname)
- [GetOuter](ue_ue.DeviceProfile.md#getouter)
- [GetWorld](ue_ue.DeviceProfile.md#getworld)
- [Find](ue_ue.DeviceProfile.md#find)
- [Load](ue_ue.DeviceProfile.md#load)
- [StaticClass](ue_ue.DeviceProfile.md#staticclass)

## Constructors

### constructor

• **new DeviceProfile**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[TextureLODSettings](ue_ue.TextureLODSettings.md).[constructor](ue_ue.TextureLODSettings.md#constructor)

#### Defined in

[ue/ue.d.ts:30798](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30798)

## Properties

### BaseProfileName

• **BaseProfileName**: `string`

#### Defined in

[ue/ue.d.ts:30800](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30800)

___

### CVars

• **CVars**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:30802](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30802)

___

### DeviceType

• **DeviceType**: `string`

#### Defined in

[ue/ue.d.ts:30799](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30799)

___

### Parent

• **Parent**: [`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:30801](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30801)

___

### TextureLODGroups

• **TextureLODGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureLODGroup`](ue_ue.TextureLODGroup.md)\>

#### Inherited from

[TextureLODSettings](ue_ue.TextureLODSettings.md).[TextureLODGroups](ue_ue.TextureLODSettings.md#texturelodgroups)

#### Defined in

[ue/ue.d.ts:30789](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30789)

___

### \_\_tid\_DeviceProfile\_\_

• **\_\_tid\_DeviceProfile\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:30807](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30807)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[TextureLODSettings](ue_ue.TextureLODSettings.md).[__tid_Object__](ue_ue.TextureLODSettings.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_TextureLODSettings\_\_

• **\_\_tid\_TextureLODSettings\_\_**: `boolean`

#### Inherited from

[TextureLODSettings](ue_ue.TextureLODSettings.md).[__tid_TextureLODSettings__](ue_ue.TextureLODSettings.md#__tid_texturelodsettings__)

#### Defined in

[ue/ue.d.ts:30794](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30794)

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

[TextureLODSettings](ue_ue.TextureLODSettings.md).[CreateDefaultSubobject](ue_ue.TextureLODSettings.md#createdefaultsubobject)

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

[TextureLODSettings](ue_ue.TextureLODSettings.md).[ExecuteUbergraph](ue_ue.TextureLODSettings.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[TextureLODSettings](ue_ue.TextureLODSettings.md).[GetClass](ue_ue.TextureLODSettings.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[TextureLODSettings](ue_ue.TextureLODSettings.md).[GetName](ue_ue.TextureLODSettings.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[TextureLODSettings](ue_ue.TextureLODSettings.md).[GetOuter](ue_ue.TextureLODSettings.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[TextureLODSettings](ue_ue.TextureLODSettings.md).[GetWorld](ue_ue.TextureLODSettings.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DeviceProfile`](ue_ue.DeviceProfile.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DeviceProfile`](ue_ue.DeviceProfile.md)

#### Overrides

[TextureLODSettings](ue_ue.TextureLODSettings.md).[Find](ue_ue.TextureLODSettings.md#find)

#### Defined in

[ue/ue.d.ts:30804](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30804)

___

### Load

▸ `Static` **Load**(`InName`): [`DeviceProfile`](ue_ue.DeviceProfile.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DeviceProfile`](ue_ue.DeviceProfile.md)

#### Overrides

[TextureLODSettings](ue_ue.TextureLODSettings.md).[Load](ue_ue.TextureLODSettings.md#load)

#### Defined in

[ue/ue.d.ts:30805](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30805)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[TextureLODSettings](ue_ue.TextureLODSettings.md).[StaticClass](ue_ue.TextureLODSettings.md#staticclass)

#### Defined in

[ue/ue.d.ts:30803](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30803)
