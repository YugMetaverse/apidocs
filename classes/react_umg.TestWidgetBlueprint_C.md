[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / TestWidgetBlueprint\_C

# Class: TestWidgetBlueprint\_C

[react-umg](../modules/react_umg.md).TestWidgetBlueprint_C

## Hierarchy

- `Component`<[`TestWidgetBlueprint_CProps`](../interfaces/react_umg.TestWidgetBlueprint_CProps.md)\>

  ↳ **`TestWidgetBlueprint_C`**

## Table of contents

### Constructors

- [constructor](react_umg.TestWidgetBlueprint_C.md#constructor)

### Properties

- [context](react_umg.TestWidgetBlueprint_C.md#context)
- [nativePtr](react_umg.TestWidgetBlueprint_C.md#nativeptr)
- [props](react_umg.TestWidgetBlueprint_C.md#props)
- [refs](react_umg.TestWidgetBlueprint_C.md#refs)
- [state](react_umg.TestWidgetBlueprint_C.md#state)

### Methods

- [componentDidMount](react_umg.TestWidgetBlueprint_C.md#componentdidmount)
- [componentDidUpdate](react_umg.TestWidgetBlueprint_C.md#componentdidupdate)
- [componentWillMount](react_umg.TestWidgetBlueprint_C.md#componentwillmount)
- [componentWillReceiveProps](react_umg.TestWidgetBlueprint_C.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.TestWidgetBlueprint_C.md#componentwillunmount)
- [componentWillUpdate](react_umg.TestWidgetBlueprint_C.md#componentwillupdate)
- [forceUpdate](react_umg.TestWidgetBlueprint_C.md#forceupdate)
- [render](react_umg.TestWidgetBlueprint_C.md#render)
- [setState](react_umg.TestWidgetBlueprint_C.md#setstate)
- [shouldComponentUpdate](react_umg.TestWidgetBlueprint_C.md#shouldcomponentupdate)

## Constructors

### constructor

• **new TestWidgetBlueprint_C**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`TestWidgetBlueprint_CProps`](../interfaces/react_umg.TestWidgetBlueprint_CProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<TestWidgetBlueprint\_CProps\>.constructor

## Properties

### context

• **context**: `any`

#### Inherited from

React.Component.context

___

### nativePtr

• **nativePtr**: [`TestWidgetBlueprint_C`](ue_ue_bp.Game.StarterContent.TestWidgetBlueprint.TestWidgetBlueprint_C.md)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`TestWidgetBlueprint_CProps`](../interfaces/react_umg.TestWidgetBlueprint_CProps.md)\>

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
| `prevProps` | `Readonly`<[`TestWidgetBlueprint_CProps`](../interfaces/react_umg.TestWidgetBlueprint_CProps.md)\> |
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
| `nextProps` | `Readonly`<[`TestWidgetBlueprint_CProps`](../interfaces/react_umg.TestWidgetBlueprint_CProps.md)\> |
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
| `nextProps` | `Readonly`<[`TestWidgetBlueprint_CProps`](../interfaces/react_umg.TestWidgetBlueprint_CProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`TestWidgetBlueprint_CProps`](../interfaces/react_umg.TestWidgetBlueprint_CProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`TestWidgetBlueprint_CProps`](../interfaces/react_umg.TestWidgetBlueprint_CProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate
