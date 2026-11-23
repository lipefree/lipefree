# About me

My main interest is researching machine learning, but here I’m just trying to enjoy coding in a world dominated by AI.

## Open-source contribution

### [mlx](https://github.com/ml-explore/mlx)

Improved Python type definitions to match runtime behavior, fixing type-checking errors for valid API calls.

- Corrected the optional `step` argument in `arange`. [#4855](https://github.com/ml-explore/mlx/pull/4855)
- Fixed optional metadata typing and documentation for `save_gguf`. [#4942](https://github.com/ml-explore/mlx/pull/4942)
- Aligned positional and keyword argument signatures for `astype`, `roll`, `count_nonzero`, and `vecdot`. [#4944](https://github.com/ml-explore/mlx/pull/4944)

### [ty](https://github.com/astral-sh/ty)

Improved type analysis, diagnostic suggestions, and Python environment discovery.

- Added suggestions to use `self.<attribute>` when an unresolved name matches an instance attribute. [#18444](https://github.com/astral-sh/ruff/pull/18444)
- Recognized lambdas as `types.FunctionType` instances, enabling typed access to attributes such as `__code__`. [#18431](https://github.com/astral-sh/ruff/pull/18431)
- Added support for legacy generic annotations such as `typing.List[T]` and `typing.Dict[K, V]`. [#18404](https://github.com/astral-sh/ruff/pull/18404)
- Added diagnostics for functions whose implicit `None` return conflicts with their return annotation. [#18359](https://github.com/astral-sh/ruff/pull/18359)
- Added `async with` suggestions when asynchronous context managers are used in regular `with` statements. [#18299](https://github.com/astral-sh/ruff/pull/18299)
- Added Python environment discovery through `CONDA_PREFIX`, supporting Conda and Pixi environments. [#18267](https://github.com/astral-sh/ruff/pull/18267)
