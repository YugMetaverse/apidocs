[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / SpinBox

# Class: SpinBox

[react-umg](../modules/react_umg.md).SpinBox

## Hierarchy

- `Component`<[`SpinBoxProps`](../interfaces/react_umg.SpinBoxProps.md)\>

  ↳ **`SpinBox`**

## Table of contents

### Constructors

- [constructor](react_umg.SpinBox.md#constructor)

### Properties

- [context](react_umg.SpinBox.md#context)
- [nativePtr](react_umg.SpinBox.md#nativeptr)
- [props](react_umg.SpinBox.md#props)
- [refs](react_umg.SpinBox.md#refs)
- [state](react_umg.SpinBox.md#state)

### Methods

- [componentDidMount](react_umg.SpinBox.md#componentdidmount)
- [componentDidUpdate](react_umg.SpinBox.md#componentdidupdate)
- [componentWillMount](react_umg.SpinBox.md#componentwillmount)
- [componentWillReceiveProps](react_umg.SpinBox.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.SpinBox.md#componentwillunmount)
- [componentWillUpdate](react_umg.SpinBox.md#componentwillupdate)
- [forceUpdate](react_umg.SpinBox.md#forceupdate)
- [render](react_umg.SpinBox.md#render)
- [setState](react_umg.SpinBox.md#setstate)
- [shouldComponentUpdate](react_umg.SpinBox.md#shouldcomponentupdate)

## Constructors

### constructor

• **new SpinBox**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`SpinBoxProps`](../interfaces/react_umg.SpinBoxProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<SpinBoxProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`SpinBox`](ue_ue.SpinBox.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`SpinBoxProps`](../interfaces/react_umg.SpinBoxProps.md)\>

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
| `prevProps` | `Readonly`<[`SpinBoxProps`](../interfaces/react_umg.SpinBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`SpinBoxProps`](../interfaces/react_umg.SpinBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`SpinBoxProps`](../interfaces/react_umg.SpinBoxProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`SpinBoxProps`](../interfaces/react_umg.SpinBoxProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`SpinBoxProps`](../interfaces/react_umg.SpinBoxProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
