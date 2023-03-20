[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / DynamicEntryBox

# Class: DynamicEntryBox

[react-umg](../modules/react_umg.md).DynamicEntryBox

## Hierarchy

- `Component`<[`DynamicEntryBoxProps`](../interfaces/react_umg.DynamicEntryBoxProps.md)\>

  ↳ **`DynamicEntryBox`**

## Table of contents

### Constructors

- [constructor](react_umg.DynamicEntryBox.md#constructor)

### Properties

- [context](react_umg.DynamicEntryBox.md#context)
- [nativePtr](react_umg.DynamicEntryBox.md#nativeptr)
- [props](react_umg.DynamicEntryBox.md#props)
- [refs](react_umg.DynamicEntryBox.md#refs)
- [state](react_umg.DynamicEntryBox.md#state)

### Methods

- [componentDidMount](react_umg.DynamicEntryBox.md#componentdidmount)
- [componentDidUpdate](react_umg.DynamicEntryBox.md#componentdidupdate)
- [componentWillMount](react_umg.DynamicEntryBox.md#componentwillmount)
- [componentWillReceiveProps](react_umg.DynamicEntryBox.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.DynamicEntryBox.md#componentwillunmount)
- [componentWillUpdate](react_umg.DynamicEntryBox.md#componentwillupdate)
- [forceUpdate](react_umg.DynamicEntryBox.md#forceupdate)
- [render](react_umg.DynamicEntryBox.md#render)
- [setState](react_umg.DynamicEntryBox.md#setstate)
- [shouldComponentUpdate](react_umg.DynamicEntryBox.md#shouldcomponentupdate)

## Constructors

### constructor

• **new DynamicEntryBox**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`DynamicEntryBoxProps`](../interfaces/react_umg.DynamicEntryBoxProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<DynamicEntryBoxProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`DynamicEntryBox`](ue_ue.DynamicEntryBox.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`DynamicEntryBoxProps`](../interfaces/react_umg.DynamicEntryBoxProps.md)\>

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
| `prevProps` | `Readonly`<[`DynamicEntryBoxProps`](../interfaces/react_umg.DynamicEntryBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`DynamicEntryBoxProps`](../interfaces/react_umg.DynamicEntryBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`DynamicEntryBoxProps`](../interfaces/react_umg.DynamicEntryBoxProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`DynamicEntryBoxProps`](../interfaces/react_umg.DynamicEntryBoxProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`DynamicEntryBoxProps`](../interfaces/react_umg.DynamicEntryBoxProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
