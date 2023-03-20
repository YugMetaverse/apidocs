[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / TileView

# Class: TileView

[react-umg](../modules/react_umg.md).TileView

## Hierarchy

- `Component`<[`TileViewProps`](../interfaces/react_umg.TileViewProps.md)\>

  ↳ **`TileView`**

## Table of contents

### Constructors

- [constructor](react_umg.TileView.md#constructor)

### Properties

- [context](react_umg.TileView.md#context)
- [nativePtr](react_umg.TileView.md#nativeptr)
- [props](react_umg.TileView.md#props)
- [refs](react_umg.TileView.md#refs)
- [state](react_umg.TileView.md#state)

### Methods

- [componentDidMount](react_umg.TileView.md#componentdidmount)
- [componentDidUpdate](react_umg.TileView.md#componentdidupdate)
- [componentWillMount](react_umg.TileView.md#componentwillmount)
- [componentWillReceiveProps](react_umg.TileView.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.TileView.md#componentwillunmount)
- [componentWillUpdate](react_umg.TileView.md#componentwillupdate)
- [forceUpdate](react_umg.TileView.md#forceupdate)
- [render](react_umg.TileView.md#render)
- [setState](react_umg.TileView.md#setstate)
- [shouldComponentUpdate](react_umg.TileView.md#shouldcomponentupdate)

## Constructors

### constructor

• **new TileView**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`TileViewProps`](../interfaces/react_umg.TileViewProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<TileViewProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`TileView`](ue_ue.TileView.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`TileViewProps`](../interfaces/react_umg.TileViewProps.md)\>

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
| `prevProps` | `Readonly`<[`TileViewProps`](../interfaces/react_umg.TileViewProps.md)\> |
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
| `nextProps` | `Readonly`<[`TileViewProps`](../interfaces/react_umg.TileViewProps.md)\> |
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
| `nextProps` | `Readonly`<[`TileViewProps`](../interfaces/react_umg.TileViewProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`TileViewProps`](../interfaces/react_umg.TileViewProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`TileViewProps`](../interfaces/react_umg.TileViewProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
