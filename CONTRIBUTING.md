# Contributing

We're so excited you're interested in helping with Oku! We are happy to help you get started, even if you don't have any previous open-source experience :blush:

## New to Open Source?

1. Take a look at [How to Contribute to an Open Source Project on GitHub](https://egghead.io/courses/how-to-contribute-to-an-open-source-project-on-github)

## Where to ask Questions?

1. Check our [Github Issues](https://github.com/oku-ui/primitives/issues) to see if someone has already answered your question.
2. Join our community on [Discord](https://chat.productdevbook.com) and feel free to ask us your questions


### Prerequisites
-   [Min Nodejs 16] & [PNPM](https://pnpm.io) installed
-   IDE: [VSCode](https://code.visualstudio.com/download)(recommended) or equivalent IDE


### VScode Extensions

-  [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
-  [Terminals Manager](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-terminals)
-  [Commands](https://marketplace.visualstudio.com/items?itemName=knisterpeter.vscode-github)

Note: What is Terminals Maganger and Commands  -> https://github.com/oku-ui/primitives/issues/34#issuecomment-1528652790

### Project Setup

1. Fork the [oku-ui](https://github.com/oku-ui/primitives) repository
2. Install the project dependencies  
   `pnpm install`
3. Build the project  
   `pnpm build`
4. If new package vue, go to `packages/example-package` example `packages/components` or `packages/core` copy. You can copy this file and build your new build on it.

## Testing

1. We use [Vitest](https://vitest.dev/) for testing
2. To run the tests  
   `pnpm test`
3. Watch mode  
   `pnpm test:watch`
4. To run a specific test file name  
   `pnpm test testfilename`

## ESLint
1. To run the linter  
   `pnpm lint`
2. All linting errors will be automatically fixed on commit
   `pnpm lint:fix`


## Pull Request

1. Before submitting a pull request make sure all tests have passed
2. Reference the relevant issue or pull request and give a clear description of changes/features added when submitting a pull request
3. Make sure the PR title follows [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) specification

## Oku Community

Oku is made possible by a passionate team and a strong community of developers. If you have any questions or would like to get more involved in the Oku community you can check out:

-   [Github Issues](https://github.com/oku-ui/primitives/issues)
-   [Discord](https://chat.productdevbook.com)
-   [Twitter](https://twitter.com/oku_ui)