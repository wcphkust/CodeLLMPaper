# Prompt Strategy

## Retrieval-augmented Generation

- [Automatic Semantic Augmentation of Language Model Prompts (for Code Summarization)](../venues/ICSE2024/paper_19.md), ([ICSE2024](../venues/ICSE2024/README.md))

  - **Abstract**: Large Language Models (LLM) are a new class of computation engines, "programmed" via prompt engineering. Researchers are still learning how to best "program" these LLMs to help developers. We start with the intuition that developers tend to consciously and unconsciously collect semantics facts, from...
  - **Labels**: [static analysis](static_analysis.md), [code summarization](code_summarization.md), [prompt strategy](prompt_strategy.md), [retrieval-augmented generation](retrieval-augmented_generation.md)


- [DroidCoder: Enhanced Android Code Completion with Context-Enriched Retrieval-Augmented Generation](../venues/ASE2024/paper_13.md), ([ASE2024](../venues/ASE2024/README.md))

  - **Abstract**: Android is the most popular mobile operating system. However, Android development requires extensive coding, especially for unique features such as lifecycle callbacks and UI widgets. Existing code completion methods typically utilize Retrieval-Augmented Generation (RAG) to provide contextual inform...
  - **Labels**: [code generation](code_generation.md), [code completion](code_completion.md), [prompt strategy](prompt_strategy.md), [retrieval-augmented generation](retrieval-augmented_generation.md)


- [EvoR: Evolving Retrieval for Code Generation](../venues/EMNLP2024/paper_3.md), ([EMNLP2024](../venues/EMNLP2024/README.md))

  - **Abstract**: Recently the retrieval-augmented generation (RAG) has been successfully applied in code generation. However, existing pipelines for retrieval-augmented code generation (RACG) employ static knowledge bases with a single source, limiting the adaptation capabilities of Large Language Models (LLMs) to d...
  - **Labels**: [code generation](code_generation.md), [code completion](code_completion.md), [source code model](source_code_model.md), [prompt strategy](prompt_strategy.md), [retrieval-augmented generation](retrieval-augmented_generation.md)


- [Instructive Code Retriever: Learn from Large Language Model's Feedback for Code Intelligence Tasks](../venues/ASE2024/paper_2.md), ([ASE2024](../venues/ASE2024/README.md))

  - **Abstract**: Recent studies proposed to leverage large language models (LLMs) with In-Context Learning (ICL) to handle code intelligence tasks without fine-tuning. ICL employs task instructions and a set of examples as demonstrations to guide the model in generating accurate answers without updating its paramete...
  - **Labels**: [prompt strategy](prompt_strategy.md), [retrieval-augmented generation](retrieval-augmented_generation.md)


- [Leandojo: Theorem proving with retrieval-augmented language models](../venues/NeurIPS2023/paper_6.md), ([NeurIPS2023](../venues/NeurIPS2023/README.md))

  - **Abstract**: Large language models (LLMs) have shown promise in proving formal theorems using proof assistants such as Lean. However, existing methods are difficult to reproduce or build on, due to private code, data, and large compute requirements. This has created substantial barriers to research on machine le...
  - **Labels**: [prompt strategy](prompt_strategy.md), [retrieval-augmented generation](retrieval-augmented_generation.md)


- [Repository-Level Prompt Generation for Large Language Models of Code](../venues/ICML2023/paper_2.md), ([ICML2023](../venues/ICML2023/README.md))

  - **Abstract**: With the success of large language models (LLMs) of code and their use as code assistants (e.g. Codex used in GitHub Copilot), techniques for introducing domain-specific knowledge in the prompt design process become important. In this work, we propose a framework called Repo-Level Prompt Generator t...
  - **Labels**: [code generation](code_generation.md), [code completion](code_completion.md), [prompt strategy](prompt_strategy.md), [retrieval-augmented generation](retrieval-augmented_generation.md)


- [Retrieval-Based Prompt Selection for Code-Related Few-Shot Learning](../venues/ICSE2023/paper_10.md), ([ICSE2023](../venues/ICSE2023/README.md))

  - **Abstract**: Large language models trained on massive code corpora can generalize to new tasks without the need for task-specific fine-tuning. In few-shot learning, these models take as input a prompt, composed of natural language instructions, a few instances of task demonstration, and a query and generate an o...
  - **Labels**: [general coding task](general_coding_task.md), [code model](code_model.md), [code model training](code_model_training.md), [prompt strategy](prompt_strategy.md), [retrieval-augmented generation](retrieval-augmented_generation.md)


## Reason With Code

- [Can LLMs Reason in the Wild with Programs?](../venues/EMNLP2024/paper_12.md), ([EMNLP2024](../venues/EMNLP2024/README.md))

  - **Abstract**: Large Language Models (LLMs) have shown superior capability to solve reasoning problems with programs. While being a promising direction, most of such frameworks are trained and evaluated in settings with a prior knowledge of task requirements. However, as LLMs become more capable, it is necessary t...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md)


- [Chain of code: Reasoning with a language model-augmented code emulator](../venues/Google2023/paper_1.md), ([Google2023](../venues/Google2023/README.md))

  - **Abstract**: Code provides a general syntactic structure to build complex programs and perform precise computations when paired with a code interpreter -- we hypothesize that language models (LMs) can leverage code-writing to improve Chain of Thought reasoning not only for logic and arithmetic tasks, but also fo...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md)


- [Code Prompting Elicits Conditional Reasoning Abilities in Text+Code LLMs](../venues/EMNLP2024/paper_26.md), ([EMNLP2024](../venues/EMNLP2024/README.md))

  - **Abstract**: Reasoning is a fundamental component of language understanding. Recent prompting techniques, such as chain of thought, have consistently improved LLMs’ performance on various reasoning tasks. Nevertheless, there is still little understanding of what triggers reasoning abilities in LLMs in the infere...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md)


- [Complementary explanations for effective in-context learning](../venues/ACL2023/paper_7.md), ([ACL2023](../venues/ACL2023/README.md))

  - **Abstract**: Large language models (LLMs) have exhibited remarkable capabilities in learning from explanations in prompts, but there has been limited understanding of exactly how these explanations function or why they are effective. This work aims to better understand the mechanisms by which explanations are us...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md), [empirical study](empirical_study.md)


- [Don't Transform the Code, Code the Transforms: Towards Precise Code Rewriting using LLMs](../venues/Meta2024/paper_2.md), ([Meta2024](../venues/Meta2024/README.md))

  - **Abstract**: Tools for rewriting, refactoring and optimizing code should be fast and correct. Large language models (LLMs), by their nature, possess neither of these qualities. Yet, there remains tremendous opportunity in using LLMs to improve code. We explore the use of LLMs not to transform code, but to code t...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md)


- [EHRAgent: Code Empowers Large Language Models for Few-shot Complex Tabular Reasoning on Electronic Health Records](../venues/EMNLP2024/paper_37.md), ([EMNLP2024](../venues/EMNLP2024/README.md))

  - **Abstract**: Clinicians often rely on data engineers to retrieve complex patient information from electronic health record (EHR) systems, a process that is both inefficient and time-consuming. We propose EHRAgent, a large language model (LLM) agent empowered with accumulative domain knowledge and robust coding c...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md)


- [Empowering Multi-step Reasoning across Languages via Program-Aided Language Models](../venues/EMNLP2024/paper_28.md), ([EMNLP2024](../venues/EMNLP2024/README.md))

  - **Abstract**: In-context learning methods are popular inference strategies where Large Language Models (LLMs) are elicited to solve a task using provided demonstrations without parameter updates. Among these approaches are the reasoning methods, best exemplified by Chain-of-Thought (CoT) and Program-Aided Languag...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md)


- [Explanation selection using unlabeled data for chain-of-thought prompting](../venues/EMNLP2023/paper_14.md), ([EMNLP2023](../venues/EMNLP2023/README.md))

  - **Abstract**: Recent work has shown how to prompt large language models with explanations to obtain strong performance on textual reasoning tasks, i.e., the chain-of-thought paradigm. However, subtly different explanations can yield widely varying downstream task accuracy. Explanations that have not been "tuned" ...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md), [empirical study](empirical_study.md)


- [Fact-Checking Complex Claims with Program-Guided Reasoning](../venues/ACL2023/paper_3.md), ([ACL2023](../venues/ACL2023/README.md))

  - **Abstract**: Fact-checking real-world claims often requires collecting multiple pieces of evidence and applying complex multi-step reasoning. In this paper, we present Program-Guided Fact-Checking (ProgramFC), a novel fact-checking model that decomposes complex claims into simpler sub-tasks that can be solved us...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md)


- [If llm is the wizard, then code is the wand: A survey on how code empowers large language models to serve as intelligent agents](../venues/arXiv2024/paper_27.md), ([arXiv2024](../venues/arXiv2024/README.md))

  - **Abstract**: The prominent large language models (LLMs) of today differ from past language models not only in size, but also in the fact that they are trained on a combination of natural language and formal language (code). As a medium between humans and computers, code translates high-level goals into executabl...
  - **Labels**: [survey](survey.md), [agent design](agent_design.md), [reason with code](reason_with_code.md)


- [Language Models as Compilers: Simulating Pseudocode Execution Improves Algorithmic Reasoning in Language Models](../venues/EMNLP2024/paper_38.md), ([EMNLP2024](../venues/EMNLP2024/README.md))

  - **Abstract**: Algorithmic reasoning tasks that involve complex logical patterns, such as completing Dyck language, pose challenges for large language models (LLMs), despite their recent success. Prior work has used LLMs to generate programming language and applied external compilers for such tasks. Yet, when on t...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md)


- [PaD: Program-aided Distillation Can Teach Small Models Reasoning Better than Chain-of-thought Fine-tuning](../venues/NAACL2024/paper_3.md), ([NAACL2024](../venues/NAACL2024/README.md))

  - **Abstract**: While large language models (LLMs) excel in various natural language processing tasks, their huge size and the inaccessibility of parameters present challenges for practical deployment. Previous studies try to distill task-specific ability from LLMs to smaller models, using data synthesis and chain-...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md)


- [Program-Aided Reasoners (Better) Know What They Know](../venues/NAACL2024/paper_2.md), ([NAACL2024](../venues/NAACL2024/README.md))

  - **Abstract**: Prior work shows that program-aided reasoning, in which large language models (LLMs) are combined with programs written in programming languages such as Python, can significantly improve accuracy on various reasoning tasks. However, while accuracy is essential, it is also important for such reasoner...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md)


- [Prompting with Pseudo-Code Instructions](../venues/EMNLP2023/paper_10.md), ([EMNLP2023](../venues/EMNLP2023/README.md))

  - **Abstract**: Prompting with natural language instructions has recently emerged as a popular method of harnessing the capabilities of large language models (LLM). Given the inherent ambiguity present in natural language, it is intuitive to consider the possible advantages of prompting with less ambiguous prompt s...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md)


- [Question Answering as Programming for Solving Time-Sensitive Questions](../venues/EMNLP2023/paper_7.md), ([EMNLP2023](../venues/EMNLP2023/README.md))

  - **Abstract**: Question answering plays a pivotal role in human daily life because it involves our acquisition of knowledge about the world. However, due to the dynamic and ever-changing nature of real-world facts, the answer can be completely different when the time constraint in the question changes. Recently, L...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md)


- [Steering Large Language Models between Code Execution and Textual Reasoning](../venues/Microsoft2024/paper_1.md), ([Microsoft2024](../venues/Microsoft2024/README.md))

  - **Abstract**: While a lot of recent research focuses on enhancing the textual reasoning capabilities of Large Language Models (LLMs) by optimizing the multi-agent framework or reasoning chains, several benchmark tasks can be solved with 100% success through direct coding, which is more scalable and avoids the com...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md)


- [When Do Program-of-Thought Works for Reasoning?](../venues/AAAI2024/paper_1.md), ([AAAI2024](../venues/AAAI2024/README.md))

  - **Abstract**: In the realm of embodied artificial intelligence, the reasoning capabilities of Large Language Models (LLMs) play a pivotal role. Although there are effective methods like program-of-thought prompting for LLMs which uses programming language to tackle complex reasoning tasks, the specific impact of ...
  - **Labels**: [prompt strategy](prompt_strategy.md), [reason with code](reason_with_code.md), [empirical study](empirical_study.md)


## Sampling And Ranking

- [Let’s Sample Step by Step: Adaptive-Consistency for Efficient Reasoning and Coding with LLMs](../venues/EMNLP2023/paper_6.md), ([EMNLP2023](../venues/EMNLP2023/README.md))

  - **Abstract**: A popular approach for improving the correctness of output from large language models (LLMs) is Self-Consistency - poll the LLM multiple times and output the most frequent solution. Existing Self-Consistency techniques always generate a constant number of samples per question, where a better approac...
  - **Labels**: [prompt strategy](prompt_strategy.md), [sampling and ranking](sampling_and_ranking.md)


- [Making Language Models Better Reasoners with Step-Aware Verifier](../venues/ACL2023/paper_2.md), ([ACL2023](../venues/ACL2023/README.md))

  - **Abstract**: Few-shot learning is a challenging task that requires language models to generalize from limited examples. Large language models like GPT-3 and PaLM have made impressive progress in this area, but they still face difficulties in reasoning tasks such as GSM8K, a benchmark for arithmetic problems. To ...
  - **Labels**: [prompt strategy](prompt_strategy.md), [sampling and ranking](sampling_and_ranking.md)


- [Ranking llm-generated loop invariants for program verification](../venues/EMNLP2023/paper_13.md), ([EMNLP2023](../venues/EMNLP2023/README.md))

  - **Abstract**: Synthesizing inductive loop invariants is fundamental to automating program verification. In this work, we observe that Large Language Models (such as gpt-3.5 or gpt-4) are capable of synthesizing loop invariants for a class of programs in a 0-shot setting, yet require several samples to generate th...
  - **Labels**: [static analysis](static_analysis.md), [program verification](program_verification.md), [invariant generation](invariant_generation.md), [prompt strategy](prompt_strategy.md), [sampling and ranking](sampling_and_ranking.md)

