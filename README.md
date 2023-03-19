# NPM Package Prototype

Storybook: https://akihiro-tj.github.io/npm-package-prototype/

## Setup

```bash
$ yarn
```

## Development

```bash
$ yarn storybook
```

## Lint

```bash
$ yarn fix
```

## Publish

```bash
$ yarn version --new-version {version}
$ git push origin v{version}
```

```bash
$ yarn version --new-version 0.1.0
$ git push origin v0.1.0
```

## Usage

```bash
$ yarn add @akihiro-tj/npm-package-prototype
```

Ex.

```tsx
import { Button } from '@akihiro-tj/npm-package-prototype';
```
