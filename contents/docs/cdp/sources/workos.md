---
title: Linking WorkOS as a source
sidebar: Docs
showTitle: true
availability:
  free: full
  selfServe: full
  enterprise: full
sourceId: WorkOS
---

The WorkOS connector can link users, organizations, organization memberships, invitations, and resources to PostHog.

To link WorkOS:

1. Go to the [sources tab](https://app.posthog.com/data-management/sources) of the data pipeline section in PostHog.

2. Click **+ New source** and then click **Link** next to WorkOS.

3. Get an API key from WorkOS. Go to your [WorkOS Dashboard](https://dashboard.workos.com/) and navigate to **API Keys**. Copy your API key.

4. Back in PostHog, paste the API key in the **API key** field and click **Next**.

5. Set up the schemas you want to sync and modify the method and frequency as needed. Click **Import**.

Once the syncs are complete, you can start using WorkOS data in PostHog.
