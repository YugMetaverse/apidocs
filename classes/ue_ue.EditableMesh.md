[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditableMesh

# Class: EditableMesh

[ue/ue](../modules/ue_ue.md).EditableMesh

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EditableMesh`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditableMesh.md#constructor)

### Properties

- [Adapters](ue_ue.EditableMesh.md#adapters)
- [PendingCompactCounter](ue_ue.EditableMesh.md#pendingcompactcounter)
- [SubdivisionCount](ue_ue.EditableMesh.md#subdivisioncount)
- [TextureCoordinateCount](ue_ue.EditableMesh.md#texturecoordinatecount)
- [\_\_tid\_EditableMesh\_\_](ue_ue.EditableMesh.md#__tid_editablemesh__)
- [\_\_tid\_Object\_\_](ue_ue.EditableMesh.md#__tid_object__)

### Methods

- [AnyChangesToUndo](ue_ue.EditableMesh.md#anychangestoundo)
- [AssignPolygonsToPolygonGroups](ue_ue.EditableMesh.md#assignpolygonstopolygongroups)
- [BevelPolygons](ue_ue.EditableMesh.md#bevelpolygons)
- [ChangePolygonsVertexInstances](ue_ue.EditableMesh.md#changepolygonsvertexinstances)
- [Commit](ue_ue.EditableMesh.md#commit)
- [CommitInstance](ue_ue.EditableMesh.md#commitinstance)
- [ComputeBoundingBox](ue_ue.EditableMesh.md#computeboundingbox)
- [ComputeBoundingBoxAndSphere](ue_ue.EditableMesh.md#computeboundingboxandsphere)
- [ComputePolygonCenter](ue_ue.EditableMesh.md#computepolygoncenter)
- [ComputePolygonNormal](ue_ue.EditableMesh.md#computepolygonnormal)
- [ComputePolygonPlane](ue_ue.EditableMesh.md#computepolygonplane)
- [ComputePolygonsSharedEdges](ue_ue.EditableMesh.md#computepolygonssharededges)
- [CreateDefaultSubobject](ue_ue.EditableMesh.md#createdefaultsubobject)
- [CreateEdges](ue_ue.EditableMesh.md#createedges)
- [CreateEmptyVertexRange](ue_ue.EditableMesh.md#createemptyvertexrange)
- [CreateMissingPolygonPerimeterEdges](ue_ue.EditableMesh.md#createmissingpolygonperimeteredges)
- [CreatePolygonGroups](ue_ue.EditableMesh.md#createpolygongroups)
- [CreatePolygons](ue_ue.EditableMesh.md#createpolygons)
- [CreateVertexInstances](ue_ue.EditableMesh.md#createvertexinstances)
- [CreateVertices](ue_ue.EditableMesh.md#createvertices)
- [DeleteEdgeAndConnectedPolygons](ue_ue.EditableMesh.md#deleteedgeandconnectedpolygons)
- [DeleteEdges](ue_ue.EditableMesh.md#deleteedges)
- [DeleteOrphanVertices](ue_ue.EditableMesh.md#deleteorphanvertices)
- [DeletePolygonGroups](ue_ue.EditableMesh.md#deletepolygongroups)
- [DeletePolygons](ue_ue.EditableMesh.md#deletepolygons)
- [DeleteVertexAndConnectedEdgesAndPolygons](ue_ue.EditableMesh.md#deletevertexandconnectededgesandpolygons)
- [DeleteVertexInstances](ue_ue.EditableMesh.md#deletevertexinstances)
- [EndModification](ue_ue.EditableMesh.md#endmodification)
- [ExecuteUbergraph](ue_ue.EditableMesh.md#executeubergraph)
- [ExtendEdges](ue_ue.EditableMesh.md#extendedges)
- [ExtendVertices](ue_ue.EditableMesh.md#extendvertices)
- [ExtrudePolygons](ue_ue.EditableMesh.md#extrudepolygons)
- [FindPolygonLoop](ue_ue.EditableMesh.md#findpolygonloop)
- [FindPolygonPerimeterEdgeNumberForVertices](ue_ue.EditableMesh.md#findpolygonperimeteredgenumberforvertices)
- [FindPolygonPerimeterVertexNumberForVertex](ue_ue.EditableMesh.md#findpolygonperimetervertexnumberforvertex)
- [FlipPolygons](ue_ue.EditableMesh.md#flippolygons)
- [GeneratePolygonTangentsAndNormals](ue_ue.EditableMesh.md#generatepolygontangentsandnormals)
- [GetClass](ue_ue.EditableMesh.md#getclass)
- [GetEdgeConnectedPolygon](ue_ue.EditableMesh.md#getedgeconnectedpolygon)
- [GetEdgeConnectedPolygonCount](ue_ue.EditableMesh.md#getedgeconnectedpolygoncount)
- [GetEdgeConnectedPolygons](ue_ue.EditableMesh.md#getedgeconnectedpolygons)
- [GetEdgeCount](ue_ue.EditableMesh.md#getedgecount)
- [GetEdgeLoopElements](ue_ue.EditableMesh.md#getedgeloopelements)
- [GetEdgeThatConnectsVertices](ue_ue.EditableMesh.md#getedgethatconnectsvertices)
- [GetEdgeVertex](ue_ue.EditableMesh.md#getedgevertex)
- [GetEdgeVertices](ue_ue.EditableMesh.md#getedgevertices)
- [GetFirstValidPolygonGroup](ue_ue.EditableMesh.md#getfirstvalidpolygongroup)
- [GetGroupForPolygon](ue_ue.EditableMesh.md#getgroupforpolygon)
- [GetName](ue_ue.EditableMesh.md#getname)
- [GetOuter](ue_ue.EditableMesh.md#getouter)
- [GetPolygonAdjacentPolygons](ue_ue.EditableMesh.md#getpolygonadjacentpolygons)
- [GetPolygonCount](ue_ue.EditableMesh.md#getpolygoncount)
- [GetPolygonCountInGroup](ue_ue.EditableMesh.md#getpolygoncountingroup)
- [GetPolygonGroupCount](ue_ue.EditableMesh.md#getpolygongroupcount)
- [GetPolygonInGroup](ue_ue.EditableMesh.md#getpolygoningroup)
- [GetPolygonPerimeterEdge](ue_ue.EditableMesh.md#getpolygonperimeteredge)
- [GetPolygonPerimeterEdgeCount](ue_ue.EditableMesh.md#getpolygonperimeteredgecount)
- [GetPolygonPerimeterEdges](ue_ue.EditableMesh.md#getpolygonperimeteredges)
- [GetPolygonPerimeterVertex](ue_ue.EditableMesh.md#getpolygonperimetervertex)
- [GetPolygonPerimeterVertexCount](ue_ue.EditableMesh.md#getpolygonperimetervertexcount)
- [GetPolygonPerimeterVertexInstance](ue_ue.EditableMesh.md#getpolygonperimetervertexinstance)
- [GetPolygonPerimeterVertexInstances](ue_ue.EditableMesh.md#getpolygonperimetervertexinstances)
- [GetPolygonPerimeterVertices](ue_ue.EditableMesh.md#getpolygonperimetervertices)
- [GetPolygonTriangulatedTriangle](ue_ue.EditableMesh.md#getpolygontriangulatedtriangle)
- [GetPolygonTriangulatedTriangleCount](ue_ue.EditableMesh.md#getpolygontriangulatedtrianglecount)
- [GetSubdivisionCount](ue_ue.EditableMesh.md#getsubdivisioncount)
- [GetSubdivisionLimitData](ue_ue.EditableMesh.md#getsubdivisionlimitdata)
- [GetTextureCoordinateCount](ue_ue.EditableMesh.md#gettexturecoordinatecount)
- [GetVertexAdjacentVertices](ue_ue.EditableMesh.md#getvertexadjacentvertices)
- [GetVertexConnectedEdge](ue_ue.EditableMesh.md#getvertexconnectededge)
- [GetVertexConnectedEdgeCount](ue_ue.EditableMesh.md#getvertexconnectededgecount)
- [GetVertexConnectedEdges](ue_ue.EditableMesh.md#getvertexconnectededges)
- [GetVertexConnectedPolygons](ue_ue.EditableMesh.md#getvertexconnectedpolygons)
- [GetVertexCount](ue_ue.EditableMesh.md#getvertexcount)
- [GetVertexInstanceConnectedPolygon](ue_ue.EditableMesh.md#getvertexinstanceconnectedpolygon)
- [GetVertexInstanceConnectedPolygonCount](ue_ue.EditableMesh.md#getvertexinstanceconnectedpolygoncount)
- [GetVertexInstanceConnectedPolygons](ue_ue.EditableMesh.md#getvertexinstanceconnectedpolygons)
- [GetVertexInstanceCount](ue_ue.EditableMesh.md#getvertexinstancecount)
- [GetVertexInstanceVertex](ue_ue.EditableMesh.md#getvertexinstancevertex)
- [GetVertexPairEdge](ue_ue.EditableMesh.md#getvertexpairedge)
- [GetWorld](ue_ue.EditableMesh.md#getworld)
- [InitializeAdapters](ue_ue.EditableMesh.md#initializeadapters)
- [InsertEdgeLoop](ue_ue.EditableMesh.md#insertedgeloop)
- [InsetPolygons](ue_ue.EditableMesh.md#insetpolygons)
- [IsBeingModified](ue_ue.EditableMesh.md#isbeingmodified)
- [IsCommitted](ue_ue.EditableMesh.md#iscommitted)
- [IsCommittedAsInstance](ue_ue.EditableMesh.md#iscommittedasinstance)
- [IsCompactAllowed](ue_ue.EditableMesh.md#iscompactallowed)
- [IsOrphanedVertex](ue_ue.EditableMesh.md#isorphanedvertex)
- [IsPreviewingSubdivisions](ue_ue.EditableMesh.md#ispreviewingsubdivisions)
- [IsSpatialDatabaseAllowed](ue_ue.EditableMesh.md#isspatialdatabaseallowed)
- [IsUndoAllowed](ue_ue.EditableMesh.md#isundoallowed)
- [IsValidEdge](ue_ue.EditableMesh.md#isvalidedge)
- [IsValidPolygon](ue_ue.EditableMesh.md#isvalidpolygon)
- [IsValidPolygonGroup](ue_ue.EditableMesh.md#isvalidpolygongroup)
- [IsValidVertex](ue_ue.EditableMesh.md#isvalidvertex)
- [MoveVertices](ue_ue.EditableMesh.md#movevertices)
- [PropagateInstanceChanges](ue_ue.EditableMesh.md#propagateinstancechanges)
- [QuadrangulateMesh](ue_ue.EditableMesh.md#quadrangulatemesh)
- [RebuildRenderMesh](ue_ue.EditableMesh.md#rebuildrendermesh)
- [Revert](ue_ue.EditableMesh.md#revert)
- [RevertInstance](ue_ue.EditableMesh.md#revertinstance)
- [SearchSpatialDatabaseForPolygonsInVolume](ue_ue.EditableMesh.md#searchspatialdatabaseforpolygonsinvolume)
- [SearchSpatialDatabaseForPolygonsPotentiallyIntersectingLineSegment](ue_ue.EditableMesh.md#searchspatialdatabaseforpolygonspotentiallyintersectinglinesegment)
- [SearchSpatialDatabaseForPolygonsPotentiallyIntersectingPlane](ue_ue.EditableMesh.md#searchspatialdatabaseforpolygonspotentiallyintersectingplane)
- [SetAllowCompact](ue_ue.EditableMesh.md#setallowcompact)
- [SetAllowSpatialDatabase](ue_ue.EditableMesh.md#setallowspatialdatabase)
- [SetAllowUndo](ue_ue.EditableMesh.md#setallowundo)
- [SetEdgesAttributes](ue_ue.EditableMesh.md#setedgesattributes)
- [SetEdgesCreaseSharpness](ue_ue.EditableMesh.md#setedgescreasesharpness)
- [SetEdgesHardness](ue_ue.EditableMesh.md#setedgeshardness)
- [SetEdgesHardnessAutomatically](ue_ue.EditableMesh.md#setedgeshardnessautomatically)
- [SetPolygonsVertexAttributes](ue_ue.EditableMesh.md#setpolygonsvertexattributes)
- [SetSubdivisionCount](ue_ue.EditableMesh.md#setsubdivisioncount)
- [SetTextureCoordinateCount](ue_ue.EditableMesh.md#settexturecoordinatecount)
- [SetVertexInstancesAttributes](ue_ue.EditableMesh.md#setvertexinstancesattributes)
- [SetVerticesAttributes](ue_ue.EditableMesh.md#setverticesattributes)
- [SetVerticesCornerSharpness](ue_ue.EditableMesh.md#setverticescornersharpness)
- [SplitEdge](ue_ue.EditableMesh.md#splitedge)
- [SplitPolygonalMesh](ue_ue.EditableMesh.md#splitpolygonalmesh)
- [SplitPolygons](ue_ue.EditableMesh.md#splitpolygons)
- [StartModification](ue_ue.EditableMesh.md#startmodification)
- [TessellatePolygons](ue_ue.EditableMesh.md#tessellatepolygons)
- [TriangulatePolygons](ue_ue.EditableMesh.md#triangulatepolygons)
- [TryToRemovePolygonEdge](ue_ue.EditableMesh.md#trytoremovepolygonedge)
- [TryToRemoveVertex](ue_ue.EditableMesh.md#trytoremovevertex)
- [WeldVertices](ue_ue.EditableMesh.md#weldvertices)
- [Find](ue_ue.EditableMesh.md#find)
- [InvalidEdgeID](ue_ue.EditableMesh.md#invalidedgeid)
- [InvalidPolygonGroupID](ue_ue.EditableMesh.md#invalidpolygongroupid)
- [InvalidPolygonID](ue_ue.EditableMesh.md#invalidpolygonid)
- [InvalidVertexID](ue_ue.EditableMesh.md#invalidvertexid)
- [Load](ue_ue.EditableMesh.md#load)
- [MakeEdgeID](ue_ue.EditableMesh.md#makeedgeid)
- [MakePolygonGroupID](ue_ue.EditableMesh.md#makepolygongroupid)
- [MakePolygonID](ue_ue.EditableMesh.md#makepolygonid)
- [MakeVertexID](ue_ue.EditableMesh.md#makevertexid)
- [StaticClass](ue_ue.EditableMesh.md#staticclass)

## Constructors

### constructor

• **new EditableMesh**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:31958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31958)

## Properties

### Adapters

• **Adapters**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditableMeshAdapter`](ue_ue.EditableMeshAdapter.md)\>

#### Defined in

[ue/ue.d.ts:31959](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31959)

___

### PendingCompactCounter

• **PendingCompactCounter**: `number`

#### Defined in

[ue/ue.d.ts:31961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31961)

___

### SubdivisionCount

• **SubdivisionCount**: `number`

#### Defined in

[ue/ue.d.ts:31962](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31962)

___

### TextureCoordinateCount

• **TextureCoordinateCount**: `number`

#### Defined in

[ue/ue.d.ts:31960](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31960)

___

### \_\_tid\_EditableMesh\_\_

• **\_\_tid\_EditableMesh\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:32096](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32096)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

## Methods

### AnyChangesToUndo

▸ **AnyChangesToUndo**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:31963](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31963)

___

### AssignPolygonsToPolygonGroups

▸ **AssignPolygonsToPolygonGroups**(`PolygonGroupForPolygons`, `bDeleteOrphanedPolygonGroups`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupForPolygons` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonGroupForPolygon`](ue_ue.PolygonGroupForPolygon.md)\> |
| `bDeleteOrphanedPolygonGroups` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31964)

___

### BevelPolygons

▸ **BevelPolygons**(`PolygonIDs`, `BevelFixedDistance`, `BevelProgressTowardCenter`, `OutNewCenterPolygonIDs`, `OutNewSidePolygonIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |
| `BevelFixedDistance` | `number` |
| `BevelProgressTowardCenter` | `number` |
| `OutNewCenterPolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |
| `OutNewSidePolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31965)

___

### ChangePolygonsVertexInstances

▸ **ChangePolygonsVertexInstances**(`VertexInstancesForPolygons`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstancesForPolygons` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChangeVertexInstancesForPolygon`](ue_ue.ChangeVertexInstancesForPolygon.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31966)

___

### Commit

▸ **Commit**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31967)

___

### CommitInstance

▸ **CommitInstance**(`ComponentToInstanceTo`): [`EditableMesh`](ue_ue.EditableMesh.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentToInstanceTo` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |

#### Returns

[`EditableMesh`](ue_ue.EditableMesh.md)

#### Defined in

[ue/ue.d.ts:31968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31968)

___

### ComputeBoundingBox

▸ **ComputeBoundingBox**(): [`Box`](ue_ue.Box.md)

#### Returns

[`Box`](ue_ue.Box.md)

#### Defined in

[ue/ue.d.ts:31969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31969)

___

### ComputeBoundingBoxAndSphere

▸ **ComputeBoundingBoxAndSphere**(): [`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Returns

[`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Defined in

[ue/ue.d.ts:31970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31970)

___

### ComputePolygonCenter

▸ **ComputePolygonCenter**(`PolygonID`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:31971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31971)

___

### ComputePolygonNormal

▸ **ComputePolygonNormal**(`PolygonID`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:31972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31972)

___

### ComputePolygonPlane

▸ **ComputePolygonPlane**(`PolygonID`): [`Plane`](ue_ue.Plane.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

[`Plane`](ue_ue.Plane.md)

#### Defined in

[ue/ue.d.ts:31973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31973)

___

### ComputePolygonsSharedEdges

▸ **ComputePolygonsSharedEdges**(`PolygonIDs`, `OutSharedEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |
| `OutSharedEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31974)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### CreateEdges

▸ **CreateEdges**(`EdgesToCreate`, `OutNewEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgesToCreate` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeToCreate`](ue_ue.EdgeToCreate.md)\> |
| `OutNewEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31975](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31975)

___

### CreateEmptyVertexRange

▸ **CreateEmptyVertexRange**(`NumVerticesToCreate`, `OutNewVertexIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumVerticesToCreate` | `number` |
| `OutNewVertexIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31976](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31976)

___

### CreateMissingPolygonPerimeterEdges

▸ **CreateMissingPolygonPerimeterEdges**(`PolygonID`, `OutNewEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `OutNewEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31977](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31977)

___

### CreatePolygonGroups

▸ **CreatePolygonGroups**(`PolygonGroupsToCreate`, `OutNewPolygonGroupIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupsToCreate` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonGroupToCreate`](ue_ue.PolygonGroupToCreate.md)\> |
| `OutNewPolygonGroupIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonGroupID`](ue_ue.PolygonGroupID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31978](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31978)

___

### CreatePolygons

▸ **CreatePolygons**(`PolygonsToCreate`, `OutNewPolygonIDs`, `OutNewEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonsToCreate` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonToCreate`](ue_ue.PolygonToCreate.md)\> |
| `OutNewPolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |
| `OutNewEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31979](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31979)

___

### CreateVertexInstances

▸ **CreateVertexInstances**(`VertexInstancesToCreate`, `OutNewVertexInstanceIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstancesToCreate` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstanceToCreate`](ue_ue.VertexInstanceToCreate.md)\> |
| `OutNewVertexInstanceIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstanceID`](ue_ue.VertexInstanceID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31980](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31980)

___

### CreateVertices

▸ **CreateVertices**(`VerticesToCreate`, `OutNewVertexIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VerticesToCreate` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexToCreate`](ue_ue.VertexToCreate.md)\> |
| `OutNewVertexIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31981](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31981)

___

### DeleteEdgeAndConnectedPolygons

▸ **DeleteEdgeAndConnectedPolygons**(`EdgeID`, `bDeleteOrphanedEdges`, `bDeleteOrphanedVertices`, `bDeleteOrphanedVertexInstances`, `bDeleteEmptyPolygonGroups`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `bDeleteOrphanedEdges` | `boolean` |
| `bDeleteOrphanedVertices` | `boolean` |
| `bDeleteOrphanedVertexInstances` | `boolean` |
| `bDeleteEmptyPolygonGroups` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31982](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31982)

___

### DeleteEdges

▸ **DeleteEdges**(`EdgeIDsToDelete`, `bDeleteOrphanedVertices`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeIDsToDelete` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\> |
| `bDeleteOrphanedVertices` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31983](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31983)

___

### DeleteOrphanVertices

▸ **DeleteOrphanVertices**(`VertexIDsToDelete`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexIDsToDelete` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31984](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31984)

___

### DeletePolygonGroups

▸ **DeletePolygonGroups**(`PolygonGroupIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonGroupID`](ue_ue.PolygonGroupID.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31985](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31985)

___

### DeletePolygons

▸ **DeletePolygons**(`PolygonIDsToDelete`, `bDeleteOrphanedEdges`, `bDeleteOrphanedVertices`, `bDeleteOrphanedVertexInstances`, `bDeleteEmptyPolygonGroups`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonIDsToDelete` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |
| `bDeleteOrphanedEdges` | `boolean` |
| `bDeleteOrphanedVertices` | `boolean` |
| `bDeleteOrphanedVertexInstances` | `boolean` |
| `bDeleteEmptyPolygonGroups` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31986](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31986)

___

### DeleteVertexAndConnectedEdgesAndPolygons

▸ **DeleteVertexAndConnectedEdgesAndPolygons**(`VertexID`, `bDeleteOrphanedEdges`, `bDeleteOrphanedVertices`, `bDeleteOrphanedVertexInstances`, `bDeleteEmptyPolygonGroups`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |
| `bDeleteOrphanedEdges` | `boolean` |
| `bDeleteOrphanedVertices` | `boolean` |
| `bDeleteOrphanedVertexInstances` | `boolean` |
| `bDeleteEmptyPolygonGroups` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31987](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31987)

___

### DeleteVertexInstances

▸ **DeleteVertexInstances**(`VertexInstanceIDsToDelete`, `bDeleteOrphanedVertices`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceIDsToDelete` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstanceID`](ue_ue.VertexInstanceID.md)\> |
| `bDeleteOrphanedVertices` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31988](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31988)

___

### EndModification

▸ **EndModification**(`bFromUndo?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bFromUndo?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31989](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31989)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### ExtendEdges

▸ **ExtendEdges**(`EdgeIDs`, `bWeldNeighbors`, `OutNewExtendedEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\> |
| `bWeldNeighbors` | `boolean` |
| `OutNewExtendedEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31990](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31990)

___

### ExtendVertices

▸ **ExtendVertices**(`VertexIDs`, `bOnlyExtendClosestEdge`, `ReferencePosition`, `OutNewExtendedVertexIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\> |
| `bOnlyExtendClosestEdge` | `boolean` |
| `ReferencePosition` | [`Vector`](ue_ue_s.Vector.md) |
| `OutNewExtendedVertexIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31991](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31991)

___

### ExtrudePolygons

▸ **ExtrudePolygons**(`Polygons`, `ExtrudeDistance`, `bKeepNeighborsTogether`, `OutNewExtrudedFrontPolygons`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Polygons` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |
| `ExtrudeDistance` | `number` |
| `bKeepNeighborsTogether` | `boolean` |
| `OutNewExtrudedFrontPolygons` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31992](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31992)

___

### FindPolygonLoop

▸ **FindPolygonLoop**(`EdgeID`, `OutEdgeLoopEdgeIDs`, `OutFlippedEdgeIDs`, `OutReversedEdgeIDPathToTake`, `OutPolygonIDsToSplit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `OutEdgeLoopEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |
| `OutFlippedEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |
| `OutReversedEdgeIDPathToTake` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |
| `OutPolygonIDsToSplit` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31993](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31993)

___

### FindPolygonPerimeterEdgeNumberForVertices

▸ **FindPolygonPerimeterEdgeNumberForVertices**(`PolygonID`, `EdgeVertexID0`, `EdgeVertexID1`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `EdgeVertexID0` | [`VertexID`](ue_ue.VertexID.md) |
| `EdgeVertexID1` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:31994](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31994)

___

### FindPolygonPerimeterVertexNumberForVertex

▸ **FindPolygonPerimeterVertexNumberForVertex**(`PolygonID`, `VertexID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:31995](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31995)

___

### FlipPolygons

▸ **FlipPolygons**(`PolygonIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31996](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31996)

___

### GeneratePolygonTangentsAndNormals

▸ **GeneratePolygonTangentsAndNormals**(`PolygonIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:31997](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31997)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetEdgeConnectedPolygon

▸ **GetEdgeConnectedPolygon**(`EdgeID`, `ConnectedPolygonNumber`): [`PolygonID`](ue_ue.PolygonID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `ConnectedPolygonNumber` | `number` |

#### Returns

[`PolygonID`](ue_ue.PolygonID.md)

#### Defined in

[ue/ue.d.ts:31998](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31998)

___

### GetEdgeConnectedPolygonCount

▸ **GetEdgeConnectedPolygonCount**(`EdgeID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:31999](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L31999)

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

#### Defined in

[ue/ue.d.ts:32000](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32000)

___

### GetEdgeCount

▸ **GetEdgeCount**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32001)

___

### GetEdgeLoopElements

▸ **GetEdgeLoopElements**(`EdgeID`, `EdgeLoopIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `EdgeLoopIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32002](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32002)

___

### GetEdgeThatConnectsVertices

▸ **GetEdgeThatConnectsVertices**(`VertexID0`, `VertexID1`): [`EdgeID`](ue_ue.EdgeID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID0` | [`VertexID`](ue_ue.VertexID.md) |
| `VertexID1` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

[`EdgeID`](ue_ue.EdgeID.md)

#### Defined in

[ue/ue.d.ts:32003](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32003)

___

### GetEdgeVertex

▸ **GetEdgeVertex**(`EdgeID`, `EdgeVertexNumber`): [`VertexID`](ue_ue.VertexID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `EdgeVertexNumber` | `number` |

#### Returns

[`VertexID`](ue_ue.VertexID.md)

#### Defined in

[ue/ue.d.ts:32004](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32004)

___

### GetEdgeVertices

▸ **GetEdgeVertices**(`EdgeID`, `OutEdgeVertexID0`, `OutEdgeVertexID1`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `OutEdgeVertexID0` | [`$Ref`](../interfaces/puerts._Ref.md)<[`VertexID`](ue_ue.VertexID.md)\> |
| `OutEdgeVertexID1` | [`$Ref`](../interfaces/puerts._Ref.md)<[`VertexID`](ue_ue.VertexID.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32005](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32005)

___

### GetFirstValidPolygonGroup

▸ **GetFirstValidPolygonGroup**(): [`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Returns

[`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Defined in

[ue/ue.d.ts:32006](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32006)

___

### GetGroupForPolygon

▸ **GetGroupForPolygon**(`PolygonID`): [`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

[`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Defined in

[ue/ue.d.ts:32007](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32007)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetPolygonAdjacentPolygons

▸ **GetPolygonAdjacentPolygons**(`PolygonID`, `OutAdjacentPolygons`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `OutAdjacentPolygons` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32008](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32008)

___

### GetPolygonCount

▸ **GetPolygonCount**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32009](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32009)

___

### GetPolygonCountInGroup

▸ **GetPolygonCountInGroup**(`PolygonGroupID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32010](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32010)

___

### GetPolygonGroupCount

▸ **GetPolygonGroupCount**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32011)

___

### GetPolygonInGroup

▸ **GetPolygonInGroup**(`PolygonGroupID`, `PolygonNumber`): [`PolygonID`](ue_ue.PolygonID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |
| `PolygonNumber` | `number` |

#### Returns

[`PolygonID`](ue_ue.PolygonID.md)

#### Defined in

[ue/ue.d.ts:32012](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32012)

___

### GetPolygonPerimeterEdge

▸ **GetPolygonPerimeterEdge**(`PolygonID`, `PerimeterEdgeNumber`, `bOutEdgeWindingIsReversedForPolygon`): [`EdgeID`](ue_ue.EdgeID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `PerimeterEdgeNumber` | `number` |
| `bOutEdgeWindingIsReversedForPolygon` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

[`EdgeID`](ue_ue.EdgeID.md)

#### Defined in

[ue/ue.d.ts:32013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32013)

___

### GetPolygonPerimeterEdgeCount

▸ **GetPolygonPerimeterEdgeCount**(`PolygonID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32014](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32014)

___

### GetPolygonPerimeterEdges

▸ **GetPolygonPerimeterEdges**(`PolygonID`, `OutPolygonPerimeterEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `OutPolygonPerimeterEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32015](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32015)

___

### GetPolygonPerimeterVertex

▸ **GetPolygonPerimeterVertex**(`PolygonID`, `PolygonVertexNumber`): [`VertexID`](ue_ue.VertexID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `PolygonVertexNumber` | `number` |

#### Returns

[`VertexID`](ue_ue.VertexID.md)

#### Defined in

[ue/ue.d.ts:32016](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32016)

___

### GetPolygonPerimeterVertexCount

▸ **GetPolygonPerimeterVertexCount**(`PolygonID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32017](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32017)

___

### GetPolygonPerimeterVertexInstance

▸ **GetPolygonPerimeterVertexInstance**(`PolygonID`, `PolygonVertexNumber`): [`VertexInstanceID`](ue_ue.VertexInstanceID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `PolygonVertexNumber` | `number` |

#### Returns

[`VertexInstanceID`](ue_ue.VertexInstanceID.md)

#### Defined in

[ue/ue.d.ts:32018](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32018)

___

### GetPolygonPerimeterVertexInstances

▸ **GetPolygonPerimeterVertexInstances**(`PolygonID`, `OutPolygonPerimeterVertexInstanceIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `OutPolygonPerimeterVertexInstanceIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexInstanceID`](ue_ue.VertexInstanceID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32019](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32019)

___

### GetPolygonPerimeterVertices

▸ **GetPolygonPerimeterVertices**(`PolygonID`, `OutPolygonPerimeterVertexIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `OutPolygonPerimeterVertexIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32020](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32020)

___

### GetPolygonTriangulatedTriangle

▸ **GetPolygonTriangulatedTriangle**(`PolygonID`, `PolygonTriangleNumber`): [`TriangleID`](ue_ue.TriangleID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `PolygonTriangleNumber` | `number` |

#### Returns

[`TriangleID`](ue_ue.TriangleID.md)

#### Defined in

[ue/ue.d.ts:32021](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32021)

___

### GetPolygonTriangulatedTriangleCount

▸ **GetPolygonTriangulatedTriangleCount**(`PolygonID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32022](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32022)

___

### GetSubdivisionCount

▸ **GetSubdivisionCount**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32023](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32023)

___

### GetSubdivisionLimitData

▸ **GetSubdivisionLimitData**(): [`SubdivisionLimitData`](ue_ue.SubdivisionLimitData.md)

#### Returns

[`SubdivisionLimitData`](ue_ue.SubdivisionLimitData.md)

#### Defined in

[ue/ue.d.ts:32024](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32024)

___

### GetTextureCoordinateCount

▸ **GetTextureCoordinateCount**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32025](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32025)

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

#### Defined in

[ue/ue.d.ts:32026](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32026)

___

### GetVertexConnectedEdge

▸ **GetVertexConnectedEdge**(`VertexID`, `ConnectedEdgeNumber`): [`EdgeID`](ue_ue.EdgeID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |
| `ConnectedEdgeNumber` | `number` |

#### Returns

[`EdgeID`](ue_ue.EdgeID.md)

#### Defined in

[ue/ue.d.ts:32027](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32027)

___

### GetVertexConnectedEdgeCount

▸ **GetVertexConnectedEdgeCount**(`VertexID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32028](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32028)

___

### GetVertexConnectedEdges

▸ **GetVertexConnectedEdges**(`VertexID`, `OutConnectedEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |
| `OutConnectedEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32029](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32029)

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

#### Defined in

[ue/ue.d.ts:32030](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32030)

___

### GetVertexCount

▸ **GetVertexCount**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32031](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32031)

___

### GetVertexInstanceConnectedPolygon

▸ **GetVertexInstanceConnectedPolygon**(`VertexInstanceID`, `ConnectedPolygonNumber`): [`PolygonID`](ue_ue.PolygonID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |
| `ConnectedPolygonNumber` | `number` |

#### Returns

[`PolygonID`](ue_ue.PolygonID.md)

#### Defined in

[ue/ue.d.ts:32032](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32032)

___

### GetVertexInstanceConnectedPolygonCount

▸ **GetVertexInstanceConnectedPolygonCount**(`VertexInstanceID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32033](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32033)

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

#### Defined in

[ue/ue.d.ts:32034](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32034)

___

### GetVertexInstanceCount

▸ **GetVertexInstanceCount**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:32035](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32035)

___

### GetVertexInstanceVertex

▸ **GetVertexInstanceVertex**(`VertexInstanceID`): [`VertexID`](ue_ue.VertexID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexInstanceID` | [`VertexInstanceID`](ue_ue.VertexInstanceID.md) |

#### Returns

[`VertexID`](ue_ue.VertexID.md)

#### Defined in

[ue/ue.d.ts:32036](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32036)

___

### GetVertexPairEdge

▸ **GetVertexPairEdge**(`VertexID`, `NextVertexID`, `bOutEdgeWindingIsReversed`): [`EdgeID`](ue_ue.EdgeID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |
| `NextVertexID` | [`VertexID`](ue_ue.VertexID.md) |
| `bOutEdgeWindingIsReversed` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

[`EdgeID`](ue_ue.EdgeID.md)

#### Defined in

[ue/ue.d.ts:32037](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32037)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### InitializeAdapters

▸ **InitializeAdapters**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32038](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32038)

___

### InsertEdgeLoop

▸ **InsertEdgeLoop**(`EdgeID`, `Splits`, `OutNewEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `Splits` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `OutNewEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32039](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32039)

___

### InsetPolygons

▸ **InsetPolygons**(`PolygonIDs`, `InsetFixedDistance`, `InsetProgressTowardCenter`, `Mode`, `OutNewCenterPolygonIDs`, `OutNewSidePolygonIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |
| `InsetFixedDistance` | `number` |
| `InsetProgressTowardCenter` | `number` |
| `Mode` | [`EInsetPolygonsMode`](../enums/ue_ue.EInsetPolygonsMode.md) |
| `OutNewCenterPolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |
| `OutNewSidePolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32040](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32040)

___

### IsBeingModified

▸ **IsBeingModified**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32041](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32041)

___

### IsCommitted

▸ **IsCommitted**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32042](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32042)

___

### IsCommittedAsInstance

▸ **IsCommittedAsInstance**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32043](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32043)

___

### IsCompactAllowed

▸ **IsCompactAllowed**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32044](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32044)

___

### IsOrphanedVertex

▸ **IsOrphanedVertex**(`VertexID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32045](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32045)

___

### IsPreviewingSubdivisions

▸ **IsPreviewingSubdivisions**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32046](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32046)

___

### IsSpatialDatabaseAllowed

▸ **IsSpatialDatabaseAllowed**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32047](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32047)

___

### IsUndoAllowed

▸ **IsUndoAllowed**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32048](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32048)

___

### IsValidEdge

▸ **IsValidEdge**(`EdgeID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32049](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32049)

___

### IsValidPolygon

▸ **IsValidPolygon**(`PolygonID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32050](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32050)

___

### IsValidPolygonGroup

▸ **IsValidPolygonGroup**(`PolygonGroupID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupID` | [`PolygonGroupID`](ue_ue.PolygonGroupID.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32051](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32051)

___

### IsValidVertex

▸ **IsValidVertex**(`VertexID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:32052](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32052)

___

### MoveVertices

▸ **MoveVertices**(`VerticesToMove`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VerticesToMove` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexToMove`](ue_ue.VertexToMove.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32053](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32053)

___

### PropagateInstanceChanges

▸ **PropagateInstanceChanges**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32054](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32054)

___

### QuadrangulateMesh

▸ **QuadrangulateMesh**(`OutNewPolygonIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutNewPolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32055](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32055)

___

### RebuildRenderMesh

▸ **RebuildRenderMesh**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32056](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32056)

___

### Revert

▸ **Revert**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32057](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32057)

___

### RevertInstance

▸ **RevertInstance**(): [`EditableMesh`](ue_ue.EditableMesh.md)

#### Returns

[`EditableMesh`](ue_ue.EditableMesh.md)

#### Defined in

[ue/ue.d.ts:32058](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32058)

___

### SearchSpatialDatabaseForPolygonsInVolume

▸ **SearchSpatialDatabaseForPolygonsInVolume**(`Planes`, `OutPolygons`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Planes` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Plane`](ue_ue.Plane.md)\> |
| `OutPolygons` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32059](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32059)

___

### SearchSpatialDatabaseForPolygonsPotentiallyIntersectingLineSegment

▸ **SearchSpatialDatabaseForPolygonsPotentiallyIntersectingLineSegment**(`LineSegmentStart`, `LineSegmentEnd`, `OutPolygons`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LineSegmentStart` | [`Vector`](ue_ue_s.Vector.md) |
| `LineSegmentEnd` | [`Vector`](ue_ue_s.Vector.md) |
| `OutPolygons` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32060](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32060)

___

### SearchSpatialDatabaseForPolygonsPotentiallyIntersectingPlane

▸ **SearchSpatialDatabaseForPolygonsPotentiallyIntersectingPlane**(`InPlane`, `OutPolygons`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPlane` | [`Plane`](ue_ue.Plane.md) |
| `OutPolygons` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32061](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32061)

___

### SetAllowCompact

▸ **SetAllowCompact**(`bInAllowCompact`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInAllowCompact` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32062](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32062)

___

### SetAllowSpatialDatabase

▸ **SetAllowSpatialDatabase**(`bInAllowSpatialDatabase`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInAllowSpatialDatabase` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32063](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32063)

___

### SetAllowUndo

▸ **SetAllowUndo**(`bInAllowUndo`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInAllowUndo` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32064](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32064)

___

### SetEdgesAttributes

▸ **SetEdgesAttributes**(`AttributesForEdges`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AttributesForEdges` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AttributesForEdge`](ue_ue.AttributesForEdge.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32065](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32065)

___

### SetEdgesCreaseSharpness

▸ **SetEdgesCreaseSharpness**(`EdgeIDs`, `EdgesNewCreaseSharpness`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\> |
| `EdgesNewCreaseSharpness` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32066](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32066)

___

### SetEdgesHardness

▸ **SetEdgesHardness**(`EdgeIDs`, `EdgesNewIsHard`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\> |
| `EdgesNewIsHard` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32067](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32067)

___

### SetEdgesHardnessAutomatically

▸ **SetEdgesHardnessAutomatically**(`EdgeIDs`, `MaxDotProductForSoftEdge`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\> |
| `MaxDotProductForSoftEdge` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32068](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32068)

___

### SetPolygonsVertexAttributes

▸ **SetPolygonsVertexAttributes**(`VertexAttributesForPolygons`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexAttributesForPolygons` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexAttributesForPolygon`](ue_ue.VertexAttributesForPolygon.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32069](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32069)

___

### SetSubdivisionCount

▸ **SetSubdivisionCount**(`NewSubdivisionCount`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewSubdivisionCount` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32070](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32070)

___

### SetTextureCoordinateCount

▸ **SetTextureCoordinateCount**(`NumTexCoords`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NumTexCoords` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32071](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32071)

___

### SetVertexInstancesAttributes

▸ **SetVertexInstancesAttributes**(`AttributesForVertexInstances`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AttributesForVertexInstances` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AttributesForVertexInstance`](ue_ue.AttributesForVertexInstance.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32072](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32072)

___

### SetVerticesAttributes

▸ **SetVerticesAttributes**(`AttributesForVertices`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AttributesForVertices` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AttributesForVertex`](ue_ue.AttributesForVertex.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32073](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32073)

___

### SetVerticesCornerSharpness

▸ **SetVerticesCornerSharpness**(`VertexIDs`, `VerticesNewCornerSharpness`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\> |
| `VerticesNewCornerSharpness` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32074](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32074)

___

### SplitEdge

▸ **SplitEdge**(`EdgeID`, `Splits`, `OutNewVertexIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `Splits` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `OutNewVertexIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32075](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32075)

___

### SplitPolygonalMesh

▸ **SplitPolygonalMesh**(`InPlane`, `PolygonIDs1`, `PolygonIDs2`, `BoundaryIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPlane` | [`Plane`](ue_ue.Plane.md) |
| `PolygonIDs1` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |
| `PolygonIDs2` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |
| `BoundaryIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32076](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32076)

___

### SplitPolygons

▸ **SplitPolygons**(`PolygonsToSplit`, `OutNewEdgeIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonsToSplit` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonToSplit`](ue_ue.PolygonToSplit.md)\> |
| `OutNewEdgeIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdgeID`](ue_ue.EdgeID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32077](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32077)

___

### StartModification

▸ **StartModification**(`MeshModificationType`, `MeshTopologyChange`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MeshModificationType` | [`EMeshModificationType`](../enums/ue_ue.EMeshModificationType.md) |
| `MeshTopologyChange` | [`EMeshTopologyChange`](../enums/ue_ue.EMeshTopologyChange.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32078](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32078)

___

### TessellatePolygons

▸ **TessellatePolygons**(`PolygonIDs`, `TriangleTessellationMode`, `OutNewPolygonIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |
| `TriangleTessellationMode` | [`ETriangleTessellationMode`](../enums/ue_ue.ETriangleTessellationMode.md) |
| `OutNewPolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32079](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32079)

___

### TriangulatePolygons

▸ **TriangulatePolygons**(`PolygonIDs`, `OutNewTrianglePolygons`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |
| `OutNewTrianglePolygons` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32080](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32080)

___

### TryToRemovePolygonEdge

▸ **TryToRemovePolygonEdge**(`EdgeID`, `bOutWasEdgeRemoved`, `OutNewPolygonID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |
| `bOutWasEdgeRemoved` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `OutNewPolygonID` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PolygonID`](ue_ue.PolygonID.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32081](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32081)

___

### TryToRemoveVertex

▸ **TryToRemoveVertex**(`VertexID`, `bOutWasVertexRemoved`, `OutNewEdgeID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID` | [`VertexID`](ue_ue.VertexID.md) |
| `bOutWasVertexRemoved` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `OutNewEdgeID` | [`$Ref`](../interfaces/puerts._Ref.md)<[`EdgeID`](ue_ue.EdgeID.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32082](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32082)

___

### WeldVertices

▸ **WeldVertices**(`VertexIDs`, `OutNewVertexID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexIDs` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VertexID`](ue_ue.VertexID.md)\> |
| `OutNewVertexID` | [`$Ref`](../interfaces/puerts._Ref.md)<[`VertexID`](ue_ue.VertexID.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:32083](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32083)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditableMesh`](ue_ue.EditableMesh.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditableMesh`](ue_ue.EditableMesh.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:32093](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32093)

___

### InvalidEdgeID

▸ `Static` **InvalidEdgeID**(): [`EdgeID`](ue_ue.EdgeID.md)

#### Returns

[`EdgeID`](ue_ue.EdgeID.md)

#### Defined in

[ue/ue.d.ts:32084](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32084)

___

### InvalidPolygonGroupID

▸ `Static` **InvalidPolygonGroupID**(): [`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Returns

[`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Defined in

[ue/ue.d.ts:32085](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32085)

___

### InvalidPolygonID

▸ `Static` **InvalidPolygonID**(): [`PolygonID`](ue_ue.PolygonID.md)

#### Returns

[`PolygonID`](ue_ue.PolygonID.md)

#### Defined in

[ue/ue.d.ts:32086](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32086)

___

### InvalidVertexID

▸ `Static` **InvalidVertexID**(): [`VertexID`](ue_ue.VertexID.md)

#### Returns

[`VertexID`](ue_ue.VertexID.md)

#### Defined in

[ue/ue.d.ts:32087](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32087)

___

### Load

▸ `Static` **Load**(`InName`): [`EditableMesh`](ue_ue.EditableMesh.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditableMesh`](ue_ue.EditableMesh.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:32094](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32094)

___

### MakeEdgeID

▸ `Static` **MakeEdgeID**(`EdgeIndex`): [`EdgeID`](ue_ue.EdgeID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeIndex` | `number` |

#### Returns

[`EdgeID`](ue_ue.EdgeID.md)

#### Defined in

[ue/ue.d.ts:32088](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32088)

___

### MakePolygonGroupID

▸ `Static` **MakePolygonGroupID**(`PolygonGroupIndex`): [`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonGroupIndex` | `number` |

#### Returns

[`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Defined in

[ue/ue.d.ts:32089](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32089)

___

### MakePolygonID

▸ `Static` **MakePolygonID**(`PolygonIndex`): [`PolygonID`](ue_ue.PolygonID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonIndex` | `number` |

#### Returns

[`PolygonID`](ue_ue.PolygonID.md)

#### Defined in

[ue/ue.d.ts:32090](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32090)

___

### MakeVertexID

▸ `Static` **MakeVertexID**(`VertexIndex`): [`VertexID`](ue_ue.VertexID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexIndex` | `number` |

#### Returns

[`VertexID`](ue_ue.VertexID.md)

#### Defined in

[ue/ue.d.ts:32091](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32091)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:32092](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32092)
