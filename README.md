# HydrAS
This repository is an overview of research activities in the project "Methods for Hypothesis-driven Analysis of Sequential Data (HydrAS)". 
HydrAS is a DFG funded project starting 2022 and running for three years. 

## Thematic description

Increased availability of large-scale digital trace data on human behavior requires the development of suitable algorithmic approaches in the fields of computer and data science. Such data often comes in the form of sequences, e.g. as sequences of visited websites or locations in cities. To analyze this kind of data and extract knowledge in large scale, the applicants and others presented a novel computational approach that enables the comparison of hypotheses (derived from intuition, previous studies, or social theories) with respect to their plausibility regarding observed sequences in a Bayesian approach.

In this project, we will develop fundamentally new data analysis methods in that direction that overcome current shortcomings. In that regard, we will (1) systemize and simplify the process of hypothesis elicitation by integrating (semi-)automatic procedures for deriving interpretable base hypotheses from background knowledge and combining base hypotheses with each other. Additionally, we aim to (2) develop methods that partition data sequences in such a way that each part of the data can be succinctly described in terms of background information on the features, and the transition behavior in each partition can be explained by given hypotheses in order to account for heterogeneity in the data. Finally, we (3) extend the general framework of hypothesis-based analysis of sequential data, which currently focuses on simple first-order Markov Chain models to more complex models such as Hidden Markov chain models, continuous time Markov chain models or neural networks for sequential data. This would allow to formalize more complex and more fine-grained hypotheses, to pick models that are most suitable for a specific scenario, and integrate additional information (e.g., time information) in an easily understandable way.

In contrast to many recently proposed methods in the field of data science and machine learning, our research will not focus on methods that yield the maximum predictive power. Instead, we concentrate on finding potential explanations of the data generation process that can be understood by human domain experts through incorporating their hypotheses directly into the analysis process. In that regard, it will provide unique opportunities to integrate hypothesis-driven data analysis on one hand with advanced machine learning techniques on the other hand to support the understanding of the underlying processes generating the observed sequences. While this project focuses on developing new data science methods for analyzing human behavior, we expect these to be easily transferable to other application areas featuring sequential data

## Staff

The following persons are involved in this project:

[Tobias Koopmann](https://www.informatik.uni-wuerzburg.de/datascience/staff/koopmann/)
[Elisabeth Fischer](https://www.informatik.uni-wuerzburg.de/datascience/staff/elisabeth-fischer/)
[Prof. Dr. Andreas Hotho](https://www.informatik.uni-wuerzburg.de/datascience/staff/hotho/)

## Publications

The following publications are related to this project:

Philipp Singer, Denis Helic, Andreas Hotho, Markus Strohmaier
[HypTrails: A Bayesian Approach for Comparing Hypotheses About Human Trails on the Web](https://dl.acm.org/doi/abs/10.1145/2736277.2741080)
Proceedings of the 24th International Conference on World Wide Web, 2015

Florian Lemmerich, Martin Becker, Philipp Singer, Denis Helic, Andreas Hotho, Markus Strohmaier
[Mining Subgroups with Exceptional Transition Behavior](https://dl.acm.org/doi/10.1145/2939672.2939752)
Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 2016

Martin Becker, Florian Lemmerich, Philipp Singer, Markus Strohmaier, Andreas Hotho:
[MixedTrails: Bayesian hypothesis comparison on heterogeneous sequential data](https://link.springer.com/article/10.1007/s10618-017-0518-x)
Data Min. Knowl. Discov. 31(5): 1359-1390 (2017)

Martin Becker, Kathrin Borchert, Matthias Hirth, Hauke Mewes, Andreas Hotho, Phuoc Tran-Gia
[MicroTrails: comparing hypotheses about task selection on a crowdsourcing platform](https://dl.acm.org/doi/10.1145/2809563.2809608)
Proceedings of the 15th International Conference on Knowledge Technologies and Data-driven Business, 2015

Martin Becker, Philipp Singer, Florian Lemmerich, Andreas Hotho, Denis Helic, Markus Strohmaier
[Photowalking the city: comparing hypotheses about urban photo trails on Flickr](https://link.springer.com/chapter/10.1007/978-3-319-27433-1_16)
Social Informatics, Volume 9471 of the series Lecture Notes in Computer Science, 2015

Florian Lemmerich, Martin Becker, Philipp Singer, Denis Helic, Andreas Hotho, Markus Strohmaier
[Mining Subgroups with Exceptional Transition Behavior](https://dl.acm.org/doi/10.1145/2939672.2939752)
Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 2016

Thomas Niebler, Martin Becker, Daniel Zoller, Stephan Doerfel, Andreas Hotho
[FolkTrails: Interpreting Navigation Behavior in a Social Tagging System](https://dl.acm.org/doi/10.1145/2983323.2983686)
Proceedings of the 25th ACM International on Conference on Information and Knowledge Management, 2016

Martin Becker, Hauke Mewes, Andreas Hotho, Dimitar Dimitrov, Florian Lemmerich, and Markus Strohmaier.
[SparkTrails: A MapReduce Implementation of HypTrails for Comparing Hypotheses About Human Trails](https://dl.acm.org/doi/10.1145/2872518.2889380)
Proceedings of the 15th International Conference on Knowledge Technologies and Data-driven Business, 2015


## Code 

The following code is related to this project:
[HypTrails](https://github.com/mgbckr/pytrails)
[SparkTrails](https://github.com/mgbckr/sparktrails)

## Further resources

A HypTrails tutorial can be found [here](https://nbviewer.org/github/psinger/HypTrails/blob/master/tutorial/hyptrails_tutorial.ipynb). 

