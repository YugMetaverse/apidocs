[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / ListView

# Class: ListView

[react-umg](../modules/react_umg.md).ListView

## Hierarchy

- `Component`<[`ListViewProps`](../interfaces/react_umg.ListViewProps.md)\>

  ↳ **`ListView`**

## Table of contents

### Constructors

- [constructor](react_umg.ListView.md#constructor)

### Properties

- [context](react_umg.ListView.md#context)
- [nativePtr](react_umg.ListView.md#nativeptr)
- [props](react_umg.ListView.md#props)
- [refs](react_umg.ListView.md#refs)
- [state](react_umg.ListView.md#state)

### Methods

- [componentDidMount](react_umg.ListView.md#componentdidmount)
- [componentDidUpdate](react_umg.ListView.md#componentdidupdate)
- [componentWillMount](react_umg.ListView.md#componentwillmount)
- [componentWillReceiveProps](react_umg.ListView.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.ListView.md#componentwillunmount)
- [componentWillUpdate](react_umg.ListView.md#componentwillupdate)
- [forceUpdate](react_umg.ListView.md#forceupdate)
- [render](react_umg.ListView.md#render)
- [setState](react_umg.ListView.md#setstate)
- [shouldComponentUpdate](react_umg.ListView.md#shouldcomponentupdate)

## Constructors

### constructor

• **new ListView**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`ListViewProps`](../interfaces/react_umg.ListViewProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<ListViewProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`ListView`](ue_ue.ListView.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`ListViewProps`](../interfaces/react_umg.ListViewProps.md)\>

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
| `prevProps` | `Readonly`<[`ListViewProps`](../interfaces/react_umg.ListViewProps.md)\> |
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
| `nextProps` | `Readonly`<[`ListViewProps`](../interfaces/react_umg.ListViewProps.md)\> |
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
| `nextProps` | `Readonly`<[`ListViewProps`](../interfaces/react_umg.ListViewProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`ListViewProps`](../interfaces/react_umg.ListViewProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`ListViewProps`](../interfaces/react_umg.ListViewProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
