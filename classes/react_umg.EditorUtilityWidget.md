[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / EditorUtilityWidget

# Class: EditorUtilityWidget

[react-umg](../modules/react_umg.md).EditorUtilityWidget

## Hierarchy

- `Component`<[`EditorUtilityWidgetProps`](../interfaces/react_umg.EditorUtilityWidgetProps.md)\>

  ↳ **`EditorUtilityWidget`**

## Table of contents

### Constructors

- [constructor](react_umg.EditorUtilityWidget.md#constructor)

### Properties

- [context](react_umg.EditorUtilityWidget.md#context)
- [nativePtr](react_umg.EditorUtilityWidget.md#nativeptr)
- [props](react_umg.EditorUtilityWidget.md#props)
- [refs](react_umg.EditorUtilityWidget.md#refs)
- [state](react_umg.EditorUtilityWidget.md#state)

### Methods

- [componentDidMount](react_umg.EditorUtilityWidget.md#componentdidmount)
- [componentDidUpdate](react_umg.EditorUtilityWidget.md#componentdidupdate)
- [componentWillMount](react_umg.EditorUtilityWidget.md#componentwillmount)
- [componentWillReceiveProps](react_umg.EditorUtilityWidget.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.EditorUtilityWidget.md#componentwillunmount)
- [componentWillUpdate](react_umg.EditorUtilityWidget.md#componentwillupdate)
- [forceUpdate](react_umg.EditorUtilityWidget.md#forceupdate)
- [render](react_umg.EditorUtilityWidget.md#render)
- [setState](react_umg.EditorUtilityWidget.md#setstate)
- [shouldComponentUpdate](react_umg.EditorUtilityWidget.md#shouldcomponentupdate)

## Constructors

### constructor

• **new EditorUtilityWidget**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`EditorUtilityWidgetProps`](../interfaces/react_umg.EditorUtilityWidgetProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<EditorUtilityWidgetProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`EditorUtilityWidget`](ue_ue.EditorUtilityWidget.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`EditorUtilityWidgetProps`](../interfaces/react_umg.EditorUtilityWidgetProps.md)\>

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
| `prevProps` | `Readonly`<[`EditorUtilityWidgetProps`](../interfaces/react_umg.EditorUtilityWidgetProps.md)\> |
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
| `nextProps` | `Readonly`<[`EditorUtilityWidgetProps`](../interfaces/react_umg.EditorUtilityWidgetProps.md)\> |
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
| `nextProps` | `Readonly`<[`EditorUtilityWidgetProps`](../interfaces/react_umg.EditorUtilityWidgetProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`EditorUtilityWidgetProps`](../interfaces/react_umg.EditorUtilityWidgetProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`EditorUtilityWidgetProps`](../interfaces/react_umg.EditorUtilityWidgetProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
