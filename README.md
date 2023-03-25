# @tapjs

Workspace for node-tap development.

* [@tapjs/core](./src/core) Most of the basic moving parts
  of tap
* [@tapjs/test](./src/test) The plugin-ified `Test` class.

Run `npm run bootstrap` to build the `@tapjs/test` module with
the default set of plugins, so that the other libraries can
build properly.  (This only has to be done once.)
