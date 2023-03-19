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
$ yarn version

info Current version: x.x.x
question New version: {version}
```

```bash
$ git push origin {version}
```

## Usage

```bash
$ yarn add @akihiro-tj/npm-package-prototype
```

Ex.

```tsx
import { Button } from '@akihiro-tj/npm-package-prototype';
```
