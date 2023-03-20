[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / TextureImage

# Class: TextureImage

[react-umg](../modules/react_umg.md).TextureImage

## Hierarchy

- `Component`<[`TextureImageProps`](../interfaces/react_umg.TextureImageProps.md)\>

  ↳ **`TextureImage`**

## Table of contents

### Constructors

- [constructor](react_umg.TextureImage.md#constructor)

### Properties

- [context](react_umg.TextureImage.md#context)
- [nativePtr](react_umg.TextureImage.md#nativeptr)
- [props](react_umg.TextureImage.md#props)
- [refs](react_umg.TextureImage.md#refs)
- [state](react_umg.TextureImage.md#state)

### Methods

- [componentDidMount](react_umg.TextureImage.md#componentdidmount)
- [componentDidUpdate](react_umg.TextureImage.md#componentdidupdate)
- [componentWillMount](react_umg.TextureImage.md#componentwillmount)
- [componentWillReceiveProps](react_umg.TextureImage.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.TextureImage.md#componentwillunmount)
- [componentWillUpdate](react_umg.TextureImage.md#componentwillupdate)
- [forceUpdate](react_umg.TextureImage.md#forceupdate)
- [render](react_umg.TextureImage.md#render)
- [setState](react_umg.TextureImage.md#setstate)
- [shouldComponentUpdate](react_umg.TextureImage.md#shouldcomponentupdate)

## Constructors

### constructor

• **new TextureImage**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`TextureImageProps`](../interfaces/react_umg.TextureImageProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<TextureImageProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`TextureImage`](ue_ue.TextureImage.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`TextureImageProps`](../interfaces/react_umg.TextureImageProps.md)\>

#### Inherited from

React.Component.props

___

### refs

• **refs**: `Object`

#### Index signature

▪ [key: `string`]: `ReactInstance`

#### Inherited from

React.Component.refs

___

### state

• **state**: `Readonly`<{}\>

#### Inherited from

React.Component.state

## Methods

### componentDidMount

▸ `Optional` **componentDidMount**(): `void`

#### Returns

`void`

#### Inherited from

React.Component.componentDidMount

___

### componentDidUpdate

▸ `Optional` **componentDidUpdate**(`prevProps`, `prevState`, `prevContext`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `prevProps` | `Readonly`<[`TextureImageProps`](../interfaces/react_umg.TextureImageProps.md)\> |
| `prevState` | `Readonly`<{}\> |
| `prevContext` | `any` |

#### Returns

`void`

#### Inherited from

React.Component.componentDidUpdate

___

### componentWillMount

▸ `Optional` **componentWillMount**(): `void`

#### Returns

`void`

#### Inherited from

React.Component.componentWillMount

___

### componentWillReceiveProps

▸ `Optional` **componentWillReceiveProps**(`nextProps`, `nextContext`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | `Readonly`<[`TextureImageProps`](../interfaces/react_umg.TextureImageProps.md)\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Inherited from

React.Component.componentWillReceiveProps

___

### componentWillUnmount

▸ `Optional` **componentWillUnmount**(): `void`

#### Returns

`void`

#### Inherited from

React.Component.componentWillUnmount

___

### componentWillUpdate

▸ `Optional` **componentWillUpdate**(`nextProps`, `nextState`, `nextContext`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | `Readonly`<[`TextureImageProps`](../interfaces/react_umg.TextureImageProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Inherited from

React.Component.componentWillUpdate

___

### forceUpdate

▸ **forceUpdate**(`callBack?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callBack?` | () => `any` |

#### Returns

`void`

#### Inherited from

React.Component.forceUpdate

___

### render

▸ **render**(): ``null`` \| ``false`` \| `Element`

#### Returns

``null`` \| ``false`` \| `Element`

#### Inherited from

React.Component.render

___

### setState

▸ **setState**<`K`\>(`state`, `callback?`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `K` | extends `never` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`TextureImageProps`](../interfaces/react_umg.TextureImageProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
| `callback?` | () => `any` |

#### Returns

`void`

#### Inherited from

React.Component.setState

___

### shouldComponentUpdate

▸ `Optional` **shouldComponentUpdate**(`nextProps`, `nextState`, `nextContext`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | `Readonly`<[`TextureImageProps`](../interfaces/react_umg.TextureImageProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
