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

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_KismetInputLibrary\_\_

• **\_\_tid\_KismetInputLibrary\_\_**: `boolean`

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

### CalibrateTilt

▸ `Static` **CalibrateTilt**(): `void`

#### Returns

`void`

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

___

### GetAnalogValue

▸ `Static` **GetAnalogValue**(`Input`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`AnalogInputEvent`](ue_ue.AnalogInputEvent.md) |

#### Returns

`number`

___

### GetKey

▸ `Static` **GetKey**(`Input`): [`Key`](ue_ue.Key.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`KeyEvent`](ue_ue.KeyEvent.md) |

#### Returns

[`Key`](ue_ue.Key.md)

___

### GetUserIndex

▸ `Static` **GetUserIndex**(`Input`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`KeyEvent`](ue_ue.KeyEvent.md) |

#### Returns

`number`

___

### InputChord\_GetDisplayName

▸ `Static` **InputChord_GetDisplayName**(`Key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`InputChord`](ue_ue.InputChord.md) |

#### Returns

`string`

___

### InputEvent\_IsAltDown

▸ `Static` **InputEvent_IsAltDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

___

### InputEvent\_IsCommandDown

▸ `Static` **InputEvent_IsCommandDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

___

### InputEvent\_IsControlDown

▸ `Static` **InputEvent_IsControlDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

___

### InputEvent\_IsLeftAltDown

▸ `Static` **InputEvent_IsLeftAltDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

___

### InputEvent\_IsLeftCommandDown

▸ `Static` **InputEvent_IsLeftCommandDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

___

### InputEvent\_IsLeftControlDown

▸ `Static` **InputEvent_IsLeftControlDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

___

### InputEvent\_IsLeftShiftDown

▸ `Static` **InputEvent_IsLeftShiftDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

___

### InputEvent\_IsRepeat

▸ `Static` **InputEvent_IsRepeat**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

___

### InputEvent\_IsRightAltDown

▸ `Static` **InputEvent_IsRightAltDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

___

### InputEvent\_IsRightCommandDown

▸ `Static` **InputEvent_IsRightCommandDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

___

### InputEvent\_IsRightControlDown

▸ `Static` **InputEvent_IsRightControlDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

___

### InputEvent\_IsRightShiftDown

▸ `Static` **InputEvent_IsRightShiftDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

___

### InputEvent\_IsShiftDown

▸ `Static` **InputEvent_IsShiftDown**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`InputEvent`](ue_ue.InputEvent.md) |

#### Returns

`boolean`

___

### Key\_GetDisplayName

▸ `Static` **Key_GetDisplayName**(`Key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`string`

___

### Key\_GetNavigationAction

▸ `Static` **Key_GetNavigationAction**(`InKey`): [`EUINavigationAction`](../enums/ue_ue.EUINavigationAction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKey` | [`Key`](ue_ue.Key.md) |

#### Returns

[`EUINavigationAction`](../enums/ue_ue.EUINavigationAction.md)

___

### Key\_GetNavigationActionFromKey

▸ `Static` **Key_GetNavigationActionFromKey**(`InKeyEvent`): [`EUINavigationAction`](../enums/ue_ue.EUINavigationAction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKeyEvent` | [`KeyEvent`](ue_ue.KeyEvent.md) |

#### Returns

[`EUINavigationAction`](../enums/ue_ue.EUINavigationAction.md)

___

### Key\_GetNavigationDirectionFromAnalog

▸ `Static` **Key_GetNavigationDirectionFromAnalog**(`InAnalogEvent`): [`EUINavigation`](../enums/ue_ue.EUINavigation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAnalogEvent` | [`AnalogInputEvent`](ue_ue.AnalogInputEvent.md) |

#### Returns

[`EUINavigation`](../enums/ue_ue.EUINavigation.md)

___

### Key\_GetNavigationDirectionFromKey

▸ `Static` **Key_GetNavigationDirectionFromKey**(`InKeyEvent`): [`EUINavigation`](../enums/ue_ue.EUINavigation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InKeyEvent` | [`KeyEvent`](ue_ue.KeyEvent.md) |

#### Returns

[`EUINavigation`](../enums/ue_ue.EUINavigation.md)

___

### Key\_IsFloatAxis

▸ `Static` **Key_IsFloatAxis**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

___

### Key\_IsGamepadKey

▸ `Static` **Key_IsGamepadKey**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

___

### Key\_IsKeyboardKey

▸ `Static` **Key_IsKeyboardKey**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

___

### Key\_IsModifierKey

▸ `Static` **Key_IsModifierKey**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

___

### Key\_IsMouseButton

▸ `Static` **Key_IsMouseButton**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

___

### Key\_IsValid

▸ `Static` **Key_IsValid**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

___

### Key\_IsVectorAxis

▸ `Static` **Key_IsVectorAxis**(`Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | [`Key`](ue_ue.Key.md) |

#### Returns

`boolean`

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

___

### PointerEvent\_GetCursorDelta

▸ `Static` **PointerEvent_GetCursorDelta**(`Input`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### PointerEvent\_GetEffectingButton

▸ `Static` **PointerEvent_GetEffectingButton**(`Input`): [`Key`](ue_ue.Key.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`Key`](ue_ue.Key.md)

___

### PointerEvent\_GetGestureDelta

▸ `Static` **PointerEvent_GetGestureDelta**(`Input`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### PointerEvent\_GetGestureType

▸ `Static` **PointerEvent_GetGestureType**(`Input`): [`ESlateGesture`](../enums/ue_ue.ESlateGesture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`ESlateGesture`](../enums/ue_ue.ESlateGesture.md)

___

### PointerEvent\_GetLastScreenSpacePosition

▸ `Static` **PointerEvent_GetLastScreenSpacePosition**(`Input`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### PointerEvent\_GetPointerIndex

▸ `Static` **PointerEvent_GetPointerIndex**(`Input`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`number`

___

### PointerEvent\_GetScreenSpacePosition

▸ `Static` **PointerEvent_GetScreenSpacePosition**(`Input`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### PointerEvent\_GetTouchpadIndex

▸ `Static` **PointerEvent_GetTouchpadIndex**(`Input`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`number`

___

### PointerEvent\_GetUserIndex

▸ `Static` **PointerEvent_GetUserIndex**(`Input`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`number`

___

### PointerEvent\_GetWheelDelta

▸ `Static` **PointerEvent_GetWheelDelta**(`Input`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`number`

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

___

### PointerEvent\_IsTouchEvent

▸ `Static` **PointerEvent_IsTouchEvent**(`Input`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Input` | [`PointerEvent`](ue_ue.PointerEvent.md) |

#### Returns

`boolean`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
