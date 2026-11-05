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

- [crysto](https://github.com/vanshaj1999/crysto): my personal AI system. Claude Code, Codex and
  free models work as one team through shared files, a claim protocol and MCP connectors.
- [rag-eval-lab](https://github.com/vanshaj1999/rag-eval-lab): hybrid RAG over the Python
  PEPs on pgvector, measured on 50 labelled questions. Vector search beat lexical (0.70 against
  0.36 recall@1), and RRF hybrid did not beat vector on top-1.
- [edge-vision-failsafe](https://github.com/vanshaj1999/edge-vision-failsafe): an on-device leaf
  disease classifier that answers "unknown" instead of guessing. YOLO11n, ONNX, CoreML and TFLite,
  with out-of-distribution rejection measured on held-out data.
- [crysto-markets](https://github.com/vanshaj1999/crysto-markets): a demo trading agent on
  Cloudflare Workers. Rule-based strategies, a D1 ledger, MCP tools for Claude, paper trading only.
- [fitbit-googlehealth-mcp](https://github.com/vanshaj1999/fitbit-googlehealth-mcp): an MCP server
  for Fitbit and the Google Health API, with insights and a dashboard.
- [vanshajkakkar.com](https://github.com/vanshaj1999/vanshajkakkar.com): my site, with an
  "ask about my work" agent behind a budget and a reviewed answer cache.

**Open source**

- [awslabs/social-messaging-agent-runtime-toolkit #97](https://github.com/awslabs/social-messaging-agent-runtime-toolkit/pull/97)
  and [#98](https://github.com/awslabs/social-messaging-agent-runtime-toolkit/pull/98): voice note
  languages in the assistant blueprint, and a delete confirmation in the admin console
- [awslabs/stickler #536](https://github.com/awslabs/stickler/pull/536): share validation and
  build logic between model factories
- [rajfirke/provena #259](https://github.com/rajfirke/provena/pull/259): derive the PostgreSQL
  advisory lock key from the trail
- [tachibanayu24/fitbit-googlehealth-mcp #1](https://github.com/tachibanayu24/fitbit-googlehealth-mcp/pull/1):
  Google Health API provider

**Writing**

- [I gave 9 free AI coding models the same real bug](https://dev.to/vanshaj1999/i-gave-9-free-ai-coding-models-the-same-real-bug-here-is-what-happened-pk3):
  hidden tests, diff review, and what the green test runs did not show

**Stack:** Python, FastAPI, TypeScript, PostgreSQL, MongoDB, pgvector, AWS serverless with CDK,
Cloudflare Workers, Docker.

[vanshajkakkar.com](https://vanshajkakkar.com) ·
[LinkedIn](https://www.linkedin.com/in/vanshaj-kakkar)
