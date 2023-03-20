[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / PropertyViewBase

# Class: PropertyViewBase

[react-umg](../modules/react_umg.md).PropertyViewBase

## Hierarchy

- `Component`<[`PropertyViewBaseProps`](../interfaces/react_umg.PropertyViewBaseProps.md)\>

  ↳ **`PropertyViewBase`**

## Table of contents

### Constructors

- [constructor](react_umg.PropertyViewBase.md#constructor)

### Properties

- [context](react_umg.PropertyViewBase.md#context)
- [nativePtr](react_umg.PropertyViewBase.md#nativeptr)
- [props](react_umg.PropertyViewBase.md#props)
- [refs](react_umg.PropertyViewBase.md#refs)
- [state](react_umg.PropertyViewBase.md#state)

### Methods

- [componentDidMount](react_umg.PropertyViewBase.md#componentdidmount)
- [componentDidUpdate](react_umg.PropertyViewBase.md#componentdidupdate)
- [componentWillMount](react_umg.PropertyViewBase.md#componentwillmount)
- [componentWillReceiveProps](react_umg.PropertyViewBase.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.PropertyViewBase.md#componentwillunmount)
- [componentWillUpdate](react_umg.PropertyViewBase.md#componentwillupdate)
- [forceUpdate](react_umg.PropertyViewBase.md#forceupdate)
- [render](react_umg.PropertyViewBase.md#render)
- [setState](react_umg.PropertyViewBase.md#setstate)
- [shouldComponentUpdate](react_umg.PropertyViewBase.md#shouldcomponentupdate)

## Constructors

### constructor

• **new PropertyViewBase**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`PropertyViewBaseProps`](../interfaces/react_umg.PropertyViewBaseProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<PropertyViewBaseProps\>.constructor

#### Defined in

node_modules/@types/react/index.d.ts:302

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

#### Defined in

node_modules/@types/react/index.d.ts:322

___

### nativePtr

• **nativePtr**: [`PropertyViewBase`](ue_ue.PropertyViewBase.md)

#### Defined in

[react-umg/index.d.ts:910](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L910)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`PropertyViewBaseProps`](../interfaces/react_umg.PropertyViewBaseProps.md)\>

#### Inherited from

React.Component.props

#### Defined in

node_modules/@types/react/index.d.ts:320

___

### refs

• **refs**: `Object`

#### Index signature

▪ [key: `string`]: `ReactInstance`

#### Inherited from

React.Component.refs

#### Defined in

node_modules/@types/react/index.d.ts:323

___

### state

• **state**: `Readonly`<{}\>

#### Inherited from

React.Component.state

#### Defined in

node_modules/@types/react/index.d.ts:321

## Methods

### componentDidMount

▸ `Optional` **componentDidMount**(): `void`

#### Returns

`void`

#### Inherited from

React.Component.componentDidMount

#### Defined in

node_modules/@types/react/index.d.ts:383

___

### componentDidUpdate

▸ `Optional` **componentDidUpdate**(`prevProps`, `prevState`, `prevContext`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `prevProps` | `Readonly`<[`PropertyViewBaseProps`](../interfaces/react_umg.PropertyViewBaseProps.md)\> |
| `prevState` | `Readonly`<{}\> |
| `prevContext` | `any` |

#### Returns

`void`

#### Inherited from

React.Component.componentDidUpdate

#### Defined in

node_modules/@types/react/index.d.ts:387

___

### componentWillMount

▸ `Optional` **componentWillMount**(): `void`

#### Returns

`void`

#### Inherited from

React.Component.componentWillMount

#### Defined in

node_modules/@types/react/index.d.ts:382

___

### componentWillReceiveProps

▸ `Optional` **componentWillReceiveProps**(`nextProps`, `nextContext`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | `Readonly`<[`PropertyViewBaseProps`](../interfaces/react_umg.PropertyViewBaseProps.md)\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Inherited from

React.Component.componentWillReceiveProps

#### Defined in

node_modules/@types/react/index.d.ts:384

___

### componentWillUnmount

▸ `Optional` **componentWillUnmount**(): `void`

#### Returns

`void`

#### Inherited from

React.Component.componentWillUnmount

#### Defined in

node_modules/@types/react/index.d.ts:388

___

### componentWillUpdate

▸ `Optional` **componentWillUpdate**(`nextProps`, `nextState`, `nextContext`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | `Readonly`<[`PropertyViewBaseProps`](../interfaces/react_umg.PropertyViewBaseProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Inherited from

React.Component.componentWillUpdate

#### Defined in

node_modules/@types/react/index.d.ts:386

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

#### Defined in

node_modules/@types/react/index.d.ts:312

___

### render

▸ **render**(): ``null`` \| ``false`` \| `Element`

#### Returns

``null`` \| ``false`` \| `Element`

#### Inherited from

React.Component.render

#### Defined in

node_modules/@types/react/index.d.ts:313

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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`PropertyViewBaseProps`](../interfaces/react_umg.PropertyViewBaseProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
| `callback?` | () => `any` |

#### Returns

`void`

#### Inherited from

React.Component.setState

#### Defined in

node_modules/@types/react/index.d.ts:307

___

### shouldComponentUpdate

▸ `Optional` **shouldComponentUpdate**(`nextProps`, `nextState`, `nextContext`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | `Readonly`<[`PropertyViewBaseProps`](../interfaces/react_umg.PropertyViewBaseProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate

#### Defined in

node_modules/@types/react/index.d.ts:385
