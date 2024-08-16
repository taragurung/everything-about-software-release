## Pull Request template
Please, go through these steps before you submit a PR.

1. Make sure the title of the Pull Request title respects the [Conventional Commits Spec](https://www.conventionalcommits.org/en/v1.0.0/#summary):

    a. Must be in the following format: `{type}({optional JIRA ticket}): {Description}` (e.g. `feat(EC-1063): Add missing Criteo variables`, `docs: Add PR template`).

    b. Type must be one of the following:
    * **feat**: A new feature
    * **improvement**: A feature improvement
    * **fix**: A bug fix
    * **docs**: Documentation only changes
    * **perf**: A code change that improves performance
    * **build**: Changes that affect the build system or external dependencies (example scopes: gulp, yarn)
    * **ci**: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
    * **refactor**: A code change that neither fixes a bug nor adds a feature
    * **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
    * **test**: Adding missing tests or correcting existing tests
    * **chore**: Improving the code base so that it can be worked with more easily

2. If your PR is related to an API route, the `{Description}` part of your PR title should be in the following format `{Add/Modify/Delete} {Method} {Resource} route` (e.g.`Add Delete Sale route`).

3. If your Pull Request includes breaking changes:

    a. Add `!` in your PR title after the type (or the JIRA ticket if any). (e.g. `feat(EC-591)!: Upgrade comma separated parameters to array in Create Product`)

    b. Add `BREAKING CHANGE: {Description of the breaking change}` in your PR description. (e.g. `BREAKING CHANGE: Upgrade comma separated parameters to array in Create Product`)

    c. Add the `breaking change` label to the PR.

**PLEASE REMOVE THIS TEMPLATE BEFORE SUBMITTING**
