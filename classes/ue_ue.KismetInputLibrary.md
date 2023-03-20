[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KismetInputLibrary

# Class: KismetInputLibrary

[ue/ue](../modules/ue_ue.md).KismetInputLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`KismetInputLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.KismetInputLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.KismetInputLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_KismetInputLibrary\_\_](ue_ue.KismetInputLibrary.md#__tid_kismetinputlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.KismetInputLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.KismetInputLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.KismetInputLibrary.md#executeubergraph)
- [GetClass](ue_ue.KismetInputLibrary.md#getclass)
- [GetName](ue_ue.KismetInputLibrary.md#getname)
- [GetOuter](ue_ue.KismetInputLibrary.md#getouter)
- [GetWorld](ue_ue.KismetInputLibrary.md#getworld)
- [CalibrateTilt](ue_ue.KismetInputLibrary.md#calibratetilt)
- [EqualEqual\_InputChordInputChord](ue_ue.KismetInputLibrary.md#equalequal_inputchordinputchord)
- [EqualEqual\_KeyKey](ue_ue.KismetInputLibrary.md#equalequal_keykey)
- [Find](ue_ue.KismetInputLibrary.md#find)
- [GetAnalogValue](ue_ue.KismetInputLibrary.md#getanalogvalue)
- [GetKey](ue_ue.KismetInputLibrary.md#getkey)
- [GetUserIndex](ue_ue.KismetInputLibrary.md#getuserindex)
- [InputChord\_GetDisplayName](ue_ue.KismetInputLibrary.md#inputchord_getdisplayname)
- [InputEvent\_IsAltDown](ue_ue.KismetInputLibrary.md#inputevent_isaltdown)
- [InputEvent\_IsCommandDown](ue_ue.KismetInputLibrary.md#inputevent_iscommanddown)
- [InputEvent\_IsControlDown](ue_ue.KismetInputLibrary.md#inputevent_iscontroldown)
- [InputEvent\_IsLeftAltDown](ue_ue.KismetInputLibrary.md#inputevent_isleftaltdown)
- [InputEvent\_IsLeftCommandDown](ue_ue.KismetInputLibrary.md#inputevent_isleftcommanddown)
- [InputEvent\_IsLeftControlDown](ue_ue.KismetInputLibrary.md#inputevent_isleftcontroldown)
- [InputEvent\_IsLeftShiftDown](ue_ue.KismetInputLibrary.md#inputevent_isleftshiftdown)
- [InputEvent\_IsRepeat](ue_ue.KismetInputLibrary.md#inputevent_isrepeat)
- [InputEvent\_IsRightAltDown](ue_ue.KismetInputLibrary.md#inputevent_isrightaltdown)
- [InputEvent\_IsRightCommandDown](ue_ue.KismetInputLibrary.md#inputevent_isrightcommanddown)
- [InputEvent\_IsRightControlDown](ue_ue.KismetInputLibrary.md#inputevent_isrightcontroldown)
- [InputEvent\_IsRightShiftDown](ue_ue.KismetInputLibrary.md#inputevent_isrightshiftdown)
- [InputEvent\_IsShiftDown](ue_ue.KismetInputLibrary.md#inputevent_isshiftdown)
- [Key\_GetDisplayName](ue_ue.KismetInputLibrary.md#key_getdisplayname)
- [Key\_GetNavigationAction](ue_ue.KismetInputLibrary.md#key_getnavigationaction)
- [Key\_GetNavigationActionFromKey](ue_ue.KismetInputLibrary.md#key_getnavigationactionfromkey)
- [Key\_GetNavigationDirectionFromAnalog](ue_ue.KismetInputLibrary.md#key_getnavigationdirectionfromanalog)
- [Key\_GetNavigationDirectionFromKey](ue_ue.KismetInputLibrary.md#key_getnavigationdirectionfromkey)
- [Key\_IsFloatAxis](ue_ue.KismetInputLibrary.md#key_isfloataxis)
- [Key\_IsGamepadKey](ue_ue.KismetInputLibrary.md#key_isgamepadkey)
- [Key\_IsKeyboardKey](ue_ue.KismetInputLibrary.md#key_iskeyboardkey)
- [Key\_IsModifierKey](ue_ue.KismetInputLibrary.md#key_ismodifierkey)
- [Key\_IsMouseButton](ue_ue.KismetInputLibrary.md#key_ismousebutton)
- [Key\_IsValid](ue_ue.KismetInputLibrary.md#key_isvalid)
- [Key\_IsVectorAxis](ue_ue.KismetInputLibrary.md#key_isvectoraxis)
- [Load](ue_ue.KismetInputLibrary.md#load)
- [PointerEvent\_GetCursorDelta](ue_ue.KismetInputLibrary.md#pointerevent_getcursordelta)
- [PointerEvent\_GetEffectingButton](ue_ue.KismetInputLibrary.md#pointerevent_geteffectingbutton)
- [PointerEvent\_GetGestureDelta](ue_ue.KismetInputLibrary.md#pointerevent_getgesturedelta)
- [PointerEvent\_GetGestureType](ue_ue.KismetInputLibrary.md#pointerevent_getgesturetype)
- [PointerEvent\_GetLastScreenSpacePosition](ue_ue.KismetInputLibrary.md#pointerevent_getlastscreenspaceposition)
- [PointerEvent\_GetPointerIndex](ue_ue.KismetInputLibrary.md#pointerevent_getpointerindex)
- [PointerEvent\_GetScreenSpacePosition](ue_ue.KismetInputLibrary.md#pointerevent_getscreenspaceposition)
- [PointerEvent\_GetTouchpadIndex](ue_ue.KismetInputLibrary.md#pointerevent_gettouchpadindex)
- [PointerEvent\_GetUserIndex](ue_ue.KismetInputLibrary.md#pointerevent_getuserindex)
- [PointerEvent\_GetWheelDelta](ue_ue.KismetInputLibrary.md#pointerevent_getwheeldelta)
- [PointerEvent\_IsMouseButtonDown](ue_ue.KismetInputLibrary.md#pointerevent_ismousebuttondown)
- [PointerEvent\_IsTouchEvent](ue_ue.KismetInputLibrary.md#pointerevent_istouchevent)
- [StaticClass](ue_ue.KismetInputLibrary.md#staticclass)

## Constructors

### constructor

• **new KismetInputLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:42185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42185)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13418)

___

### \_\_tid\_KismetInputLibrary\_\_

• **\_\_tid\_KismetInputLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:42234](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42234)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### CalibrateTilt

▸ `Static` **CalibrateTilt**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:42186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42186)

___

### EqualEqual\_InputChordInputChord

▸ `Static` **EqualEqual_InputChordInputChord**(`A`, `B`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`InputChord`](ue_ue.InputChord.md) |
| `B` | [`InputChord`](ue_ue.InputChord.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42187)

___

### EqualEqual\_KeyKey

▸ `Static` **EqualEqual_KeyKey**(`A`, `B`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Key`](ue_ue.Key.md) |
| `B` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42188)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`KismetInputLibrary`](ue_ue.KismetInputLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`KismetInputLibrary`](ue_ue.KismetInputLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:42231](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42231)

___

### GetAnalogValue

▸ `Static` **GetAnalogValue**(`Input`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`AnalogInputEvent`](ue_ue.AnalogInputEvent.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42189)

___

### GetKey

▸ `Static` **GetKey**(`Input`): [`Key`](ue_ue.Key.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`KeyEvent`](ue_ue.KeyEvent.md) |

#### Returns

[`Key`](ue_ue.Key.md)

#### Defined in

[ue/ue.d.ts:42190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42190)

___

### GetUserIndex

▸ `Static` **GetUserIndex**(`Input`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`KeyEvent`](ue_ue.KeyEvent.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42191](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42191)

___

### InputChord\_GetDisplayName

▸ `Static` **InputChord_GetDisplayName**(`Key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`InputChord`](ue_ue.InputChord.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:42192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42192)

___

### InputEvent\_IsAltDown

▸ `Static` **InputEvent_IsAltDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42193)

___

### InputEvent\_IsCommandDown

▸ `Static` **InputEvent_IsCommandDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42194](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42194)

___

### InputEvent\_IsControlDown

▸ `Static` **InputEvent_IsControlDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42195](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42195)

___

### InputEvent\_IsLeftAltDown

▸ `Static` **InputEvent_IsLeftAltDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42196](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42196)

___

### InputEvent\_IsLeftCommandDown

▸ `Static` **InputEvent_IsLeftCommandDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42197](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42197)

___

### InputEvent\_IsLeftControlDown

▸ `Static` **InputEvent_IsLeftControlDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42198](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42198)

___

### InputEvent\_IsLeftShiftDown

▸ `Static` **InputEvent_IsLeftShiftDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42199](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42199)

___

### InputEvent\_IsRepeat

▸ `Static` **InputEvent_IsRepeat**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42200](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42200)

___

### InputEvent\_IsRightAltDown

▸ `Static` **InputEvent_IsRightAltDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42201](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42201)

___

### InputEvent\_IsRightCommandDown

▸ `Static` **InputEvent_IsRightCommandDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42202](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42202)

___

### InputEvent\_IsRightControlDown

▸ `Static` **InputEvent_IsRightControlDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42203](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42203)

___

### InputEvent\_IsRightShiftDown

▸ `Static` **InputEvent_IsRightShiftDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42204](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42204)

___

### InputEvent\_IsShiftDown

▸ `Static` **InputEvent_IsShiftDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42205](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42205)

___

### Key\_GetDisplayName

▸ `Static` **Key_GetDisplayName**(`Key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:42206](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42206)

___

### Key\_GetNavigationAction

▸ `Static` **Key_GetNavigationAction**(`InKey`): [`EUINavigationAction`](../enums/ue_ue.EUINavigationAction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKey` | [`Key`](ue_ue.Key.md) |

#### Returns

[`EUINavigationAction`](../enums/ue_ue.EUINavigationAction.md)

#### Defined in

[ue/ue.d.ts:42207](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42207)

___

### Key\_GetNavigationActionFromKey

▸ `Static` **Key_GetNavigationActionFromKey**(`InKeyEvent`): [`EUINavigationAction`](../enums/ue_ue.EUINavigationAction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKeyEvent` | [`KeyEvent`](ue_ue.KeyEvent.md) |

#### Returns

[`EUINavigationAction`](../enums/ue_ue.EUINavigationAction.md)

#### Defined in

[ue/ue.d.ts:42208](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42208)

___

### Key\_GetNavigationDirectionFromAnalog

▸ `Static` **Key_GetNavigationDirectionFromAnalog**(`InAnalogEvent`): [`EUINavigation`](../enums/ue_ue.EUINavigation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnalogEvent` | [`AnalogInputEvent`](ue_ue.AnalogInputEvent.md) |

#### Returns

[`EUINavigation`](../enums/ue_ue.EUINavigation.md)

#### Defined in

[ue/ue.d.ts:42209](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42209)

___

### Key\_GetNavigationDirectionFromKey

▸ `Static` **Key_GetNavigationDirectionFromKey**(`InKeyEvent`): [`EUINavigation`](../enums/ue_ue.EUINavigation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKeyEvent` | [`KeyEvent`](ue_ue.KeyEvent.md) |

#### Returns

[`EUINavigation`](../enums/ue_ue.EUINavigation.md)

#### Defined in

[ue/ue.d.ts:42210](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42210)

___

### Key\_IsFloatAxis

▸ `Static` **Key_IsFloatAxis**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42211](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42211)

___

### Key\_IsGamepadKey

▸ `Static` **Key_IsGamepadKey**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42212](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42212)

___

### Key\_IsKeyboardKey

▸ `Static` **Key_IsKeyboardKey**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42213](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42213)

___

### Key\_IsModifierKey

▸ `Static` **Key_IsModifierKey**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42214](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42214)

___

### Key\_IsMouseButton

▸ `Static` **Key_IsMouseButton**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42215](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42215)

___

### Key\_IsValid

▸ `Static` **Key_IsValid**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42216](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42216)

___

### Key\_IsVectorAxis

▸ `Static` **Key_IsVectorAxis**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42217](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42217)

___

### Load

▸ `Static` **Load**(`InName`): [`KismetInputLibrary`](ue_ue.KismetInputLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`KismetInputLibrary`](ue_ue.KismetInputLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:42232](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42232)

___

### PointerEvent\_GetCursorDelta

▸ `Static` **PointerEvent_GetCursorDelta**(`Input`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:42218](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42218)

___

### PointerEvent\_GetEffectingButton

▸ `Static` **PointerEvent_GetEffectingButton**(`Input`): [`Key`](ue_ue.Key.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`Key`](ue_ue.Key.md)

#### Defined in

[ue/ue.d.ts:42219](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42219)

___

### PointerEvent\_GetGestureDelta

▸ `Static` **PointerEvent_GetGestureDelta**(`Input`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:42220](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42220)

___

### PointerEvent\_GetGestureType

▸ `Static` **PointerEvent_GetGestureType**(`Input`): [`ESlateGesture`](../enums/ue_ue.ESlateGesture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`ESlateGesture`](../enums/ue_ue.ESlateGesture.md)

#### Defined in

[ue/ue.d.ts:42221](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42221)

___

### PointerEvent\_GetLastScreenSpacePosition

▸ `Static` **PointerEvent_GetLastScreenSpacePosition**(`Input`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:42222](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42222)

___

### PointerEvent\_GetPointerIndex

▸ `Static` **PointerEvent_GetPointerIndex**(`Input`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42223](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42223)

___

### PointerEvent\_GetScreenSpacePosition

▸ `Static` **PointerEvent_GetScreenSpacePosition**(`Input`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:42224](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42224)

___

### PointerEvent\_GetTouchpadIndex

▸ `Static` **PointerEvent_GetTouchpadIndex**(`Input`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42225](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42225)

___

### PointerEvent\_GetUserIndex

▸ `Static` **PointerEvent_GetUserIndex**(`Input`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42226](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42226)

___

### PointerEvent\_GetWheelDelta

▸ `Static` **PointerEvent_GetWheelDelta**(`Input`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:42227](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42227)

___

### PointerEvent\_IsMouseButtonDown

▸ `Static` **PointerEvent_IsMouseButtonDown**(`Input`, `MouseButton`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |
| `MouseButton` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42228](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42228)

___

### PointerEvent\_IsTouchEvent

▸ `Static` **PointerEvent_IsTouchEvent**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:42229](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42229)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:42230](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L42230)
