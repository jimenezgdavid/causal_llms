# Semantic Engine for Causal Inference and Discovery (SECID)

We want to test the idea of the LLM as a causal model discovery agent. We want to understand how using descriptions of each column can change the structure of the SCM proposed by the LLM. 

## Tasks

- [ ] Get datasets and problems previously solved for causal inference.
- [ ] Solve these problems with python code.

## Hypotheses

An LLM can:
- answer the human causal query.
  - translate a human causal query into a formal causal query.
- generate a hypothetical causal DAG structure to answer the causal query.
- check in a set of data structures if the query can be answered with the current data or not.
- write a causal inference program using the DAG and structure of the data.
- run the program
- answer the query

## References

- https://github.com/AMLab-Amsterdam/CEVAE/tree/master
- https://rdrr.io/cran/qte/man/lalonde.html#heading-0
