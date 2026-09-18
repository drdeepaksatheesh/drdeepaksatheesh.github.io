# Open Research Charter

This charter defines the default principles for projects maintained by Dr Deepak S.

## Purpose

The goal is to build scientific and educational tools that can be inspected, reproduced, adapted, and used without dependence on a single institution, vendor, laboratory, or proprietary workflow.

The four standing principles are:

**Open-source · Decentralized · Reliable · Reproducible**

These principles apply to software, teaching tools, data workflows, analysis methods, instrumentation projects, and publication-linked releases unless a project documents a specific reason for an exception.

## 1. Open-source

Released scientific tools should expose the source necessary to understand and reproduce the released result.

Projects should:

- use a clear open license;
- preserve third-party licenses and attribution;
- make released analysis logic inspectable;
- publish documentation alongside code;
- visibly acknowledge datasets, investigators, repositories, and upstream projects;
- keep paper-linked versions available as immutable snapshots.

Openness does not require every unfinished experiment or private development branch to be public in real time. It does require that scientific claims made from a released tool remain independently inspectable.

## 2. Decentralized

A user should not have to depend on the original author, institution, cloud account, vendor, or proprietary file format to keep using a released tool.

Projects should prefer:

- local-first or offline-capable workflows where practical;
- browser-accessible/static tools where practical;
- standard, documented data formats;
- exportable raw and processed data;
- modular hardware and software interfaces;
- replaceable models, devices, and analysis components;
- no hidden telemetry or mandatory cloud service;
- workflows that another laboratory or teacher can reproduce independently.

A vendor may be supported, but should not become the identity of the scientific method.

## 3. Reliable

A tool should make only the claims supported by the evidence available for that version.

Projects should:

- benchmark calculations against trusted reference data or established methods;
- add automated tests for important numerical and provenance logic;
- preserve raw data and distinguish it from processed data;
- make transformations visible;
- report limitations and failed cases;
- use explicit maturity labels such as demo, beta, validated, or paper release;
- avoid clinical or diagnostic claims unless separately validated for that purpose;
- prefer a visible unsupported/error state over a fabricated or silently substituted result.

Reliability is evidence, not appearance.

## 4. Reproducible

A reader should be able to determine exactly how a published or demonstrated result was produced.

Publication-linked work should record, where applicable:

- exact software version and commit;
- input dataset and exact records/subset;
- dataset version, DOI or persistent identifier;
- source institution and investigators;
- license/reuse terms;
- sampling rate, units, and known preprocessing;
- parameters and transformations;
- expected outputs and benchmark metrics;
- environment/dependency versions;
- checksums or hashes where useful;
- frozen release/tag associated with the paper.

If a result cannot be reproduced from the information released, the reproducibility work is not finished.

## Data and attribution

Open does not mean attribution-free.

Every project using external data should make provenance visible. A user should be able to answer:

> Where did this come from, who produced it, under what terms may it be reused, what did this project change, and which version produced the displayed result?

Where redistribution is not permitted, tools should link to or retrieve from the authoritative source rather than silently republishing the data.

## Publication principle

Projects may grow as connected systems, but each standalone publication should have an independently meaningful scientific, technical, or educational question.

Do not create papers merely because software has multiple modules.

A separate publication should normally add a distinct:
- scientific question;
- validation problem;
- dataset or experiment;
- educational hypothesis;
- primary outcome; or
- independently useful instrument.

The long-term record should look like cumulative scientific construction, not fragmented reporting.

## Accessibility

Accessibility is a consequence and test of the four principles.

A strong project should move toward a state in which another student, teacher, researcher, or laboratory can use it without needing privileged institutional access, expensive proprietary software, or direct help from the original author.

## Default release standard

Before a public scientific release, ask:

1. Is the source open?
2. Can someone else run it without depending on us?
3. Is the claim supported by tests or reference evidence?
4. Can the exact result be reproduced?
5. Are all external contributors, datasets, and upstream projects visibly acknowledged?

If the answer to any of these is no, the release is not complete.
