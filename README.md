# sketch-reference-files

> A store of automatically generated Sketch file JSON organised by document version and Sketch feature.

## Overview

Sketch documents are stored as ZIP archives containing JSON encoded data. The file format was
originally introduced in Sketch 43 and allows for better third-party integration. For example
generating, reading and modifying documents without opening them in Sketch.

In order to provide concrete examples of how different Sketch features are serialised into JSON this
repo maintains an archive of reference files.

It's published as an npm module to aid use cases that may involve importing these reference files as
test fixtures.

## Related projects

- [sketch-file-format](https://github.com/sketch-hq/sketch-file-format)

## Usage

### JavaScript

Add the npm module using `npm` or `yarn`

```sh
npm install @sketch-hq/sketch-reference-files
```

```js
import files from '@sketch-hq/sketch-reference-files'
```

The module exports reference file metadata and json contents for each supported document `version`.

```
[
  {
    document: 118,
    sketchVersions: ['55', '55.1'],
    files: [
      { id, name, description, data },
      ...
    ],
  },
  ...
]
```

### HTTP

The raw reference file JSON can be accessed over HTTP via predicable urls:

- https://unpkg.com/browse/@sketch-hq/sketch-reference-files@latest/files/

## Scripts

| Script              | Description                                                                                                                                                            |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| yarn download-apps  | Download and locally cache all Sketch app binaries needed to generate the files                                                                                        |
| yarn generate-files | Generate reference files into the `files/` folder. Existing reference files are skipped, so delete the `files/` folder if you need to generate everything from scratch |
| yarn build          | Builds the module entrypoint into the the `dist/` folder                                                                                                               |
| yarn update-readme  | Updates the tables in the "Browse" section of the readme automatically                                                                                                 |
| yarn release        | Tags the repo and updates the changelog and semver automatically based on commit history. You'll still need to push the changes and publish manually afterwards        |

## Browse

### Document 121

> Sketch versions: 59, 60

| Feature          | Document                                                                                                       | Pages                                                                                                  | Meta                                                                                                       | User                                                                                                       |
| ---------------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| Empty            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/empty/document.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/empty/pages)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/empty/meta.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/empty/user.json)            |
| Groups           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/groups/document.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/groups/pages)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/groups/meta.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/groups/user.json)           |
| Images           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/images/document.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/images/pages)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/images/meta.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/images/user.json)           |
| Library styles   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/library-styles/document.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/library-styles/pages)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/library-styles/meta.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/library-styles/user.json)   |
| Library symbols  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/library-symbols/document.json)  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/library-symbols/pages)  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/library-symbols/meta.json)  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/library-symbols/user.json)  |
| Prototypes       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/prototypes/document.json)       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/prototypes/pages)       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/prototypes/meta.json)       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/prototypes/user.json)       |
| Shape paths      | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/shape-paths/document.json)      | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/shape-paths/pages)      | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/shape-paths/meta.json)      | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/shape-paths/user.json)      |
| Shapes           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/shapes/document.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/shapes/pages)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/shapes/meta.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/shapes/user.json)           |
| Symbol overrides | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/symbol-overrides/document.json) | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/symbol-overrides/pages) | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/symbol-overrides/meta.json) | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/symbol-overrides/user.json) |
| Symbols          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/symbols/document.json)          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/symbols/pages)          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/symbols/meta.json)          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/symbols/user.json)          |
| Text             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/text/document.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/text/pages)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/text/meta.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/text/user.json)             |
| Smart layout     | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/smart-layout/document.json)     | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/smart-layout/pages)     | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/smart-layout/meta.json)     | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/smart-layout/user.json)     |
| Blur             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/blur/document.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/blur/pages)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/blur/meta.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/blur/user.json)             |
| Slice            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/slice/document.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/slice/pages)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/slice/meta.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/slice/user.json)            |
| Export formats   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/export-formats/document.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/export-formats/pages)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/export-formats/meta.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/export-formats/user.json)   |
| Variable font    | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/variable-font/document.json)    | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/variable-font/pages)    | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/variable-font/meta.json)    | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/121/variable-font/user.json)    |

### Document 120

> Sketch versions: 58

| Feature          | Document                                                                                                       | Pages                                                                                                  | Meta                                                                                                       | User                                                                                                       |
| ---------------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| Empty            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/empty/document.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/empty/pages)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/empty/meta.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/empty/user.json)            |
| Groups           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/groups/document.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/groups/pages)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/groups/meta.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/groups/user.json)           |
| Images           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/images/document.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/images/pages)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/images/meta.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/images/user.json)           |
| Library styles   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/library-styles/document.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/library-styles/pages)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/library-styles/meta.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/library-styles/user.json)   |
| Library symbols  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/library-symbols/document.json)  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/library-symbols/pages)  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/library-symbols/meta.json)  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/library-symbols/user.json)  |
| Prototypes       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/prototypes/document.json)       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/prototypes/pages)       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/prototypes/meta.json)       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/prototypes/user.json)       |
| Shape paths      | -                                                                                                              | -                                                                                                      | -                                                                                                          | -                                                                                                          |
| Shapes           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/shapes/document.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/shapes/pages)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/shapes/meta.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/shapes/user.json)           |
| Symbol overrides | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/symbol-overrides/document.json) | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/symbol-overrides/pages) | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/symbol-overrides/meta.json) | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/symbol-overrides/user.json) |
| Symbols          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/symbols/document.json)          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/symbols/pages)          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/symbols/meta.json)          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/symbols/user.json)          |
| Text             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/text/document.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/text/pages)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/text/meta.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/text/user.json)             |
| Smart layout     | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/smart-layout/document.json)     | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/smart-layout/pages)     | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/smart-layout/meta.json)     | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/smart-layout/user.json)     |
| Blur             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/blur/document.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/blur/pages)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/blur/meta.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/blur/user.json)             |
| Slice            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/slice/document.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/slice/pages)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/slice/meta.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/slice/user.json)            |
| Export formats   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/export-formats/document.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/export-formats/pages)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/export-formats/meta.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/120/export-formats/user.json)   |
| Variable font    | -                                                                                                              | -                                                                                                      | -                                                                                                          | -                                                                                                          |

### Document 119

> Sketch versions: 55.2, 56, 56.1, 56.2, 56.3, 57, 57.1

| Feature          | Document                                                                                                       | Pages                                                                                                  | Meta                                                                                                       | User                                                                                                       |
| ---------------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| Empty            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/empty/document.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/empty/pages)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/empty/meta.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/empty/user.json)            |
| Groups           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/groups/document.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/groups/pages)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/groups/meta.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/groups/user.json)           |
| Images           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/images/document.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/images/pages)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/images/meta.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/images/user.json)           |
| Library styles   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/library-styles/document.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/library-styles/pages)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/library-styles/meta.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/library-styles/user.json)   |
| Library symbols  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/library-symbols/document.json)  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/library-symbols/pages)  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/library-symbols/meta.json)  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/library-symbols/user.json)  |
| Prototypes       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/prototypes/document.json)       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/prototypes/pages)       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/prototypes/meta.json)       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/prototypes/user.json)       |
| Shape paths      | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/shape-paths/document.json)      | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/shape-paths/pages)      | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/shape-paths/meta.json)      | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/shape-paths/user.json)      |
| Shapes           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/shapes/document.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/shapes/pages)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/shapes/meta.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/shapes/user.json)           |
| Symbol overrides | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/symbol-overrides/document.json) | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/symbol-overrides/pages) | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/symbol-overrides/meta.json) | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/symbol-overrides/user.json) |
| Symbols          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/symbols/document.json)          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/symbols/pages)          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/symbols/meta.json)          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/symbols/user.json)          |
| Text             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/text/document.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/text/pages)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/text/meta.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/text/user.json)             |
| Smart layout     | -                                                                                                              | -                                                                                                      | -                                                                                                          | -                                                                                                          |
| Blur             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/blur/document.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/blur/pages)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/blur/meta.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/blur/user.json)             |
| Slice            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/slice/document.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/slice/pages)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/slice/meta.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/slice/user.json)            |
| Export formats   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/export-formats/document.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/export-formats/pages)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/export-formats/meta.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/119/export-formats/user.json)   |
| Variable font    | -                                                                                                              | -                                                                                                      | -                                                                                                          | -                                                                                                          |

### Document 118

> Sketch versions: 55, 55.1

| Feature          | Document                                                                                                       | Pages                                                                                                  | Meta                                                                                                       | User                                                                                                       |
| ---------------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| Empty            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/empty/document.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/empty/pages)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/empty/meta.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/empty/user.json)            |
| Groups           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/groups/document.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/groups/pages)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/groups/meta.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/groups/user.json)           |
| Images           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/images/document.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/images/pages)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/images/meta.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/images/user.json)           |
| Library styles   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/library-styles/document.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/library-styles/pages)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/library-styles/meta.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/library-styles/user.json)   |
| Library symbols  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/library-symbols/document.json)  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/library-symbols/pages)  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/library-symbols/meta.json)  | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/library-symbols/user.json)  |
| Prototypes       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/prototypes/document.json)       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/prototypes/pages)       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/prototypes/meta.json)       | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/prototypes/user.json)       |
| Shape paths      | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/shape-paths/document.json)      | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/shape-paths/pages)      | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/shape-paths/meta.json)      | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/shape-paths/user.json)      |
| Shapes           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/shapes/document.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/shapes/pages)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/shapes/meta.json)           | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/shapes/user.json)           |
| Symbol overrides | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/symbol-overrides/document.json) | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/symbol-overrides/pages) | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/symbol-overrides/meta.json) | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/symbol-overrides/user.json) |
| Symbols          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/symbols/document.json)          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/symbols/pages)          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/symbols/meta.json)          | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/symbols/user.json)          |
| Text             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/text/document.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/text/pages)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/text/meta.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/text/user.json)             |
| Smart layout     | -                                                                                                              | -                                                                                                      | -                                                                                                          | -                                                                                                          |
| Blur             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/blur/document.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/blur/pages)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/blur/meta.json)             | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/blur/user.json)             |
| Slice            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/slice/document.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/slice/pages)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/slice/meta.json)            | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/slice/user.json)            |
| Export formats   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/export-formats/document.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/export-formats/pages)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/export-formats/meta.json)   | [🔗](https://github.com/sketch-hq/sketch-reference-files/tree/v2.0.0/files/118/export-formats/user.json)   |
| Variable font    | -                                                                                                              | -                                                                                                      | -                                                                                                          | -                                                                                                          |
