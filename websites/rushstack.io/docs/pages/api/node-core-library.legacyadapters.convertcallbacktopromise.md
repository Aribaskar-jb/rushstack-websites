---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [LegacyAdapters](./node-core-library.legacyadapters.md) &gt; [convertCallbackToPromise](./node-core-library.legacyadapters.convertcallbacktopromise.md)

## LegacyAdapters.convertCallbackToPromise() method

This function wraps a function with a callback in a promise.

<b>Signature:</b>

```typescript
static convertCallbackToPromise<TResult, TError>(fn: (cb: LegacyCallback<TResult, TError>) => void): Promise<TResult>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  fn | (cb: [LegacyCallback](./node-core-library.legacycallback.md) &lt;TResult, TError&gt;) =&gt; void |  |

<b>Returns:</b>

Promise&lt;TResult&gt;
