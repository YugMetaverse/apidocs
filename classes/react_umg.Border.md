[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / Border

# Class: Border

[react-umg](../modules/react_umg.md).Border

## Hierarchy

- `Component`<[`BorderProps`](../interfaces/react_umg.BorderProps.md)\>

  ↳ **`Border`**

## Table of contents

### Constructors

- [constructor](react_umg.Border.md#constructor)

### Properties

- [context](react_umg.Border.md#context)
- [nativePtr](react_umg.Border.md#nativeptr)
- [props](react_umg.Border.md#props)
- [refs](react_umg.Border.md#refs)
- [state](react_umg.Border.md#state)

### Methods

- [componentDidMount](react_umg.Border.md#componentdidmount)
- [componentDidUpdate](react_umg.Border.md#componentdidupdate)
- [componentWillMount](react_umg.Border.md#componentwillmount)
- [componentWillReceiveProps](react_umg.Border.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.Border.md#componentwillunmount)
- [componentWillUpdate](react_umg.Border.md#componentwillupdate)
- [forceUpdate](react_umg.Border.md#forceupdate)
- [render](react_umg.Border.md#render)
- [setState](react_umg.Border.md#setstate)
- [shouldComponentUpdate](react_umg.Border.md#shouldcomponentupdate)

## Constructors

### constructor

• **new Border**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`BorderProps`](../interfaces/react_umg.BorderProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<BorderProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`Border`](ue_ue.Border.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`BorderProps`](../interfaces/react_umg.BorderProps.md)\>

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
| `prevProps` | `Readonly`<[`BorderProps`](../interfaces/react_umg.BorderProps.md)\> |
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
| `nextProps` | `Readonly`<[`BorderProps`](../interfaces/react_umg.BorderProps.md)\> |
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
| `nextProps` | `Readonly`<[`BorderProps`](../interfaces/react_umg.BorderProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`BorderProps`](../interfaces/react_umg.BorderProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`BorderProps`](../interfaces/react_umg.BorderProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
