---
title: Disabling team discussions for your organization
intro: Organization owners can choose to disable or enable team discussions across the organization.
redirect_from:
  - /articles/disabling-team-discussions-for-your-organization
  - /github/setting-up-and-managing-organizations-and-teams/disabling-team-discussions-for-your-organization
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Organizations
  - Teams
shortTitle: Disable team discussions
---

{% ifversion team-discussions-migration %}
{% data reusables.organizations.team-discussions-migration %}
{% endif %}

{% data reusables.organizations.team-discussions-default %} For more information on team discussions, see "[AUTOTITLE](/organizations/collaborating-with-your-team/about-team-discussions)."

{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
{% data reusables.organizations.teams_sidebar %}
5. Under "Team discussions", unselect **Enable team discussions for this organization**.
6. Click **Save**.
