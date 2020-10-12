# uniclogs-pass-calculator
[![License](https://img.shields.io/github/license/oresat/uniclogs-pass-calculator)](./LICENSE)
![Unit Tests](https://github.com/oresat/uniclogs-pass-calculator/workflows/Pass%20Calculator%20Unit%20Tests/badge.svg)
[![Issues](https://img.shields.io/github/issues/oresat/uniclogs-pass-calculator)](https://github.com/oresat/uniclogs-pass-calculator/issues)

A common python module for calculating orbital passes used by ULTRA and RADS.
Mostly a simple wrapper ontop of [skyfield].

## Install Dependencies

`$` `pip install -r requirements.txt`

## Build
`$` `python3 setup.py bdist_wheel`

## Installation

**Install for single-user:**

`$` `python -m pip install dist/pass_calculator-*-py3-none-any.whl`


**Install globally:**

`$` `sudo python -m pip install dist/pass_calculator-*-py3-none-any.whl`

[skyfield]:https://rhodesmill.org/skyfield/
