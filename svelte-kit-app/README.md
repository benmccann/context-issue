# Test context-issue

See the issue:

```bash
git clone https://github.com/enyo/context-issue-repo.git
cd context-issue-repo
npm install
npm run dev
```

This will fail with:

> Function called outside component initialization

As you can see, the imported library only uses `setContext()` in the top level function.
