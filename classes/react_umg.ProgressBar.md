[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / ProgressBar

# Class: ProgressBar

[react-umg](../modules/react_umg.md).ProgressBar

## Hierarchy

- `Component`<[`ProgressBarProps`](../interfaces/react_umg.ProgressBarProps.md)\>

  ↳ **`ProgressBar`**

## Table of contents

### Constructors

- [constructor](react_umg.ProgressBar.md#constructor)

### Properties

- [context](react_umg.ProgressBar.md#context)
- [nativePtr](react_umg.ProgressBar.md#nativeptr)
- [props](react_umg.ProgressBar.md#props)
- [refs](react_umg.ProgressBar.md#refs)
- [state](react_umg.ProgressBar.md#state)

### Methods

- [componentDidMount](react_umg.ProgressBar.md#componentdidmount)
- [componentDidUpdate](react_umg.ProgressBar.md#componentdidupdate)
- [componentWillMount](react_umg.ProgressBar.md#componentwillmount)
- [componentWillReceiveProps](react_umg.ProgressBar.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.ProgressBar.md#componentwillunmount)
- [componentWillUpdate](react_umg.ProgressBar.md#componentwillupdate)
- [forceUpdate](react_umg.ProgressBar.md#forceupdate)
- [render](react_umg.ProgressBar.md#render)
- [setState](react_umg.ProgressBar.md#setstate)
- [shouldComponentUpdate](react_umg.ProgressBar.md#shouldcomponentupdate)

## Constructors

### constructor

• **new ProgressBar**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`ProgressBarProps`](../interfaces/react_umg.ProgressBarProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<ProgressBarProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`ProgressBar`](ue_ue.ProgressBar.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`ProgressBarProps`](../interfaces/react_umg.ProgressBarProps.md)\>

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
| `prevProps` | `Readonly`<[`ProgressBarProps`](../interfaces/react_umg.ProgressBarProps.md)\> |
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
| `nextProps` | `Readonly`<[`ProgressBarProps`](../interfaces/react_umg.ProgressBarProps.md)\> |
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
| `nextProps` | `Readonly`<[`ProgressBarProps`](../interfaces/react_umg.ProgressBarProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`ProgressBarProps`](../interfaces/react_umg.ProgressBarProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`ProgressBarProps`](../interfaces/react_umg.ProgressBarProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
