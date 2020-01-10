<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@remirror/core-extensions](./core-extensions.md) &gt; [PositionTrackerExtension](./core-extensions.positiontrackerextension.md) &gt; [helpers](./core-extensions.positiontrackerextension.helpers.md)

## PositionTrackerExtension.helpers() method

<b>Signature:</b>

```typescript
helpers({ getState }: ExtensionManagerParams): {
        addPositionTracker: ({ pos, id }: AddPositionTrackerParams, tr?: import("prosemirror-state").Transaction<import("@remirror/core").EditorSchema<string, string>>) => import("prosemirror-state").Transaction<any> | undefined;
        removePositionTracker: ({ id }: RemovePositionTrackerParams, tr?: import("prosemirror-state").Transaction<import("@remirror/core").EditorSchema<string, string>>) => import("prosemirror-state").Transaction<any> | undefined;
        clearPositionTrackers: (tr?: Transaction<any>) => import("prosemirror-state").Transaction<any> | undefined;
        findPositionTracker: (id: unknown) => number | undefined;
        findAllPositionTrackers: () => Record<string, number>;
    };
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  { getState } | <code>ExtensionManagerParams</code> |  |

<b>Returns:</b>

`{
        addPositionTracker: ({ pos, id }: AddPositionTrackerParams, tr?: import("prosemirror-state").Transaction<import("@remirror/core").EditorSchema<string, string>>) => import("prosemirror-state").Transaction<any> | undefined;
        removePositionTracker: ({ id }: RemovePositionTrackerParams, tr?: import("prosemirror-state").Transaction<import("@remirror/core").EditorSchema<string, string>>) => import("prosemirror-state").Transaction<any> | undefined;
        clearPositionTrackers: (tr?: Transaction<any>) => import("prosemirror-state").Transaction<any> | undefined;
        findPositionTracker: (id: unknown) => number | undefined;
        findAllPositionTrackers: () => Record<string, number>;
    }`
