[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PaperFlipbook

# Class: PaperFlipbook

[ue/ue](../modules/ue_ue.md).PaperFlipbook

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PaperFlipbook`**

## Table of contents

### Constructors

- [constructor](ue_ue.PaperFlipbook.md#constructor)

### Properties

- [CollisionSource](ue_ue.PaperFlipbook.md#collisionsource)
- [DefaultMaterial](ue_ue.PaperFlipbook.md#defaultmaterial)
- [FramesPerSecond](ue_ue.PaperFlipbook.md#framespersecond)
- [KeyFrames](ue_ue.PaperFlipbook.md#keyframes)
- [\_\_tid\_Object\_\_](ue_ue.PaperFlipbook.md#__tid_object__)
- [\_\_tid\_PaperFlipbook\_\_](ue_ue.PaperFlipbook.md#__tid_paperflipbook__)

### Methods

- [CreateDefaultSubobject](ue_ue.PaperFlipbook.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PaperFlipbook.md#executeubergraph)
- [GetClass](ue_ue.PaperFlipbook.md#getclass)
- [GetKeyFrameIndexAtTime](ue_ue.PaperFlipbook.md#getkeyframeindexattime)
- [GetName](ue_ue.PaperFlipbook.md#getname)
- [GetNumFrames](ue_ue.PaperFlipbook.md#getnumframes)
- [GetNumKeyFrames](ue_ue.PaperFlipbook.md#getnumkeyframes)
- [GetOuter](ue_ue.PaperFlipbook.md#getouter)
- [GetSpriteAtFrame](ue_ue.PaperFlipbook.md#getspriteatframe)
- [GetSpriteAtTime](ue_ue.PaperFlipbook.md#getspriteattime)
- [GetTotalDuration](ue_ue.PaperFlipbook.md#gettotalduration)
- [GetWorld](ue_ue.PaperFlipbook.md#getworld)
- [IsValidKeyFrameIndex](ue_ue.PaperFlipbook.md#isvalidkeyframeindex)
- [Find](ue_ue.PaperFlipbook.md#find)
- [Load](ue_ue.PaperFlipbook.md#load)
- [StaticClass](ue_ue.PaperFlipbook.md#staticclass)

## Constructors

### constructor

• **new PaperFlipbook**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### CollisionSource

• **CollisionSource**: [`EFlipbookCollisionMode`](../enums/ue_ue.EFlipbookCollisionMode.md)

___

### DefaultMaterial

• **DefaultMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### FramesPerSecond

• **FramesPerSecond**: `number`

___

### KeyFrames

• **KeyFrames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PaperFlipbookKeyFrame`](ue_ue.PaperFlipbookKeyFrame.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PaperFlipbook\_\_

• **\_\_tid\_PaperFlipbook\_\_**: `boolean`

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

### GetKeyFrameIndexAtTime

▸ **GetKeyFrameIndexAtTime**(`Time`, `bClampToEnds?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `bClampToEnds?` | `boolean` |

#### Returns

`number`

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetNumFrames

▸ **GetNumFrames**(): `number`

#### Returns

`number`

___

### GetNumKeyFrames

▸ **GetNumKeyFrames**(): `number`

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

### GetSpriteAtFrame

▸ **GetSpriteAtFrame**(`FrameIndex`): [`PaperSprite`](ue_ue.PaperSprite.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `FrameIndex` | `number` |

#### Returns

[`PaperSprite`](ue_ue.PaperSprite.md)

___

### GetSpriteAtTime

▸ **GetSpriteAtTime**(`Time`, `bClampToEnds?`): [`PaperSprite`](ue_ue.PaperSprite.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | `number` |
| `bClampToEnds?` | `boolean` |

#### Returns

[`PaperSprite`](ue_ue.PaperSprite.md)

___

### GetTotalDuration

▸ **GetTotalDuration**(): `number`

#### Returns

`number`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### IsValidKeyFrameIndex

▸ **IsValidKeyFrameIndex**(`Index`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PaperFlipbook`](ue_ue.PaperFlipbook.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PaperFlipbook`](ue_ue.PaperFlipbook.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PaperFlipbook`](ue_ue.PaperFlipbook.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PaperFlipbook`](ue_ue.PaperFlipbook.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
