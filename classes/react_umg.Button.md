[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / Button

# Class: Button

[react-umg](../modules/react_umg.md).Button

## Hierarchy

- `Component`<[`ButtonProps`](../interfaces/react_umg.ButtonProps.md)\>

  ↳ **`Button`**

## Table of contents

### Constructors

- [constructor](react_umg.Button.md#constructor)

### Properties

- [context](react_umg.Button.md#context)
- [nativePtr](react_umg.Button.md#nativeptr)
- [props](react_umg.Button.md#props)
- [refs](react_umg.Button.md#refs)
- [state](react_umg.Button.md#state)

### Methods

- [componentDidMount](react_umg.Button.md#componentdidmount)
- [componentDidUpdate](react_umg.Button.md#componentdidupdate)
- [componentWillMount](react_umg.Button.md#componentwillmount)
- [componentWillReceiveProps](react_umg.Button.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.Button.md#componentwillunmount)
- [componentWillUpdate](react_umg.Button.md#componentwillupdate)
- [forceUpdate](react_umg.Button.md#forceupdate)
- [render](react_umg.Button.md#render)
- [setState](react_umg.Button.md#setstate)
- [shouldComponentUpdate](react_umg.Button.md#shouldcomponentupdate)

## Constructors

### constructor

• **new Button**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`ButtonProps`](../interfaces/react_umg.ButtonProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<ButtonProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`Button`](ue_ue.Button.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`ButtonProps`](../interfaces/react_umg.ButtonProps.md)\>

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
| `prevProps` | `Readonly`<[`ButtonProps`](../interfaces/react_umg.ButtonProps.md)\> |
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
| `nextProps` | `Readonly`<[`ButtonProps`](../interfaces/react_umg.ButtonProps.md)\> |
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
| `nextProps` | `Readonly`<[`ButtonProps`](../interfaces/react_umg.ButtonProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`ButtonProps`](../interfaces/react_umg.ButtonProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`ButtonProps`](../interfaces/react_umg.ButtonProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
