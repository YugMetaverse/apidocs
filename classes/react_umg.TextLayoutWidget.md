[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / TextLayoutWidget

# Class: TextLayoutWidget

[react-umg](../modules/react_umg.md).TextLayoutWidget

## Hierarchy

- `Component`<[`TextLayoutWidgetProps`](../interfaces/react_umg.TextLayoutWidgetProps.md)\>

  ↳ **`TextLayoutWidget`**

## Table of contents

### Constructors

- [constructor](react_umg.TextLayoutWidget.md#constructor)

### Properties

- [context](react_umg.TextLayoutWidget.md#context)
- [nativePtr](react_umg.TextLayoutWidget.md#nativeptr)
- [props](react_umg.TextLayoutWidget.md#props)
- [refs](react_umg.TextLayoutWidget.md#refs)
- [state](react_umg.TextLayoutWidget.md#state)

### Methods

- [componentDidMount](react_umg.TextLayoutWidget.md#componentdidmount)
- [componentDidUpdate](react_umg.TextLayoutWidget.md#componentdidupdate)
- [componentWillMount](react_umg.TextLayoutWidget.md#componentwillmount)
- [componentWillReceiveProps](react_umg.TextLayoutWidget.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.TextLayoutWidget.md#componentwillunmount)
- [componentWillUpdate](react_umg.TextLayoutWidget.md#componentwillupdate)
- [forceUpdate](react_umg.TextLayoutWidget.md#forceupdate)
- [render](react_umg.TextLayoutWidget.md#render)
- [setState](react_umg.TextLayoutWidget.md#setstate)
- [shouldComponentUpdate](react_umg.TextLayoutWidget.md#shouldcomponentupdate)

## Constructors

### constructor

• **new TextLayoutWidget**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`TextLayoutWidgetProps`](../interfaces/react_umg.TextLayoutWidgetProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<TextLayoutWidgetProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`TextLayoutWidget`](ue_ue.TextLayoutWidget.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`TextLayoutWidgetProps`](../interfaces/react_umg.TextLayoutWidgetProps.md)\>

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
| `prevProps` | `Readonly`<[`TextLayoutWidgetProps`](../interfaces/react_umg.TextLayoutWidgetProps.md)\> |
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
| `nextProps` | `Readonly`<[`TextLayoutWidgetProps`](../interfaces/react_umg.TextLayoutWidgetProps.md)\> |
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
| `nextProps` | `Readonly`<[`TextLayoutWidgetProps`](../interfaces/react_umg.TextLayoutWidgetProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`TextLayoutWidgetProps`](../interfaces/react_umg.TextLayoutWidgetProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`TextLayoutWidgetProps`](../interfaces/react_umg.TextLayoutWidgetProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
