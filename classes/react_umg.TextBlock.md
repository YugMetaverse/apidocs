[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / TextBlock

# Class: TextBlock

[react-umg](../modules/react_umg.md).TextBlock

## Hierarchy

- `Component`<[`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)\>

  ↳ **`TextBlock`**

## Table of contents

### Constructors

- [constructor](react_umg.TextBlock.md#constructor)

### Properties

- [context](react_umg.TextBlock.md#context)
- [nativePtr](react_umg.TextBlock.md#nativeptr)
- [props](react_umg.TextBlock.md#props)
- [refs](react_umg.TextBlock.md#refs)
- [state](react_umg.TextBlock.md#state)

### Methods

- [componentDidMount](react_umg.TextBlock.md#componentdidmount)
- [componentDidUpdate](react_umg.TextBlock.md#componentdidupdate)
- [componentWillMount](react_umg.TextBlock.md#componentwillmount)
- [componentWillReceiveProps](react_umg.TextBlock.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.TextBlock.md#componentwillunmount)
- [componentWillUpdate](react_umg.TextBlock.md#componentwillupdate)
- [forceUpdate](react_umg.TextBlock.md#forceupdate)
- [render](react_umg.TextBlock.md#render)
- [setState](react_umg.TextBlock.md#setstate)
- [shouldComponentUpdate](react_umg.TextBlock.md#shouldcomponentupdate)

## Constructors

### constructor

• **new TextBlock**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<TextBlockProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`TextBlock`](ue_ue.TextBlock.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)\>

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
| `prevProps` | `Readonly`<[`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)\> |
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
| `nextProps` | `Readonly`<[`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)\> |
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
| `nextProps` | `Readonly`<[`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
