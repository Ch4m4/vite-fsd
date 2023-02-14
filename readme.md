# Vite-FSD
The command line interface (CLI) for creating and maintain front-end projects.

## Stack
A modern approach to creating a frontend application:
- [Vite] - the fast and easy bundler.
- [Feature-Sliced Design] - the powerful architecture for frontend projects.
- [Vitest] - a vite powered testing framework.
- [ESLint FSD rules] - The rules for FSD help ensure correct adherence to the architecture without pain.
- [Typescript] - a strongly typed programming language that builds on JavaScript

## Installation
```bash
npm install -g vite-fsd
```

## Usage
```bash
vite-fsd <command> <param> --option <value>
```

> For more information of [Vite-FSD CLI], you can run the following command:
> ```bash
> vite-fsd --help
> ```

## Features

### 1. Create a new project
It's really fast, easy and powerful!

```bash
vite-fsd init
```

- one of the best architecture for frontend projects
- development and production environments
- fastest testing environment
> Enjoy! Stay tuned for more useful tools:

> - CI/CD environment
> - documentation environment
> - deployment environment
> - monitoring environment
> - analytics environment

### 2. Use the CLI to create a new feature
Configured templates for FSD. Just create a slice for your feature :)

```bash
vite-fsd create <template> <name> --[options]
```

Vite-FSD currently supports the following templates: `ui`, `lib`, `feauture`

## License
Vite-FSD is open-source software, licensed under the [MIT License].

[//]: # (Links)
[Vite]: https://vitejs.dev/
[Feature-Sliced Design]: https://feature-sliced.design/
[Vitest]: https://vitest.dev/
[ESLint FSD rules]: https://github.com/feature-sliced/eslint-config
[TypeScript]: https://www.typescriptlang.org/
[MIT License]: ./LICENSE

[//]: # (Wiki)
[Vite-FSD Wiki]: https://github.com/Ch4m4/vite-fsd/wiki
[Vite-FSD CLI]: https://github.com/Ch4m4/vite-fsd/wiki/CLI

