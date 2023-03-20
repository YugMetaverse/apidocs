[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / EditableTextBox

# Class: EditableTextBox

[react-umg](../modules/react_umg.md).EditableTextBox

## Hierarchy

- `Component`<[`EditableTextBoxProps`](../interfaces/react_umg.EditableTextBoxProps.md)\>

  ↳ **`EditableTextBox`**

## Table of contents

### Constructors

- [constructor](react_umg.EditableTextBox.md#constructor)

### Properties

- [context](react_umg.EditableTextBox.md#context)
- [nativePtr](react_umg.EditableTextBox.md#nativeptr)
- [props](react_umg.EditableTextBox.md#props)
- [refs](react_umg.EditableTextBox.md#refs)
- [state](react_umg.EditableTextBox.md#state)

### Methods

- [componentDidMount](react_umg.EditableTextBox.md#componentdidmount)
- [componentDidUpdate](react_umg.EditableTextBox.md#componentdidupdate)
- [componentWillMount](react_umg.EditableTextBox.md#componentwillmount)
- [componentWillReceiveProps](react_umg.EditableTextBox.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.EditableTextBox.md#componentwillunmount)
- [componentWillUpdate](react_umg.EditableTextBox.md#componentwillupdate)
- [forceUpdate](react_umg.EditableTextBox.md#forceupdate)
- [render](react_umg.EditableTextBox.md#render)
- [setState](react_umg.EditableTextBox.md#setstate)
- [shouldComponentUpdate](react_umg.EditableTextBox.md#shouldcomponentupdate)

## Constructors

### constructor

• **new EditableTextBox**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`EditableTextBoxProps`](../interfaces/react_umg.EditableTextBoxProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<EditableTextBoxProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`EditableTextBox`](ue_ue.EditableTextBox.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`EditableTextBoxProps`](../interfaces/react_umg.EditableTextBoxProps.md)\>

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
| `prevProps` | `Readonly`<[`EditableTextBoxProps`](../interfaces/react_umg.EditableTextBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`EditableTextBoxProps`](../interfaces/react_umg.EditableTextBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`EditableTextBoxProps`](../interfaces/react_umg.EditableTextBoxProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`EditableTextBoxProps`](../interfaces/react_umg.EditableTextBoxProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`EditableTextBoxProps`](../interfaces/react_umg.EditableTextBoxProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
