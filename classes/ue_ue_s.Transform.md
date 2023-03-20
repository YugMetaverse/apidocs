[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_s](../modules/ue_ue_s.md) / Transform

# Class: Transform

[ue/ue_s](../modules/ue_ue_s.md).Transform

## Table of contents

### Constructors

- [constructor](ue_ue_s.Transform.md#constructor)

### Properties

- [\_\_tid\_Transform\_\_](ue_ue_s.Transform.md#__tid_transform__)

### Methods

- [Accumulate](ue_ue_s.Transform.md#accumulate)
- [AddToTranslation](ue_ue_s.Transform.md#addtotranslation)
- [Blend](ue_ue_s.Transform.md#blend)
- [BlendWith](ue_ue_s.Transform.md#blendwith)
- [ConcatenateRotation](ue_ue_s.Transform.md#concatenaterotation)
- [ContainsNaN](ue_ue_s.Transform.md#containsnan)
- [CopyRotation](ue_ue_s.Transform.md#copyrotation)
- [CopyRotationPart](ue_ue_s.Transform.md#copyrotationpart)
- [CopyScale3D](ue_ue_s.Transform.md#copyscale3d)
- [CopyTranslation](ue_ue_s.Transform.md#copytranslation)
- [CopyTranslationAndScale3D](ue_ue_s.Transform.md#copytranslationandscale3d)
- [DebugPrint](ue_ue_s.Transform.md#debugprint)
- [DiagnosticCheckNaN\_All](ue_ue_s.Transform.md#diagnosticchecknan_all)
- [DiagnosticCheckNaN\_Rotate](ue_ue_s.Transform.md#diagnosticchecknan_rotate)
- [DiagnosticCheckNaN\_Scale3D](ue_ue_s.Transform.md#diagnosticchecknan_scale3d)
- [DiagnosticCheckNaN\_Translate](ue_ue_s.Transform.md#diagnosticchecknan_translate)
- [DiagnosticCheck\_IsValid](ue_ue_s.Transform.md#diagnosticcheck_isvalid)
- [Equals](ue_ue_s.Transform.md#equals)
- [EqualsNoScale](ue_ue_s.Transform.md#equalsnoscale)
- [GetDeterminant](ue_ue_s.Transform.md#getdeterminant)
- [GetLocation](ue_ue_s.Transform.md#getlocation)
- [GetMaximumAxisScale](ue_ue_s.Transform.md#getmaximumaxisscale)
- [GetMinimumAxisScale](ue_ue_s.Transform.md#getminimumaxisscale)
- [GetRelativeTransform](ue_ue_s.Transform.md#getrelativetransform)
- [GetRelativeTransformReverse](ue_ue_s.Transform.md#getrelativetransformreverse)
- [GetRotation](ue_ue_s.Transform.md#getrotation)
- [GetScale3D](ue_ue_s.Transform.md#getscale3d)
- [GetScaled](ue_ue_s.Transform.md#getscaled)
- [GetScaledAxis](ue_ue_s.Transform.md#getscaledaxis)
- [GetTranslation](ue_ue_s.Transform.md#gettranslation)
- [GetUnitAxis](ue_ue_s.Transform.md#getunitaxis)
- [InitFromString](ue_ue_s.Transform.md#initfromstring)
- [Inverse](ue_ue_s.Transform.md#inverse)
- [InverseTransformPosition](ue_ue_s.Transform.md#inversetransformposition)
- [InverseTransformPositionNoScale](ue_ue_s.Transform.md#inversetransformpositionnoscale)
- [InverseTransformRotation](ue_ue_s.Transform.md#inversetransformrotation)
- [InverseTransformVector](ue_ue_s.Transform.md#inversetransformvector)
- [InverseTransformVectorNoScale](ue_ue_s.Transform.md#inversetransformvectornoscale)
- [IsRotationNormalized](ue_ue_s.Transform.md#isrotationnormalized)
- [IsValid](ue_ue_s.Transform.md#isvalid)
- [Mirror](ue_ue_s.Transform.md#mirror)
- [MultiplyScale3D](ue_ue_s.Transform.md#multiplyscale3d)
- [NormalizeRotation](ue_ue_s.Transform.md#normalizerotation)
- [RemoveScaling](ue_ue_s.Transform.md#removescaling)
- [RotationEquals](ue_ue_s.Transform.md#rotationequals)
- [Rotator](ue_ue_s.Transform.md#rotator)
- [Scale3DEquals](ue_ue_s.Transform.md#scale3dequals)
- [ScaleTranslation](ue_ue_s.Transform.md#scaletranslation)
- [SetComponents](ue_ue_s.Transform.md#setcomponents)
- [SetIdentity](ue_ue_s.Transform.md#setidentity)
- [SetLocation](ue_ue_s.Transform.md#setlocation)
- [SetRotation](ue_ue_s.Transform.md#setrotation)
- [SetScale3D](ue_ue_s.Transform.md#setscale3d)
- [SetToRelativeTransform](ue_ue_s.Transform.md#settorelativetransform)
- [SetTranslation](ue_ue_s.Transform.md#settranslation)
- [SetTranslationAndScale3D](ue_ue_s.Transform.md#settranslationandscale3d)
- [ToHumanReadableString](ue_ue_s.Transform.md#tohumanreadablestring)
- [ToString](ue_ue_s.Transform.md#tostring)
- [TransformFVector4](ue_ue_s.Transform.md#transformfvector4)
- [TransformFVector4NoScale](ue_ue_s.Transform.md#transformfvector4noscale)
- [TransformPosition](ue_ue_s.Transform.md#transformposition)
- [TransformPositionNoScale](ue_ue_s.Transform.md#transformpositionnoscale)
- [TransformRotation](ue_ue_s.Transform.md#transformrotation)
- [TransformVector](ue_ue_s.Transform.md#transformvector)
- [TransformVectorNoScale](ue_ue_s.Transform.md#transformvectornoscale)
- [TranslationEquals](ue_ue_s.Transform.md#translationequals)
- [op\_Addition](ue_ue_s.Transform.md#op_addition)
- [op\_Multiply](ue_ue_s.Transform.md#op_multiply)
- [AddTranslations](ue_ue_s.Transform.md#addtranslations)
- [AnyHasNegativeScale](ue_ue_s.Transform.md#anyhasnegativescale)
- [AreRotationsEqual](ue_ue_s.Transform.md#arerotationsequal)
- [AreScale3DsEqual](ue_ue_s.Transform.md#arescale3dsequal)
- [AreTranslationsEqual](ue_ue_s.Transform.md#aretranslationsequal)
- [GetSafeScaleReciprocal](ue_ue_s.Transform.md#getsafescalereciprocal)
- [Multiply](ue_ue_s.Transform.md#multiply)
- [StaticClass](ue_ue_s.Transform.md#staticclass)
- [StaticStruct](ue_ue_s.Transform.md#staticstruct)
- [SubtractTranslations](ue_ue_s.Transform.md#subtracttranslations)

## Constructors

### constructor

• **new Transform**()

• **new Transform**(`InTranslation`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTranslation` | [`Vector`](ue_ue_s.Vector.md) |

• **new Transform**(`InRotation`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRotation` | [`Quat`](ue_ue_s.Quat.md) |

• **new Transform**(`InRotation`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

• **new Transform**(`InRotation`, `InTranslation`, `InScale3D`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRotation` | [`Quat`](ue_ue_s.Quat.md) |
| `InTranslation` | [`Vector`](ue_ue_s.Vector.md) |
| `InScale3D` | [`Vector`](ue_ue_s.Vector.md) |

• **new Transform**(`InRotation`, `InTranslation`, `InScale3D`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `InTranslation` | [`Vector`](ue_ue_s.Vector.md) |
| `InScale3D` | [`Vector`](ue_ue_s.Vector.md) |

• **new Transform**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

• **new Transform**(`InX`, `InY`, `InZ`, `InTranslation`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | [`Vector`](ue_ue_s.Vector.md) |
| `InY` | [`Vector`](ue_ue_s.Vector.md) |
| `InZ` | [`Vector`](ue_ue_s.Vector.md) |
| `InTranslation` | [`Vector`](ue_ue_s.Vector.md) |

## Properties

### \_\_tid\_Transform\_\_

• `Private` **\_\_tid\_Transform\_\_**: `boolean`

## Methods

### Accumulate

▸ **Accumulate**(`SourceAtom`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceAtom` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

___

### AddToTranslation

▸ **AddToTranslation**(`DeltaTranslation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTranslation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### Blend

▸ **Blend**(`Atom1`, `Atom2`, `Alpha`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Atom1` | [`Transform`](ue_ue_s.Transform.md) |
| `Atom2` | [`Transform`](ue_ue_s.Transform.md) |
| `Alpha` | `number` |

#### Returns

`void`

___

### BlendWith

▸ **BlendWith**(`OtherAtom`, `Alpha`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherAtom` | [`Transform`](ue_ue_s.Transform.md) |
| `Alpha` | `number` |

#### Returns

`void`

___

### ConcatenateRotation

▸ **ConcatenateRotation**(`DeltaRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaRotation` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`void`

___

### ContainsNaN

▸ **ContainsNaN**(): `boolean`

#### Returns

`boolean`

___

### CopyRotation

▸ **CopyRotation**(`Other`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

___

### CopyRotationPart

▸ **CopyRotationPart**(`SrcBA`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SrcBA` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

___

### CopyScale3D

▸ **CopyScale3D**(`Other`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

___

### CopyTranslation

▸ **CopyTranslation**(`Other`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

___

### CopyTranslationAndScale3D

▸ **CopyTranslationAndScale3D**(`SrcBA`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SrcBA` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

___

### DebugPrint

▸ **DebugPrint**(): `void`

#### Returns

`void`

___

### DiagnosticCheckNaN\_All

▸ **DiagnosticCheckNaN_All**(): `void`

#### Returns

`void`

___

### DiagnosticCheckNaN\_Rotate

▸ **DiagnosticCheckNaN_Rotate**(): `void`

#### Returns

`void`

___

### DiagnosticCheckNaN\_Scale3D

▸ **DiagnosticCheckNaN_Scale3D**(): `void`

#### Returns

`void`

___

### DiagnosticCheckNaN\_Translate

▸ **DiagnosticCheckNaN_Translate**(): `void`

#### Returns

`void`

___

### DiagnosticCheck\_IsValid

▸ **DiagnosticCheck_IsValid**(): `void`

#### Returns

`void`

___

### Equals

▸ **Equals**(`Other`, `Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### EqualsNoScale

▸ **EqualsNoScale**(`Other`, `Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### GetDeterminant

▸ **GetDeterminant**(): `number`

#### Returns

`number`

___

### GetLocation

▸ **GetLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetMaximumAxisScale

▸ **GetMaximumAxisScale**(): `number`

#### Returns

`number`

___

### GetMinimumAxisScale

▸ **GetMinimumAxisScale**(): `number`

#### Returns

`number`

___

### GetRelativeTransform

▸ **GetRelativeTransform**(`Other`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### GetRelativeTransformReverse

▸ **GetRelativeTransformReverse**(`Other`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### GetRotation

▸ **GetRotation**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### GetScale3D

▸ **GetScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetScaled

▸ **GetScaled**(`Scale`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

▸ **GetScaled**(`Scale`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### GetScaledAxis

▸ **GetScaledAxis**(`InAxis`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAxis` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetTranslation

▸ **GetTranslation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetUnitAxis

▸ **GetUnitAxis**(`InAxis`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAxis` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### InitFromString

▸ **InitFromString**(`InSourceString`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSourceString` | `string` |

#### Returns

`boolean`

___

### Inverse

▸ **Inverse**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### InverseTransformPosition

▸ **InverseTransformPosition**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### InverseTransformPositionNoScale

▸ **InverseTransformPositionNoScale**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### InverseTransformRotation

▸ **InverseTransformRotation**(`Q`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### InverseTransformVector

▸ **InverseTransformVector**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### InverseTransformVectorNoScale

▸ **InverseTransformVectorNoScale**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### IsRotationNormalized

▸ **IsRotationNormalized**(): `boolean`

#### Returns

`boolean`

___

### IsValid

▸ **IsValid**(): `boolean`

#### Returns

`boolean`

___

### Mirror

▸ **Mirror**(`MirrorAxis`, `FlipAxis`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MirrorAxis` | `number` |
| `FlipAxis` | `number` |

#### Returns

`void`

___

### MultiplyScale3D

▸ **MultiplyScale3D**(`Scale3DMultiplier`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale3DMultiplier` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### NormalizeRotation

▸ **NormalizeRotation**(): `void`

#### Returns

`void`

___

### RemoveScaling

▸ **RemoveScaling**(`Tolerance`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`void`

___

### RotationEquals

▸ **RotationEquals**(`Other`, `Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### Rotator

▸ **Rotator**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### Scale3DEquals

▸ **Scale3DEquals**(`Other`, `Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### ScaleTranslation

▸ **ScaleTranslation**(`InScale3D`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

▸ **ScaleTranslation**(`Scale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

`void`

___

### SetComponents

▸ **SetComponents**(`InRotation`, `InTranslation`, `InScale3D`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRotation` | [`Quat`](ue_ue_s.Quat.md) |
| `InTranslation` | [`Vector`](ue_ue_s.Vector.md) |
| `InScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### SetIdentity

▸ **SetIdentity**(): `void`

#### Returns

`void`

___

### SetLocation

▸ **SetLocation**(`Origin`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Origin` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### SetRotation

▸ **SetRotation**(`NewRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRotation` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`void`

___

### SetScale3D

▸ **SetScale3D**(`NewScale3D`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### SetToRelativeTransform

▸ **SetToRelativeTransform**(`ParentTransform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParentTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

___

### SetTranslation

▸ **SetTranslation**(`NewTranslation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTranslation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### SetTranslationAndScale3D

▸ **SetTranslationAndScale3D**(`NewTranslation`, `NewScale3D`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTranslation` | [`Vector`](ue_ue_s.Vector.md) |
| `NewScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### ToHumanReadableString

▸ **ToHumanReadableString**(): `string`

#### Returns

`string`

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

___

### TransformFVector4

▸ **TransformFVector4**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

___

### TransformFVector4NoScale

▸ **TransformFVector4NoScale**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

___

### TransformPosition

▸ **TransformPosition**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### TransformPositionNoScale

▸ **TransformPositionNoScale**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### TransformRotation

▸ **TransformRotation**(`Q`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### TransformVector

▸ **TransformVector**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### TransformVectorNoScale

▸ **TransformVectorNoScale**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### TranslationEquals

▸ **TranslationEquals**(`Other`, `Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### op\_Addition

▸ **op_Addition**(`Atom`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Atom` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### op\_Multiply

▸ **op_Multiply**(`Other`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

▸ **op_Multiply**(`Other`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### AddTranslations

▸ `Static` **AddTranslations**(`A`, `B`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Transform`](ue_ue_s.Transform.md) |
| `B` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### AnyHasNegativeScale

▸ `Static` **AnyHasNegativeScale**(`InScale3D`, `InOtherScale3D`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InScale3D` | [`Vector`](ue_ue_s.Vector.md) |
| `InOtherScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`boolean`

___

### AreRotationsEqual

▸ `Static` **AreRotationsEqual**(`A`, `B`, `Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Transform`](ue_ue_s.Transform.md) |
| `B` | [`Transform`](ue_ue_s.Transform.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### AreScale3DsEqual

▸ `Static` **AreScale3DsEqual**(`A`, `B`, `Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Transform`](ue_ue_s.Transform.md) |
| `B` | [`Transform`](ue_ue_s.Transform.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### AreTranslationsEqual

▸ `Static` **AreTranslationsEqual**(`A`, `B`, `Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Transform`](ue_ue_s.Transform.md) |
| `B` | [`Transform`](ue_ue_s.Transform.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### GetSafeScaleReciprocal

▸ `Static` **GetSafeScaleReciprocal**(`InScale`, `Tolerance`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InScale` | [`Vector`](ue_ue_s.Vector.md) |
| `Tolerance` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### Multiply

▸ `Static` **Multiply**(`OutTransform`, `A`, `B`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `A` | [`Transform`](ue_ue_s.Transform.md) |
| `B` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### SubtractTranslations

▸ `Static` **SubtractTranslations**(`A`, `B`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Transform`](ue_ue_s.Transform.md) |
| `B` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)
