---
layout: archive
title: "Code and Data"
permalink: /code/
author_profile: true
redirect_from:
  - /data
---

{% include base_path %}

## SimpleNLG-ZH

SimpleNLG-ZH is a realisation engine for Mandarin that follows the software design paradigm of SimpleNLG, i.e., keeping a clear separation between morphological and syntactic operations. Mandarin, as a highly analytical language, needs far fewer morphological operations but many more syntactic constraints than English. SimpleNLG-ZH (“Zhongwen” is Mandarin for “Chinese'”) was first built as a realiser for generating referring expressions in Mandarin which are mostly noun phrases together with simple verb phrases, and then extended to cover other constructions and phenomena in Mandarin. The current version of SimpleNLG-ZH was developed as an adaptation from V4.4.8 of the original [SimpleNLG](https://github.com/simplenlg/simplenlg).

The source code of SimpleNLG-ZH (written in Java) can be downloaded at: [here](https://github.com/a-quei/simplenlg-zh).

**References**:

Chen G., van Deemter K., and Lin C. *SimpleNLG-ZH: a Linguistic Realisation Engine for Mandarin*, The 11th International Conference on Natural Language Generation, Tilburg,  Netherlands, 2018.

<br>

## QTUNA


QTUNA is a series of elicitation experiments in which human speakers were asked to perform a linguistic task that invites the use of quantified expressions in order to inform a possible Natural Language Generation algorithms that mimic humans' use of quantified expressions. This work was inspired by a line of work focusing one specific class of noun phrases, i.e., referring expression, where they focus on corpora of referring expressions  that  were  elicited  under  experimentally  controlled  conditions (e.g., [TUNA](https://www.abdn.ac.uk/ncs/departments/computing-science/tuna-318.php) experiment), but aiming  this  time  to  gain  insights into quantified noun phrases.

The dataset yielded from the QTUNA experiments can be found at: [here](https://github.com/a-quei/qtuna).

**References**:

Chen G., van Deemter K., Pagliaro S., Smalbil L. and Lin C.  *QTUNA: A Corpus for Understanding How Speakers Use Quantification*, The 12th International Conference on Natural Language Generation,  Tokyo, 2019.

<br>

## Quantified Description Generation

We designed two quantified description generation (QDG) algorithms, namely, the incremental algorithm and the greedy algorithm, for simulating human production of quantified expressions, and for reproducing descriptions in the [QTUNA dataset](https://github.com/a-quei/quantified-description-generation).

Given a target scene with its domain knowledge, the generator constructs a set containing all possible scenes in the same domain as the target scene. The generator then calls a QDG algorithm to construct a description containing a set of QEs. The algorithm selects from a set of candidate quantified patterns, based on the common knowledge by mimicking how human beings did so in the QTUNA experiment. Finally, a simple template-based surface realiser is called to map the description (in logical form) into natural language text.

The source code (written in Python) can be downloaded at: [here](https://github.com/a-quei/quantified-description-generation).

**References**:

Chen G., van Deemter K. and Lin C. *Generating Quantified Descriptions of Abstract Visual Scenes*, The 12th International Conference on Natural Language Generation,  Tokyo, 2019.