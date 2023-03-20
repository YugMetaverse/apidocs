[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UserInterfaceSettings

# Class: UserInterfaceSettings

[ue/ue](../modules/ue_ue.md).UserInterfaceSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`UserInterfaceSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.UserInterfaceSettings.md#constructor)

### Properties

- [ApplicationScale](ue_ue.UserInterfaceSettings.md#applicationscale)
- [CrosshairsCursor](ue_ue.UserInterfaceSettings.md#crosshairscursor)
- [CursorClasses](ue_ue.UserInterfaceSettings.md#cursorclasses)
- [CustomScalingRule](ue_ue.UserInterfaceSettings.md#customscalingrule)
- [CustomScalingRuleClass](ue_ue.UserInterfaceSettings.md#customscalingruleclass)
- [CustomScalingRuleClassInstance](ue_ue.UserInterfaceSettings.md#customscalingruleclassinstance)
- [DefaultCursor](ue_ue.UserInterfaceSettings.md#defaultcursor)
- [GrabHandClosedCursor](ue_ue.UserInterfaceSettings.md#grabhandclosedcursor)
- [GrabHandCursor](ue_ue.UserInterfaceSettings.md#grabhandcursor)
- [HandCursor](ue_ue.UserInterfaceSettings.md#handcursor)
- [HardwareCursors](ue_ue.UserInterfaceSettings.md#hardwarecursors)
- [RenderFocusRule](ue_ue.UserInterfaceSettings.md#renderfocusrule)
- [SlashedCircleCursor](ue_ue.UserInterfaceSettings.md#slashedcirclecursor)
- [SoftwareCursors](ue_ue.UserInterfaceSettings.md#softwarecursors)
- [TextEditBeamCursor](ue_ue.UserInterfaceSettings.md#texteditbeamcursor)
- [UIScaleCurve](ue_ue.UserInterfaceSettings.md#uiscalecurve)
- [UIScaleRule](ue_ue.UserInterfaceSettings.md#uiscalerule)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.UserInterfaceSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.UserInterfaceSettings.md#__tid_object__)
- [\_\_tid\_UserInterfaceSettings\_\_](ue_ue.UserInterfaceSettings.md#__tid_userinterfacesettings__)
- [bAllowHighDPIInGameMode](ue_ue.UserInterfaceSettings.md#ballowhighdpiingamemode)
- [bLoadWidgetsOnDedicatedServer](ue_ue.UserInterfaceSettings.md#bloadwidgetsondedicatedserver)

### Methods

- [CreateDefaultSubobject](ue_ue.UserInterfaceSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UserInterfaceSettings.md#executeubergraph)
- [GetClass](ue_ue.UserInterfaceSettings.md#getclass)
- [GetName](ue_ue.UserInterfaceSettings.md#getname)
- [GetOuter](ue_ue.UserInterfaceSettings.md#getouter)
- [GetWorld](ue_ue.UserInterfaceSettings.md#getworld)
- [Find](ue_ue.UserInterfaceSettings.md#find)
- [Load](ue_ue.UserInterfaceSettings.md#load)
- [StaticClass](ue_ue.UserInterfaceSettings.md#staticclass)

## Constructors

### constructor

• **new UserInterfaceSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### ApplicationScale

• **ApplicationScale**: `number`

___

### CrosshairsCursor

• **CrosshairsCursor**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### CursorClasses

• **CursorClasses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### CustomScalingRule

• **CustomScalingRule**: [`DPICustomScalingRule`](ue_ue.DPICustomScalingRule.md)

___

### CustomScalingRuleClass

• **CustomScalingRuleClass**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### CustomScalingRuleClassInstance

• **CustomScalingRuleClassInstance**: [`Class`](ue_ue.Class.md)

___

### DefaultCursor

• **DefaultCursor**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### GrabHandClosedCursor

• **GrabHandClosedCursor**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### GrabHandCursor

• **GrabHandCursor**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### HandCursor

• **HandCursor**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### HardwareCursors

• **HardwareCursors**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`EMouseCursor`](../enums/ue_ue.EMouseCursor.md), [`HardwareCursorReference`](ue_ue.HardwareCursorReference.md)\>

___

### RenderFocusRule

• **RenderFocusRule**: [`ERenderFocusRule`](../enums/ue_ue.ERenderFocusRule.md)

___

### SlashedCircleCursor

• **SlashedCircleCursor**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### SoftwareCursors

• **SoftwareCursors**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`EMouseCursor`](../enums/ue_ue.EMouseCursor.md), [`SoftClassPath`](ue_ue.SoftClassPath.md)\>

___

### TextEditBeamCursor

• **TextEditBeamCursor**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### UIScaleCurve

• **UIScaleCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

___

### UIScaleRule

• **UIScaleRule**: [`EUIScalingRule`](../enums/ue_ue.EUIScalingRule.md)

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

### \_\_tid\_UserInterfaceSettings\_\_

• **\_\_tid\_UserInterfaceSettings\_\_**: `boolean`

___

### bAllowHighDPIInGameMode

• **bAllowHighDPIInGameMode**: `boolean`

___

### bLoadWidgetsOnDedicatedServer

• **bLoadWidgetsOnDedicatedServer**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UserInterfaceSettings`](ue_ue.UserInterfaceSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UserInterfaceSettings`](ue_ue.UserInterfaceSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`UserInterfaceSettings`](ue_ue.UserInterfaceSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UserInterfaceSettings`](ue_ue.UserInterfaceSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
