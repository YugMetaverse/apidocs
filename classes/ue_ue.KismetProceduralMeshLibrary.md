[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KismetProceduralMeshLibrary

# Class: KismetProceduralMeshLibrary

[ue/ue](../modules/ue_ue.md).KismetProceduralMeshLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`KismetProceduralMeshLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.KismetProceduralMeshLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.KismetProceduralMeshLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_KismetProceduralMeshLibrary\_\_](ue_ue.KismetProceduralMeshLibrary.md#__tid_kismetproceduralmeshlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.KismetProceduralMeshLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.KismetProceduralMeshLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.KismetProceduralMeshLibrary.md#executeubergraph)
- [GetClass](ue_ue.KismetProceduralMeshLibrary.md#getclass)
- [GetName](ue_ue.KismetProceduralMeshLibrary.md#getname)
- [GetOuter](ue_ue.KismetProceduralMeshLibrary.md#getouter)
- [GetWorld](ue_ue.KismetProceduralMeshLibrary.md#getworld)
- [CalculateTangentsForMesh](ue_ue.KismetProceduralMeshLibrary.md#calculatetangentsformesh)
- [ConvertQuadToTriangles](ue_ue.KismetProceduralMeshLibrary.md#convertquadtotriangles)
- [CopyProceduralMeshFromStaticMeshComponent](ue_ue.KismetProceduralMeshLibrary.md#copyproceduralmeshfromstaticmeshcomponent)
- [CreateGridMeshSplit](ue_ue.KismetProceduralMeshLibrary.md#creategridmeshsplit)
- [CreateGridMeshTriangles](ue_ue.KismetProceduralMeshLibrary.md#creategridmeshtriangles)
- [CreateGridMeshWelded](ue_ue.KismetProceduralMeshLibrary.md#creategridmeshwelded)
- [Find](ue_ue.KismetProceduralMeshLibrary.md#find)
- [GenerateBoxMesh](ue_ue.KismetProceduralMeshLibrary.md#generateboxmesh)
- [GetSectionFromProceduralMesh](ue_ue.KismetProceduralMeshLibrary.md#getsectionfromproceduralmesh)
- [GetSectionFromStaticMesh](ue_ue.KismetProceduralMeshLibrary.md#getsectionfromstaticmesh)
- [Load](ue_ue.KismetProceduralMeshLibrary.md#load)
- [SliceProceduralMesh](ue_ue.KismetProceduralMeshLibrary.md#sliceproceduralmesh)
- [StaticClass](ue_ue.KismetProceduralMeshLibrary.md#staticclass)

## Constructors

### constructor

• **new KismetProceduralMeshLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:43051](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43051)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_KismetProceduralMeshLibrary\_\_

• **\_\_tid\_KismetProceduralMeshLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:43066](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43066)

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

### CalculateTangentsForMesh

▸ `Static` **CalculateTangentsForMesh**(`Vertices`, `Triangles`, `UVs`, `Normals`, `Tangents`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Vertices` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Triangles` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `UVs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |
| `Normals` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |
| `Tangents` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ProcMeshTangent`](ue_ue.ProcMeshTangent.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43052](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43052)

___

### ConvertQuadToTriangles

▸ `Static` **ConvertQuadToTriangles**(`Triangles`, `Vert0`, `Vert1`, `Vert2`, `Vert3`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Triangles` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |
| `Vert0` | `number` |
| `Vert1` | `number` |
| `Vert2` | `number` |
| `Vert3` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43053](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43053)

___

### CopyProceduralMeshFromStaticMeshComponent

▸ `Static` **CopyProceduralMeshFromStaticMeshComponent**(`StaticMeshComponent`, `LODIndex`, `ProcMeshComponent`, `bCreateCollision`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StaticMeshComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)\> |
| `LODIndex` | `number` |
| `ProcMeshComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ProceduralMeshComponent`](ue_ue.ProceduralMeshComponent.md)\> |
| `bCreateCollision` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43054](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43054)

___

### CreateGridMeshSplit

▸ `Static` **CreateGridMeshSplit**(`NumX`, `NumY`, `Triangles`, `Vertices`, `UVs`, `UV1s`, `GridSpacing?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumX` | `number` |
| `NumY` | `number` |
| `Triangles` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |
| `Vertices` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |
| `UVs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\>\> |
| `UV1s` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\>\> |
| `GridSpacing?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43055](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43055)

___

### CreateGridMeshTriangles

▸ `Static` **CreateGridMeshTriangles**(`NumX`, `NumY`, `bWinding`, `Triangles`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumX` | `number` |
| `NumY` | `number` |
| `bWinding` | `boolean` |
| `Triangles` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43056](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43056)

___

### CreateGridMeshWelded

▸ `Static` **CreateGridMeshWelded**(`NumX`, `NumY`, `Triangles`, `Vertices`, `UVs`, `GridSpacing?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumX` | `number` |
| `NumY` | `number` |
| `Triangles` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |
| `Vertices` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |
| `UVs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\>\> |
| `GridSpacing?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43057](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43057)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`KismetProceduralMeshLibrary`](ue_ue.KismetProceduralMeshLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`KismetProceduralMeshLibrary`](ue_ue.KismetProceduralMeshLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:43063](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43063)

___

### GenerateBoxMesh

▸ `Static` **GenerateBoxMesh**(`BoxRadius`, `Vertices`, `Triangles`, `Normals`, `UVs`, `Tangents`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoxRadius` | [`Vector`](ue_ue_s.Vector.md) |
| `Vertices` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |
| `Triangles` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |
| `Normals` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |
| `UVs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\>\> |
| `Tangents` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ProcMeshTangent`](ue_ue.ProcMeshTangent.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43058](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43058)

___

### GetSectionFromProceduralMesh

▸ `Static` **GetSectionFromProceduralMesh**(`InProcMesh`, `SectionIndex`, `Vertices`, `Triangles`, `Normals`, `UVs`, `Tangents`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InProcMesh` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ProceduralMeshComponent`](ue_ue.ProceduralMeshComponent.md)\> |
| `SectionIndex` | `number` |
| `Vertices` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |
| `Triangles` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |
| `Normals` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |
| `UVs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\>\> |
| `Tangents` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ProcMeshTangent`](ue_ue.ProcMeshTangent.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43059](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43059)

___

### GetSectionFromStaticMesh

▸ `Static` **GetSectionFromStaticMesh**(`InMesh`, `LODIndex`, `SectionIndex`, `Vertices`, `Triangles`, `Normals`, `UVs`, `Tangents`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMesh` | [`$Nullable`](../modules/puerts.md#$nullable)<[`StaticMesh`](ue_ue.StaticMesh.md)\> |
| `LODIndex` | `number` |
| `SectionIndex` | `number` |
| `Vertices` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |
| `Triangles` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |
| `Normals` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |
| `UVs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\>\> |
| `Tangents` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ProcMeshTangent`](ue_ue.ProcMeshTangent.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43060](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43060)

___

### Load

▸ `Static` **Load**(`InName`): [`KismetProceduralMeshLibrary`](ue_ue.KismetProceduralMeshLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`KismetProceduralMeshLibrary`](ue_ue.KismetProceduralMeshLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:43064](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43064)

___

### SliceProceduralMesh

▸ `Static` **SliceProceduralMesh**(`InProcMesh`, `PlanePosition`, `PlaneNormal`, `bCreateOtherHalf`, `OutOtherHalfProcMesh`, `CapOption`, `CapMaterial`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InProcMesh` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ProceduralMeshComponent`](ue_ue.ProceduralMeshComponent.md)\> |
| `PlanePosition` | [`Vector`](ue_ue_s.Vector.md) |
| `PlaneNormal` | [`Vector`](ue_ue_s.Vector.md) |
| `bCreateOtherHalf` | `boolean` |
| `OutOtherHalfProcMesh` | [`$Ref`](../interfaces/puerts._Ref.md)<[`ProceduralMeshComponent`](ue_ue.ProceduralMeshComponent.md)\> |
| `CapOption` | [`EProcMeshSliceCapOption`](../enums/ue_ue.EProcMeshSliceCapOption.md) |
| `CapMaterial` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43061](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43061)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:43062](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43062)
