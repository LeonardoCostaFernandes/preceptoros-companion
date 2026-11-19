# DECLARATION.md — LeonardoCostaFernandes / Policy Lens (working name)

**Status:** DRAFT prepared by the owner's AI assistant from facts the owner supplied; pending the owner's signature (HITL). Not authenticated, not deployed, not LIVE.

**What it is.** A local, multilingual assistant that checks content against a written platform policy and returns a structured verdict (policy clause, evidence span, decision suggestion, confidence) for a human reviewer to accept or reject. The model suggests; the human decides.

**What it solves.** Policy review across many languages depends on consistent reading of long policy texts. The assistant makes the reasoning auditable: every suggestion cites the clause and the exact text it relied on, and anything it cannot ground returns `NO_DATA(cause)`.

**For whom.** Content-policy reviewers, quality analysts and trainers who need consistent, explainable decisions, and anyone who wants to study policy reasoning on their own hardware without sending content to a cloud service.

**Stack.** Local model on the owner's machine · Qwen2.5-3B-Instruct Q4_K_M on the owner's PC · Python standard-library tools in the owner's `lab` · Claude Code (orchestrator), Junie and Grok CLI agents under HITL.

**Current state.** `CODE_EXISTS`: lab benchmark tool and tests. Local model: being installed. Policy-review pipeline: `NO_DATA(not_built)`. Android APP test: `NO_DATA(no_android_device)`.

**Privacy line.** Only synthetic or public examples enter this repository. No real user content, no employer or client material, ever.

Append-only.
