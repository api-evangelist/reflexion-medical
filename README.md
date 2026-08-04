# RefleXion Medical

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

RefleXion Medical is a privately held therapeutic oncology company headquartered in Hayward, California, founded in 2009 by Sam Mazin and Akshay Nanduri around the biology-guided radiotherapy (BgRT) concept conceived at Stanford University in 2007. It designs, manufactures and commercializes the RefleXion X1 radiotherapy platform and SCINTIX biology-guided radiotherapy, which uses onboard PET detectors to sense emissions from an injected radiopharmaceutical and autonomously direct external-beam radiotherapy with sub-second latency. The X1 was FDA cleared for SRS, SBRT and IMRT in 2020; SCINTIX therapy was FDA cleared in February 2023 for tumors in the lung or bone.

## API surface

**None published.** As of 2026-08-02, RefleXion publishes no developer portal, API documentation, SDKs, or machine-readable contract. Probes of `reflexion.com` for `/openapi.json`, `/swagger.json`, `/api-docs`, `/llms.txt`, `/.well-known/security.txt`, `/.well-known/openid-configuration`, `/.well-known/oauth-authorization-server`, `/.well-known/api-catalog`, `/.well-known/ai-plugin.json`, `/.well-known/agent-card.json` and `/.well-known/agent.json` all returned HTTP 404, and `api.`, `developer.`, `docs.`, `status.` and `trust.reflexion.com` do not resolve. See `well-known/reflexion-medical-well-known.yml` for the probe log.

## Artifacts

- `conformance/` — regulatory and standards posture (OIG guidance, AdvaMed Code, California H&S Code, FDA clearances).
- `security/` — probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC for reflexion.com.
- `well-known/` — negative discovery probe log.
- `llms/` — generated llms.txt.

## Links

- https://reflexion.com/
- https://reflexion.com/scintix-therapy/
- https://forgeglobal.com/reflexion-medical_stock/
