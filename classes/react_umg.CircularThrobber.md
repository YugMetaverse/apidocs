[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / CircularThrobber

# Class: CircularThrobber

[react-umg](../modules/react_umg.md).CircularThrobber

## Hierarchy

- `Component`<[`CircularThrobberProps`](../interfaces/react_umg.CircularThrobberProps.md)\>

  ↳ **`CircularThrobber`**

## Table of contents

### Constructors

- [constructor](react_umg.CircularThrobber.md#constructor)

### Properties

- [context](react_umg.CircularThrobber.md#context)
- [nativePtr](react_umg.CircularThrobber.md#nativeptr)
- [props](react_umg.CircularThrobber.md#props)
- [refs](react_umg.CircularThrobber.md#refs)
- [state](react_umg.CircularThrobber.md#state)

### Methods

- [componentDidMount](react_umg.CircularThrobber.md#componentdidmount)
- [componentDidUpdate](react_umg.CircularThrobber.md#componentdidupdate)
- [componentWillMount](react_umg.CircularThrobber.md#componentwillmount)
- [componentWillReceiveProps](react_umg.CircularThrobber.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.CircularThrobber.md#componentwillunmount)
- [componentWillUpdate](react_umg.CircularThrobber.md#componentwillupdate)
- [forceUpdate](react_umg.CircularThrobber.md#forceupdate)
- [render](react_umg.CircularThrobber.md#render)
- [setState](react_umg.CircularThrobber.md#setstate)
- [shouldComponentUpdate](react_umg.CircularThrobber.md#shouldcomponentupdate)

## Constructors

### constructor

• **new CircularThrobber**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`CircularThrobberProps`](../interfaces/react_umg.CircularThrobberProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<CircularThrobberProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`CircularThrobber`](ue_ue.CircularThrobber.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`CircularThrobberProps`](../interfaces/react_umg.CircularThrobberProps.md)\>

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
| `prevProps` | `Readonly`<[`CircularThrobberProps`](../interfaces/react_umg.CircularThrobberProps.md)\> |
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
| `nextProps` | `Readonly`<[`CircularThrobberProps`](../interfaces/react_umg.CircularThrobberProps.md)\> |
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
| `nextProps` | `Readonly`<[`CircularThrobberProps`](../interfaces/react_umg.CircularThrobberProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`CircularThrobberProps`](../interfaces/react_umg.CircularThrobberProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`CircularThrobberProps`](../interfaces/react_umg.CircularThrobberProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
