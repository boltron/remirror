<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@remirror/core](./core.md) &gt; [ExtensionManager](./core.extensionmanager.md) &gt; [create](./core.extensionmanager.create.md)

## ExtensionManager.create() method

A static method for creating a new extension manager.

<b>Signature:</b>

```typescript
static create<GFlexibleList extends FlexibleExtension[]>(prioritizedExtensions: GFlexibleList): ExtensionManager<import("./extension-types").InferFlexibleExtension<GFlexibleList[number]>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  prioritizedExtensions | <code>GFlexibleList</code> |  |

<b>Returns:</b>

`ExtensionManager<import("./extension-types").InferFlexibleExtension<GFlexibleList[number]>>`
