[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / SinglePropertyView

# Class: SinglePropertyView

[react-umg](../modules/react_umg.md).SinglePropertyView

## Hierarchy

- `Component`<[`SinglePropertyViewProps`](../interfaces/react_umg.SinglePropertyViewProps.md)\>

  ↳ **`SinglePropertyView`**

## Table of contents

### Constructors

- [constructor](react_umg.SinglePropertyView.md#constructor)

### Properties

- [context](react_umg.SinglePropertyView.md#context)
- [nativePtr](react_umg.SinglePropertyView.md#nativeptr)
- [props](react_umg.SinglePropertyView.md#props)
- [refs](react_umg.SinglePropertyView.md#refs)
- [state](react_umg.SinglePropertyView.md#state)

### Methods

- [componentDidMount](react_umg.SinglePropertyView.md#componentdidmount)
- [componentDidUpdate](react_umg.SinglePropertyView.md#componentdidupdate)
- [componentWillMount](react_umg.SinglePropertyView.md#componentwillmount)
- [componentWillReceiveProps](react_umg.SinglePropertyView.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.SinglePropertyView.md#componentwillunmount)
- [componentWillUpdate](react_umg.SinglePropertyView.md#componentwillupdate)
- [forceUpdate](react_umg.SinglePropertyView.md#forceupdate)
- [render](react_umg.SinglePropertyView.md#render)
- [setState](react_umg.SinglePropertyView.md#setstate)
- [shouldComponentUpdate](react_umg.SinglePropertyView.md#shouldcomponentupdate)

## Constructors

### constructor

• **new SinglePropertyView**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`SinglePropertyViewProps`](../interfaces/react_umg.SinglePropertyViewProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<SinglePropertyViewProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`SinglePropertyView`](ue_ue.SinglePropertyView.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`SinglePropertyViewProps`](../interfaces/react_umg.SinglePropertyViewProps.md)\>

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
| `prevProps` | `Readonly`<[`SinglePropertyViewProps`](../interfaces/react_umg.SinglePropertyViewProps.md)\> |
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
| `nextProps` | `Readonly`<[`SinglePropertyViewProps`](../interfaces/react_umg.SinglePropertyViewProps.md)\> |
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
| `nextProps` | `Readonly`<[`SinglePropertyViewProps`](../interfaces/react_umg.SinglePropertyViewProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`SinglePropertyViewProps`](../interfaces/react_umg.SinglePropertyViewProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`SinglePropertyViewProps`](../interfaces/react_umg.SinglePropertyViewProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
