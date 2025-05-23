---
title: Commit statuses
intro: Use the REST API to interact with commit statuses.
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - API
miniTocMaxHeadingLevel: 3
allowTitleToDifferFromFilename: true
---

## About commit statuses

You can use the REST API to allow external services to mark commits with an `error`, `failure`, `pending`, or `success` state, which is then reflected in pull requests involving those commits. Statuses can also include an optional `description` and `target_url`, and we highly recommend providing them as they make statuses much more useful in the GitHub UI.

As an example, one common use is for continuous integration services to mark commits as passing or failing builds using status.  The `target_url` would be the full URL to the build output, and the `description` would be the high level summary of what happened with the build.

Statuses can include a `context` to indicate what service is providing that status. For example, you may have your continuous integration service push statuses with a context of `ci`, and a security audit tool push statuses with a context of `security`.  You can then use the REST API to [Get the combined status for a specific reference](/rest/commits/statuses#get-the-combined-status-for-a-specific-reference) to retrieve the whole status for a commit.

Note that the `repo:status` [OAuth scope](/developers/apps/scopes-for-oauth-apps) grants targeted access to statuses **without** also granting access to repository code, while the `repo` scope grants permission to code as well as statuses.

If you are developing a GitHub App and want to provide more detailed information about an external service, you may want to use the REST API to manage checks. For more information, see "[Checks](/rest/reference/checks)."
