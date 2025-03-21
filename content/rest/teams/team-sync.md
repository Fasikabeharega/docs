---
title: Team synchronization
intro: 'Use the REST API to manage connections between {% data variables.product.product_name %} teams and external identity provider (IdP) groups.'
versions:
  ghec: '*'
topics:
  - API
miniTocMaxHeadingLevel: 3
allowTitleToDifferFromFilename: true
---

## About team synchronization

To use these endpoints, the authenticated user must be a team maintainer or an owner of the organization associated with the team. The token you use to authenticate will also need to be authorized for use with your IdP (SSO) provider. For more information, see "[Authorizing a {% data variables.product.pat_generic %} for use with a SAML single sign-on organization](/enterprise-cloud@latest/authentication/authenticating-with-saml-single-sign-on/authorizing-a-personal-access-token-for-use-with-saml-single-sign-on)."

You can manage {% data variables.product.product_name %} team members through your IdP with team synchronization. Team synchronization must be enabled to use these endpoints. For more information, see "[Managing team synchronization for your organization](/enterprise-cloud@latest/organizations/managing-saml-single-sign-on-for-your-organization/managing-team-synchronization-for-your-organization)."

{% note %}

**Note:** These endpoints cannot be used with {% data variables.product.prodname_emus %}. To learn more about managing an {% data variables.enterprise.prodname_emu_org %}, see "[External groups](/enterprise-cloud@latest/rest/teams/external-groups)".

{% endnote %}
