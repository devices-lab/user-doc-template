# user-doc-template
A template repository for user-facing documentation of hardware

See the latest instructions for how to use this package at: [https://devices-lab.github.io/user-doc-template/](https://devices-lab.github.io/user-doc-template/)

## Note

This template now does not by-default pull changes from the upstream package ( [https://devices-lab.github.io/user-doc-base/](https://devices-lab.github.io/user-doc-base/) ) - to get the latest style, assets, and layouts for your documentation, set the `syncChanges` option to `true`, like so: `await userDocBase(eleventyConfig, { inputDir: "src", syncChanges: false });` and re-run a build or the development server.

This will cause the base style to overwrite its old styles (and any changes you've made!) to bring them in-line with the latest version.
