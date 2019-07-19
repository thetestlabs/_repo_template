# Contributing Guidelines

When contributing to this repository, please take into account these guidelines to ensure that the process is as smooth as possible.

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Branching Strategy

This repository uses a branch-based workflow for adding or updating features. When you want to work on a new feature or fix an issue, please create a new branch from the `master` branch. When creating a feature branch, it's important that the name is descriptive and gives an indication of the purpose of the feature or issue that you are working on, for example `add-authentication-method`, `update-to-terraform-12`, or `resolve-database-caching-issue`.

## Commits

When working on a feature, commits should ideally contain a discreet unit of change, and follow these guidelines:

- Work on a single change at a time
- Ensure changes you make are as small as possible
- Commit often, with good commit messages
- If tests are defined, ensure they pass at each commit

Following these guidelines will help you and others track, understand, read, review, and revert commits if necessary.

Please try and include clear commit messages, as these help other contributors or interested parties understand what has been changed and why. Commits should consist of a subject line and a body - here are some guidelines for creating good commit messages:

- The subject should be a summary of *what* you have done
    - It should be short - no more than 50 characters
    - It should be capitalized, and not end in a full stop - think of it as a title, not a sentence
    - The subject line should use the imperative mood, e.g. "Add Foo to Bar" rather than "This Feature Adds Foo to Bar"
    - It should complete the sentence *"If applied, this commit will `your subject line here`"*
- The body of the commit shoud explain *why* the change is being made, plus any more details of the what that couldn't be expressed in the subject line
    - How does it address the issue (provide issue reference if there is one)
    - What benefits does the feature provide, and why were they required
    - What effects does the patch have
    - Do not assume the reviewer understands what the original problem was
    - Do not assume the code is self-evident/self-documenting

## Pull Request Process

Once you feel that your feature branch is ready to merge into the master branch, the process for submitting and reviewing PR's is as follows:

- Submit a PR with a brief description of the change
- If you are providing new code as opposed to updating existing code, please ensure that there is a README.md file present including details of any tests
- The PR will need to be reviewed and receive approval from at least one other engineer after any agreed changes are made
- Once the branch is merged to master, it should be deleted
