# Contributing

Thank you for your willingness to contribute to this project! We appreciate your effort. Please note our [Code of Conduct](https://github.com/inkrend/.github/blob/main/CODE_OF_CONDUCT.md) before proceeding.


## Issues

When creating a new issue...

1. check to see if your issue has already been raised
2. use an appropriate issue template when available
3. select appropriate labels
4. never disclose security vulnerabilities in an issue; refer to this project's [security policy](https://github.com/inkrend/.github/blob/main/SECURITY.md)


## Commit Messages

Always be clear when describing the changes you commit to the project. Shorter commit messages are fine for minor changes, but the commit messages for large contributions should include more information:

```shell
$ git commit -m "a summary of your changes
>
> Additional text describing what was changed and why."
```


## Coding Conventions

This project adheres to a set of coding conventions, which your contributions are expected to follow. Enabling [EditorConfig](https://editorconfig.org/) in your IDE will help with the basics in your editor, but it won't catch everything. For that, this project uses ESLint to enforce consistency. Linting is automatically performed when tests are run, but you can also manually run ESLint at any point with the following NPM script:

```shell
npm run eslint
```


## Pull Requests

Don't create a pull request without referencing an issue, opening one first if necessary. Changes must be discussed before proceeding to the pull request stage. Failure to do so may result in rejection of your pull request.

When creating a new pull request...

1. use an appropriate pull request template when available
2. reference any issue(s) related to your pull request
3. specify which issue(s) your pull request closes by adding [`Closes #XXX`](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword) in your pull request
4. provide thorough tests for code you contribute
5. note that all pull requests will be reviewed before they are merged


## Licensing

By contributing to one of this organization's repositories, you agree to license your contributions under that repository's license, which may vary from repository to repository. Please review an individual repository's license prior to contributing.
