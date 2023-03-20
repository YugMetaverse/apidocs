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

#### Defined in

[ue/ue.d.ts:7963](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7963)

## Properties

### \_\_tid\_MeshDescriptionBase\_\_

• **\_\_tid\_MeshDescriptionBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:8053](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8053)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

## Methods

### ComputePolygonTriangulation

▸ **ComputePolygonTriangulation**(`PolygonID`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:7964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7964)

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

### CreateEdge

▸ **CreateEdge**(`VertexID0`, `VertexID1`): [`EdgeID`](ue_ue.EdgeID.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VertexID0` | [`VertexID`](ue_ue.VertexID.md) |
| `VertexID1` | [`VertexID`](ue_ue.VertexID.md) |

#### Returns

[`EdgeID`](ue_ue.EdgeID.md)

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

#### Defined in

[ue/ue.d.ts:7967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7967)

___

### CreatePolygonGroup

▸ **CreatePolygonGroup**(): [`PolygonGroupID`](ue_ue.PolygonGroupID.md)

#### Returns

[`PolygonGroupID`](ue_ue.PolygonGroupID.md)

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

#### Defined in

[ue/ue.d.ts:7972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7972)

___

### CreateVertex

▸ **CreateVertex**(): [`VertexID`](ue_ue.VertexID.md)

#### Returns

[`VertexID`](ue_ue.VertexID.md)

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

#### Defined in

[ue/ue.d.ts:7982](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7982)

___

### Empty

▸ **Empty**(): `void`

#### Returns

`void`

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

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

#### Defined in

[ue/ue.d.ts:7987](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7987)

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

### GetNumEdgeConnectedPolygons

▸ **GetNumEdgeConnectedPolygons**(`EdgeID`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |

#### Returns

`number`

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

#### Defined in

[ue/ue.d.ts:7999](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7999)

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

▸ **GetPolygonAdjacentPolygons**(`PolygonID`, `OutPolygonIDs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PolygonID` | [`PolygonID`](ue_ue.PolygonID.md) |
| `OutPolygonIDs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`PolygonID`](ue_ue.PolygonID.md)\>\> |

#### Returns

`void`

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

#### Defined in

[ue/ue.d.ts:8023](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8023)

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

#### Defined in

[ue/ue.d.ts:8027](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8027)

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

### IsEdgeInternal

▸ **IsEdgeInternal**(`EdgeID`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EdgeID` | [`EdgeID`](ue_ue.EdgeID.md) |

#### Returns

`boolean`

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

#### Defined in

[ue/ue.d.ts:8030](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8030)

___

### IsEmpty

▸ **IsEmpty**(): `boolean`

#### Returns

`boolean`

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

#### Defined in

[ue/ue.d.ts:8045](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8045)

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

#### Defined in

[ue/ue.d.ts:8047](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8047)

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

#### Defined in

[ue/ue.d.ts:8048](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8048)

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

#### Defined in

[ue/ue.d.ts:8050](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8050)

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

#### Defined in

[ue/ue.d.ts:8051](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8051)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:8049](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8049)
