---
title: Data Speaks for Itself
layout: single
permalink: 
date: 2023-10-23
last_modified_at: 
toc: "true"
toc_label: 
toc_icon: 
author_profile: true
read_time: 
comments: 
search: 
excerpt: "You have probably heard that before, but the real meaning behind this idea is not what you might think"
header:
  teaser: /images/photos/AHVJ5357.jpg
  # image: 
  og_image: /images/photos/AHVJ5357.jpg
  # image_description: 
  # overlay_image: /images/photos/AHVJ5357.jpg
  # overlay_filter: 0.5
  # caption: ""
  # overlay_color: 
  # actions:
  #   - label: 
  #   - url: 
# sidebar:
#   title: sample title
#   nav: sidebar-sample
# collection: 
# entries_layout: grid
# classes: wide
tags: 
subject: 
type: 
topic: 
calendar: 
status: 
rating: 
aliases:
---


Especially now, the phrase "data speaks for itself" is a well-known sentence found all over the internet and specifically on social media platforms such as LinkedIn or Medium publications. Because of the popularity of that sentence, it is also not difficult to come across articles attempting to negate that or, at least, to improve upon it. I think, however, that many of such attempts - the ones I have encountered thus far - are equally mistaken in at least one important aspect.

It seems that the main critical reply to the statement that "data speaks for itself" is that data `storytelling` is more important than letting data speak for itself because data does not speak, and "we need to speak for the data". While mentioning that we should interpret data and know the audience before tailoring the message does indeed make sense, it fails to make clear hidden aspects of the entire process. 

The discussion of what is reading data and what is interpreting data has its roots in the conundrum of absolute truth or laws of Nature. Whether we derive or discover knowledge by observing the world, as Aristotle said, or actively impose our laws upon Nature, as [Kant](https://en.wikipedia.org/wiki/Critique_of_Pure_Reason) believed: "Our intellect does not draw its laws from nature, but imposes its laws upon nature". Similarly, we can ask if mathematics is simply [discovered or created](https://www.youtube.com/watch?v=ujvS2K06dg4&t=69s) by us instead. Yet, for the practical use of data, which is not about basic laws of Nature, the picture is much simpler.

#### **The selective nature of observations** 

A camera serves as a kind of license to see, enabling us to collect data in the form of frozen moments. These moments are spatially bounded due to the finite size of the camera's frame and are captured in a millisecond instant of time determined by its shutter. Light, in the form of photons hitting the camera sensor, is the primary source of the stored information.

Similar to a photograph, data is captured as the result of observations. Observations are always selective. Even before the act of observation, the designers of the observation have a theoretical framework in mind, an expectation or a question based on current knowledge. This means there is no such thing as untainted data, and no amount of storytelling can change or "cleanse" it, as long as the analysis occurs after data collection. 

In Street Photography, [Joel Meyerowitz](https://en.wikipedia.org/wiki/Joel_Meyerowitz) introduced a related concept  of `bruising` the scene, which is a more fine-grained version of staged photography, where the photographer tries to interfere as little as possible with the image being captured. Even if they succeed in not bruising the scene, they will still be either "fishing" or "hunting" for a photograph, meaning they will carefully choose their subject(s), the main object of their observation. 

**Styles in Street Photography**  
_Fishing_: Choose the environment or background and patiently wait for the main subject.  
_Hunting_: Constantly move to find the interesting moment as it happens.  
{: .notice--info}

Does this imply that a bruised photo or even a staged photo is useless or meaningless? 
Of course not. Here is a staged photo by [Fan Ho](https://en.wikipedia.org/wiki/Fan_Ho) that is brimming with meaning:

<!-- ![](/images/posts/Pastedimage20230919115500.png) -->

<figure style="width: 70%" class="align-center">
  <img src="/images/posts/Pastedimage20230919115500.png" alt="Fan Ho's photo"> <figcaption>Photo: Approaching Shadow, Fan Ho (1954)</figcaption>
</figure>


As a practical example from Physics, the $4.5 billion particle accelerator, LHC, was in search of the [Higgs particle](https://en.wikipedia.org/wiki/Search_for_the_Higgs_boson), but it was even designed and precisely tuned to find a particle within the energy range predicted by a theory, the Standard Model (SM).

**Higgs boson**  
_Higgs SM-theory_: There is a SM-like Higgs boson with mass in the range \[70, 800\] GeV.   
_Experiments_: Searched and discovered a particle with mass ~ 125.3 GeV.
{: .notice--primary} 

There are, however, important reasons why it is important to bear in mind the selective nature of observation, especially if data is used to convey an idea or inform a decision.
If we do not stress out that enough, one can say that the data is speaking for itself, without any interpretations from its analysts and, therefore, (intentionally) quickly jumping into a hasty potentially erroneous conclusion based on a justification that I refer to as `data authority`, which of course is not really justified. 

Similarly, with an effective storytelling, one could advocate distinct conclusions based on different interpretations of the same data. Then, it becomes important to distinguish between what constitutes a good interpretation from a bad one. This distinction is highly compromised when the nature of the data remains unknown, that is, if the adopted criteria, or theoretical framework, for selecting the data are not explicitly stated. In either case, the focus is misplaced when it is too much shifted towards the authority of the data itself or the authority of the storyteller, who claims to possess an allegedly correct interpretation of the data. 

#### **What does constitute a good interpretation of data for storytelling?**

If by "good" we mean truthful, the answer is that a good interpretation must first capture some objectively key true/false statements about the data and eliminate false statements from the claims one is prepared to make as a result of their analysis. There are claims that can be made with certainty, but only within the limits of the observed data. Data quality, which includes the design of experiments, clearly plays a role in limiting the applicability or the predictive power of finite data.

Usually, however, we want to go beyond tautologies by making bold claims that are predictions, and sometimes also prescriptions. In Science, these claims should be proposed as conjectures or hypotheses, which can be further investigated with the intention of being tested ([falsified](https://en.wikipedia.org/wiki/Falsifiability)) and, only if they survive the tests, they are increasingly corroborated. 

In a business context where instrumentalism (tools for practical purposes only) holds major importance, the idea is not to exhaustively test claims to the point where they become false,  but rather to identify a reasonable range of applicability - a kind of confidence interval - where the claims will serve the purposes of the business owners or stakeholders. Given that business questions are predominantly practical, these claims will at some point turn out to be confirmed based on their usefulness or rejected for failing to meet desired or required objectives.

As predictive tools designed for specific purposes, they can be constantly updated with new data in order to become increasingly accurate while accommodating uncertainty or variance. The presence of uncertainty also implies that other facts beyond data analysis and statistical forecasting, such as domain knowledge and experience, should be taken into account for final decisions. 

One important question is the true extent of the potential discoveries that can be made by such useful AI tools. Can they lead to breakthrough discoveries? That is really a question for another post.   


#### **How about exploratory data analysis?** 

In a world where observations are guided by hypotheses and theories, one might question what is exploratory analysis really doing. After all, exploratory analysis should be investigations that lack a sharply defined purpose to limit the analysis.  

Exploratory data analysis is often guided by some expectation or intention to address a particular question, and it can be very useful in providing an understanding of a problem. Purely exploratory analyses tend to serve more as descriptions of situations or effects rather than as a method of discovery. It is fair to say that there are instances of chance discoveries in such exploratory endeavours, but even those are generally influenced by existing theories or conjectures. 

A notable example is the discovery of the antiparticle [positron](https://pubs.aip.org/physicstoday/online/9041/Positron-discovered), which was "accidentally" found by [Anderson](https://en.wikipedia.org/wiki/Carl_David_Anderson) in 1932 but theoretically predicted and proposed by [Dirac](https://en.wikipedia.org/wiki/Paul_Dirac) in 1931. Nonetheless, chance discoveries do not represent the standard procedure leading to the most significant discoveries. They are certainly important and can be remarkably surprising.       

Whatever may constitute good criteria used to assess data designed for different use cases, there exists a component of the process that should not be neglected at the risk of missing important aspects of the problem that one is trying to solve. That is the theoretical framework that was assumed before any conceivable experiment designed to observe data. 

#### **Final thoughts**

When working with data for significant investigations, acknowledging the nature of the data itself is equally important as extracting the intended predictions. It is necessary to clarify the distinctions between the relevant presumptions or the background framework inherited by the data, the actual data content, and the claims of predictions or prescriptions that have a conjectural character.     

Data speaking for itself should really mean the (posterior) **non-subjective** reading of data.
- *Reading the data*: Examine the content of data solely based on the selective character that was imposed on it by the process of experiment design or observation. 

- *Data storytelling*:  Given the data that has already been observed or collected, which is never free of the inherent choices made by its designers or observers, find the pitch or the expression that best fits your interpretation of the data. What is considered "best" here is highly **subjective**, as it depends on the purposes and the audience for which the data is intended to serve.  

Thus, data can indeed speak for itself, or better still, there is a non-subjective reading of data,  but what it has to say is precisely what was selected by its creators or observers during the initial data collection process. One can, however, engage in various forms of storytelling but cannot avoid the inherent selection, the residual bruise, that was imprinted on the data even before any subsequent interpretation. 









