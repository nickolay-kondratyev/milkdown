I'm on a fork and either publish this to NPM repository in my own scope.

Here are the changes. Only the plugin listener have changed.
What steps do I need to do just to build and publish a plugin listener? And then we also want to modify the package that's in my own scope and put a version such as fix on top of it so it's clear that this is a fixed version.


```
 .changeset/fix-listener-debounce.md           |  5 +++
 e2e/src/plugin-listener/main.ts               |  8 ++++
 e2e/tests/plugin/listener.spec.ts             | 26 +++++++++++++
 packages/plugins/plugin-listener/src/index.ts | 55 +++++++++++++++------------
 4 files changed, 69 insertions(+), 25 deletions(-)
 ```

My username is `nickolaykondratyev`
 on npm
