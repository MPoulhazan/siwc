# Sign in with Conflux

Sign-In with Conflux describes how Conflux accounts authenticate with
off-chain services by signing a standard message format parameterized by scope,
session details, and security mechanisms (e.g., a nonce). The goals of this
specification are to provide a self-custodied alternative to centralized
identity providers, improve interoperability across off-chain services for
Conflux-based authentication, and provide wallet vendors a consistent
machine-readable message format to achieve improved user experiences and
consent management.

This project is based on <a href="https://github.com/spruceid/siwe" target="_blank">Sign-In With Ethereum</a>.

## Getting Started

To use siwc in you project, execute the following command

```
npm i siwc
```

Or with yarn

```
yarn add siwc
```

Check this <a href="https://medium.com/@mickalpoulhazan/f394d9c0d099" target="_blank">article</a> for more informations.

## Examples

A siwc-quickstart project with front and back examples can be found <a href="https://github.com/MPoulhazan/siwc-quickstart" target="_blank">here</a>.

## Prerequisites

Npm installed

## Installing

Run `npm install` to install dependencies, then `npm bootstrap` to link the dependencies in their respective packages.
Afteward run `npm run build` to build the library.
Development can occur on the `package/*` level with tests being run on each package itself.

## Running the tests

Go to package `siwc` or `siwc-parser` and run `npm run test` to run the tests with Jest.

## Deployment

SIWC is deployed on npm registry.

## Built With

- [Javascript](https://www.javascript.com/) - For js files
- [Typescript](https://www.typescriptlang.org/) - For ts files
- [Jest](https://jestjs.io/fr/) - Tests framework
- [Npm](https://www.npmjs.com/) - Package manager

## Contributing

Please read [CONTRIBUTING.md](https://github.com/MPoulhazan/siwc) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

For the versions available, see the [tags on this repository](https://github.com/MPoulhazan/siwc/tags).

## Authors

- **Mickael Poulhazan** - _Fullstack dev_ - [MPoulhazan](https://github.com/MPoulhazan)
- **Spruce System, Inc** - _Multiple contributors_ - [Spruceid](https://github.com/spruceid)

See also the list of [contributors](https://github.com/MPoulhazan/siwc/contributors) who participated in this project and SIWE [contributors](https://github.com/spruceid/siwe/graphs/contributors) for initial project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
