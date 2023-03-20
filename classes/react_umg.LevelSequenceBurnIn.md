[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / LevelSequenceBurnIn

# Class: LevelSequenceBurnIn

[react-umg](../modules/react_umg.md).LevelSequenceBurnIn

## Hierarchy

- `Component`<[`LevelSequenceBurnInProps`](../interfaces/react_umg.LevelSequenceBurnInProps.md)\>

  ↳ **`LevelSequenceBurnIn`**

## Table of contents

### Constructors

- [constructor](react_umg.LevelSequenceBurnIn.md#constructor)

### Properties

- [context](react_umg.LevelSequenceBurnIn.md#context)
- [nativePtr](react_umg.LevelSequenceBurnIn.md#nativeptr)
- [props](react_umg.LevelSequenceBurnIn.md#props)
- [refs](react_umg.LevelSequenceBurnIn.md#refs)
- [state](react_umg.LevelSequenceBurnIn.md#state)

### Methods

- [componentDidMount](react_umg.LevelSequenceBurnIn.md#componentdidmount)
- [componentDidUpdate](react_umg.LevelSequenceBurnIn.md#componentdidupdate)
- [componentWillMount](react_umg.LevelSequenceBurnIn.md#componentwillmount)
- [componentWillReceiveProps](react_umg.LevelSequenceBurnIn.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.LevelSequenceBurnIn.md#componentwillunmount)
- [componentWillUpdate](react_umg.LevelSequenceBurnIn.md#componentwillupdate)
- [forceUpdate](react_umg.LevelSequenceBurnIn.md#forceupdate)
- [render](react_umg.LevelSequenceBurnIn.md#render)
- [setState](react_umg.LevelSequenceBurnIn.md#setstate)
- [shouldComponentUpdate](react_umg.LevelSequenceBurnIn.md#shouldcomponentupdate)

## Constructors

### constructor

• **new LevelSequenceBurnIn**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`LevelSequenceBurnInProps`](../interfaces/react_umg.LevelSequenceBurnInProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<LevelSequenceBurnInProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`LevelSequenceBurnIn`](ue_ue.LevelSequenceBurnIn.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`LevelSequenceBurnInProps`](../interfaces/react_umg.LevelSequenceBurnInProps.md)\>

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
| `prevProps` | `Readonly`<[`LevelSequenceBurnInProps`](../interfaces/react_umg.LevelSequenceBurnInProps.md)\> |
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
| `nextProps` | `Readonly`<[`LevelSequenceBurnInProps`](../interfaces/react_umg.LevelSequenceBurnInProps.md)\> |
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
| `nextProps` | `Readonly`<[`LevelSequenceBurnInProps`](../interfaces/react_umg.LevelSequenceBurnInProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`LevelSequenceBurnInProps`](../interfaces/react_umg.LevelSequenceBurnInProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`LevelSequenceBurnInProps`](../interfaces/react_umg.LevelSequenceBurnInProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
