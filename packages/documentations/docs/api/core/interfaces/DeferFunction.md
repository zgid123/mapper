---
id: "DeferFunction"
title: "Interface: DeferFunction<TSource, TDestination, TSelectorReturn>"
sidebar_label: "DeferFunction"
sidebar_position: 0
custom_edit_url: null
---

## Type parameters

| Name | Type |
| :------ | :------ |
| `TSource` | extends [`Dictionary`](../modules.md#dictionary)<`TSource`\> |
| `TDestination` | extends [`Dictionary`](../modules.md#dictionary)<`TDestination`\> |
| `TSelectorReturn` | [`SelectorReturn`](../modules.md#selectorreturn)<`TDestination`\> |

## Callable

### DeferFunction

▸ **DeferFunction**(`source`): [`MemberMapReturnNoDefer`](../modules.md#membermapreturnnodefer)<`TSource`, `TDestination`, `TSelectorReturn`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `source` | `TSource` |

#### Returns

[`MemberMapReturnNoDefer`](../modules.md#membermapreturnnodefer)<`TSource`, `TDestination`, `TSelectorReturn`\>

#### Defined in

[lib/types.ts:296](https://github.com/nartc/mapper/blob/e4b240d/packages/core/src/lib/types.ts#L296)