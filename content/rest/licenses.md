---
title: Licenses
intro: Use the REST API to retrieve popular open source licenses and information about a particular project's license file.
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - API
miniTocMaxHeadingLevel: 3
redirect_from:
  - /rest/reference/licenses
---

## About licenses

{% data variables.product.company_short %} uses [the open source Ruby Gem Licensee](https://github.com/benbalter/licensee) to attempt to identify the license for a project. Licensee matches the contents of a project's `LICENSE` file (if it exists) against a short list of known licenses. As a result, the API does not take into account the licenses of project dependencies or other means of documenting a project's license such as references to the license name in the documentation.

If a license is matched, the license key and name returned conforms to the [SPDX specification](https://spdx.org/).

**Note:** These endpoints will also return a repository's license information:

- [Get a repository](/rest/reference/repos#get-a-repository)
- [List repositories for a user](/rest/reference/repos#list-repositories-for-a-user)
- [List organization repositories](/rest/reference/repos#list-organization-repositories)
- [List forks](/rest/reference/repos#list-forks)
- [List repositories watched by a user](/rest/reference/activity#list-repositories-watched-by-a-user)
- [List team repositories](/rest/reference/teams#list-team-repositories)

{% warning %}

GitHub is a lot of things, but it’s not a law firm. As such, {% data variables.product.company_short %} does not provide legal advice. Using the API or sending us an email about it does not constitute legal advice nor does it create an attorney-client relationship. If you have any questions about what you can and can't do with a particular license, you should consult with your own legal counsel before moving forward. In fact, you should always consult with your own lawyer before making any decisions that might have legal ramifications or that may impact your legal rights.

{% data variables.product.company_short %} created these endpoints to help users get information about open source licenses and the projects that use them. We hope it helps, but please keep in mind that we’re not lawyers (at least most of us aren't) and that we make mistakes like everyone else. For that reason, {% data variables.product.company_short %} provides the API on an "as-is" basis and makes no warranties regarding any information or licenses provided on or through it, and disclaims liability for damages resulting from using the API.

{% endwarning %}
