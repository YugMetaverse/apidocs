[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / BackgroundBlur

# Class: BackgroundBlur

[react-umg](../modules/react_umg.md).BackgroundBlur

## Hierarchy

- `Component`<[`BackgroundBlurProps`](../interfaces/react_umg.BackgroundBlurProps.md)\>

  ↳ **`BackgroundBlur`**

## Table of contents

### Constructors

- [constructor](react_umg.BackgroundBlur.md#constructor)

### Properties

- [context](react_umg.BackgroundBlur.md#context)
- [nativePtr](react_umg.BackgroundBlur.md#nativeptr)
- [props](react_umg.BackgroundBlur.md#props)
- [refs](react_umg.BackgroundBlur.md#refs)
- [state](react_umg.BackgroundBlur.md#state)

### Methods

- [componentDidMount](react_umg.BackgroundBlur.md#componentdidmount)
- [componentDidUpdate](react_umg.BackgroundBlur.md#componentdidupdate)
- [componentWillMount](react_umg.BackgroundBlur.md#componentwillmount)
- [componentWillReceiveProps](react_umg.BackgroundBlur.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.BackgroundBlur.md#componentwillunmount)
- [componentWillUpdate](react_umg.BackgroundBlur.md#componentwillupdate)
- [forceUpdate](react_umg.BackgroundBlur.md#forceupdate)
- [render](react_umg.BackgroundBlur.md#render)
- [setState](react_umg.BackgroundBlur.md#setstate)
- [shouldComponentUpdate](react_umg.BackgroundBlur.md#shouldcomponentupdate)

## Constructors

### constructor

• **new BackgroundBlur**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`BackgroundBlurProps`](../interfaces/react_umg.BackgroundBlurProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<BackgroundBlurProps\>.constructor

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

• **nativePtr**: [`BackgroundBlur`](ue_ue.BackgroundBlur.md)

#### Defined in

[react-umg/index.d.ts:227](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L227)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`BackgroundBlurProps`](../interfaces/react_umg.BackgroundBlurProps.md)\>

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
| `prevProps` | `Readonly`<[`BackgroundBlurProps`](../interfaces/react_umg.BackgroundBlurProps.md)\> |
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
| `nextProps` | `Readonly`<[`BackgroundBlurProps`](../interfaces/react_umg.BackgroundBlurProps.md)\> |
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
| `nextProps` | `Readonly`<[`BackgroundBlurProps`](../interfaces/react_umg.BackgroundBlurProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`BackgroundBlurProps`](../interfaces/react_umg.BackgroundBlurProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`BackgroundBlurProps`](../interfaces/react_umg.BackgroundBlurProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate

#### Defined in

node_modules/@types/react/index.d.ts:385
