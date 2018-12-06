# 1.0.7

-   Move the imports of the `oyaml` module directly into the methods that use it.

# 1.0.6

-   Fix a bug: check if subset partial config contains `chapters` section correctly.
-   Inherit the class `Cli` from `BaseCli`, not from `Cliar`.

# 1.0.5

-   Do not use `yaml` alias for `oyaml` module to prevent possible influence of this overriding on other parts of code.

# 1.0.4

-   Tidy up command line arguments one more time.

# 1.0.3

-   Tidy up command line arguments.

# 1.0.2

-   Fix a bug with object names.

# 1.0.1

-   Parse YAML fairly. Merge config files recursively.
