## Hi, I'm Karthik

Sr. Technical Program Manager with ~19 years in tech. Currently focused on privacy and compliance engineering.

### Background

I've spent the last few years as the single-threaded leader for Privacy, DMA, DSA, and Accessibility compliance across a large shopping organization. That means working across legal, engineering, and central privacy teams to ensure things like DSAR, data deletion, and Privacy by Design are actually happening — not just documented.

Before that, I built and scaled a 3P vendor operations function from scratch — grew it from 1 analyst to a full team, launched 4 standalone services, and scaled coverage from 22 to 165+ vendors supporting ~$190M in annual contracts. Also owned SSO implementation across 30+ vendor systems after identifying a gap in security compliance.

Earlier in my career, I managed 24/7 support for Microsoft Identity Services handling ~850M users and ~3B transactions/week. Started out hands-on with livesite operations, deployments, and patching across 18,000+ servers.

M.S. in Software Engineering from BITS Pilani. CIPM, CSPO, CSM, and ITIL certified.

### What I Built Recently

Compliance attestation reviews in our org were completely manual — each one taking 30-60 minutes, with 1,400+ applications to cover. Instead of just scoping it out and handing it off, I decided to build the solution.

The result is a production system that pulls data from a 150M+ row data warehouse, caches it in DynamoDB with S3 overflow for oversized items, and runs LLM-powered reviews automatically. Also built an MCP server so AI agents can use the tools directly, and a browser overlay that renders findings on attestation pages.

Hit some real technical blockers along the way — data warehouse federation trust issues, massive query timeouts, a boolean encoding bug that silently corrupted the entire cache. Figured out workarounds for all of them and documented the solutions.

I open-sourced a generic version of the architecture here:

🔗 [compliance-copilot](https://github.com/karkuku7/compliance-copilot) — Full stack reference architecture with data extraction pipeline, serverless cache API, LLM review engine, MCP server, CDK infrastructure, property-based tests, and detailed docs on design decisions and roadblocks.

### How I Work

I use AI-assisted development as a force multiplier — I drive the architecture and decisions, AI helps me move fast on implementation. I think this is where technical leadership is headed.
