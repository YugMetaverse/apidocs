[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / SizeBox

# Class: SizeBox

[react-umg](../modules/react_umg.md).SizeBox

## Hierarchy

- `Component`<[`SizeBoxProps`](../interfaces/react_umg.SizeBoxProps.md)\>

  ↳ **`SizeBox`**

## Table of contents

### Constructors

- [constructor](react_umg.SizeBox.md#constructor)

### Properties

- [context](react_umg.SizeBox.md#context)
- [nativePtr](react_umg.SizeBox.md#nativeptr)
- [props](react_umg.SizeBox.md#props)
- [refs](react_umg.SizeBox.md#refs)
- [state](react_umg.SizeBox.md#state)

### Methods

- [componentDidMount](react_umg.SizeBox.md#componentdidmount)
- [componentDidUpdate](react_umg.SizeBox.md#componentdidupdate)
- [componentWillMount](react_umg.SizeBox.md#componentwillmount)
- [componentWillReceiveProps](react_umg.SizeBox.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.SizeBox.md#componentwillunmount)
- [componentWillUpdate](react_umg.SizeBox.md#componentwillupdate)
- [forceUpdate](react_umg.SizeBox.md#forceupdate)
- [render](react_umg.SizeBox.md#render)
- [setState](react_umg.SizeBox.md#setstate)
- [shouldComponentUpdate](react_umg.SizeBox.md#shouldcomponentupdate)

## Constructors

### constructor

• **new SizeBox**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`SizeBoxProps`](../interfaces/react_umg.SizeBoxProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<SizeBoxProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`SizeBox`](ue_ue.SizeBox.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`SizeBoxProps`](../interfaces/react_umg.SizeBoxProps.md)\>

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
| `prevProps` | `Readonly`<[`SizeBoxProps`](../interfaces/react_umg.SizeBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`SizeBoxProps`](../interfaces/react_umg.SizeBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`SizeBoxProps`](../interfaces/react_umg.SizeBoxProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`SizeBoxProps`](../interfaces/react_umg.SizeBoxProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`SizeBoxProps`](../interfaces/react_umg.SizeBoxProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
