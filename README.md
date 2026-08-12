# Sampler

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Sampler — legally The Sampler App Inc., of Toronto — was a digital product-sampling platform for
consumer packaged goods and retail brands. It was surfaced as a portfolio company of 500 Global and
added to the API Evangelist network as a stub for enrichment.

**This company is defunct.** Sampler filed for bankruptcy on 2024-06-27 with CAD 12.9M in
liabilities against roughly CAD 300K in assets, and ceased operations. The enrichment pipeline ran
against it on 2026-08-12 and found the entire estate decommissioned:

- `sampler.io` and `www.sampler.io` terminate the TLS handshake with an internal-error alert before
  any HTTP request is sent — reproduced from three independent SSL stacks.
- `api.sampler.io` still resolves to three stale AWS EC2 addresses, all of which refuse connections
  on tcp/80 and tcp/443.
- `docs.`, `developers.`, `app.` and `dashboard.sampler.io` are NXDOMAIN.

Sampler never published a public developer API, developer portal, documentation host, OpenAPI, or
machine-readable discovery surface. The `api.sampler.io/v1/` endpoints that appear in archived
crawls were the private backend of its consumer claim widget and internal admin console — they
answered 401/403 to anything outside that flow and were never a documented developer product.

The coverage state recorded in `apis.yml` is `none` / `defunct`. That is an honest zero: there is
no API surface here to profile, and no one to ask for one.

Backed by: 500 Global — https://sampler.io
