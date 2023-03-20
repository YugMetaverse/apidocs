[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / StaticMeshDescription

# Class: StaticMeshDescription

[ue/ue](../modules/ue_ue.md).StaticMeshDescription

## Hierarchy

- [`MeshDescriptionBase`](ue_ue.MeshDescriptionBase.md)

  ↳ **`StaticMeshDescription`**

## Table of contents

### Constructors

- [constructor](ue_ue.StaticMeshDescription.md#constructor)

### Properties

- [\_\_tid\_MeshDescriptionBase\_\_](ue_ue.StaticMeshDescription.md#__tid_meshdescriptionbase__)
- [\_\_tid\_Object\_\_](ue_ue.StaticMeshDescription.md#__tid_object__)
- [\_\_tid\_StaticMeshDescription\_\_](ue_ue.StaticMeshDescription.md#__tid_staticmeshdescription__)

### Methods

- [ComputePolygonTriangulation](ue_ue.StaticMeshDescription.md#computepolygontriangulation)
- [CreateCube](ue_ue.StaticMeshDescription.md#createcube)
- [CreateDefaultSubobject](ue_ue.StaticMeshDescription.md#createdefaultsubobject)
- [CreateEdge](ue_ue.StaticMeshDescription.md#createedge)
- [CreateEdgeWithID](ue_ue.StaticMeshDescription.md#createedgewithid)
- [CreatePolygon](ue_ue.StaticMeshDescription.md#createpolygon)
- [CreatePolygonGroup](ue_ue.StaticMeshDescription.md#createpolygongroup)
- [CreatePolygonGroupWithID](ue_ue.StaticMeshDescription.md#createpolygongroupwithid)
- [CreatePolygonWithID](ue_ue.StaticMeshDescription.md#createpolygonwithid)
- [CreateTriangle](ue_ue.StaticMeshDescription.md#createtriangle)
- [CreateTriangleWithID](ue_ue.StaticMeshDescription.md#createtrianglewithid)
- [CreateVertex](ue_ue.StaticMeshDescription.md#createvertex)
- [CreateVertexInstance](ue_ue.StaticMeshDescription.md#createvertexinstance)
- [CreateVertexInstanceWithID](ue_ue.StaticMeshDescription.md#createvertexinstancewithid)
- [CreateVertexWithID](ue_ue.StaticMeshDescription.md#createvertexwithid)
- [DeleteEdge](ue_ue.StaticMeshDescription.md#deleteedge)
- [DeletePolygon](ue_ue.StaticMeshDescription.md#deletepolygon)
- [DeletePolygonGroup](ue_ue.StaticMeshDescription.md#deletepolygongroup)
- [DeleteTriangle](ue_ue.StaticMeshDescription.md#deletetriangle)
- [DeleteVertex](ue_ue.StaticMeshDescription.md#deletevertex)
- [DeleteVertexInstance](ue_ue.StaticMeshDescription.md#deletevertexinstance)
- [Empty](ue_ue.StaticMeshDescription.md#empty)
- [ExecuteUbergraph](ue_ue.StaticMeshDescription.md#executeubergraph)
- [GetClass](ue_ue.StaticMeshDescription.md#getclass)
- [GetEdgeConnectedPolygons](ue_ue.StaticMeshDescription.md#getedgeconnectedpolygons)
- [GetEdgeConnectedTriangles](ue_ue.StaticMeshDescription.md#getedgeconnectedtriangles)
- [GetEdgeVertex](ue_ue.StaticMeshDescription.md#getedgevertex)
- [GetEdgeVertices](ue_ue.StaticMeshDescription.md#getedgevertices)
- [GetName](ue_ue.StaticMeshDescription.md#getname)
- [GetNumEdgeConnectedPolygons](ue_ue.StaticMeshDescription.md#getnumedgeconnectedpolygons)
- [GetNumEdgeConnectedTriangles](ue_ue.StaticMeshDescription.md#getnumedgeconnectedtriangles)
- [GetNumPolygonGroupPolygons](ue_ue.StaticMeshDescription.md#getnumpolygongrouppolygons)
- [GetNumPolygonInternalEdges](ue_ue.StaticMeshDescription.md#getnumpolygoninternaledges)
- [GetNumPolygonTriangles](ue_ue.StaticMeshDescription.md#getnumpolygontriangles)
- [GetNumPolygonVertices](ue_ue.StaticMeshDescription.md#getnumpolygonvertices)
- [GetNumVertexConnectedEdges](ue_ue.StaticMeshDescription.md#getnumvertexconnectededges)
- [GetNumVertexConnectedPolygons](ue_ue.StaticMeshDescription.md#getnumvertexconnectedpolygons)
- [GetNumVertexConnectedTriangles](ue_ue.StaticMeshDescription.md#getnumvertexconnectedtriangles)
- [GetNumVertexInstanceConnectedPolygons](ue_ue.StaticMeshDescription.md#getnumvertexinstanceconnectedpolygons)
- [GetNumVertexInstanceConnectedTriangles](ue_ue.StaticMeshDescription.md#getnumvertexinstanceconnectedtriangles)
- [GetNumVertexVertexInstances](ue_ue.StaticMeshDescription.md#getnumvertexvertexinstances)
- [GetOuter](ue_ue.StaticMeshDescription.md#getouter)
- [GetPolygonAdjacentPolygons](ue_ue.StaticMeshDescription.md#getpolygonadjacentpolygons)
- [GetPolygonGroupPolygons](ue_ue.StaticMeshDescription.md#getpolygongrouppolygons)
- [GetPolygonInternalEdges](ue_ue.StaticMeshDescription.md#getpolygoninternaledges)
- [GetPolygonPerimeterEdges](ue_ue.StaticMeshDescription.md#getpolygonperimeteredges)
- [GetPolygonPolygonGroup](ue_ue.StaticMeshDescription.md#getpolygonpolygongroup)
- [GetPolygonTriangles](ue_ue.StaticMeshDescription.md#getpolygontriangles)
- [GetPolygonVertexInstances](ue_ue.StaticMeshDescription.md#getpolygonvertexinstances)
- [GetPolygonVertices](ue_ue.StaticMeshDescription.md#getpolygonvertices)
- [GetTriangleAdjacentTriangles](ue_ue.StaticMeshDescription.md#gettriangleadjacenttriangles)
- [GetTriangleEdges](ue_ue.StaticMeshDescription.md#gettriangleedges)
- [GetTrianglePolygon](ue_ue.StaticMeshDescription.md#gettrianglepolygon)
- [GetTrianglePolygonGroup](ue_ue.StaticMeshDescription.md#gettrianglepolygongroup)
- [GetTriangleVertexInstance](ue_ue.StaticMeshDescription.md#gettrianglevertexinstance)
- [GetTriangleVertexInstances](ue_ue.StaticMeshDescription.md#gettrianglevertexinstances)
- [GetTriangleVertices](ue_ue.StaticMeshDescription.md#gettrianglevertices)
- [GetVertexAdjacentVertices](ue_ue.StaticMeshDescription.md#getvertexadjacentvertices)
- [GetVertexConnectedEdges](ue_ue.StaticMeshDescription.md#getvertexconnectededges)
- [GetVertexConnectedPolygons](ue_ue.StaticMeshDescription.md#getvertexconnectedpolygons)
- [GetVertexConnectedTriangles](ue_ue.StaticMeshDescription.md#getvertexconnectedtriangles)
- [GetVertexInstanceConnectedPolygons](ue_ue.StaticMeshDescription.md#getvertexinstanceconnectedpolygons)
- [GetVertexInstanceConnectedTriangles](ue_ue.StaticMeshDescription.md#getvertexinstanceconnectedtriangles)
- [GetVertexInstanceForPolygonVertex](ue_ue.StaticMeshDescription.md#getvertexinstanceforpolygonvertex)
- [GetVertexInstanceForTriangleVertex](ue_ue.StaticMeshDescription.md#getvertexinstancefortrianglevertex)
- [GetVertexInstancePairEdge](ue_ue.StaticMeshDescription.md#getvertexinstancepairedge)
- [GetVertexInstanceUV](ue_ue.StaticMeshDescription.md#getvertexinstanceuv)
- [GetVertexInstanceVertex](ue_ue.StaticMeshDescription.md#getvertexinstancevertex)
- [GetVertexPairEdge](ue_ue.StaticMeshDescription.md#getvertexpairedge)
- [GetVertexPosition](ue_ue.StaticMeshDescription.md#getvertexposition)
- [GetVertexVertexInstances](ue_ue.StaticMeshDescription.md#getvertexvertexinstances)
- [GetWorld](ue_ue.StaticMeshDescription.md#getworld)
- [IsEdgeInternal](ue_ue.StaticMeshDescription.md#isedgeinternal)
- [IsEdgeInternalToPolygon](ue_ue.StaticMeshDescription.md#isedgeinternaltopolygon)
- [IsEdgeValid](ue_ue.StaticMeshDescription.md#isedgevalid)
- [IsEmpty](ue_ue.StaticMeshDescription.md#isempty)
- [IsPolygonGroupValid](ue_ue.StaticMeshDescription.md#ispolygongroupvalid)
- [IsPolygonValid](ue_ue.StaticMeshDescription.md#ispolygonvalid)
- [IsTrianglePartOfNgon](ue_ue.StaticMeshDescription.md#istrianglepartofngon)
- [IsTriangleValid](ue_ue.StaticMeshDescription.md#istrianglevalid)
- [IsVertexInstanceValid](ue_ue.StaticMeshDescription.md#isvertexinstancevalid)
- [IsVertexOrphaned](ue_ue.StaticMeshDescription.md#isvertexorphaned)
- [IsVertexValid](ue_ue.StaticMeshDescription.md#isvertexvalid)
- [ReserveNewEdges](ue_ue.StaticMeshDescription.md#reservenewedges)
- [ReserveNewPolygonGroups](ue_ue.StaticMeshDescription.md#reservenewpolygongroups)
- [ReserveNewPolygons](ue_ue.StaticMeshDescription.md#reservenewpolygons)
- [ReserveNewTriangles](ue_ue.StaticMeshDescription.md#reservenewtriangles)
- [ReserveNewVertexInstances](ue_ue.StaticMeshDescription.md#reservenewvertexinstances)
- [ReserveNewVertices](ue_ue.StaticMeshDescription.md#reservenewvertices)
- [ReversePolygonFacing](ue_ue.StaticMeshDescription.md#reversepolygonfacing)
- [SetPolygonGroupMaterialSlotName](ue_ue.StaticMeshDescription.md#setpolygongroupmaterialslotname)
- [SetPolygonPolygonGroup](ue_ue.StaticMeshDescription.md#setpolygonpolygongroup)
- [SetPolygonVertexInstance](ue_ue.StaticMeshDescription.md#setpolygonvertexinstance)
- [SetVertexInstanceUV](ue_ue.StaticMeshDescription.md#setvertexinstanceuv)
- [SetVertexPosition](ue_ue.StaticMeshDescription.md#setvertexposition)
- [Find](ue_ue.StaticMeshDescription.md#find)
- [Load](ue_ue.StaticMeshDescription.md#load)
- [StaticClass](ue_ue.StaticMeshDescription.md#staticclass)

## Constructors

### constructor

• **new StaticMeshDescription**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[constructor](ue_ue.MeshDescriptionBase.md#constructor)

#### Defined in

[ue/ue.d.ts:8057](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8057)

## Properties

### \_\_tid\_MeshDescriptionBase\_\_

• **\_\_tid\_MeshDescriptionBase\_\_**: `boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[__tid_MeshDescriptionBase__](ue_ue.MeshDescriptionBase.md#__tid_meshdescriptionbase__)

#### Defined in

[ue/ue.d.ts:8053](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8053)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[__tid_Object__](ue_ue.MeshDescriptionBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_StaticMeshDescription\_\_

• **\_\_tid\_StaticMeshDescription\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:8066](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8066)

## Methods

### ComputePolygonTriangulation

▸ **ComputePolygonTriangulation**(`PolygonID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[ComputePolygonTriangulation](ue_ue.MeshDescriptionBase.md#computepolygontriangulation)

#### Defined in

[ue/ue.d.ts:7964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7964)

___

### CreateCube

▸ **CreateCube**(`Center`, `HalfExtents`, `PolygonGroup`, `PolygonID_PlusX`, `PolygonID_MinusX`, `PolygonID_PlusY`, `PolygonID_MinusY`, `PolygonID_PlusZ`, `PolygonID_MinusZ`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Center` | [`Vector`](ue_ue_s.Vector.md) |
| `HalfExtents` | [`Vector`](ue_ue_s.Vector.md) |
| `PolygonGroup` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |
| `PolygonID_PlusX` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |
| `PolygonID_MinusX` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |
| `PolygonID_PlusY` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |
| `PolygonID_MinusY` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |
| `PolygonID_PlusZ` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |
| `PolygonID_MinusZ` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8058](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8058)

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

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreateDefaultSubobject](ue_ue.MeshDescriptionBase.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### CreateEdge

▸ **CreateEdge**(`VertexID0`, `VertexID1`): [`EdgeID`](ue_ue.EdgeID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID0` | [`VertexID`](ue_ue.VertexID.md) |
| `VertexID1` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

[`EdgeID`](ue_ue.EdgeID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreateEdge](ue_ue.MeshDescriptionBase.md#createedge)

#### Defined in

[ue/ue.d.ts:7965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7965)

___

### CreateEdgeWithID

▸ **CreateEdgeWithID**(`EdgeID`, `VertexID0`, `VertexID1`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `VertexID0` | [`VertexID`](ue_ue.VertexID.md) |
| `VertexID1` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreateEdgeWithID](ue_ue.MeshDescriptionBase.md#createedgewithid)

#### Defined in

[ue/ue.d.ts:7966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7966)

___

### CreatePolygon

▸ **CreatePolygon**(`PolygonGroupID`, `VertexInstanceIDs`, `NewEdgeIDs`): [`PolygonID`](ue_ue.PolygonID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |
| `VertexInstanceIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstanceID`](ue_ue.VertexInstanceID.md)\>\> |
| `NewEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

[`PolygonID`](ue_ue.PolygonID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreatePolygon](ue_ue.MeshDescriptionBase.md#createpolygon)

#### Defined in

[ue/ue.d.ts:7967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7967)

___

### CreatePolygonGroup

▸ **CreatePolygonGroup**(): [`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Returns

[`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreatePolygonGroup](ue_ue.MeshDescriptionBase.md#createpolygongroup)

#### Defined in

[ue/ue.d.ts:7968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7968)

___

### CreatePolygonGroupWithID

▸ **CreatePolygonGroupWithID**(`PolygonGroupID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreatePolygonGroupWithID](ue_ue.MeshDescriptionBase.md#createpolygongroupwithid)

#### Defined in

[ue/ue.d.ts:7969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7969)

___

### CreatePolygonWithID

▸ **CreatePolygonWithID**(`PolygonID`, `PolygonGroupID`, `VertexInstanceIDs`, `NewEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |
| `VertexInstanceIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstanceID`](ue_ue.VertexInstanceID.md)\>\> |
| `NewEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreatePolygonWithID](ue_ue.MeshDescriptionBase.md#createpolygonwithid)

#### Defined in

[ue/ue.d.ts:7970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7970)

___

### CreateTriangle

▸ **CreateTriangle**(`PolygonGroupID`, `VertexInstanceIDs`, `NewEdgeIDs`): [`TriangleID`](ue_ue.TriangleID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |
| `VertexInstanceIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstanceID`](ue_ue.VertexInstanceID.md)\> |
| `NewEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

[`TriangleID`](ue_ue.TriangleID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreateTriangle](ue_ue.MeshDescriptionBase.md#createtriangle)

#### Defined in

[ue/ue.d.ts:7971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7971)

___

### CreateTriangleWithID

▸ **CreateTriangleWithID**(`TriangleID`, `PolygonGroupID`, `VertexInstanceIDs`, `NewEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |
| `VertexInstanceIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstanceID`](ue_ue.VertexInstanceID.md)\> |
| `NewEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreateTriangleWithID](ue_ue.MeshDescriptionBase.md#createtrianglewithid)

#### Defined in

[ue/ue.d.ts:7972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7972)

___

### CreateVertex

▸ **CreateVertex**(): [`VertexID`](ue_ue.VertexID.md)

#### Returns

[`VertexID`](ue_ue.VertexID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreateVertex](ue_ue.MeshDescriptionBase.md#createvertex)

#### Defined in

[ue/ue.d.ts:7973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7973)

___

### CreateVertexInstance

▸ **CreateVertexInstance**(`VertexID`): [`VertexInstanceID`](ue_ue.VertexInstanceID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

[`VertexInstanceID`](ue_ue.VertexInstanceID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreateVertexInstance](ue_ue.MeshDescriptionBase.md#createvertexinstance)

#### Defined in

[ue/ue.d.ts:7974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7974)

___

### CreateVertexInstanceWithID

▸ **CreateVertexInstanceWithID**(`VertexInstanceID`, `VertexID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreateVertexInstanceWithID](ue_ue.MeshDescriptionBase.md#createvertexinstancewithid)

#### Defined in

[ue/ue.d.ts:7975](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7975)

___

### CreateVertexWithID

▸ **CreateVertexWithID**(`VertexID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreateVertexWithID](ue_ue.MeshDescriptionBase.md#createvertexwithid)

#### Defined in

[ue/ue.d.ts:7976](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7976)

___

### DeleteEdge

▸ **DeleteEdge**(`EdgeID`, `OrphanedVertices`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `OrphanedVertices` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[DeleteEdge](ue_ue.MeshDescriptionBase.md#deleteedge)

#### Defined in

[ue/ue.d.ts:7977](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7977)

___

### DeletePolygon

▸ **DeletePolygon**(`PolygonID`, `OrphanedEdges`, `OrphanedVertexInstances`, `OrphanedPolygonGroups`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `OrphanedEdges` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |
| `OrphanedVertexInstances` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstanceID`](ue_ue.VertexInstanceID.md)\>\> |
| `OrphanedPolygonGroups` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonGroupID`](ue_ue.PolygonGroupID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[DeletePolygon](ue_ue.MeshDescriptionBase.md#deletepolygon)

#### Defined in

[ue/ue.d.ts:7978](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7978)

___

### DeletePolygonGroup

▸ **DeletePolygonGroup**(`PolygonGroupID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[DeletePolygonGroup](ue_ue.MeshDescriptionBase.md#deletepolygongroup)

#### Defined in

[ue/ue.d.ts:7979](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7979)

___

### DeleteTriangle

▸ **DeleteTriangle**(`TriangleID`, `OrphanedEdges`, `OrphanedVertexInstances`, `OrphanedPolygonGroupsPtr`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |
| `OrphanedEdges` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |
| `OrphanedVertexInstances` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstanceID`](ue_ue.VertexInstanceID.md)\>\> |
| `OrphanedPolygonGroupsPtr` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonGroupID`](ue_ue.PolygonGroupID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[DeleteTriangle](ue_ue.MeshDescriptionBase.md#deletetriangle)

#### Defined in

[ue/ue.d.ts:7980](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7980)

___

### DeleteVertex

▸ **DeleteVertex**(`VertexID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[DeleteVertex](ue_ue.MeshDescriptionBase.md#deletevertex)

#### Defined in

[ue/ue.d.ts:7981](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7981)

___

### DeleteVertexInstance

▸ **DeleteVertexInstance**(`VertexInstanceID`, `OrphanedVertices`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |
| `OrphanedVertices` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[DeleteVertexInstance](ue_ue.MeshDescriptionBase.md#deletevertexinstance)

#### Defined in

[ue/ue.d.ts:7982](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7982)

___

### Empty

▸ **Empty**(): `void`

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[Empty](ue_ue.MeshDescriptionBase.md#empty)

#### Defined in

[ue/ue.d.ts:7983](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7983)

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

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[ExecuteUbergraph](ue_ue.MeshDescriptionBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetClass](ue_ue.MeshDescriptionBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetEdgeConnectedPolygons

▸ **GetEdgeConnectedPolygons**(`EdgeID`, `OutConnectedPolygonIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `OutConnectedPolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetEdgeConnectedPolygons](ue_ue.MeshDescriptionBase.md#getedgeconnectedpolygons)

#### Defined in

[ue/ue.d.ts:7984](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7984)

___

### GetEdgeConnectedTriangles

▸ **GetEdgeConnectedTriangles**(`EdgeID`, `OutConnectedTriangleIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `OutConnectedTriangleIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`TriangleID`](ue_ue.TriangleID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetEdgeConnectedTriangles](ue_ue.MeshDescriptionBase.md#getedgeconnectedtriangles)

#### Defined in

[ue/ue.d.ts:7985](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7985)

___

### GetEdgeVertex

▸ **GetEdgeVertex**(`EdgeID`, `VertexNumber`): [`VertexID`](ue_ue.VertexID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `VertexNumber` | `number` |

#### Returns

[`VertexID`](ue_ue.VertexID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetEdgeVertex](ue_ue.MeshDescriptionBase.md#getedgevertex)

#### Defined in

[ue/ue.d.ts:7986](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7986)

___

### GetEdgeVertices

▸ **GetEdgeVertices**(`EdgeID`, `OutVertexIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `OutVertexIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetEdgeVertices](ue_ue.MeshDescriptionBase.md#getedgevertices)

#### Defined in

[ue/ue.d.ts:7987](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7987)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetName](ue_ue.MeshDescriptionBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetNumEdgeConnectedPolygons

▸ **GetNumEdgeConnectedPolygons**(`EdgeID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |

#### Returns

`number`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetNumEdgeConnectedPolygons](ue_ue.MeshDescriptionBase.md#getnumedgeconnectedpolygons)

#### Defined in

[ue/ue.d.ts:7988](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7988)

___

### GetNumEdgeConnectedTriangles

▸ **GetNumEdgeConnectedTriangles**(`EdgeID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |

#### Returns

`number`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetNumEdgeConnectedTriangles](ue_ue.MeshDescriptionBase.md#getnumedgeconnectedtriangles)

#### Defined in

[ue/ue.d.ts:7989](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7989)

___

### GetNumPolygonGroupPolygons

▸ **GetNumPolygonGroupPolygons**(`PolygonGroupID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |

#### Returns

`number`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetNumPolygonGroupPolygons](ue_ue.MeshDescriptionBase.md#getnumpolygongrouppolygons)

#### Defined in

[ue/ue.d.ts:7990](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7990)

___

### GetNumPolygonInternalEdges

▸ **GetNumPolygonInternalEdges**(`PolygonID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`number`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetNumPolygonInternalEdges](ue_ue.MeshDescriptionBase.md#getnumpolygoninternaledges)

#### Defined in

[ue/ue.d.ts:7991](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7991)

___

### GetNumPolygonTriangles

▸ **GetNumPolygonTriangles**(`PolygonID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`number`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetNumPolygonTriangles](ue_ue.MeshDescriptionBase.md#getnumpolygontriangles)

#### Defined in

[ue/ue.d.ts:7992](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7992)

___

### GetNumPolygonVertices

▸ **GetNumPolygonVertices**(`PolygonID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`number`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetNumPolygonVertices](ue_ue.MeshDescriptionBase.md#getnumpolygonvertices)

#### Defined in

[ue/ue.d.ts:7993](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7993)

___

### GetNumVertexConnectedEdges

▸ **GetNumVertexConnectedEdges**(`VertexID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`number`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetNumVertexConnectedEdges](ue_ue.MeshDescriptionBase.md#getnumvertexconnectededges)

#### Defined in

[ue/ue.d.ts:7994](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7994)

___

### GetNumVertexConnectedPolygons

▸ **GetNumVertexConnectedPolygons**(`VertexID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`number`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetNumVertexConnectedPolygons](ue_ue.MeshDescriptionBase.md#getnumvertexconnectedpolygons)

#### Defined in

[ue/ue.d.ts:7995](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7995)

___

### GetNumVertexConnectedTriangles

▸ **GetNumVertexConnectedTriangles**(`VertexID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`number`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetNumVertexConnectedTriangles](ue_ue.MeshDescriptionBase.md#getnumvertexconnectedtriangles)

#### Defined in

[ue/ue.d.ts:7996](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7996)

___

### GetNumVertexInstanceConnectedPolygons

▸ **GetNumVertexInstanceConnectedPolygons**(`VertexInstanceID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |

#### Returns

`number`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetNumVertexInstanceConnectedPolygons](ue_ue.MeshDescriptionBase.md#getnumvertexinstanceconnectedpolygons)

#### Defined in

[ue/ue.d.ts:7997](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7997)

___

### GetNumVertexInstanceConnectedTriangles

▸ **GetNumVertexInstanceConnectedTriangles**(`VertexInstanceID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |

#### Returns

`number`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetNumVertexInstanceConnectedTriangles](ue_ue.MeshDescriptionBase.md#getnumvertexinstanceconnectedtriangles)

#### Defined in

[ue/ue.d.ts:7998](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7998)

___

### GetNumVertexVertexInstances

▸ **GetNumVertexVertexInstances**(`VertexID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`number`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetNumVertexVertexInstances](ue_ue.MeshDescriptionBase.md#getnumvertexvertexinstances)

#### Defined in

[ue/ue.d.ts:7999](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7999)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetOuter](ue_ue.MeshDescriptionBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetPolygonAdjacentPolygons

▸ **GetPolygonAdjacentPolygons**(`PolygonID`, `OutPolygonIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `OutPolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetPolygonAdjacentPolygons](ue_ue.MeshDescriptionBase.md#getpolygonadjacentpolygons)

#### Defined in

[ue/ue.d.ts:8000](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8000)

___

### GetPolygonGroupPolygons

▸ **GetPolygonGroupPolygons**(`PolygonGroupID`, `OutPolygonIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |
| `OutPolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetPolygonGroupPolygons](ue_ue.MeshDescriptionBase.md#getpolygongrouppolygons)

#### Defined in

[ue/ue.d.ts:8001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8001)

___

### GetPolygonInternalEdges

▸ **GetPolygonInternalEdges**(`PolygonID`, `OutEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `OutEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetPolygonInternalEdges](ue_ue.MeshDescriptionBase.md#getpolygoninternaledges)

#### Defined in

[ue/ue.d.ts:8002](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8002)

___

### GetPolygonPerimeterEdges

▸ **GetPolygonPerimeterEdges**(`PolygonID`, `OutEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `OutEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetPolygonPerimeterEdges](ue_ue.MeshDescriptionBase.md#getpolygonperimeteredges)

#### Defined in

[ue/ue.d.ts:8003](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8003)

___

### GetPolygonPolygonGroup

▸ **GetPolygonPolygonGroup**(`PolygonID`): [`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

[`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetPolygonPolygonGroup](ue_ue.MeshDescriptionBase.md#getpolygonpolygongroup)

#### Defined in

[ue/ue.d.ts:8004](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8004)

___

### GetPolygonTriangles

▸ **GetPolygonTriangles**(`PolygonID`, `OutTriangleIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `OutTriangleIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`TriangleID`](ue_ue.TriangleID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetPolygonTriangles](ue_ue.MeshDescriptionBase.md#getpolygontriangles)

#### Defined in

[ue/ue.d.ts:8005](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8005)

___

### GetPolygonVertexInstances

▸ **GetPolygonVertexInstances**(`PolygonID`, `OutVertexInstanceIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `OutVertexInstanceIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstanceID`](ue_ue.VertexInstanceID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetPolygonVertexInstances](ue_ue.MeshDescriptionBase.md#getpolygonvertexinstances)

#### Defined in

[ue/ue.d.ts:8006](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8006)

___

### GetPolygonVertices

▸ **GetPolygonVertices**(`PolygonID`, `OutVertexIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `OutVertexIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetPolygonVertices](ue_ue.MeshDescriptionBase.md#getpolygonvertices)

#### Defined in

[ue/ue.d.ts:8007](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8007)

___

### GetTriangleAdjacentTriangles

▸ **GetTriangleAdjacentTriangles**(`TriangleID`, `OutTriangleIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |
| `OutTriangleIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`TriangleID`](ue_ue.TriangleID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetTriangleAdjacentTriangles](ue_ue.MeshDescriptionBase.md#gettriangleadjacenttriangles)

#### Defined in

[ue/ue.d.ts:8008](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8008)

___

### GetTriangleEdges

▸ **GetTriangleEdges**(`TriangleID`, `OutEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |
| `OutEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetTriangleEdges](ue_ue.MeshDescriptionBase.md#gettriangleedges)

#### Defined in

[ue/ue.d.ts:8009](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8009)

___

### GetTrianglePolygon

▸ **GetTrianglePolygon**(`TriangleID`): [`PolygonID`](ue_ue.PolygonID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |

#### Returns

[`PolygonID`](ue_ue.PolygonID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetTrianglePolygon](ue_ue.MeshDescriptionBase.md#gettrianglepolygon)

#### Defined in

[ue/ue.d.ts:8010](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8010)

___

### GetTrianglePolygonGroup

▸ **GetTrianglePolygonGroup**(`TriangleID`): [`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |

#### Returns

[`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetTrianglePolygonGroup](ue_ue.MeshDescriptionBase.md#gettrianglepolygongroup)

#### Defined in

[ue/ue.d.ts:8011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8011)

___

### GetTriangleVertexInstance

▸ **GetTriangleVertexInstance**(`TriangleID`, `Index`): [`VertexInstanceID`](ue_ue.VertexInstanceID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |
| `Index` | `number` |

#### Returns

[`VertexInstanceID`](ue_ue.VertexInstanceID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetTriangleVertexInstance](ue_ue.MeshDescriptionBase.md#gettrianglevertexinstance)

#### Defined in

[ue/ue.d.ts:8012](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8012)

___

### GetTriangleVertexInstances

▸ **GetTriangleVertexInstances**(`TriangleID`, `OutVertexInstanceIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |
| `OutVertexInstanceIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstanceID`](ue_ue.VertexInstanceID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetTriangleVertexInstances](ue_ue.MeshDescriptionBase.md#gettrianglevertexinstances)

#### Defined in

[ue/ue.d.ts:8013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8013)

___

### GetTriangleVertices

▸ **GetTriangleVertices**(`TriangleID`, `OutVertexIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |
| `OutVertexIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetTriangleVertices](ue_ue.MeshDescriptionBase.md#gettrianglevertices)

#### Defined in

[ue/ue.d.ts:8014](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8014)

___

### GetVertexAdjacentVertices

▸ **GetVertexAdjacentVertices**(`VertexID`, `OutAdjacentVertexIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |
| `OutAdjacentVertexIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetVertexAdjacentVertices](ue_ue.MeshDescriptionBase.md#getvertexadjacentvertices)

#### Defined in

[ue/ue.d.ts:8015](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8015)

___

### GetVertexConnectedEdges

▸ **GetVertexConnectedEdges**(`VertexID`, `OutEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |
| `OutEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetVertexConnectedEdges](ue_ue.MeshDescriptionBase.md#getvertexconnectededges)

#### Defined in

[ue/ue.d.ts:8016](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8016)

___

### GetVertexConnectedPolygons

▸ **GetVertexConnectedPolygons**(`VertexID`, `OutConnectedPolygonIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |
| `OutConnectedPolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetVertexConnectedPolygons](ue_ue.MeshDescriptionBase.md#getvertexconnectedpolygons)

#### Defined in

[ue/ue.d.ts:8017](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8017)

___

### GetVertexConnectedTriangles

▸ **GetVertexConnectedTriangles**(`VertexID`, `OutConnectedTriangleIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |
| `OutConnectedTriangleIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`TriangleID`](ue_ue.TriangleID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetVertexConnectedTriangles](ue_ue.MeshDescriptionBase.md#getvertexconnectedtriangles)

#### Defined in

[ue/ue.d.ts:8018](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8018)

___

### GetVertexInstanceConnectedPolygons

▸ **GetVertexInstanceConnectedPolygons**(`VertexInstanceID`, `OutConnectedPolygonIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |
| `OutConnectedPolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetVertexInstanceConnectedPolygons](ue_ue.MeshDescriptionBase.md#getvertexinstanceconnectedpolygons)

#### Defined in

[ue/ue.d.ts:8019](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8019)

___

### GetVertexInstanceConnectedTriangles

▸ **GetVertexInstanceConnectedTriangles**(`VertexInstanceID`, `OutConnectedTriangleIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |
| `OutConnectedTriangleIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`TriangleID`](ue_ue.TriangleID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetVertexInstanceConnectedTriangles](ue_ue.MeshDescriptionBase.md#getvertexinstanceconnectedtriangles)

#### Defined in

[ue/ue.d.ts:8020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8020)

___

### GetVertexInstanceForPolygonVertex

▸ **GetVertexInstanceForPolygonVertex**(`PolygonID`, `VertexID`): [`VertexInstanceID`](ue_ue.VertexInstanceID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

[`VertexInstanceID`](ue_ue.VertexInstanceID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetVertexInstanceForPolygonVertex](ue_ue.MeshDescriptionBase.md#getvertexinstanceforpolygonvertex)

#### Defined in

[ue/ue.d.ts:8021](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8021)

___

### GetVertexInstanceForTriangleVertex

▸ **GetVertexInstanceForTriangleVertex**(`TriangleID`, `VertexID`): [`VertexInstanceID`](ue_ue.VertexInstanceID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

[`VertexInstanceID`](ue_ue.VertexInstanceID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetVertexInstanceForTriangleVertex](ue_ue.MeshDescriptionBase.md#getvertexinstancefortrianglevertex)

#### Defined in

[ue/ue.d.ts:8022](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8022)

___

### GetVertexInstancePairEdge

▸ **GetVertexInstancePairEdge**(`VertexInstanceID0`, `VertexInstanceID1`): [`EdgeID`](ue_ue.EdgeID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID0` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |
| `VertexInstanceID1` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |

#### Returns

[`EdgeID`](ue_ue.EdgeID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetVertexInstancePairEdge](ue_ue.MeshDescriptionBase.md#getvertexinstancepairedge)

#### Defined in

[ue/ue.d.ts:8023](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8023)

___

### GetVertexInstanceUV

▸ **GetVertexInstanceUV**(`VertexInstanceID`, `UVIndex?`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |
| `UVIndex?` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:8059](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8059)

___

### GetVertexInstanceVertex

▸ **GetVertexInstanceVertex**(`VertexInstanceID`): [`VertexID`](ue_ue.VertexID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |

#### Returns

[`VertexID`](ue_ue.VertexID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetVertexInstanceVertex](ue_ue.MeshDescriptionBase.md#getvertexinstancevertex)

#### Defined in

[ue/ue.d.ts:8024](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8024)

___

### GetVertexPairEdge

▸ **GetVertexPairEdge**(`VertexID0`, `VertexID1`): [`EdgeID`](ue_ue.EdgeID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID0` | [`VertexID`](ue_ue.VertexID.md) |
| `VertexID1` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

[`EdgeID`](ue_ue.EdgeID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetVertexPairEdge](ue_ue.MeshDescriptionBase.md#getvertexpairedge)

#### Defined in

[ue/ue.d.ts:8025](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8025)

___

### GetVertexPosition

▸ **GetVertexPosition**(`VertexID`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetVertexPosition](ue_ue.MeshDescriptionBase.md#getvertexposition)

#### Defined in

[ue/ue.d.ts:8026](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8026)

___

### GetVertexVertexInstances

▸ **GetVertexVertexInstances**(`VertexID`, `OutVertexInstanceIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |
| `OutVertexInstanceIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstanceID`](ue_ue.VertexInstanceID.md)\>\> |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetVertexVertexInstances](ue_ue.MeshDescriptionBase.md#getvertexvertexinstances)

#### Defined in

[ue/ue.d.ts:8027](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8027)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetWorld](ue_ue.MeshDescriptionBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsEdgeInternal

▸ **IsEdgeInternal**(`EdgeID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |

#### Returns

`boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[IsEdgeInternal](ue_ue.MeshDescriptionBase.md#isedgeinternal)

#### Defined in

[ue/ue.d.ts:8028](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8028)

___

### IsEdgeInternalToPolygon

▸ **IsEdgeInternalToPolygon**(`EdgeID`, `PolygonID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[IsEdgeInternalToPolygon](ue_ue.MeshDescriptionBase.md#isedgeinternaltopolygon)

#### Defined in

[ue/ue.d.ts:8029](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8029)

___

### IsEdgeValid

▸ **IsEdgeValid**(`EdgeID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |

#### Returns

`boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[IsEdgeValid](ue_ue.MeshDescriptionBase.md#isedgevalid)

#### Defined in

[ue/ue.d.ts:8030](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8030)

___

### IsEmpty

▸ **IsEmpty**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[IsEmpty](ue_ue.MeshDescriptionBase.md#isempty)

#### Defined in

[ue/ue.d.ts:8031](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8031)

___

### IsPolygonGroupValid

▸ **IsPolygonGroupValid**(`PolygonGroupID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |

#### Returns

`boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[IsPolygonGroupValid](ue_ue.MeshDescriptionBase.md#ispolygongroupvalid)

#### Defined in

[ue/ue.d.ts:8032](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8032)

___

### IsPolygonValid

▸ **IsPolygonValid**(`PolygonID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[IsPolygonValid](ue_ue.MeshDescriptionBase.md#ispolygonvalid)

#### Defined in

[ue/ue.d.ts:8033](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8033)

___

### IsTrianglePartOfNgon

▸ **IsTrianglePartOfNgon**(`TriangleID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |

#### Returns

`boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[IsTrianglePartOfNgon](ue_ue.MeshDescriptionBase.md#istrianglepartofngon)

#### Defined in

[ue/ue.d.ts:8034](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8034)

___

### IsTriangleValid

▸ **IsTriangleValid**(`TriangleID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |

#### Returns

`boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[IsTriangleValid](ue_ue.MeshDescriptionBase.md#istrianglevalid)

#### Defined in

[ue/ue.d.ts:8035](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8035)

___

### IsVertexInstanceValid

▸ **IsVertexInstanceValid**(`VertexInstanceID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |

#### Returns

`boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[IsVertexInstanceValid](ue_ue.MeshDescriptionBase.md#isvertexinstancevalid)

#### Defined in

[ue/ue.d.ts:8036](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8036)

___

### IsVertexOrphaned

▸ **IsVertexOrphaned**(`VertexID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[IsVertexOrphaned](ue_ue.MeshDescriptionBase.md#isvertexorphaned)

#### Defined in

[ue/ue.d.ts:8037](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8037)

___

### IsVertexValid

▸ **IsVertexValid**(`VertexID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[IsVertexValid](ue_ue.MeshDescriptionBase.md#isvertexvalid)

#### Defined in

[ue/ue.d.ts:8038](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8038)

___

### ReserveNewEdges

▸ **ReserveNewEdges**(`NumberOfNewEdges`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumberOfNewEdges` | `number` |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[ReserveNewEdges](ue_ue.MeshDescriptionBase.md#reservenewedges)

#### Defined in

[ue/ue.d.ts:8039](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8039)

___

### ReserveNewPolygonGroups

▸ **ReserveNewPolygonGroups**(`NumberOfNewPolygonGroups`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumberOfNewPolygonGroups` | `number` |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[ReserveNewPolygonGroups](ue_ue.MeshDescriptionBase.md#reservenewpolygongroups)

#### Defined in

[ue/ue.d.ts:8040](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8040)

___

### ReserveNewPolygons

▸ **ReserveNewPolygons**(`NumberOfNewPolygons`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumberOfNewPolygons` | `number` |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[ReserveNewPolygons](ue_ue.MeshDescriptionBase.md#reservenewpolygons)

#### Defined in

[ue/ue.d.ts:8041](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8041)

___

### ReserveNewTriangles

▸ **ReserveNewTriangles**(`NumberOfNewTriangles`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumberOfNewTriangles` | `number` |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[ReserveNewTriangles](ue_ue.MeshDescriptionBase.md#reservenewtriangles)

#### Defined in

[ue/ue.d.ts:8042](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8042)

___

### ReserveNewVertexInstances

▸ **ReserveNewVertexInstances**(`NumberOfNewVertexInstances`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumberOfNewVertexInstances` | `number` |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[ReserveNewVertexInstances](ue_ue.MeshDescriptionBase.md#reservenewvertexinstances)

#### Defined in

[ue/ue.d.ts:8043](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8043)

___

### ReserveNewVertices

▸ **ReserveNewVertices**(`NumberOfNewVertices`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumberOfNewVertices` | `number` |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[ReserveNewVertices](ue_ue.MeshDescriptionBase.md#reservenewvertices)

#### Defined in

[ue/ue.d.ts:8044](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8044)

___

### ReversePolygonFacing

▸ **ReversePolygonFacing**(`PolygonID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[ReversePolygonFacing](ue_ue.MeshDescriptionBase.md#reversepolygonfacing)

#### Defined in

[ue/ue.d.ts:8045](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8045)

___

### SetPolygonGroupMaterialSlotName

▸ **SetPolygonGroupMaterialSlotName**(`PolygonGroupID`, `SlotName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |
| `SlotName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8060](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8060)

___

### SetPolygonPolygonGroup

▸ **SetPolygonPolygonGroup**(`PolygonID`, `PolygonGroupID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[SetPolygonPolygonGroup](ue_ue.MeshDescriptionBase.md#setpolygonpolygongroup)

#### Defined in

[ue/ue.d.ts:8046](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8046)

___

### SetPolygonVertexInstance

▸ **SetPolygonVertexInstance**(`PolygonID`, `PerimeterIndex`, `VertexInstanceID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `PerimeterIndex` | `number` |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[SetPolygonVertexInstance](ue_ue.MeshDescriptionBase.md#setpolygonvertexinstance)

#### Defined in

[ue/ue.d.ts:8047](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8047)

___

### SetVertexInstanceUV

▸ **SetVertexInstanceUV**(`VertexInstanceID`, `UV`, `UVIndex?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |
| `UV` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `UVIndex?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8061](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8061)

___

### SetVertexPosition

▸ **SetVertexPosition**(`VertexID`, `Position`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |
| `Position` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[SetVertexPosition](ue_ue.MeshDescriptionBase.md#setvertexposition)

#### Defined in

[ue/ue.d.ts:8048](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8048)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`StaticMeshDescription`](ue_ue.StaticMeshDescription.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`StaticMeshDescription`](ue_ue.StaticMeshDescription.md)

#### Overrides

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[Find](ue_ue.MeshDescriptionBase.md#find)

#### Defined in

[ue/ue.d.ts:8063](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8063)

___

### Load

▸ `Static` **Load**(`InName`): [`StaticMeshDescription`](ue_ue.StaticMeshDescription.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`StaticMeshDescription`](ue_ue.StaticMeshDescription.md)

#### Overrides

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[Load](ue_ue.MeshDescriptionBase.md#load)

#### Defined in

[ue/ue.d.ts:8064](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8064)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[StaticClass](ue_ue.MeshDescriptionBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:8062](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8062)
