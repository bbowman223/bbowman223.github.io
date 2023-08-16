---
layout: default
---

<img src="{{ "/assets/self_portrait_3.jpg" | prepend: site.baseurl }}"  alt="portrait of Ben" width="300">

> It is difficult to stop the impulse to reveal secrets in conversation, as if information had the desire to live and the power to multiply. -- Nassim Taleb, The Bed of Procrustes


# Bio

I am an Applied Scientist at [AWS AI Labs](https://www.amazon.science/) working on deep learning and computer vision.  I earned my Ph.D. in applied mathematics at [UCLA](https://ww3.math.ucla.edu/) working under the supervision of [Guido Montúfar](https://www.math.ucla.edu/~montufar/).  In the past I studied primarily the training/optimization process of neural networks, seeking to understand how the parameterization and algorithm influence the properties of the network throughout time and at convergence. Currently, I focus more on developing scalable machine learning methods that respect individual's data usage and privacy rights.

Some of my research interests:
* Machine unlearning
* Data privacy
* Compute and parameter efficient adaption of large models
* Implicit bias/regularization of gradient descent
* Neural Tangent Kernel (NTK)

Before [UCLA](https://ww3.math.ucla.edu/) I studied computational mathematics at [Penn State](https://science.psu.edu/math).  Outside of work I enjoy coffee, cooking, and cocktails.


# À-la-carte Learning
Classically, machine learning has focused on training on a monolithic dataset.  However, for deployed models training on a monolithic dataset is problematic.  As new data become available (continual learning), finetuning can be prohibitively expensive or lead to poor performance (catastrophic forgetting).  Furthermore, users can change their sharing preferences at any time, leading to datasets that shrink over time (machine unlearning) or different subsets of the data being usable by different users (compartmentalization).  To address these challenges, in our [CVPR 2023 paper](https://openaccess.thecvf.com/content/CVPR2023/html/Bowman_A-La-Carte_Prompt_Tuning_APT_Combining_Distinct_Data_via_Composable_Prompting_CVPR_2023_paper.html) we introduce the *À-la-carte Learning Problem*.  The mandate of *À-la-carte Learning* is to construct bespoke machine learning models specific to each user's data access rights and preferences.  Through our method (APT), we demonstrate that we can assemble models by combining learned prompts trained on compartmentalized data sources to achieve performance competitive with monolithic training, with further benefits for privacy, model securitization, and model customization.  For the continual learning benchmarks Split-CIFAR100 and CORe50, we achieve state-of-the-art performance.  For more information, see the video below or drop by our poster in-person in Vancouver (WED-PM-251)
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/FQ8s-0HDtTE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>




# News
07/2023 Our paper [*SAFE: Machine Unlearning With Shard Graphs*](https://arxiv.org/abs/2304.13169) was accepted to [ICCV 2023](https://iccv2023.thecvf.com/)

07/2023 I have started work as an Applied Scientist at [AWS AI Labs](https://www.amazon.science/)

06/2023 My [thesis](https://escholarship.org/uc/item/0p62k7nd) was accepted and I have earned my Ph.D. in mathematics

02/2023 Our paper [*À-la-carte Prompt Tuning (APT): Combining Distinct Data Via Composable Prompting*](https://arxiv.org/abs/2302.07994) was accepted to [CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/html/Bowman_A-La-Carte_Prompt_Tuning_APT_Combining_Distinct_Data_via_Composable_Prompting_CVPR_2023_paper.html)

01/2023 Our paper [*Characterizing the Spectrum of the NTK via a Power Series Expansion*](https://arxiv.org/abs/2211.07844) was accepted to [ICLR 2023](https://iclr.cc/)

06/2022 Our paper [*Spectral Bias Outside the Training Set for Deep Networks in the Kernel Regime*](https://proceedings.neurips.cc/paper_files/paper/2022/hash/c4006ff54a7bbda74c09bad6f7586f5b-Abstract-Conference.html) was accepted to [NeurIPS 2022](https://nips.cc/)

06/2022 This summer I will be an Applied Scientist Intern at [Amazon](https://www.amazon.science/) (AWS)

01/2022 Our paper [*Implicit Bias of MSE Gradient Optimization in Underparameterized Neural Networks*](https://arxiv.org/abs/2201.04738) was accepted to [ICLR 2022](https://iclr.cc/Conferences/2022).  (If you are interested in this work, our more [recent work](https://arxiv.org/abs/2206.02927) offers significant improvements). 

06/2021 I will be spending the summer in [Leipzig, Germany](https://en.wikipedia.org/wiki/Monday_demonstrations_in_East_Germany) as a summer researcher at the [Max Planck Institute for Mathematics in the Sciences](https://www.mis.mpg.de/) working on training dynamics of neural networks