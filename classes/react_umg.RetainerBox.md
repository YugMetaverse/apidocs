[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / RetainerBox

# Class: RetainerBox

[react-umg](../modules/react_umg.md).RetainerBox

## Hierarchy

- `Component`<[`RetainerBoxProps`](../interfaces/react_umg.RetainerBoxProps.md)\>

  ↳ **`RetainerBox`**

## Table of contents

### Constructors

- [constructor](react_umg.RetainerBox.md#constructor)

### Properties

- [context](react_umg.RetainerBox.md#context)
- [nativePtr](react_umg.RetainerBox.md#nativeptr)
- [props](react_umg.RetainerBox.md#props)
- [refs](react_umg.RetainerBox.md#refs)
- [state](react_umg.RetainerBox.md#state)

### Methods

- [componentDidMount](react_umg.RetainerBox.md#componentdidmount)
- [componentDidUpdate](react_umg.RetainerBox.md#componentdidupdate)
- [componentWillMount](react_umg.RetainerBox.md#componentwillmount)
- [componentWillReceiveProps](react_umg.RetainerBox.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.RetainerBox.md#componentwillunmount)
- [componentWillUpdate](react_umg.RetainerBox.md#componentwillupdate)
- [forceUpdate](react_umg.RetainerBox.md#forceupdate)
- [render](react_umg.RetainerBox.md#render)
- [setState](react_umg.RetainerBox.md#setstate)
- [shouldComponentUpdate](react_umg.RetainerBox.md#shouldcomponentupdate)

## Constructors

### constructor

• **new RetainerBox**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`RetainerBoxProps`](../interfaces/react_umg.RetainerBoxProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<RetainerBoxProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`RetainerBox`](ue_ue.RetainerBox.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`RetainerBoxProps`](../interfaces/react_umg.RetainerBoxProps.md)\>

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
| `prevProps` | `Readonly`<[`RetainerBoxProps`](../interfaces/react_umg.RetainerBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`RetainerBoxProps`](../interfaces/react_umg.RetainerBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`RetainerBoxProps`](../interfaces/react_umg.RetainerBoxProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`RetainerBoxProps`](../interfaces/react_umg.RetainerBoxProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`RetainerBoxProps`](../interfaces/react_umg.RetainerBoxProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
