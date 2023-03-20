[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / CanvasPanel

# Class: CanvasPanel

[react-umg](../modules/react_umg.md).CanvasPanel

## Hierarchy

- `Component`<[`CanvasPanelProps`](../interfaces/react_umg.CanvasPanelProps.md)\>

  ↳ **`CanvasPanel`**

## Table of contents

### Constructors

- [constructor](react_umg.CanvasPanel.md#constructor)

### Properties

- [context](react_umg.CanvasPanel.md#context)
- [nativePtr](react_umg.CanvasPanel.md#nativeptr)
- [props](react_umg.CanvasPanel.md#props)
- [refs](react_umg.CanvasPanel.md#refs)
- [state](react_umg.CanvasPanel.md#state)

### Methods

- [componentDidMount](react_umg.CanvasPanel.md#componentdidmount)
- [componentDidUpdate](react_umg.CanvasPanel.md#componentdidupdate)
- [componentWillMount](react_umg.CanvasPanel.md#componentwillmount)
- [componentWillReceiveProps](react_umg.CanvasPanel.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.CanvasPanel.md#componentwillunmount)
- [componentWillUpdate](react_umg.CanvasPanel.md#componentwillupdate)
- [forceUpdate](react_umg.CanvasPanel.md#forceupdate)
- [render](react_umg.CanvasPanel.md#render)
- [setState](react_umg.CanvasPanel.md#setstate)
- [shouldComponentUpdate](react_umg.CanvasPanel.md#shouldcomponentupdate)

## Constructors

### constructor

• **new CanvasPanel**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`CanvasPanelProps`](../interfaces/react_umg.CanvasPanelProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<CanvasPanelProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`CanvasPanel`](ue_ue.CanvasPanel.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`CanvasPanelProps`](../interfaces/react_umg.CanvasPanelProps.md)\>

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
| `prevProps` | `Readonly`<[`CanvasPanelProps`](../interfaces/react_umg.CanvasPanelProps.md)\> |
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
| `nextProps` | `Readonly`<[`CanvasPanelProps`](../interfaces/react_umg.CanvasPanelProps.md)\> |
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
| `nextProps` | `Readonly`<[`CanvasPanelProps`](../interfaces/react_umg.CanvasPanelProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`CanvasPanelProps`](../interfaces/react_umg.CanvasPanelProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`CanvasPanelProps`](../interfaces/react_umg.CanvasPanelProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
