# python-lint

<p align="left">
  <a href="https://github.com/ricardochaves/python-lint"><img alt="GitHub Actions status" src="https://github.com/ricardochaves/python-lint/workflows/Python%20Lint/badge.svg"></a>
</p>

This action must be used for aplication the bids:

- [black](https://github.com/psf/black)
- [pylint](https://www.pylint.org/)
- [isort](https://github.com/timothycrosley/isort)
- [pycodestyle](https://pycodestyle.readthedocs.io)
- [flake8](http://flake8.pycqa.org)
- [mypy](http://mypy-lang.org/)

## Usage

See [action.yml](action.yml)

Basic:

```yml
steps:
  - uses: actions/checkout@v1
  - uses: ricardochaves/python-lint@test
```

Options:

```yml
steps:
  - uses: actions/checkout@v1
  - uses: ricardochaves/python-lint@test
    with:
      python-root-list: "python_alelo tests"
      use-pylint: false
      use-pycodestyle: false
      use-flake8: false
      use-black: false
      use-mypy: false
      use-isort: false
```

## License

The scripts and documentation in this project are released under the [MIT License](LICENSE)

## Contributions

Contributions are welcome! See [Contributor's Guide](docs/contributors.md)