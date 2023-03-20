[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / Viewport

# Class: Viewport

[react-umg](../modules/react_umg.md).Viewport

## Hierarchy

- `Component`<[`ViewportProps`](../interfaces/react_umg.ViewportProps.md)\>

  ↳ **`Viewport`**

## Table of contents

### Constructors

- [constructor](react_umg.Viewport.md#constructor)

### Properties

- [context](react_umg.Viewport.md#context)
- [nativePtr](react_umg.Viewport.md#nativeptr)
- [props](react_umg.Viewport.md#props)
- [refs](react_umg.Viewport.md#refs)
- [state](react_umg.Viewport.md#state)

### Methods

- [componentDidMount](react_umg.Viewport.md#componentdidmount)
- [componentDidUpdate](react_umg.Viewport.md#componentdidupdate)
- [componentWillMount](react_umg.Viewport.md#componentwillmount)
- [componentWillReceiveProps](react_umg.Viewport.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.Viewport.md#componentwillunmount)
- [componentWillUpdate](react_umg.Viewport.md#componentwillupdate)
- [forceUpdate](react_umg.Viewport.md#forceupdate)
- [render](react_umg.Viewport.md#render)
- [setState](react_umg.Viewport.md#setstate)
- [shouldComponentUpdate](react_umg.Viewport.md#shouldcomponentupdate)

## Constructors

### constructor

• **new Viewport**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`ViewportProps`](../interfaces/react_umg.ViewportProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<ViewportProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`Viewport`](ue_ue.Viewport.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`ViewportProps`](../interfaces/react_umg.ViewportProps.md)\>

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
| `prevProps` | `Readonly`<[`ViewportProps`](../interfaces/react_umg.ViewportProps.md)\> |
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
| `nextProps` | `Readonly`<[`ViewportProps`](../interfaces/react_umg.ViewportProps.md)\> |
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
| `nextProps` | `Readonly`<[`ViewportProps`](../interfaces/react_umg.ViewportProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`ViewportProps`](../interfaces/react_umg.ViewportProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`ViewportProps`](../interfaces/react_umg.ViewportProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
