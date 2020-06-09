# setup-conjur

This action sets up a Conjur environment for use in workflows.

## Certification level

TBD

## Requirements

TBD

## Usage instructions

Basic:

```yaml
steps:
  - uses: actions/checkout@master
  - uses: infamousjoeg/setup-conjur@v1
    with:
        conjur-version: '1.7.2' # The Conjur version to download (if necessary) and use.
  - run: conjur version

## Contributing

We welcome contributions of all kinds to this repository. For instructions on how to get started and descriptions
of our development workflows, please see our [contributing guide](CONTRIBUTING.md).

## License

This repository is licensed under Apache License 2.0 - see [`LICENSE`](LICENSE) for more details.
