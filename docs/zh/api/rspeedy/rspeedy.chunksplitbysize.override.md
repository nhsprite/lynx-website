<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@lynx-js/rspeedy](./rspeedy.md) &gt; [ChunkSplitBySize](./rspeedy.chunksplitbysize.md) &gt; [override](./rspeedy.chunksplitbysize.override.md)

## ChunkSplitBySize.override property

Custom Rspack chunk splitting config can be specified.

**Signature:**

```typescript
override?: Rspack.Configuration extends {
        optimization?: {
            splitChunks?: infer P;
        } | undefined;
    } ? P : never;
```
