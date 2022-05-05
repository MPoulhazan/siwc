# Sign in with Conflux

Sign-In with Conflux describes how Conflux accounts authenticate with
off-chain services by signing a standard message format parameterized by scope,
session details, and security mechanisms (e.g., a nonce). The goals of this
specification are to provide a self-custodied alternative to centralized
identity providers, improve interoperability across off-chain services for
Conflux-based authentication, and provide wallet vendors a consistent
machine-readable message format to achieve improved user experiences and
consent management.

## Getting Started

To use siwc in you project, execute the following command

```
npm i siwc
```

Or with yarn

```
yarn add siwc
```

### Prerequisites

Npm installed

### Installing

Run `npm install` to install dependencies, then `npm bootstrap` to link the dependencies in their respective packages.
Afteward run `npm run build` to build the library.
Development can occur on the `package/*` level with tests being run on each package itself.

## Running the tests

Run `npm run test` to run the tests with Jest.

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

See also the list of [contributors](https://github.com/MPoulhazan/siwc/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
