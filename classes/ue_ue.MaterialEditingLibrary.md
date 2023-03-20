[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialEditingLibrary

# Class: MaterialEditingLibrary

[ue/ue](../modules/ue_ue.md).MaterialEditingLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`MaterialEditingLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialEditingLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.MaterialEditingLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_MaterialEditingLibrary\_\_](ue_ue.MaterialEditingLibrary.md#__tid_materialeditinglibrary__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialEditingLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialEditingLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialEditingLibrary.md#executeubergraph)
- [GetClass](ue_ue.MaterialEditingLibrary.md#getclass)
- [GetName](ue_ue.MaterialEditingLibrary.md#getname)
- [GetOuter](ue_ue.MaterialEditingLibrary.md#getouter)
- [GetScalarParameterSource](ue_ue.MaterialEditingLibrary.md#getscalarparametersource)
- [GetStaticSwitchParameterSource](ue_ue.MaterialEditingLibrary.md#getstaticswitchparametersource)
- [GetTextureParameterSource](ue_ue.MaterialEditingLibrary.md#gettextureparametersource)
- [GetVectorParameterSource](ue_ue.MaterialEditingLibrary.md#getvectorparametersource)
- [GetWorld](ue_ue.MaterialEditingLibrary.md#getworld)
- [ClearAllMaterialInstanceParameters](ue_ue.MaterialEditingLibrary.md#clearallmaterialinstanceparameters)
- [ConnectMaterialExpressions](ue_ue.MaterialEditingLibrary.md#connectmaterialexpressions)
- [ConnectMaterialProperty](ue_ue.MaterialEditingLibrary.md#connectmaterialproperty)
- [CreateMaterialExpression](ue_ue.MaterialEditingLibrary.md#creatematerialexpression)
- [CreateMaterialExpressionInFunction](ue_ue.MaterialEditingLibrary.md#creatematerialexpressioninfunction)
- [DeleteAllMaterialExpressions](ue_ue.MaterialEditingLibrary.md#deleteallmaterialexpressions)
- [DeleteAllMaterialExpressionsInFunction](ue_ue.MaterialEditingLibrary.md#deleteallmaterialexpressionsinfunction)
- [DeleteMaterialExpression](ue_ue.MaterialEditingLibrary.md#deletematerialexpression)
- [DeleteMaterialExpressionInFunction](ue_ue.MaterialEditingLibrary.md#deletematerialexpressioninfunction)
- [Find](ue_ue.MaterialEditingLibrary.md#find)
- [GetChildInstances](ue_ue.MaterialEditingLibrary.md#getchildinstances)
- [GetMaterialDefaultScalarParameterValue](ue_ue.MaterialEditingLibrary.md#getmaterialdefaultscalarparametervalue)
- [GetMaterialDefaultStaticSwitchParameterValue](ue_ue.MaterialEditingLibrary.md#getmaterialdefaultstaticswitchparametervalue)
- [GetMaterialDefaultTextureParameterValue](ue_ue.MaterialEditingLibrary.md#getmaterialdefaulttextureparametervalue)
- [GetMaterialDefaultVectorParameterValue](ue_ue.MaterialEditingLibrary.md#getmaterialdefaultvectorparametervalue)
- [GetMaterialInstanceScalarParameterValue](ue_ue.MaterialEditingLibrary.md#getmaterialinstancescalarparametervalue)
- [GetMaterialInstanceStaticSwitchParameterValue](ue_ue.MaterialEditingLibrary.md#getmaterialinstancestaticswitchparametervalue)
- [GetMaterialInstanceTextureParameterValue](ue_ue.MaterialEditingLibrary.md#getmaterialinstancetextureparametervalue)
- [GetMaterialInstanceVectorParameterValue](ue_ue.MaterialEditingLibrary.md#getmaterialinstancevectorparametervalue)
- [GetMaterialSelectedNodes](ue_ue.MaterialEditingLibrary.md#getmaterialselectednodes)
- [GetNumMaterialExpressions](ue_ue.MaterialEditingLibrary.md#getnummaterialexpressions)
- [GetNumMaterialExpressionsInFunction](ue_ue.MaterialEditingLibrary.md#getnummaterialexpressionsinfunction)
- [GetScalarParameterNames](ue_ue.MaterialEditingLibrary.md#getscalarparameternames)
- [GetStaticSwitchParameterNames](ue_ue.MaterialEditingLibrary.md#getstaticswitchparameternames)
- [GetTextureParameterNames](ue_ue.MaterialEditingLibrary.md#gettextureparameternames)
- [GetVectorParameterNames](ue_ue.MaterialEditingLibrary.md#getvectorparameternames)
- [HasMaterialUsage](ue_ue.MaterialEditingLibrary.md#hasmaterialusage)
- [LayoutMaterialExpressions](ue_ue.MaterialEditingLibrary.md#layoutmaterialexpressions)
- [LayoutMaterialFunctionExpressions](ue_ue.MaterialEditingLibrary.md#layoutmaterialfunctionexpressions)
- [Load](ue_ue.MaterialEditingLibrary.md#load)
- [RecompileMaterial](ue_ue.MaterialEditingLibrary.md#recompilematerial)
- [SetMaterialInstanceParent](ue_ue.MaterialEditingLibrary.md#setmaterialinstanceparent)
- [SetMaterialInstanceScalarParameterValue](ue_ue.MaterialEditingLibrary.md#setmaterialinstancescalarparametervalue)
- [SetMaterialInstanceTextureParameterValue](ue_ue.MaterialEditingLibrary.md#setmaterialinstancetextureparametervalue)
- [SetMaterialInstanceVectorParameterValue](ue_ue.MaterialEditingLibrary.md#setmaterialinstancevectorparametervalue)
- [SetMaterialUsage](ue_ue.MaterialEditingLibrary.md#setmaterialusage)
- [StaticClass](ue_ue.MaterialEditingLibrary.md#staticclass)
- [UpdateMaterialFunction](ue_ue.MaterialEditingLibrary.md#updatematerialfunction)
- [UpdateMaterialInstance](ue_ue.MaterialEditingLibrary.md#updatematerialinstance)

## Constructors

### constructor

• **new MaterialEditingLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:47268](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47268)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_MaterialEditingLibrary\_\_

• **\_\_tid\_MaterialEditingLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:47313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47313)

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

### GetScalarParameterSource

▸ **GetScalarParameterSource**(`Material`, `ParameterName`, `ParameterSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `ParameterName` | `string` |
| `ParameterSource` | [`$Ref`](../interfaces/puerts._Ref.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:47269](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47269)

___

### GetStaticSwitchParameterSource

▸ **GetStaticSwitchParameterSource**(`Material`, `ParameterName`, `ParameterSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `ParameterName` | `string` |
| `ParameterSource` | [`$Ref`](../interfaces/puerts._Ref.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:47270](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47270)

___

### GetTextureParameterSource

▸ **GetTextureParameterSource**(`Material`, `ParameterName`, `ParameterSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `ParameterName` | `string` |
| `ParameterSource` | [`$Ref`](../interfaces/puerts._Ref.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:47271](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47271)

___

### GetVectorParameterSource

▸ **GetVectorParameterSource**(`Material`, `ParameterName`, `ParameterSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `ParameterName` | `string` |
| `ParameterSource` | [`$Ref`](../interfaces/puerts._Ref.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:47272](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47272)

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

### ClearAllMaterialInstanceParameters

▸ `Static` **ClearAllMaterialInstanceParameters**(`Instance`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Instance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47273](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47273)

___

### ConnectMaterialExpressions

▸ `Static` **ConnectMaterialExpressions**(`FromExpression`, `FromOutputName`, `ToExpression`, `ToInputName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FromExpression` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialExpression`](ue_ue.MaterialExpression.md)\> |
| `FromOutputName` | `string` |
| `ToExpression` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialExpression`](ue_ue.MaterialExpression.md)\> |
| `ToInputName` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:47274](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47274)

___

### ConnectMaterialProperty

▸ `Static` **ConnectMaterialProperty**(`FromExpression`, `FromOutputName`, `Property`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FromExpression` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialExpression`](ue_ue.MaterialExpression.md)\> |
| `FromOutputName` | `string` |
| `Property` | [`EMaterialProperty`](../enums/ue_ue.EMaterialProperty.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:47275](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47275)

___

### CreateMaterialExpression

▸ `Static` **CreateMaterialExpression**(`Material`, `ExpressionClass`, `NodePosX?`, `NodePosY?`): [`MaterialExpression`](ue_ue.MaterialExpression.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Material`](ue_ue.Material.md)\> |
| `ExpressionClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `NodePosX?` | `number` |
| `NodePosY?` | `number` |

#### Returns

[`MaterialExpression`](ue_ue.MaterialExpression.md)

#### Defined in

[ue/ue.d.ts:47276](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47276)

___

### CreateMaterialExpressionInFunction

▸ `Static` **CreateMaterialExpressionInFunction**(`MaterialFunction`, `ExpressionClass`, `NodePosX?`, `NodePosY?`): [`MaterialExpression`](ue_ue.MaterialExpression.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialFunction` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialFunction`](ue_ue.MaterialFunction.md)\> |
| `ExpressionClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `NodePosX?` | `number` |
| `NodePosY?` | `number` |

#### Returns

[`MaterialExpression`](ue_ue.MaterialExpression.md)

#### Defined in

[ue/ue.d.ts:47277](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47277)

___

### DeleteAllMaterialExpressions

▸ `Static` **DeleteAllMaterialExpressions**(`Material`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Material`](ue_ue.Material.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47278](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47278)

___

### DeleteAllMaterialExpressionsInFunction

▸ `Static` **DeleteAllMaterialExpressionsInFunction**(`MaterialFunction`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialFunction` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialFunction`](ue_ue.MaterialFunction.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47279](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47279)

___

### DeleteMaterialExpression

▸ `Static` **DeleteMaterialExpression**(`Material`, `Expression`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Material`](ue_ue.Material.md)\> |
| `Expression` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialExpression`](ue_ue.MaterialExpression.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47280](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47280)

___

### DeleteMaterialExpressionInFunction

▸ `Static` **DeleteMaterialExpressionInFunction**(`MaterialFunction`, `Expression`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialFunction` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialFunction`](ue_ue.MaterialFunction.md)\> |
| `Expression` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialExpression`](ue_ue.MaterialExpression.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47281](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47281)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialEditingLibrary`](ue_ue.MaterialEditingLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialEditingLibrary`](ue_ue.MaterialEditingLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:47310](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47310)

___

### GetChildInstances

▸ `Static` **GetChildInstances**(`Parent`, `ChildInstances`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Parent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `ChildInstances` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47282](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47282)

___

### GetMaterialDefaultScalarParameterValue

▸ `Static` **GetMaterialDefaultScalarParameterValue**(`Material`, `ParameterName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Material`](ue_ue.Material.md)\> |
| `ParameterName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:47283](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47283)

___

### GetMaterialDefaultStaticSwitchParameterValue

▸ `Static` **GetMaterialDefaultStaticSwitchParameterValue**(`Material`, `ParameterName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Material`](ue_ue.Material.md)\> |
| `ParameterName` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:47284](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47284)

___

### GetMaterialDefaultTextureParameterValue

▸ `Static` **GetMaterialDefaultTextureParameterValue**(`Material`, `ParameterName`): [`Texture`](ue_ue.Texture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Material`](ue_ue.Material.md)\> |
| `ParameterName` | `string` |

#### Returns

[`Texture`](ue_ue.Texture.md)

#### Defined in

[ue/ue.d.ts:47285](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47285)

___

### GetMaterialDefaultVectorParameterValue

▸ `Static` **GetMaterialDefaultVectorParameterValue**(`Material`, `ParameterName`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Material`](ue_ue.Material.md)\> |
| `ParameterName` | `string` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:47286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47286)

___

### GetMaterialInstanceScalarParameterValue

▸ `Static` **GetMaterialInstanceScalarParameterValue**(`Instance`, `ParameterName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Instance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\> |
| `ParameterName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:47287](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47287)

___

### GetMaterialInstanceStaticSwitchParameterValue

▸ `Static` **GetMaterialInstanceStaticSwitchParameterValue**(`Instance`, `ParameterName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Instance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\> |
| `ParameterName` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:47288](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47288)

___

### GetMaterialInstanceTextureParameterValue

▸ `Static` **GetMaterialInstanceTextureParameterValue**(`Instance`, `ParameterName`): [`Texture`](ue_ue.Texture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Instance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\> |
| `ParameterName` | `string` |

#### Returns

[`Texture`](ue_ue.Texture.md)

#### Defined in

[ue/ue.d.ts:47289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47289)

___

### GetMaterialInstanceVectorParameterValue

▸ `Static` **GetMaterialInstanceVectorParameterValue**(`Instance`, `ParameterName`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Instance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\> |
| `ParameterName` | `string` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:47290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47290)

___

### GetMaterialSelectedNodes

▸ `Static` **GetMaterialSelectedNodes**(`Material`): [`TSet`](../interfaces/ue_puerts.TSet.md)<[`Object`](ue_ue.Object.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Material`](ue_ue.Material.md)\> |

#### Returns

[`TSet`](../interfaces/ue_puerts.TSet.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:47291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47291)

___

### GetNumMaterialExpressions

▸ `Static` **GetNumMaterialExpressions**(`Material`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Material`](ue_ue.Material.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:47292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47292)

___

### GetNumMaterialExpressionsInFunction

▸ `Static` **GetNumMaterialExpressionsInFunction**(`MaterialFunction`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialFunction` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialFunction`](ue_ue.MaterialFunction.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:47293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47293)

___

### GetScalarParameterNames

▸ `Static` **GetScalarParameterNames**(`Material`, `ParameterNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `ParameterNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47294)

___

### GetStaticSwitchParameterNames

▸ `Static` **GetStaticSwitchParameterNames**(`Material`, `ParameterNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `ParameterNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47295)

___

### GetTextureParameterNames

▸ `Static` **GetTextureParameterNames**(`Material`, `ParameterNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `ParameterNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47296)

___

### GetVectorParameterNames

▸ `Static` **GetVectorParameterNames**(`Material`, `ParameterNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `ParameterNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47297)

___

### HasMaterialUsage

▸ `Static` **HasMaterialUsage**(`Material`, `Usage`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Material`](ue_ue.Material.md)\> |
| `Usage` | [`EMaterialUsage`](../enums/ue_ue.EMaterialUsage.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:47298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47298)

___

### LayoutMaterialExpressions

▸ `Static` **LayoutMaterialExpressions**(`Material`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Material`](ue_ue.Material.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47299)

___

### LayoutMaterialFunctionExpressions

▸ `Static` **LayoutMaterialFunctionExpressions**(`MaterialFunction`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialFunction` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialFunction`](ue_ue.MaterialFunction.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47300)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialEditingLibrary`](ue_ue.MaterialEditingLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialEditingLibrary`](ue_ue.MaterialEditingLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:47311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47311)

___

### RecompileMaterial

▸ `Static` **RecompileMaterial**(`Material`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Material`](ue_ue.Material.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47301)

___

### SetMaterialInstanceParent

▸ `Static` **SetMaterialInstanceParent**(`Instance`, `NewParent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Instance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\> |
| `NewParent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47302)

___

### SetMaterialInstanceScalarParameterValue

▸ `Static` **SetMaterialInstanceScalarParameterValue**(`Instance`, `ParameterName`, `Value`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Instance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\> |
| `ParameterName` | `string` |
| `Value` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:47303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47303)

___

### SetMaterialInstanceTextureParameterValue

▸ `Static` **SetMaterialInstanceTextureParameterValue**(`Instance`, `ParameterName`, `Value`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Instance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\> |
| `ParameterName` | `string` |
| `Value` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:47304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47304)

___

### SetMaterialInstanceVectorParameterValue

▸ `Static` **SetMaterialInstanceVectorParameterValue**(`Instance`, `ParameterName`, `Value`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Instance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\> |
| `ParameterName` | `string` |
| `Value` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:47305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47305)

___

### SetMaterialUsage

▸ `Static` **SetMaterialUsage**(`Material`, `Usage`, `bNeedsRecompile`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Material`](ue_ue.Material.md)\> |
| `Usage` | [`EMaterialUsage`](../enums/ue_ue.EMaterialUsage.md) |
| `bNeedsRecompile` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:47306](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47306)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:47309](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47309)

___

### UpdateMaterialFunction

▸ `Static` **UpdateMaterialFunction**(`MaterialFunction`, `PreviewMaterial?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialFunction` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialFunctionInterface`](ue_ue.MaterialFunctionInterface.md)\> |
| `PreviewMaterial?` | [`Material`](ue_ue.Material.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47307](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47307)

___

### UpdateMaterialInstance

▸ `Static` **UpdateMaterialInstance**(`Instance`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Instance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:47308](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47308)
