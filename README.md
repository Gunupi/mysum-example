# mysum-example

![Tests](https://github.com/diegoabt/mysum-example/actions/workflows/tests.yml/badge.svg)
[![codecov](https://codecov.io/gh/diegoabt/mysum-example/graph/badge.svg)](https://codecov.io/gh/diegoabt/mysum-example)

A minimal Python example demonstrating unit testing and CI.

## What's here

- `mysum.py` — a validated sum function
- `test_mysum.py` — 7 unit tests following the AAA pattern
- `.github/workflows/tests.yml` — runs tests automatically on every push

## Run tests locally

```bash
python -m unittest test_mysum.py -v
```

## Run with coverage

```bash
python -m coverage run -m unittest test_mysum.py -v
python -m coverage report
```
