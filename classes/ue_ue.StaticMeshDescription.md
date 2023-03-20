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

## Properties

### \_\_tid\_MeshDescriptionBase\_\_

• **\_\_tid\_MeshDescriptionBase\_\_**: `boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[__tid_MeshDescriptionBase__](ue_ue.MeshDescriptionBase.md#__tid_meshdescriptionbase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[__tid_Object__](ue_ue.MeshDescriptionBase.md#__tid_object__)

___

### \_\_tid\_StaticMeshDescription\_\_

• **\_\_tid\_StaticMeshDescription\_\_**: `boolean`

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

___

### CreatePolygonGroup

▸ **CreatePolygonGroup**(): [`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Returns

[`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreatePolygonGroup](ue_ue.MeshDescriptionBase.md#createpolygongroup)

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

___

### CreateVertex

▸ **CreateVertex**(): [`VertexID`](ue_ue.VertexID.md)

#### Returns

[`VertexID`](ue_ue.VertexID.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[CreateVertex](ue_ue.MeshDescriptionBase.md#createvertex)

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

___

### Empty

▸ **Empty**(): `void`

#### Returns

`void`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[Empty](ue_ue.MeshDescriptionBase.md#empty)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetClass](ue_ue.MeshDescriptionBase.md#getclass)

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

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetName](ue_ue.MeshDescriptionBase.md#getname)

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

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetOuter](ue_ue.MeshDescriptionBase.md#getouter)

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

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[GetWorld](ue_ue.MeshDescriptionBase.md#getworld)

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

___

### IsEmpty

▸ **IsEmpty**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[IsEmpty](ue_ue.MeshDescriptionBase.md#isempty)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MeshDescriptionBase](ue_ue.MeshDescriptionBase.md).[StaticClass](ue_ue.MeshDescriptionBase.md#staticclass)
