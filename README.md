

## Lore
In days long goneby, the admin api docs for [dbt-cloud](https://github.com/dbt-labs/dbt-cloud) were a manual affair.
When new endpoints in our django monolith were updated, savvy engineers knew this repo actually existed, and would
manually update the openapi spec within. Most knew not that this existed. Some were surprised we even had api docs.

The cloud config team, from its unseen perch, heard the cry of Topher to automate this annoying processs. APIs were
consistently mismatched with the docs and customers, I mean, the masses sought refuge. Stuck in the mires of the django monolith, a
custom process was built. The docs were born anew.

For many fortnights, this "automation" was manual and oft forgotten. The darkness gained its foothold...

And yet cloud config fought back! They rode once more into the veil. Some bold warriors found and slayed the miscast
beasts that lurked oncemore. With docs once more showing the truth, they shew'ed dbt-cloud the path to guard
itself and keep the people informed once more of the truth (via CI).

## wtf?
Yeah yeah, it's weird it's a repo. It should be dumped in S3 if we want these specs cached. But it is nice to have a history of changesets.
Really it's just that there used to be a need for the repo, and it was easier to keep things in place then to start dumping to S3
and reroute the docs.getdbt.com repo to the new location. Maybe you'll be the hero we need to switch things. But for now,
it's good enough 👍
