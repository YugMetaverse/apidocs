[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / ScrollBar

# Class: ScrollBar

[react-umg](../modules/react_umg.md).ScrollBar

## Hierarchy

- `Component`<[`ScrollBarProps`](../interfaces/react_umg.ScrollBarProps.md)\>

  ↳ **`ScrollBar`**

## Table of contents

### Constructors

- [constructor](react_umg.ScrollBar.md#constructor)

### Properties

- [context](react_umg.ScrollBar.md#context)
- [nativePtr](react_umg.ScrollBar.md#nativeptr)
- [props](react_umg.ScrollBar.md#props)
- [refs](react_umg.ScrollBar.md#refs)
- [state](react_umg.ScrollBar.md#state)

### Methods

- [componentDidMount](react_umg.ScrollBar.md#componentdidmount)
- [componentDidUpdate](react_umg.ScrollBar.md#componentdidupdate)
- [componentWillMount](react_umg.ScrollBar.md#componentwillmount)
- [componentWillReceiveProps](react_umg.ScrollBar.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.ScrollBar.md#componentwillunmount)
- [componentWillUpdate](react_umg.ScrollBar.md#componentwillupdate)
- [forceUpdate](react_umg.ScrollBar.md#forceupdate)
- [render](react_umg.ScrollBar.md#render)
- [setState](react_umg.ScrollBar.md#setstate)
- [shouldComponentUpdate](react_umg.ScrollBar.md#shouldcomponentupdate)

## Constructors

### constructor

• **new ScrollBar**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`ScrollBarProps`](../interfaces/react_umg.ScrollBarProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<ScrollBarProps\>.constructor

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

• **nativePtr**: [`ScrollBar`](ue_ue.ScrollBar.md)

#### Defined in

[react-umg/index.d.ts:680](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L680)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`ScrollBarProps`](../interfaces/react_umg.ScrollBarProps.md)\>

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
| `prevProps` | `Readonly`<[`ScrollBarProps`](../interfaces/react_umg.ScrollBarProps.md)\> |
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
| `nextProps` | `Readonly`<[`ScrollBarProps`](../interfaces/react_umg.ScrollBarProps.md)\> |
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
| `nextProps` | `Readonly`<[`ScrollBarProps`](../interfaces/react_umg.ScrollBarProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`ScrollBarProps`](../interfaces/react_umg.ScrollBarProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`ScrollBarProps`](../interfaces/react_umg.ScrollBarProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate

#### Defined in

node_modules/@types/react/index.d.ts:385
