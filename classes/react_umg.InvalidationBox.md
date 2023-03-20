[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / InvalidationBox

# Class: InvalidationBox

[react-umg](../modules/react_umg.md).InvalidationBox

## Hierarchy

- `Component`<[`InvalidationBoxProps`](../interfaces/react_umg.InvalidationBoxProps.md)\>

  ↳ **`InvalidationBox`**

## Table of contents

### Constructors

- [constructor](react_umg.InvalidationBox.md#constructor)

### Properties

- [context](react_umg.InvalidationBox.md#context)
- [nativePtr](react_umg.InvalidationBox.md#nativeptr)
- [props](react_umg.InvalidationBox.md#props)
- [refs](react_umg.InvalidationBox.md#refs)
- [state](react_umg.InvalidationBox.md#state)

### Methods

- [componentDidMount](react_umg.InvalidationBox.md#componentdidmount)
- [componentDidUpdate](react_umg.InvalidationBox.md#componentdidupdate)
- [componentWillMount](react_umg.InvalidationBox.md#componentwillmount)
- [componentWillReceiveProps](react_umg.InvalidationBox.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.InvalidationBox.md#componentwillunmount)
- [componentWillUpdate](react_umg.InvalidationBox.md#componentwillupdate)
- [forceUpdate](react_umg.InvalidationBox.md#forceupdate)
- [render](react_umg.InvalidationBox.md#render)
- [setState](react_umg.InvalidationBox.md#setstate)
- [shouldComponentUpdate](react_umg.InvalidationBox.md#shouldcomponentupdate)

## Constructors

### constructor

• **new InvalidationBox**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`InvalidationBoxProps`](../interfaces/react_umg.InvalidationBoxProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<InvalidationBoxProps\>.constructor

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

• **nativePtr**: [`InvalidationBox`](ue_ue.InvalidationBox.md)

#### Defined in

[react-umg/index.d.ts:489](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L489)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`InvalidationBoxProps`](../interfaces/react_umg.InvalidationBoxProps.md)\>

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
| `prevProps` | `Readonly`<[`InvalidationBoxProps`](../interfaces/react_umg.InvalidationBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`InvalidationBoxProps`](../interfaces/react_umg.InvalidationBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`InvalidationBoxProps`](../interfaces/react_umg.InvalidationBoxProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`InvalidationBoxProps`](../interfaces/react_umg.InvalidationBoxProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`InvalidationBoxProps`](../interfaces/react_umg.InvalidationBoxProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate

#### Defined in

node_modules/@types/react/index.d.ts:385
