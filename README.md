![Sign-In with Conflux logo](https://login.xyz/favicon.png "Sign-In with Conflux logo")

Sign-In with Conflux describes how Conflux accounts authenticate with
off-chain services by signing a standard message format parameterized by scope,
session details, and security mechanisms (e.g., a nonce). The goals of this
specification are to provide a self-custodied alternative to centralized
identity providers, improve interoperability across off-chain services for
Conflux-based authentication, and provide wallet vendors a consistent
machine-readable message format to achieve improved user experiences and
consent management.

## Mono Repo Install and Build

Run `npm install` to install dependencies, then `npm bootstrap` to link the dependencies
in their respective packages. Afteward run `npm run build` to build the library.
Development can occur on the `package/*` level with tests being run on each package itself.
