# phase4

General information on FedRAMP 20x Phase 4.

## Local development

Zensical requires Python 3.11 or newer. The GitHub Pages build uses Python 3.13,
so Python 3.13 is recommended for local development.

Create and activate a virtual environment from the repository root:

```shell
python3.13 -m venv .venv
source .venv/bin/activate
```

Install the exact dependency versions used by the Pages build:

```shell
python -m pip install --require-hashes -r requirements.txt
```

Start a local development server with live reload:

```shell
zensical serve
```

The site is normally available at <http://127.0.0.1:8000/>. Edit Markdown files
under [`content/`](content/) and configuration in [`zensical.toml`](zensical.toml).

To create a production-like build in [`html/`](html/), run:

```shell
zensical build --clean
```

## Adding plugins or dependencies

Add the package and an exact version to [`requirements.in`](requirements.in).
For example:

```text
some-zensical-plugin==1.2.3
```

Regenerate the hashed lock file after installing `uv`:

```shell
python -m pip install uv
uv pip compile requirements.in \
  --python-version 3.13 \
  --python-platform x86_64-manylinux_2_17 \
  --generate-hashes \
  --output-file requirements.txt
```

Configure the plugin in [`zensical.toml`](zensical.toml) according to its
documentation. Commit both `requirements.in` and the regenerated
`requirements.txt`; the workflow installs only the locked, hash-verified
dependencies.
