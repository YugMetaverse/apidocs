[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / MultiLineEditableText

# Class: MultiLineEditableText

[react-umg](../modules/react_umg.md).MultiLineEditableText

## Hierarchy

- `Component`<[`MultiLineEditableTextProps`](../interfaces/react_umg.MultiLineEditableTextProps.md)\>

  ↳ **`MultiLineEditableText`**

## Table of contents

### Constructors

- [constructor](react_umg.MultiLineEditableText.md#constructor)

### Properties

- [context](react_umg.MultiLineEditableText.md#context)
- [nativePtr](react_umg.MultiLineEditableText.md#nativeptr)
- [props](react_umg.MultiLineEditableText.md#props)
- [refs](react_umg.MultiLineEditableText.md#refs)
- [state](react_umg.MultiLineEditableText.md#state)

### Methods

- [componentDidMount](react_umg.MultiLineEditableText.md#componentdidmount)
- [componentDidUpdate](react_umg.MultiLineEditableText.md#componentdidupdate)
- [componentWillMount](react_umg.MultiLineEditableText.md#componentwillmount)
- [componentWillReceiveProps](react_umg.MultiLineEditableText.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.MultiLineEditableText.md#componentwillunmount)
- [componentWillUpdate](react_umg.MultiLineEditableText.md#componentwillupdate)
- [forceUpdate](react_umg.MultiLineEditableText.md#forceupdate)
- [render](react_umg.MultiLineEditableText.md#render)
- [setState](react_umg.MultiLineEditableText.md#setstate)
- [shouldComponentUpdate](react_umg.MultiLineEditableText.md#shouldcomponentupdate)

## Constructors

### constructor

• **new MultiLineEditableText**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`MultiLineEditableTextProps`](../interfaces/react_umg.MultiLineEditableTextProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<MultiLineEditableTextProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`MultiLineEditableText`](ue_ue.MultiLineEditableText.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`MultiLineEditableTextProps`](../interfaces/react_umg.MultiLineEditableTextProps.md)\>

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
| `prevProps` | `Readonly`<[`MultiLineEditableTextProps`](../interfaces/react_umg.MultiLineEditableTextProps.md)\> |
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
| `nextProps` | `Readonly`<[`MultiLineEditableTextProps`](../interfaces/react_umg.MultiLineEditableTextProps.md)\> |
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
| `nextProps` | `Readonly`<[`MultiLineEditableTextProps`](../interfaces/react_umg.MultiLineEditableTextProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`MultiLineEditableTextProps`](../interfaces/react_umg.MultiLineEditableTextProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`MultiLineEditableTextProps`](../interfaces/react_umg.MultiLineEditableTextProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
