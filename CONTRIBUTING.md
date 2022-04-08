# Contribution Guidelines

| Audience     |
| :----------- |
| Contributors |

Follow these guidelines to add or modify shared docs.

## Getting Started

Easiest way to get started is to copy the root `README.md` and modify. That way you get the markdown table pre-formatted, and only have to change the second row to fill it in.

## Metadata for docs

Each file (or for long files, each section) should have a markdown table declaring at a minimum:

- **Audience:** `Everyone`, `Maintainers`, `Contributors`, `Themers`, etc.

Additionally it could be helpful to list technical info when it's known:

- **Stack:** `Universal`, `node.js`, `drupal`
- **Projects:** `OPS`, `HID`, `CD`, etc.

Here's a sample markdown table with all three columns:

```md
| Audience | Stack     | Projects |
| :------- | :-------- | :------- |
| Everyone | Universal | None     |
```

:information_source: _Note:_ the columns of each row **do NOT have to line up** to render correctly.

## Organizing files

For now, creating a directory with a short, hyphenated name to describe your docs is the only method of organization.

## Commit messages

Please use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/#summary). Some points to consider:

- Although most will obviously be `docs:` you can still use the `!` symbol, or the `BREAKING CHANGE: ...` commit footer to indicate when documentation has changed so dramatically as to warrant a review on repos that link here.
- If you wish, ticket your work and use `Refs: JIRA-XXX`. Many projects are autolinked and we can always add more.

## Submit for Review

Create a PR against the docs repo to have it reviewed by someone who has (or needs to have) the documentation. Often the PR will be an important proof-reading step that improves your docs, so don't be afraid to ask for feedback!
