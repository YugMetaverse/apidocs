[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / ListViewBase

# Class: ListViewBase

[react-umg](../modules/react_umg.md).ListViewBase

## Hierarchy

- `Component`<[`ListViewBaseProps`](../interfaces/react_umg.ListViewBaseProps.md)\>

  ↳ **`ListViewBase`**

## Table of contents

### Constructors

- [constructor](react_umg.ListViewBase.md#constructor)

### Properties

- [context](react_umg.ListViewBase.md#context)
- [nativePtr](react_umg.ListViewBase.md#nativeptr)
- [props](react_umg.ListViewBase.md#props)
- [refs](react_umg.ListViewBase.md#refs)
- [state](react_umg.ListViewBase.md#state)

### Methods

- [componentDidMount](react_umg.ListViewBase.md#componentdidmount)
- [componentDidUpdate](react_umg.ListViewBase.md#componentdidupdate)
- [componentWillMount](react_umg.ListViewBase.md#componentwillmount)
- [componentWillReceiveProps](react_umg.ListViewBase.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.ListViewBase.md#componentwillunmount)
- [componentWillUpdate](react_umg.ListViewBase.md#componentwillupdate)
- [forceUpdate](react_umg.ListViewBase.md#forceupdate)
- [render](react_umg.ListViewBase.md#render)
- [setState](react_umg.ListViewBase.md#setstate)
- [shouldComponentUpdate](react_umg.ListViewBase.md#shouldcomponentupdate)

## Constructors

### constructor

• **new ListViewBase**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`ListViewBaseProps`](../interfaces/react_umg.ListViewBaseProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<ListViewBaseProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`ListViewBase`](ue_ue.ListViewBase.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`ListViewBaseProps`](../interfaces/react_umg.ListViewBaseProps.md)\>

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
| `prevProps` | `Readonly`<[`ListViewBaseProps`](../interfaces/react_umg.ListViewBaseProps.md)\> |
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
| `nextProps` | `Readonly`<[`ListViewBaseProps`](../interfaces/react_umg.ListViewBaseProps.md)\> |
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
| `nextProps` | `Readonly`<[`ListViewBaseProps`](../interfaces/react_umg.ListViewBaseProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`ListViewBaseProps`](../interfaces/react_umg.ListViewBaseProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`ListViewBaseProps`](../interfaces/react_umg.ListViewBaseProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
