# Effective Date

**Contributor**: Neel Guha (nguha@stanford.edu)

**Source**: [Atticus Project](https://www.atticusprojectai.org/cuad>)

**License**: [CC By 4.0](https://creativecommons.org/licenses/by/4.0/)

**Task summary**: Does the clause specify the date upon which the agreement becomes effective?

**Size (samples)**: 246

## Task Description

This is a binary classification task in which the model must determine if a contractual clause falls under the category of "Effective Date".

## Task Construction

This task was constructed from the [CUAD dataset](https://www.atticusprojectai.org/cuad), which annotated clauses in 500 contracts according to 41 types. Positive samples for this task correspond to clauses for which annotators answered the following question in the affirmative:

```text
Does the clause specify the date upon which the agreement becomes effective?
```

Negative samples are randomly selected from other clauses.