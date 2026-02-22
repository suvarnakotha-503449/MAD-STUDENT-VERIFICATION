# MAD-STUDENT-VERIFICATION

$ cd /workspace/app/frontend
$ cd /workspace/app/frontend && pnpm run lint


> shadcnui@ lint /workspace/app/frontend
> eslint --quiet ./src

$ cd /workspace/app/frontend && pnpm run build


> shadcnui@ build /workspace/app/frontend
> vite build

vite v5.4.21 building for production...
transforming...
✓ 12 modules transformed.
x Build failed in 1.79s
error during build:
Could not resolve "./pages/NotFound" from "src/App.tsx"
file: /workspace/app/frontend/src/App.tsx
    at getRollupError (file:///workspace/app/frontend/node_modules/.pnpm/rollup@4.57.0/node_modules/rollup/dist/es/shared/parseAst.js:402:41)
    at error (file:///workspace/app/frontend/node_modules/.pnpm/rollup@4.57.0/node_modules/rollup/dist/es/shared/parseAst.js:398:42)
    at ModuleLoader.handleInvalidResolvedId (file:///workspace/app/frontend/node_modules/.pnpm/rollup@4.57.0/node_modules/rollup/dist/es/shared/node-entry.js:21684:24)
    at file:///workspace/app/frontend/node_modules/.pnpm/rollup@4.57.0/node_modules/rollup/dist/es/shared/node-entry.js:21644:26
 ELIFECYCLE  Command failed with exit code 1.
$ cd /workspace/app/frontend && pnpm run build


> shadcnui@ build /workspace/app/frontend
> vite build

vite v5.4.21 building for production...
transforming...
✓ 1718 modules transformed.
rendering chunks...
computing gzip size...
dist/index.html                          1.18 kB │ gzip:  0.50 kB
dist/assets/index-DUQ8v35_.css          64.12 kB │ gzip: 11.20 kB
dist/assets/react-vendor-Q6eICO6F.js     0.03 kB │ gzip:  0.05 kB
dist/assets/form-vendor-Q6eICO6F.js      0.03 kB │ gzip:  0.05 kB
dist/assets/router-vendor-DH5nl515.js   19.03 kB │ gzip:  7.25 kB
dist/assets/utils-vendor-BHmMMNF7.js    27.20 kB │ gzip:  8.62 kB
dist/assets/query-vendor-B0FA2nFn.js    27.81 kB │ gzip:  8.50 kB
dist/assets/index-DJd9t6Wp.js           62.32 kB │ gzip: 17.50 kB
dist/assets/ui-vendor-B-PWFn1Y.js      227.21 kB │ gzip: 74.00 kB
✓ built in 6.01s
