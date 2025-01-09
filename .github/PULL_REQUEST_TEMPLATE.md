Please, go through these steps before you submit a PR.

1. Make sure that your PR is not a duplicate.
2. If not, then make sure that:

   a. You have done your changes in a separate branch. Branches MUST have descriptive names that start with either the `fix/` or `feature/` prefixes. Good examples are: `fix/signin-issue` or `feature/issue-templates`.

   b. You have a descriptive commit message with a short title (first line).

   c. You have only one commit (if not, squash them into one commit).

   d. `cargo test` doesn't throw any error. If it does, fix them first and amend your commit (`git commit --amend`).

3. **After** these steps, you're ready to open a pull request.

   a. Your pull request MUST NOT target the `main` branch on this repository. You probably want to target `develop` instead.

   b. Give a descriptive title to your PR.

   c. Describe your changes.

   d. Put `closes #XXXX` in your comment to auto-close the issue that your PR fixes (if such).

**PLEASE REMOVE THIS TEMPLATE BEFORE SUBMITTING**
___

**Please check if the PR fulfills these requirements**
- [ ] The commit message follows our guidelines
- [ ] Tests for the changes have been added (for bug fixes/features)
- [ ] Docs have been added / updated (for bug fixes / features)


* **What kind of change does this PR introduce?** (Bug fix, feature, docs update, ...)


* **What is the current behavior?** (You can also link to an open issue here)


* **What is the new behavior (if this is a feature change)?**


* **Does this PR introduce a breaking change?** (What changes might users need to make in their application due to this PR?)


* **Other information**:

