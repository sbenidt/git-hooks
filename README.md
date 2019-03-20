Storage repo for some useful git hooks

------------------------------------------

To use these hooks, place them in .git/hooks and remove the ".*" from their filenames
i.e. rename pre-commit.disablecommits to pre-commit

Alternatively, multiple pre-commit.* hooks could be placed in .git/hooks and could be controlled
from a single pre-commit executable.
i.e. a text file structured as follows

```
./pre-commit.disablecommits
./pre-commit.rununittests
./pre-commit.runlinter
```
