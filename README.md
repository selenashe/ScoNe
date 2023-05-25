# Scoped Negation Benchmark (ScoNe)

## Description

Hi! This repository contains the datasets introduced in the paper **ScoNe: Benchmarking Negation Reasoning in Language Models With Fine-Tuning and In-Context Learning.**

## ScoNe-NLI

ScoNe-NLI contains contrast sets of five examples where entailment relations are impacted by the scope of one or two negations. The five splits have 1202 examples each:

* `no_negation.csv`: No negation is present.
* `one_not_scoped.csv`: One negation that does not scope over the relevant lexical item. 
* `two_not_scoped.csv`: Two negations, neither scope over the relevant lexical item. 
* `two_scoped.csv`: Two negations, one scopes over the relevant lexical item, but the second scopes over the first, canceling it out. 
* `one_scoped.csv`: One negation that scopes over the relevant lexical item. This split contains the negated examples (NMoNLI) from Geiger et al., 2020.
* `one_scoped_one_not_scoped.csv`: Two negations, but only one scopes over the relevant lexical item.

In each file, premises and hypotheses are the columns labeled `sentence1_edited` and `sentence2_edited`. The entailment relations are in the `gold_label_edited` column. One exception is the `one_scoped.csv` file, where they are just labeled as `sentence1`, `sentence2`, and `gold_label`.

## ScoNe-NLG

ScoNe-NLG is a natural language generation dataset that contains 74 contrasting triplets of examples where half-completed naturalistic narratives that have different coherent completions depending on the presence and scope of a negation.

## Language

English

## Citing Our Work

````
@inproceedings{
````
