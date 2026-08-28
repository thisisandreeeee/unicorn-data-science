# Contributing

Contributions are welcome through a pull request or a [suggestion issue](https://github.com/thisisandreeeee/unicorn-data-science/issues/new).

## What to contribute

Add articles, papers, and guides that explain a difficult idea unusually well and remain useful over time. This repository does not collect software tools or libraries.

Add each resource as `[Title](URL)` under the most relevant heading in [README.md](./README.md). Do not edit the generated table of contents near the top of the file.

For a browser-only contribution, [edit README.md on GitHub](https://github.com/thisisandreeeee/unicorn-data-science/edit/master/README.md) and open a pull request. No local setup is required.

## Local setup

[Install uv](https://docs.astral.sh/uv/getting-started/installation/) if needed, then run:

```sh
uv sync
uv run pre-commit install --install-hooks
uv run pre-commit run --all-files
```

The pre-commit hook updates the table of contents. If it changes `README.md` during a commit, stage the file and commit again.

## Attribution

These contributing guidelines are adapted from [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted).
