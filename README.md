# Prebuilt binaries for the swc project


## dbg-swc


Using dbg-swc to debug size issue of your next.js app:

1. Download one from the releases page
2. Rename it to `dbg-swc` and add it to your `PATH`.
3. Install `terser`, globally or locally.

e.g. `yarn global add terser` or `yarn add -D terser` will both work.

4. `dbg-swc minify next check-size`  in your next.js app