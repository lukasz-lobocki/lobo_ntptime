# lobo_ntptime

## Typical build workflow

```bash
git add --update
```

```bash
git commit -m "fix: change"
```

```bash
poetry run semantic-release version
```

```bash
git push
```

## Cookiecutter initiation

```bash
cookiecutter \
  ssh://git@github.com/lukasz-lobocki/py-pkgs-cookiecutter.git \
  package_name="lobo_ntptime"
```

### was run with following variables

- package_name: **`lobo_ntptime`**;
package_short_description: `Reads time from internet server.`

- package_version: `0.2.3`; python_version: `3.10`

- author_name: `Lukasz Lobocki`;
open_source_license: `CC0 v1.0 Universal`

- __package_slug: `lobo_ntptime`; include_github_actions: `no`

### on

`2023-07-31 10:10:25 +0200`
