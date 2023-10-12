## Files

- **middleware.ts** -Proxy implementation file. This works as an [Edge Middleware](https://vercel.com/docs/functions/edge-middleware) of Vercel.
- **built-in-api-paths.js** - List of paths excluded from multi-tenancy path rewriting. This is a copy of the file generated when `yarn genApiPaths` run in [clubsx](https://github.com/dev-protocol/clubsx).
