# Workable (workable)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Workable is an end-to-end hiring platform with ATS, AI sourcing, employer branding, video interviewing, assessments, and HR. The Workable REST API (v3) exposes jobs, candidates, stages, members, departments, custom attributes, offers, assessments, and webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/workable/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/workable/refs/heads/main/apis.yml)

## Tags

- HR
- ATS
- Recruiting
- Sourcing
- Video Interviews
- Assessments
- SaaS

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Workable Jobs API

Create, read, update, and publish job postings. Jobs are the core organizing entity in Workable; pipelines, candidates, members, and activities are scoped to a job shortcode.

#### Tags

- Jobs
- Postings

#### Properties

- [Documentation](https://workable.readme.io/)
- [API Reference](https://workable.readme.io/reference)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Candidates API

Create candidates from external sources, retrieve candidate profiles, and update profile data, resumes, cover letters, and source attribution.

#### Tags

- Candidates
- Applicants

#### Properties

- [Documentation](https://workable.readme.io/)
- [API Reference](https://workable.readme.io/reference)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Stages API

Read pipeline stages configured for a job and move candidates between stages (sourced, applied, phone screen, interview, offer, hired).

#### Tags

- Stages
- Pipeline

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Members API

Manage Workable team members, recruiter accounts, and the per-job collaborators (hiring managers, interviewers, reviewers).

#### Tags

- Members
- Recruiters
- Users

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Recruiters API

Manage external agency recruiters who can submit candidates against Workable jobs.

#### Tags

- Recruiters
- External

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Departments API

Read the company's department list used to scope job postings and reporting.

#### Tags

- Departments
- Org Structure

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Custom Attributes API

Define and read custom attributes attached to candidates, jobs, and requisitions for tenant-specific reporting and automation.

#### Tags

- Custom Attributes
- Metadata

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Activities API

Read activity-log entries for candidates and jobs (stage moves, comments, evaluations) for audit and integration use cases.

#### Tags

- Activities
- Audit

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Comments API

Add and read free-form comments and @-mentions on candidate profiles for collaboration with hiring teams.

#### Tags

- Comments
- Notes

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Evaluations API

Submit and read interviewer evaluations and scorecards aligned to the job's interview kit.

#### Tags

- Evaluations
- Scorecards
- Feedback

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Offers API

Generate and track offers including templates, compensation breakdowns, and offer letter PDFs.

#### Tags

- Offers

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Assessments API

Trigger and read candidate assessments delivered through Workable's assessment platform (Assessments+).

#### Tags

- Assessments
- Tests

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Disqualification Reasons API

List configured disqualification reasons used when rejecting a candidate (not a fit, withdrew, declined offer, hired elsewhere).

#### Tags

- Disqualification
- Rejection

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Questions API

Manage application form questions per job, including knockout questions and EEO surveys.

#### Tags

- Questions
- Application Forms

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Events API

Read and create scheduled events (phone screens, interviews) for a candidate, integrated with Workable's calendar sync.

#### Tags

- Events
- Interviews
- Scheduling

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Webhooks API

Subscribe to Workable events (candidate.created, candidate.moved, candidate.hired, candidate.disqualified, member.created) for downstream automation.

#### Tags

- Webhooks
- Subscriptions

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workable Public Jobs API

Read-only public endpoint that exposes published jobs for embedding job listings on external careers pages without authentication.

#### Tags

- Jobs
- Public

#### Properties

- [Documentation](https://workable.readme.io/)
- [Postman Collection](collections/workable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/workable-software)
- [Website](https://www.workable.com/)
- [Documentation](https://workable.readme.io/)
- [API Reference](https://workable.readme.io/reference)
- [Pricing](https://www.workable.com/pricing)
- [Login](https://www.workable.com/login)
- [Status Page](https://status.workable.com/)
- [Blog](https://resources.workable.com/)
- [Support](https://help.workable.com/)
- [GitHub Organization](https://github.com/Workable)
- [Privacy Policy](https://www.workable.com/privacy-policy)
- [Terms of Service](https://www.workable.com/terms)
- [Plans](plans/workable-plans-pricing.yml)
- [Rate Limits](rate-limits/workable-rate-limits.yml)
- [Fin Ops](finops/workable-finops.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
