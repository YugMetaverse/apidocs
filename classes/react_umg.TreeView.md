[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / TreeView

# Class: TreeView

[react-umg](../modules/react_umg.md).TreeView

## Hierarchy

- `Component`<[`TreeViewProps`](../interfaces/react_umg.TreeViewProps.md)\>

  ↳ **`TreeView`**

## Table of contents

### Constructors

- [constructor](react_umg.TreeView.md#constructor)

### Properties

- [context](react_umg.TreeView.md#context)
- [nativePtr](react_umg.TreeView.md#nativeptr)
- [props](react_umg.TreeView.md#props)
- [refs](react_umg.TreeView.md#refs)
- [state](react_umg.TreeView.md#state)

### Methods

- [componentDidMount](react_umg.TreeView.md#componentdidmount)
- [componentDidUpdate](react_umg.TreeView.md#componentdidupdate)
- [componentWillMount](react_umg.TreeView.md#componentwillmount)
- [componentWillReceiveProps](react_umg.TreeView.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.TreeView.md#componentwillunmount)
- [componentWillUpdate](react_umg.TreeView.md#componentwillupdate)
- [forceUpdate](react_umg.TreeView.md#forceupdate)
- [render](react_umg.TreeView.md#render)
- [setState](react_umg.TreeView.md#setstate)
- [shouldComponentUpdate](react_umg.TreeView.md#shouldcomponentupdate)

## Constructors

### constructor

• **new TreeView**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`TreeViewProps`](../interfaces/react_umg.TreeViewProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<TreeViewProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`TreeView`](ue_ue.TreeView.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`TreeViewProps`](../interfaces/react_umg.TreeViewProps.md)\>

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
| `prevProps` | `Readonly`<[`TreeViewProps`](../interfaces/react_umg.TreeViewProps.md)\> |
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
| `nextProps` | `Readonly`<[`TreeViewProps`](../interfaces/react_umg.TreeViewProps.md)\> |
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
| `nextProps` | `Readonly`<[`TreeViewProps`](../interfaces/react_umg.TreeViewProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`TreeViewProps`](../interfaces/react_umg.TreeViewProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`TreeViewProps`](../interfaces/react_umg.TreeViewProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
