# V8 stalled top level await reproduction

Run

```sh
d8 repro-main.mjs
```

Which should result in a stalled top level await error

```text
/home/repro-main.mjs:2: Error: Top-level await promise never resolved
await run();
^
Error: Top-level await promise never resolved
```
