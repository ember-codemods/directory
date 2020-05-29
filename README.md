# Ember.js codemods

A directory of ember-codemods

| Codemod | Description | Area | Requirement |
| --- | --- | --- | --- |
| [ember-3x-codemods](https://github.com/ember-codemods/ember-3x-codemods) | A collection of codemods for adressing deprecations introduced in Ember 3.x | General | <small>ember 3.x (varies)</small>
| [ember-tracked-properties-codemod](https://github.com/ember-codemods/ember-tracked-properties-codemod) | Transforms your app code to use @tracked properties | General | ember 3.13+ |
| [es5-getter-ember-codemod](https://github.com/ember-codemods/es5-getter-ember-codemod) | Transforms `get`s to native property access | General | ember 3.1+ |
| [ember-angle-brackets-codemod](https://github.com/ember-codemods/ember-angle-brackets-codemod) | Transforms your templates to use angle bracket syntax | Templates | ember? |
| [ember-component-template-colocation-migrator](https://github.com/ember-codemods/ember-component-template-colocation-migrator) | Migrates classical components to colocated components | Components | ember? |
| [ember-native-class-codemod](https://github.com/ember-codemods/ember-native-class-codemod) | Transforms your app code to use the native classes and decorators | General | ember? |
| [ember-mocha-codemods](https://github.com/ember-codemods/ember-mocha-codemods) | Transforms your Mocha test modules to use the `setup*` helper family | Testing | ember 2.4+, ember-mocha? |
| [ember-qunit-codemod](https://github.com/ember-codemods/ember-qunit-codemod) | Transforms your QUnit test modules to use the `setup*` helper family | Testing | ember 2.4+, ember-qunit? |
| [ember-test-helpers-codemod](https://github.com/ember-codemods/ember-test-helpers-codemod) | Transforms your test code to use `@ember/test-helpers` | Testing | ember 2.4+ |
| [ember-computed-getter-codemod](https://github.com/ember-codemods/ember-computed-getter-codemod) | Transforms computed properties to use split `get` and `set` functions | General | ember? | 
| [ember-modules-codemod](https://github.com/ember-codemods/ember-modules-codemod) | Transforms your code to use the [module API](https://github.com/emberjs/rfcs/pull/176) | General | ember? |
| [ember-memory-leaks-codemod](https://github.com/ember-codemods/ember-memory-leaks-codemod) | Identifies and fixes common memory leaks in Ember apps | General | |
| [ember-cli-htmlbars-inline-precompile-codemod](https://github.com/ember-codemods/ember-cli-htmlbars-inline-precompile-codemod) | Transforms imports to avoid using `htmlbars-inline-precompile` | General | |
| [tagless-ember-components-codemod](https://github.com/ember-codemods/tagless-ember-components-codemod) | Transforms your components to use `tagName: ''` | Components | |
| [ember-no-implicit-this-codemod](https://github.com/ember-codemods/ember-no-implicit-this-codemod) | Transforms your templates to use explicit `this` | Templates | |
| [ember-test-onerror-codemod](https://github.com/ember-codemods/ember-test-onerror-codemod) | Transforms your test code to avoid using Ember.onerror | Testing | |

## Addons

| Codemod | Description |
| --- | --- |
| [ember-data-codemod](https://github.com/ember-codemods/ember-data-codemod) | A collection of codemods for [ember-data](https://github.com/emberjs/data) |
| [ember-sinon-sandbox-codemod](https://github.com/ember-codemods/ember-sinon-sandbox-codemod) | A collection of codemods for [sinon](https://github.com/sinonjs/sinon) |
| [power-select-deprecation-codemod](https://github.com/ember-codemods/power-select-deprecation-codemod) | A collection of codemods for [ember-power-select](https://github.com/cibernox/ember-power-select) |
