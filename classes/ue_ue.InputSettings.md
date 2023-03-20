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

## Properties

### ActionMappings

• **ActionMappings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InputActionKeyMapping`](ue_ue.InputActionKeyMapping.md)\>

___

### AxisConfig

• **AxisConfig**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InputAxisConfigEntry`](ue_ue.InputAxisConfigEntry.md)\>

___

### AxisMappings

• **AxisMappings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InputAxisKeyMapping`](ue_ue.InputAxisKeyMapping.md)\>

___

### ConsoleKey

• **ConsoleKey**: [`Key`](ue_ue.Key.md)

___

### ConsoleKeys

• **ConsoleKeys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Key`](ue_ue.Key.md)\>

___

### DefaultTouchInterface

• **DefaultTouchInterface**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### DefaultViewportMouseCaptureMode

• **DefaultViewportMouseCaptureMode**: [`EMouseCaptureMode`](../enums/ue_ue.EMouseCaptureMode.md)

___

### DefaultViewportMouseLockMode

• **DefaultViewportMouseLockMode**: [`EMouseLockMode`](../enums/ue_ue.EMouseLockMode.md)

___

### DoubleClickTime

• **DoubleClickTime**: `number`

___

### ExcludedAutocorrectCultures

• **ExcludedAutocorrectCultures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ExcludedAutocorrectDeviceModels

• **ExcludedAutocorrectDeviceModels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ExcludedAutocorrectOS

• **ExcludedAutocorrectOS**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### FOVScale

• **FOVScale**: `number`

___

### SpeechMappings

• **SpeechMappings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InputActionSpeechMapping`](ue_ue.InputActionSpeechMapping.md)\>

___

### \_\_tid\_InputSettings\_\_

• **\_\_tid\_InputSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAltEnterTogglesFullscreen

• **bAltEnterTogglesFullscreen**: `boolean`

___

### bAlwaysShowTouchInterface

• **bAlwaysShowTouchInterface**: `boolean`

___

### bCaptureMouseOnLaunch

• **bCaptureMouseOnLaunch**: `boolean`

___

### bDefaultViewportMouseLock

• **bDefaultViewportMouseLock**: `boolean`

___

### bEnableFOVScaling

• **bEnableFOVScaling**: `boolean`

___

### bEnableGestureRecognizer

• **bEnableGestureRecognizer**: `boolean`

___

### bEnableMouseSmoothing

• **bEnableMouseSmoothing**: `boolean`

___

### bF11TogglesFullscreen

• **bF11TogglesFullscreen**: `boolean`

___

### bShowConsoleOnFourFingerTap

• **bShowConsoleOnFourFingerTap**: `boolean`

___

### bUseAutocorrect

• **bUseAutocorrect**: `boolean`

___

### bUseMouseForTouch

• **bUseMouseForTouch**: `boolean`

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

### ForceRebuildKeymaps

▸ **ForceRebuildKeymaps**(): `void`

#### Returns

`void`

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

___

### GetActionNames

▸ **GetActionNames**(`ActionNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActionNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

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

___

### GetAxisNames

▸ **GetAxisNames**(`AxisNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AxisNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

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

### RemoveActionMapping

▸ **RemoveActionMapping**(`KeyMapping`, `bForceRebuildKeymaps?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `KeyMapping` | [`InputActionKeyMapping`](ue_ue.InputActionKeyMapping.md) |
| `bForceRebuildKeymaps?` | `boolean` |

#### Returns

`void`

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

___

### SaveKeyMappings

▸ **SaveKeyMappings**(): `void`

#### Returns

`void`

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

___

### GetInputSettings

▸ `Static` **GetInputSettings**(): [`InputSettings`](ue_ue.InputSettings.md)

#### Returns

[`InputSettings`](ue_ue.InputSettings.md)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
