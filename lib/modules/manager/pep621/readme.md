This manager supports updating dependencies inside `pyproject.toml` files.

In addition to standard dependencies, these toolsets are also supported:

- `pdm` (including `pdm.lock` files)
- `uv` (including `uv.lock` files)
- `hatch`

Available `depType`s:

- `project.dependencies`
- `project.optional-dependencies`
- `dependency-groups`
- `build-system.requires`
- `tool.pdm.dev-dependencies`
- `tool.uv.dev-dependencies`
- `tool.uv.sources`
- `tool.hatch.envs.<env-name>`
