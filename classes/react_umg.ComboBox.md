[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / ComboBox

# Class: ComboBox

[react-umg](../modules/react_umg.md).ComboBox

## Hierarchy

- `Component`<[`ComboBoxProps`](../interfaces/react_umg.ComboBoxProps.md)\>

  ↳ **`ComboBox`**

## Table of contents

### Constructors

- [constructor](react_umg.ComboBox.md#constructor)

### Properties

- [context](react_umg.ComboBox.md#context)
- [nativePtr](react_umg.ComboBox.md#nativeptr)
- [props](react_umg.ComboBox.md#props)
- [refs](react_umg.ComboBox.md#refs)
- [state](react_umg.ComboBox.md#state)

### Methods

- [componentDidMount](react_umg.ComboBox.md#componentdidmount)
- [componentDidUpdate](react_umg.ComboBox.md#componentdidupdate)
- [componentWillMount](react_umg.ComboBox.md#componentwillmount)
- [componentWillReceiveProps](react_umg.ComboBox.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.ComboBox.md#componentwillunmount)
- [componentWillUpdate](react_umg.ComboBox.md#componentwillupdate)
- [forceUpdate](react_umg.ComboBox.md#forceupdate)
- [render](react_umg.ComboBox.md#render)
- [setState](react_umg.ComboBox.md#setstate)
- [shouldComponentUpdate](react_umg.ComboBox.md#shouldcomponentupdate)

## Constructors

### constructor

• **new ComboBox**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`ComboBoxProps`](../interfaces/react_umg.ComboBoxProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<ComboBoxProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`ComboBox`](ue_ue.ComboBox.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`ComboBoxProps`](../interfaces/react_umg.ComboBoxProps.md)\>

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
| `prevProps` | `Readonly`<[`ComboBoxProps`](../interfaces/react_umg.ComboBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`ComboBoxProps`](../interfaces/react_umg.ComboBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`ComboBoxProps`](../interfaces/react_umg.ComboBoxProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`ComboBoxProps`](../interfaces/react_umg.ComboBoxProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`ComboBoxProps`](../interfaces/react_umg.ComboBoxProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
