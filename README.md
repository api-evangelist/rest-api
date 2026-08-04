# REST API

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

Representational State Transfer (REST) is an architectural style for designing networked applications using standard HTTP methods and stateless communication between client and server. REST APIs define how client and server applications communicate over the web using GET, POST, PUT, DELETE, and PATCH methods against resource-oriented URLs. REST is the dominant API paradigm, used by 89% of organisations as their primary API format. This index covers the REST API landscape including specifications, tools, frameworks, best practices, and educational resources.

**Website:** [restfulapi.net](https://restfulapi.net)  
**Original Dissertation:** [Roy Fielding — REST Architectural Style](https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm)

## Tags

`Architecture` `HTTP` `Web Services` `REST` `API Design`

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## Artifacts

| Type | Name | Link |
|---|---|---|
| Vocabulary | REST API Vocabulary | [vocabulary/rest-api-vocabulary.yml](vocabulary/rest-api-vocabulary.yml) |
| JSON-LD Context | REST API Context | [json-ld/rest-api-context.jsonld](json-ld/rest-api-context.jsonld) |

## Core REST Constraints

REST is defined by six architectural constraints:

1. **Client-Server** — Separation of concerns between UI and data storage
2. **Stateless** — Each request contains all information needed; no session state on server
3. **Cacheable** — Responses must define themselves as cacheable or non-cacheable
4. **Uniform Interface** — Standardized interface between components
5. **Layered System** — Client cannot tell whether it's connected directly to the end server
6. **Code on Demand** — Optional: servers can extend client functionality via scripts

## Key Concepts

- **Resources** — Named information entities addressed via URIs
- **HTTP Methods** — GET (read), POST (create), PUT (replace), PATCH (modify), DELETE (remove)
- **Status Codes** — 2xx success, 3xx redirect, 4xx client error, 5xx server error
- **Content Negotiation** — Accept and Content-Type headers for format agreement
- **HATEOAS** — Hypermedia links in responses enabling dynamic navigation

## Maintainers

**Kin Lane** — kin@apievangelist.com
