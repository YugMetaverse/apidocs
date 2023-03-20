[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / WrapBox

# Class: WrapBox

[react-umg](../modules/react_umg.md).WrapBox

## Hierarchy

- `Component`<[`WrapBoxProps`](../interfaces/react_umg.WrapBoxProps.md)\>

  ↳ **`WrapBox`**

## Table of contents

### Constructors

- [constructor](react_umg.WrapBox.md#constructor)

### Properties

- [context](react_umg.WrapBox.md#context)
- [nativePtr](react_umg.WrapBox.md#nativeptr)
- [props](react_umg.WrapBox.md#props)
- [refs](react_umg.WrapBox.md#refs)
- [state](react_umg.WrapBox.md#state)

### Methods

- [componentDidMount](react_umg.WrapBox.md#componentdidmount)
- [componentDidUpdate](react_umg.WrapBox.md#componentdidupdate)
- [componentWillMount](react_umg.WrapBox.md#componentwillmount)
- [componentWillReceiveProps](react_umg.WrapBox.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.WrapBox.md#componentwillunmount)
- [componentWillUpdate](react_umg.WrapBox.md#componentwillupdate)
- [forceUpdate](react_umg.WrapBox.md#forceupdate)
- [render](react_umg.WrapBox.md#render)
- [setState](react_umg.WrapBox.md#setstate)
- [shouldComponentUpdate](react_umg.WrapBox.md#shouldcomponentupdate)

## Constructors

### constructor

• **new WrapBox**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`WrapBoxProps`](../interfaces/react_umg.WrapBoxProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<WrapBoxProps\>.constructor

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

• **nativePtr**: [`WrapBox`](ue_ue.WrapBox.md)

#### Defined in

[react-umg/index.d.ts:892](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L892)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`WrapBoxProps`](../interfaces/react_umg.WrapBoxProps.md)\>

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
| `prevProps` | `Readonly`<[`WrapBoxProps`](../interfaces/react_umg.WrapBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`WrapBoxProps`](../interfaces/react_umg.WrapBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`WrapBoxProps`](../interfaces/react_umg.WrapBoxProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`WrapBoxProps`](../interfaces/react_umg.WrapBoxProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`WrapBoxProps`](../interfaces/react_umg.WrapBoxProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate

#### Defined in

node_modules/@types/react/index.d.ts:385
