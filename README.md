# Joomla (joomla)

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

Joomla is a free and open-source content management system (CMS) built in PHP that includes a built-in REST API for managing core content types. The Web Services API provides JSON endpoints for articles, categories, contacts, banners, menus, modules, tags, fields, and user accounts. Authentication is handled via Bearer tokens with optional HMAC security, and every endpoint requires authentication unless explicitly marked public. Joomla is maintained entirely by volunteers and released under the GNU General Public License.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/joomla/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/joomla/refs/heads/main/apis.yml)

## Tags

- CMS
- Content Management
- Open Source
- PHP
- REST API
- Articles
- Categories
- Contacts
- Menus
- Modules
- Users

## Timestamps

- **Created:** Fri Jun 12 2026 20:00:00 GMT-0400 (Eastern Daylight Time)
- **Modified:** Fri Jun 12 2026 20:00:00 GMT-0400 (Eastern Daylight Time)

## APIs

### Joomla Web Services API

The built-in Joomla Web Services API provides RESTful JSON endpoints for managing articles, categories, contacts, banners, menus, modules, tags, custom fields, and user accounts in a Joomla installation. Authentication uses Bearer tokens issued per-user. The API is available in Joomla 4.x and later and follows the {base_url}/api/index.php/v1/ URL pattern.

- **Human URL:** [https://docs.joomla.org/J4.x:Joomla_Core_APIs](https://docs.joomla.org/J4.x:Joomla_Core_APIs)
- **Base URL:** `https://{your-joomla-site}/api/index.php/v1`

#### Tags

- Articles
- Categories
- Contacts
- Banners
- Menus
- Modules
- Users
- Tags
- Fields

#### Properties

- [Documentation](https://docs.joomla.org/J4.x:Joomla_Core_APIs)
- [Specification](https://docs.joomla.org/Joomla_Api_Specification)

## Common Properties

- [Website](https://www.joomla.org)
- [Documentation](https://docs.joomla.org/J4.x:Joomla_Core_APIs)
- [Git Hub Org](https://github.com/joomla)
- [LinkedIn](https://www.linkedin.com/company/joomla)
- [Blog](https://community.joomla.org/blogs.html)
- [Pricing](https://www.joomla.org/download.html)
- [X (Twitter)](https://twitter.com/joomla)
- [Plans](plans/joomla-plans-pricing.yml)
- [Rate Limits](rate-limits/joomla-rate-limits.yml)
- [Fin Ops](finops/joomla-finops.yml)
- [Blog Posts](blogs/blogs.json)
- [J S O Nld](json-ld/joomla.json) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
