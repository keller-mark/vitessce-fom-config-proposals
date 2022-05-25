# vitessce-fom-config-proposals

This repository is meant to manually convert existing Vitessce configs to corresponding upgraded configs under the proposed feature-observation support (basically how they would look at the point when [#1128](https://github.com/vitessce/vitessce/issues/1128) can be closed).
While the upgrading will ultimately occur automatically, it may be a useful exercise to manually convert them and explore the diffs.

The files with `.debug.json` suffixes have been obtained by adding the `debug=true` URL parameter to ensure that we are doing these comparisons both before and after view config initialization.

Existing configs will be on the `main` branch.
Proposed configs will be on the `fom` branch to facilitate diffing with `main`.

[Compare](https://github.com/keller-mark/vitessce-fom-config-proposals/compare/main...fom)

Here I will not try to [break apart the spatial layers](https://github.com/vitessce/vitessce/issues/830) as I think that can be proposed/tackled independently.