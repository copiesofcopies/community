---
name: "\U0001F58ASoftware Project Contribution and Onboarding"
about: To Contribute a Software Project to FINOS
title: Software Project Contribution and Onboarding
labels: contribution
assignees: aitana16, maoo

---
Please note that only FINOS members can propose new projects. If you're interested in membership, see https://www.finos.org/membership-benefits#become-a-member.

## Business Problem
*Describe the business problem the contribution solves*
 
## Proposed Solution
*Describe the type of contribution (project or working group) and how it solves that business problem*
 
## Current State
*Summarize the history and current state of the project*
 
## Existing Materials
*If materials already exist, provide a link to them that Foundation staff can access - if it's in a private GitHub.com repositories, you should invite the finos-admin user with R/O permissions to those repositories*

## Development Team
*List out all of the current team members, including full name, affiliation, work email address, and GitHub.com username*

# Contribution process (v. 1.0, last updated on October 2, 2020)
Below is the list of tasks that FINOS Team and the contribution author go through in order to complete the FINOS contribution process.
**Please do not edit these contents at contribution time!**

## FINOS Contrib POC
- [ ] Identify and Assign FINOS Contrib POC

## Identify project meta (Lead: FINOS Contrib POC, Support: FINOS Marketing)
- [ ] Project Name
    - [ ] Assess current trademark status
    - [ ] Define new project name (if applicable)
    - [ ] Design new project logo (if applicable)
    - [ ] Trademark new project name and logo (if applicable)
- [ ] Category and sub-category (for FINOS Landscape)
- [ ] Existing code or new Github repository
- [ ] Existing code releases (and which artifact repositories are used)
- [ ] Team composition: lead maintainer and other maintainers
- [ ] Meetings (existing/yes/no)
- [ ] Meeting minutes, agenda, attendance tracking (existing/yes/no)
- [ ] Continuous Integration (existing/yes/no)
- [ ] Documentation website (existing/yes/no)
- [ ] Define project slug

## Maintainers, contributors and CLAs (Lead: FINOS Contrib POC, Support: FINOS infra)
- [ ] For each maintainer identified in the previous step, collect: the following info:
  - Fullname
  - GitHub username
  - Corporate email address
- [ ] Identify other existing contributors (assuming there's a contribution history (eg Git history)
- [ ] Check if maintainers and other contributors are all covered by FINOS CLA
- [ ] Engage with FINOS Legal team to figure out what’s needed to cover all maintainers and contributors with FINOS CLA
- [ ] Reach out to contributors and employers to coordinate CLA signatures

## Project Communication Channel(s)
- [ ] Ask maintainers which communications channels they'd like to use
- Asynchronous
  - [ ] GitHub Issues (_public_)
  - [ ] GitHub Discussions (_public_)
  - [ ] GitHub Team Discussions (_public_ and _private_ **FINOS CLAs Required**)
  - [ ] Google Groups
- Synchronous
  - [ ] FINOS Slack Channel (general _public Slack_ / leadership _private Slack_)
- [ ] Create the identified communication channels during infra set up
- [ ] Link communication channels linked front and center in the project README.md

## Code validation (only if code is contributed) (Lead: FINOS Infra)
- [ ] The codebase doesn’t have HIGH or CRITICAL CVEs across direct and transitive libraries
- [ ] The codebase doesn’t have any unfriendly licenses across direct and transitive libraries
- [ ] (optional - if a build system is provided) The build process runs successfully
- [ ] [finos-admin](http://github.com/finos-admin) is Admin of the GitHub repository to transfer
- [ ] The codebase doesn’t include any patent or copyright that conflicts with FINOS Governance and bylaws (to be validated with FINOS Legal team)
- [ ] Apply project blueprint contents - see [ODP docs](https://odp.finos.org/docs/project-collaboration/#finos-project-blueprint)
    - [ ] Ensure that the proper project governance is in the CONTRIBUTING.md file
- [ ] [All incubating criteria](https://finosfoundation.atlassian.net/wiki/spaces/FINOS/pages/75530363/Incubating) are checked and documented below

## Approval (Lead: FINOS Infra)
- [ ] Assign issue to Executive Director (@mindthegab) to trigger voting
- [ ] (optional) if additional socialization is required, the Executive Director may bring projects to the FINOS Governing Board
- [ ] FINOS accepts the contribution (and the contribution process can move forward)

## Code transfer (Lead: FINOS Infra)
- [ ] Check GitHub repository transfer requirements:
  - [ ] [finos-admin](http://github.com/finos-admin) has `Admin` to all repositories to transfer
  - [ ] [finos-admin](http://github.com/finos-admin) ia allowed to transfer repositories out of the org
  - [ ] if the repository is owned by a user (and not an org), the user must be able to transfer the repository to [finos-admin](http://github.com/finos-admin)
- [ ] Transfer all code assets as GitHub repositories under github.com/finos
- [ ] Invite GitHub usernames to GitHub FINOS Org
- [ ] Create `<project-name>-maintainers` GitHub team and invite users
- [ ] Configure `finos-admins` and `finos-staff` team permissions

## Infra setup (Lead: FINOS Infra)
- [ ] Update release coordinates and code namespace to include `finos` (best effort)
- [ ] Update project badge
- [ ] Update project README
- [ ] Enable security vulnerabilities scanning
- [ ] Aggregate mailing lists to community@finos.org
- [ ] Enable meeting attendance tracking (optional)
- [ ] (optional) Onboard into legend.finos.org/studio

## Metadata update (Lead: FINOS Infra)
- [ ] Add project to metadata
- [ ] Add identities, orgs and affiliations to metadata
- [ ] Add logo to FINOS landscape
- [ ] Add project maintainers emails to finos-project-maintainers@finos.org list
- [ ] Add project maintainers GitHub usernames to the project-maintainers Team
- [ ] Onboard project on LF systems ([SFDC](https://jira.linuxfoundation.org/browse/SOPS), Insights, EasyCLA, Groups.io)

## Mailing list (optional)
- [ ] Create mailing-list
- [ ] Enable Hubspot Sync for all project mailing lists created
- [ ] Update marketing lists
  - Add new list to the included "Email List" part of the filter
  - Add new list to the excluded "Email" part of the filter
## Announcement (Lead: FINOS Contrib POC)
- [ ] Work with FINOS marketing to send out announcement to announce@finos.org , checkout announcement template at https://finosfoundation.atlassian.net/wiki/spaces/FINOS/pages/83034172/Contribute
- [ ] Notify FINOS Contrib POC and FINOS marketing manager once the announcement has been sent out (FINOS infra)

## Marketing collateral and Social (Lead: FINOS Marketing)
- [ ] Update FINOS marketing collaterals to update numbers and include the new project
- [ ] Post on FINOS social media
- [ ] Post on LF social media
- [ ] Email brief announcement to lf_staff@linuxfoundation.org (Optional depending applicability of contribution)

## Onboarding and training (Lead: FINOS Infra)
- [ ] FINOS Project Governance
- [ ] FINOS Project Lifecycle
- [ ] ODP Training

## Press Release (OPTIONAL - Lead: FINOS Marketing)
- [ ] Identify quotes for press release
- [ ] Draft press release
- [ ] Send embargoed press release to reporters
