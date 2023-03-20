[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / DetailsView

# Class: DetailsView

[react-umg](../modules/react_umg.md).DetailsView

## Hierarchy

- `Component`<[`DetailsViewProps`](../interfaces/react_umg.DetailsViewProps.md)\>

  ↳ **`DetailsView`**

## Table of contents

### Constructors

- [constructor](react_umg.DetailsView.md#constructor)

### Properties

- [context](react_umg.DetailsView.md#context)
- [nativePtr](react_umg.DetailsView.md#nativeptr)
- [props](react_umg.DetailsView.md#props)
- [refs](react_umg.DetailsView.md#refs)
- [state](react_umg.DetailsView.md#state)

### Methods

- [componentDidMount](react_umg.DetailsView.md#componentdidmount)
- [componentDidUpdate](react_umg.DetailsView.md#componentdidupdate)
- [componentWillMount](react_umg.DetailsView.md#componentwillmount)
- [componentWillReceiveProps](react_umg.DetailsView.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.DetailsView.md#componentwillunmount)
- [componentWillUpdate](react_umg.DetailsView.md#componentwillupdate)
- [forceUpdate](react_umg.DetailsView.md#forceupdate)
- [render](react_umg.DetailsView.md#render)
- [setState](react_umg.DetailsView.md#setstate)
- [shouldComponentUpdate](react_umg.DetailsView.md#shouldcomponentupdate)

## Constructors

### constructor

• **new DetailsView**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`DetailsViewProps`](../interfaces/react_umg.DetailsViewProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<DetailsViewProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`DetailsView`](ue_ue.DetailsView.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`DetailsViewProps`](../interfaces/react_umg.DetailsViewProps.md)\>

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
| `prevProps` | `Readonly`<[`DetailsViewProps`](../interfaces/react_umg.DetailsViewProps.md)\> |
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
| `nextProps` | `Readonly`<[`DetailsViewProps`](../interfaces/react_umg.DetailsViewProps.md)\> |
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
| `nextProps` | `Readonly`<[`DetailsViewProps`](../interfaces/react_umg.DetailsViewProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`DetailsViewProps`](../interfaces/react_umg.DetailsViewProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`DetailsViewProps`](../interfaces/react_umg.DetailsViewProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
