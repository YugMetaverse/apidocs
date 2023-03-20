[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapHandTrackingFunctionLibrary

# Class: MagicLeapHandTrackingFunctionLibrary

[ue/ue](../modules/ue_ue.md).MagicLeapHandTrackingFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`MagicLeapHandTrackingFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_MagicLeapHandTrackingFunctionLibrary\_\_](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#__tid_magicleaphandtrackingfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#getclass)
- [GetName](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#getname)
- [GetOuter](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#getworld)
- [Find](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#find)
- [GetConfiguration](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#getconfiguration)
- [GetCurrentGesture](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#getcurrentgesture)
- [GetCurrentGestureConfidence](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#getcurrentgestureconfidence)
- [GetGestureKeypointTransform](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#getgesturekeypointtransform)
- [GetGestureKeypoints](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#getgesturekeypoints)
- [GetHandCenter](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#gethandcenter)
- [GetHandCenterNormalized](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#gethandcenternormalized)
- [GetHandIndexFingerTip](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#gethandindexfingertip)
- [GetHandThumbTip](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#gethandthumbtip)
- [GetMagicLeapHandTrackingLiveLinkSource](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#getmagicleaphandtrackinglivelinksource)
- [GetStaticGestureConfidenceThreshold](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#getstaticgestureconfidencethreshold)
- [Load](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#load)
- [SetConfiguration](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#setconfiguration)
- [SetStaticGestureConfidenceThreshold](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#setstaticgestureconfidencethreshold)
- [StaticClass](ue_ue.MagicLeapHandTrackingFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new MagicLeapHandTrackingFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:46709](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46709)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_MagicLeapHandTrackingFunctionLibrary\_\_

• **\_\_tid\_MagicLeapHandTrackingFunctionLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:46727](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46727)

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MagicLeapHandTrackingFunctionLibrary`](ue_ue.MagicLeapHandTrackingFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MagicLeapHandTrackingFunctionLibrary`](ue_ue.MagicLeapHandTrackingFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:46724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46724)

___

### GetConfiguration

▸ `Static` **GetConfiguration**(`ActiveStaticGestures`, `KeypointsFilterLevel`, `GestureFilterLevel`, `bTrackingEnabled`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActiveStaticGestures` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EMagicLeapHandTrackingGesture`](../enums/ue_ue.EMagicLeapHandTrackingGesture.md)\>\> |
| `KeypointsFilterLevel` | [`$Ref`](../interfaces/puerts._Ref.md)<[`EMagicLeapHandTrackingKeypointFilterLevel`](../enums/ue_ue.EMagicLeapHandTrackingKeypointFilterLevel.md)\> |
| `GestureFilterLevel` | [`$Ref`](../interfaces/puerts._Ref.md)<[`EMagicLeapHandTrackingGestureFilterLevel`](../enums/ue_ue.EMagicLeapHandTrackingGestureFilterLevel.md)\> |
| `bTrackingEnabled` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46710](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46710)

___

### GetCurrentGesture

▸ `Static` **GetCurrentGesture**(`Hand`, `Gesture`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `Gesture` | [`$Ref`](../interfaces/puerts._Ref.md)<[`EMagicLeapHandTrackingGesture`](../enums/ue_ue.EMagicLeapHandTrackingGesture.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46711](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46711)

___

### GetCurrentGestureConfidence

▸ `Static` **GetCurrentGestureConfidence**(`Hand`, `Confidence`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `Confidence` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46712](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46712)

___

### GetGestureKeypointTransform

▸ `Static` **GetGestureKeypointTransform**(`Hand`, `Keypoint`, `TransformSpace`, `Transform`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `Keypoint` | [`EMagicLeapHandTrackingKeypoint`](../enums/ue_ue.EMagicLeapHandTrackingKeypoint.md) |
| `TransformSpace` | [`EMagicLeapGestureTransformSpace`](../enums/ue_ue.EMagicLeapGestureTransformSpace.md) |
| `Transform` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Transform`](ue_ue_s.Transform.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46714](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46714)

___

### GetGestureKeypoints

▸ `Static` **GetGestureKeypoints**(`Hand`, `Keypoints`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `Keypoints` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46713](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46713)

___

### GetHandCenter

▸ `Static` **GetHandCenter**(`Hand`, `HandCenter`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `HandCenter` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Transform`](ue_ue_s.Transform.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46715)

___

### GetHandCenterNormalized

▸ `Static` **GetHandCenterNormalized**(`Hand`, `HandCenterNormalized`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `HandCenterNormalized` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46716)

___

### GetHandIndexFingerTip

▸ `Static` **GetHandIndexFingerTip**(`Hand`, `TransformSpace`, `Pointer`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `TransformSpace` | [`EMagicLeapGestureTransformSpace`](../enums/ue_ue.EMagicLeapGestureTransformSpace.md) |
| `Pointer` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Transform`](ue_ue_s.Transform.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46717](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46717)

___

### GetHandThumbTip

▸ `Static` **GetHandThumbTip**(`Hand`, `TransformSpace`, `Secondary`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `TransformSpace` | [`EMagicLeapGestureTransformSpace`](../enums/ue_ue.EMagicLeapGestureTransformSpace.md) |
| `Secondary` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Transform`](ue_ue_s.Transform.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46718)

___

### GetMagicLeapHandTrackingLiveLinkSource

▸ `Static` **GetMagicLeapHandTrackingLiveLinkSource**(`SourceHandle`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceHandle` | [`$Ref`](../interfaces/puerts._Ref.md)<[`LiveLinkSourceHandle`](ue_ue.LiveLinkSourceHandle.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46719)

___

### GetStaticGestureConfidenceThreshold

▸ `Static` **GetStaticGestureConfidenceThreshold**(`Gesture`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Gesture` | [`EMagicLeapHandTrackingGesture`](../enums/ue_ue.EMagicLeapHandTrackingGesture.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:46720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46720)

___

### Load

▸ `Static` **Load**(`InName`): [`MagicLeapHandTrackingFunctionLibrary`](ue_ue.MagicLeapHandTrackingFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MagicLeapHandTrackingFunctionLibrary`](ue_ue.MagicLeapHandTrackingFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:46725](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46725)

___

### SetConfiguration

▸ `Static` **SetConfiguration**(`StaticGesturesToActivate`, `KeypointsFilterLevel?`, `GestureFilterLevel?`, `bTrackingEnabled?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StaticGesturesToActivate` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EMagicLeapHandTrackingGesture`](../enums/ue_ue.EMagicLeapHandTrackingGesture.md)\> |
| `KeypointsFilterLevel?` | [`EMagicLeapHandTrackingKeypointFilterLevel`](../enums/ue_ue.EMagicLeapHandTrackingKeypointFilterLevel.md) |
| `GestureFilterLevel?` | [`EMagicLeapHandTrackingGestureFilterLevel`](../enums/ue_ue.EMagicLeapHandTrackingGestureFilterLevel.md) |
| `bTrackingEnabled?` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:46721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46721)

___

### SetStaticGestureConfidenceThreshold

▸ `Static` **SetStaticGestureConfidenceThreshold**(`Gesture`, `Confidence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Gesture` | [`EMagicLeapHandTrackingGesture`](../enums/ue_ue.EMagicLeapHandTrackingGesture.md) |
| `Confidence` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:46722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46722)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:46723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L46723)
