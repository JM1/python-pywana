# TODO
* Add unit-tests
  - e.g. [python-gnupg](https://github.com/isislovecruft/python-gnupg/tree/master/pretty_bad_protocol/test)
  - adapt setup.py to include:
    ```python3
    setuptools.setup(
      # ...
      test_suite       = 'pywana.test.test_wana',
      # ...
    )
    ```
  - adapt .travis.yml to include:
    ```sh
    script:
      - pytest
    ```
