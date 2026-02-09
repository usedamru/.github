# Damru

**Damru** is an open-source organization focused on building **developer-first tools** for **data modeling, AI-assisted system design, and modern backend workflows**.

We build tools that help engineers **understand, reason about, and evolve complex systems** — with a strong emphasis on **determinism, explainability, and human-in-the-loop AI**.

---

## Philosophy

Damru tools follow a few core principles:

* **Deterministic by default**
  Same input → same output. No hidden magic.

* **AI as an assistant, not an authority**
  LLMs are optional, explainable, and never auto-apply changes.

* **Human-in-the-loop**
  Developers stay in control of decisions, migrations, and architecture.

* **Local-first & OSS-first**
  Tools run locally, remain inspectable, and stay open-source.

---

## Projects

### sql2nosql

**Analyze SQL databases and generate explainable NoSQL schema designs.**

`sql2nosql` helps developers understand how relational schemas translate into NoSQL models by analyzing SQL DDL and producing structured, explainable NoSQL proposals — with optional AI-powered recommendations.

**Key features:**

* SQL schema introspection (PostgreSQL)
* Deterministic SQL → NoSQL mapping
* Optional LLM recommendations (embed vs reference trade-offs)
* Migration script generation (human-run)
* HTML visualization for side-by-side analysis

Repository → [https://github.com/usedamru/sql2nosql](https://github.com/usedamru/sql2nosql)

---

## Who This Is For

* Backend & platform engineers
* Data engineers & architects
* Teams migrating from SQL to NoSQL
* Developers who want **clarity before migration**
* OSS contributors interested in data modeling & AI tooling

---

## Status

Damru is **early-stage and evolving**.
Expect:

* Rapid iteration
* Opinionated design decisions
* Clear documentation
* Strong emphasis on correctness and explainability

---

## Contributing

Contributions, ideas, and discussions are welcome.

* Open issues for bugs or feature ideas
* For large changes, start a discussion first
* Keep things deterministic, readable, and developer-friendly

---

## License

All projects under Damru are released under the **MIT License**, unless stated otherwise.

---
