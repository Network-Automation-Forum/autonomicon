# *Autonomicon* Glossary

A glossary of terms used by and within NAF. If you'd like to contribute to, or see revisions to some of these terms, discussion occurs in Network Automation Forum Slack in channel #doc-autonomicon.

---

**Automation**
> Software or other tooling designed to complete a task with no human intervention

**Idempotent**
> A process or task that can be run multiple times and always reach the desired outcome

**Orchestration**
> Software or other tooling designed to complete a series of tasks with no human intervention in a workflow based on a defined set of inputs

**System of Origin (SoO)**
> The system that users interact with to create new data points. It is sometimes the SoR, but is always tightly coupled to the business process that manages the data within a domain.

**System of Record (SoR)**
> This is the primary reference point that is authoritative for a particular data domain.

**Source of Truth (SOT)**
> The single aggregated state representing holistic network automation. Often integrates or incorporates SoR data and offers additional relationships[^1] between data across data domains.

**Workflow**
> A series of ordered tasks, with potentially conditional execution, designed to complete a work process with minimal or no human intervention

[^1]: Such as relationship with interfaces and IP addresses that may not exist in a single SoR.
