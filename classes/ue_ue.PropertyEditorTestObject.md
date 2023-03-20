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

## Properties

### ActorPropertyArray

• **ActorPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### ActorSet

• **ActorSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`Actor`](ue_ue.Actor.md)\>

___

### AnimClassInterface

• **AnimClassInterface**: [`AnimClassInterface`](ue_ue.AnimClassInterface.md)

___

### AnyMaterialInterface

• **AnyMaterialInterface**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### ArrayOfEditInlineNewSMCs

• **ArrayOfEditInlineNewSMCs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)\>

___

### ArrayOfStructs

• **ArrayOfStructs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)\>

___

### ArrayOfStructsWithEditCondition

• **ArrayOfStructsWithEditCondition**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)\>

___

### ArrayWithEditCondition

• **ArrayWithEditCondition**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Texture2D`](ue_ue.Texture2D.md)\>

___

### AssetReferenceCustomStruct

• **AssetReferenceCustomStruct**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### AssetReferenceCustomStructWithEditCondition

• **AssetReferenceCustomStructWithEditCondition**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### AssetReferenceCustomStructWithThumbnail

• **AssetReferenceCustomStructWithThumbnail**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### BlendableInterface

• **BlendableInterface**: [`BlendableInterface`](ue_ue.BlendableInterface.md)

___

### BoolProperty

• **BoolProperty**: `boolean`

___

### BoolPropertyArray

• **BoolPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

___

### ByteProperty

• **ByteProperty**: `number`

___

### BytePropertyArray

• **BytePropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### ClassProperty

• **ClassProperty**: [`Class`](ue_ue.Class.md)

___

### ClassPropertyWithAllowed

• **ClassPropertyWithAllowed**: [`Class`](ue_ue.Class.md)

___

### ClassPropertyWithDisallowed

• **ClassPropertyWithDisallowed**: [`Class`](ue_ue.Class.md)

___

### ColorProperty

• **ColorProperty**: [`Color`](ue_ue_s.Color.md)

___

### ColorPropertyArray

• **ColorPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Color`](ue_ue_s.Color.md)\>

___

### DateTime

• **DateTime**: [`DateTime`](ue_ue.DateTime.md)

___

### DoubleProperty

• **DoubleProperty**: `number`

___

### EditColorSet

• **EditColorSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`EditColor`](../enums/ue_ue.EditColor.md)\>

___

### EditInlineNewStaticMeshComponent

• **EditInlineNewStaticMeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

___

### EnumAsByteEditCondition

• **EnumAsByteEditCondition**: [`PropertyEditorTestEnum`](../enums/ue_ue.PropertyEditorTestEnum.md)

___

### EnumByteProperty

• **EnumByteProperty**: [`PropertyEditorTestEnum`](../enums/ue_ue.PropertyEditorTestEnum.md)

___

### EnumEditCondition

• **EnumEditCondition**: [`EditColor`](../enums/ue_ue.EditColor.md)

___

### EnumProperty

• **EnumProperty**: [`EditColor`](../enums/ue_ue.EditColor.md)

___

### EnumPropertyArray

• **EnumPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyEditorTestEnum`](../enums/ue_ue.PropertyEditorTestEnum.md)\>

___

### ExactPointOrSpotLightActorReference

• **ExactPointOrSpotLightActorReference**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### ExactlyPointLightActorReference

• **ExactlyPointLightActorReference**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### FixedArrayOfInts

• **FixedArrayOfInts**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### FloatEditCondition

• **FloatEditCondition**: `number`

___

### FloatProperty

• **FloatProperty**: `number`

___

### FloatPropertyArray

• **FloatPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### FloatPropertyWithClampedRange

• **FloatPropertyWithClampedRange**: `number`

___

### FloatSet

• **FloatSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\>

___

### InlineProperty

• **InlineProperty**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

___

### Int16Property

• **Int16Property**: `number`

___

### Int32Property

• **Int32Property**: `number`

___

### Int32Set

• **Int32Set**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`number`\>

___

### Int32ToStringMap

• **Int32ToStringMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `string`\>

___

### Int32ToStructMap

• **Int32ToStructMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, [`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)\>

___

### Int64Property

• **Int64Property**: `bigint`

___

### Int8Property

• **Int8Property**: `number`

___

### IntPointProperty

• **IntPointProperty**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### IntProperty32Array

• **IntProperty32Array**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### IntPropertyWithClampedRange

• **IntPropertyWithClampedRange**: `number`

___

### IntThatCannotBeChanged

• **IntThatCannotBeChanged**: `number`

___

### IntToCustomMap

• **IntToCustomMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, [`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)\>

___

### IntToEnumMap

• **IntToEnumMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, [`PropertyEditorTestEnum`](../enums/ue_ue.PropertyEditorTestEnum.md)\>

___

### IntToSubStructMap

• **IntToSubStructMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, [`PropertyEditorTestSubStruct`](ue_ue.PropertyEditorTestSubStruct.md)\>

___

### IntegerEditCondition

• **IntegerEditCondition**: `number`

___

### LightActorReference

• **LightActorReference**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### LightOrStaticMeshActorReference

• **LightOrStaticMeshActorReference**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### LightPropagationVolumeBlendable

• **LightPropagationVolumeBlendable**: [`BlendableInterface`](ue_ue.BlendableInterface.md)

___

### LinearColorProperty

• **LinearColorProperty**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### LinearColorPropertyArray

• **LinearColorPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

___

### LinearColorSet

• **LinearColorSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`LinearColor`](ue_ue_s.LinearColor.md)\>

___

### LinearColorToStringMap

• **LinearColorToStringMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`LinearColor`](ue_ue_s.LinearColor.md), `string`\>

___

### LinearColorToVectorMap

• **LinearColorToVectorMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`LinearColor`](ue_ue_s.LinearColor.md), [`Vector`](ue_ue_s.Vector.md)\>

___

### MaterialOrTextureAssetReference

• **MaterialOrTextureAssetReference**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### MatrixProperty

• **MatrixProperty**: [`Matrix`](ue_ue.Matrix.md)

___

### NameProperty

• **NameProperty**: `string`

___

### NamePropertyArray

• **NamePropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### NameSet

• **NameSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`string`\>

___

### NameToNameMap

• **NameToNameMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

___

### NotLightActorReference

• **NotLightActorReference**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### ObjectProperty

• **ObjectProperty**: [`Object`](ue_ue.Object.md)

___

### ObjectPropertyArray

• **ObjectPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### ObjectSet

• **ObjectSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`Object`](ue_ue.Object.md)\>

___

### ObjectThatCannotBeChanged

• **ObjectThatCannotBeChanged**: [`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)

___

### ObjectToColorMap

• **ObjectToColorMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Object`](ue_ue.Object.md), [`LinearColor`](ue_ue_s.LinearColor.md)\>

___

### ObjectToInt32Map

• **ObjectToInt32Map**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Object`](ue_ue.Object.md), `number`\>

___

### OnlyActorsAllowed

• **OnlyActorsAllowed**: [`Actor`](ue_ue.Actor.md)

___

### PropertyThatHides

• **PropertyThatHides**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

___

### RichCurve

• **RichCurve**: [`RichCurve`](ue_ue.RichCurve.md)

___

### RotatorProperty

• **RotatorProperty**: [`Rotator`](ue_ue_s.Rotator.md)

___

### RotatorPropertyArray

• **RotatorPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Rotator`](ue_ue_s.Rotator.md)\>

___

### SimplePropertyWithEditCondition

• **SimplePropertyWithEditCondition**: `number`

___

### StaticArrayOfInts

• **StaticArrayOfInts**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<`number`\>

___

### StaticArrayOfIntsWithEnumLabels

• **StaticArrayOfIntsWithEnumLabels**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<`number`\>

___

### StaticMeshProp

• **StaticMeshProp**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### StringPasswordProperty

• **StringPasswordProperty**: `string`

___

### StringProperty

• **StringProperty**: `string`

___

### StringPropertyArray

• **StringPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### StringSet

• **StringSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`string`\>

___

### StringThatCannotBeChanged

• **StringThatCannotBeChanged**: `string`

___

### StringToActorMap

• **StringToActorMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`Actor`](ue_ue.Actor.md)\>

___

### StringToColorMap

• **StringToColorMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`LinearColor`](ue_ue_s.LinearColor.md)\>

___

### StringToFloatMap

• **StringToFloatMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>

___

### StringToObjectMap

• **StringToObjectMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`Object`](ue_ue.Object.md)\>

___

### Struct

• **Struct**: [`PropertyEditTestTextStruct`](ue_ue.PropertyEditTestTextStruct.md)

___

### StructPropertyArray

• **StructPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)\>

___

### StructWithMultipleInstances1

• **StructWithMultipleInstances1**: [`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)

___

### StructWithMultipleInstances2

• **StructWithMultipleInstances2**: [`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)

___

### SubclassOfTexture

• **SubclassOfTexture**: [`Class`](ue_ue.Class.md)

___

### SubclassOfWithAllowed

• **SubclassOfWithAllowed**: [`Class`](ue_ue.Class.md)

___

### SubclassOfWithDisallowed

• **SubclassOfWithDisallowed**: [`Class`](ue_ue.Class.md)

___

### TextPasswordProperty

• **TextPasswordProperty**: `string`

___

### TextProperty

• **TextProperty**: `string`

___

### TextPropertyArray

• **TextPropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### TextureOrBlendableInterface

• **TextureOrBlendableInterface**: [`Object`](ue_ue.Object.md)

___

### TextureProp

• **TextureProp**: [`Texture`](ue_ue.Texture.md)

___

### ThisIsBrokenIfItsVisibleInADetailsView

• **ThisIsBrokenIfItsVisibleInADetailsView**: [`PropertyEditorTestBasicStruct`](ue_ue.PropertyEditorTestBasicStruct.md)

___

### TransformProperty

• **TransformProperty**: [`Transform`](ue_ue_s.Transform.md)

___

### UnsignedInt16Property

• **UnsignedInt16Property**: `number`

___

### UnsignedInt32Property

• **UnsignedInt32Property**: `number`

___

### UnsignedInt64Property

• **UnsignedInt64Property**: `bigint`

___

### Vector2Property

• **Vector2Property**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### Vector2PropertyArray

• **Vector2PropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\>

___

### Vector3Property

• **Vector3Property**: [`Vector`](ue_ue_s.Vector.md)

___

### Vector3PropertyArray

• **Vector3PropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### Vector4Property

• **Vector4Property**: [`Vector4`](ue_ue_s.Vector4.md)

___

### Vector4PropertyArray

• **Vector4PropertyArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector4`](ue_ue_s.Vector4.md)\>

___

### VectorSet

• **VectorSet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### VectorToFloatMap

• **VectorToFloatMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Vector`](ue_ue_s.Vector.md), `number`\>

___

### VisibleWhenStationary

• **VisibleWhenStationary**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PropertyEditorTestObject\_\_

• **\_\_tid\_PropertyEditorTestObject\_\_**: `boolean`

___

### bEditCondition

• **bEditCondition**: `boolean`

___

### bEditConditionAssetReferenceCustomStructWithEditCondition

• **bEditConditionAssetReferenceCustomStructWithEditCondition**: `boolean`

___

### bEditConditionForArrays

• **bEditConditionForArrays**: `boolean`

___

### bEditConditionStructWithMultipleInstances2

• **bEditConditionStructWithMultipleInstances2**: `boolean`

___

### bEnabledByPrevious

• **bEnabledByPrevious**: `boolean`

___

### bEnabledWhenBlue

• **bEnabledWhenBlue**: `boolean`

___

### bEnabledWhenEnumIs2

• **bEnabledWhenEnumIs2**: `boolean`

___

### bEnabledWhenEnumIs4

• **bEnabledWhenEnumIs4**: `boolean`

___

### bEnabledWhenFloatGreaterThan5

• **bEnabledWhenFloatGreaterThan5**: `boolean`

___

### bEnabledWhenFloatLessThan10

• **bEnabledWhenFloatLessThan10**: `boolean`

___

### bEnabledWhenIntGreaterOrEqual5

• **bEnabledWhenIntGreaterOrEqual5**: `boolean`

___

### bEnabledWhenIntLessOrEqual10

• **bEnabledWhenIntLessOrEqual10**: `boolean`

___

### bEnabledWhenPink

• **bEnabledWhenPink**: `boolean`

___

### bEnablesNext

• **bEnablesNext**: `boolean`

___

### bSubcategory

• **bSubcategory**: `boolean`

___

### bSubcategoryAdvanced

• **bSubcategoryAdvanced**: `boolean`

___

### bSubcategoryBarAdvanced

• **bSubcategoryBarAdvanced**: `boolean`

___

### bSubcategoryBarSimple

• **bSubcategoryBarSimple**: `boolean`

___

### bSubcategoryFooAdvanced

• **bSubcategoryFooAdvanced**: `boolean`

___

### bSubcategoryFooSimple

• **bSubcategoryFooSimple**: `boolean`

___

### bSubcategoryLast

• **bSubcategoryLast**: `boolean`

___

### bVisibleWhenStatic

• **bVisibleWhenStatic**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
