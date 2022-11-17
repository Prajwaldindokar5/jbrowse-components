---
id: linearcomparativedisplay
title: LinearComparativeDisplay
toplevel: true
---

Note: this document is automatically generated from mobx-state-tree objects in
our source code. See [Core concepts and intro to pluggable
elements](/docs/developer_guide/) for more info

## Docs

### LinearComparativeDisplay - Properties

#### property: type

```js
// type signature
ISimpleType<"LinearComparativeDisplay">
// code
type: types.literal('LinearComparativeDisplay')
```

#### property: configuration

```js
// type signature
ITypeUnion<any, any, any>
// code
configuration: ConfigurationReference(configSchema)
```

#### property: height

```js
// type signature
number
// code
height: 100
```

### LinearComparativeDisplay - Getters

#### getter: rendererTypeName

```js
// type
any
```

#### getter: renderProps

```js
// type
() => { rpcDriverName: string; displayModel: { id: string; type: "LinearComparativeDisplay"; rpcDriverName: string; configuration: any; height: number; } & NonEmptyObject & ... 4 more ... & IStateTreeNode<...>; highResolutionScaling: number; }
```

### LinearComparativeDisplay - Actions

#### action: setLoading

controlled by a reaction

```js
// type signature
setLoading: (abortController: AbortController) => void
```

#### action: setMessage

controlled by a reaction

```js
// type signature
setMessage: (messageText: string) => void
```

#### action: setRendered

controlled by a reaction

```js
// type signature
setRendered: (args?: { data: unknown; reactElement: React.ReactElement; renderingComponent: React.Component; }) => void
```

#### action: setError

controlled by a reaction

```js
// type signature
setError: (error: unknown) => void
```