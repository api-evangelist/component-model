# Component Model

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

The WebAssembly Component Model is a broad-reaching architecture for building interoperable WebAssembly libraries, applications, and environments. It defines components as portable, sandboxed units of code that can compose with each other across language and runtime boundaries. The model introduces interfaces, worlds, and the WebAssembly Interface Type (WIT) language, along with a canonical ABI, binary and text formats, and a concurrency model.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/component-model/refs/heads/main/apis.yml)

## Tags

- ABI, Bytecode Alliance, Component, Interface, Modular, Specification, WASI, WebAssembly, WIT, World

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

### WebAssembly Component Model Specification
The W3C WebAssembly Community Group repository for design documents, the formal specification, the WIT grammar, the canonical ABI, and the binary and text formats.

**Human URL:** [https://github.com/WebAssembly/component-model](https://github.com/WebAssembly/component-model)

#### Tags
- Specification, W3C, WebAssembly

### WebAssembly Interface Type (WIT)
The interface definition language for the Component Model. Describes imports and exports of a component using interfaces and worlds.

**Human URL:** [WIT design](https://component-model.bytecodealliance.org/design/wit.html)

#### Tags
- Bindings, IDL, Interface, WIT

### WebAssembly System Interface Preview 2
The first WASI release built on the Component Model. Defines wasi:filesystem, wasi:io, wasi:http, wasi:cli, and wasi:sockets.

**Human URL:** [https://wasi.dev/](https://wasi.dev/)

#### Tags
- System Interface, WASI, Capabilities

### Component Model Implementations
Wasmtime, Jco, wit-bindgen, cargo-component, ComponentizeJS, Spin, and other toolchains and runtimes that implement the Component Model.

**Human URL:** [https://bytecodealliance.org/](https://bytecodealliance.org/)

#### Tags
- Bytecode Alliance, Implementations, Runtimes, Toolchains

## Common Properties

- [Website](https://component-model.bytecodealliance.org/)
- [Documentation](https://component-model.bytecodealliance.org/design/)
- [GitHubRepository](https://github.com/WebAssembly/component-model)
- [GitHub Organization](https://github.com/WebAssembly)
- [WASI](https://wasi.dev/)
- [Bytecode Alliance](https://bytecodealliance.org/)
- [W3C Community Group](https://www.w3.org/community/webassembly/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
