# BinaryAI: Binary Software Composition Analysis via Intelligent Binary Source Code Matching

**Authors**: Jiang, Ling and An, Junwen and Huang, Huihui and Tang, Qiyi and Nie, Sen and Wu, Shi and Zhang, Yuqun

**Abstract**:

While third-party libraries (TPLs) are extensively reused to enhance productivity during software development, they can also introduce potential security risks such as vulnerability propagation. Software composition analysis (SCA), proposed to identify reused TPLs for reducing such risks, has become an essential procedure within modern DevSecOps. As one of the mainstream SCA techniques, binary-to-source SCA identifies the third-party source projects contained in binary files via binary source code matching, which is a major challenge in reverse engineering since binary and source code exhibit substantial disparities after compilation. The existing binary-to-source SCA techniques leverage basic syntactic features that suffer from redundancy and lack robustness in the large-scale TPL dataset, leading to inevitable false positives and compromised recall. To mitigate these limitations, we introduce BinaryAI, a novel binary-to-source SCA technique with two-phase binary source code matching to capture both syntactic and semantic code features. First, BinaryAI trains a transformer-based model to produce function-level embeddings and obtain similar source functions for each binary function accordingly. Then by applying the link-time locality to facilitate function matching, BinaryAI detects the reused TPLs based on the ratio of matched source functions. Our experimental results demonstrate the superior performance of BinaryAI in terms of binary source code matching and the downstream SCA task. Specifically, our embedding model outperforms the state-of-the-art model CodeCMR, i.e., achieving 22.54\% recall@1 and 0.34 MRR compared with 10.75\% and 0.17 respectively. Additionally, BinaryAI outperforms all existing binary-to-source SCA tools in TPL detection, increasing the precision from 73.36\% to 85.84\% and recall from 59.81\% to 64.98\% compared with the well-recognized commercial SCA product Black Duck.https://www.binaryai.net

**Link**: [Read Paper](https://doi.org/10.1145/3597503.3639100)

**Labels**: [static analysis](../../labels/static_analysis.md), [software composition analysis](../../labels/software_composition_analysis.md), [code model](../../labels/code_model.md), [code model training](../../labels/code_model_training.md), [binary code model](../../labels/binary_code_model.md)