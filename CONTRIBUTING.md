# Contributing Guide

I love your input! I want to make contributing to one of my projects as easy and
transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

I use GitHub to

- host code
- track issues and feature requests
- accept pull requests.
- tag & publish release as well as pushing those to npm.

## Reporting bugs or requesting a feature

I use GitHub issues to track public bugs or discuss about new features. Please
write bug reports or feature requests with detail, background, and sample code
if necessary.

Just try to _open a new issue_ & follow the instructions that should be
prefilled for [bug](.github/ISSUE_TEMPLATE/bug.md) or
[feature request](.github/ISSUE_TEMPLATE/feature.md).

People _love_ thorough bug reports. Not even kidding.

## Fixing bugs & implementing features

I use [Github flow](https://guides.github.com/introduction/flow/index.html), so
most code changes happen through Pull Requests.

[Pull Requests](https://help.github.com/en/articles/about-pull-requests) are the
best way to propose changes to the codebase since they notify watchers & allow
contributors to discuss about changes.

I actively welcome your pull requests.

To make a pull request, you need to:

1. [Fork the repo](https://help.github.com/en/articles/fork-a-repo)
2. Clone it
3. Follow development installation if any (eg: `npm install` or `yarn`)
4. Create a local branch, from `main` (unless specified differently)
   ```console
   git checkout -b <name-of-your-branch>
   ```
5. Add your changes!
   - If you've added code that should be tested, add tests.
   - If you've changed APIs, update the documentation.
6. Ensure the everything is still fine (eg: run tests if any).
7. Commit & push your branch online
   ```console
   git add -A .
   git commit -m "Your commit message"
   ```
8. [Create a pull request](https://help.github.com/en/articles/creating-a-pull-request)

_If you are new to Git or GitHub, we encourage you to have a look to
[makeapullrequest.com](http://makeapullrequest.com)._

## Code styling

Everything as been automated: as soon as you commit, everything should be
automatically reformated if necessary (eg: transparent git hook) so we
don't have to think about it!

## Licensing

By contributing, you agree that your contributions will be licensed under an
MIT License.

When you submit code changes, your submissions are understood to be under the
same license that covers the project. Feel free to contact the
maintainers if that's a concern.
