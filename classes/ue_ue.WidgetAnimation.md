[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WidgetAnimation

# Class: WidgetAnimation

[ue/ue](../modules/ue_ue.md).WidgetAnimation

## Hierarchy

- [`MovieSceneSequence`](ue_ue.MovieSceneSequence.md)

  ↳ **`WidgetAnimation`**

## Table of contents

### Constructors

- [constructor](ue_ue.WidgetAnimation.md#constructor)

### Properties

- [AnimationBindings](ue_ue.WidgetAnimation.md#animationbindings)
- [DefaultCompletionMode](ue_ue.WidgetAnimation.md#defaultcompletionmode)
- [DisplayLabel](ue_ue.WidgetAnimation.md#displaylabel)
- [MovieScene](ue_ue.WidgetAnimation.md#moviescene)
- [OnAnimationFinished](ue_ue.WidgetAnimation.md#onanimationfinished)
- [OnAnimationStarted](ue_ue.WidgetAnimation.md#onanimationstarted)
- [PrecompiledEvaluationTemplate](ue_ue.WidgetAnimation.md#precompiledevaluationtemplate)
- [Signature](ue_ue.WidgetAnimation.md#signature)
- [\_\_tid\_MovieSceneSequence\_\_](ue_ue.WidgetAnimation.md#__tid_moviescenesequence__)
- [\_\_tid\_MovieSceneSignedObject\_\_](ue_ue.WidgetAnimation.md#__tid_moviescenesignedobject__)
- [\_\_tid\_Object\_\_](ue_ue.WidgetAnimation.md#__tid_object__)
- [\_\_tid\_WidgetAnimation\_\_](ue_ue.WidgetAnimation.md#__tid_widgetanimation__)
- [bLegacyFinishOnStop](ue_ue.WidgetAnimation.md#blegacyfinishonstop)
- [bParentContextsAreSignificant](ue_ue.WidgetAnimation.md#bparentcontextsaresignificant)
- [bPlayableDirectly](ue_ue.WidgetAnimation.md#bplayabledirectly)

### Methods

- [BindToAnimationFinished](ue_ue.WidgetAnimation.md#bindtoanimationfinished)
- [BindToAnimationStarted](ue_ue.WidgetAnimation.md#bindtoanimationstarted)
- [CreateDefaultSubobject](ue_ue.WidgetAnimation.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.WidgetAnimation.md#executeubergraph)
- [FindBindingByTag](ue_ue.WidgetAnimation.md#findbindingbytag)
- [FindBindingsByTag](ue_ue.WidgetAnimation.md#findbindingsbytag)
- [GetClass](ue_ue.WidgetAnimation.md#getclass)
- [GetEndTime](ue_ue.WidgetAnimation.md#getendtime)
- [GetName](ue_ue.WidgetAnimation.md#getname)
- [GetOuter](ue_ue.WidgetAnimation.md#getouter)
- [GetStartTime](ue_ue.WidgetAnimation.md#getstarttime)
- [GetWorld](ue_ue.WidgetAnimation.md#getworld)
- [UnbindAllFromAnimationFinished](ue_ue.WidgetAnimation.md#unbindallfromanimationfinished)
- [UnbindAllFromAnimationStarted](ue_ue.WidgetAnimation.md#unbindallfromanimationstarted)
- [UnbindFromAnimationFinished](ue_ue.WidgetAnimation.md#unbindfromanimationfinished)
- [UnbindFromAnimationStarted](ue_ue.WidgetAnimation.md#unbindfromanimationstarted)
- [Find](ue_ue.WidgetAnimation.md#find)
- [Load](ue_ue.WidgetAnimation.md#load)
- [StaticClass](ue_ue.WidgetAnimation.md#staticclass)

## Constructors

### constructor

• **new WidgetAnimation**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[constructor](ue_ue.MovieSceneSequence.md#constructor)

#### Defined in

[ue/ue.d.ts:11886](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11886)

## Properties

### AnimationBindings

• **AnimationBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`WidgetAnimationBinding`](ue_ue.WidgetAnimationBinding.md)\>

#### Defined in

[ue/ue.d.ts:11890](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11890)

___

### DefaultCompletionMode

• **DefaultCompletionMode**: [`EMovieSceneCompletionMode`](../enums/ue_ue.EMovieSceneCompletionMode.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[DefaultCompletionMode](ue_ue.MovieSceneSequence.md#defaultcompletionmode)

#### Defined in

[ue/ue.d.ts:11511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11511)

___

### DisplayLabel

• **DisplayLabel**: `string`

#### Defined in

[ue/ue.d.ts:11892](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11892)

___

### MovieScene

• **MovieScene**: [`MovieScene`](ue_ue.MovieScene.md)

#### Defined in

[ue/ue.d.ts:11889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11889)

___

### OnAnimationFinished

• **OnAnimationFinished**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:11888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11888)

___

### OnAnimationStarted

• **OnAnimationStarted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:11887](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11887)

___

### PrecompiledEvaluationTemplate

• **PrecompiledEvaluationTemplate**: [`MovieSceneEvaluationTemplate`](ue_ue.MovieSceneEvaluationTemplate.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[PrecompiledEvaluationTemplate](ue_ue.MovieSceneSequence.md#precompiledevaluationtemplate)

#### Defined in

[ue/ue.d.ts:11510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11510)

___

### Signature

• **Signature**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[Signature](ue_ue.MovieSceneSequence.md#signature)

#### Defined in

[ue/ue.d.ts:11034](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11034)

___

### \_\_tid\_MovieSceneSequence\_\_

• **\_\_tid\_MovieSceneSequence\_\_**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[__tid_MovieSceneSequence__](ue_ue.MovieSceneSequence.md#__tid_moviescenesequence__)

#### Defined in

[ue/ue.d.ts:11520](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11520)

___

### \_\_tid\_MovieSceneSignedObject\_\_

• **\_\_tid\_MovieSceneSignedObject\_\_**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[__tid_MovieSceneSignedObject__](ue_ue.MovieSceneSequence.md#__tid_moviescenesignedobject__)

#### Defined in

[ue/ue.d.ts:11039](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11039)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[__tid_Object__](ue_ue.MovieSceneSequence.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_WidgetAnimation\_\_

• **\_\_tid\_WidgetAnimation\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:11905](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11905)

___

### bLegacyFinishOnStop

• **bLegacyFinishOnStop**: `boolean`

#### Defined in

[ue/ue.d.ts:11891](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11891)

___

### bParentContextsAreSignificant

• **bParentContextsAreSignificant**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[bParentContextsAreSignificant](ue_ue.MovieSceneSequence.md#bparentcontextsaresignificant)

#### Defined in

[ue/ue.d.ts:11512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11512)

___

### bPlayableDirectly

• **bPlayableDirectly**: `boolean`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[bPlayableDirectly](ue_ue.MovieSceneSequence.md#bplayabledirectly)

#### Defined in

[ue/ue.d.ts:11513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11513)

## Methods

### BindToAnimationFinished

▸ **BindToAnimationFinished**(`Widget`, `Delegate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\> |
| `Delegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11893](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11893)

___

### BindToAnimationStarted

▸ **BindToAnimationStarted**(`Widget`, `Delegate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\> |
| `Delegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11894](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11894)

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

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[CreateDefaultSubobject](ue_ue.MovieSceneSequence.md#createdefaultsubobject)

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

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[ExecuteUbergraph](ue_ue.MovieSceneSequence.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### FindBindingByTag

▸ **FindBindingByTag**(`InBindingName`): [`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBindingName` | `string` |

#### Returns

[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[FindBindingByTag](ue_ue.MovieSceneSequence.md#findbindingbytag)

#### Defined in

[ue/ue.d.ts:11514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11514)

___

### FindBindingsByTag

▸ **FindBindingsByTag**(`InBindingName`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBindingName` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneObjectBindingID`](ue_ue.MovieSceneObjectBindingID.md)\>

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[FindBindingsByTag](ue_ue.MovieSceneSequence.md#findbindingsbytag)

#### Defined in

[ue/ue.d.ts:11515](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11515)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[GetClass](ue_ue.MovieSceneSequence.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetEndTime

▸ **GetEndTime**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:11895](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11895)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[GetName](ue_ue.MovieSceneSequence.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[GetOuter](ue_ue.MovieSceneSequence.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetStartTime

▸ **GetStartTime**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:11896](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11896)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[GetWorld](ue_ue.MovieSceneSequence.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### UnbindAllFromAnimationFinished

▸ **UnbindAllFromAnimationFinished**(`Widget`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11897)

___

### UnbindAllFromAnimationStarted

▸ **UnbindAllFromAnimationStarted**(`Widget`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11898](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11898)

___

### UnbindFromAnimationFinished

▸ **UnbindFromAnimationFinished**(`Widget`, `Delegate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\> |
| `Delegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11899](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11899)

___

### UnbindFromAnimationStarted

▸ **UnbindFromAnimationStarted**(`Widget`, `Delegate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\> |
| `Delegate` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:11900](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11900)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`WidgetAnimation`](ue_ue.WidgetAnimation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`WidgetAnimation`](ue_ue.WidgetAnimation.md)

#### Overrides

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[Find](ue_ue.MovieSceneSequence.md#find)

#### Defined in

[ue/ue.d.ts:11902](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11902)

___

### Load

▸ `Static` **Load**(`InName`): [`WidgetAnimation`](ue_ue.WidgetAnimation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`WidgetAnimation`](ue_ue.WidgetAnimation.md)

#### Overrides

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[Load](ue_ue.MovieSceneSequence.md#load)

#### Defined in

[ue/ue.d.ts:11903](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11903)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneSequence](ue_ue.MovieSceneSequence.md).[StaticClass](ue_ue.MovieSceneSequence.md#staticclass)

#### Defined in

[ue/ue.d.ts:11901](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11901)
