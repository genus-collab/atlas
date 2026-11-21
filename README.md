# GENUS · atlas

A curated, cross-strand collection of the collaboration's conjectures, open
questions, examples, counterexamples and computed invariants
(Gopakumar–Vafa/BPS invariants, DT and PT counts, partition functions, …).

Every entry records its **status label**, its **conventions and normalisations**,
its **provenance** (the project that produced it) and the **code** that reproduces it.

```
conjectures/      one YAML file per conjecture or open question
examples/         examples and counterexamples
invariants/       tables of computed invariants (CSV + companion YAML)
schema/           entry schemas
```

## Status labels

| Label | Meaning |
|---|---|
| `conjectural` | Stated without proof or decisive evidence |
| `numerically supported` | Supported by computation, not proved |
| `AI-proposed, unchecked` | An AI-produced argument no human has yet checked |
| `proved (human-checked)` | Checked by a contributor independent of the argument's originator |
| `formally verified` | Machine-checked, with the formal statement validated by a subject expert |

## Contributing

Open a PR adding an entry that follows `schema/`. Entries must link back to a
workshop project. The atlas is maintained by a standing infrastructure working group.
