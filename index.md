# What do language models really understand?

**Course Description**: Large language models such as GPT-3 and ChatGPT have led to great advances in the field of natural language processing, and in many cases they provide responses to prompts that suggest that possess non-trivial abilities to understand language. At the same time, however, these models are primarily trained on text and have no explicit connection with the real world, whereas humans learn language by interacting with other humans and forming associations between words and phrases and entities and events in the world.

In this seminar, we will focus on the question to what extent large language models understand language. We'll cover different philosophical schools of what it means to understand language, and then focus on a series of recent empirical papers that aim to evaluate different aspects of language understanding in models.

**Course Management System**: [https://cms.sic.saarland/wdlmu23/](https://cms.sic.saarland/wdlmu23/)

**Instructor**: [Sebastian Schuster](https://sebschu.com)

**Time**: Thursdays, 2:15-3:45pm

**Room**: C7.3 1.12

### Syllabus

Exact readings are still subject to change!

|    Date    |                                         Topic                                        |                        Papers                        | Slides | Additional Materials | Presenter |
|:----------:|:------------------------------------------------------------------------------------:|:----------------------------------------------------:|:------:|:-------------------:|:---------:|
| 04/13/2023 |                          Foundations: Large language models                          |       [Devlin et al. (2019)](https://aclanthology.org/N19-1423/), [Brown et al. (2020)](https://proceedings.neurips.cc/paper/2020/file/1457c0d6bfcb4967418bfb8ac142f64a-Paper.pdf)      | [Slides](slides/1_LLMs.pdf) | [Alammar: Illustrated GPT-2](https://jalammar.github.io/illustrated-gpt2/), [Rush: The annotated transformer](https://nlp.seas.harvard.edu/2018/04/03/attention.html), [Stanford CS224N lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rOSH4v6133s9LFPRHjEmbmJ), [S&LP, Ch. 10](https://web.stanford.edu/~jurafsky/slp3/10.pdf), [HuggingFace NLP Course](https://huggingface.co/learn/nlp-course/chapter1/1), [Kulshrestha: Transformers](https://towardsdatascience.com/transformers-89034557de14), [Vaswani et al. (2017)](https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf) |  Sebastian |
| 04/20/2023 |        Foundations: Fine-tuning and reinforcement learning from human feedback       |      [Ouyang et al. (2022)](https://arxiv.org/abs/2203.02155)                 | [Slides](slides/2_FineTuning_etc.pdf) | [S&LP, Ch. 11](https://web.stanford.edu/~jurafsky/slp3/11.pdf), [Goldberg: Reinforcement Learning for Language Models](https://gist.github.com/yoavg/6bff0fecd65950898eba1bb321cfbd81) | Sebastian |
| 04/27/2023 | Foundations: What does it mean to 'understand'? and methods for assessing understanding. | [Bender and Koller (2020)](https://aclanthology.org/2020.acl-main.463/), [Piantadosi and Hill (2022)](https://arxiv.org/abs/2208.02957) | [Slides](slides/3_understanding.pdf) |  | Sebastian |
| 05/04/2023 |                      Methods: Behavioral experiments and probing                     |      [Linzen et al. (2016)](https://aclanthology.org/Q16-1037/), [Tenney et al. (2019)](https://openreview.net/pdf?id=SJzSgnRcKX)      | | |   Aarushi, Mikhail       |
| 05/11/2023 |                     Negation                     |      [Ettinger (2020)](https://aclanthology.org/2020.tacl-1.3/), [Shivagunde et al. (2023)](https://arxiv.org/abs/2303.16445)       | |  | Bilal Emadeldeen Abdelkader, Lucas            |
| 05/16/2023 8:15am-9:45am (Special day/time!) |                     Compositionality                     |      [Kim and Linzen (2020)](https://aclanthology.org/2020.emnlp-main.731/), [Qiu et al. (2022)](https://aclanthology.org/2022.emnlp-main.624/)     | | | Megan, Haseon          |
| 05/18/2023 |                        _no class_ (public holiday)                  |         | | |           |
| 05/25/2023 |                      Entity tracking / world models I                       |      [Li et al. (2021)](https://aclanthology.org/2021.acl-long.143/), Kim and Schuster (to appear)    | | |     Lin, Nursulu     |
| 06/01/2023 |                        Entity tracking / world models II                    |   [Toshniwal et al. (2021)](https://ojs.aaai.org/index.php/AAAI/article/view/21390), [Li et al. (2023)](https://arxiv.org/abs/2210.13382)      | | |   Tim, Florian        |
| 06/06/2023  8:15am-9:45am  (Special day/time!) |  Discourse understading and connectives                                   |   [Pandia and Ettinger (2021)](https://aclanthology.org/2021.emnlp-main.119/), [Pandia et al. (2021)](https://aclanthology.org/2021.conll-1.29/)       | |    |   Saahithi Pradhan, Lotta     |
| 06/08/2023 |                      _no class_ (public holiday)                    |       | | |          |
| 06/15/2023 |                        Pragmatic inferences                   |  [Hu et al. (2022)](https://arxiv.org/abs/2212.06801), [Ruis et al. (2022)](https://arxiv.org/abs/2210.14986)        | | |   Chih-Ying, Sarah       |
| 06/22/2023 |                       Metaphors / Figurative meaning                       | [Comșa et al. (2022)](https://aclanthology.org/2022.aacl-short.46/), [Chakrabarty et al. (2022)](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00478/111221/It-s-not-Rocket-Science-Interpreting-Figurative)   | | |   Vitalii, Subrat Kishore       |
| 06/29/2023 |                        Grounding / Reporting bias            |   [Paik et al. (2021)](https://aclanthology.org/2021.emnlp-main.63/), [Liu et al., (2022)](https://aclanthology.org/2022.aacl-short.27/)    |           | |  Lynn, GowthamKrishna |
| 07/06/2023 |                       Multimodal models            |  [Thrush et al. (2022)](https://openaccess.thecvf.com/content/CVPR2022/papers/Thrush_Winoground_Probing_Vision_and_Language_Models_for_Visio-Linguistic_Compositionality_CVPR_2022_paper.pdf), [Yuksekgonul et al. (2023)](https://openreview.net/pdf?id=KRLUvxh8uaX)   | | |    Hüseyin, Priya       |
| 07/13/2023 |                       _no class_           |    | | |         |
| 07/20/2023 |                       _no class_           |     | | |           |


### Course format and requirements

This course will be run as a seminar and except for the first three units, where I will provide some background on language models and the philopsophy of understanding, two students will present in each unit. Every student will present exactly once.

Starting with the fourth unit, all students are expected to read both readings every week and have to submit one question about each reading by Wednesday evening (or Monday evening for the two sessions that will be held Tuesday morning).

### Grading

For students taking the seminar for 4 credits:

* Presentation: 60%
* Questions about readings: 40%

For students taking the seminar for 7 credits:

* Presentation: 40%
* Questions about readings: 20%
* Final paper: 40% (more on that soon)

Questions about the readings are graded on a 3-point scale (0: no question submitted, 1: superficial question, 2: insightful question). I will drop the 3 lowest scores (out of the 19 questions that you will have to submit) when computing this portion of the grade.

More information about the presentation and final paper rubrics will be announced soon.

### Office hours

Please contact Sebastian at [seschust@lst.uni-saarland.de](mailto:seschust@lst.uni-saarland.de) to schedule a meeting.

### Accommodations

If you need any accommodations due to a disability or chronic illness, please either contact Sebastian at [seschust@lst.uni-saarland.de](mailto:seschust@lst.uni-saarland.de) or the [Equal Opportunities and Diversity Management Unit](https://www.uni-saarland.de/en/verwaltung/chancengleichheit/ksb) of the university.

### All students are welcome

I am committed to doing what I can to work for equity and to create an inclusive learning environment that actively values the diversity of backgrounds, identities, and experiences of everyone in this seminar. I also know that I will sometimes make missteps. If you notice some way that I could do better, I hope that you will let me know about it.
