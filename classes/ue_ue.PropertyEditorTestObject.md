[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PropertyEditorTestObject

# Class: PropertyEditorTestObject

[ue/ue](../modules/ue_ue.md).PropertyEditorTestObject

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PropertyEditorTestObject`**

## Table of contents

### Constructors

- [constructor](ue_ue.PropertyEditorTestObject.md#constructor)

### Properties

- [ActorPropertyArray](ue_ue.PropertyEditorTestObject.md#actorpropertyarray)
- [ActorSet](ue_ue.PropertyEditorTestObject.md#actorset)
- [AnimClassInterface](ue_ue.PropertyEditorTestObject.md#animclassinterface)
- [AnyMaterialInterface](ue_ue.PropertyEditorTestObject.md#anymaterialinterface)
- [ArrayOfEditInlineNewSMCs](ue_ue.PropertyEditorTestObject.md#arrayofeditinlinenewsmcs)
- [ArrayOfStructs](ue_ue.PropertyEditorTestObject.md#arrayofstructs)
- [ArrayOfStructsWithEditCondition](ue_ue.PropertyEditorTestObject.md#arrayofstructswitheditcondition)
- [ArrayWithEditCondition](ue_ue.PropertyEditorTestObject.md#arraywitheditcondition)
- [AssetReferenceCustomStruct](ue_ue.PropertyEditorTestObject.md#assetreferencecustomstruct)
- [AssetReferenceCustomStructWithEditCondition](ue_ue.PropertyEditorTestObject.md#assetreferencecustomstructwitheditcondition)
- [AssetReferenceCustomStructWithThumbnail](ue_ue.PropertyEditorTestObject.md#assetreferencecustomstructwiththumbnail)
- [BlendableInterface](ue_ue.PropertyEditorTestObject.md#blendableinterface)
- [BoolProperty](ue_ue.PropertyEditorTestObject.md#boolproperty)
- [BoolPropertyArray](ue_ue.PropertyEditorTestObject.md#boolpropertyarray)
- [ByteProperty](ue_ue.PropertyEditorTestObject.md#byteproperty)
- [BytePropertyArray](ue_ue.PropertyEditorTestObject.md#bytepropertyarray)
- [ClassProperty](ue_ue.PropertyEditorTestObject.md#classproperty)
- [ClassPropertyWithAllowed](ue_ue.PropertyEditorTestObject.md#classpropertywithallowed)
- [ClassPropertyWithDisallowed](ue_ue.PropertyEditorTestObject.md#classpropertywithdisallowed)
- [ColorProperty](ue_ue.PropertyEditorTestObject.md#colorproperty)
- [ColorPropertyArray](ue_ue.PropertyEditorTestObject.md#colorpropertyarray)
- [DateTime](ue_ue.PropertyEditorTestObject.md#datetime)
- [DoubleProperty](ue_ue.PropertyEditorTestObject.md#doubleproperty)
- [EditColorSet](ue_ue.PropertyEditorTestObject.md#editcolorset)
- [EditInlineNewStaticMeshComponent](ue_ue.PropertyEditorTestObject.md#editinlinenewstaticmeshcomponent)
- [EnumAsByteEditCondition](ue_ue.PropertyEditorTestObject.md#enumasbyteeditcondition)
- [EnumByteProperty](ue_ue.PropertyEditorTestObject.md#enumbyteproperty)
- [EnumEditCondition](ue_ue.PropertyEditorTestObject.md#enumeditcondition)
- [EnumProperty](ue_ue.PropertyEditorTestObject.md#enumproperty)
- [EnumPropertyArray](ue_ue.PropertyEditorTestObject.md#enumpropertyarray)
- [ExactPointOrSpotLightActorReference](ue_ue.PropertyEditorTestObject.md#exactpointorspotlightactorreference)
- [ExactlyPointLightActorReference](ue_ue.PropertyEditorTestObject.md#exactlypointlightactorreference)
- [FixedArrayOfInts](ue_ue.PropertyEditorTestObject.md#fixedarrayofints)
- [FloatEditCondition](ue_ue.PropertyEditorTestObject.md#floateditcondition)
- [FloatProperty](ue_ue.PropertyEditorTestObject.md#floatproperty)
- [FloatPropertyArray](ue_ue.PropertyEditorTestObject.md#floatpropertyarray)
- [FloatPropertyWithClampedRange](ue_ue.PropertyEditorTestObject.md#floatpropertywithclampedrange)
- [FloatSet](ue_ue.PropertyEditorTestObject.md#floatset)
- [InlineProperty](ue_ue.PropertyEditorTestObject.md#inlineproperty)
- [Int16Property](ue_ue.PropertyEditorTestObject.md#int16property)
- [Int32Property](ue_ue.PropertyEditorTestObject.md#int32property)
- [Int32Set](ue_ue.PropertyEditorTestObject.md#int32set)
- [Int32ToStringMap](ue_ue.PropertyEditorTestObject.md#int32tostringmap)
- [Int32ToStructMap](ue_ue.PropertyEditorTestObject.md#int32tostructmap)
- [Int64Property](ue_ue.PropertyEditorTestObject.md#int64property)
- [Int8Property](ue_ue.PropertyEditorTestObject.md#int8property)
- [IntPointProperty](ue_ue.PropertyEditorTestObject.md#intpointproperty)
- [IntProperty32Array](ue_ue.PropertyEditorTestObject.md#intproperty32array)
- [IntPropertyWithClampedRange](ue_ue.PropertyEditorTestObject.md#intpropertywithclampedrange)
- [IntThatCannotBeChanged](ue_ue.PropertyEditorTestObject.md#intthatcannotbechanged)
- [IntToCustomMap](ue_ue.PropertyEditorTestObject.md#inttocustommap)
- [IntToEnumMap](ue_ue.PropertyEditorTestObject.md#inttoenummap)
- [IntToSubStructMap](ue_ue.PropertyEditorTestObject.md#inttosubstructmap)
- [IntegerEditCondition](ue_ue.PropertyEditorTestObject.md#integereditcondition)
- [LightActorReference](ue_ue.PropertyEditorTestObject.md#lightactorreference)
- [LightOrStaticMeshActorReference](ue_ue.PropertyEditorTestObject.md#lightorstaticmeshactorreference)
- [LightPropagationVolumeBlendable](ue_ue.PropertyEditorTestObject.md#lightpropagationvolumeblendable)
- [LinearColorProperty](ue_ue.PropertyEditorTestObject.md#linearcolorproperty)
- [LinearColorPropertyArray](ue_ue.PropertyEditorTestObject.md#linearcolorpropertyarray)
- [LinearColorSet](ue_ue.PropertyEditorTestObject.md#linearcolorset)
- [LinearColorToStringMap](ue_ue.PropertyEditorTestObject.md#linearcolortostringmap)
- [LinearColorToVectorMap](ue_ue.PropertyEditorTestObject.md#linearcolortovectormap)
- [MaterialOrTextureAssetReference](ue_ue.PropertyEditorTestObject.md#materialortextureassetreference)
- [MatrixProperty](ue_ue.PropertyEditorTestObject.md#matrixproperty)
- [NameProperty](ue_ue.PropertyEditorTestObject.md#nameproperty)
- [NamePropertyArray](ue_ue.PropertyEditorTestObject.md#namepropertyarray)
- [NameSet](ue_ue.PropertyEditorTestObject.md#nameset)
- [NameToNameMap](ue_ue.PropertyEditorTestObject.md#nametonamemap)
- [NotLightActorReference](ue_ue.PropertyEditorTestObject.md#notlightactorreference)
- [ObjectProperty](ue_ue.PropertyEditorTestObject.md#objectproperty)
- [ObjectPropertyArray](ue_ue.PropertyEditorTestObject.md#objectpropertyarray)
- [ObjectSet](ue_ue.PropertyEditorTestObject.md#objectset)
- [ObjectThatCannotBeChanged](ue_ue.PropertyEditorTestObject.md#objectthatcannotbechanged)
- [ObjectToColorMap](ue_ue.PropertyEditorTestObject.md#objecttocolormap)
- [ObjectToInt32Map](ue_ue.PropertyEditorTestObject.md#objecttoint32map)
- [OnlyActorsAllowed](ue_ue.PropertyEditorTestObject.md#onlyactorsallowed)
- [PropertyThatHides](ue_ue.PropertyEditorTestObject.md#propertythathides)
- [RichCurve](ue_ue.PropertyEditorTestObject.md#richcurve)
- [RotatorProperty](ue_ue.PropertyEditorTestObject.md#rotatorproperty)
- [RotatorPropertyArray](ue_ue.PropertyEditorTestObject.md#rotatorpropertyarray)
- [SimplePropertyWithEditCondition](ue_ue.PropertyEditorTestObject.md#simplepropertywitheditcondition)
- [StaticArrayOfInts](ue_ue.PropertyEditorTestObject.md#staticarrayofints)
- [StaticArrayOfIntsWithEnumLabels](ue_ue.PropertyEditorTestObject.md#staticarrayofintswithenumlabels)
- [StaticMeshProp](ue_ue.PropertyEditorTestObject.md#staticmeshprop)
- [StringPasswordProperty](ue_ue.PropertyEditorTestObject.md#stringpasswordproperty)
- [StringProperty](ue_ue.PropertyEditorTestObject.md#stringproperty)
- [StringPropertyArray](ue_ue.PropertyEditorTestObject.md#stringpropertyarray)
- [StringSet](ue_ue.PropertyEditorTestObject.md#stringset)
- [StringThatCannotBeChanged](ue_ue.PropertyEditorTestObject.md#stringthatcannotbechanged)
- [StringToActorMap](ue_ue.PropertyEditorTestObject.md#stringtoactormap)
- [StringToColorMap](ue_ue.PropertyEditorTestObject.md#stringtocolormap)
- [StringToFloatMap](ue_ue.PropertyEditorTestObject.md#stringtofloatmap)
- [StringToObjectMap](ue_ue.PropertyEditorTestObject.md#stringtoobjectmap)
- [Struct](ue_ue.PropertyEditorTestObject.md#struct)
- [StructPropertyArray](ue_ue.PropertyEditorTestObject.md#structpropertyarray)
- [StructWithMultipleInstances1](ue_ue.PropertyEditorTestObject.md#structwithmultipleinstances1)
- [StructWithMultipleInstances2](ue_ue.PropertyEditorTestObject.md#structwithmultipleinstances2)
- [SubclassOfTexture](ue_ue.PropertyEditorTestObject.md#subclassoftexture)
- [SubclassOfWithAllowed](ue_ue.PropertyEditorTestObject.md#subclassofwithallowed)
- [SubclassOfWithDisallowed](ue_ue.PropertyEditorTestObject.md#subclassofwithdisallowed)
- [TextPasswordProperty](ue_ue.PropertyEditorTestObject.md#textpasswordproperty)
- [TextProperty](ue_ue.PropertyEditorTestObject.md#textproperty)
- [TextPropertyArray](ue_ue.PropertyEditorTestObject.md#textpropertyarray)
- [TextureOrBlendableInterface](ue_ue.PropertyEditorTestObject.md#textureorblendableinterface)
- [TextureProp](ue_ue.PropertyEditorTestObject.md#textureprop)
- [ThisIsBrokenIfItsVisibleInADetailsView](ue_ue.PropertyEditorTestObject.md#thisisbrokenifitsvisibleinadetailsview)
- [TransformProperty](ue_ue.PropertyEditorTestObject.md#transformproperty)
- [UnsignedInt16Property](ue_ue.PropertyEditorTestObject.md#unsignedint16property)
- [UnsignedInt32Property](ue_ue.PropertyEditorTestObject.md#unsignedint32property)
- [UnsignedInt64Property](ue_ue.PropertyEditorTestObject.md#unsignedint64property)
- [Vector2Property](ue_ue.PropertyEditorTestObject.md#vector2property)
- [Vector2PropertyArray](ue_ue.PropertyEditorTestObject.md#vector2propertyarray)
- [Vector3Property](ue_ue.PropertyEditorTestObject.md#vector3property)
- [Vector3PropertyArray](ue_ue.PropertyEditorTestObject.md#vector3propertyarray)
- [Vector4Property](ue_ue.PropertyEditorTestObject.md#vector4property)
- [Vector4PropertyArray](ue_ue.PropertyEditorTestObject.md#vector4propertyarray)
- [VectorSet](ue_ue.PropertyEditorTestObject.md#vectorset)
- [VectorToFloatMap](ue_ue.PropertyEditorTestObject.md#vectortofloatmap)
- [VisibleWhenStationary](ue_ue.PropertyEditorTestObject.md#visiblewhenstationary)
- [\_\_tid\_Object\_\_](ue_ue.PropertyEditorTestObject.md#__tid_object__)
- [\_\_tid\_PropertyEditorTestObject\_\_](ue_ue.PropertyEditorTestObject.md#__tid_propertyeditortestobject__)
- [bEditCondition](ue_ue.PropertyEditorTestObject.md#beditcondition)
- [bEditConditionAssetReferenceCustomStructWithEditCondition](ue_ue.PropertyEditorTestObject.md#beditconditionassetreferencecustomstructwitheditcondition)
- [bEditConditionForArrays](ue_ue.PropertyEditorTestObject.md#beditconditionforarrays)
- [bEditConditionStructWithMultipleInstances2](ue_ue.PropertyEditorTestObject.md#beditconditionstructwithmultipleinstances2)
- [bEnabledByPrevious](ue_ue.PropertyEditorTestObject.md#benabledbyprevious)
- [bEnabledWhenBlue](ue_ue.PropertyEditorTestObject.md#benabledwhenblue)
- [bEnabledWhenEnumIs2](ue_ue.PropertyEditorTestObject.md#benabledwhenenumis2)
- [bEnabledWhenEnumIs4](ue_ue.PropertyEditorTestObject.md#benabledwhenenumis4)
- [bEnabledWhenFloatGreaterThan5](ue_ue.PropertyEditorTestObject.md#benabledwhenfloatgreaterthan5)
- [bEnabledWhenFloatLessThan10](ue_ue.PropertyEditorTestObject.md#benabledwhenfloatlessthan10)
- [bEnabledWhenIntGreaterOrEqual5](ue_ue.PropertyEditorTestObject.md#benabledwhenintgreaterorequal5)
- [bEnabledWhenIntLessOrEqual10](ue_ue.PropertyEditorTestObject.md#benabledwhenintlessorequal10)
- [bEnabledWhenPink](ue_ue.PropertyEditorTestObject.md#benabledwhenpink)
- [bEnablesNext](ue_ue.PropertyEditorTestObject.md#benablesnext)
- [bSubcategory](ue_ue.PropertyEditorTestObject.md#bsubcategory)
- [bSubcategoryAdvanced](ue_ue.PropertyEditorTestObject.md#bsubcategoryadvanced)
- [bSubcategoryBarAdvanced](ue_ue.PropertyEditorTestObject.md#bsubcategorybaradvanced)
- [bSubcategoryBarSimple](ue_ue.PropertyEditorTestObject.md#bsubcategorybarsimple)
- [bSubcategoryFooAdvanced](ue_ue.PropertyEditorTestObject.md#bsubcategoryfooadvanced)
- [bSubcategoryFooSimple](ue_ue.PropertyEditorTestObject.md#bsubcategoryfoosimple)
- [bSubcategoryLast](ue_ue.PropertyEditorTestObject.md#bsubcategorylast)
- [bVisibleWhenStatic](ue_ue.PropertyEditorTestObject.md#bvisiblewhenstatic)

### Methods

- [CreateDefaultSubobject](ue_ue.PropertyEditorTestObject.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PropertyEditorTestObject.md#executeubergraph)
- [GetClass](ue_ue.PropertyEditorTestObject.md#getclass)
- [GetName](ue_ue.PropertyEditorTestObject.md#getname)
- [GetOuter](ue_ue.PropertyEditorTestObject.md#getouter)
- [GetWorld](ue_ue.PropertyEditorTestObject.md#getworld)
- [Find](ue_ue.PropertyEditorTestObject.md#find)
- [Load](ue_ue.PropertyEditorTestObject.md#load)
- [StaticClass](ue_ue.PropertyEditorTestObject.md#staticclass)

## Constructors

### constructor

• **new PropertyEditorTestObject**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:58749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58749)

## Properties

### ActorPropertyArray

• **ActorPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:58794](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58794)

___

### ActorSet

• **ActorSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:58838](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58838)

___

### AnimClassInterface

• **AnimClassInterface**: [`AnimClassInterface`](ue_ue.AnimClassInterface.md)

#### Defined in

[ue/ue.d.ts:58859](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58859)

___

### AnyMaterialInterface

• **AnyMaterialInterface**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:58832](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58832)

___

### ArrayOfEditInlineNewSMCs

• **ArrayOfEditInlineNewSMCs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)\>

#### Defined in

[ue/ue.d.ts:58829](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58829)

___

### ArrayOfStructs

• **ArrayOfStructs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)\>

#### Defined in

[ue/ue.d.ts:58826](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58826)

___

### ArrayOfStructsWithEditCondition

• **ArrayOfStructsWithEditCondition**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)\>

#### Defined in

[ue/ue.d.ts:58885](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58885)

___

### ArrayWithEditCondition

• **ArrayWithEditCondition**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Texture2D`](ue_ue.Texture2D.md)\>

#### Defined in

[ue/ue.d.ts:58884](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58884)

___

### AssetReferenceCustomStruct

• **AssetReferenceCustomStruct**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:58814](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58814)

___

### AssetReferenceCustomStructWithEditCondition

• **AssetReferenceCustomStructWithEditCondition**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:58825](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58825)

___

### AssetReferenceCustomStructWithThumbnail

• **AssetReferenceCustomStructWithThumbnail**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:58815](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58815)

___

### BlendableInterface

• **BlendableInterface**: [`BlendableInterface`](ue_ue.BlendableInterface.md)

#### Defined in

[ue/ue.d.ts:58858](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58858)

___

### BoolProperty

• **BoolProperty**: `boolean`

#### Defined in

[ue/ue.d.ts:58761](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58761)

___

### BoolPropertyArray

• **BoolPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

#### Defined in

[ue/ue.d.ts:58786](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58786)

___

### ByteProperty

• **ByteProperty**: `number`

#### Defined in

[ue/ue.d.ts:58754](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58754)

___

### BytePropertyArray

• **BytePropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:58783](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58783)

___

### ClassProperty

• **ClassProperty**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:58770](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58770)

___

### ClassPropertyWithAllowed

• **ClassPropertyWithAllowed**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:58771](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58771)

___

### ClassPropertyWithDisallowed

• **ClassPropertyWithDisallowed**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:58772](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58772)

___

### ColorProperty

• **ColorProperty**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:58777](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58777)

___

### ColorPropertyArray

• **ColorPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

#### Defined in

[ue/ue.d.ts:58796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58796)

___

### DateTime

• **DateTime**: [`DateTime`](ue_ue.DateTime.md)

#### Defined in

[ue/ue.d.ts:58890](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58890)

___

### DoubleProperty

• **DoubleProperty**: `number`

#### Defined in

[ue/ue.d.ts:58759](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58759)

___

### EditColorSet

• **EditColorSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`EditColor`](../enums/ue_ue.EditColor.md)\>

#### Defined in

[ue/ue.d.ts:58839](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58839)

___

### EditInlineNewStaticMeshComponent

• **EditInlineNewStaticMeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Defined in

[ue/ue.d.ts:58828](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58828)

___

### EnumAsByteEditCondition

• **EnumAsByteEditCondition**: [`PropertyEditorTestEnum`](../enums/ue_ue.PropertyEditorTestEnum.md)

#### Defined in

[ue/ue.d.ts:58874](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58874)

___

### EnumByteProperty

• **EnumByteProperty**: [`PropertyEditorTestEnum`](../enums/ue_ue.PropertyEditorTestEnum.md)

#### Defined in

[ue/ue.d.ts:58778](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58778)

___

### EnumEditCondition

• **EnumEditCondition**: [`EditColor`](../enums/ue_ue.EditColor.md)

#### Defined in

[ue/ue.d.ts:58871](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58871)

___

### EnumProperty

• **EnumProperty**: [`EditColor`](../enums/ue_ue.EditColor.md)

#### Defined in

[ue/ue.d.ts:58779](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58779)

___

### EnumPropertyArray

• **EnumPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyEditorTestEnum`](../enums/ue_ue.PropertyEditorTestEnum.md)\>

#### Defined in

[ue/ue.d.ts:58797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58797)

___

### ExactPointOrSpotLightActorReference

• **ExactPointOrSpotLightActorReference**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:58818](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58818)

___

### ExactlyPointLightActorReference

• **ExactlyPointLightActorReference**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:58816](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58816)

___

### FixedArrayOfInts

• **FixedArrayOfInts**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:58799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58799)

___

### FloatEditCondition

• **FloatEditCondition**: `number`

#### Defined in

[ue/ue.d.ts:58880](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58880)

___

### FloatProperty

• **FloatProperty**: `number`

#### Defined in

[ue/ue.d.ts:58758](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58758)

___

### FloatPropertyArray

• **FloatPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:58784](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58784)

___

### FloatPropertyWithClampedRange

• **FloatPropertyWithClampedRange**: `number`

#### Defined in

[ue/ue.d.ts:58802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58802)

___

### FloatSet

• **FloatSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\>

#### Defined in

[ue/ue.d.ts:58835](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58835)

___

### InlineProperty

• **InlineProperty**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Defined in

[ue/ue.d.ts:58886](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58886)

___

### Int16Property

• **Int16Property**: `number`

#### Defined in

[ue/ue.d.ts:58751](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58751)

___

### Int32Property

• **Int32Property**: `number`

#### Defined in

[ue/ue.d.ts:58752](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58752)

___

### Int32Set

• **Int32Set**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\>

#### Defined in

[ue/ue.d.ts:58834](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58834)

___

### Int32ToStringMap

• **Int32ToStringMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `string`\>

#### Defined in

[ue/ue.d.ts:58841](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58841)

___

### Int32ToStructMap

• **Int32ToStructMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, [`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)\>

#### Defined in

[ue/ue.d.ts:58843](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58843)

___

### Int64Property

• **Int64Property**: `bigint`

#### Defined in

[ue/ue.d.ts:58753](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58753)

___

### Int8Property

• **Int8Property**: `number`

#### Defined in

[ue/ue.d.ts:58750](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58750)

___

### IntPointProperty

• **IntPointProperty**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:58764](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58764)

___

### IntProperty32Array

• **IntProperty32Array**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:58782](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58782)

___

### IntPropertyWithClampedRange

• **IntPropertyWithClampedRange**: `number`

#### Defined in

[ue/ue.d.ts:58803](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58803)

___

### IntThatCannotBeChanged

• **IntThatCannotBeChanged**: `number`

#### Defined in

[ue/ue.d.ts:58804](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58804)

___

### IntToCustomMap

• **IntToCustomMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, [`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)\>

#### Defined in

[ue/ue.d.ts:58851](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58851)

___

### IntToEnumMap

• **IntToEnumMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, [`PropertyEditorTestEnum`](../enums/ue_ue.PropertyEditorTestEnum.md)\>

#### Defined in

[ue/ue.d.ts:58849](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58849)

___

### IntToSubStructMap

• **IntToSubStructMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, [`PropertyEditorTestSubStruct`](ue_ue.PropertyEditorTestSubStruct.md)\>

#### Defined in

[ue/ue.d.ts:58852](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58852)

___

### IntegerEditCondition

• **IntegerEditCondition**: `number`

#### Defined in

[ue/ue.d.ts:58877](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58877)

___

### LightActorReference

• **LightActorReference**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:58817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58817)

___

### LightOrStaticMeshActorReference

• **LightOrStaticMeshActorReference**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:58819](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58819)

___

### LightPropagationVolumeBlendable

• **LightPropagationVolumeBlendable**: [`BlendableInterface`](ue_ue.BlendableInterface.md)

#### Defined in

[ue/ue.d.ts:58860](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58860)

___

### LinearColorProperty

• **LinearColorProperty**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:58776](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58776)

___

### LinearColorPropertyArray

• **LinearColorPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Defined in

[ue/ue.d.ts:58795](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58795)

___

### LinearColorSet

• **LinearColorSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Defined in

[ue/ue.d.ts:58853](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58853)

___

### LinearColorToStringMap

• **LinearColorToStringMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`LinearColor`](ue_ue_s.LinearColor.md), `string`\>

#### Defined in

[ue/ue.d.ts:58855](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58855)

___

### LinearColorToVectorMap

• **LinearColorToVectorMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`LinearColor`](ue_ue_s.LinearColor.md), [`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:58857](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58857)

___

### MaterialOrTextureAssetReference

• **MaterialOrTextureAssetReference**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:58821](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58821)

___

### MatrixProperty

• **MatrixProperty**: [`Matrix`](ue_ue.Matrix.md)

#### Defined in

[ue/ue.d.ts:58780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58780)

___

### NameProperty

• **NameProperty**: `string`

#### Defined in

[ue/ue.d.ts:58760](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58760)

___

### NamePropertyArray

• **NamePropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:58785](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58785)

___

### NameSet

• **NameSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`string`\>

#### Defined in

[ue/ue.d.ts:58840](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58840)

___

### NameToNameMap

• **NameToNameMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Defined in

[ue/ue.d.ts:58850](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58850)

___

### NotLightActorReference

• **NotLightActorReference**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:58820](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58820)

___

### ObjectProperty

• **ObjectProperty**: [`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:58769](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58769)

___

### ObjectPropertyArray

• **ObjectPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:58793](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58793)

___

### ObjectSet

• **ObjectSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:58837](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58837)

___

### ObjectThatCannotBeChanged

• **ObjectThatCannotBeChanged**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

#### Defined in

[ue/ue.d.ts:58806](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58806)

___

### ObjectToColorMap

• **ObjectToColorMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Object`](ue_ue.Object.md), [`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Defined in

[ue/ue.d.ts:58848](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58848)

___

### ObjectToInt32Map

• **ObjectToInt32Map**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Object`](ue_ue.Object.md), `number`\>

#### Defined in

[ue/ue.d.ts:58847](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58847)

___

### OnlyActorsAllowed

• **OnlyActorsAllowed**: [`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:58833](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58833)

___

### PropertyThatHides

• **PropertyThatHides**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Defined in

[ue/ue.d.ts:58887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58887)

___

### RichCurve

• **RichCurve**: [`RichCurve`](ue_ue.RichCurve.md)

#### Defined in

[ue/ue.d.ts:58813](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58813)

___

### RotatorProperty

• **RotatorProperty**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:58768](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58768)

___

### RotatorPropertyArray

• **RotatorPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Rotator`](ue_ue_s.Rotator.md)\>

#### Defined in

[ue/ue.d.ts:58792](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58792)

___

### SimplePropertyWithEditCondition

• **SimplePropertyWithEditCondition**: `number`

#### Defined in

[ue/ue.d.ts:58823](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58823)

___

### StaticArrayOfInts

• **StaticArrayOfInts**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:58800](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58800)

___

### StaticArrayOfIntsWithEnumLabels

• **StaticArrayOfIntsWithEnumLabels**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:58801](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58801)

___

### StaticMeshProp

• **StaticMeshProp**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:58831](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58831)

___

### StringPasswordProperty

• **StringPasswordProperty**: `string`

#### Defined in

[ue/ue.d.ts:58807](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58807)

___

### StringProperty

• **StringProperty**: `string`

#### Defined in

[ue/ue.d.ts:58762](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58762)

___

### StringPropertyArray

• **StringPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:58787](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58787)

___

### StringSet

• **StringSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`string`\>

#### Defined in

[ue/ue.d.ts:58836](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58836)

___

### StringThatCannotBeChanged

• **StringThatCannotBeChanged**: `string`

#### Defined in

[ue/ue.d.ts:58805](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58805)

___

### StringToActorMap

• **StringToActorMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:58846](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58846)

___

### StringToColorMap

• **StringToColorMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Defined in

[ue/ue.d.ts:58842](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58842)

___

### StringToFloatMap

• **StringToFloatMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>

#### Defined in

[ue/ue.d.ts:58844](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58844)

___

### StringToObjectMap

• **StringToObjectMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:58845](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58845)

___

### Struct

• **Struct**: [`PropertyEditTestTextStruct`](ue_ue.PropertyEditTestTextStruct.md)

#### Defined in

[ue/ue.d.ts:58827](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58827)

___

### StructPropertyArray

• **StructPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)\>

#### Defined in

[ue/ue.d.ts:58798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58798)

___

### StructWithMultipleInstances1

• **StructWithMultipleInstances1**: [`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)

#### Defined in

[ue/ue.d.ts:58810](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58810)

___

### StructWithMultipleInstances2

• **StructWithMultipleInstances2**: [`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)

#### Defined in

[ue/ue.d.ts:58812](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58812)

___

### SubclassOfTexture

• **SubclassOfTexture**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:58773](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58773)

___

### SubclassOfWithAllowed

• **SubclassOfWithAllowed**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:58774](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58774)

___

### SubclassOfWithDisallowed

• **SubclassOfWithDisallowed**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:58775](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58775)

___

### TextPasswordProperty

• **TextPasswordProperty**: `string`

#### Defined in

[ue/ue.d.ts:58808](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58808)

___

### TextProperty

• **TextProperty**: `string`

#### Defined in

[ue/ue.d.ts:58763](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58763)

___

### TextPropertyArray

• **TextPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:58788](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58788)

___

### TextureOrBlendableInterface

• **TextureOrBlendableInterface**: [`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:58861](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58861)

___

### TextureProp

• **TextureProp**: [`Texture`](ue_ue.Texture.md)

#### Defined in

[ue/ue.d.ts:58830](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58830)

___

### ThisIsBrokenIfItsVisibleInADetailsView

• **ThisIsBrokenIfItsVisibleInADetailsView**: [`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)

#### Defined in

[ue/ue.d.ts:58809](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58809)

___

### TransformProperty

• **TransformProperty**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:58781](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58781)

___

### UnsignedInt16Property

• **UnsignedInt16Property**: `number`

#### Defined in

[ue/ue.d.ts:58755](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58755)

___

### UnsignedInt32Property

• **UnsignedInt32Property**: `number`

#### Defined in

[ue/ue.d.ts:58756](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58756)

___

### UnsignedInt64Property

• **UnsignedInt64Property**: `bigint`

#### Defined in

[ue/ue.d.ts:58757](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58757)

___

### Vector2Property

• **Vector2Property**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:58766](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58766)

___

### Vector2PropertyArray

• **Vector2PropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\>

#### Defined in

[ue/ue.d.ts:58790](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58790)

___

### Vector3Property

• **Vector3Property**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:58765](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58765)

___

### Vector3PropertyArray

• **Vector3PropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:58789](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58789)

___

### Vector4Property

• **Vector4Property**: [`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue.d.ts:58767](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58767)

___

### Vector4PropertyArray

• **Vector4PropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector4`](ue_ue_s.Vector4.md)\>

#### Defined in

[ue/ue.d.ts:58791](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58791)

___

### VectorSet

• **VectorSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:58854](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58854)

___

### VectorToFloatMap

• **VectorToFloatMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Vector`](ue_ue_s.Vector.md), `number`\>

#### Defined in

[ue/ue.d.ts:58856](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58856)

___

### VisibleWhenStationary

• **VisibleWhenStationary**: `number`

#### Defined in

[ue/ue.d.ts:58889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58889)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PropertyEditorTestObject\_\_

• **\_\_tid\_PropertyEditorTestObject\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:58895](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58895)

___

### bEditCondition

• **bEditCondition**: `boolean`

#### Defined in

[ue/ue.d.ts:58822](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58822)

___

### bEditConditionAssetReferenceCustomStructWithEditCondition

• **bEditConditionAssetReferenceCustomStructWithEditCondition**: `boolean`

#### Defined in

[ue/ue.d.ts:58824](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58824)

___

### bEditConditionForArrays

• **bEditConditionForArrays**: `boolean`

#### Defined in

[ue/ue.d.ts:58883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58883)

___

### bEditConditionStructWithMultipleInstances2

• **bEditConditionStructWithMultipleInstances2**: `boolean`

#### Defined in

[ue/ue.d.ts:58811](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58811)

___

### bEnabledByPrevious

• **bEnabledByPrevious**: `boolean`

#### Defined in

[ue/ue.d.ts:58870](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58870)

___

### bEnabledWhenBlue

• **bEnabledWhenBlue**: `boolean`

#### Defined in

[ue/ue.d.ts:58872](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58872)

___

### bEnabledWhenEnumIs2

• **bEnabledWhenEnumIs2**: `boolean`

#### Defined in

[ue/ue.d.ts:58875](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58875)

___

### bEnabledWhenEnumIs4

• **bEnabledWhenEnumIs4**: `boolean`

#### Defined in

[ue/ue.d.ts:58876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58876)

___

### bEnabledWhenFloatGreaterThan5

• **bEnabledWhenFloatGreaterThan5**: `boolean`

#### Defined in

[ue/ue.d.ts:58881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58881)

___

### bEnabledWhenFloatLessThan10

• **bEnabledWhenFloatLessThan10**: `boolean`

#### Defined in

[ue/ue.d.ts:58882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58882)

___

### bEnabledWhenIntGreaterOrEqual5

• **bEnabledWhenIntGreaterOrEqual5**: `boolean`

#### Defined in

[ue/ue.d.ts:58878](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58878)

___

### bEnabledWhenIntLessOrEqual10

• **bEnabledWhenIntLessOrEqual10**: `boolean`

#### Defined in

[ue/ue.d.ts:58879](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58879)

___

### bEnabledWhenPink

• **bEnabledWhenPink**: `boolean`

#### Defined in

[ue/ue.d.ts:58873](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58873)

___

### bEnablesNext

• **bEnablesNext**: `boolean`

#### Defined in

[ue/ue.d.ts:58869](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58869)

___

### bSubcategory

• **bSubcategory**: `boolean`

#### Defined in

[ue/ue.d.ts:58862](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58862)

___

### bSubcategoryAdvanced

• **bSubcategoryAdvanced**: `boolean`

#### Defined in

[ue/ue.d.ts:58863](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58863)

___

### bSubcategoryBarAdvanced

• **bSubcategoryBarAdvanced**: `boolean`

#### Defined in

[ue/ue.d.ts:58867](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58867)

___

### bSubcategoryBarSimple

• **bSubcategoryBarSimple**: `boolean`

#### Defined in

[ue/ue.d.ts:58866](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58866)

___

### bSubcategoryFooAdvanced

• **bSubcategoryFooAdvanced**: `boolean`

#### Defined in

[ue/ue.d.ts:58865](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58865)

___

### bSubcategoryFooSimple

• **bSubcategoryFooSimple**: `boolean`

#### Defined in

[ue/ue.d.ts:58864](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58864)

___

### bSubcategoryLast

• **bSubcategoryLast**: `boolean`

#### Defined in

[ue/ue.d.ts:58868](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58868)

___

### bVisibleWhenStatic

• **bVisibleWhenStatic**: `boolean`

#### Defined in

[ue/ue.d.ts:58888](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58888)

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PropertyEditorTestObject`](ue_ue.PropertyEditorTestObject.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PropertyEditorTestObject`](ue_ue.PropertyEditorTestObject.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:58892](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58892)

___

### Load

▸ `Static` **Load**(`InName`): [`PropertyEditorTestObject`](ue_ue.PropertyEditorTestObject.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PropertyEditorTestObject`](ue_ue.PropertyEditorTestObject.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:58893](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58893)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:58891](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58891)
