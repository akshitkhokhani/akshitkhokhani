# Akshit Khokhani

**AI infrastructure · Backend systems · Open-source engineering**

I build the infrastructure that makes AI systems reliable: data pipelines, inference services, persistent state, and the APIs around them. I work from a reproducible problem to a tested implementation, then stay involved through review and integration.

[LinkedIn](https://www.linkedin.com/in/akshitkhokhani) · [Email](mailto:akshitkhokhani20@gmail.com) · [Open-source contributions](https://github.com/pulls?q=is%3Apr+author%3Aakshitkhokhani+is%3Amerged+-user%3Aakshitkhokhani)

## Selected merged contributions

| Project | Contribution |
| --- | --- |
| **PyTorch TensorDict** | [Avoid unnecessary dataset reads when listing lazy HDF5 keys](https://github.com/pytorch/tensordict/pull/3208). |
| **OpenClaw** | [Wait for expired MCP session recovery on the next explicit call](https://github.com/openclaw/openclaw/pull/177427), without replaying the failed call; [prevent duplicate CLI progress replies in session history](https://github.com/openclaw/openclaw/pull/177417). |
| **Meta's Muse Gadget SDK** | [Keep rejected device registration from being treated as successful](https://github.com/facebookincubator/muse-gadget-sdk/pull/82). |
| **REA** | [Honor JavaScript `module-sync` package exports](https://github.com/morluto/rea/pull/1361). |

## Larger contributions in progress

- **[SGLang: native gRPC health checks](https://github.com/sgl-project/sglang/pull/46665)** — add standard `Check` and `Watch` endpoints with shared, bounded probes of scheduler activity. **Open PR.**
- **[ComfyUI: persistent execution history](https://github.com/Comfy-Org/ComfyUI/pull/17330)** — retain completed workflow records across restarts, with retention controls, transactional deletion, and privacy-aware storage. **Open PR.**
- **[Chroma: native sparse search](https://github.com/chroma-core/chroma/pull/7949)** — add exact sparse search to the embedded query path. **Draft PR.**
- **[LanceDB: streaming checkpoint provenance](https://github.com/lancedb/lancedb/pull/4640)** — make checkpoint identity and restore compatibility explicit. **Draft PR.**

- **[SkyPilot: Vast direct TCP ports](https://github.com/skypilot-org/skypilot/pull/11202)** — configure creation-time port mappings and discover provider-reported endpoints, preserving the legacy 8080 fallback. **Draft PR.**
- **[Dagster: multiprocess worker lifetime limits](https://github.com/dagster-io/dagster/pull/34355)** — add opt-in worker timeouts, confirming worker exit before retries or slot reuse. **Open PR.**

## Projects I build

- **[zero-hour](https://github.com/akshitkhokhani/zero-hour)** — supply-chain incident triage for coding agents, connecting security advisories to dependency and file-level evidence.
- **[Japanese OCR for RAG](https://github.com/akshitkhokhani/jp-ocr-rag)** — extract Japanese PDFs into traceable text for retrieval pipelines, processing large documents page by page.

## Engineering focus

My work spans machine learning, backend services, and cloud infrastructure: forecasting, recommendation systems, document intelligence, APIs, and deployment automation. I focus on correctness under failure, measurable performance, and compatibility with the systems people already use.

**Tools:** Python, TypeScript/JavaScript, Go, FastAPI, PostgreSQL, AWS, Docker, and GitHub Actions.

M.S. in Computer Science, New York Institute of Technology · B.Tech. in Computer Engineering, UKA Tarsadia University.

Building AI infrastructure or working through a difficult systems problem? [Let's talk](mailto:akshitkhokhani20@gmail.com).
