---
'@sveltejs/kit': patch
---

post_install.js script doesn't successfuly create .svelte-kit directory in monorepositories that use glob patterns to enumerate their workspaces. Using globby allows us to support both fully enumerated workspace directories and glob patterns.
