[yug_typings](../README.md) / [Modules](../modules.md) / [react-umg](../modules/react_umg.md) / EditableText

# Class: EditableText

[react-umg](../modules/react_umg.md).EditableText

## Hierarchy

- `Component`<[`EditableTextProps`](../interfaces/react_umg.EditableTextProps.md)\>

  ↳ **`EditableText`**

## Table of contents

### Constructors

- [constructor](react_umg.EditableText.md#constructor)

### Properties

- [context](react_umg.EditableText.md#context)
- [nativePtr](react_umg.EditableText.md#nativeptr)
- [props](react_umg.EditableText.md#props)
- [refs](react_umg.EditableText.md#refs)
- [state](react_umg.EditableText.md#state)

### Methods

- [componentDidMount](react_umg.EditableText.md#componentdidmount)
- [componentDidUpdate](react_umg.EditableText.md#componentdidupdate)
- [componentWillMount](react_umg.EditableText.md#componentwillmount)
- [componentWillReceiveProps](react_umg.EditableText.md#componentwillreceiveprops)
- [componentWillUnmount](react_umg.EditableText.md#componentwillunmount)
- [componentWillUpdate](react_umg.EditableText.md#componentwillupdate)
- [forceUpdate](react_umg.EditableText.md#forceupdate)
- [render](react_umg.EditableText.md#render)
- [setState](react_umg.EditableText.md#setstate)
- [shouldComponentUpdate](react_umg.EditableText.md#shouldcomponentupdate)

## Constructors

### constructor

• **new EditableText**(`props?`, `context?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props?` | [`EditableTextProps`](../interfaces/react_umg.EditableTextProps.md) |
| `context?` | `any` |

#### Inherited from

React.Component<EditableTextProps\>.constructor

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

• **nativePtr**: [`EditableText`](ue_ue.EditableText.md)

#### Defined in

[react-umg/index.d.ts:384](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/react-umg/index.d.ts#L384)

___

### props

• **props**: `Readonly`<{ `children?`: `ReactNode`  }\> & `Readonly`<[`EditableTextProps`](../interfaces/react_umg.EditableTextProps.md)\>

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
| `prevProps` | `Readonly`<[`EditableTextProps`](../interfaces/react_umg.EditableTextProps.md)\> |
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
| `nextProps` | `Readonly`<[`EditableTextProps`](../interfaces/react_umg.EditableTextProps.md)\> |
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
| `nextProps` | `Readonly`<[`EditableTextProps`](../interfaces/react_umg.EditableTextProps.md)\> |
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
| `state` | {} \| (`prevState`: `Readonly`<{}\>, `props`: [`EditableTextProps`](../interfaces/react_umg.EditableTextProps.md)) => {} \| `Pick`<{}, `K`\> \| `Pick`<{}, `K`\> |
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
| `nextProps` | `Readonly`<[`EditableTextProps`](../interfaces/react_umg.EditableTextProps.md)\> |
| `nextState` | `Readonly`<{}\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

React.Component.shouldComponentUpdate

#### Defined in

node_modules/@types/react/index.d.ts:385