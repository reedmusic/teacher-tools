# Teacher Tools
{: .no_toc}

Excel tools to support retrieval practice and generate automatic quizzes from banks of questions.

<!-- No TOC needed if ## Overview
- TOC
{:toc}
-->

## Overview {#overview}

| Tool | Usage | Download  |
| ---- | -------- | ----- |
| [Retrieval Roulette](#roulette) | Questions and Answers generate random test. Pick entire topic(s) to include. | [Download](https://github.com/MrReedSWCHS/teacher-tools/raw/main/downloads/roulette.xlsx) |
| [MCQ Machine](#mcq) | Questions and Multiple-Choice Answers generate random test. Pick individual questions to include.  | [Download](https://github.com/MrReedSWCHS/teacher-tools/raw/main/downloads/mcq.xlsx) |
| [Vocab Roulette](#vocab) | Terms and definitions generate random test. Pick individual terms to include. | [Download](https://github.com/MrReedSWCHS/teacher-tools/raw/main/downloads/vroulette.xlsx) |


## Retrieval Roulette {#roulette}

![](img/roulette.png)

[Download Roulette here](https://github.com/MrReedSWCHS/teacher-tools/raw/main/downloads/roulette.xlsx).

The retrieval roulette[^1] is a spreadsheet. It contains bank of questions and answers from which a random quiz is automatically generated.

It supports retrieval practice and spaced repetition: questions from previous and current topics are mixed up randomly (at your control).

### Features

![](img/roulette2.png)

* **Questions** sheet holds all the questions and answers (and the topic they fall under).
* **Options** sheet selects which topics to include in the test.
* **1_Q** sheet asks 1 question.
* **5_Q** asks 5 questions. (**5_A** shows answers).
* **10_Q** asks 10 questions. (**10_A** shows answers).
* **Print Q** fills an A4 paper with questions, for homework or test. (**Print A** shows answers)
* **Print KO** randomly hides questions and answers, like a deletion test in a Knowledge Organiser. (**Print A** shows answers)

Adapted from the example and information in [Adam Boxer's blog](https://achemicalorthodoxy.wordpress.com/2018/08/18/retrieval-roulettes/). Links to many different examples at the bottom.

## MCQ Machine {#mcq}

![](img/mcq.png)

[Download MCQ Machine here](https://github.com/MrReedSWCHS/teacher-tools/raw/main/downloads/mcq.xlsx).

The MCQ machine generates five multiple-choice questions from a list. You turn individual questions on or off in the **Questions** sheet and Excel will randomly choose five. The order of the responses are also randomised.

### Instructions

Instructions in the Excel file.

![](img/mcq2.png)

### Tips

* You can leave rows blank or add headings to organise topics/weeks etc.
* Select a number of the yellow cells, then press Ctrl+Enter to type 'Y' into many cells at once (for example to select questions for an entire topic).

<!-- Thoughts on writing [high-quality MCQs](https://testing.byu.edu/handbooks/14%20Rules%20for%20Writing%20Multiple-Choice%20Questions.pdf).
-->

## Vocab Roulette {#vocab}

![](img/vocab.png)

[Download Vocab Roulette here](https://github.com/MrReedSWCHS/teacher-tools/raw/main/downloads/vroulette.xlsx).

10-question vocabulary tests from a spreadsheet of terms and definitions.

### Features

![](img/vocab2.png)

* **Glossary** sheet holds terms and definitions. 
	* Type Y to turn individual terms on/off.
	* (Optional) Type X to include difficult terms as potential 'extra' questions, e.g. for differentiation (see yellow questions in above image).
* **Terms** tests definitions.
* **Definitions** tests terms.
* **Answers** shows both.
* **Gaps** deletes every other term or definition.
* **Terms (ext)** and **Definitions (ext)** ask 7 normal questions and 3 'extra' questions (e.g. harder terms for differentiation or for more recent topics covered...). **Answers (ext)** shows answers.



[^1]: Inspired by Adam Boxer's blog and examples [here](https://achemicalorthodoxy.wordpress.com/2018/08/18/retrieval-roulettes/).