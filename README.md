<p align="center">
  <h1 align="center">Measuring Harm Uplift on Dangerous Knowledge Queries</h1>
  <p align="center"><strong>Build a local red-team harness that measures uplift on dangerous-knowledge style queries with safety gates.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Measuring Harm Uplift on Dangerous Knowledge Queries**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Build a local red-team harness that measures uplift on dangerous-knowledge style queries with safety gates.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
