# How Effective Are Neural Networks for Fixing Security Vulnerabilities

**Authors**: Wu, Yi and Jiang, Nan and Pham, Hung Viet and Lutellier, Thibaud and Davis, Jordan and Tan, Lin and Babkin, Petr and Shah, Sameena

**Abstract**:

Security vulnerability repair is a difficult task that is in dire need of automation. Two groups of techniques have shown promise: (1) large code language models (LLMs) that have been pre-trained on source code for tasks such as code completion, and (2) automated program repair (APR) techniques that use deep learning (DL) models to automatically fix software bugs. This paper is the first to study and compare Java vulnerability repair capabilities of LLMs and DL-based APR models. The contributions include that we (1) apply and evaluate five LLMs (Codex, CodeGen, CodeT5, PLBART and InCoder), four fine-tuned LLMs, and four DL-based APR techniques on two real-world Java vulnerability benchmarks (Vul4J and VJBench), (2) design code transformations to address the training and test data overlapping threat to Codex, (3) create a new Java vulnerability repair benchmark VJBench, and its transformed version VJBench-trans, to better evaluate LLMs and APR techniques, and (4) evaluate LLMs and APR techniques on the transformed vulnerabilities in VJBench-trans. Our findings include that (1) existing LLMs and APR models fix very few Java vulnerabilities. Codex fixes 10.2 (20.4\%), the most number of vulnerabilities. Many of the generated patches are uncompilable patches. (2) Fine-tuning with general APR data improves LLMs’ vulnerability-fixing capabilities. (3) Our new VJBench reveals that LLMs and APR models fail to fix many Common Weakness Enumeration (CWE) types, such as CWE-325 Missing cryptographic step and CWE-444 HTTP request smuggling. (4) Codex still fixes 8.7 transformed vulnerabilities, outperforming all the other LLMs and APR models on transformed vulnerabilities. The results call for innovations to enhance automated Java vulnerability repair such as creating larger vulnerability repair training data, tuning LLMs with such data, and applying code simplification transformation to facilitate vulnerability repair.

**Link**: [Read Paper](https://doi.org/10.1145/3597926.3598135)

**Labels**: [code generation](../../labels/code_generation.md), [program repair](../../labels/program_repair.md), [benchmark](../../labels/benchmark.md)