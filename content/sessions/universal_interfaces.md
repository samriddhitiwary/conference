---
key: universal_interfaces
title: Universal Interfaces - Turning Schemas into IDEs, UIs, CLIs and LLM Contracts
id: universal_interfaces
format: talk
duration: 25
tags:
  - talk
  - tooling
speakers_info:
  - name: "Daniel Marcotte"
    company: "Engineer at KSON"
    city: ""
    photoURL: "/images/speakers/Speakers-2025/Daniel Marcotte.jpeg"
draft: false
---

Configuration files are now the primary UI for everything from Kubernetes to AI‑driven pipelines to new tools every day. And this trend has only accelerated in the AI era where everything wants to be text. But is text always the best interface? This talk shows how we can have our text and eat it too.

We'll explore how a single JSON Schema can be the single source of truth that unlocks the full spectrum of computer interfaces for both humans and machines:

- an IDE experience (autocomplete, hover docs, validation)
- a CLI validator (instant “‑‑check” style validation)
- a UI generator (web forms, dashboards, wizard‑style editors)
- an LLM contract (structured input/output for determinism)

... all without inventing a proprietary format or building custom tooling.

This talk walks through concrete approaches and tools to accomplish all this for JSON and YAML, plus we'll also take a look at KSON, which was designed around these exact principles with JSON Schema integration right at its core to facilitate creating and maintaining these Configuration User Interfaces.