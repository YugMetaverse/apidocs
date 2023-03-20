[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / RichTextBlock

# Class: RichTextBlock

[react-umg](../modules/react_umg.md).RichTextBlock

## Hierarchy

- `Component`<[`RichTextBlockProps`](../interfaces/react_umg.RichTextBlockProps.md)\>

  ↳ **`RichTextBlock`**

## Table of contents

### Constructors

- [constructor](react_umg.RichTextBlock.md#constructor)

### Properties

- [context](react_umg.RichTextBlock.md#context)
- [nativePtr](react_umg.RichTextBlock.md#nativeptr)
- [props](react_umg.RichTextBlock.md#props)
- [refs](react_umg.RichTextBlock.md#refs)
- [state](react_umg.RichTextBlock.md#state)

### Methods

- [componentDidMount](react_umg.RichTextBlock.md#componentdidmount)
- [componentDidUpdate](react_umg.RichTextBlock.md#componentdidupdate)
- [componentWillMount](react_umg.RichTextBlock.md#componentwillmount)
- [componentWillReceiveProps](react_umg.RichTextBlock.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.RichTextBlock.md#componentwillunmount)
- [componentWillUpdate](react_umg.RichTextBlock.md#componentwillupdate)
- [forceUpdate](react_umg.RichTextBlock.md#forceupdate)
- [render](react_umg.RichTextBlock.md#render)
- [setState](react_umg.RichTextBlock.md#setstate)
- [shouldComponentUpdate](react_umg.RichTextBlock.md#shouldcomponentupdate)

## Constructors

### constructor

• **new RichTextBlock**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`RichTextBlockProps`](../interfaces/react_umg.RichTextBlockProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<RichTextBlockProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`RichTextBlock`](ue_ue.RichTextBlock.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`RichTextBlockProps`](../interfaces/react_umg.RichTextBlockProps.md)\>

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
| `prevProps` | `Readonly`<[`RichTextBlockProps`](../interfaces/react_umg.RichTextBlockProps.md)\> |
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
| `nextProps` | `Readonly`<[`RichTextBlockProps`](../interfaces/react_umg.RichTextBlockProps.md)\> |
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
| `nextProps` | `Readonly`<[`RichTextBlockProps`](../interfaces/react_umg.RichTextBlockProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`RichTextBlockProps`](../interfaces/react_umg.RichTextBlockProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`RichTextBlockProps`](../interfaces/react_umg.RichTextBlockProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
