[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InputSettings

# Class: InputSettings

[ue/ue](../modules/ue_ue.md).InputSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InputSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.InputSettings.md#constructor)

### Properties

- [ActionMappings](ue_ue.InputSettings.md#actionmappings)
- [AxisConfig](ue_ue.InputSettings.md#axisconfig)
- [AxisMappings](ue_ue.InputSettings.md#axismappings)
- [ConsoleKey](ue_ue.InputSettings.md#consolekey)
- [ConsoleKeys](ue_ue.InputSettings.md#consolekeys)
- [DefaultTouchInterface](ue_ue.InputSettings.md#defaulttouchinterface)
- [DefaultViewportMouseCaptureMode](ue_ue.InputSettings.md#defaultviewportmousecapturemode)
- [DefaultViewportMouseLockMode](ue_ue.InputSettings.md#defaultviewportmouselockmode)
- [DoubleClickTime](ue_ue.InputSettings.md#doubleclicktime)
- [ExcludedAutocorrectCultures](ue_ue.InputSettings.md#excludedautocorrectcultures)
- [ExcludedAutocorrectDeviceModels](ue_ue.InputSettings.md#excludedautocorrectdevicemodels)
- [ExcludedAutocorrectOS](ue_ue.InputSettings.md#excludedautocorrectos)
- [FOVScale](ue_ue.InputSettings.md#fovscale)
- [SpeechMappings](ue_ue.InputSettings.md#speechmappings)
- [\_\_tid\_InputSettings\_\_](ue_ue.InputSettings.md#__tid_inputsettings__)
- [\_\_tid\_Object\_\_](ue_ue.InputSettings.md#__tid_object__)
- [bAltEnterTogglesFullscreen](ue_ue.InputSettings.md#baltentertogglesfullscreen)
- [bAlwaysShowTouchInterface](ue_ue.InputSettings.md#balwaysshowtouchinterface)
- [bCaptureMouseOnLaunch](ue_ue.InputSettings.md#bcapturemouseonlaunch)
- [bDefaultViewportMouseLock](ue_ue.InputSettings.md#bdefaultviewportmouselock)
- [bEnableFOVScaling](ue_ue.InputSettings.md#benablefovscaling)
- [bEnableGestureRecognizer](ue_ue.InputSettings.md#benablegesturerecognizer)
- [bEnableMouseSmoothing](ue_ue.InputSettings.md#benablemousesmoothing)
- [bF11TogglesFullscreen](ue_ue.InputSettings.md#bf11togglesfullscreen)
- [bShowConsoleOnFourFingerTap](ue_ue.InputSettings.md#bshowconsoleonfourfingertap)
- [bUseAutocorrect](ue_ue.InputSettings.md#buseautocorrect)
- [bUseMouseForTouch](ue_ue.InputSettings.md#busemousefortouch)

### Methods

- [AddActionMapping](ue_ue.InputSettings.md#addactionmapping)
- [AddAxisMapping](ue_ue.InputSettings.md#addaxismapping)
- [CreateDefaultSubobject](ue_ue.InputSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InputSettings.md#executeubergraph)
- [ForceRebuildKeymaps](ue_ue.InputSettings.md#forcerebuildkeymaps)
- [GetActionMappingByName](ue_ue.InputSettings.md#getactionmappingbyname)
- [GetActionNames](ue_ue.InputSettings.md#getactionnames)
- [GetAxisMappingByName](ue_ue.InputSettings.md#getaxismappingbyname)
- [GetAxisNames](ue_ue.InputSettings.md#getaxisnames)
- [GetClass](ue_ue.InputSettings.md#getclass)
- [GetName](ue_ue.InputSettings.md#getname)
- [GetOuter](ue_ue.InputSettings.md#getouter)
- [GetWorld](ue_ue.InputSettings.md#getworld)
- [RemoveActionMapping](ue_ue.InputSettings.md#removeactionmapping)
- [RemoveAxisMapping](ue_ue.InputSettings.md#removeaxismapping)
- [SaveKeyMappings](ue_ue.InputSettings.md#savekeymappings)
- [Find](ue_ue.InputSettings.md#find)
- [GetInputSettings](ue_ue.InputSettings.md#getinputsettings)
- [Load](ue_ue.InputSettings.md#load)
- [StaticClass](ue_ue.InputSettings.md#staticclass)

## Constructors

### constructor

• **new InputSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:39367](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39367)

## Properties

### ActionMappings

• **ActionMappings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InputActionKeyMapping`](ue_ue.InputActionKeyMapping.md)\>

#### Defined in

[ue/ue.d.ts:39387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39387)

___

### AxisConfig

• **AxisConfig**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InputAxisConfigEntry`](ue_ue.InputAxisConfigEntry.md)\>

#### Defined in

[ue/ue.d.ts:39368](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39368)

___

### AxisMappings

• **AxisMappings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InputAxisKeyMapping`](ue_ue.InputAxisKeyMapping.md)\>

#### Defined in

[ue/ue.d.ts:39388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39388)

___

### ConsoleKey

• **ConsoleKey**: [`Key`](ue_ue.Key.md)

#### Defined in

[ue/ue.d.ts:39391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39391)

___

### ConsoleKeys

• **ConsoleKeys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Key`](ue_ue.Key.md)\>

#### Defined in

[ue/ue.d.ts:39392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39392)

___

### DefaultTouchInterface

• **DefaultTouchInterface**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:39390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39390)

___

### DefaultViewportMouseCaptureMode

• **DefaultViewportMouseCaptureMode**: [`EMouseCaptureMode`](../enums/ue_ue.EMouseCaptureMode.md)

#### Defined in

[ue/ue.d.ts:39383](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39383)

___

### DefaultViewportMouseLockMode

• **DefaultViewportMouseLockMode**: [`EMouseLockMode`](../enums/ue_ue.EMouseLockMode.md)

#### Defined in

[ue/ue.d.ts:39384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39384)

___

### DoubleClickTime

• **DoubleClickTime**: `number`

#### Defined in

[ue/ue.d.ts:39386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39386)

___

### ExcludedAutocorrectCultures

• **ExcludedAutocorrectCultures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:39381](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39381)

___

### ExcludedAutocorrectDeviceModels

• **ExcludedAutocorrectDeviceModels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:39382](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39382)

___

### ExcludedAutocorrectOS

• **ExcludedAutocorrectOS**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:39380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39380)

___

### FOVScale

• **FOVScale**: `number`

#### Defined in

[ue/ue.d.ts:39385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39385)

___

### SpeechMappings

• **SpeechMappings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InputActionSpeechMapping`](ue_ue.InputActionSpeechMapping.md)\>

#### Defined in

[ue/ue.d.ts:39389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39389)

___

### \_\_tid\_InputSettings\_\_

• **\_\_tid\_InputSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:39408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39408)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAltEnterTogglesFullscreen

• **bAltEnterTogglesFullscreen**: `boolean`

#### Defined in

[ue/ue.d.ts:39369](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39369)

___

### bAlwaysShowTouchInterface

• **bAlwaysShowTouchInterface**: `boolean`

#### Defined in

[ue/ue.d.ts:39376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39376)

___

### bCaptureMouseOnLaunch

• **bCaptureMouseOnLaunch**: `boolean`

#### Defined in

[ue/ue.d.ts:39374](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39374)

___

### bDefaultViewportMouseLock

• **bDefaultViewportMouseLock**: `boolean`

#### Defined in

[ue/ue.d.ts:39375](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39375)

___

### bEnableFOVScaling

• **bEnableFOVScaling**: `boolean`

#### Defined in

[ue/ue.d.ts:39373](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39373)

___

### bEnableGestureRecognizer

• **bEnableGestureRecognizer**: `boolean`

#### Defined in

[ue/ue.d.ts:39378](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39378)

___

### bEnableMouseSmoothing

• **bEnableMouseSmoothing**: `boolean`

#### Defined in

[ue/ue.d.ts:39372](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39372)

___

### bF11TogglesFullscreen

• **bF11TogglesFullscreen**: `boolean`

#### Defined in

[ue/ue.d.ts:39370](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39370)

___

### bShowConsoleOnFourFingerTap

• **bShowConsoleOnFourFingerTap**: `boolean`

#### Defined in

[ue/ue.d.ts:39377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39377)

___

### bUseAutocorrect

• **bUseAutocorrect**: `boolean`

#### Defined in

[ue/ue.d.ts:39379](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39379)

___

### bUseMouseForTouch

• **bUseMouseForTouch**: `boolean`

#### Defined in

[ue/ue.d.ts:39371](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39371)

## Methods

### AddActionMapping

▸ **AddActionMapping**(`KeyMapping`, `bForceRebuildKeymaps?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyMapping` | [`InputActionKeyMapping`](ue_ue.InputActionKeyMapping.md) |
| `bForceRebuildKeymaps?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:39393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39393)

___

### AddAxisMapping

▸ **AddAxisMapping**(`KeyMapping`, `bForceRebuildKeymaps?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyMapping` | [`InputAxisKeyMapping`](ue_ue.InputAxisKeyMapping.md) |
| `bForceRebuildKeymaps?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:39394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39394)

___

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### ForceRebuildKeymaps

▸ **ForceRebuildKeymaps**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:39395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39395)

___

### GetActionMappingByName

▸ **GetActionMappingByName**(`InActionName`, `OutMappings`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InActionName` | `string` |
| `OutMappings` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`InputActionKeyMapping`](ue_ue.InputActionKeyMapping.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:39396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39396)

___

### GetActionNames

▸ **GetActionNames**(`ActionNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActionNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:39397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39397)

___

### GetAxisMappingByName

▸ **GetAxisMappingByName**(`InAxisName`, `OutMappings`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAxisName` | `string` |
| `OutMappings` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`InputAxisKeyMapping`](ue_ue.InputAxisKeyMapping.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:39398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39398)

___

### GetAxisNames

▸ **GetAxisNames**(`AxisNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AxisNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:39399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39399)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### RemoveActionMapping

▸ **RemoveActionMapping**(`KeyMapping`, `bForceRebuildKeymaps?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyMapping` | [`InputActionKeyMapping`](ue_ue.InputActionKeyMapping.md) |
| `bForceRebuildKeymaps?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:39400](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39400)

___

### RemoveAxisMapping

▸ **RemoveAxisMapping**(`KeyMapping`, `bForceRebuildKeymaps?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyMapping` | [`InputAxisKeyMapping`](ue_ue.InputAxisKeyMapping.md) |
| `bForceRebuildKeymaps?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:39401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39401)

___

### SaveKeyMappings

▸ **SaveKeyMappings**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:39402](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39402)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InputSettings`](ue_ue.InputSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InputSettings`](ue_ue.InputSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:39405](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39405)

___

### GetInputSettings

▸ `Static` **GetInputSettings**(): [`InputSettings`](ue_ue.InputSettings.md)

#### Returns

[`InputSettings`](ue_ue.InputSettings.md)

#### Defined in

[ue/ue.d.ts:39403](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39403)

___

### Load

▸ `Static` **Load**(`InName`): [`InputSettings`](ue_ue.InputSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InputSettings`](ue_ue.InputSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:39406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39406)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:39404](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39404)
