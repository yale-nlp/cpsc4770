---
layout: page
permalink: /logistics/
title: Logistics
---

* (The list will be replaced with the table of contents.)
{:toc}

***

### Introduction

This course provides a deep dive into modern Natural Language Processing (NLP), focusing on neural approaches, and (large) language models. The curriculum spans both foundational neural concepts and cutting-edge developments in the field.  
The course begins with core neural network concepts in NLP, covering word embeddings, sequence modeling, and attention mechanisms. Students will gain a strong understanding of these building blocks while learning their practical implementations.  
Building on these foundations, we explore transformer architectures and their evolution, including language models like GPT and T5. The course examines how these models enable sophisticated language understanding and generation through pre-training and transfer learning.
The latter portion covers contemporary advances: Large Language Models (LLMs), multi-modal integration, parameter-efficient fine-tuning, evaluation, multi-agent systems, and model compression. We'll analyze the capabilities and limitations of current systems while discussing emerging research directions.  

Through lectures, hands-on assignments, and projects, students will gain both theoretical understanding and practical experience implementing modern NLP systems. The course emphasizes reproducible experimentation and real-world applications.

### Prerequisites
This course requires:

- Strong programming skills in Python and prior exposure to libraries such as numpy, PyTorch, or TensorFlow
- Familiarity with probability and statistics, and linear algebra
- Prior exposure to machine learning concepts through courses Intro to ML (CPSC 381/581) or Intro to AI (CPSC 370/570).

**Important Note:** This course assumes familiarity with fundamental machine learning concepts like gradient descent, neural networks, and backpropagation. 
Although we review these concepts, students without prior ML/AI coursework should first take an introductory ML or AI course before enrolling. The course material builds heavily on these concepts from day one, and there will not be time to cover these basics in detail.
If unsure about prerequisites, please consult the instructor before enrolling.


### FAQ
> **Q: Can I take this course?**
>
> You should have taken one of the prerequisite courses. If you have not, please consult the instructor before enrolling.
>
> **Q: I have equivalent experience but haven't taken the prereq courses. Can I enroll?**
>
> Please contact the instructor with: Relevant coursework/grades and your programming experience (including ML projects) and math background
>
> **Q: I may miss several lectures. Can I still take the course?**
>
> Regular attendance is mandatory, and we do not guarantee lecture recordings. Missing more than a few classes significantly impacts learning outcomes and participation grade. If you anticipate scheduling conflicts, consider taking the course in a future semester.

### Learning Resources

#### Textbook

- Dan Jurafsky and James H. Martin. Speech and Language Processing (2024)
- Yoav Goldberg. A Primer on Neural Network Models for Natural Language Processing

We will also using papers from major conferences in the field including ACL, EMNLP, NAACL, ICLR, NeurIPS, etc. 

### Communication

We use Canvas, Ed and email for main announcements.
For questions about the course, discussions about material, and faciliatating discussions for projects between students, we will mainly use Ed Discussion.

***

### Grading

Final grades will be comprised of:

- 23%: Assignments, which includes both written and coding problem sets
- 40%: Two Midterm Exams (20% each), in person, closed book
- 12%: Participation and quizzes
- 25%: Final projects
- Grading for graduate students: Graduate students will need to incorporate a novelty element and a more in-depth literature review in their final projects

The cutoffs for final grades will be approximately 93+ A, 89+ A-, 85+ B+, 82+ B, 78+ B-, ...
Although we reserve some flexiblity to change these thresholds slightly.

### Quizzes

This course uses occasional two-stage quizzes. Students first complete a short quiz individually. Immediately afterward, they discuss the same questions with peers and submit a second set of answers. The goal is to promote deeper understanding through reflection and peer discussion.

### AI Assistant policies

The use of AI tools (including but not limited to ChatGPT, Claude, GPT-4o, etc) for coursework is regulated as follows:

#### For Assignments and Quizzes

Permitted Uses:

- Writing assistance: Grammar checks, style improvements, and clarity enhancements
- Learning tool: Exploring concepts and asking questions while studying

Prohibited Uses:

- Generating code solutions for assignments
- Completing homework problems
- Answering quiz/exam questions
- Using GitHub Copilot or similar coding assistants

Required Disclosure:  

You must document any AI assistance in your submissions by:

- Specifying which parts received AI assistance
- Explaining how the AI was used
- Including relevant prompts/interactions

Academic Integrity:  

**Using AI tools beyond these guidelines constitutes an Honor Code violation. When in doubt, consult the instructor before using AI tools.**

#### AI Tools Policy (Final Project Only)

For the final project only, students may use any AI tools, including coding and writing assistants (e.g., Codex, Claude Code, Cursor, OpenHands, etc).

**Required Disclosure**

Each submission must include a brief AI Usage Statement describing:

- Which AI tools were used
- Which parts of the project involved AI assistance
- How the tools were used (with representative prompts or interactions)

Projects will be evaluated on ambition, technical depth, analysis, and clarity, not on limiting AI usage.
**Failure to disclose AI use accurately constitutes an Academic Integrity violation.**

### Late submissions

You can still submit your assignment after the deadlines for up to **5 days**.
You will, however, receive partial credit for late submissions. Every late day will result in 10% deduction in full credit for that assignment

Note: Late days can only be used on the assignments, and not on the project proposal or the final report and the presentation.

**Grading for graduate students**

Grading components for graduate students will be the same as undergraduate students. The only difference is the following:

For class projects we expect graduate students to work on a research problem (The project should propose either a novel research, a novel investigation of existing methods, an extension of prior work for a specific purpose, or a new application.). Graduate student projects are also expected to have a more thorough literature review component in their final project report. 

#### Class project (**25%**)

The final project is an open-ended, ambitious project completed in small (2-3 students) teams. **Students may freely use any AI tools for this project.**

Each project must follow one of two tracks:

**Track 1: Application Track**

Build a complete application or system that uses LLM-based or AI technologies in a nontrivial way (e.g., web app, interactive system, agent-based workflow, evaluation tool).
Projects should go beyond basic prompting and demonstrate thoughtful system design, evaluation, and reflection.

**Track 2: Research Track**

Conduct a research-oriented project. Examples include but not limited to: extending an existing paper, analysis or interpretability of LLMs, reproducing and analyzing prior work, or providing new empirical or conceptual insights.
Negative results are acceptable but must be accompanied by careful analysis.

**Final Report**

Submit a 2–4 page report (maximum 4 pages) in a conference paper format (e.g., NeurIPS-style), including:

- Motivation and problem statement
- Related work
- Proposed approach or system design
- Results or evaluation
- Discussion and analysis

References and appendix do not count toward the page limit.

-   **3%**: proposal
    -   Students should submit a 1 page proposal for their project. The proposal should state and motivate the problem, and position the proposed project within related work. The project proposal should also include a brief description of the approach as well as the experimental plan (e.g., baselines, datasets, etc) to validate the effectiveness of the approach.

-   **10%**: Final project report
    -   As described above: 2-4 (no more than 4 pages) page conference format report (e.g., [NeurIPS](https://www.overleaf.com/latex/templates/neurips-2023/vstgtvjwgdng)) detailing the project motivation, related work, proposed approach, results, and discussion. You can think of this as a short conference paper. Negative results will not be penalized, but should be accompanied with detailed analysis of why the proposed methods didn't work and provide some additional insights into the problem. 
    -   References and appendix won't count towards the page limit

-   **11%**: Final project presentation
    -  5 minute in person in-class presentations

-   **1%**: Code and reproducibility checklist
    -  Your project code should be clean, readable, with clear running instructions, and the results should be fully reproducible. We will provide a reproducibility checklist that should be returned.


## Integrity

[Academic integrity](http://catalog.yale.edu/undergraduate-regulations/regulations/academic-dishonesty/) requires that students at Yale acknowledge all of the sources that inform their coursework. Most commonly, this means (a) citing the sources of any text or data that you include in papers and projects, and (b) only collaborating with other students or using AI composition software in ways that are explicitly endorsed by the assignment. Yale’s dedication to academic integrity flows from our two primary commitments: supporting research and educating students to contribute to ongoing scholarship. A safe and ethical climate for research demands that previous authors and artists receive credit for their work. And learning requires that you do your own work. Conventions for acknowledging sources vary across disciplines, and instructors should instruct you in the forms they expect; they should also delineate which forms of collaboration among students are permitted. But ultimately it is the student’s responsibility to act with integrity, and the burden is on you to ask questions if anything about course policies is unclear.

## Diversity statement
Our course welcomes students of all backgrounds, identities, and experiences. We value diverse perspectives and believe they enhance our understanding of the subject matter. We are committed to creating an inclusive environment where all students can participate fully and succeed.


<!-- ## FAQs

- What if I am unable to attend the class?  
A: If a student frequently misses classes or can't attend a significant part of the course we recommend dropping the course.

- How to audit the course?  
A: We welcome Yale students to audit the course! If you want to actually master the material of the class, we very strongly recommend that auditors do all the assignments. However due to high demand we cannot grade assignments. Also please do not use course resources such as TA or instructor time.


- Will the lectures be recorded?  
A: This course is in-person, and regular attendance is mandatory. Some lectures might be recorded for future use, but regular, high-quality video recordings aren't assured. Students should plan assuming there won't be recordings. Those who can't attend in person should NOT take the course.  -->
