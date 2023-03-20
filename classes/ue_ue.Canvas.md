[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Canvas

# Class: Canvas

[ue/ue](../modules/ue_ue.md).Canvas

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Canvas`**

## Table of contents

### Constructors

- [constructor](ue_ue.Canvas.md#constructor)

### Properties

- [ClipX](ue_ue.Canvas.md#clipx)
- [ClipY](ue_ue.Canvas.md#clipy)
- [ColorModulate](ue_ue.Canvas.md#colormodulate)
- [DefaultTexture](ue_ue.Canvas.md#defaulttexture)
- [DrawColor](ue_ue.Canvas.md#drawcolor)
- [GradientTexture0](ue_ue.Canvas.md#gradienttexture0)
- [OrgX](ue_ue.Canvas.md#orgx)
- [OrgY](ue_ue.Canvas.md#orgy)
- [ReporterGraph](ue_ue.Canvas.md#reportergraph)
- [SizeX](ue_ue.Canvas.md#sizex)
- [SizeY](ue_ue.Canvas.md#sizey)
- [\_\_tid\_Canvas\_\_](ue_ue.Canvas.md#__tid_canvas__)
- [\_\_tid\_Object\_\_](ue_ue.Canvas.md#__tid_object__)
- [bCenterX](ue_ue.Canvas.md#bcenterx)
- [bCenterY](ue_ue.Canvas.md#bcentery)
- [bNoSmooth](ue_ue.Canvas.md#bnosmooth)

### Methods

- [CreateDefaultSubobject](ue_ue.Canvas.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Canvas.md#executeubergraph)
- [GetClass](ue_ue.Canvas.md#getclass)
- [GetName](ue_ue.Canvas.md#getname)
- [GetOuter](ue_ue.Canvas.md#getouter)
- [GetWorld](ue_ue.Canvas.md#getworld)
- [K2\_Deproject](ue_ue.Canvas.md#k2_deproject)
- [K2\_DrawBorder](ue_ue.Canvas.md#k2_drawborder)
- [K2\_DrawBox](ue_ue.Canvas.md#k2_drawbox)
- [K2\_DrawLine](ue_ue.Canvas.md#k2_drawline)
- [K2\_DrawMaterial](ue_ue.Canvas.md#k2_drawmaterial)
- [K2\_DrawMaterialTriangle](ue_ue.Canvas.md#k2_drawmaterialtriangle)
- [K2\_DrawPolygon](ue_ue.Canvas.md#k2_drawpolygon)
- [K2\_DrawText](ue_ue.Canvas.md#k2_drawtext)
- [K2\_DrawTexture](ue_ue.Canvas.md#k2_drawtexture)
- [K2\_DrawTriangle](ue_ue.Canvas.md#k2_drawtriangle)
- [K2\_Project](ue_ue.Canvas.md#k2_project)
- [K2\_StrLen](ue_ue.Canvas.md#k2_strlen)
- [K2\_TextSize](ue_ue.Canvas.md#k2_textsize)
- [Find](ue_ue.Canvas.md#find)
- [Load](ue_ue.Canvas.md#load)
- [StaticClass](ue_ue.Canvas.md#staticclass)

## Constructors

### constructor

• **new Canvas**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ClipX

• **ClipX**: `number`

___

### ClipY

• **ClipY**: `number`

___

### ColorModulate

• **ColorModulate**: [`Plane`](ue_ue.Plane.md)

___

### DefaultTexture

• **DefaultTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### DrawColor

• **DrawColor**: [`Color`](ue_ue_s.Color.md)

___

### GradientTexture0

• **GradientTexture0**: [`Texture2D`](ue_ue.Texture2D.md)

___

### OrgX

• **OrgX**: `number`

___

### OrgY

• **OrgY**: `number`

___

### ReporterGraph

• **ReporterGraph**: [`ReporterGraph`](ue_ue.ReporterGraph.md)

___

### SizeX

• **SizeX**: `number`

___

### SizeY

• **SizeY**: `number`

___

### \_\_tid\_Canvas\_\_

• **\_\_tid\_Canvas\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bCenterX

• **bCenterX**: `boolean`

___

### bCenterY

• **bCenterY**: `boolean`

___

### bNoSmooth

• **bNoSmooth**: `boolean`

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

### K2\_Deproject

▸ **K2_Deproject**(`ScreenPosition`, `WorldOrigin`, `WorldDirection`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScreenPosition` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `WorldOrigin` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `WorldDirection` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

___

### K2\_DrawBorder

▸ **K2_DrawBorder**(`BorderTexture`, `BackgroundTexture`, `LeftBorderTexture`, `RightBorderTexture`, `TopBorderTexture`, `BottomBorderTexture`, `ScreenPosition`, `ScreenSize`, `CoordinatePosition`, `CoordinateSize?`, `RenderColor?`, `BorderScale?`, `BackgroundScale?`, `Rotation?`, `PivotPoint?`, `CornerSize?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BorderTexture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `BackgroundTexture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `LeftBorderTexture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `RightBorderTexture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `TopBorderTexture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `BottomBorderTexture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `ScreenPosition` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `ScreenSize` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `CoordinatePosition` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `CoordinateSize?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `RenderColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `BorderScale?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `BackgroundScale?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Rotation?` | `number` |
| `PivotPoint?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `CornerSize?` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

___

### K2\_DrawBox

▸ **K2_DrawBox**(`ScreenPosition`, `ScreenSize`, `Thickness?`, `RenderColor?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScreenPosition` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `ScreenSize` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Thickness?` | `number` |
| `RenderColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

___

### K2\_DrawLine

▸ **K2_DrawLine**(`ScreenPositionA?`, `ScreenPositionB?`, `Thickness?`, `RenderColor?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScreenPositionA?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `ScreenPositionB?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Thickness?` | `number` |
| `RenderColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

___

### K2\_DrawMaterial

▸ **K2_DrawMaterial**(`RenderMaterial`, `ScreenPosition`, `ScreenSize`, `CoordinatePosition`, `CoordinateSize?`, `Rotation?`, `PivotPoint?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RenderMaterial` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `ScreenPosition` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `ScreenSize` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `CoordinatePosition` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `CoordinateSize?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Rotation?` | `number` |
| `PivotPoint?` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

___

### K2\_DrawMaterialTriangle

▸ **K2_DrawMaterialTriangle**(`RenderMaterial`, `Triangles`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RenderMaterial` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `Triangles` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CanvasUVTri`](ue_ue.CanvasUVTri.md)\> |

#### Returns

`void`

___

### K2\_DrawPolygon

▸ **K2_DrawPolygon**(`RenderTexture`, `ScreenPosition`, `Radius?`, `NumberOfSides?`, `RenderColor?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RenderTexture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `ScreenPosition` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Radius?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `NumberOfSides?` | `number` |
| `RenderColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

___

### K2\_DrawText

▸ **K2_DrawText**(`RenderFont`, `RenderText`, `ScreenPosition`, `Scale?`, `RenderColor?`, `Kerning?`, `ShadowColor?`, `ShadowOffset?`, `bCentreX?`, `bCentreY?`, `bOutlined?`, `OutlineColor?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RenderFont` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Font`](ue_ue.Font.md)\> |
| `RenderText` | `string` |
| `ScreenPosition` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Scale?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `RenderColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `Kerning?` | `number` |
| `ShadowColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `ShadowOffset?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `bCentreX?` | `boolean` |
| `bCentreY?` | `boolean` |
| `bOutlined?` | `boolean` |
| `OutlineColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

___

### K2\_DrawTexture

▸ **K2_DrawTexture**(`RenderTexture`, `ScreenPosition`, `ScreenSize`, `CoordinatePosition`, `CoordinateSize?`, `RenderColor?`, `BlendMode?`, `Rotation?`, `PivotPoint?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RenderTexture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `ScreenPosition` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `ScreenSize` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `CoordinatePosition` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `CoordinateSize?` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `RenderColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `BlendMode?` | [`EBlendMode`](../enums/ue_ue.EBlendMode.md) |
| `Rotation?` | `number` |
| `PivotPoint?` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`void`

___

### K2\_DrawTriangle

▸ **K2_DrawTriangle**(`RenderTexture`, `Triangles`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `RenderTexture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `Triangles` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CanvasUVTri`](ue_ue.CanvasUVTri.md)\> |

#### Returns

`void`

___

### K2\_Project

▸ **K2_Project**(`WorldLocation`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### K2\_StrLen

▸ **K2_StrLen**(`RenderFont`, `RenderText`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `RenderFont` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Font`](ue_ue.Font.md)\> |
| `RenderText` | `string` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### K2\_TextSize

▸ **K2_TextSize**(`RenderFont`, `RenderText`, `Scale?`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `RenderFont` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Font`](ue_ue.Font.md)\> |
| `RenderText` | `string` |
| `Scale?` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Canvas`](ue_ue.Canvas.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Canvas`](ue_ue.Canvas.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Canvas`](ue_ue.Canvas.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Canvas`](ue_ue.Canvas.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
