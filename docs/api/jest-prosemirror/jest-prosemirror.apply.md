<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [jest-prosemirror](./jest-prosemirror.md) &gt; [apply](./jest-prosemirror.apply.md)

## apply variable

Apply the command to the prosemirror node passed in.

Returns a tuple matching the following structure \[ bool =<!-- -->&gt; was the command successfully applied taggedDoc =<!-- -->&gt; the new doc as a result of the command state =<!-- -->&gt; The new editor state after applying the command \]

<b>Signature:</b>

```typescript
apply: <GSchema extends EditorSchema<string, string> = any>(taggedDoc: TaggedProsemirrorNode<GSchema>, command: CommandFunction<GSchema>, result?: TaggedProsemirrorNode<GSchema> | undefined) => ApplyReturn<GSchema>
```