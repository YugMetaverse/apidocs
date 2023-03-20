[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / ReactWidget

# Class: ReactWidget

[react-umg](../modules/react_umg.md).ReactWidget

## Hierarchy

- `Component`<[`ReactWidgetProps`](../interfaces/react_umg.ReactWidgetProps.md)\>

  ↳ **`ReactWidget`**

## Table of contents

### Constructors

- [constructor](react_umg.ReactWidget.md#constructor)

### Properties

- [context](react_umg.ReactWidget.md#context)
- [nativePtr](react_umg.ReactWidget.md#nativeptr)
- [props](react_umg.ReactWidget.md#props)
- [refs](react_umg.ReactWidget.md#refs)
- [state](react_umg.ReactWidget.md#state)

### Methods

- [componentDidMount](react_umg.ReactWidget.md#componentdidmount)
- [componentDidUpdate](react_umg.ReactWidget.md#componentdidupdate)
- [componentWillMount](react_umg.ReactWidget.md#componentwillmount)
- [componentWillReceiveProps](react_umg.ReactWidget.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.ReactWidget.md#componentwillunmount)
- [componentWillUpdate](react_umg.ReactWidget.md#componentwillupdate)
- [forceUpdate](react_umg.ReactWidget.md#forceupdate)
- [render](react_umg.ReactWidget.md#render)
- [setState](react_umg.ReactWidget.md#setstate)
- [shouldComponentUpdate](react_umg.ReactWidget.md#shouldcomponentupdate)

## Constructors

### constructor

• **new ReactWidget**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`ReactWidgetProps`](../interfaces/react_umg.ReactWidgetProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<ReactWidgetProps\>.constructor

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

• **nativePtr**: [`ReactWidget`](ue_ue.ReactWidget.md)

#### Defined in

[react-umg/index.d.ts:955](https://github.com/YugMetaverse/yug_typings/blob/25cad34/react-umg/index.d.ts#L955)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`ReactWidgetProps`](../interfaces/react_umg.ReactWidgetProps.md)\>

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
| `prevProps` | `Readonly`<[`ReactWidgetProps`](../interfaces/react_umg.ReactWidgetProps.md)\> |
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
| `nextProps` | `Readonly`<[`ReactWidgetProps`](../interfaces/react_umg.ReactWidgetProps.md)\> |
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
| `nextProps` | `Readonly`<[`ReactWidgetProps`](../interfaces/react_umg.ReactWidgetProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`ReactWidgetProps`](../interfaces/react_umg.ReactWidgetProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`ReactWidgetProps`](../interfaces/react_umg.ReactWidgetProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate

#### Defined in

node_modules/@types/react/index.d.ts:385
