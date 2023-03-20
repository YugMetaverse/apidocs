[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / ScaleBox

# Class: ScaleBox

[react-umg](../modules/react_umg.md).ScaleBox

## Hierarchy

- `Component`<[`ScaleBoxProps`](../interfaces/react_umg.ScaleBoxProps.md)\>

  ↳ **`ScaleBox`**

## Table of contents

### Constructors

- [constructor](react_umg.ScaleBox.md#constructor)

### Properties

- [context](react_umg.ScaleBox.md#context)
- [nativePtr](react_umg.ScaleBox.md#nativeptr)
- [props](react_umg.ScaleBox.md#props)
- [refs](react_umg.ScaleBox.md#refs)
- [state](react_umg.ScaleBox.md#state)

### Methods

- [componentDidMount](react_umg.ScaleBox.md#componentdidmount)
- [componentDidUpdate](react_umg.ScaleBox.md#componentdidupdate)
- [componentWillMount](react_umg.ScaleBox.md#componentwillmount)
- [componentWillReceiveProps](react_umg.ScaleBox.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.ScaleBox.md#componentwillunmount)
- [componentWillUpdate](react_umg.ScaleBox.md#componentwillupdate)
- [forceUpdate](react_umg.ScaleBox.md#forceupdate)
- [render](react_umg.ScaleBox.md#render)
- [setState](react_umg.ScaleBox.md#setstate)
- [shouldComponentUpdate](react_umg.ScaleBox.md#shouldcomponentupdate)

## Constructors

### constructor

• **new ScaleBox**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`ScaleBoxProps`](../interfaces/react_umg.ScaleBoxProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<ScaleBoxProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`ScaleBox`](ue_ue.ScaleBox.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`ScaleBoxProps`](../interfaces/react_umg.ScaleBoxProps.md)\>

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
| `prevProps` | `Readonly`<[`ScaleBoxProps`](../interfaces/react_umg.ScaleBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`ScaleBoxProps`](../interfaces/react_umg.ScaleBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`ScaleBoxProps`](../interfaces/react_umg.ScaleBoxProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`ScaleBoxProps`](../interfaces/react_umg.ScaleBoxProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`ScaleBoxProps`](../interfaces/react_umg.ScaleBoxProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
