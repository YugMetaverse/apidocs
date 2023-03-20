[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / Overlay

# Class: Overlay

[react-umg](../modules/react_umg.md).Overlay

## Hierarchy

- `Component`<[`OverlayProps`](../interfaces/react_umg.OverlayProps.md)\>

  ↳ **`Overlay`**

## Table of contents

### Constructors

- [constructor](react_umg.Overlay.md#constructor)

### Properties

- [context](react_umg.Overlay.md#context)
- [nativePtr](react_umg.Overlay.md#nativeptr)
- [props](react_umg.Overlay.md#props)
- [refs](react_umg.Overlay.md#refs)
- [state](react_umg.Overlay.md#state)

### Methods

- [componentDidMount](react_umg.Overlay.md#componentdidmount)
- [componentDidUpdate](react_umg.Overlay.md#componentdidupdate)
- [componentWillMount](react_umg.Overlay.md#componentwillmount)
- [componentWillReceiveProps](react_umg.Overlay.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.Overlay.md#componentwillunmount)
- [componentWillUpdate](react_umg.Overlay.md#componentwillupdate)
- [forceUpdate](react_umg.Overlay.md#forceupdate)
- [render](react_umg.Overlay.md#render)
- [setState](react_umg.Overlay.md#setstate)
- [shouldComponentUpdate](react_umg.Overlay.md#shouldcomponentupdate)

## Constructors

### constructor

• **new Overlay**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`OverlayProps`](../interfaces/react_umg.OverlayProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<OverlayProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`Overlay`](ue_ue.Overlay.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`OverlayProps`](../interfaces/react_umg.OverlayProps.md)\>

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
| `prevProps` | `Readonly`<[`OverlayProps`](../interfaces/react_umg.OverlayProps.md)\> |
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
| `nextProps` | `Readonly`<[`OverlayProps`](../interfaces/react_umg.OverlayProps.md)\> |
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
| `nextProps` | `Readonly`<[`OverlayProps`](../interfaces/react_umg.OverlayProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`OverlayProps`](../interfaces/react_umg.OverlayProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`OverlayProps`](../interfaces/react_umg.OverlayProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
