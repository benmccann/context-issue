# Test context-issue

See the issue:

```bash
git clone https://github.com/enyo/context-issue.git
cd context-issue/svelte-kit-app
npm install
npm run dev
```

This will fail with:

> Function called outside component initialization

As you can see, the imported library only uses `setContext()` in the top level
function.

## Fix

Change the import in `src/routes/index.svelte` to a relative import and it works
again.
