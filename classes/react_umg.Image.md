[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / Image

# Class: Image

[react-umg](../modules/react_umg.md).Image

## Hierarchy

- `Component`<[`ImageProps`](../interfaces/react_umg.ImageProps.md)\>

  ↳ **`Image`**

## Table of contents

### Constructors

- [constructor](react_umg.Image.md#constructor)

### Properties

- [context](react_umg.Image.md#context)
- [nativePtr](react_umg.Image.md#nativeptr)
- [props](react_umg.Image.md#props)
- [refs](react_umg.Image.md#refs)
- [state](react_umg.Image.md#state)

### Methods

- [componentDidMount](react_umg.Image.md#componentdidmount)
- [componentDidUpdate](react_umg.Image.md#componentdidupdate)
- [componentWillMount](react_umg.Image.md#componentwillmount)
- [componentWillReceiveProps](react_umg.Image.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.Image.md#componentwillunmount)
- [componentWillUpdate](react_umg.Image.md#componentwillupdate)
- [forceUpdate](react_umg.Image.md#forceupdate)
- [render](react_umg.Image.md#render)
- [setState](react_umg.Image.md#setstate)
- [shouldComponentUpdate](react_umg.Image.md#shouldcomponentupdate)

## Constructors

### constructor

• **new Image**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`ImageProps`](../interfaces/react_umg.ImageProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<ImageProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`Image`](ue_ue.Image.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`ImageProps`](../interfaces/react_umg.ImageProps.md)\>

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
| `prevProps` | `Readonly`<[`ImageProps`](../interfaces/react_umg.ImageProps.md)\> |
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
| `nextProps` | `Readonly`<[`ImageProps`](../interfaces/react_umg.ImageProps.md)\> |
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
| `nextProps` | `Readonly`<[`ImageProps`](../interfaces/react_umg.ImageProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`ImageProps`](../interfaces/react_umg.ImageProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`ImageProps`](../interfaces/react_umg.ImageProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
