# twa

Mono-repository, containing all the packages, connected with TypeScript
development on Web Apps platform. To learn more, follow packages own
documentation.

## Packages

- [core](/packages/core) - core utilities reused all over the ecosystem
  libraries. You probably don't need to use this package directly, but it's
  surely useful to know how most of our libraries works.
- [bridge](/packages/bridge) - provides utilities to simplify communication
  flow between frontend and Telegram native applications. It also solves some
  across-platform data difference problems to protect developers code and save
  their time.
- [theme-params](/packages/theme-params) - provides developer
  information about which colors are currently used by native application and
  expects developer to use them.
- [init-data](/packages/init-data) - TypeScript isomorphic library to make work
  with Telegram Web Apps init data easier. Could be used both in browser and
  Node JS.
- [sdk](/packages/sdk) - Made from scratch TypeScript library for communication with Telegram Web Apps
  functionality.

## Contribution

Any contribution is appreciated. Feel free to create new feature requests, bug
reports etc. In case, you found a bug in Web Apps platform (not in SDK), please, create new
issue [here](https://github.com/Telegram-Web-Apps/sdk/issues/new/choose).