[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintEditorProjectSettings

# Class: BlueprintEditorProjectSettings

[ue/ue](../modules/ue_ue.md).BlueprintEditorProjectSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`BlueprintEditorProjectSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintEditorProjectSettings.md#constructor)

### Properties

- [DisabledCompilerMessages](ue_ue.BlueprintEditorProjectSettings.md#disabledcompilermessages)
- [DisabledCompilerMessagesExceptEditor](ue_ue.BlueprintEditorProjectSettings.md#disabledcompilermessagesexcepteditor)
- [\_\_tid\_BlueprintEditorProjectSettings\_\_](ue_ue.BlueprintEditorProjectSettings.md#__tid_blueprinteditorprojectsettings__)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.BlueprintEditorProjectSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.BlueprintEditorProjectSettings.md#__tid_object__)
- [bForceAllDependenciesToRecompile](ue_ue.BlueprintEditorProjectSettings.md#bforcealldependenciestorecompile)
- [bValidateUnloadedSoftActorReferences](ue_ue.BlueprintEditorProjectSettings.md#bvalidateunloadedsoftactorreferences)

### Methods

- [CreateDefaultSubobject](ue_ue.BlueprintEditorProjectSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlueprintEditorProjectSettings.md#executeubergraph)
- [GetClass](ue_ue.BlueprintEditorProjectSettings.md#getclass)
- [GetName](ue_ue.BlueprintEditorProjectSettings.md#getname)
- [GetOuter](ue_ue.BlueprintEditorProjectSettings.md#getouter)
- [GetWorld](ue_ue.BlueprintEditorProjectSettings.md#getworld)
- [Find](ue_ue.BlueprintEditorProjectSettings.md#find)
- [Load](ue_ue.BlueprintEditorProjectSettings.md#load)
- [StaticClass](ue_ue.BlueprintEditorProjectSettings.md#staticclass)

## Constructors

### constructor

• **new BlueprintEditorProjectSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### DisabledCompilerMessages

• **DisabledCompilerMessages**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### DisabledCompilerMessagesExceptEditor

• **DisabledCompilerMessagesExceptEditor**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### \_\_tid\_BlueprintEditorProjectSettings\_\_

• **\_\_tid\_BlueprintEditorProjectSettings\_\_**: `boolean`

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### bForceAllDependenciesToRecompile

• **bForceAllDependenciesToRecompile**: `boolean`

___

### bValidateUnloadedSoftActorReferences

• **bValidateUnloadedSoftActorReferences**: `boolean`

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlueprintEditorProjectSettings`](ue_ue.BlueprintEditorProjectSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlueprintEditorProjectSettings`](ue_ue.BlueprintEditorProjectSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BlueprintEditorProjectSettings`](ue_ue.BlueprintEditorProjectSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlueprintEditorProjectSettings`](ue_ue.BlueprintEditorProjectSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
