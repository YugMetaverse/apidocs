[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KismetRenderingLibrary

# Class: KismetRenderingLibrary

[ue/ue](../modules/ue_ue.md).KismetRenderingLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`KismetRenderingLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.KismetRenderingLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.KismetRenderingLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_KismetRenderingLibrary\_\_](ue_ue.KismetRenderingLibrary.md#__tid_kismetrenderinglibrary__)
- [\_\_tid\_Object\_\_](ue_ue.KismetRenderingLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.KismetRenderingLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.KismetRenderingLibrary.md#executeubergraph)
- [GetClass](ue_ue.KismetRenderingLibrary.md#getclass)
- [GetName](ue_ue.KismetRenderingLibrary.md#getname)
- [GetOuter](ue_ue.KismetRenderingLibrary.md#getouter)
- [GetWorld](ue_ue.KismetRenderingLibrary.md#getworld)
- [BeginDrawCanvasToRenderTarget](ue_ue.KismetRenderingLibrary.md#begindrawcanvastorendertarget)
- [BreakSkinWeightInfo](ue_ue.KismetRenderingLibrary.md#breakskinweightinfo)
- [ClearRenderTarget2D](ue_ue.KismetRenderingLibrary.md#clearrendertarget2d)
- [ConvertRenderTargetToTexture2DEditorOnly](ue_ue.KismetRenderingLibrary.md#convertrendertargettotexture2deditoronly)
- [CreateRenderTarget2D](ue_ue.KismetRenderingLibrary.md#createrendertarget2d)
- [DrawMaterialToRenderTarget](ue_ue.KismetRenderingLibrary.md#drawmaterialtorendertarget)
- [EndDrawCanvasToRenderTarget](ue_ue.KismetRenderingLibrary.md#enddrawcanvastorendertarget)
- [ExportRenderTarget](ue_ue.KismetRenderingLibrary.md#exportrendertarget)
- [ExportTexture2D](ue_ue.KismetRenderingLibrary.md#exporttexture2d)
- [Find](ue_ue.KismetRenderingLibrary.md#find)
- [ImportBufferAsTexture2D](ue_ue.KismetRenderingLibrary.md#importbufferastexture2d)
- [ImportFileAsTexture2D](ue_ue.KismetRenderingLibrary.md#importfileastexture2d)
- [Load](ue_ue.KismetRenderingLibrary.md#load)
- [MakeSkinWeightInfo](ue_ue.KismetRenderingLibrary.md#makeskinweightinfo)
- [ReadRenderTargetPixel](ue_ue.KismetRenderingLibrary.md#readrendertargetpixel)
- [ReadRenderTargetRawPixel](ue_ue.KismetRenderingLibrary.md#readrendertargetrawpixel)
- [ReadRenderTargetRawUV](ue_ue.KismetRenderingLibrary.md#readrendertargetrawuv)
- [ReadRenderTargetUV](ue_ue.KismetRenderingLibrary.md#readrendertargetuv)
- [ReleaseRenderTarget2D](ue_ue.KismetRenderingLibrary.md#releaserendertarget2d)
- [RenderTargetCreateStaticTexture2DEditorOnly](ue_ue.KismetRenderingLibrary.md#rendertargetcreatestatictexture2deditoronly)
- [SetCastInsetShadowForAllAttachments](ue_ue.KismetRenderingLibrary.md#setcastinsetshadowforallattachments)
- [StaticClass](ue_ue.KismetRenderingLibrary.md#staticclass)

## Constructors

### constructor

• **new KismetRenderingLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:43082](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43082)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13418)

___

### \_\_tid\_KismetRenderingLibrary\_\_

• **\_\_tid\_KismetRenderingLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:43106](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43106)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### BeginDrawCanvasToRenderTarget

▸ `Static` **BeginDrawCanvasToRenderTarget**(`WorldContextObject`, `TextureRenderTarget`, `Canvas`, `Size`, `Context`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `TextureRenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `Canvas` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Canvas`](ue_ue.Canvas.md)\> |
| `Size` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |
| `Context` | [`$Ref`](../interfaces/puerts._Ref.md)<[`DrawToRenderTargetContext`](ue_ue.DrawToRenderTargetContext.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43083](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43083)

___

### BreakSkinWeightInfo

▸ `Static` **BreakSkinWeightInfo**(`InWeight`, `Bone0`, `Weight0`, `Bone1`, `Weight1`, `Bone2`, `Weight2`, `Bone3`, `Weight3`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InWeight` | [`SkelMeshSkinWeightInfo`](ue_ue.SkelMeshSkinWeightInfo.md) |
| `Bone0` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Weight0` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Bone1` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Weight1` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Bone2` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Weight2` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Bone3` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Weight3` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43084](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43084)

___

### ClearRenderTarget2D

▸ `Static` **ClearRenderTarget2D**(`WorldContextObject`, `TextureRenderTarget`, `ClearColor?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `TextureRenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `ClearColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43085](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43085)

___

### ConvertRenderTargetToTexture2DEditorOnly

▸ `Static` **ConvertRenderTargetToTexture2DEditorOnly**(`WorldContextObject`, `RenderTarget`, `Texture`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `RenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `Texture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture2D`](ue_ue.Texture2D.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43086](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43086)

___

### CreateRenderTarget2D

▸ `Static` **CreateRenderTarget2D**(`WorldContextObject`, `Width?`, `Height?`, `Format?`, `ClearColor?`, `bAutoGenerateMipMaps?`): [`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Width?` | `number` |
| `Height?` | `number` |
| `Format?` | [`ETextureRenderTargetFormat`](../enums/ue_ue.ETextureRenderTargetFormat.md) |
| `ClearColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `bAutoGenerateMipMaps?` | `boolean` |

#### Returns

[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

#### Defined in

[ue/ue.d.ts:43087](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43087)

___

### DrawMaterialToRenderTarget

▸ `Static` **DrawMaterialToRenderTarget**(`WorldContextObject`, `TextureRenderTarget`, `Material`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `TextureRenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43088](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43088)

___

### EndDrawCanvasToRenderTarget

▸ `Static` **EndDrawCanvasToRenderTarget**(`WorldContextObject`, `Context`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Context` | [`DrawToRenderTargetContext`](ue_ue.DrawToRenderTargetContext.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43089](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43089)

___

### ExportRenderTarget

▸ `Static` **ExportRenderTarget**(`WorldContextObject`, `TextureRenderTarget`, `FilePath`, `FileName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `TextureRenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `FilePath` | `string` |
| `FileName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43090](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43090)

___

### ExportTexture2D

▸ `Static` **ExportTexture2D**(`WorldContextObject`, `Texture`, `FilePath`, `FileName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Texture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture2D`](ue_ue.Texture2D.md)\> |
| `FilePath` | `string` |
| `FileName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43091](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43091)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`KismetRenderingLibrary`](ue_ue.KismetRenderingLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`KismetRenderingLibrary`](ue_ue.KismetRenderingLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:43103](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43103)

___

### ImportBufferAsTexture2D

▸ `Static` **ImportBufferAsTexture2D**(`WorldContextObject`, `Buffer`): [`Texture2D`](ue_ue.Texture2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Buffer` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

[`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:43092](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43092)

___

### ImportFileAsTexture2D

▸ `Static` **ImportFileAsTexture2D**(`WorldContextObject`, `Filename`): [`Texture2D`](ue_ue.Texture2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Filename` | `string` |

#### Returns

[`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:43093](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43093)

___

### Load

▸ `Static` **Load**(`InName`): [`KismetRenderingLibrary`](ue_ue.KismetRenderingLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`KismetRenderingLibrary`](ue_ue.KismetRenderingLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:43104](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43104)

___

### MakeSkinWeightInfo

▸ `Static` **MakeSkinWeightInfo**(`Bone0`, `Weight0`, `Bone1`, `Weight1`, `Bone2`, `Weight2`, `Bone3`, `Weight3`): [`SkelMeshSkinWeightInfo`](ue_ue.SkelMeshSkinWeightInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Bone0` | `number` |
| `Weight0` | `number` |
| `Bone1` | `number` |
| `Weight1` | `number` |
| `Bone2` | `number` |
| `Weight2` | `number` |
| `Bone3` | `number` |
| `Weight3` | `number` |

#### Returns

[`SkelMeshSkinWeightInfo`](ue_ue.SkelMeshSkinWeightInfo.md)

#### Defined in

[ue/ue.d.ts:43094](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43094)

___

### ReadRenderTargetPixel

▸ `Static` **ReadRenderTargetPixel**(`WorldContextObject`, `TextureRenderTarget`, `X`, `Y`): [`Color`](ue_ue_s.Color.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `TextureRenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `X` | `number` |
| `Y` | `number` |

#### Returns

[`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:43095](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43095)

___

### ReadRenderTargetRawPixel

▸ `Static` **ReadRenderTargetRawPixel**(`WorldContextObject`, `TextureRenderTarget`, `X`, `Y`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `TextureRenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `X` | `number` |
| `Y` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:43096](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43096)

___

### ReadRenderTargetRawUV

▸ `Static` **ReadRenderTargetRawUV**(`WorldContextObject`, `TextureRenderTarget`, `U`, `V`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `TextureRenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `U` | `number` |
| `V` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:43097](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43097)

___

### ReadRenderTargetUV

▸ `Static` **ReadRenderTargetUV**(`WorldContextObject`, `TextureRenderTarget`, `U`, `V`): [`Color`](ue_ue_s.Color.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `TextureRenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `U` | `number` |
| `V` | `number` |

#### Returns

[`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:43098](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43098)

___

### ReleaseRenderTarget2D

▸ `Static` **ReleaseRenderTarget2D**(`TextureRenderTarget`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TextureRenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43099](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43099)

___

### RenderTargetCreateStaticTexture2DEditorOnly

▸ `Static` **RenderTargetCreateStaticTexture2DEditorOnly**(`RenderTarget`, `Name?`, `CompressionSettings?`, `MipSettings?`): [`Texture2D`](ue_ue.Texture2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `RenderTarget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)\> |
| `Name?` | `string` |
| `CompressionSettings?` | [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md) |
| `MipSettings?` | [`TextureMipGenSettings`](../enums/ue_ue.TextureMipGenSettings.md) |

#### Returns

[`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:43100](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43100)

___

### SetCastInsetShadowForAllAttachments

▸ `Static` **SetCastInsetShadowForAllAttachments**(`PrimitiveComponent`, `bCastInsetShadow`, `bLightAttachmentsAsGroup`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrimitiveComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `bCastInsetShadow` | `boolean` |
| `bLightAttachmentsAsGroup` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:43101](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43101)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:43102](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L43102)
