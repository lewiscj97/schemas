---
# These are optional elements. Feel free to remove any of them.
status: accepted
date: $(date --iso-8601)
deciders: @adam-moss
---

# Use Markdown Any Decision Records

## Context and Problem Statement

We want to record any decisions made in this project independent of whether the decision concerns the architecture (an "architectural decision record"), the code, or anything else deemed materially relevant.

Which format and structure should these records follow?

## Considered Options

- [MADR](https://adr.github.io/madr/) 3.0.0 - The Markdown Any Decision Records
- [Michael Nygard's template](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions) – The first incarnation of the term "ADR"
- [Sustainable Architectural Decisions](https://www.infoq.com/articles/sustainable-architectural-design-decisions) – The Y-Statements
- Other templates listed at <https://github.com/joelparkerhenderson/architecture_decision_record>
- Formless - no conventions for file format and structure

## Decision Outcome

Chosen option: "MADR 3.0.0", because

- Design documentation is important to enable people to understand decisions later on
- Implicit assumptions should be made explicit
- MADR allows for structured capturing of any decision
- The MADR format is lean and fits the development style
- The MADR structure is comprehensible and facilitates usage and maintenance

## More Information

1. [A rational design process: How and why to fake it](https://doi.org/10.1109/TSE.1986.6312940)
