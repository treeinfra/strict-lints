# Strict Lints

A shared linter rules template that enable as much linter options as possible.
All options except the ones already provided by the
[`flutter_lints`](https://pub.dev/packages/flutter_lints) package
are all listed inside the [`lib/strict_lints.yaml`](./lib/strict_lints.yaml)
source file. Even if the conflicted ones are only commented by remained.
You can refer to the [APIs](https://dart.dev/tools/linter-rules)
for more details.

## How to use

First, add it to your `dev_dependencies` in the `pubspec.yaml` manifest file.

```yaml
dev_dependencies:
  strict_lints: ^<version>
```

Then, include it inside your `analysis_options.yaml` file.

```yaml
include: package:strict_lints/strict_lints.yaml
```

## License and Contributors

This package is released under the MIT License.
(see the [license file](./LICENSE))
And all contributors are listed here.
(please at lease use a name in ASCII code and sort alphabetically).

- James Aprosail <aprosail@outlook.com>
