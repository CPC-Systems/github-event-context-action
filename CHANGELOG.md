# Changelog

## Unreleased

Upgraded to Node.js version `24` (was `20`).

## 1.3.0

Adds an `artifact-path` output.

## 1.2.1

Support manual workflow trigger on a tag.

## 1.2.0

Forked for CPC Systems from Ably original, upgrading to Node.js 20.

## [1.1.1](https://github.com/ably/github-event-context-action/releases/tag/v1.1.1)

- fix: guard `ref` property access if `null` [\#4](https://github.com/ably/github-event-context-action/pull/4)

## [1.1.0](https://github.com/ably/github-event-context-action/releases/tag/v1.1.0)

This release adds an additional output to this Action called `build-metadata`, in a format that is compatible for use as [build metadata](https://semver.org/#spec-item-10) in a semantically versioned 'number' (the text after the `+`).

Also added is support for use in a job where the workflow was triggered manually (a `workflow_dispatch` event), which is a typical scenario where the `build-metadata` output would subsequently be consumed.
