# Scoped Negation Benchmark (ScoNe)

## Description

This repository contains the ScoNe-NLI and ScoNe-NLG datasets introduced in the ScoNe paper.

## ScoNe-NLI

ScoNe-NLI contains contrast sets of five examples where entailment relations are impacted by the scope of one or two negations. The five splits have 1202 examples each:

* `one_scoped.csv`: One negation that scopes over the relevant lexical item
* `one_non_scoped.csv`: One negation that does not scope over the relevant lexical item. 
* `scoped_and_non_scoped.csv`: Two negations, but only one scopes over the relevant lexical item.
* `two_non_scoped.csv`: Two negations, neither scope over the relevant lexical item. 
* `two_scoped.csv`: Two negations, one scopes over the relevant lexical item, but the second scopes over the first, canceling it out. 

## ScoNe-NLG

ScoNe-NLG is a natural language generation dataset that contains 74 contrasting triplets of examples where half-completed naturalistic narratives that have different coherent completions depending on the presence and scope of a negation.

## Language

English
