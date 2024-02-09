---
layout: welcome
title: IPOL MLBriefs Workshop
cover: false
---

# Welcome to the 4<sup>th</sup> edition of the IPOL MLBriefs workshop
**<font size="4">May 27<sup>th</sup> — May 31<sup>st</sup>, 2024.</font>**

**<font size="4">A BPI Sesame OVDSaas project</font>**

In many fields of applied mathematics and computer science (computer vision, machine learning, image/signal processing, …), new methods and applications are appearing at a vertiginous pace, to the point it is hard to keep up with all new methods.
Yet, being able to understand and try these methods oneself is crucial for research.

To bridge this gap and promote **reproducible research**, during the IPOL MLBriefs workshop we will help you use the [IPOL journal and demo system](http://www.ipol.im/)
to **create and publish an online demo of a method** with a companion technical article describing the method and experimentally highlighting its use cases and limitations.

This workshop will be also be a great opportunity to **meet fellow researchers** and attend plenary talks from invited speakers.

**Registration is free but mandatory. Please register by filling [this form](https://docs.google.com/forms/d/e/1FAIpQLSdWX29KpiDAtGN1KnJMXO24JE4ycpcovenixJBcK-RCtWWbrw/viewform?usp=sf_link) by _March 16<sup>th</sup>_.**

# Important Dates

The workshop will be held between **May 27<sup>th</sup>** and **May 31<sup>st</sup>** 2024.

Registration is free but mandatory. You can register at [this link](https://docs.google.com/forms/d/e/1FAIpQLSdWX29KpiDAtGN1KnJMXO24JE4ycpcovenixJBcK-RCtWWbrw/viewform?usp=sf_link).

Submissions will open when the workshop start, and will close at the earliest on June 30<sup>th</sup>, 2024.

# Call for Papers


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
In this track, authors submit an online demo accompanied by a technical paper analysing and experimenting on the method.
At the very least, the paper is expected to contain a description of the implemented method and its parameters, as well as experiments (both qualitative and quantitative) highlighting its strengths and shortcomings.
The code that is used for the demo does not necessarily needs to be the authors' code, as long as the licence of the code is respected.

Even though the method does not need to be new, we expect the submitted paper to be exciting to read in addition to, or instead of, the paper describing the original method. The contributions of the submitted article towards the method should be discussed within the introduction of the paper. Such contribution can include, but is not limited to:

* **Survey:** Rather than working on a single method, create demos for an array of different methods. The paper can then analyse how the methods differ, and how it can affect the results. The qualitative and quantitative experiments should be done comparatively, to explain the differing results, use cases, and limitations. If possible, those results should be linked to the theoretical analysis to explain why the results differ. The choice of compared methods should also be discussed. Full exhaustivity is of course not required — some methods have no published code, or the licence prevents use in IPOL —, but there should be some reasoning behind the choice of methods (e. g. comparing methods that follow a specific approach, or recent methods to further easy experimentation on them, etc)
* **Simplification:** Some published methods are very interesting, but also highly technical and complicated to read, either by themselves or due to low accessibility without specific prior knowledge. Yet, these methods can often be insightful for people from other domains, that do not have the required knowledge to read the method. Therefore, articles that take a complicated method and explain it in a more simple way, or from a different point of view, can be very interesting to many people.
* **Analysis:** On the other hand, some methods that are published work very well, but it is not understood why. Theoretical and experimental analysis of where and why the method works, to better specify the use cases and limitation of the method, are welcome.
* **Method improvements and domain adaptation**: When implementing a method, you can sometimes think of small changes or improvements that lead to better results or usability of the method in new domains.


### IPOL track
The IPOL track is the traditional track of IPOL submissions, and exists independently of the MLBriefs workshop.
The description of the method is expected to be exhaustive, and supported by pseudo-code descriptions.
Emphasis is placed on the reproducibility of the work:

* If a model is trained, all information related to the data and the training should be provided in the article.
* The article should contain enough information to recode the method from scratch, producing the exact same results as the submitted code.
* In addition to the paper and online demo, **the code will be peer-reviewed to ensure that the submitted code exactly matches the article description and pseudo-code.**

The code is usually the authors' work as well, although this is not a strict requirement.

The article is complemented by a rigorous experimental analysis highlighting the use cases, strengths and limitations of the method. Papers can also explain the method from an alternative viewpoint than the original article, provide a rigorous theoretical analysis explaining why some of the strengths and limitations appear, and/or improve the method or adapt it to new domains.

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

## Page limits

There is no set minimum or hard limit to the number of pages. Authors are free to write as long a paper as they deem reasonable. Note the following point:

* Longer papers are perfectly acceptable when the contributions of the paper are extensive enough to justify it, however papers should not be needlessly long. Note that very long papers can be difficult to read for the audiance, and will also result in longer review times. When the paper is long, it becomes even more crucial that it be well-organized. Question the relevance of each part. Relevant but minor results can also be placed in an annex to simplified reading.
* Papers are expected to provide a significant contribution. There can be excellent short papers, but papers without a meaningful contribution shall be rejected
* Because there is no hard limit to the number of pages, there is no reason to tamper with the margins, rephrase the sentences to make them shorter at the cost of them being illegible, or reduce the figure sizes. Please keep the paper legible.

# Organizing Committees

### General MLBriefs organization
**Quentin Bammey**, Centre Borelli, École Normale Supérieure Paris-Saclay, Université Paris-Saclay, France

### Program Committee
They invite plenary speakers and organize the workshop program
* **Gabriele Facciolo**, Centre Borelli, École Normale Supérieure Paris-Saclay, Université Paris-Saclay, Gif-sur-Yvette, France
* **Pablo Musé**, Universidad de la República, Montevideo, Uruguay
* **Jean-Michel Morel**, City University of Hong Kong (CityU), Hong Kong
* **Quentin Bammey**, Centre Borelli, École Normale Supérieure Paris-Saclay, Université Paris-Saclay, Gif-sur-Yvette, France

### Editorial board
They manage the reviewing process for the submitted papers

#### MLBriefs track
* **Quentin Bammey**, Centre Borelli, École Normale Supérieure Paris-Saclay, Université Paris-Saclay, France
* **Gabriele Facciolo**, Centre Borelli, École Normale Supérieure Paris-Saclay, Université Paris-Saclay, Gif-sur-Yvette, France
* **Pablo Musé**, Universidad de la República, Montevideo, Uruguay

#### IPOL track
* **Jose-Luis Lisani**, Universitat de les Illes Balears, Palma de Mallorca, Spain
* [The IPOL editorial board](http://www.ipol.im/meta/board/)

### Technical Committee
They develop the IPOL demo system and provide technical help to the participants on demo creation
* **Jérémy Anger**, Kayrros SAS, France / Centre Borelli, École Normale Supérieure Paris-Saclay, Université Paris-Saclay, France
* **Amyn Jaafar**, Centre Borelli, École Normale Supérieure Paris-Saclay, Université Paris-Saclay, France
* **Héctor Macías Casado**, Centre Borelli, École Normale Supérieure Paris-Saclay, Université Paris-Saclay, France
* **Jyotsna Rajan**, Centre Borelli, École Normale Supérieure Paris-Saclay, Université Paris-Saclay, France
* **Miguel Colom**, Centre Borelli, École Normale Supérieure Paris-Saclay, Université Paris-Saclay, France
* **Tina Nikoukhah**, Centre Borelli, École Normale Supérieure Paris-Saclay, Université Paris-Saclay, France

# Program

The conference program will be announced later.

<!-- Plenary talks will be held in the mornings, Monday, May 27<sup>th</sup>, to Thursday, May 30<sup>th</sup>.
On afternoons and on Friday, May 31<sup>st</sup>, participants will gather in the workshop rooms and work on their demos and articles. 
-->

# Venue and Travel

The conference will be held at the ENS Paris-Saclay, Gif-sur-Yvette, France.

All sessions will be transmitted by Zoom as well.

<div style="text-decoration:none; overflow:hidden;max-width:100%;width:350px;height:250px;"><div id="my-map-canvas" style="height:100%; width:100%;max-width:100%;"><iframe style="height:100%;width:100%;border:0;" frameborder="0" src="https://www.google.com/maps/embed/v1/place?q=ENS+Paris-Saclay,+Avenue+des+Sciences,+Gif-sur-Yvette,+France&key=AIzaSyBFw0Qbyq9zTFTd-tUY6dZWTgaQzuU17R8"></iframe></div><a class="embed-map-html" href="https://www.bootstrapskins.com/themes" id="get-map-data">premium bootstrap themes</a><style>#my-map-canvas .text-marker{}.map-generator{max-width: 100%; max-height: 100%; background: none;</style></div>

The ENS is easily accessible from the Paris city centre.

## Coming from Paris
From the Paris city centre, take the RER B towards Saint-Rémy-lès-Chevreuse, get off at Le Guichet, then take the bus 9 towards Campus HEC / Gare de Jouy-en-Josas, and get off at Moulon, in front of the ENS.
You can also get off the RER B at Massy-Palaiseau, take bus 91.06 or 91.10, and get off at Moulon.

Count between one hour and one hour and half from Châtelet les Halles to the ENS.

## Coming by train
The ENS is best deserved by the Massy-Palaiseau TGV station, buses 91.06 and 91.10 go from the Massy-Palaiseau bus station (which is next to the train station) to Moulon (in front of the ENS) in 20 to 30 minutes.

If you arrive at any of the other Paris stations, first reach the RER B, then follow the instructions from the [previous section](#coming-from-paris).

## Coming by plane
Paris is served by two major airports: Paris Charles de Gaulle and Orly.

The Charles de Gaulle airport is located directly on the RER B, from there you can follow the instructions of the first section ["Coming from Paris"](#coming-from-paris). The trip will take around 2 hours.
Note that in May, the RER B will not operate between Châtelet les Halles and the airport in the evening, starting at 10.45 PM. If you arrive after this hour, you can take the RoissyBus shuttle, which operates between the airport and Paris.

From the Orly airport, take the RER C towards Massy - Palaiseau, stop there and take bus 91.06 or 91.10 to get off at Moulon. The journey will take around one hour.

## Coming by car
There are several free car parks near the ENS, the closest being the "Parking Digiteo". Note that as per university policy, we cannot grant you entry in the ENS car park, which is reserved for employees.

# Sponsors


The IPOL MLBriefs workshop is a great place to meet young researchers. We expect more than 100 attendees from over the world.

If you would like to sponsor the IPOL MLBriefs workshop, please [contact us](mailto:contact@mlbriefs.com).

Sponsor benefits include:

* Your name and logo on the MLBriefs website, as well as thanks during the introduction session.
* The possibility to give a plenary talk to the attendees, about the scientific work of your company,
* The possibility to distribute goodies and/or leaflets to the attendees,

Your sponsorship will help funding the organization of the workshop, possibly travel grants for international attendees, and foster the overall development of the [IPOL](ipol.im) platform.

