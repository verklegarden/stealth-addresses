<div align="center">

<h1>Stealth Addresses</h1>

<a href="">[![Unit Tests][tests-shield]][tests-shield-url]</a>
<a href="">![Apache2/MIT licensed][license-shield]</a>

</div>

A Solidity implementation of ERC-5564 stealth addresses for offchain usage.

## Installation

Install with [Foundry](https://getfoundry.sh/):

```bash
$ forge install verklegarden/stealth-addresses
```

## Contributing

The project uses the Foundry toolchain. You can find installation instructions [here](https://getfoundry.sh/).

Setup:

```bash
$ git clone https://github.com/verklegarden/stealth-addresses
$ cd stealth-addresses/
$ forge install
```

Run tests:

```bash
$ forge test
$ forge test -vvvv # Run with full stack traces
$ FOUNDRY_PROFILE=intense forge test # Run in intense mode
```

Lint:

```bash
$ forge fmt [--check]
```

## Safety

This is **experimental software** and is provided on an "as is" and "as available" basis.

We **do not give any warranties** and **will not be liable** for any loss incurred through any use of this codebase.

<!--- Shields -->
[tests-shield]: https://github.com/pmerkleplant/verklegarden/stealth-addresses/actions/workflows/unit-tests.yml/badge.svg
[tests-shield-url]: https://github.com/verklegarden/stealth-addresses/actions/workflows/unit-tests.yml
[license-shield]: https://img.shields.io/badge/license-Apache2.0/MIT-blue.svg
