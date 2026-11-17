# Collaborating on TCUP workshop training

**Proposed—not adopted.**

Start with `README.md` and `index.md`. Lessons live under `notebooks/`. The site
uses `_config.yml` and the development container is described in
`.devcontainer.json`. Check actual setup before reporting it as tested.

## Coordinate the work

Search open issues and PRs. Use an issue when a question, dependency or choice
needs discussion. State the desired result, affected files and completion
criteria. Small corrections can go directly to a PR. Agree on one editor per
file before overlapping work begins.

## Prepare and review a change

1. Use a short-lived topic branch or a fork if you lack write access and
   repository policy permits. Preserve originals, attribution and applicable
   lesson/data licenses.
2. Open a focused PR describing the problem, the change, relevant issues, checks
   and open questions. Request review from an affected maintainer. For site or
   notebook changes, include the rendered result or execution summary when
   available.
3. Resolve feedback and check deployment behavior before an authorized
   maintainer merges. Verify the rendered site after deployment. Close the issue
   when its completion criteria are met.

Keep public profiles optional and explicitly opt-in. Participants choose their
fields, and contact information is optional. Keep private records and
community-controlled data out of public changes. Share questionnaire results in
aggregate and omit individual free-text quotes.

## Agent-assisted contributions

Follow `AGENTS.md`. Charles Jason Tinant (CJT) authorizes work and GitHub
actions by the agents he runs. When an agent lacks Git access, it can provide a
local diff and proposed PR text for the authorized human. Use the real checkout
for commits.

Have an affected maintainer review substantive changes. CJT’s `cjtinant` and
`cjtinant-alt` accounts represent one person. Use the authorized Comment review
and independent maintainer route described in `AGENTS.md`.
