[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / WidgetSwitcher

# Class: WidgetSwitcher

[react-umg](../modules/react_umg.md).WidgetSwitcher

## Hierarchy

- `Component`<[`WidgetSwitcherProps`](../interfaces/react_umg.WidgetSwitcherProps.md)\>

  ↳ **`WidgetSwitcher`**

## Table of contents

### Constructors

- [constructor](react_umg.WidgetSwitcher.md#constructor)

### Properties

- [context](react_umg.WidgetSwitcher.md#context)
- [nativePtr](react_umg.WidgetSwitcher.md#nativeptr)
- [props](react_umg.WidgetSwitcher.md#props)
- [refs](react_umg.WidgetSwitcher.md#refs)
- [state](react_umg.WidgetSwitcher.md#state)

### Methods

- [componentDidMount](react_umg.WidgetSwitcher.md#componentdidmount)
- [componentDidUpdate](react_umg.WidgetSwitcher.md#componentdidupdate)
- [componentWillMount](react_umg.WidgetSwitcher.md#componentwillmount)
- [componentWillReceiveProps](react_umg.WidgetSwitcher.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.WidgetSwitcher.md#componentwillunmount)
- [componentWillUpdate](react_umg.WidgetSwitcher.md#componentwillupdate)
- [forceUpdate](react_umg.WidgetSwitcher.md#forceupdate)
- [render](react_umg.WidgetSwitcher.md#render)
- [setState](react_umg.WidgetSwitcher.md#setstate)
- [shouldComponentUpdate](react_umg.WidgetSwitcher.md#shouldcomponentupdate)

## Constructors

### constructor

• **new WidgetSwitcher**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`WidgetSwitcherProps`](../interfaces/react_umg.WidgetSwitcherProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<WidgetSwitcherProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`WidgetSwitcher`](ue_ue.WidgetSwitcher.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`WidgetSwitcherProps`](../interfaces/react_umg.WidgetSwitcherProps.md)\>

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
| `prevProps` | `Readonly`<[`WidgetSwitcherProps`](../interfaces/react_umg.WidgetSwitcherProps.md)\> |
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
| `nextProps` | `Readonly`<[`WidgetSwitcherProps`](../interfaces/react_umg.WidgetSwitcherProps.md)\> |
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
| `nextProps` | `Readonly`<[`WidgetSwitcherProps`](../interfaces/react_umg.WidgetSwitcherProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`WidgetSwitcherProps`](../interfaces/react_umg.WidgetSwitcherProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`WidgetSwitcherProps`](../interfaces/react_umg.WidgetSwitcherProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
