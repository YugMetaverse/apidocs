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

#### Defined in

[ue/ue_s.d.ts:287](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L287)

• **new Transform**(`InTranslation`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTranslation` | [`Vector`](ue_ue_s.Vector.md) |

#### Defined in

[ue/ue_s.d.ts:288](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L288)

• **new Transform**(`InRotation`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRotation` | [`Quat`](ue_ue_s.Quat.md) |

#### Defined in

[ue/ue_s.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L289)

• **new Transform**(`InRotation`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Defined in

[ue/ue_s.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L290)

• **new Transform**(`InRotation`, `InTranslation`, `InScale3D`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRotation` | [`Quat`](ue_ue_s.Quat.md) |
| `InTranslation` | [`Vector`](ue_ue_s.Vector.md) |
| `InScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Defined in

[ue/ue_s.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L291)

• **new Transform**(`InRotation`, `InTranslation`, `InScale3D`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `InTranslation` | [`Vector`](ue_ue_s.Vector.md) |
| `InScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Defined in

[ue/ue_s.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L292)

• **new Transform**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

#### Defined in

[ue/ue_s.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L293)

• **new Transform**(`InX`, `InY`, `InZ`, `InTranslation`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | [`Vector`](ue_ue_s.Vector.md) |
| `InY` | [`Vector`](ue_ue_s.Vector.md) |
| `InZ` | [`Vector`](ue_ue_s.Vector.md) |
| `InTranslation` | [`Vector`](ue_ue_s.Vector.md) |

#### Defined in

[ue/ue_s.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L294)

## Properties

### \_\_tid\_Transform\_\_

• `Private` **\_\_tid\_Transform\_\_**: `boolean`

#### Defined in

[ue/ue_s.d.ts:381](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L381)

## Methods

### Accumulate

▸ **Accumulate**(`SourceAtom`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceAtom` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:366](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L366)

___

### AddToTranslation

▸ **AddToTranslation**(`DeltaTranslation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTranslation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:358](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L358)

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

#### Defined in

[ue/ue_s.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L305)

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

#### Defined in

[ue/ue_s.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L306)

___

### ConcatenateRotation

▸ **ConcatenateRotation**(`DeltaRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaRotation` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:357](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L357)

___

### ContainsNaN

▸ **ContainsNaN**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L341)

___

### CopyRotation

▸ **CopyRotation**(`Other`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:362](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L362)

___

### CopyRotationPart

▸ **CopyRotationPart**(`SrcBA`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SrcBA` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:372](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L372)

___

### CopyScale3D

▸ **CopyScale3D**(`Other`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:364](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L364)

___

### CopyTranslation

▸ **CopyTranslation**(`Other`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:356](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L356)

___

### CopyTranslationAndScale3D

▸ **CopyTranslationAndScale3D**(`SrcBA`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SrcBA` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:373](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L373)

___

### DebugPrint

▸ **DebugPrint**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L300)

___

### DiagnosticCheckNaN\_All

▸ **DiagnosticCheckNaN_All**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L298)

___

### DiagnosticCheckNaN\_Rotate

▸ **DiagnosticCheckNaN_Rotate**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L296)

___

### DiagnosticCheckNaN\_Scale3D

▸ **DiagnosticCheckNaN_Scale3D**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L297)

___

### DiagnosticCheckNaN\_Translate

▸ **DiagnosticCheckNaN_Translate**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L295)

___

### DiagnosticCheck\_IsValid

▸ **DiagnosticCheck_IsValid**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L299)

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

#### Defined in

[ue/ue_s.d.ts:349](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L349)

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

#### Defined in

[ue/ue_s.d.ts:350](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L350)

___

### GetDeterminant

▸ **GetDeterminant**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L339)

___

### GetLocation

▸ **GetLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L337)

___

### GetMaximumAxisScale

▸ **GetMaximumAxisScale**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L314)

___

### GetMinimumAxisScale

▸ **GetMinimumAxisScale**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L315)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(`Other`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue_s.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L316)

___

### GetRelativeTransformReverse

▸ **GetRelativeTransformReverse**(`Other`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue_s.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L317)

___

### GetRotation

▸ **GetRotation**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:369](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L369)

___

### GetScale3D

▸ **GetScale3D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:371](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L371)

___

### GetScaled

▸ **GetScaled**(`Scale`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue_s.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L331)

▸ **GetScaled**(`Scale`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue_s.d.ts:332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L332)

___

### GetScaledAxis

▸ **GetScaledAxis**(`InAxis`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAxis` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L333)

___

### GetTranslation

▸ **GetTranslation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:370](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L370)

___

### GetUnitAxis

▸ **GetUnitAxis**(`InAxis`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAxis` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L334)

___

### InitFromString

▸ **InitFromString**(`InSourceString`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSourceString` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L303)

___

### Inverse

▸ **Inverse**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue_s.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L304)

___

### InverseTransformPosition

▸ **InverseTransformPosition**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L323)

___

### InverseTransformPositionNoScale

▸ **InverseTransformPositionNoScale**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L324)

___

### InverseTransformRotation

▸ **InverseTransformRotation**(`Q`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L330)

___

### InverseTransformVector

▸ **InverseTransformVector**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L327)

___

### InverseTransformVectorNoScale

▸ **InverseTransformVectorNoScale**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L328)

___

### IsRotationNormalized

▸ **IsRotationNormalized**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:368](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L368)

___

### IsValid

▸ **IsValid**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:342](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L342)

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

#### Defined in

[ue/ue_s.d.ts:335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L335)

___

### MultiplyScale3D

▸ **MultiplyScale3D**(`Scale3DMultiplier`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale3DMultiplier` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:354](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L354)

___

### NormalizeRotation

▸ **NormalizeRotation**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:367](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L367)

___

### RemoveScaling

▸ **RemoveScaling**(`Tolerance`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L313)

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

#### Defined in

[ue/ue_s.d.ts:346](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L346)

___

### Rotator

▸ **Rotator**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L338)

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

#### Defined in

[ue/ue_s.d.ts:348](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L348)

___

### ScaleTranslation

▸ **ScaleTranslation**(`InScale3D`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L311)

▸ **ScaleTranslation**(`Scale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L312)

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

#### Defined in

[ue/ue_s.d.ts:352](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L352)

___

### SetIdentity

▸ **SetIdentity**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:353](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L353)

___

### SetLocation

▸ **SetLocation**(`Origin`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Origin` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L340)

___

### SetRotation

▸ **SetRotation**(`NewRotation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRotation` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:361](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L361)

___

### SetScale3D

▸ **SetScale3D**(`NewScale3D`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:363](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L363)

___

### SetToRelativeTransform

▸ **SetToRelativeTransform**(`ParentTransform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParentTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:318](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L318)

___

### SetTranslation

▸ **SetTranslation**(`NewTranslation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTranslation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:355](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L355)

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

#### Defined in

[ue/ue_s.d.ts:365](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L365)

___

### ToHumanReadableString

▸ **ToHumanReadableString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L301)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L302)

___

### TransformFVector4

▸ **TransformFVector4**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue_s.d.ts:319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L319)

___

### TransformFVector4NoScale

▸ **TransformFVector4NoScale**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue_s.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L320)

___

### TransformPosition

▸ **TransformPosition**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L321)

___

### TransformPositionNoScale

▸ **TransformPositionNoScale**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L322)

___

### TransformRotation

▸ **TransformRotation**(`Q`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L329)

___

### TransformVector

▸ **TransformVector**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L325)

___

### TransformVectorNoScale

▸ **TransformVectorNoScale**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L326)

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

#### Defined in

[ue/ue_s.d.ts:347](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L347)

___

### op\_Addition

▸ **op_Addition**(`Atom`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Atom` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue_s.d.ts:307](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L307)

___

### op\_Multiply

▸ **op_Multiply**(`Other`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue_s.d.ts:308](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L308)

▸ **op_Multiply**(`Other`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue_s.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L309)

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

#### Defined in

[ue/ue_s.d.ts:359](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L359)

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

#### Defined in

[ue/ue_s.d.ts:310](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L310)

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

#### Defined in

[ue/ue_s.d.ts:343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L343)

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

#### Defined in

[ue/ue_s.d.ts:345](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L345)

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

#### Defined in

[ue/ue_s.d.ts:344](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L344)

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

#### Defined in

[ue/ue_s.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L336)

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

#### Defined in

[ue/ue_s.d.ts:351](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L351)

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:378](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L378)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:379](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L379)

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

#### Defined in

[ue/ue_s.d.ts:360](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L360)
