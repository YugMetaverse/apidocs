[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / PanelWidget

# Class: PanelWidget

[react-umg](../modules/react_umg.md).PanelWidget

## Hierarchy

- `Component`<[`PanelWidgetProps`](../interfaces/react_umg.PanelWidgetProps.md)\>

  ↳ **`PanelWidget`**

## Table of contents

### Constructors

- [constructor](react_umg.PanelWidget.md#constructor)

### Properties

- [context](react_umg.PanelWidget.md#context)
- [nativePtr](react_umg.PanelWidget.md#nativeptr)
- [props](react_umg.PanelWidget.md#props)
- [refs](react_umg.PanelWidget.md#refs)
- [state](react_umg.PanelWidget.md#state)

### Methods

- [componentDidMount](react_umg.PanelWidget.md#componentdidmount)
- [componentDidUpdate](react_umg.PanelWidget.md#componentdidupdate)
- [componentWillMount](react_umg.PanelWidget.md#componentwillmount)
- [componentWillReceiveProps](react_umg.PanelWidget.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.PanelWidget.md#componentwillunmount)
- [componentWillUpdate](react_umg.PanelWidget.md#componentwillupdate)
- [forceUpdate](react_umg.PanelWidget.md#forceupdate)
- [render](react_umg.PanelWidget.md#render)
- [setState](react_umg.PanelWidget.md#setstate)
- [shouldComponentUpdate](react_umg.PanelWidget.md#shouldcomponentupdate)

## Constructors

### constructor

• **new PanelWidget**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`PanelWidgetProps`](../interfaces/react_umg.PanelWidgetProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<PanelWidgetProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`PanelWidget`](ue_ue.PanelWidget.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`PanelWidgetProps`](../interfaces/react_umg.PanelWidgetProps.md)\>

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
| `prevProps` | `Readonly`<[`PanelWidgetProps`](../interfaces/react_umg.PanelWidgetProps.md)\> |
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
| `nextProps` | `Readonly`<[`PanelWidgetProps`](../interfaces/react_umg.PanelWidgetProps.md)\> |
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
| `nextProps` | `Readonly`<[`PanelWidgetProps`](../interfaces/react_umg.PanelWidgetProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`PanelWidgetProps`](../interfaces/react_umg.PanelWidgetProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`PanelWidgetProps`](../interfaces/react_umg.PanelWidgetProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
