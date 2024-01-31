---
layout: page
title: IPOL MLBriefs — Call for Papers
cover: false
---

Submissions consist of an online demo of a method, with a paper describing and analysing the method. Starting from a working code, you will be taught how to create a demo during the workshop. The companion paper describes the method and experiments on it.

* Contrary to many workshops, you are invited to prepare your submission **during** the workshop. You will be given time to submit the paper after the workshop ends.
It is **not** expected that you submit the paper before the workshop starts.
* IPOL and MLBriefs publications usually act as companions to more traditional publications. It is allowed, and even encouraged, to submit an article covering an already-published method.
Please check our [authorship and double submission policy below](#dual) for more information.
* Due to the growing number of submissions, all authors may be asked to review several papers.
{:.note}

## Submission areas
Areas of submission are broad; the IPOL journal mainly focuses on (but is not limited to):
* Image and video processing
* Computer vision
* Machine learning
* Signal processing

## Tracks
Papers can be submitted to different tracks. The IPOL tracks are open year-long (Check the [IPOL](https://www.ipol.im) website to submit), while the MLBriefs track will open during the workshop and stay open for at least one month after the workshop ends.

### MLBriefs track
In this track, authors submit an online demo accompanied by a typically short paper (around 5 single-columns pages) describing the method.
The paper is expected to contain a description of the implemented method and its parameters, as well as mainly qualitative experiments that highlights its strengths and shortcomings.
In the MLBriefs tracks, only the paper and the demo are peer-reviewed; the implementation itself is not peer-reviewed.
The code that is used for the demo does not necessarily needs to be the authors' code, as long as the licence of the code is respected.

### MLBriefs Survey track
A Survey track submission is more extensive than an MLBriefs track paper. In the Survey track, several methods are compared in one paper. One demo per method is usually expected, although one demo may regroup several methods if they are deemed close enough.
In addition to the description of each method and its parameters, the submitted paper should compare the different methods at all stages:

* There should be an analysis of how the methods differ, and how it can affect their results
* The qualitative experiments should be done comparatively, to explain the differing results, use cases, and limitations. If possible, those results should be linked to the theoretical analysis to explain why the results differ.
* In the survey track, quantitative, comparative experiments are usually expected as well, if possible on varied datasets.

Even more so than for the single-method track, the experiments should be done with critical thinking, and the paper should discuss how possible biases and different processing of use cases can alter the comparisons. The paper should also verify and mention if any of the tested methods were actually trained on this data.

When preparing a survey track submission, the choice of compared methods should also be discussed. Full exhaustivity is of course not required — some methods have no published code, or the licence prevents use in IPOL —, but there should be some reasoning behind the choice of methods (e. g. comparing methods that follow a specific approach, or recent methods to further easy experimentation on them, etc) 

### IPOL track
The IPOL track is the traditional track of IPOL submissions, and exists independently of the MLBriefs workshop.
Regular IPOL papers place are more comprehensive, and typically longer than MLBriefs papers.
The code is usually the authors' work as well.
The description of the method is expected to be exhaustive, and supported by pseudo-code descriptions.
Emphasis is placed on the reproducibility of the work:

* If a model is trained, all information related to the data and the training should be provided in the article.
* The article should contain enough information to recode the method from scratch, producing the exact same results as the submitted code.
* In addition to the paper and online demo, **the code will be peer-reviewed to ensure that the submitted code exactly matches the article description and pseudo-code.**

Due to this code peer-review requirement, note that IPOL submissions can only be considered if the code is submitted in Python, C, C++, Matlab or GNU Octave.
If you want to submit code in other languages, please contact us first: submission may still be possible depending on the available reviewers.

### IPOL dataset track
The success of algorithms depends on the quality of the data they process and on the reliable information about how these data were obtained.
The algorithms evaluation should be systematically performed on high quality data shared among many researchers.
Their properties have to be certified in the best possible way.
For this reason, IPOL welcomes the submission of datasets, with companion articles explaining thoroughly how the data have been obtained, how they can be used and with all additional information that can help researchers to use them properly. The submissions will be evaluated by referees by the same procedure as for other IPOL articles.

Although not a method, an IPOL dataset submission can be complemented by a demo as well. Depending on the dataset, this demo might help explore the dataset, or help generate new data in the case of synthetic dataset.

## Code and article licence and access
Articles published on IPOL are distributed under a [Creative Commons CC-BY-NC-SA 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) licence.
Users are free to copy, distribute, transmit and adapt the articles for non-commercial purposes if they attribute the work to the authors and maintain this license.

The codes are published along the demos under a free software licence chosen by the authors, usually [GPL](http://www.gnu.org/licenses/gpl.html), [AGPL](http://www.gnu.org/licenses/agpl.html), [LGPL](http://www.gnu.org/licenses/lgpl.html) or [BSD](http://creativecommons.org/licenses/BSD/).
As an exception, implementations of patented algorithms may be distributed with ad-hoc licencing terms.

There are no licencing fees or article processing charges for publishing to IPOL: publishing is free.

## <a name=dual></a> Dual submissions and authorship

IPOL authors do not necessarily need to be the inventors of the algorithms they publish.
IPOL authors are the authors of the online demo, a technical description of the algorithm, experiments, and possibly of the code and implementation.
IPOL publishes new, but also basic and well-known algorithms. IPOL therefore does not guarantee the novelty of the published algorithms, nor the novelty or validity of their underlying theory.
When the submitted algorithm is new, IPOL encourages a parallel submission by the authors to classic journals.
A submitted algorithm and code may use several other algorithms and computer programs. In that case, the authors must specify the part which is submitted to IPOL. Only this part will be evaluated.

IPOL welcomes submissions of algorithms based on theories submitted or already published in journal papers.
In particular, joint submissions to IPOL and [SIIMS](http://www.siam.org/journals/siims.php) (SIAM Journal of Imaging Science) are encouraged. Reviews are separate and independent, and acceptance/rejection of the submissions for one journal is not conditioned in any form either on the submission or acceptance/rejection on the other.

Upon acceptance, cross links between both electronic articles will be placed, so readers will be able to automatically navigate between the [SIIMS](http://www.siam.org/journals/siims.php) and IPOL complementary materials.

