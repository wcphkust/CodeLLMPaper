# Statically Contextualizing Large Language Models with Typed Holes

**Authors**: Blinn, Andrew and Li, Xiang and Kim, June Hyung and Omar, Cyrus

**Abstract**:

Large language models (LLMs) have reshaped the landscape of program synthesis. However, contemporary LLM-based code completion systems often hallucinate broken code because they lack appropriate code context, particularly when working with definitions that are neither in the training data nor near the cursor. This paper demonstrates that tighter integration with the type and binding structure of the programming language in use, as exposed by its language server, can help address this contextualization problem in a token-efficient manner. In short, we contend that AIs need IDEs, too! In particular, we integrate LLM code generation into the Hazel live program sketching environment. The Hazel Language Server is able to identify the type and typing context of the hole that the programmer is filling, with Hazel's total syntax and type error correction ensuring that a meaningful program sketch is available whenever the developer requests a completion. This allows the system to prompt the LLM with codebase-wide contextual information that is not lexically local to the cursor, nor necessarily in the same file, but that is likely to be semantically local to the developer's goal. Completions synthesized by the LLM are then iteratively refined via further dialog with the language server, which provides error localization and error messages. To evaluate these techniques, we introduce MVUBench, a dataset of model-view-update (MVU) web applications with accompanying unit tests that have been written from scratch to avoid data contamination, and that can easily be ported to new languages because they do not have large external library dependencies. These applications serve as challenge problems due to their extensive reliance on application-specific data structures. Through an ablation study, we examine the impact of contextualization with type definitions, function headers, and errors messages, individually and in combination. We find that contextualization with type definitions is particularly impactful. After introducing our ideas in the context of Hazel, a low-resource language, we duplicate our techniques and port MVUBench to TypeScript in order to validate the applicability of these methods to higher-resource mainstream languages. Finally, we outline ChatLSP, a conservative extension to the Language Server Protocol (LSP) that language servers can implement to expose capabilities that AI code completion systems of various designs can use to incorporate static context when generating prompts for an LLM.

**Link**: [Read Paper](https://doi.org/10.1145/3689728)

**Labels**: [code generation](../../labels/code_generation.md), [program synthesis](../../labels/program_synthesis.md), [benchmark](../../labels/benchmark.md), [empirical study](../../labels/empirical_study.md)