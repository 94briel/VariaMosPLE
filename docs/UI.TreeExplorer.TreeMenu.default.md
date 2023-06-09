# Class: default

[UI/TreeExplorer/TreeMenu](../wiki/UI.TreeExplorer.TreeMenu).default

## Hierarchy

- `Component`<`Props`, `State`\>

  ↳ **`default`**

## Table of contents

### Constructors

- [constructor](../wiki/UI.TreeExplorer.TreeMenu.default#constructor)

### Properties

- [context](../wiki/UI.TreeExplorer.TreeMenu.default#context)
- [props](../wiki/UI.TreeExplorer.TreeMenu.default#props)
- [refs](../wiki/UI.TreeExplorer.TreeMenu.default#refs)
- [state](../wiki/UI.TreeExplorer.TreeMenu.default#state)
- [contextType](../wiki/UI.TreeExplorer.TreeMenu.default#contexttype)

### Methods

- [UNSAFE\_componentWillMount](../wiki/UI.TreeExplorer.TreeMenu.default#unsafe_componentwillmount)
- [UNSAFE\_componentWillReceiveProps](../wiki/UI.TreeExplorer.TreeMenu.default#unsafe_componentwillreceiveprops)
- [UNSAFE\_componentWillUpdate](../wiki/UI.TreeExplorer.TreeMenu.default#unsafe_componentwillupdate)
- [addNewAdaptation](../wiki/UI.TreeExplorer.TreeMenu.default#addnewadaptation)
- [addNewAdaptationModel](../wiki/UI.TreeExplorer.TreeMenu.default#addnewadaptationmodel)
- [addNewApplication](../wiki/UI.TreeExplorer.TreeMenu.default#addnewapplication)
- [addNewApplicationEModel](../wiki/UI.TreeExplorer.TreeMenu.default#addnewapplicationemodel)
- [addNewApplicationModel](../wiki/UI.TreeExplorer.TreeMenu.default#addnewapplicationmodel)
- [addNewDomainEModel](../wiki/UI.TreeExplorer.TreeMenu.default#addnewdomainemodel)
- [addNewEModel](../wiki/UI.TreeExplorer.TreeMenu.default#addnewemodel)
- [addNewFolder](../wiki/UI.TreeExplorer.TreeMenu.default#addnewfolder)
- [addNewProductLine](../wiki/UI.TreeExplorer.TreeMenu.default#addnewproductline)
- [callExternalFuntion](../wiki/UI.TreeExplorer.TreeMenu.default#callexternalfuntion)
- [componentDidCatch](../wiki/UI.TreeExplorer.TreeMenu.default#componentdidcatch)
- [componentDidMount](../wiki/UI.TreeExplorer.TreeMenu.default#componentdidmount)
- [componentDidUpdate](../wiki/UI.TreeExplorer.TreeMenu.default#componentdidupdate)
- [componentWillMount](../wiki/UI.TreeExplorer.TreeMenu.default#componentwillmount)
- [componentWillReceiveProps](../wiki/UI.TreeExplorer.TreeMenu.default#componentwillreceiveprops)
- [componentWillUnmount](../wiki/UI.TreeExplorer.TreeMenu.default#componentwillunmount)
- [componentWillUpdate](../wiki/UI.TreeExplorer.TreeMenu.default#componentwillupdate)
- [deleteItemProject](../wiki/UI.TreeExplorer.TreeMenu.default#deleteitemproject)
- [forceUpdate](../wiki/UI.TreeExplorer.TreeMenu.default#forceupdate)
- [getSnapshotBeforeUpdate](../wiki/UI.TreeExplorer.TreeMenu.default#getsnapshotbeforeupdate)
- [handleUpdateEditorText](../wiki/UI.TreeExplorer.TreeMenu.default#handleupdateeditortext)
- [handleUpdateNewSelected](../wiki/UI.TreeExplorer.TreeMenu.default#handleupdatenewselected)
- [onEnterModal](../wiki/UI.TreeExplorer.TreeMenu.default#onentermodal)
- [projectService\_addListener](../wiki/UI.TreeExplorer.TreeMenu.default#projectservice_addlistener)
- [removeHidden](../wiki/UI.TreeExplorer.TreeMenu.default#removehidden)
- [renameItemProject](../wiki/UI.TreeExplorer.TreeMenu.default#renameitemproject)
- [render](../wiki/UI.TreeExplorer.TreeMenu.default#render)
- [setState](../wiki/UI.TreeExplorer.TreeMenu.default#setstate)
- [shouldComponentUpdate](../wiki/UI.TreeExplorer.TreeMenu.default#shouldcomponentupdate)
- [updateModal](../wiki/UI.TreeExplorer.TreeMenu.default#updatemodal)
- [viewMenuTree\_addListener](../wiki/UI.TreeExplorer.TreeMenu.default#viewmenutree_addlistener)

## Constructors

### constructor

• **new default**(`props`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `any` |

#### Overrides

Component&lt;Props, State\&gt;.constructor

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:32](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L32)

## Properties

### context

• **context**: `any`

If using the new style context, re-declare this in your class to be the
`React.ContextType` of your `static contextType`.
Should be used with type annotation or static contextType.

```ts
static contextType = MyContext
// For TS pre-3.7:
context!: React.ContextType<typeof MyContext>
// For TS 3.7 and above:
declare context: React.ContextType<typeof MyContext>
```

**`See`**

https://reactjs.org/docs/context.html

#### Inherited from

Component.context

#### Defined in

node_modules/@types/react/index.d.ts:479

___

### props

• `Readonly` **props**: `Readonly`<`Props`\> & `Readonly`<{ `children?`: `ReactNode`  }\>

#### Inherited from

Component.props

#### Defined in

node_modules/@types/react/index.d.ts:504

___

### refs

• **refs**: `Object`

**`Deprecated`**

https://reactjs.org/docs/refs-and-the-dom.html#legacy-api-string-refs

#### Index signature

▪ [key: `string`]: `ReactInstance`

#### Inherited from

Component.refs

#### Defined in

node_modules/@types/react/index.d.ts:510

___

### state

• **state**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `menu` | `boolean` |
| `modalInputText` | `string` |
| `modalInputValue` | `string` |
| `modalTittle` | `string` |
| `newSelected` | `string` |
| `optionAllowAdaptation` | `boolean` |
| `optionAllowApplication` | `boolean` |
| `optionAllowDelete` | `boolean` |
| `optionAllowEFunctions` | `boolean` |
| `optionAllowModelAdaptation` | `boolean` |
| `optionAllowModelApplication` | `boolean` |
| `optionAllowModelDomain` | `boolean` |
| `optionAllowModelEnable` | `boolean` |
| `optionAllowProductLine` | `boolean` |
| `optionAllowRename` | `boolean` |

#### Overrides

Component.state

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:14](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L14)

___

### contextType

▪ `Static` `Optional` **contextType**: `Context`<`any`\>

If set, `this.context` will be set at runtime to the current value of the given Context.

Usage:

```ts
type MyContext = number
const Ctx = React.createContext<MyContext>(0)

class Foo extends React.Component {
  static contextType = Ctx
  context!: React.ContextType<typeof Ctx>
  render () {
    return <>My context's value: {this.context}</>;
  }
}
```

**`See`**

https://reactjs.org/docs/context.html#classcontexttype

#### Inherited from

Component.contextType

#### Defined in

node_modules/@types/react/index.d.ts:461

## Methods

### UNSAFE\_componentWillMount

▸ `Optional` **UNSAFE_componentWillMount**(): `void`

Called immediately before mounting occurs, and before `Component#render`.
Avoid introducing any side-effects or subscriptions in this method.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`Deprecated`**

16.3, use componentDidMount or the constructor instead

**`See`**

 - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#initializing-state
 - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

#### Returns

`void`

#### Inherited from

Component.UNSAFE\_componentWillMount

#### Defined in

node_modules/@types/react/index.d.ts:717

___

### UNSAFE\_componentWillReceiveProps

▸ `Optional` **UNSAFE_componentWillReceiveProps**(`nextProps`, `nextContext`): `void`

Called when the component may be receiving new props.
React may call this even if props have not changed, so be sure to compare new and existing
props if you only want to handle changes.

Calling `Component#setState` generally does not trigger this method.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`Deprecated`**

16.3, use static getDerivedStateFromProps instead

**`See`**

 - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#updating-state-based-on-props
 - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | `Readonly`<`Props`\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Inherited from

Component.UNSAFE\_componentWillReceiveProps

#### Defined in

node_modules/@types/react/index.d.ts:749

___

### UNSAFE\_componentWillUpdate

▸ `Optional` **UNSAFE_componentWillUpdate**(`nextProps`, `nextState`, `nextContext`): `void`

Called immediately before rendering when new props or state is received. Not called for the initial render.

Note: You cannot call `Component#setState` here.

This method will not stop working in React 17.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`Deprecated`**

16.3, use getSnapshotBeforeUpdate instead

**`See`**

 - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#reading-dom-properties-before-an-update
 - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | `Readonly`<`Props`\> |
| `nextState` | `Readonly`<`State`\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Inherited from

Component.UNSAFE\_componentWillUpdate

#### Defined in

node_modules/@types/react/index.d.ts:777

___

### addNewAdaptation

▸ **addNewAdaptation**(`adaptationName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `adaptationName` | `string` |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:269](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L269)

___

### addNewAdaptationModel

▸ **addNewAdaptationModel**(`languageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `languageName` | `string` |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:346](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L346)

___

### addNewApplication

▸ **addNewApplication**(`applicationName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `applicationName` | `string` |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:260](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L260)

___

### addNewApplicationEModel

▸ **addNewApplicationEModel**(`languageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `languageName` | `string` |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:324](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L324)

___

### addNewApplicationModel

▸ **addNewApplicationModel**(`languageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `languageName` | `string` |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:337](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L337)

___

### addNewDomainEModel

▸ **addNewDomainEModel**(`languageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `languageName` | `string` |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:311](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L311)

___

### addNewEModel

▸ **addNewEModel**(`language`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `language` | [`Language`](../wiki/Domain.ProductLineEngineering.Entities.Language.Language) |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:278](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L278)

___

### addNewFolder

▸ **addNewFolder**(`event`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `any` |

#### Returns

`boolean`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:219](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L219)

___

### addNewProductLine

▸ **addNewProductLine**(`productLineName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `productLineName` | `string` |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:251](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L251)

___

### callExternalFuntion

▸ **callExternalFuntion**(`efunction`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `efunction` | [`ExternalFuntion`](../wiki/Domain.ProductLineEngineering.Entities.ExternalFuntion.ExternalFuntion) |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:58](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L58)

___

### componentDidCatch

▸ `Optional` **componentDidCatch**(`error`, `errorInfo`): `void`

Catches exceptions generated in descendant components. Unhandled exceptions will cause
the entire component tree to unmount.

#### Parameters

| Name | Type |
| :------ | :------ |
| `error` | `Error` |
| `errorInfo` | `ErrorInfo` |

#### Returns

`void`

#### Inherited from

Component.componentDidCatch

#### Defined in

node_modules/@types/react/index.d.ts:646

___

### componentDidMount

▸ **componentDidMount**(): `void`

#### Returns

`void`

#### Overrides

Component.componentDidMount

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:156](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L156)

___

### componentDidUpdate

▸ `Optional` **componentDidUpdate**(`prevProps`, `prevState`, `snapshot?`): `void`

Called immediately after updating occurs. Not called for the initial render.

The snapshot is only present if getSnapshotBeforeUpdate is present and returns non-null.

#### Parameters

| Name | Type |
| :------ | :------ |
| `prevProps` | `Readonly`<`Props`\> |
| `prevState` | `Readonly`<`State`\> |
| `snapshot?` | `any` |

#### Returns

`void`

#### Inherited from

Component.componentDidUpdate

#### Defined in

node_modules/@types/react/index.d.ts:688

___

### componentWillMount

▸ `Optional` **componentWillMount**(): `void`

Called immediately before mounting occurs, and before `Component#render`.
Avoid introducing any side-effects or subscriptions in this method.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`Deprecated`**

16.3, use componentDidMount or the constructor instead; will stop working in React 17

**`See`**

 - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#initializing-state
 - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

#### Returns

`void`

#### Inherited from

Component.componentWillMount

#### Defined in

node_modules/@types/react/index.d.ts:703

___

### componentWillReceiveProps

▸ `Optional` **componentWillReceiveProps**(`nextProps`, `nextContext`): `void`

Called when the component may be receiving new props.
React may call this even if props have not changed, so be sure to compare new and existing
props if you only want to handle changes.

Calling `Component#setState` generally does not trigger this method.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`Deprecated`**

16.3, use static getDerivedStateFromProps instead; will stop working in React 17

**`See`**

 - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#updating-state-based-on-props
 - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | `Readonly`<`Props`\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Inherited from

Component.componentWillReceiveProps

#### Defined in

node_modules/@types/react/index.d.ts:732

___

### componentWillUnmount

▸ `Optional` **componentWillUnmount**(): `void`

Called immediately before a component is destroyed. Perform any necessary cleanup in this method, such as
cancelled network requests, or cleaning up any DOM elements created in `componentDidMount`.

#### Returns

`void`

#### Inherited from

Component.componentWillUnmount

#### Defined in

node_modules/@types/react/index.d.ts:641

___

### componentWillUpdate

▸ `Optional` **componentWillUpdate**(`nextProps`, `nextState`, `nextContext`): `void`

Called immediately before rendering when new props or state is received. Not called for the initial render.

Note: You cannot call `Component#setState` here.

Note: the presence of getSnapshotBeforeUpdate or getDerivedStateFromProps
prevents this from being invoked.

**`Deprecated`**

16.3, use getSnapshotBeforeUpdate instead; will stop working in React 17

**`See`**

 - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#reading-dom-properties-before-an-update
 - https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html#gradual-migration-path

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | `Readonly`<`Props`\> |
| `nextState` | `Readonly`<`State`\> |
| `nextContext` | `any` |

#### Returns

`void`

#### Inherited from

Component.componentWillUpdate

#### Defined in

node_modules/@types/react/index.d.ts:762

___

### deleteItemProject

▸ **deleteItemProject**(): `void`

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:66](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L66)

___

### forceUpdate

▸ **forceUpdate**(`callback?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback?` | () => `void` |

#### Returns

`void`

#### Inherited from

Component.forceUpdate

#### Defined in

node_modules/@types/react/index.d.ts:496

___

### getSnapshotBeforeUpdate

▸ `Optional` **getSnapshotBeforeUpdate**(`prevProps`, `prevState`): `any`

Runs before React applies the result of `render` to the document, and
returns an object to be given to componentDidUpdate. Useful for saving
things such as scroll position before `render` causes changes to it.

Note: the presence of getSnapshotBeforeUpdate prevents any of the deprecated
lifecycle events from running.

#### Parameters

| Name | Type |
| :------ | :------ |
| `prevProps` | `Readonly`<`Props`\> |
| `prevState` | `Readonly`<`State`\> |

#### Returns

`any`

#### Inherited from

Component.getSnapshotBeforeUpdate

#### Defined in

node_modules/@types/react/index.d.ts:682

___

### handleUpdateEditorText

▸ **handleUpdateEditorText**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `any` |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:169](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L169)

___

### handleUpdateNewSelected

▸ **handleUpdateNewSelected**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `any` |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:175](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L175)

___

### onEnterModal

▸ **onEnterModal**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `any` |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:62](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L62)

___

### projectService\_addListener

▸ **projectService_addListener**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `any` |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:214](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L214)

___

### removeHidden

▸ **removeHidden**(): `void`

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:141](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L141)

___

### renameItemProject

▸ **renameItemProject**(`newName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `newName` | `string` |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:70](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L70)

___

### render

▸ **render**(): `Element`

#### Returns

`Element`

#### Overrides

Component.render

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:355](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L355)

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
| `state` | `State` \| (`prevState`: `Readonly`<`State`\>, `props`: `Readonly`<`Props`\>) => `State` \| `Pick`<`State`, `K`\> \| `Pick`<`State`, `K`\> |
| `callback?` | () => `void` |

#### Returns

`void`

#### Inherited from

Component.setState

#### Defined in

node_modules/@types/react/index.d.ts:491

___

### shouldComponentUpdate

▸ `Optional` **shouldComponentUpdate**(`nextProps`, `nextState`, `nextContext`): `boolean`

Called to determine whether the change in props and state should trigger a re-render.

`Component` always returns true.
`PureComponent` implements a shallow comparison on props and state and returns true if any
props or states have changed.

If false is returned, `Component#render`, `componentWillUpdate`
and `componentDidUpdate` will not be called.

#### Parameters

| Name | Type |
| :------ | :------ |
| `nextProps` | `Readonly`<`Props`\> |
| `nextState` | `Readonly`<`State`\> |
| `nextContext` | `any` |

#### Returns

`boolean`

#### Inherited from

Component.shouldComponentUpdate

#### Defined in

node_modules/@types/react/index.d.ts:636

___

### updateModal

▸ **updateModal**(`eventId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventId` | `string` |

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:179](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L179)

___

### viewMenuTree\_addListener

▸ **viewMenuTree_addListener**(): `void`

#### Returns

`void`

#### Defined in

[src/UI/TreeExplorer/TreeMenu.tsx:74](https://github.com/94briel/VariaMosPLE/blob/0611efd/src/UI/TreeExplorer/TreeMenu.tsx#L74)