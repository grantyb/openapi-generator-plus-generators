# @openapi-generator-plus/typescript-fetch-node-client-generator

## 1.8.2

### Patch Changes

- Updated dependencies [c8cea0e]
  - @openapi-generator-plus/handlebars-templates@1.11.2
  - @openapi-generator-plus/typescript-generator-common@1.12.1
  - @openapi-generator-plus/typescript-fetch-client-generator@1.12.1

## 1.8.1

### Patch Changes

- Updated dependencies [f97a924]
  - @openapi-generator-plus/typescript-fetch-client-generator@1.12.0

## 1.8.0

### Minor Changes

- 366ada5: Add `enumMemberStyle` option with new `preserve` option

  The actual naming of the enum members can be really important. We default to the old behaviour, which is to name the enum members according
  to the preferred constant style of the language being generated, but we now add an option to try to preserve the enum member names from the
  API spec. Preserving is important if you use the enum member names in code such as by serializing them or matching them by their string names,
  e.g. Java's `EnumType.valueOf(String)`.

### Patch Changes

- 601553e: Update core
- Updated dependencies [366ada5]
- Updated dependencies [601553e]
  - @openapi-generator-plus/typescript-fetch-client-generator@1.11.0
  - @openapi-generator-plus/typescript-generator-common@1.12.0
  - @openapi-generator-plus/handlebars-templates@1.11.1
  - @openapi-generator-plus/generator-common@1.7.1

## 1.7.2

### Patch Changes

- Updated dependencies [8c59015]
  - @openapi-generator-plus/handlebars-templates@1.11.0
  - @openapi-generator-plus/typescript-generator-common@1.11.2
  - @openapi-generator-plus/typescript-fetch-client-generator@1.10.2

## 1.7.1

### Patch Changes

- Updated dependencies [8b4824a]
  - @openapi-generator-plus/handlebars-templates@1.10.0
  - @openapi-generator-plus/typescript-generator-common@1.11.1
  - @openapi-generator-plus/typescript-fetch-client-generator@1.10.1

## 1.7.0

### Minor Changes

- 382b02c: Bump core version and now explicitly depend upon core

### Patch Changes

- Updated dependencies [382b02c]
  - @openapi-generator-plus/typescript-fetch-client-generator@1.10.0
  - @openapi-generator-plus/handlebars-templates@1.9.0
  - @openapi-generator-plus/typescript-generator-common@1.11.0
  - @openapi-generator-plus/generator-common@1.7.0

## 1.6.1

### Patch Changes

- Updated dependencies [2685ee7]
  - @openapi-generator-plus/generator-common@1.6.1
  - @openapi-generator-plus/handlebars-templates@1.8.1
  - @openapi-generator-plus/typescript-generator-common@1.10.1
  - @openapi-generator-plus/typescript-fetch-client-generator@1.9.1

## 1.6.0

### Minor Changes

- 5b78af2: Upgrade core

### Patch Changes

- Updated dependencies [e52907f]
- Updated dependencies [f5080b5]
- Updated dependencies [dfae89b]
- Updated dependencies [50f5d88]
- Updated dependencies [820892f]
- Updated dependencies [5b78af2]
- Updated dependencies [e1d7fa3]
- Updated dependencies [976d656]
  - @openapi-generator-plus/handlebars-templates@1.8.0
  - @openapi-generator-plus/typescript-fetch-client-generator@1.9.0
  - @openapi-generator-plus/typescript-generator-common@1.10.0
  - @openapi-generator-plus/generator-common@1.6.0

## 1.5.0

### Minor Changes

- 9e1dc23: Update upstream

### Patch Changes

- Updated dependencies [9e1dc23]
- Updated dependencies [3363813]
  - @openapi-generator-plus/typescript-fetch-client-generator@1.8.0
  - @openapi-generator-plus/handlebars-templates@1.7.0
  - @openapi-generator-plus/typescript-generator-common@1.9.0
  - @openapi-generator-plus/generator-common@1.5.0

## 1.4.2

### Patch Changes

- Updated dependencies [4b9c50f]
  - @openapi-generator-plus/handlebars-templates@1.6.0
  - @openapi-generator-plus/typescript-generator-common@1.8.2
  - @openapi-generator-plus/typescript-fetch-client-generator@1.7.2

## 1.4.1

### Patch Changes

- Updated dependencies [df4a78f]
  - @openapi-generator-plus/handlebars-templates@1.5.1
  - @openapi-generator-plus/typescript-generator-common@1.8.1
  - @openapi-generator-plus/typescript-fetch-client-generator@1.7.1

## 1.4.0

### Minor Changes

- 18ff6da: Support new FILE schema type

### Patch Changes

- 506c9be: Use pnpm 9 and workspace uris
- a5c7d64: Update templates for changes to multipart file properties to no longer contain metadata generated in core. If we want to bring back metadata in a generator template we'll need to add a specific FILE type to store that.
- 5790781: Add CodegenContent type checking Handlebars helpers
- 2f86851: Update openapi-generator-plus upstream
- Updated dependencies [506c9be]
- Updated dependencies [18ff6da]
- Updated dependencies [5c51b1d]
- Updated dependencies [a5c7d64]
- Updated dependencies [6d43eca]
- Updated dependencies [5790781]
- Updated dependencies [2f86851]
  - @openapi-generator-plus/typescript-fetch-client-generator@1.7.0
  - @openapi-generator-plus/handlebars-templates@1.5.0
  - @openapi-generator-plus/typescript-generator-common@1.8.0
  - @openapi-generator-plus/generator-common@1.4.1

## 1.3.1

### Patch Changes

- Updated dependencies [b8188524]
  - @openapi-generator-plus/typescript-generator-common@1.7.1
  - @openapi-generator-plus/typescript-fetch-client-generator@1.6.1

## 1.3.0

### Minor Changes

- 26c8e2bd: Fix handling of catch-all responses

### Patch Changes

- Updated dependencies [26c8e2bd]
  - @openapi-generator-plus/typescript-fetch-client-generator@1.6.0
  - @openapi-generator-plus/handlebars-templates@1.4.0
  - @openapi-generator-plus/typescript-generator-common@1.7.0
  - @openapi-generator-plus/generator-common@1.4.0

## 1.2.5

### Patch Changes

- bc8647d6: Update core
- Updated dependencies [bc8647d6]
  - @openapi-generator-plus/typescript-fetch-client-generator@1.5.6
  - @openapi-generator-plus/handlebars-templates@1.3.5
  - @openapi-generator-plus/typescript-generator-common@1.6.5
  - @openapi-generator-plus/generator-common@1.3.9

## 1.2.4

### Patch Changes

- 9b87ba44: Update core
- Updated dependencies [9b87ba44]
  - @openapi-generator-plus/typescript-fetch-client-generator@1.5.5
  - @openapi-generator-plus/handlebars-templates@1.3.4
  - @openapi-generator-plus/typescript-generator-common@1.6.4
  - @openapi-generator-plus/generator-common@1.3.8

## 1.2.3

### Patch Changes

- cc2bb308: Update core types
- Updated dependencies [cc2bb308]
  - @openapi-generator-plus/typescript-fetch-client-generator@1.5.4
  - @openapi-generator-plus/handlebars-templates@1.3.3
  - @openapi-generator-plus/typescript-generator-common@1.6.3
  - @openapi-generator-plus/generator-common@1.3.7

## 1.2.2

### Patch Changes

- 81de680: Update to latest core types
- Updated dependencies [81de680]
  - @openapi-generator-plus/typescript-fetch-client-generator@1.5.3
  - @openapi-generator-plus/handlebars-templates@1.3.2
  - @openapi-generator-plus/typescript-generator-common@1.6.2
  - @openapi-generator-plus/generator-common@1.3.6

## 1.2.1

### Patch Changes

- d41da8d: Upgrade core types
- b6d16d9: Update dependencies
- Updated dependencies [d41da8d]
- Updated dependencies [b6d16d9]
- Updated dependencies [1f8b503]
  - @openapi-generator-plus/typescript-fetch-client-generator@1.5.2
  - @openapi-generator-plus/handlebars-templates@1.3.1
  - @openapi-generator-plus/typescript-generator-common@1.6.1
  - @openapi-generator-plus/generator-common@1.3.5

## 1.2.0

### Minor Changes

- 8c9c533: Update third party dependencies

### Patch Changes

- Updated dependencies [59c2ca9]
- Updated dependencies [8c9c533]
  - @openapi-generator-plus/generator-common@1.3.4
  - @openapi-generator-plus/handlebars-templates@1.3.0
  - @openapi-generator-plus/typescript-generator-common@1.6.0
  - @openapi-generator-plus/typescript-fetch-client-generator@1.5.1

## 1.1.6

### Patch Changes

- Updated dependencies [a5561e1]
- Updated dependencies [958a0a8]
  - @openapi-generator-plus/typescript-generator-common@1.5.4
  - @openapi-generator-plus/typescript-fetch-client-generator@1.5.0

## 1.1.5

### Patch Changes

- da518bb: Update core types
- Updated dependencies [da518bb]
  - @openapi-generator-plus/typescript-fetch-client-generator@1.4.3
  - @openapi-generator-plus/handlebars-templates@1.2.4
  - @openapi-generator-plus/typescript-generator-common@1.5.3
  - @openapi-generator-plus/generator-common@1.3.3

## 1.1.4

### Patch Changes

- Updated dependencies [5601ab5]
  - @openapi-generator-plus/handlebars-templates@1.2.3
  - @openapi-generator-plus/typescript-fetch-client-generator@1.4.2
  - @openapi-generator-plus/typescript-generator-common@1.5.2

## 1.1.3

### Patch Changes

- 9732cd1: Update core to 2.3.0
- Updated dependencies [9732cd1]
- Updated dependencies [bd75c7d]
  - @openapi-generator-plus/generator-common@1.3.2
  - @openapi-generator-plus/handlebars-templates@1.2.2
  - @openapi-generator-plus/typescript-generator-common@1.5.1
  - @openapi-generator-plus/typescript-fetch-client-generator@1.4.1

## 1.1.2

### Patch Changes

- Updated dependencies [7477d77]
  - @openapi-generator-plus/typescript-generator-common@1.5.0
  - @openapi-generator-plus/typescript-fetch-client-generator@1.4.0

## 1.1.1

### Patch Changes

- 691f556: Update core to 2.2.0
- 75f9ee3: Include DOM lib for missing functions
- Updated dependencies [691f556]
- Updated dependencies [84e4151]
  - @openapi-generator-plus/generator-common@1.3.1
  - @openapi-generator-plus/handlebars-templates@1.2.1
  - @openapi-generator-plus/typescript-generator-common@1.4.0
  - @openapi-generator-plus/typescript-fetch-client-generator@1.3.1

## 1.1.0

### Minor Changes

- db48add: Upgrade core types to 2.1.0 to return the `initialValue` function removed incorrectly in 2.0.0

### Patch Changes

- Updated dependencies [02405ff]
- Updated dependencies [db48add]
  - @openapi-generator-plus/typescript-generator-common@1.3.0
  - @openapi-generator-plus/generator-common@1.3.0
  - @openapi-generator-plus/handlebars-templates@1.2.0
  - @openapi-generator-plus/typescript-fetch-client-generator@1.3.0

## 1.0.5

### Patch Changes

- 19a8994: Update @openapi-generator-plus/core to 2.0.0

  _Note_ Please check the changelog for Java generators for breaking changes to the default values in generated model classes.

- Updated dependencies [19a8994]
- Updated dependencies [0664881]
- Updated dependencies [87bd6b5]
  - @openapi-generator-plus/generator-common@1.2.0
  - @openapi-generator-plus/handlebars-templates@1.1.4
  - @openapi-generator-plus/typescript-generator-common@1.2.0
  - @openapi-generator-plus/typescript-fetch-client-generator@1.2.1

## 1.0.4

### Patch Changes

- Updated dependencies [2842518]
- Updated dependencies [072fe50]
  - @openapi-generator-plus/typescript-generator-common@1.1.0
  - @openapi-generator-plus/typescript-fetch-client-generator@1.2.0
  - @openapi-generator-plus/handlebars-templates@1.1.3

## 1.0.3

### Patch Changes

- 4ea4845: Tidy dependencies on @openapi-generator-plus core modules
- cab735b: Upgrade dependencies
- Updated dependencies [4ea4845]
- Updated dependencies [cab735b]
  - @openapi-generator-plus/generator-common@1.1.2
  - @openapi-generator-plus/handlebars-templates@1.1.2
  - @openapi-generator-plus/typescript-generator-common@1.0.2
  - @openapi-generator-plus/typescript-fetch-client-generator@1.1.2

## 1.0.2

### Patch Changes

- cb18c75: Upgrade dependencies
- Updated dependencies [be034fb]
- Updated dependencies [53b8a63]
- Updated dependencies [cb18c75]
  - @openapi-generator-plus/handlebars-templates@1.1.0
  - @openapi-generator-plus/typescript-fetch-client-generator@1.1.1

## 1.0.1

### Patch Changes

- b46fa0c: Use pnpm to install for speed-up, and to build to avoid using TypeScript API
- Updated dependencies [555ee39]
- Updated dependencies [b46fa0c]
  - @openapi-generator-plus/typescript-fetch-client-generator@1.1.0

## 1.0.0

### Major Changes

- 8717cfb: First major release

### Patch Changes

- Updated dependencies [63e4795]
- Updated dependencies [8717cfb]
  - @openapi-generator-plus/handlebars-templates@1.0.0
  - @openapi-generator-plus/typescript-generator-common@1.0.0
  - @openapi-generator-plus/typescript-fetch-client-generator@3.0.0

## 0.4.15

### Patch Changes

- Updated dependencies [7c0f5ec]
- Updated dependencies [b5f3bf9]
- Updated dependencies [1109255]
  - @openapi-generator-plus/typescript-generator-common@0.25.7
  - @openapi-generator-plus/typescript-fetch-client-generator@0.35.0
  - @openapi-generator-plus/handlebars-templates@0.27.1

## 0.4.14

### Patch Changes

- Updated dependencies [3fc7ccf]
  - @openapi-generator-plus/typescript-fetch-client-generator@0.34.0

## 0.4.13

### Patch Changes

- Updated dependencies [8793a55]
- Updated dependencies [94ff264]
- Updated dependencies [29f4f58]
- Updated dependencies [9056504]
  - @openapi-generator-plus/typescript-fetch-client-generator@0.33.0

## 0.4.12

### Patch Changes

- Updated dependencies [23171d5]
  - @openapi-generator-plus/handlebars-templates@0.27.0
  - @openapi-generator-plus/typescript-generator-common@0.25.6
  - @openapi-generator-plus/typescript-fetch-client-generator@0.32.1

## 0.4.11

### Patch Changes

- Updated dependencies [3b2b515]
- Updated dependencies [807775a]
- Updated dependencies [0cc86ee]
  - @openapi-generator-plus/typescript-fetch-client-generator@0.32.0
  - @openapi-generator-plus/typescript-generator-common@0.25.5

## 0.4.10

### Patch Changes

- 2e840bb: Standardise on OpenAPI Generator Plus instead of OpenAPI Generator+
- Updated dependencies [2e840bb]
  - @openapi-generator-plus/typescript-generator-common@0.25.4
  - @openapi-generator-plus/typescript-fetch-client-generator@0.31.5

## 0.4.9

### Patch Changes

- 28e4e3b: Standardise terminology from generator module to generator template
- Updated dependencies [28e4e3b]
  - @openapi-generator-plus/typescript-fetch-client-generator@0.31.4

## 0.4.8

### Patch Changes

- b45576a: Update package.json metadata to include better homepage URLs
- Updated dependencies [b45576a]
  - @openapi-generator-plus/handlebars-templates@0.26.1
  - @openapi-generator-plus/typescript-generator-common@0.25.3
  - @openapi-generator-plus/typescript-fetch-client-generator@0.31.3

## 0.4.7

### Patch Changes

- Updated dependencies [630ba24]
- Updated dependencies [25a8ab6]
- Updated dependencies [0cfd306]
  - @openapi-generator-plus/handlebars-templates@0.26.0
  - @openapi-generator-plus/typescript-generator-common@0.25.2
  - @openapi-generator-plus/typescript-fetch-client-generator@0.31.2

## 0.4.6

### Patch Changes

- Updated dependencies [e72fec6]
- Updated dependencies [9afa386]
- Updated dependencies [ad19364]
- Updated dependencies [a2ae651]
- Updated dependencies [c1da0ee]
  - @openapi-generator-plus/handlebars-templates@0.25.0
  - @openapi-generator-plus/typescript-generator-common@0.25.1
  - @openapi-generator-plus/typescript-fetch-client-generator@0.31.1

## 0.4.5

### Patch Changes

- Updated dependencies [ff4ee4f]
- Updated dependencies [10aeb32]
- Updated dependencies [9c992d5]
- Updated dependencies [11b32c0]
  - @openapi-generator-plus/handlebars-templates@0.24.0
  - @openapi-generator-plus/typescript-generator-common@0.25.0
  - @openapi-generator-plus/typescript-fetch-client-generator@0.31.0

## 0.4.4

### Patch Changes

- Updated dependencies [26e7810]
- Updated dependencies [135a732]
  - @openapi-generator-plus/handlebars-templates@0.23.0
  - @openapi-generator-plus/typescript-generator-common@0.24.0
  - @openapi-generator-plus/typescript-fetch-client-generator@0.30.0

## 0.4.3

### Patch Changes

- Updated dependencies [fa0f593]
- Updated dependencies [5d3a6fe]
  - @openapi-generator-plus/handlebars-templates@0.22.0
  - @openapi-generator-plus/typescript-generator-common@0.23.0
  - @openapi-generator-plus/typescript-fetch-client-generator@0.29.2

## 0.4.2

### Patch Changes

- Updated dependencies [b5ad150]
  - @openapi-generator-plus/handlebars-templates@0.21.0
  - @openapi-generator-plus/typescript-generator-common@0.22.5
  - @openapi-generator-plus/typescript-fetch-client-generator@0.29.1

## 0.4.1

### Patch Changes

- Updated dependencies [cb453ba]
- Updated dependencies [6c1300d]
- Updated dependencies [83a47f4]
  - @openapi-generator-plus/typescript-fetch-client-generator@0.29.0
  - @openapi-generator-plus/handlebars-templates@0.20.1

## 0.4.0

### Minor Changes

- 419828e: Improve parameter serialization including removing x-serialize-nested-as-json vendor extension and making that the default (as that's what editor.swagger.io) does, fixing serialization of header parameters

### Patch Changes

- Updated dependencies [419828e]
- Updated dependencies [742a47d]
- Updated dependencies [15d56ca]
  - @openapi-generator-plus/typescript-fetch-client-generator@0.28.0

## 0.3.2

### Patch Changes

- Updated dependencies [6f81fa5]
- Updated dependencies [37478df]
- Updated dependencies [c34292b]
- Updated dependencies [cdc41e6]
- Updated dependencies [38d4257]
  - @openapi-generator-plus/handlebars-templates@0.20.0
  - @openapi-generator-plus/typescript-fetch-client-generator@0.27.0
  - @openapi-generator-plus/typescript-generator-common@0.22.4

## 0.3.1

### Patch Changes

- Updated dependencies [a6146f6]
  - @openapi-generator-plus/typescript-fetch-client-generator@0.26.0

## 0.3.0

### Minor Changes

- ee03854: Core update

### Patch Changes

- Updated dependencies [7a86b15]
- Updated dependencies [7c50b17]
- Updated dependencies [ee03854]
  - @openapi-generator-plus/handlebars-templates@0.19.0
  - @openapi-generator-plus/typescript-fetch-client-generator@0.25.1
  - @openapi-generator-plus/typescript-generator-common@0.22.2

## 0.2.3

### Patch Changes

- Updated dependencies [9f6ef06]
- Updated dependencies [9dbd093]
- Updated dependencies [83cde2b]
  - @openapi-generator-plus/typescript-fetch-client-generator@0.25.0

## 0.2.2

### Patch Changes

- Updated dependencies [a84fd09]
- Updated dependencies [04d59a7]
- Updated dependencies [68cc337]
- Updated dependencies [60f75a9]
- Updated dependencies [bab3808]
  - @openapi-generator-plus/handlebars-templates@0.18.0
  - @openapi-generator-plus/typescript-generator-common@0.22.1
  - @openapi-generator-plus/typescript-fetch-client-generator@0.24.0

## 0.2.1

### Patch Changes

- a65b3ce: Upgrade dependencies
- Updated dependencies [a65b3ce]
  - @openapi-generator-plus/handlebars-templates@0.17.1
  - @openapi-generator-plus/typescript-fetch-client-generator@0.23.1

## 0.2.0

### Minor Changes

- 86c4e5d: Support the allOf, anyOf, oneOf handling changes in core.

### Patch Changes

- 05d3c03: Changed from lerna to pnpm for monorepo management, and changesets for releases and versioning
- Updated dependencies [05d3c03]
- Updated dependencies [86c4e5d]
  - @openapi-generator-plus/handlebars-templates@0.17.0
  - @openapi-generator-plus/typescript-generator-common@0.22.0
  - @openapi-generator-plus/typescript-fetch-client-generator@0.23.0
