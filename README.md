# opamx

1. Add `$(opamx where)` to your `$PATH`
2. Available commands:
  ```
  opamx install [package]* # install given packages (upgrade all installed if no packages given)
  opamx remove {package}+  # remove given packages
  opamx update             # update available packages information
  opamx where              # location where binaries are installed
  opamx list               # list installed packages
  opamx search ...         # search opam repository
  ```

This project is inspired by [pipx](https://github.com/pypa/pipx), [uvx](https://docs.astral.sh/uv/guides/tools/), [npx](https://docs.npmjs.com/cli/v11/commands/npx), and similars.
