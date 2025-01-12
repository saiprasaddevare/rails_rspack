# README

This is sample repo that uses jsbundling-rails to setup rspack as bundler.

What changes you will find.

- You will see rspack.config.js
- This uses `rspack --config rspack.config.js` to build your assets
- This has "@rspack/cli", "@rspack/core" as dependency.
- Gemfile includes `jsbundling-rails`, this is pointing to forked repo of jsbundling-rails. This contain the [PR](https://github.com/saiprasaddevare/jsbundling-rails/pull/1) that does all the rspack config. 
- Onces this PR gets approved and merged, you dont need this forked repo. You can use `jsbundling-rails` directly(The actual jsbundling-rails [repo](https://github.com/rails/jsbundling-rails) ).
- This `jsbundling-rails` will have command `rails javascript:install:rspack`.
