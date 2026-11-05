### Hi, I'm Vanshaj

AI Engineer in Adelaide. I build LLM and machine learning systems and take them all the way into
production: the model, the retrieval layer, the API, the database and the cost of running it.

**What I work on**

- **Agents and tool use:** multi-tenant agent runtimes on Claude (Anthropic API and AWS Bedrock),
  with authorisation enforced in the API rather than the prompt.
- **Retrieval:** hybrid RAG over pgvector with HNSW, lexical and vector results fused by
  reciprocal rank, with source links carried into every answer.
- **Inference cost:** a model router that picks the cheapest model able to answer and logs
  every routing decision.
- **Computer vision on device:** YOLO detectors and disease classifiers exported to TFLite, ONNX
  and CoreML, built to fail safe with "unknown" rather than a guess.
- **Analytics:** a multi-tenant event pipeline for 41 organisations over ~2 million events.

Most of that work is private client code. The repos here are my own projects and open source
contributions.

**Projects**

- [crysto-markets](https://github.com/vanshaj1999/crysto-markets): a demo trading agent on
  Cloudflare Workers. Rule-based strategies, a D1 ledger, MCP tools for Claude, paper trading only.
- [fitbit-googlehealth-mcp](https://github.com/vanshaj1999/fitbit-googlehealth-mcp): an MCP server
  for Fitbit and the Google Health API, with insights and a dashboard.
- [vanshajkakkar.com](https://github.com/vanshaj1999/vanshajkakkar.com): my site, with an
  "ask about my work" agent behind a budget and a reviewed answer cache.

**Open source**

- [awslabs/stickler #536](https://github.com/awslabs/stickler/pull/536): share validation and
  build logic between model factories
- [rajfirke/provena #259](https://github.com/rajfirke/provena/pull/259): derive the PostgreSQL
  advisory lock key from the trail
- [tachibanayu24/fitbit-googlehealth-mcp #1](https://github.com/tachibanayu24/fitbit-googlehealth-mcp/pull/1):
  Google Health API provider

**Stack:** Python, FastAPI, TypeScript, PostgreSQL, MongoDB, pgvector, AWS serverless with CDK,
Cloudflare Workers, Docker.

[vanshajkakkar.com](https://vanshajkakkar.com) ·
[LinkedIn](https://www.linkedin.com/in/vanshaj-kakkar)
