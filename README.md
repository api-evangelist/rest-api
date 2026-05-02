# REST API

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
