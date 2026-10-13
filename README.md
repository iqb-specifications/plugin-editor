[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

# TBA Plugin: Specification for Editor

In order to understand TBA Plugins, please go
to [TBA Plugins Introduction](https://iqb-specifications.github.io/concepts/plugins/)!

Read the spec here:
* [Html-Document](https://iqb-specifications.github.io/plugin-editor)
* [AsyncApi source yaml](editorapi.yaml). Please note: The data structure `variable-info` is [externally specified](https://iqb-specifications.github.io/variable-info/).

## For Contributors
This api is written as [async api](https://www.asyncapi.com/de) yaml file. After committing to main branch, a GitHub action is triggered to build the html page. Don't forget to update the version and the release notes in `README.md`. Then, create an release.

If you like to check the html page before committing to main branch, 

* have an npm/node.js-environment installed
* check out the repo
* run `npm install`
* run the `generate` script in package.json.

After that, you can check `docs/index.html` in a browser. This file will be ignored by git.
