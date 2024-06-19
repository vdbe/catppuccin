# pigeon's temporary port wrangling scripts

these will not remain.

**requires pyyaml & requests**

## setup

```console
$ python -m venv .venv && .venv/bin/pip install pyyaml requests
```

## scripts

### re-port

converts [`../resources/ports.yml`](../resources/ports.yml) to [`ports.yml`](ports.yml)

```console
$ python -m pigeon.report
```

### porcelain

generates [`ports.porcelain.yml`](ports.porcelain.yml) from [`ports.yml`](ports.yml)

```console
$ python -m pigeon.porcelain
```