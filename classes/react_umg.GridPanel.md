[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / GridPanel

# Class: GridPanel

[react-umg](../modules/react_umg.md).GridPanel

## Hierarchy

- `Component`<[`GridPanelProps`](../interfaces/react_umg.GridPanelProps.md)\>

  ↳ **`GridPanel`**

## Table of contents

### Constructors

- [constructor](react_umg.GridPanel.md#constructor)

### Properties

- [context](react_umg.GridPanel.md#context)
- [nativePtr](react_umg.GridPanel.md#nativeptr)
- [props](react_umg.GridPanel.md#props)
- [refs](react_umg.GridPanel.md#refs)
- [state](react_umg.GridPanel.md#state)

### Methods

- [componentDidMount](react_umg.GridPanel.md#componentdidmount)
- [componentDidUpdate](react_umg.GridPanel.md#componentdidupdate)
- [componentWillMount](react_umg.GridPanel.md#componentwillmount)
- [componentWillReceiveProps](react_umg.GridPanel.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.GridPanel.md#componentwillunmount)
- [componentWillUpdate](react_umg.GridPanel.md#componentwillupdate)
- [forceUpdate](react_umg.GridPanel.md#forceupdate)
- [render](react_umg.GridPanel.md#render)
- [setState](react_umg.GridPanel.md#setstate)
- [shouldComponentUpdate](react_umg.GridPanel.md#shouldcomponentupdate)

## Constructors

### constructor

• **new GridPanel**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`GridPanelProps`](../interfaces/react_umg.GridPanelProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<GridPanelProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`GridPanel`](ue_ue.GridPanel.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`GridPanelProps`](../interfaces/react_umg.GridPanelProps.md)\>

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
| `prevProps` | `Readonly`<[`GridPanelProps`](../interfaces/react_umg.GridPanelProps.md)\> |
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
| `nextProps` | `Readonly`<[`GridPanelProps`](../interfaces/react_umg.GridPanelProps.md)\> |
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
| `nextProps` | `Readonly`<[`GridPanelProps`](../interfaces/react_umg.GridPanelProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`GridPanelProps`](../interfaces/react_umg.GridPanelProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`GridPanelProps`](../interfaces/react_umg.GridPanelProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
