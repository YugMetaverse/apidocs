[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MeshDescriptionBase

# Class: MeshDescriptionBase

[ue/ue](../modules/ue_ue.md).MeshDescriptionBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MeshDescriptionBase`**

  ↳↳ [`StaticMeshDescription`](ue_ue.StaticMeshDescription.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MeshDescriptionBase.md#constructor)

### Properties

- [\_\_tid\_MeshDescriptionBase\_\_](ue_ue.MeshDescriptionBase.md#__tid_meshdescriptionbase__)
- [\_\_tid\_Object\_\_](ue_ue.MeshDescriptionBase.md#__tid_object__)

### Methods

- [ComputePolygonTriangulation](ue_ue.MeshDescriptionBase.md#computepolygontriangulation)
- [CreateDefaultSubobject](ue_ue.MeshDescriptionBase.md#createdefaultsubobject)
- [CreateEdge](ue_ue.MeshDescriptionBase.md#createedge)
- [CreateEdgeWithID](ue_ue.MeshDescriptionBase.md#createedgewithid)
- [CreatePolygon](ue_ue.MeshDescriptionBase.md#createpolygon)
- [CreatePolygonGroup](ue_ue.MeshDescriptionBase.md#createpolygongroup)
- [CreatePolygonGroupWithID](ue_ue.MeshDescriptionBase.md#createpolygongroupwithid)
- [CreatePolygonWithID](ue_ue.MeshDescriptionBase.md#createpolygonwithid)
- [CreateTriangle](ue_ue.MeshDescriptionBase.md#createtriangle)
- [CreateTriangleWithID](ue_ue.MeshDescriptionBase.md#createtrianglewithid)
- [CreateVertex](ue_ue.MeshDescriptionBase.md#createvertex)
- [CreateVertexInstance](ue_ue.MeshDescriptionBase.md#createvertexinstance)
- [CreateVertexInstanceWithID](ue_ue.MeshDescriptionBase.md#createvertexinstancewithid)
- [CreateVertexWithID](ue_ue.MeshDescriptionBase.md#createvertexwithid)
- [DeleteEdge](ue_ue.MeshDescriptionBase.md#deleteedge)
- [DeletePolygon](ue_ue.MeshDescriptionBase.md#deletepolygon)
- [DeletePolygonGroup](ue_ue.MeshDescriptionBase.md#deletepolygongroup)
- [DeleteTriangle](ue_ue.MeshDescriptionBase.md#deletetriangle)
- [DeleteVertex](ue_ue.MeshDescriptionBase.md#deletevertex)
- [DeleteVertexInstance](ue_ue.MeshDescriptionBase.md#deletevertexinstance)
- [Empty](ue_ue.MeshDescriptionBase.md#empty)
- [ExecuteUbergraph](ue_ue.MeshDescriptionBase.md#executeubergraph)
- [GetClass](ue_ue.MeshDescriptionBase.md#getclass)
- [GetEdgeConnectedPolygons](ue_ue.MeshDescriptionBase.md#getedgeconnectedpolygons)
- [GetEdgeConnectedTriangles](ue_ue.MeshDescriptionBase.md#getedgeconnectedtriangles)
- [GetEdgeVertex](ue_ue.MeshDescriptionBase.md#getedgevertex)
- [GetEdgeVertices](ue_ue.MeshDescriptionBase.md#getedgevertices)
- [GetName](ue_ue.MeshDescriptionBase.md#getname)
- [GetNumEdgeConnectedPolygons](ue_ue.MeshDescriptionBase.md#getnumedgeconnectedpolygons)
- [GetNumEdgeConnectedTriangles](ue_ue.MeshDescriptionBase.md#getnumedgeconnectedtriangles)
- [GetNumPolygonGroupPolygons](ue_ue.MeshDescriptionBase.md#getnumpolygongrouppolygons)
- [GetNumPolygonInternalEdges](ue_ue.MeshDescriptionBase.md#getnumpolygoninternaledges)
- [GetNumPolygonTriangles](ue_ue.MeshDescriptionBase.md#getnumpolygontriangles)
- [GetNumPolygonVertices](ue_ue.MeshDescriptionBase.md#getnumpolygonvertices)
- [GetNumVertexConnectedEdges](ue_ue.MeshDescriptionBase.md#getnumvertexconnectededges)
- [GetNumVertexConnectedPolygons](ue_ue.MeshDescriptionBase.md#getnumvertexconnectedpolygons)
- [GetNumVertexConnectedTriangles](ue_ue.MeshDescriptionBase.md#getnumvertexconnectedtriangles)
- [GetNumVertexInstanceConnectedPolygons](ue_ue.MeshDescriptionBase.md#getnumvertexinstanceconnectedpolygons)
- [GetNumVertexInstanceConnectedTriangles](ue_ue.MeshDescriptionBase.md#getnumvertexinstanceconnectedtriangles)
- [GetNumVertexVertexInstances](ue_ue.MeshDescriptionBase.md#getnumvertexvertexinstances)
- [GetOuter](ue_ue.MeshDescriptionBase.md#getouter)
- [GetPolygonAdjacentPolygons](ue_ue.MeshDescriptionBase.md#getpolygonadjacentpolygons)
- [GetPolygonGroupPolygons](ue_ue.MeshDescriptionBase.md#getpolygongrouppolygons)
- [GetPolygonInternalEdges](ue_ue.MeshDescriptionBase.md#getpolygoninternaledges)
- [GetPolygonPerimeterEdges](ue_ue.MeshDescriptionBase.md#getpolygonperimeteredges)
- [GetPolygonPolygonGroup](ue_ue.MeshDescriptionBase.md#getpolygonpolygongroup)
- [GetPolygonTriangles](ue_ue.MeshDescriptionBase.md#getpolygontriangles)
- [GetPolygonVertexInstances](ue_ue.MeshDescriptionBase.md#getpolygonvertexinstances)
- [GetPolygonVertices](ue_ue.MeshDescriptionBase.md#getpolygonvertices)
- [GetTriangleAdjacentTriangles](ue_ue.MeshDescriptionBase.md#gettriangleadjacenttriangles)
- [GetTriangleEdges](ue_ue.MeshDescriptionBase.md#gettriangleedges)
- [GetTrianglePolygon](ue_ue.MeshDescriptionBase.md#gettrianglepolygon)
- [GetTrianglePolygonGroup](ue_ue.MeshDescriptionBase.md#gettrianglepolygongroup)
- [GetTriangleVertexInstance](ue_ue.MeshDescriptionBase.md#gettrianglevertexinstance)
- [GetTriangleVertexInstances](ue_ue.MeshDescriptionBase.md#gettrianglevertexinstances)
- [GetTriangleVertices](ue_ue.MeshDescriptionBase.md#gettrianglevertices)
- [GetVertexAdjacentVertices](ue_ue.MeshDescriptionBase.md#getvertexadjacentvertices)
- [GetVertexConnectedEdges](ue_ue.MeshDescriptionBase.md#getvertexconnectededges)
- [GetVertexConnectedPolygons](ue_ue.MeshDescriptionBase.md#getvertexconnectedpolygons)
- [GetVertexConnectedTriangles](ue_ue.MeshDescriptionBase.md#getvertexconnectedtriangles)
- [GetVertexInstanceConnectedPolygons](ue_ue.MeshDescriptionBase.md#getvertexinstanceconnectedpolygons)
- [GetVertexInstanceConnectedTriangles](ue_ue.MeshDescriptionBase.md#getvertexinstanceconnectedtriangles)
- [GetVertexInstanceForPolygonVertex](ue_ue.MeshDescriptionBase.md#getvertexinstanceforpolygonvertex)
- [GetVertexInstanceForTriangleVertex](ue_ue.MeshDescriptionBase.md#getvertexinstancefortrianglevertex)
- [GetVertexInstancePairEdge](ue_ue.MeshDescriptionBase.md#getvertexinstancepairedge)
- [GetVertexInstanceVertex](ue_ue.MeshDescriptionBase.md#getvertexinstancevertex)
- [GetVertexPairEdge](ue_ue.MeshDescriptionBase.md#getvertexpairedge)
- [GetVertexPosition](ue_ue.MeshDescriptionBase.md#getvertexposition)
- [GetVertexVertexInstances](ue_ue.MeshDescriptionBase.md#getvertexvertexinstances)
- [GetWorld](ue_ue.MeshDescriptionBase.md#getworld)
- [IsEdgeInternal](ue_ue.MeshDescriptionBase.md#isedgeinternal)
- [IsEdgeInternalToPolygon](ue_ue.MeshDescriptionBase.md#isedgeinternaltopolygon)
- [IsEdgeValid](ue_ue.MeshDescriptionBase.md#isedgevalid)
- [IsEmpty](ue_ue.MeshDescriptionBase.md#isempty)
- [IsPolygonGroupValid](ue_ue.MeshDescriptionBase.md#ispolygongroupvalid)
- [IsPolygonValid](ue_ue.MeshDescriptionBase.md#ispolygonvalid)
- [IsTrianglePartOfNgon](ue_ue.MeshDescriptionBase.md#istrianglepartofngon)
- [IsTriangleValid](ue_ue.MeshDescriptionBase.md#istrianglevalid)
- [IsVertexInstanceValid](ue_ue.MeshDescriptionBase.md#isvertexinstancevalid)
- [IsVertexOrphaned](ue_ue.MeshDescriptionBase.md#isvertexorphaned)
- [IsVertexValid](ue_ue.MeshDescriptionBase.md#isvertexvalid)
- [ReserveNewEdges](ue_ue.MeshDescriptionBase.md#reservenewedges)
- [ReserveNewPolygonGroups](ue_ue.MeshDescriptionBase.md#reservenewpolygongroups)
- [ReserveNewPolygons](ue_ue.MeshDescriptionBase.md#reservenewpolygons)
- [ReserveNewTriangles](ue_ue.MeshDescriptionBase.md#reservenewtriangles)
- [ReserveNewVertexInstances](ue_ue.MeshDescriptionBase.md#reservenewvertexinstances)
- [ReserveNewVertices](ue_ue.MeshDescriptionBase.md#reservenewvertices)
- [ReversePolygonFacing](ue_ue.MeshDescriptionBase.md#reversepolygonfacing)
- [SetPolygonPolygonGroup](ue_ue.MeshDescriptionBase.md#setpolygonpolygongroup)
- [SetPolygonVertexInstance](ue_ue.MeshDescriptionBase.md#setpolygonvertexinstance)
- [SetVertexPosition](ue_ue.MeshDescriptionBase.md#setvertexposition)
- [Find](ue_ue.MeshDescriptionBase.md#find)
- [Load](ue_ue.MeshDescriptionBase.md#load)
- [StaticClass](ue_ue.MeshDescriptionBase.md#staticclass)

## Constructors

### constructor

• **new MeshDescriptionBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_MeshDescriptionBase\_\_

• **\_\_tid\_MeshDescriptionBase\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

## Methods

### ComputePolygonTriangulation

▸ **ComputePolygonTriangulation**(`PolygonID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

___

### CreatePolygonGroup

▸ **CreatePolygonGroup**(): [`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Returns

[`PolygonGroupID`](ue_ue.PolygonGroupID.md)

___

### CreatePolygonGroupWithID

▸ **CreatePolygonGroupWithID**(`PolygonGroupID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |

#### Returns

`void`

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

___

### CreateVertex

▸ **CreateVertex**(): [`VertexID`](ue_ue.VertexID.md)

#### Returns

[`VertexID`](ue_ue.VertexID.md)

___

### CreateVertexInstance

▸ **CreateVertexInstance**(`VertexID`): [`VertexInstanceID`](ue_ue.VertexInstanceID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

[`VertexInstanceID`](ue_ue.VertexInstanceID.md)

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

___

### CreateVertexWithID

▸ **CreateVertexWithID**(`VertexID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`void`

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

___

### DeletePolygonGroup

▸ **DeletePolygonGroup**(`PolygonGroupID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |

#### Returns

`void`

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

___

### DeleteVertex

▸ **DeleteVertex**(`VertexID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`void`

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

___

### Empty

▸ **Empty**(): `void`

#### Returns

`void`

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

### GetEdgeConnectedPolygons

▸ **GetEdgeConnectedPolygons**(`EdgeID`, `OutConnectedPolygonIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `OutConnectedPolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

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

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetNumEdgeConnectedPolygons

▸ **GetNumEdgeConnectedPolygons**(`EdgeID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |

#### Returns

`number`

___

### GetNumEdgeConnectedTriangles

▸ **GetNumEdgeConnectedTriangles**(`EdgeID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |

#### Returns

`number`

___

### GetNumPolygonGroupPolygons

▸ **GetNumPolygonGroupPolygons**(`PolygonGroupID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |

#### Returns

`number`

___

### GetNumPolygonInternalEdges

▸ **GetNumPolygonInternalEdges**(`PolygonID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`number`

___

### GetNumPolygonTriangles

▸ **GetNumPolygonTriangles**(`PolygonID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`number`

___

### GetNumPolygonVertices

▸ **GetNumPolygonVertices**(`PolygonID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`number`

___

### GetNumVertexConnectedEdges

▸ **GetNumVertexConnectedEdges**(`VertexID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`number`

___

### GetNumVertexConnectedPolygons

▸ **GetNumVertexConnectedPolygons**(`VertexID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`number`

___

### GetNumVertexConnectedTriangles

▸ **GetNumVertexConnectedTriangles**(`VertexID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`number`

___

### GetNumVertexInstanceConnectedPolygons

▸ **GetNumVertexInstanceConnectedPolygons**(`VertexInstanceID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |

#### Returns

`number`

___

### GetNumVertexInstanceConnectedTriangles

▸ **GetNumVertexInstanceConnectedTriangles**(`VertexInstanceID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |

#### Returns

`number`

___

### GetNumVertexVertexInstances

▸ **GetNumVertexVertexInstances**(`VertexID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`number`

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

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

___

### GetPolygonPolygonGroup

▸ **GetPolygonPolygonGroup**(`PolygonID`): [`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

[`PolygonGroupID`](ue_ue.PolygonGroupID.md)

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

___

### GetTrianglePolygon

▸ **GetTrianglePolygon**(`TriangleID`): [`PolygonID`](ue_ue.PolygonID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |

#### Returns

[`PolygonID`](ue_ue.PolygonID.md)

___

### GetTrianglePolygonGroup

▸ **GetTrianglePolygonGroup**(`TriangleID`): [`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |

#### Returns

[`PolygonGroupID`](ue_ue.PolygonGroupID.md)

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

___

### GetVertexInstanceVertex

▸ **GetVertexInstanceVertex**(`VertexInstanceID`): [`VertexID`](ue_ue.VertexID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |

#### Returns

[`VertexID`](ue_ue.VertexID.md)

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

___

### GetVertexPosition

▸ **GetVertexPosition**(`VertexID`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### IsEdgeInternal

▸ **IsEdgeInternal**(`EdgeID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |

#### Returns

`boolean`

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

___

### IsEdgeValid

▸ **IsEdgeValid**(`EdgeID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |

#### Returns

`boolean`

___

### IsEmpty

▸ **IsEmpty**(): `boolean`

#### Returns

`boolean`

___

### IsPolygonGroupValid

▸ **IsPolygonGroupValid**(`PolygonGroupID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |

#### Returns

`boolean`

___

### IsPolygonValid

▸ **IsPolygonValid**(`PolygonID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`boolean`

___

### IsTrianglePartOfNgon

▸ **IsTrianglePartOfNgon**(`TriangleID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |

#### Returns

`boolean`

___

### IsTriangleValid

▸ **IsTriangleValid**(`TriangleID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TriangleID` | [`TriangleID`](ue_ue.TriangleID.md) |

#### Returns

`boolean`

___

### IsVertexInstanceValid

▸ **IsVertexInstanceValid**(`VertexInstanceID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |

#### Returns

`boolean`

___

### IsVertexOrphaned

▸ **IsVertexOrphaned**(`VertexID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`boolean`

___

### IsVertexValid

▸ **IsVertexValid**(`VertexID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`boolean`

___

### ReserveNewEdges

▸ **ReserveNewEdges**(`NumberOfNewEdges`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumberOfNewEdges` | `number` |

#### Returns

`void`

___

### ReserveNewPolygonGroups

▸ **ReserveNewPolygonGroups**(`NumberOfNewPolygonGroups`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumberOfNewPolygonGroups` | `number` |

#### Returns

`void`

___

### ReserveNewPolygons

▸ **ReserveNewPolygons**(`NumberOfNewPolygons`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumberOfNewPolygons` | `number` |

#### Returns

`void`

___

### ReserveNewTriangles

▸ **ReserveNewTriangles**(`NumberOfNewTriangles`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumberOfNewTriangles` | `number` |

#### Returns

`void`

___

### ReserveNewVertexInstances

▸ **ReserveNewVertexInstances**(`NumberOfNewVertexInstances`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumberOfNewVertexInstances` | `number` |

#### Returns

`void`

___

### ReserveNewVertices

▸ **ReserveNewVertices**(`NumberOfNewVertices`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumberOfNewVertices` | `number` |

#### Returns

`void`

___

### ReversePolygonFacing

▸ **ReversePolygonFacing**(`PolygonID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

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

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MeshDescriptionBase`](ue_ue.MeshDescriptionBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MeshDescriptionBase`](ue_ue.MeshDescriptionBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MeshDescriptionBase`](ue_ue.MeshDescriptionBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MeshDescriptionBase`](ue_ue.MeshDescriptionBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
