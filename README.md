EquationGPT OpenAI Finetune Dataset
=================================== 

Introduction
================
This repo is to hold the public dataset for EquationGPT, which aims to collect Equation related GPT Q&A corpus to finetune foundation models of GPT/ChatGPT.
Each prompt-completion pairs contains information about the latex code for the equation, the meaning of each symbols, and related materials. The dataset is collected from website http://www.deepnlp.org/equation/ and contains 8k+ prompt-completion pairs to finetune the GPT model.

See this OpenAI blog for details of how to finetune your GPT model. https://platform.openai.com/docs/guides/fine-tuning.


### Dataset Statistics

| SubField | Cnt      |
|math|1435|
|physics|1674|
|chemistry|738|
|economics|1614|
|machine learning|747|
|statistics|151|
|geometry|860|
|financial engineering|538|


Recent Original Blogs Contents on website www.deepnlp.org
==========================================================

### Equation
http://www.deepnlp.org/equation/
http://www.deepnlp.org/workspace/detail/
http://www.deepnlp.org/search/

### Math
http://www.deepnlp.org/blog/linear-matrix-algebra-formulas
http://www.deepnlp.org/blog/calculus-formulas-latex-limits-differentiation
http://www.deepnlp.org/blog/calculus-formulas-latex-integration

