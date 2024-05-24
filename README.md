# Natural language processing course 2023/24: `Project 4: Slovenian Instruction-based Corpus Generation (Slavko)`

<!--- Please, organize README and the whole structure of the repository to be self-contained and reproducible. --->

## Instructions
Large Language Models (LLMs) have shown great promise as highly capable AI assistants that excel in complex reasoning tasks requiring expert knowledge across a wide range of fields, including in specialized domains such as programming and creative writing. They enable interaction with humans through intuitive chat interfaces, which has led to rapid and widespread adoption among the general public. Recently, a number of different very large language models were introduced, such as LaMDA, BLOOM, GPT(-3), Galactica, Mixtral, OPT, ... It is also infeasible to train such models without a powerful GPU infrastructure or large amounts of corpora. Based on these models, text-to-text models were often trained, compared to training specific models per each NLP task, such as text classification, question answering, Our task is to get to know LLMs and try to understand their creation from higher levels. Try to prepare large amounts of conversational data in Slovene (this is the focus of this task!) that is correctly organized and of good quality to be fed into fine-tuning a multi-lingual LLM (that supports Slovene). Demonstrate work by adapting a model to fine-tune a conversational agent for Slovene.

### Proposed methodology:

- Review usable LLMs, select one that you might use (e.g., within SLING infrastructure, VEGA, Nvidia A100 GPUs).
- (main goal of the project) Review datasets construction and categorization of instructions for selected Instruce-based LLMs. Prepare a plan for data gathering and identify sources (e.g., med-over.net, slo-tech forum, ...). Write crawlers, ... organize data in a way that is useful for "fine-tuning" the model. Check papers (e.g., BLOOM's, LLaMa 2's) to get to know, what aspects are important when preparing data.
- Use the data to adapt an existing model using your data (optional).
- Report on all your findings in the final report.

### References:

- Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll L. Wainwright, Pamela Mishkin, Chong Zhang, Sandhini Agarwal, Katarina Slama, Alex Ray, John Schulman, Jacob Hilton, Fraser Kelton, Luke Miller, Maddie Simens, Amanda Askell, Peter Welinder, Paul Christiano, Jan Leike, Ryan Lowe, Training language models to follow instructions with human feedback, https://arxiv.org/abs/2203.02155.
- Touvron, H., Martin, L., Stone, K., Albert, P., Almahairi, A., Babaei, Y., ... & Scialom, T. (2023). Llama 2: Open foundation and fine-tuned chat models. https://arxiv.org/abs/2307.09288.
- Teven Le Scao, Angela Fan, Christopher Akiki, Ellie Pavlick, Suzana Ilić, Daniel Hesslow, Roman Castagné, Alexandra Sasha Luccioni, François Yvon, Matthias Gallé, Jonathan Tow, Alexander M. Rush, ...  et al. (300+ additional authors not shown), BLOOM: A 176B-Parameter Open-Access Multilingual Language Model, https://arxiv.org/abs/2211.05100, model: https://huggingface.co/bigscience/bloom 

### Requirements:
In order to fetch all of the required packages, please download the requirements.txt and run **pip install -r "requirements.txt"**
