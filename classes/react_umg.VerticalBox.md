[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / VerticalBox

# Class: VerticalBox

[react-umg](../modules/react_umg.md).VerticalBox

## Hierarchy

- `Component`<[`VerticalBoxProps`](../interfaces/react_umg.VerticalBoxProps.md)\>

  ↳ **`VerticalBox`**

## Table of contents

### Constructors

- [constructor](react_umg.VerticalBox.md#constructor)

### Properties

- [context](react_umg.VerticalBox.md#context)
- [nativePtr](react_umg.VerticalBox.md#nativeptr)
- [props](react_umg.VerticalBox.md#props)
- [refs](react_umg.VerticalBox.md#refs)
- [state](react_umg.VerticalBox.md#state)

### Methods

- [componentDidMount](react_umg.VerticalBox.md#componentdidmount)
- [componentDidUpdate](react_umg.VerticalBox.md#componentdidupdate)
- [componentWillMount](react_umg.VerticalBox.md#componentwillmount)
- [componentWillReceiveProps](react_umg.VerticalBox.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.VerticalBox.md#componentwillunmount)
- [componentWillUpdate](react_umg.VerticalBox.md#componentwillupdate)
- [forceUpdate](react_umg.VerticalBox.md#forceupdate)
- [render](react_umg.VerticalBox.md#render)
- [setState](react_umg.VerticalBox.md#setstate)
- [shouldComponentUpdate](react_umg.VerticalBox.md#shouldcomponentupdate)

## Constructors

### constructor

• **new VerticalBox**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`VerticalBoxProps`](../interfaces/react_umg.VerticalBoxProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<VerticalBoxProps\>.constructor

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

• **nativePtr**: [`VerticalBox`](ue_ue.VerticalBox.md)

#### Defined in

[react-umg/index.d.ts:857](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L857)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`VerticalBoxProps`](../interfaces/react_umg.VerticalBoxProps.md)\>

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
| `prevProps` | `Readonly`<[`VerticalBoxProps`](../interfaces/react_umg.VerticalBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`VerticalBoxProps`](../interfaces/react_umg.VerticalBoxProps.md)\> |
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
| `nextProps` | `Readonly`<[`VerticalBoxProps`](../interfaces/react_umg.VerticalBoxProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`VerticalBoxProps`](../interfaces/react_umg.VerticalBoxProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`VerticalBoxProps`](../interfaces/react_umg.VerticalBoxProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate

#### Defined in

node_modules/@types/react/index.d.ts:385
