---
title: Profiles Sync Overview
plan: unify
---

Profiles Sync connects identity-resolved customer profiles to a data warehouse of your choice.

With a continual flow of synced profiles, teams can enrich and use these data sets as the basis for new audiences and models. Profiles Sync addresses a number of use cases, with applications for identity graph monitoring, attribution analysis, machine learning, and more. View [Profiles Sync Sample Queries](/docs/unify/profiles-sync/sample-queries) for an in-depth guide to Profiles Sync applications.


## Profiles Sync use cases

To help you get started, here are a few example use cases:

### Understand how Segment creates Profiles

Use Profiles Sync for more insight into profiles generated by Segment's [Identity Resolution](/docs/unify/identity-resolution/). Query the Profile Sync data set to answer questions such as:
- What's causing profile merges in a given period?
- How many merges occur for each profile?
- How many emails are associated with a profile?

Understanding how Segment creates profiles helps you detect potential instrumentation errors.

### Create golden profiles

Join Segment's profile data with existing object data from your warehouse to create a single view of the customer. You can then use this data set to create personalized  experiences on any channel. For example, B2B companies can build a report that maps sales executives (object data synced with a source like Salesforce) with customers who are most likely to buy a certain product (Profile Traits data synced with Profiles Sync).

### Understand a customer's journey

With Profiles Sync, your data teams can better understand profile merge events. Connect anonymous IDs, User IDs, and emails to understand your customer's journey with details such as:
- How often a user has paid.
- If someone is a bad actor.
- If a user has subscribed or not.
- What products users are viewing, even when they aren't logged in.

### Build attribution models

Use Profiles Sync to build data models that marketing partners can trust. Trace prospective customer journeys before buying products, and build models that help you understand which channels provide the most value.


### Use machine learning

Access profile traits and see how they change over time. This will help you to better understand how your customer's behavior evolves, and build models that predict LTV, churn, and propensity scores.


## Next steps

To learn more about Profiles Sync, visit the following docs:

- [Profiles Sync Setup](/docs/unify/profiles-sync/): Learn how to set up Profiles Sync, enable historical backfill, and adjust settings for warehouses you've connected.
- [Sample Queries](/docs/unify/profiles-sync/sample-queries/): View sample queries you can run to help you familiarize yourself with Profiles Sync.
- [Tables and materialized views](/docs/unify/profiles-sync/tables/): Learn how to use data sets and models that Segment provides to enrich customer profiles.


> info ""
> For more on Profiles Sync logic, table mappings, and data types, download this [Profiles Sync ERD](/docs/unify/files/ERD.png).
