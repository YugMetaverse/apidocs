[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / TextBlock

# Class: TextBlock

[react-umg](../modules/react_umg.md).TextBlock

## Hierarchy

- `Component`<[`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)\>

  ↳ **`TextBlock`**

## Table of contents

### Constructors

- [constructor](react_umg.TextBlock.md#constructor)

### Properties

- [context](react_umg.TextBlock.md#context)
- [nativePtr](react_umg.TextBlock.md#nativeptr)
- [props](react_umg.TextBlock.md#props)
- [refs](react_umg.TextBlock.md#refs)
- [state](react_umg.TextBlock.md#state)

### Methods

- [componentDidMount](react_umg.TextBlock.md#componentdidmount)
- [componentDidUpdate](react_umg.TextBlock.md#componentdidupdate)
- [componentWillMount](react_umg.TextBlock.md#componentwillmount)
- [componentWillReceiveProps](react_umg.TextBlock.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.TextBlock.md#componentwillunmount)
- [componentWillUpdate](react_umg.TextBlock.md#componentwillupdate)
- [forceUpdate](react_umg.TextBlock.md#forceupdate)
- [render](react_umg.TextBlock.md#render)
- [setState](react_umg.TextBlock.md#setstate)
- [shouldComponentUpdate](react_umg.TextBlock.md#shouldcomponentupdate)

## Constructors

### constructor

• **new TextBlock**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<TextBlockProps\>.constructor

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

• **nativePtr**: [`TextBlock`](ue_ue.TextBlock.md)

#### Defined in

[react-umg/index.d.ts:810](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L810)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)\>

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
| `prevProps` | `Readonly`<[`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)\> |
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
| `nextProps` | `Readonly`<[`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)\> |
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
| `nextProps` | `Readonly`<[`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`TextBlockProps`](../interfaces/react_umg.TextBlockProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate

#### Defined in

node_modules/@types/react/index.d.ts:385
