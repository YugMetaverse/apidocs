[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / UserWidget

# Class: UserWidget

[react-umg](../modules/react_umg.md).UserWidget

## Hierarchy

- `Component`<[`UserWidgetProps`](../interfaces/react_umg.UserWidgetProps.md)\>

  ↳ **`UserWidget`**

## Table of contents

### Constructors

- [constructor](react_umg.UserWidget.md#constructor)

### Properties

- [context](react_umg.UserWidget.md#context)
- [nativePtr](react_umg.UserWidget.md#nativeptr)
- [props](react_umg.UserWidget.md#props)
- [refs](react_umg.UserWidget.md#refs)
- [state](react_umg.UserWidget.md#state)

### Methods

- [componentDidMount](react_umg.UserWidget.md#componentdidmount)
- [componentDidUpdate](react_umg.UserWidget.md#componentdidupdate)
- [componentWillMount](react_umg.UserWidget.md#componentwillmount)
- [componentWillReceiveProps](react_umg.UserWidget.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.UserWidget.md#componentwillunmount)
- [componentWillUpdate](react_umg.UserWidget.md#componentwillupdate)
- [forceUpdate](react_umg.UserWidget.md#forceupdate)
- [render](react_umg.UserWidget.md#render)
- [setState](react_umg.UserWidget.md#setstate)
- [shouldComponentUpdate](react_umg.UserWidget.md#shouldcomponentupdate)

## Constructors

### constructor

• **new UserWidget**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`UserWidgetProps`](../interfaces/react_umg.UserWidgetProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<UserWidgetProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`UserWidget`](ue_ue.UserWidget.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`UserWidgetProps`](../interfaces/react_umg.UserWidgetProps.md)\>

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
| `prevProps` | `Readonly`<[`UserWidgetProps`](../interfaces/react_umg.UserWidgetProps.md)\> |
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
| `nextProps` | `Readonly`<[`UserWidgetProps`](../interfaces/react_umg.UserWidgetProps.md)\> |
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
| `nextProps` | `Readonly`<[`UserWidgetProps`](../interfaces/react_umg.UserWidgetProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`UserWidgetProps`](../interfaces/react_umg.UserWidgetProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`UserWidgetProps`](../interfaces/react_umg.UserWidgetProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
